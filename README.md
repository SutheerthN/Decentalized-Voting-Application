# VoltaBlockchain Decentralized Voting Application

A secure, transparent, and tamper-proof decentralized voting system built on **Volta Blockchain**.  
This application ensures that every vote is recorded on-chain, verifiable by anyone, and resistant to manipulation.

## Features

- **Blockchain-Backed Security** – Every vote is stored on the immutable Volta blockchain.
- **Transparency** – Voting data can be publicly verified.
- **Decentralization** – No central authority controls the vote counting.
- **User-Friendly Interface** – Simple and intuitive UI for voters.
- **Smart Contract Driven** – Secure, automated vote handling using Solidity smart contracts.

## ⚙️ Tech Stack

- **Blockchain**: [Volta Blockchain](https://volta.io)
- **Smart Contracts**: Solidity
- **Framework**: Truffle / Hardhat
- **Frontend**: React.js / Web3.js or Ethers.js
- **Wallet**: MetaMask

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/volta-voting-dapp.git
   cd volta-voting-dapp

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Configure Volta Network**

   * In MetaMask, add Volta Blockchain test network.
   * Update `truffle-config.js` or `hardhat.config.js` with your Volta network details.

4. **Compile and deploy smart contracts**

   ```bash
   truffle compile
   truffle migrate --network volta
   ```

5. **Run the frontend**

   ```bash
   npm start
   ```

## 🧪 Running Tests

```bash
truffle test
```

## 📜 Smart Contract Overview

* **Voting.sol** – Manages candidates, voting process, and result tallying.
* **Ownership** – Ensures only authorized users can start/end voting.

## 🔒 Security Considerations

* Uses **modifier-based access control**.
* Protects against double voting.
* Stores all votes immutably on Volta blockchain.

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

💡 *Built for secure, transparent, and democratic decision-making in the Web3 era.*
