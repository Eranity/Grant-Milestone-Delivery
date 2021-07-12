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
| 1. | Analysis of a network's transfer transaction; search for necessary libraries or APIs;determination of transaction preparation logic; writing logic; signing; writing the send logic |...| ...| 
| 2.  |Source code|Detailed links applied below| Source code for blockhain integration on our platform |
| 3.  |Testing| https://www.youtube.com/watch?v=HuQiDl2OQ9s&ab_channel=YerassylMurat| Send transaction demonstration video|

| Task ID | Module name | Description | Link |
| ------ | ----------- | ---- | ----- |
| 1.0 | Handle the account by the private key | Create a Keyring object from user's private key to handle the account | https://github.com/Eranity/citadelpolkadot/blob/main/oneseed-polkadot.ts  |
| 1.1 | Create registry to make RPC calls | Prepare a TypeRegistry with active MetaData for decode extrinsic payload since signing process is offline. | https://github.com/Eranity/citadelpolkadot/blob/main/base.signing-strategy.ts#L47 |
| 1.2 | Generate a signature for requested transaction | Generate a signature by signing the Extrinsic Payload with Keyring which stores private key | https://github.com/Eranity/citadelpolkadot/blob/main/base.signing-strategy.ts#L51 |
| 1.3 | Request the transaction sending | Send the signature to server to get hash of the transaction on blockchain | https://github.com/Eranity/citadelpolkadot/blob/main/base.signing-strategy.ts#L56 |
| 2.0 | Show details of the transaction | Checking availability of transaction in polkascan | https://github.com/Eranity/citadelpolkadot/blob/main/listoftransaction.js |

