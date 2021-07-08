# Milestone Delivery :mailbox:

> ⚡ Only the GitHub account, which is responsible for the pull request of the accepted application is allowed to submit milestones. 
> 
> Don't remove any of the mandatory parts presented in bold letters or as headlines! Lines starting with `>`, such as this one, can be removed.

**The [invoice form :pencil:](https://docs.google.com/forms/d/e/1FAIpQLSfmNYaoCgrxyhzgoKQ0ynQvnNRoTmgApz9NrMp-hd8mhIiO0A/viewform) has been filled out correctly for this milestone and the delivery is according to the official [milestone delivery guidelines](https://github.com/w3f/General-Grants-Program/blob/master/grants/milestone-deliverables-guidelines.md).**  

* **Application Document:** Please, provide a link to the merged contract (the `.md` file in the [applications](https://github.com/w3f/Open-Grants-Program/tree/master/applications) directory). 
* **Milestone Number:** The number of the milestone

> Please provide a list of all deliverables of the milestone extracted from the initial application and a link to the deliverable itself. Ideally all links inside the below table should include a commit hash, which will be used for testing. If you don't provide a commit hash, we will work off the default branch of your repository. Thus, if you plan on continuing work after delivery, we suggest you create a separate branch for either the delivery or your continuing work. 
> 
> If there is anything particular about any of the deliverables we or a future reader should know, use the respective `Notes` column.

| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 1. | Analysis of network's staking transaction, search for necessary libraries or APIs;determination of transaction preparation logic; writing logic; signing; writing the send logic. Polkadot validator list parsing. |Link| ...| 
| 2.  |Source code|[link ](https://gitlab.com/gregory.shabalov/citadel_core/-/blob/dev/imports/iPolkadot.js)| Source code for blockhain integration on our platform |
| 3.  |Testing| [link for testing]| video stake |


| Task ID | Module name | Description | Link |
| ------ | ----------- | ---- | ----- |
| 1.0 | Writing logic for delegation of coins| To get rewards from nodes, delegate and stake coins | [link](RAKW backend code) |
| 1.1 | Implementation of prepared delegation transaction | For the server send necessary information for preparing transaction | [link](https://github.com/Eranity/citadelpolkadot/blob/main/preparestake.js) |
| 1.2 | Signing of delegation transaction | After getting of signing data from server, implement signAndSendTransaction method | [link](https://github.com/Eranity/citadelpolkadot/blob/main/stake.js) |
| 2.0 | Stake nodes | Showing the list of staked nodes, ability to stake new nodes | [link](https://github.com/Eranity/citadelpolkadot/tree/main/stakenodes) |
