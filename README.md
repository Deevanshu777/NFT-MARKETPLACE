# 🖼️ NFT Marketplace: Decentralized Digital Asset Exchange

> **Own it. Trade it. Prove it — on-chain.**

[![Next.js](https://img.shields.io/badge/Next.js-12-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![Solidity](https://img.shields.io/badge/Solidity-Smart_Contracts-363636?style=for-the-badge&logo=solidity)](https://soliditylang.org/)
[![Hardhat](https://img.shields.io/badge/Hardhat-Dev_Framework-F7DF1E?style=for-the-badge)](https://hardhat.org/)
[![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-Contracts-4E5EE4?style=for-the-badge)](https://openzeppelin.com/)
[![Web3Modal](https://img.shields.io/badge/Web3Modal-Wallet_Connect-3B99FC?style=for-the-badge)](https://web3modal.com/)

## 📖 Overview

A fully decentralized NFT Marketplace built on Ethereum where creators can mint, list, buy, and sell NFTs without intermediaries. Smart contracts deployed via Hardhat handle all ownership transfers and marketplace logic on-chain, ensuring trustless and transparent transactions.

Users connect their MetaMask wallet, browse the marketplace, and interact directly with the blockchain — no central authority controls their assets.

## ✨ Features

- 🔗 **Wallet Connect** — MetaMask integration via Web3Modal
- 🖼️ **NFT Minting** — Upload and mint digital assets directly from the UI
- 🛒 **Buy & Sell** — List NFTs for sale and purchase from other creators
- 👤 **Creator Profiles** — Author pages with owned and created NFTs
- 🔍 **Search & Filter** — Browse NFTs by name, collection, or creator
- 🏆 **Top Creators** — Leaderboard of most active marketplace participants
- 📦 **Collection Pages** — Grouped NFT collections with detail views
- ⛓️ **On-Chain Logic** — All marketplace transactions handled by Solidity smart contracts

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js 12, React 18, Framer Motion |
| Styling | CSS Modules |
| Smart Contracts | Solidity, OpenZeppelin ERC-721 |
| Blockchain Dev | Hardhat, Hardhat Toolbox |
| Wallet | Web3Modal, Ethers.js |
| Network | Holesky Testnet / Localhost |

## 🚀 Getting Started

### Prerequisites
- Node.js v16+
- MetaMask browser extension
- A funded Holesky testnet wallet (for testnet deployment)

### 1. Clone the Repository
```bash
git clone https://github.com/Deevanshu777/NFT-MARKETPLACE.git
cd NFT-MARKETPLACE
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Environment Variables

Create a `.env` file in the root:
```env
NEXT_PUBLIC_CONTRACT_ADDRESS=your_deployed_contract_address
NEXT_PUBLIC_RPC_URL=your_rpc_url
PRIVATE_KEY=your_wallet_private_key
```

### 4. Run a Local Blockchain Node
```bash
# Terminal 1 — Start local Hardhat node
npm run node
```

### 5. Deploy Smart Contracts
```bash
# Terminal 2 — Deploy to local network
npm run deploy-local

# OR deploy to Holesky testnet
npm run deploy
```

### 6. Run the Frontend
```bash
# Terminal 3
npm run dev
```

Navigate to `http://localhost:3000` and connect your MetaMask wallet.

## 🗺️ Roadmap

- [x] NFT Minting UI
- [x] Smart Contract Deployment via Hardhat
- [x] Wallet Connect with Web3Modal
- [x] Author & Collection Pages
- [x] Search & Top Creators
- [ ] IPFS Integration for Decentralized Media Storage
- [ ] Auction & Bidding System
- [ ] Royalty Support (ERC-2981)
- [ ] Mainnet Deployment

## 🤝 Let's Connect

Built by **Deevanshu Aggarwal** and **Nitish Rai** — CSE student at Bennett University, actively seeking internships in full-stack and Web3 engineering.

- 🔗 **LinkedIn:** [linkedin.com/in/nitish-rai-dev](https://linkedin.com/in/nitish-rai-dev)
- 📧 **Email:** deevanshuaggarwal777@gmail.com  || mailnr7000@gmail.com  

---

> *Trustless by design. Decentralized by default.*
