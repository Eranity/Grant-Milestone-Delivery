| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 1. | Transaction and price feed metrics adding | ... | At this stage, we are preparing the relevant data for charts and the network's significant metrics | 
| 2. | Source code | https://github.com/citadeldao/polkadot/blob/main/sourceCode.js | Source code for blockhain integration on our platform |
| 3.  |Testing|  https://github.com/citadeldao/polkadot/blob/main/testing.js | Testing the parser with mocha test|


| Task ID | Module name | Description | Link |
| ------ | ----------- | ---- | ----- |
| 1.0 | Multiple currency rates  | Get currency rates and store them in the database to visualize changes on the charts | https://github.com/citadeldao/polkadot/blob/main/OtherCoins.js  |
| 2.0 | Approximated era duration | We use approximated era duration which is 24 hours to handle the unstaked assets | https://github.com/citadeldao/polkadot/blob/main/eraduration.js |
| 3.0 | Minimum Nominator Bond value | We use minNominatorBond to optimize the transactions and to avoid fails | https://github.com/citadeldao/polkadot/blob/main/minnominatorbondvalue.js |
