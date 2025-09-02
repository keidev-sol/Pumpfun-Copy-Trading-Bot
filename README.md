# 🚀 Pumpfun Copy Trading Bot

A **high-performance copy trading bot** on Solana that automatically tracks and replicates trades from a target wallet in real time.  
The bot continuously monitors on-chain activity (buy/sell transactions) and mirrors them in your wallet with customizable settings.  
It enables you to follow top traders seamlessly on **Pumpfun** as well as other major Solana DEXs.  

---

## 🔑 Features
- **Real-Time Trade Mirroring**: Instantly copies buy and sell actions from selected wallets.  
- **Cross-DEX Support**: Works with Pumpfun, Raydium, Jupiter, and other Solana-based exchanges.  
- **Automated Execution**: Executes trades automatically based on your configuration.  
- **Customizable Strategies**: Adjust buy/sell sizes, slippage, and risk preferences.  
- **Multi-Wallet Management**: Run copy trading on multiple wallets simultaneously.  

---

## ⚡ Enhanced WebSocket Example

```json
{
  "jsonrpc": "2.0",
  "id": 420,
  "method": "transactionSubscribe",
  "params": [
    {
      "vote": false,
      "failed": false,
      "signature": "2dd5zTLrSs2udfNsegFRCnzSyQcPrM9svX6m1UbEM5bSdXXFj3XpqaodtKarLYFP2mTVUsV27sRDdZCgcKhjeD9S",
      "accountInclude": ["pqx3fvvh6b2eZBfLhTtQ5KxzU3CginmgGTmDCjk8TPP"],
      "accountExclude": ["FbfwE8ZmVdwUbbEXdq4ofhuUEiAxeSk5kaoYrJJekpnZ"],
      "accountRequired": ["As1XYY9RdGkjs62isDhLKG3yxMCMatnbanXrqU85XvXW"]
    },
    {
      "commitment": "processed",
      "encoding": "base64",
      "transactionDetails": "full",
      "showRewards": true,
      "maxSupportedTransactionVersion": 0 
    }
  ]
}

```

---

## 👤 Author  

- **Telegram**: [Kei Novak](https://t.me/Kei4650)  
- **Twitter (X)**: [Kei Novak](https://x.com/kei_4650)  

---


