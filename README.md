# 🔗 Web3 & Blockchain Basics — Setup Wallet & Explore DApps

An interactive, single-page educational web application that guides learners through blockchain fundamentals, crypto wallet setup, testnet interactions, and decentralized application (DApp) exploration — all in a risk-free environment.

![Vite](https://img.shields.io/badge/Vite-6.0-646CFF?logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES2022-F7DF1E?logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![License](https://img.shields.io/badge/License-Educational-green)

---

## 📖 Overview

This project is a hands-on learning platform designed to teach Web3 and blockchain concepts through interactive content and guided walkthroughs. It covers everything from foundational concepts to performing real testnet transactions, making it ideal for students and beginners entering the decentralized ecosystem.

## ✨ Features

### 🧠 Blockchain & Web3 Fundamentals
- **Interactive flip cards** covering Distributed Ledger Technology, Consensus Mechanisms, Smart Contracts, Gas Fees, Web2 vs Web3, and Cryptographic Principles
- Click-to-reveal explanations with detailed breakdowns and comparisons

### 🦊 MetaMask Wallet Setup Guide
- Step-by-step accordion walkthrough for installing MetaMask
- Wallet creation with seed phrase security best practices
- Sepolia testnet configuration with network details (Chain ID, RPC, Block Explorer)

### 💧 Testnet ETH & Faucets
- Links to multiple Sepolia faucets (Google Cloud, Alchemy, Infura, PoW Faucet)
- Instructions for copying wallet addresses and verifying transactions
- Detailed transaction anatomy breakdown on Etherscan

### 🦄 DApp Interaction Guides
- **Uniswap (DEX)** — Token swap walkthrough on Sepolia testnet
- **OpenSea (NFT Marketplace)** — Browse and understand NFTs on testnet
- Tabbed interface for easy switching between DApp guides
- Visual transaction lifecycle flowchart (Initiate → Sign → Pending → Validate → Confirmed)

### 🔍 Block Explorer Education
- Simulated Etherscan transaction view with labeled fields
- Guide to reading transaction hashes, gas fees, status, and block numbers
- Tips for what to capture for submission

### 🔐 Security Best Practices
- Severity-rated security cards (Critical / High / Medium)
- Covers seed phrase protection, phishing prevention, transaction verification, and general safety

### 📄 Submission Document Generator
- Built-in form to collect all assignment deliverables
- Generates a formatted submission document with:
  - Personal & wallet information
  - Transaction hashes and Etherscan links
  - Screenshot checklist
  - Written reflection (with live word counter: 300–500 words)
- **Copy to Clipboard** and **Print / Save as PDF** functionality

### 🎨 UI/UX Features
- Responsive design with mobile navigation (hamburger menu)
- Scroll-based animations with Intersection Observer
- Sticky navigation with active section highlighting
- Smooth scrolling and scroll-to-top button
- Glassmorphism cards and gradient text effects
- Google Fonts (Inter, JetBrains Mono)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic page structure |
| **CSS3** | Custom styling, animations, responsive layout |
| **Vanilla JavaScript** | Interactivity, DOM manipulation, form handling |
| **Vite 6** | Dev server & production bundler |
| **Google Fonts** | Inter (UI) + JetBrains Mono (code) |

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- npm (comes with Node.js)

### Installation

```bash
# Clone the repository
git clone https://github.com/raghavendra2006/-Setup-Wallet-and-Explore-DApps.git
cd -Setup-Wallet-and-Explore-DApps

# Install dependencies
npm install
```

### Development

```bash
# Start the dev server (opens at http://localhost:5173)
npm run dev
```

### Production Build

```bash
# Build for production
npm run build

# Preview the production build
npm run preview
```

---

## 📁 Project Structure

```
-Setup-Wallet-and-Explore-DApps/
├── index.html          # Main HTML — all sections and content
├── style.css           # Complete stylesheet (36KB) — layout, animations, themes
├── main.js             # JavaScript — navigation, flip cards, accordions, form logic, doc generator
├── vite.config.js      # Vite configuration (port 5173, auto-open)
├── package.json        # Project metadata & scripts
├── .gitignore          # Ignored files (node_modules, dist)
└── dist/               # Production build output (generated)
```

---

## 📚 Sections Breakdown

| # | Section | Description |
|---|---------|-------------|
| 01 | **Concepts** | Interactive flip cards on blockchain fundamentals |
| 02 | **Wallet Setup** | MetaMask installation & configuration guide |
| 03 | **Testnet ETH** | Faucet links & balance verification steps |
| 04 | **DApp Interaction** | Uniswap & OpenSea guided walkthroughs |
| 05 | **Block Explorer** | Reading Etherscan transaction data |
| 06 | **Security** | Best practices for Web3 safety |
| 07 | **Submission** | Document generator with print/export |

---

## 🌐 External Resources Used

- [MetaMask](https://metamask.io/) — Ethereum wallet browser extension
- [Sepolia Etherscan](https://sepolia.etherscan.io/) — Testnet block explorer
- [Uniswap](https://app.uniswap.org/) — Decentralized exchange
- [OpenSea Testnets](https://testnets.opensea.io/) — NFT marketplace (testnet)
- [Google Cloud Faucet](https://cloud.google.com/application/web3/faucet/ethereum/sepolia) — Sepolia ETH faucet
- [Alchemy Faucet](https://www.alchemy.com/faucets/ethereum-sepolia) — Sepolia ETH faucet
- [Infura Faucet](https://www.infura.io/faucet/sepolia) — Sepolia ETH faucet

---

## ⚠️ Disclaimer

This project is for **educational purposes only**. It is **not financial advice**. All interactions demonstrated use **testnet tokens** with no real-world monetary value. Never share your seed phrase or private keys with anyone.
