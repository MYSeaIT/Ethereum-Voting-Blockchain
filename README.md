# Ethereum Voting Blockchain

## Overview
This project is an Ethereum Smart Contract Voting System based on Blockchain. It aims to provide a decentralized and secure platform for conducting voting processes using Ethereum blockchain technology.

## Installation
To run the project, follow these steps:
1. Clone the repository to your local machine.
2. Install Node.js and npm if not already installed.
3. Install the necessary dependencies by running `npm install` in the project directory.

## Usage
To run the application, follow these steps:
1. Deploy the Ethereum Smart Contract `Voting.sol` to your local Ethereum network or testnet.
2. Update the contract address in the `index.js` file to reflect the deployed contract address.
3. Open the `index.html` file in a web browser to interact with the voting interface.

## Troubleshooting and Error Resolution
### Error: ReferenceError - Web3 is not defined
- Description: This error occurred in the `index.js` file when attempting to create an instance of `Web3` without importing it.
- Resolution: 
  - Installed the Web3.js library via npm by running `npm install web3`.
  - Added the code `const Web3 = require('web3');` at the top of the `index.js` file to import the Web3 library.

### Other Errors Encountered
- If there were any other errors encountered during the setup or execution of the project, provide a detailed description of the error, its cause, and the specific steps taken to resolve it.


