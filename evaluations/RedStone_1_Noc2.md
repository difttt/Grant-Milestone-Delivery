# Evaluation

- **Status:** Accepted
- **Contract Link:** https://github.com/w3f/Grants-Program/blob/master/applications/RedStone%20Network.md
* **Milestone:** 1
* **Kusama Identity:** [HFG4FvoJv8uanizzetS1tPA6wigNAiKuEHKcm1NaKNNDwve](https://polkascan.io/pre/kusama/account/HFG4FvoJv8uanizzetS1tPA6wigNAiKuEHKcm1NaKNNDwve)
* **Previously successfully merged evaluation:** All evaluations by Noc2

| Number | Deliverable | Accepted | Link | Evaluation Notes |
| ------ | ----------- | -------- | ---- |----------------- |
| 0a. | License | <ul><li>[x] </li></ul> | [Apache 2.0](https://github.com/Cumulus2021/cess/blob/main/LICENSE) |  Correct License |
| 0b. | Documentation | <ul><li>[x] </li></ul> | [https://github.com/redstone-network/redstone-node#run-the-rsn-node](https://github.com/redstone-network/redstone-node#run-the-rsn-node) | Basic documentation inside the readme and the pallets  |
| 0c. | Testing Guide | <ul><li>[x] </li></ul> | [https://github.com/redstone-network/redstone-node#run-testnet](https://github.com/redstone-network/redstone-node#run-testnet) | Basic testing guide |
| 0d. | Article/Tutorial | <ul><li>[x] </li></ul> | [https://github.com/redstone-network/redstone-node#module-documentation](https://github.com/redstone-network/redstone-node#module-documentation) | Not really an article, but this is fine, given that the grant is below 10k  |
| 1a. | Substrate module: Defense | <ul><li>[x] </li></ul> | [https://github.com/redstone-network/redstone-node/tree/main/pallets/defense](https://github.com/redstone-network/redstone-node/tree/main/pallets/defense) | Weights are not correct and the formatting seems to be a little bit off, but it's implemented according to the contract |
| 1b. | Substrate module: Notification | <ul><li>[x] </li></ul> | [https://github.com/redstone-network/redstone-node/tree/main/pallets/notification](https://github.com/redstone-network/redstone-node/tree/main/pallets/notification) |  see above  |
| 1c. | Substrate module: Permission-capture | <ul><li>[x] </li></ul> | [https://github.com/redstone-network/redstone-node/tree/main/pallets/permission-capture](https://github.com/redstone-network/redstone-node/tree/main/pallets/permission-capture) |  see above |
| 2. | Docker | <ul><li>[x] </li></ul> | [https://github.com/redstone-network/redstone-node#run-in-docker](https://github.com/redstone-network/redstone-node#run-in-docker) | Works |

## General Notes

Everything immediately worked according to the contract. But external people should keep in mind that these are only the first pallets and it’s far from a decentralized secure storage solution in it's current form. 
