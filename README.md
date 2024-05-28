# Nuxt.js 2 + Web3.js + Metamask Starter Kit 🦊

This project is a proof-of-concept (POC) that demonstrates how to build a simple decentralized application (dApp) using Nuxt.js 2, Web3.js, and Metamask for interacting with the Tron blockchain.

![Homepage](/images/homepage.png)

## Features 🚀

- **Metamask Connection:** Connect users' Metamask wallets to your dApp.
- **TRC20 Token Deposits:** Deposit TRC20 tokens (e.g., USDT) onto the Tron blockchain.

## Prerequisites 🛠️

- Node.js v13+
- Metamask browser extension installed

## Getting Started 🎬

1. **Clone the Repository:**

   ```bash
   git clone git@github.com:canhta/nuxt2-web3.git
   ```

2. **Install Dependencies:**

   ```bash
   cd nuxt2-web3
   npm install
   ```

3. **Configure Environment:**

   - Create a `.env` file in the root of the project.
   - Add your TRC20 token contract address and ABI (Application Binary Interface):
     ```
     USDT_CONTRACT_ADDRESS=your_usdt_contract_address
     USDT_CONTRACT_ABI=your_usdt_contract_abi
     ```
   - Make sure Metamask is set to connect to the Tron network.

4. **Start Development Server:**
   ```bash
   npm run dev
   ```

## Acknowledgements 🙏

- [web3.js](https://web3js.readthedocs.io/)
- [Metamask](https://metamask.io/)
- [Tron](https://tron.network/)
