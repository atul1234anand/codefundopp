# Decentralised voting system Using Blockchain

**Introduction**

Blockchain has brought in a certain sense of security to technology, giving users an opportunity to execute ledgers while trading ethereum from one user to another. The concept of having ledgers stored in the blockchain, and validated to prevent malicious use of applications can be *extended to create an election and voting application which is completely decentralised*.

User can validate his credentials using a "Unique User Identification id" which in our case is Aadhar, to create an ethereum account with ether.  User can then use this ethereum account to participate in the voting proccess by connecting to the blockchain through the Web App.

**Primary Goals**

- Prevent all forms of malicious voting, by creating ethereum accounts for validated users and preventing duplicate/proxy votes.
- The transactions are monitored by a consensus algorithm and are cryptographically stored across nodes thereby, ensuring that the voters sercurity isn't compromised.
- Providing a phase wise aggregated election result as and when the polls are completed.

**Pre-requisites**

The participating audience needs to have an Aadhar Id, which can be used to validate citizens eligibility to vote.

**Platform**

*Web app*: Responsive nature and can adapt to the device on which its viewed.

**Tech Stack used**:

- React.js: Used to develop the front end facility for the dApp.
- Solidity: Used to develop smart contracts.
- Truffle: Used to migrate, compile and test smart contracts.
- Web3.js: Can be used to connect blockchain to application/web browser and the user will be able to interact with the  blockchain. Also used for creating user accounts.
- Azure Workbench: Used to deploy blockchain.
- Node.js: Used in the installation of various tools using npm.
 
**Reference**

*Conventional Vs Blockchain applications*:

Unlike a conventional application that has a front end, back end and a database that the backend interacts with, the database and the network are created using the blockchain. The blockchain service, comprises of various nodes attached to one another. Each node will consist of a copy of your ledger. The blockchain is written onto using a smart contract. 

<img src="http://www.dappuniversity.com/web_application_diagram.png" width="200" height = "200">

<img src="http://www.dappuniversity.com/dapp_diagram.png" width="200" height = "200">
