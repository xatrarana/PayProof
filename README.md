# 🦾 PayProof – Decentralized Invoice Generator with On-Chain Escrow

> Freelancers get paid *only* after client approval. Clients pay *only* after work is verified. PayProof builds trust using smart contracts, IPFS, and Web3 wallets.

---

## 🔍 Why PayProof?

Freelancing and remote work are booming. But trust is fragile.

* 🎯 **Freelancers worry:** Will the client pay me after I deliver?
* ❓ **Clients worry:** What if the work is incomplete?

**PayProof solves this** using a decentralized smart contract escrow system with proof-of-payment and transparent workflows.

---

## 🚀 Features

* ✅ **Decentralized Invoice Generation**
* 🔐 **Escrow-based smart contract** for secure payment holding
* 🦾 **IPFS storage** for immutable invoice metadata
* 🤩 **NFT receipts (optional)** to prove work history
* 💼 **Wallet login** via MetaMask or WalletConnect
* ⚒️ Built with **Solidity**, **Next.js**, **Tailwind**, and **PostgreSQL**

---

## 🧠 Project Overview

```text
Freelancer → Create Invoice → IPFS Upload
          → Client Locks Payment (Escrow)
          → Freelancer Delivers Work
          → Client Approves → Funds Released
          → (Optional) NFT Receipt Minted
```

---

## 🏗 Tech Stack

| Layer      | Stack                          |
| ---------- | ------------------------------ |
| Frontend   | Next.js, Tailwind CSS          |
| Blockchain | Solidity, Hardhat              |
| Storage    | IPFS via nft.storage           |
| Auth       | Wallet (Metamask) or Clerk     |
| Backend DB | PostgreSQL (Neon) + Prisma     |
| Deployment | Vercel (Frontend), IPFS (Data) |

---


## 🛠 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/xatrarana/PayProof.git
cd PayProof
```

### 2. Install dependencies

Using Bun:

```bash
bun install
```

Using npm:

```bash
npm install
```

### 3. Set up environment variables

```bash
cp .env.example .env
```

Fill in your IPFS token, wallet keys, and DB URLs.

### 4. Run the dev server

```bash
bun run dev
# or
npm run dev
```

---

## 🔐 Smart Contracts

* `InvoiceEscrow.sol`: Secure contract to lock, approve, or refund payments between two parties.

To compile and deploy:

```bash
npx hardhat compile
npx hardhat deploy --network polygonMumbai
```

---

## 🧪 Testing

```bash
npx hardhat test
```

Smart contract tests and frontend logic can be tested via Playwright or Cypress.

---

## 🌍 Live Demo (Coming Soon)

🧪 Testnet: [Polygon Mumbai](https://mumbai.polygonscan.com)
🔗 Frontend: [https://payproof.vercel.app](https://payproof.vercel.app)

---

## 🢑 Contributing

Pull requests are welcome! To contribute:

1. Fork this repo
2. Create a feature branch: `git checkout -b feat/your-feature`
3. Push and open a PR

---

## 📜 License

MIT © 2025 \ Chhatra Rana

---

## 💡 Roadmap (MVP → v2)

* [x] Invoice creation form
* [x] Deploy to testnet
* [x] Basic escrow flow
* [ ] IPFS invoice upload
* [ ] NFT receipt system
* [ ] DAO-based dispute resolution
* [ ] Fiat → crypto bridge

---

## 🔗 Links

* 🧱 [Smart Contract Code](./contracts)
* 👨‍💼 Author: [xatrarana](https://github.com/xatrarana)

---

> Built with ❤️ to empower freelancers & protect client trust using the power of Web3.
