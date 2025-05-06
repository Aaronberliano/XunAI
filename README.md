# Xun AI 

**Decentralized Infrastructure for AI Agents on Solana**

Welcome to the official repository of **Xun AI**, a decentralized infrastructure platform designed for Solana developers aiming to integrate AI agents and reliable data feeds into their dApps.

![XunAI](assets/XunAI.png)

Xun AI is powered by the advanced capabilities of **Qwen3**, a hybrid, multilingual Mixture-of-Experts (MoE) model. It combines high-speed execution, ultra-low transaction costs, and state-of-the-art AI to unlock new possibilities for Web3 applications.

---

## Introduction

Xun AI provides a decentralized GPU/CPU compute marketplace and AI-driven oracle network for Solana developers. Use it to integrate AI-validated data into your smart contracts or run agents directly on-chain.

### Origins
The name "Xun" is derived from the Chinese character 询 (xún), meaning "to inquire". This philosophy is at the heart of the project: delivering reliable, intelligent responses through decentralized AI infrastructure.

---

## Prerequisites

- A Solana wallet (Phantom, Solflare, etc.)
- Node.js v14+ (v16+ recommended)
- Rust v1.60+ (v1.70+ recommended)
- Solana CLI v1.10+ (v1.16+ recommended)
- $XUN tokens (acquired through staking or devnet faucet)

### Devnet Tokens
For testing purposes, request $XUN test tokens via our **faucet** or join the **developer Discord**.

---

## Use Cases

- **AI Trading Bots**: Strategies using sentiment and price prediction data
- **Sentiment-Aware DeFi**: Lending, insurance, and DAO governance based on live AI sentiment
- **Dynamic NFTs**: That evolve based on on-chain or off-chain events
- **Predictive Dashboards**: For tokens, protocols, and broader crypto market trends
- **AI-Augmented Games**: With intelligent agents and dynamic economies

### Emerging Use Cases:
- **Smart DAOs**: Automated governance, AI-based recommendations
- **Autonomous AI Agents**: Interacting with the blockchain natively

---

## Platform Architecture

1. **Core Infrastructure**: Built on Solana for 700K TPS and sub-cent fees
2. **Decentralized Network**: Of compute nodes and oracle validators
3. **Qwen3 MoE Model**: For optimized, cost-effective compute allocation
4. **Developer SDK/API**: With support for JS, Python, and Rust

---

## SDK Configuration Example

```ts
const config = {
  endpoint: 'https://api.xun.ai/',
  wallet: myWalletInstance,
  apiKey: 'YOUR_API_KEY',
  network: 'mainnet-beta',
  timeout: 30000
};
```

> You can authenticate using either your wallet (for client-side apps) or an API key (for server-side).

---

## Compute Marketplace

- **Tasks**: Define, submit via Solana smart contracts, monitor, and cancel
- **Monitoring**: List, cancel, and track task states (pending → running → completed)
- **Results**: Stored for 7 days post-completion
- **Models Supported**:
  - `qwen3-7b` (fast, for basic tasks)
  - `qwen3-30b-a3b` (cost/performance balance)
  - `qwen3-72b` (advanced reasoning, 128K context)

### Example Task Types
- Price prediction for BTC
- Sentiment analysis on $SOL mentions
- News feed summarization

### Task Priorities

| Priority | Cost Modifier | Queue Position     |
|----------|----------------|---------------------|
| High     | +50%           | Front of the queue  |
| Normal   | +0%            | Middle              |
| Low      | -25%           | Back of the queue   |

---

## Oracle Network

### Data Feeds
- Sentiment analysis (social + news)
- Price forecasting
- Crypto news analysis
- Cross-chain metrics and comparisons

### How It Works
1. **Data Collection**: By distributed nodes
2. **AI Processing**: Via Qwen3 hybrid reasoning
3. **Consensus**: Through cryptographic validation
4. **Publishing**: To Solana blockchain

> The oracle network uses cryptographic proofs, anomaly detection, and validator incentives for reliability.

---

## Staking

- Up to **18% APY** on staked $XUN
- Up to **40% discount** on compute and oracle fees
- Access to premium feeds and higher usage limits
- **Governance rights** in future DAO proposals

```ts
await xun.staking.stake(1000); // Stake 1000 $XUN
```

---

## Supported Environments

| Environment | Minimum | Recommended | Purpose               |
|-------------|---------|-------------|------------------------|
| Node.js     | v14     | v16+        | For SDK integration   |
| Rust        | 1.60    | 1.70+       | For Solana programs   |
| Python      | 3.8     | 3.10+       | Optional SDK usage    |
| Solana CLI  | 1.10    | 1.16+       | On-chain interaction  |

---

## Contributing

Open to all contributors. Fork the repo, open issues, suggest features, and build the decentralized AI future with us.

---

## License
MIT License. See the `LICENSE` file for details.

