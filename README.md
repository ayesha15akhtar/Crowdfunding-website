
# Crowd Funding Platform with Block-Chain Transactions

## Deployment

To deploy this project, follow the following. -

Below are the steps to create a `.env` file, install dependencies, deploy a smart contract, and update the contract address.

#### Create a `.env` file:

1. In your project's web3 directory, create a new file named `.env.`

2. Add your MetaMask private key to this file in the following format:

   ```
   PRIVATE_KEY=YOUR_METAMASK_PRIVATE_KEY
   ```

   Replace `YOUR_METAMASK_PRIVATE_KEY` with your actual private key. Make sure to keep this file secure and never share it publicly.

#### Install Dependencies:

After creating the `.env` file, follow these steps to install dependencies and deploy the smart contract.

1. Navigate to the `client` directory and the `web3` directory using the command line.

   ```bash
   cd client
   ```

   ```bash
   cd web3
   ```

2. In both the `client` and `web3` directories, run the following command to install the necessary dependencies:

   ```bash
   npm install
   ```

#### Deploy the Smart Contract:

1. In the `web3` directory, run the following command to deploy the smart contract:

   ```bash
   npm run deploy
   ```

   Ensure your MetaMask private key is correctly configured in the `.env` file to sign the deployment transaction.

   Follow the link that appears in the terminal and deploy the contract in the desired network. (Polygon or Ethereum).
   
   My contract deployment link is as follows:
   https://thirdweb.com/mumbai/0xDDd1DBb6B42Bb30ac97eBf8aa6c19Cd914E13B07/explorer

   The deployment process will provide you with the contract address once it's successfully deployed.

#### Update the Contract Address:

Once the smart contract is deployed and you have the contract address:

1. Open the `client` directory.

2. Locate the relevant file where the contract address is being used (e.g., in a JavaScript file). You can find that [here](https://github.com/ayesha15akhtar/Crowdfunding-website/blob/main/client/src/context/index.jsx)

3. Update the contract address in the file with the address of the deployed smart contract on the third web.
   https://github.com/ayesha15akhtar/Crowdfunding-website/blob/main/client/src/context/index.jsx


