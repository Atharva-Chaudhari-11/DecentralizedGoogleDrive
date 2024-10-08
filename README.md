# Decentralized Image Upload and Sharing

This project facilitates decentralized image upload and sharing on the blockchain using Solidity for the smart contract and React for the front-end interface. It enables users to securely upload images to IPFS (InterPlanetary File System) and share access with specified users through smart contract functionality.

## Features

- **Decentralized Storage:** Images are uploaded to IPFS, ensuring decentralized and immutable storage.
- **Smart Contract:** Utilizes Solidity smart contracts on the Ethereum blockchain for access control and ownership management.
- **Access Control:** Users can grant or revoke access to their uploaded images to specific individuals through the smart contract.

## Technologies Used

- **Solidity:** Smart contract development for ownership and access control.
- **React:** Front-end interface for uploading images and managing access.
- **IPFS:** Decentralized storage protocol for hosting uploaded images.

## Usage

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Atharva-Chaudhari-11/DecentralizedGoogleDrive.git

2.Install dependencies for Hardhat   
# Navigate to the root directory
cd Dgdrive3.0
# Install Hardhat dependencies
npm install

3.Compile the smart contract for artifacts:
# Compile Smart Contract
npx hardhat compile
4.Deploy the Solidity smart contract to an Ethereum testnet or local development environment:
# Deploy Smart Contract
npx hardhat run scripts/deploy.js --network <network-name>
5.Install dependencies for the React front end:
# Navigate to the React client directory
cd client 
# Install React dependencies
npm install
6.Run the React application:
# Start React Application
npm start
