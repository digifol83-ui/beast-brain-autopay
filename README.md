# ⚡ BeastBrain AutoPay

**Universal Fiat-to-Crypto Payment Infrastructure — One Integration, Every Gateway.**

Card → Wallet in seconds. Zero OTP. 100% settlement.

## 🏗️ Architecture

```
User → BeastBrain API → Gateway Router → [Transak | Stripe | Plisio | ChangeNOW]
                                              ↓
                                    Solana Blockchain (USDC)
                                              ↓
                                       Recipient Wallet
```

## 📦 SDKs & Integrations

| Service      | Type       | Install Command                                   |
|-------------|-----------|---------------------------------------------------|
| **Transak**  | Frontend  | `npm install @transak/transak-sdk`                |
| **Stripe**   | Fullstack | `pip install stripe` / `npm install stripe`       |
| **Plisio**   | Backend   | `composer require plisio/plisio-api-php`          |
| **ChangeNOW**| Backend   | REST API (no SDK needed)                          |
| **Google Cloud** | Infra | `pip install google-cloud-secret-manager`         |
| **Solana**   | Blockchain| `npm install @solana/web3.js @solana/spl-token`   |

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/digifol83-ui/beast-brain-autopay.git
cd beast-brain-autopay

# Open the interactive developer portal
open index.html   # or double-click in file explorer
```

## 🌐 Interactive Developer Portal

Open `index.html` in your browser — a full interactive portal with:

- **Live Code Samples** — every SDK with copy-to-clipboard
- **API Playground** — test BeastBrain endpoints in-browser
- **Architecture Diagram** — visual system overview
- **Search** — find any SDK, command, or concept instantly
- **All 6 SDKs** — Transak, Stripe, Plisio, ChangeNOW, Google Cloud, Solana

## 📂 Project Structure

```
beast-brain-autopay/
├── index.html          # Interactive developer portal
├── README.md           # This file
└── .gitignore
```

## 🔗 Related Repositories

- [brain-api](https://github.com/digifol83-ui/brain-api) — BeastBrain core API
- [payment-gateway](https://github.com/digifol83-ui/payment-gateway) — Gateway activation & management

## 📄 License

MIT © 2026 BeastBrain
