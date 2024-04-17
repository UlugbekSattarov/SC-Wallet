# SC-Wallet

## Description

SC Wallet is an implementation of an over-collateralized algorithmic stablecoin using Cardano's ADA as collateral

# Installation Instructions

## Setting up Blockfrost

1. **Create a Blockfrost Project:**
   - Navigate to [Blockfrost.io](https://blockfrost.io/) and sign up or log in.
   - Create a new project and copy your Project ID.

2. **Configure Project ID:**
   - Go to the file located at `SC-Wallet/front-back/off-chain/frontend/src/pages/_app.tsx`.
   - Paste your Project ID into the Blockfrost constructor within this file.

## Configuring Nami Wallet

1. **Install Nami Wallet:**
   - Download and install Nami Wallet from its official website or browser extension store.
   - Activate Preview mode in the wallet settings. Ensure you have some ADA in your wallet to handle transactions.

## Running the Frontend

1. **Start the Development Server:**
   - Open your terminal and navigate to the folder `SC-Wallet/front-back/off-chain/frontend/`.
   - Run the following command to start the development server:
     ```bash
     npm run dev
     ```
   - This command will launch the frontend application locally for development and testing.

Follow these steps to set up and run the front-end portion of the SC-Wallet application on your local machine.

