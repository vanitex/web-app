<div align="center">
  <img src="docs/logo.png" alt="Vanitex" width="120" />

  <h1>Vanitex</h1>

  <p><strong>The Premier BSC Vanity Launchpad</strong></p>

  <p>
    <a href="https://vanitex.app"><img src="https://img.shields.io/badge/Live-vanitex.app-7c3aed?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live" /></a>
    <a href="https://x.com/vanitexapp"><img src="https://img.shields.io/badge/Twitter-@vanitexapp-000000?style=for-the-badge&logo=x&logoColor=white" alt="Twitter" /></a>
    <a href="https://t.me/vanitex"><img src="https://img.shields.io/badge/Telegram-@vanitex-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Chain-BNB%20Smart%20Chain-F0B90B?style=flat-square&logo=binance&logoColor=white" />
    <img src="https://img.shields.io/badge/License-MIT-7c3aed?style=flat-square" />
    <img src="https://img.shields.io/badge/Status-Live-22c55e?style=flat-square" />
  </p>
</div>

---

## Overview

**Vanitex** is a next-generation crypto launchpad built exclusively on BNB Smart Chain (BSC). It combines vanity wallet address generation with a full-featured token launchpad, presale platform, and staking ecosystem — all powered by the **VEX** token.

Every token launched through Vanitex receives a vanity address ending in `...5555`, mined client-side using multi-threaded Web Workers.

---

## Features

### Vanity Address Launchpad
- Launch tokens with addresses ending in `...5555` — mined in the browser, no server needed
- Bonding curve model: tokens graduate to PancakeSwap V2 at 6 BNB raised
- Graduated LP burned to `0xdead` — permanently locked
- Supports BNB, USDT, USDC, and ASTER as raise currencies
- Optional anti-sniper tax with auto-expiry, clog tax, and farmer protection
- Dividend token type with auto-distribution

### VEX Presale
- 15-stage presale from $0.0002 → $0.0015 (listing at $0.0020)
- Pay with BNB, USDT, or USDC
- On-chain referral system with tiered rewards
- Bonus code system (keccak256-verified on-chain)
- Live stage progress, countdown timer, and real-time BNB/USD pricing

### VEX Staking Vaults
| Vault | Lock Period | APY |
|---|---|---|
| Vault 1 | 1 Day | 183% |
| Vault 2 | 3 Days | 219% |
| Vault 3 | 7 Days | 55% |
| Vault 4 | 15 Days | 128% |

- Minimum stake: 1,000 VEX
- 10% early exit penalty
- Claim rewards anytime without unstaking

### Vanity Wallet Generator
- Generate BSC wallets with custom suffixes (e.g. `...5555`, `...DEAD`, `...CAFE`)
- 100% client-side — private keys never leave the browser
- Multi-threaded mining across all CPU cores

---

## Tokenomics — VEX

| Allocation | Amount | % |
|---|---|---|
| Presale | 500,000,000 | 50% |
| DEX Liquidity | 200,000,000 | 20% |
| Staking Rewards | 100,000,000 | 10% |
| Team | 100,000,000 | 10% |
| CEX | 100,000,000 | 10% |
| **Total Supply** | **1,000,000,000** | **100%** |

---

## Contracts (BSC Mainnet)

| Contract | Address |
|---|---|
| VEX Token | [`0xA12D634c8d98F2Afc3c5e2772370ffC6f8325555`](https://bscscan.com/token/0xA12D634c8d98F2Afc3c5e2772370ffC6f8325555) |
| VEX Presale | [`0x631B0C0D468E0aB95994581a48bC0a60d2c95555`](https://bscscan.com/address/0x631B0C0D468E0aB95994581a48bC0a60d2c95555) |
| Launchpad Portal | [`0x679138cE41C259d28070128d7ee9dAb7c0Ad654f`](https://bscscan.com/address/0x679138cE41C259d28070128d7ee9dAb7c0Ad654f) |
| VEXVault 1-Day (183%) | [`0x53C2489489dC435ceFa6E14bb1c4e80E5A359BdA`](https://bscscan.com/address/0x53C2489489dC435ceFa6E14bb1c4e80E5A359BdA) |
| VEXVault 3-Day (219%) | [`0x3668E0CC9971795a28B3A22e2C03512d110f7bA7`](https://bscscan.com/address/0x3668E0CC9971795a28B3A22e2C03512d110f7bA7) |
| VEXVault 7-Day (55%) | [`0x4650F017D2ED8b89dEa096e6AfeEF9Ee43fC30d5`](https://bscscan.com/address/0x4650F017D2ED8b89dEa096e6AfeEF9Ee43fC30d5) |
| VEXVault 15-Day (128%) | [`0x5fDeCD9352a5DD42238f79b8beB1071B4FC44a6d`](https://bscscan.com/address/0x5fDeCD9352a5DD42238f79b8beB1071B4FC44a6d) |

All contracts verified on BSCScan.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 18, Vite, TypeScript, Tailwind CSS |
| Web3 | ethers.js v6, MetaMask / injected wallets |
| Chain | BNB Smart Chain (BSC) mainnet |
| Smart Contracts | Solidity 0.8.34 |
| Infrastructure | AlmaLinux 9, Apache, PM2 |
| IPFS | Pinata |

---

## Getting Started

### Prerequisites
- MetaMask or any BSC-compatible wallet
- BNB for gas fees
- BSC network configured (Chain ID: 56)

### Using the Launchpad
1. Visit [vanitex.app/dashboard/launchpad/create](https://vanitex.app/dashboard/launchpad/create)
2. Fill in your token details
3. Choose your raise currency and initial buy amount
4. Click **GOING BIG** — MetaMask will pop up to confirm
5. Your token launches with a `...5555` vanity address

### Participating in the VEX Presale
1. Visit [vanitex.app/presale](https://vanitex.app/presale)
2. Connect your wallet
3. Buy VEX with BNB, USDT, or USDC
4. Optionally stake directly from the presale page

---

## Community

| Platform | Link |
|---|---|
| Website | [vanitex.app](https://vanitex.app) |
| Twitter / X | [@vanitexapp](https://x.com/vanitexapp) |
| Telegram | [@vanitex](https://t.me/vanitex) |
| GitHub | [github.com/vanitex/web-app](https://github.com/vanitex/web-app) |

---

## License

MIT © Vanitex
