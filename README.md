# Blockchain-Store


Description
A decentralized application built with Solidity for Ethereum Blockchain. It privides access to Blockchain bookstore where educational, informative and helpful materials can be purchased and rent.
This application has been built as final project during the Consensys Developer Bootcamp It's composed of several smart contracts and a web application.

Follow the steps in order to run it on your local machine

Initial setup with Node Packet Manager(NPM):
Install Node.js v8+ LTS and npm
Install Truffle
truffle unbox pet-shop
Install GanacheCLI
Install Metamask on web browser


Clone the Blockchain-Store Repo into your local machine

Move into the directory which is "blockchain-store" 

run "npm install" to install the nesessary dependencies

"npm start" to start the local server


Setting up local blockchain Development environment:

Install ganache GUI in your local computer 

Start ganache: ganache-cli

Accounts comes with pre-funded accounts.

Setting up metamask to sign transactions:

Install metamask extention for your web browser

Set up the metamask by entering the seed phrase which is available in ganache GUI accounts section and enter password of your own

Now Import the pre funded accounts from ganache to metamask by entering the private keys
On top of the metamask extention you will see Network section, go to network to setup custom network
In network section at the botton you shell see custom RPC click on it and enter the NETWORK NAME of you choice and NETWORK URL is http://127.0.0.1:7545 which is RPC Server address from ganache
Save the changes
Compiling and Migrating Smart contracts:

Run "truffle compile" to compile contracts
Run "truffle migrate" to migrate contracts
Note down the contract address which is produced under 3_deploy_contract.js after the compilation
Go to the project home page on your web browser enter the contract address
Now you shell be taken to campaign page which provides details about the contract and allows user to contibute in ether
Enter your contibutions and press the button
Now metamask will prompt for your permission/signature to approve transaction
Once you conform the transaction it would be recorded into local ganache blockchain network
Now the conteract state is updated on campaign page
Note: If you see campaign is expired then just restart the ganache server and run "truffle migrate" command



Thanks a lot!!

