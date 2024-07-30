# dApp Chat Application

Welcome to the dApp Chat Application! This decentralized application (dApp) allows users to communicate securely using blockchain technology. The app leverages Ethereum smart contracts to ensure privacy and security in messaging.

#Table of Contents
-Introduction
-Features
-Prerequisites
-Installation
-Usage
-Contributing
-License

# Introduction

This dApp Chat Application is a decentralized platform that enables users to chat privately and securely. It uses Ethereum smart contracts to handle user authentication and message storage, ensuring that all communications are encrypted and tamper-proof.

# Features

Decentralized Messaging: Messages are stored on the blockchain, ensuring privacy and security.
Secure Authentication: Users log in using their MetaMask wallets, providing a secure and seamless authentication process.
End-to-End Encryption: All communications are encrypted, protecting user data.
Open Source: The project is open source, allowing for community contributions and transparency.
#Prerequisites
Before setting up the project, ensure you have the following:

Node.js (v14.x or later)
MetaMask browser extension
Hardhat (for local blockchain development)

# Installation

Follow these steps to set up the project locally:

1. Clone the Repository
   bash
   git clone https://github.com/your-username/dapp-chat-application.git
   cd dapp-chat-application
2. Install Dependencies
   Install the necessary Node.js packages:

npm install

3. Set Up MetaMask
   (i) Install the MetaMask browser extension.
   (ii) Create a new wallet or import an existing one.
   (iii) Save your seed phrase securely. 4. Start the Local Blockchain
   Launch a local Ethereum network using Hardhat:

npx hardhat node
This will start a local blockchain and provide accounts for testing.

5. Deploy Smart Contracts
   Deploy the smart contracts to the local blockchain:

npx hardhat run --network localhost scripts/deploy.js

6. Start the Application
   Run the development server:

npm run dev
The application will be available at http://localhost:3000.

7. Connect MetaMask to Localhost
   (i)Open MetaMask and switch to the "Localhost 8545" network.
   (ii)Import an account using the private key provided by Hardhat. You can find these keys in the terminal where the local blockchain is running.

# Usage

Once set up, users can:

- Log In: Authenticate using their MetaMask wallet.
- Send Messages: Securely send and receive messages.
- Manage Profile: Update their profile and view other users.

# Contributing

We welcome contributions from the community! To contribute:

(i) Fork the repository.
(ii)Create a new branch (git checkout -b feature/your-feature).
(iii)Make your changes and commit them (git commit -m 'Add new feature').
(iv)Push to the branch (git push origin feature/your-feature).
(v)Open a Pull Request.
Please adhere to the project's code of conduct and follow the contribution guidelines.
