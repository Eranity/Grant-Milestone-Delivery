| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 1. | Performing different types of testing. Verification of the main scenarios such as sending tokens, and staking in the various environments including Ledger and Trezor wallets. | Detailed links applied below | ...| 


| Task ID | Module name | Description | Link |
| ------ | ----------- | ---- | ----- |
| 1.0 | Testing of block details by number | Parse extrinsics and events of block, test for correct different types of transaction properties | https://gitlab.com/gregory.shabalov/citadel_core/-/blob/dev/test/connectors/polkadot/getOneBlock.js#L12|
| 2.0 | Test every type of transaction | Manually testing of different transactions on the platform | --- |
| 2.1 | Test transfer | Transfering some balance to the new and elderly another addresses to check if it is possible to avoid the error of the case "an account liquidity restrictions prevent withdrawal" | --- |
| 2.2 | Test stake and nominate | To check if it is possible to stake and nominate once, since nominating is possible only if the amount to bond or active bonded amount is more than minNominatorBond. | --- |
| 3.0 | Test list of validators | Check if all active validators at current era appears with identity name | --- |
| 4.0 | Test address balances | Check if all balances of the address are correctly appeared on the platform | --- |
| 5.0 | Test sent transaction hash | Check if hash of the transaction sent on the platform to blockchain is correct on scanners | --- |




