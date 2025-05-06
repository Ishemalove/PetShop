# 🐾 Online Pet Shop DApp

Welcome to the **Decentralized Pet Shop** project! This is a blockchain-powered application built with **Truffle**, **Ganache**, and **MetaMask** that allows users to adopt pets through smart contracts deployed on a local Ethereum network.

---

## 🚀 Project Overview

This project is a simple yet powerful demonstration of how decentralized applications (DApps) work. Users can connect their MetaMask wallets and adopt pets using Ethereum smart contracts.

### Features:

* Connect to MetaMask
* Adopt pets through a smart contract
* View adoption status for each pet
* Uses local Ethereum blockchain with Ganache

---

## 🛠️ Technologies Used

* **Solidity** — Smart contract development
* **Truffle** — Framework for testing and deploying contracts
* **Ganache** — Personal local Ethereum blockchain for development
* **MetaMask** — Wallet and Ethereum identity provider
* **JavaScript / Web3.js** — Frontend interaction with smart contracts
* **HTML/CSS** — User Interface

---

## 📦 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/pet-shop-dapp.git
cd pet-shop-dapp
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start Ganache

Open Ganache and create a new workspace or use the quickstart Ethereum blockchain.

### 4. Compile and Migrate Contracts

```bash
truffle compile
truffle migrate
```

### 5. Run Tests

```bash
truffle test
```

### 6. Launch the frontend

```bash
npm run dev
```

---

## 🔗 Connect MetaMask

1. Open MetaMask extension
2. Add a new network with the following info:

   * Network Name: Ganache
   * RPC URL: [http://127.0.0.1:7545](http://127.0.0.1:7545)
   * Chain ID: 1337
3. Import an account using the private key from Ganache

---

## 🤖 Smart Contract

Located in `contracts/Adoption.sol`. This contract handles the adoption logic and stores adopter addresses for each pet.

---

## 🧪 Testing

Smart contract unit tests are written using Truffle in JavaScript:

```js
assert.equal(adopter, expectedAdopter, "The owner of the adopted pet should be the correct account.");
```

Test files are located in the `/test` directory.

---

## ❤️ Credits

* Truffle Suite Team
* Ethereum Foundation
* MetaMask Team
* \[Your Name Here 💖]

---

Happy coding and happy adopting! 🐕🐈💻✨
