# Milestone Delivery :mailbox:

> ⚡ Only the GitHub account, which is responsible for the pull request of the accepted application is allowed to submit milestones. 
> 
> Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with `>`, such as this one, can be removed.

**The [invoice form :pencil:](https://docs.google.com/forms/d/e/1FAIpQLSfmNYaoCgrxyhzgoKQ0ynQvnNRoTmgApz9NrMp-hd8mhIiO0A/viewform) has been filled out correctly for this milestone and the delivery is according to the official [milestone delivery guidelines](https://github.com/w3f/General-Grants-Program/blob/master/grants/milestone-deliverables-guidelines.md).**  

* **PR Link:** https://github.com/w3f/Open-Grants-Program/pull/81
* **Milestone Number:** 6

> Please provide a list of all deliverables of the milestone extracted from the initial application and a link to the deliverable itself. Ideally all links inside the below table should include a commit hash, which will be used for testing. If you don't provide a commit hash, we will work off the default branch of your repository. Thus, if you plan on continuing work after delivery, we suggest you create a separate branch for either the delivery or your continuing work. 
> 
> If there is anything particular about any of the deliverables we or a future reader should know, use the respective `Notes` column.

| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 1. | Analysis of network's staking transaction, search for necessary libraries or APIs;determination of transaction preparation logic; writing logic; signing; writing the send logic. Polkadot validator list parsing. | Detailed links applied below | ...| 
| 2.  |Testing| https://youtu.be/BcE-KQgXV5k | Polkadot stake nodes demonstration video |


| Task ID | Module name | Description | Link |
| ------ | ----------- | ---- | ----- |
| 1.0 | Implementation of properties to build nomination and staking transaction | Collecting properties and request the builded transaction | https://github.com/Eranity/citadelpolkadot/blob/main/preparestake.js |
| 1.1 | Strategy of nominating and staking| Stake and nominate validators to earn rewards | https://github.com/Eranity/citadelpolkadot/blob/main/polkadot.js#L381 |
| 1.2 | Strategy of signing the nominating and staking transaction | Generate the signature for builded transaction with users private key | https://github.com/Eranity/citadelpolkadot/blob/main/stake.js |
| 2.0 | Nominated validators | Show the list of nominated and active validators on current era | https://github.com/Eranity/citadelpolkadot/tree/main/stakenodes |
