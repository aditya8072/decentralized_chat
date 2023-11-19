# Chat App with Blockchain Integration

This repository contains a simple chat application built using Ethereum smart contracts for message storage and retrieval. Users can send messages to each other by interacting with the Ethereum blockchain.

## Smart Contract - `Chat.sol`

### Description
The smart contract `Chat.sol` is written in Solidity and facilitates the sending of messages between users. It emits an event whenever a message is sent.

### Functions
- `sendMessage`: Allows users to send messages to each other. Emits a `message` event.

### Events
- `message`: Triggered when a message is sent, capturing details such as sender, recipient, message content, and timestamp.

## Web Interface - HTML, CSS, Bootstrap, and JavaScript

### Files
1. `index.html`: Login form for users to enter their Ethereum address and password.
2. `account.html`: Dashboard for logged-in users to view and send messages.

### Dependencies
- Bootstrap v5.2.0
- jQuery v3.5.1
- Popper.js v1.16.0
- Font Awesome v4.7.0
- Web3.js v1.7.4

### Features
- User authentication using Ethereum address.
- Integration with the Ethereum blockchain for message storage.
- Logout functionality.

### Usage
1. Open `index.html` in a web browser.
2. Enter your Ethereum address and password to log in.
3. Upon successful login, you will be redirected to `account.html`.
4. View and send messages to other users.
5. Logout using the provided button.

### Note
- Make sure you have an Ethereum address and password to use the application.
- The application assumes the use of a local Ethereum node with RPC endpoint at `http://127.0.0.1:7545`.
- Ensure that MetaMask or a similar Ethereum wallet is connected to the local node.

## Smart Contract Deployment
1. Deploy the `Payment` contract to your Ethereum network.
2. Update the contract address in `account.html` under the `contractAddress` variable.

## Local Development
- For local development, run the HTML files on a local server (e.g., using VS Code Live Server).

## License
This project is licensed under the GNU General Public License v3.0.
