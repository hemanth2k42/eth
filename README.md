# Smart Contract Management Project: Function Frontend

## Overview

This project involves creating a simple smart contract with 2-3 functions and developing a frontend application to interact with it. The frontend will connect to MetaMask and include functions to change a name and transfer an amount from MetaMask to the contract.

## Requirements

- Node.js and npm
- Solidity ^0.8.9
- MetaMask
- Visual Studio Code (VSCode)
- React.js


## Deployment using VS Code

1. **Set Up the Environment**:
   - Open Visual Studio Code.
   - Install the Solidity extension.
   - Create a new directory for your project.
   - Inside the project directory, create a file named `SimpleContract.sol` and paste the contract code into it.

2. **Initialize Hardhat**:
   - Open a terminal in VS Code.
   - Run the following commands to initialize a Hardhat project:

   - Follow the prompts to create a basic sample project.

3. **Configure Hardhat**:
   - Open the `hardhat.config.js` file and configure it to use the Ethereum network. Here is an example configuration:

4. **Deploy the Contract**:
   - Create a new file in the `scripts` directory named `deploy.js` and add the deployment script:
    
5. **Save the Contract Address**:
   - Note the deployed contract address from the console output. You will need this address for the frontend application.

## Frontend Application

### Project Setup

1. **Initialize a React Project**:

2. **Install Dependencies**:


### Running the Frontend

1. **Start the React Application**:

2. **Open the Application**:
   - Open your browser and go to `http://localhost:3000`.
   - Connect your MetaMask wallet.
   - You should see the current name and contract balance.
   - Use the input fields and buttons to set a new name and deposit ETH.

## MetaMask Configuration

1. **Add Ethereum Network**:
   - Open MetaMask.
   - Ensure you are connected to the Ethereum mainnet or a testnet like Ropsten, Rinkeby, or Goerli.

2. **Add SimpleContract to MetaMask**:
   - Open MetaMask.
   - Click on "Assets" and then "Add Token".
   - Select "Custom Token" and enter the SimpleContract address.


## License

This project is licensed under the MIT License - see the LICENSE file for details.
