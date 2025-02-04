# Milestone Delivery :mailbox:

> ⚡ Only the GitHub account, which is responsible for the pull request of the accepted application is allowed to submit milestones. 
> 
> Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with `>`, such as this one, can be removed.

**The [invoice form :pencil:](https://docs.google.com/forms/d/e/1FAIpQLSfmNYaoCgrxyhzgoKQ0ynQvnNRoTmgApz9NrMp-hd8mhIiO0A/viewform) has been filled out correctly for this milestone and the delivery is according to the official [milestone delivery guidelines](https://github.com/w3f/General-Grants-Program/blob/master/grants/milestone-deliverables-guidelines.md).**  

* **PR Link:** https://github.com/w3f/Open-Grants-Program/pull/81
* **Milestone Number:** 4

> Please provide a list of all deliverables of the milestone extracted from the initial application and a link to the deliverable itself. Ideally all links inside the below table should include a commit hash, which will be used for testing. If you don't provide a commit hash, we will work off the default branch of your repository. Thus, if you plan on continuing work after delivery, we suggest you create a separate branch for either the delivery or your continuing work. 
> 
> If there is anything particular about any of the deliverables we or a future reader should know, use the respective `Notes` column.

| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 1. | Examination of Polkadot transfer methods and staking system| ... | This is the building step of transactions with requested properties such as: transfer and stake | 
| 2.  |Source code| https://github.com/Eranity/citadelpolkadot/blob/main/sourceCode.js | Source code for building transactions |



| Task ID | Module name | Description | Link |
| ------ | ----------- | ---- | ----- |
| 1.0 | Build transactions | Create unsigned transaction with requested properties| https://github.com/Eranity/citadelpolkadot/blob/main/polkadot.js |
| 1.1 | Build transfers | Create unsigned transaction for transferring balances | https://github.com/Eranity/citadelpolkadot/blob/main/polkadot.js#L362 |
| 1.1.0 | Build transfer | Create transaction for transferring some liquid free balance to another account | https://github.com/Eranity/citadelpolkadot/blob/main/polkadot.js#L362 |
| 1.1.1 | Build transferKeepAlive | Create transaction for transferring balance, but with a check that a transfer will not kill the origin account | https://github.com/Eranity/citadelpolkadot/blob/main/polkadot.js#L362 |
| 1.2 | Build staking | Create unsigned transaction for staking balances | https://github.com/Eranity/citadelpolkadot/blob/main/polkadot.js#L406 |
| 1.2.0 | Build bond | Create transactions for bonding balances, including a stash account where rewards will drip | https://github.com/Eranity/citadelpolkadot/blob/main/polkadot.js#L406 |
| 1.2.1 | Build bondExtra | Create transactions for adding balances to the bonded ones | https://github.com/Eranity/citadelpolkadot/blob/main/polkadot.js#L406 |
| 2.0 | Create payload | Create a signer payload for builded transaction | https://github.com/Eranity/citadelpolkadot/blob/main/payload.js |
| 2.1 | Insert properties to payload | Insert necessary properties such tip, transactionVersion, genesisHash, blockHash, runtimeVersion, account nonce, extrinsicVersion | https://github.com/Eranity/citadelpolkadot/blob/main/payload.js |
| 3.0 | Evaluate fees for transactions | Get the fee for builded transaction| https://github.com/Eranity/citadelpolkadot/blob/main/evaluateFee.js |

