# feature-pancakeswap-v2-liquidity-operations

# 🥞 PancakeSwap V2 Liquidity Management Scripts

A set of JavaScript scripts for interacting with PancakeSwap V2 smart contracts using `ethers.js`. Supports:

- ✅ Adding liquidity to any token pair (token/token)
- ✅ Adding liquidity to token/BNB (addLiquidityETH)
- ✅ Removing liquidity from token/token
- ✅ Removing liquidity from token/BNB (removeLiquidityETH)

---

## 🛠️ Prerequisites

- Node.js (>= 16)
- NPM/Yarn
- `.env` file with the required configuration
- RPC access to BNB Smart Chain (mainnet or testnet)
- Funded wallet (with BNB and tokens)

---

## 📦 Installation

```bash
npm install ethers dotenv
