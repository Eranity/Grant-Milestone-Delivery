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
| 1. | Polkadot blockchain scrutiny, data transfer to PostgreSQL (for data aggregation and statistics building)|Link| This step will bring us some vital milestones: our database will contain all the transactions - new ones sourced directly from the blockchain will be also stored in our database that is convenient for the development needs (balance/rewards charts creation, etc.)| 
| 2.  |Source code|(https://github.com/Eranity/citadelpolkadot/blob/main/sourceCode.js)| Source code for blockhain integration on our platform |
| 3.  |Testing| [link for testing](https://github.com/Eranity/citadelpolkadot/tree/main)| Testing the parser with mocha test|


| Task ID | Module name | Description | Link |
| ------ | ----------- | ---- | ----- |
| 1.0 | Parsing transactions| Download all blocks with transactions to our database | link  |
| 2.0 | Connector with methods: (isSystemAddress, validateAddress, getLastBlock, getOneBlock, filterOperations, getDelegationBalanceInfo) | methods for processing a transactions | link |
| 3.0 | Download the list of validators | Downloading the validators list for staking. This process done by automated script. | link |
| 3.1 | List of validators by address | Get the list of validators by address who is nominated| link |
| 4.0 | Currency exchange data and market caps | Download, update and store currency exchange data and the market caps |link |
