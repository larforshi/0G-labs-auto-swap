# 0G Labs Auto Swap Bot (Jaine App)

Bot automates token swaps on the 0G Labs network, designed specifically to interact with [Jaine App](https://test.jaine.app/) and push transactions on-chain to maximize airdrop participation.

<img width="1515" height="823" alt="image" src="https://github.com/user-attachments/assets/06b88e85-a244-4ab7-a2b2-5066edb36c0a" />

## 🎯 Purpose

This script performs randomized token swaps between:

- **BTC → USDT**
- **BTC → ETH**

It simulates organic, human-like usage activity across multiple wallets, helping farm potential **airdrop points** on the Jaine platform — which rewards active users.

## ⚙️ Features

- 🔁 Daily automated swaps (34–56 tx daily)
- 🔄 Random swap types (BTC → USDT or BTC → ETH)
- 🎲 Random amount per swap (0.000001 – 0.00001 BTC)
- ⏱️ Random delay between swaps (3–12 minutes)
- 👥 Supports **multi-wallet** operation via `.env`
- ✅ Automatically checks & sends `approve()` if needed

## 📦 Installation

### 1. Clone this repository:
```bash
git clone https://github.com/larforshi/0G-labs-auto-swap.git
```
```bash
cd 0G-labs-auto-swap
```
### 2. Install dependencies:
```bash
npm install
```
### 3. Create a .env file:
```bash
nano .env
```
Input your privatekey
```bash
ACCOUNT_1_ADDRESS=0xYourAddressHere
ACCOUNT_1_PRIVATE_KEY=0xYourPrivateKeyHere

ACCOUNT_2_ADDRESS=0xAnotherAddress
ACCOUNT_2_PRIVATE_KEY=0xAnotherPrivateKey
```
You can add as many accounts as needed (ACCOUNT_3_..., etc).

### 4 Running the Bot
To run the script:
```bash
node index.js
```

- It starts immediately, performs 34–56 swaps for the day, then sleeps for 24 hours.

- Each transaction is pushed on-chain via 0G RPC and targets the Jaine App router contract.

- You will see printed logs for each swap, including transaction hash, token direction, and block number.

## 📌 About Jaine App
Jaine is a testnet DeFi protocol on 0G Labs, currently tracking swap activity and interaction frequency.
This bot helps simulate real usage to accumulate airdrop eligibility.

## ⚠️ Notes
- Ensure your test wallets are funded with test BTC, USDT, ETH on 0G Labs.
- This is for testnet and airdrop farming purposes only.
  
# 
#0GLabs #JaineApp #AirdropHunter #AirdropFarming #TestnetFarming #DeFiBot 
#PythonDeFi #AutoSwap #WalletAutomation #OnchainActivity #Web3Tools 
#CryptoAutomation #EthereumBot #DeFiTestnet #FarmingBot
