# Guardian X 🛡️

**The Most Advanced Solana Token Security Scanner**

Guardian X is the #1 comprehensive security platform for Solana tokens, providing real-time threat detection, AI-powered audits, and wallet protection. Built for traders, developers, and communities who demand the highest level of security.

---

## 🚀 Why Guardian X is the Best

### Real-Time DexScreener Integration
- **Live Liquidity Data**: Fetches real USD liquidity values from DexScreener API
- **Market Intelligence**: Real-time price, volume, and FDV tracking
- **Accurate Detection**: $76K liquidity? We'll show it as SAFE, not a false honeypot

### Smart Risk Analysis
- **$50K+ Liquidity = Automatic Safe Rating**: High liquidity makes rug pulls economically unfeasible
- **Intelligent Scoring**: Considers liquidity amount, lock status, volume, and on-chain data
- **Context-Aware**: Mint authority only flagged as risk when combined with low liquidity

### Comprehensive Security Checks
- ✅ Real liquidity verification via DexScreener
- ✅ Honeypot detection using on-chain data
- ✅ Rug pull risk assessment
- ✅ Mint & freeze authority verification
- ✅ Transfer restrictions analysis
- ✅ Tax calculation (buy/sell)
- ✅ Volume & market activity tracking
- ✅ AI-powered audit reports

---

## 💎 Pricing Tiers

### 🆓 Free Scan
- Quick Honeypot Check
- Dust Wallet Detection
- Basic Token Info
- **3 Free Scans Daily**
- **Price: FREE**

### 💎 Deep Scan
- Full Smart Contract Analysis
- **Real-time DexScreener Data**
- Rug & Blacklist Detection
- Liquidity Breakdown
- Threat Meter + Human Explanation
- **Price: $0.10 USD per scan**

### 🧠 Pro Guardian ($9.99/month)
- **Unlimited Deep Scans**
- Predictive AI Threat Modeling
- Wallet Trust Score Tracking
- Auto Risk Alerts
- Jupiter Swap Guard
- Priority Scan Speed
- Exclusive Threat Reports
- Daily Gem Claiming

### 🪙 OG Guardian NFT (Limited)
- **Lifetime Pro Access**
- Free Unlimited Scans
- Exclusive OG Badge
- 2× Referral Rewards
- $GDNX Airdrop Eligibility
- Early Feature Access
- Tradable on Marketplaces

### 🧰 API / B2B
- Volume-based pricing ($0.02-$0.05/scan)
- Custom branding & dashboard
- Team support
- Perfect for wallets, DEXes, NFT marketplaces

---

## 🎁 Referral System - Earn While You Protect

- **Invite Friends**: +1 FREE Deep Scan per signup
- **Share on X**: +3 Bonus Deep Scans per verified share
- **Top Referrer**: Free Pro Guardian + Leaderboard exposure
- **OG NFT Holders**: 2× referral rewards

### Your Personal Referral Link
Every user gets a unique referral code automatically. Share it and stack rewards!

---

## 💰 Daily Gems System

Claim 1 gem daily for future $GDNX token airdrop eligibility. The more gems you collect, the better your allocation!

---

## 🔥 Features That Make Us #1

### 1. Real Liquidity Verification
Unlike other scanners that use mock simulations, we fetch actual liquidity data from DexScreener:
```javascript
// ✅ Guardian X
const liquidityUsd = await fetchFromDexScreener(tokenAddress)
if (liquidityUsd >= 50000) markAsSafe()

// ❌ Other scanners
if (mockSimulation.failed) markAsHoneypot() // Often wrong!
```

### 2. Smart Context-Aware Analysis
- High liquidity ($50K+) → Safe even if not explicitly locked
- Medium liquidity ($10K-$50K) unlocked → Suspicious
- Low liquidity (<$10K) → High risk
- No liquidity → Honeypot

### 3. AI-Powered Comprehensive Audits
- Uses Google Gemini AI
- Analyzes all metrics holistically
- Provides human-readable explanations
- Scores tokens 0-100 with detailed findings

### 4. Wallet Protection
- Dust token detection
- Real-time wallet analysis
- Simulated transaction testing
- Risk score for holdings

### 5. Beautiful, Professional UI
- Dark mode optimized
- Real-time statistics dashboard
- Animated risk meters
- Color-coded threat levels
- Mobile responsive

---

## 🛠️ Tech Stack

- **Frontend**: React + TypeScript + Vite
- **Styling**: Tailwind CSS + Custom Design System
- **Backend**: Supabase Edge Functions
- **Blockchain**: Solana Web3.js
- **APIs**: DexScreener, Solana RPC
- **AI**: Google Gemini 2.5 Flash
- **Payments**: Solana Pay to treasury

---

## 💻 Quick Start

### Prerequisites
- Node.js & npm installed ([install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating))

### Setup
```bash
# Clone the repository
git clone <YOUR_GIT_URL>

# Navigate to directory
cd <YOUR_PROJECT_NAME>

# Install dependencies
npm install

# Start development server
npm run dev
```

### Environment Variables
Required environment variables:
- `VITE_SUPABASE_URL`
- `VITE_SUPABASE_PUBLISHABLE_KEY`

---

## 🔐 Security & Privacy

- All payments verified on-chain
- Row-Level Security (RLS) on all tables
- Secrets managed via Supabase Vault
- No API keys stored client-side
- CORS-protected edge functions

---

## 📊 Platform Statistics

Live tracking of:
- Total scans performed
- Safe vs risky tokens
- Active wallets analyzed
- Real-time threat detection

---

## 🎯 Use Cases

### For Traders
Scan tokens before buying to avoid:
- Honeypots (can't sell)
- Rug pulls (liquidity removal)
- Hidden mint functions
- Excessive taxes

### For Developers
Benchmark your token security before launch and ensure it passes all checks.

### For Communities
Protect members with real-time monitoring and risk alerts.

### For DeFi Protocols
Integrate our API to protect users automatically.

---

## 🚦 Safety Indicators Explained

| Indicator | Safe | Suspicious | Dangerous |
|-----------|------|------------|-----------|
| Liquidity | $50K+ | $10K-$50K unlocked | <$10K or none |
| Volume | $100K+ daily | $10K-$100K | <$10K |
| Mint Authority | Renounced | Active (high liq) | Active (low liq) |
| Taxes | <5% | 5-10% | >10% |

---

## 📱 Mobile Support

Fully responsive design works perfectly on:
- Desktop (1920px+)
- Laptop (1366px+)
- Tablet (768px+)
- Mobile (375px+)

---

## 🌐 Deployment

### Build for Production
```bash
npm run build
```

### Deploy
Deploy the `dist` folder to your preferred hosting service (Vercel, Netlify, etc.)

---

## 📝 Changelog

### v2.0.0 - The Best Scanner Update ⭐
- ✅ Real DexScreener API integration
- ✅ Fixed false honeypot detections
- ✅ Smart liquidity-based risk scoring
- ✅ Pricing reduced to $0.10/scan
- ✅ Market data display (price, volume, FDV)
- ✅ Risk factors breakdown
- ✅ Security guide for users
- ✅ Improved UI/UX

### v1.0.0 - Initial Release
- Basic honeypot detection
- AI audit system
- User authentication
- Payment integration

---

## 🏆 What Makes Us Different

| Feature | Guardian X | Other Scanners |
|---------|------------|----------------|
| Real Liquidity Data | ✅ DexScreener API | ❌ Mock simulations |
| Smart Risk Scoring | ✅ Context-aware | ❌ Binary yes/no |
| AI Audits | ✅ Gemini 2.5 | ❌ Limited or none |
| Wallet Protection | ✅ Full analysis | ⚠️ Basic |
| Price | $0.10/scan | $0.50-$2.00/scan |
| False Positives | ✅ Minimal | ❌ Common |
| Real-time Market Data | ✅ Yes | ❌ No |

---

## 🏗️ Architecture

### Edge Functions
Located in `supabase/functions/`:
- `honeypot-scanner` - Main token security scanner with DexScreener integration
- `dust-scanner` - Wallet dust detection
- `token-audit` - AI-powered comprehensive audit
- `process-payment` - Solana payment verification

### Database Schema
- `user_profiles` - User accounts with tier and referral tracking
- `token_scans` - Scan history and results
- `wallet_scans` - Wallet analysis data
- `payments` - On-chain payment verification
- `subscriptions` - Tier subscriptions
- `referrals` - Referral tracking system
- `daily_gems` - Gem claiming records
- `social_shares` - Social media share tracking

---

## 🙏 Credits

Built with ❤️ using:
- [Supabase](https://supabase.com) - Backend infrastructure
- [DexScreener](https://dexscreener.com) - Real-time market data API
- [Solana](https://solana.com) - Fast, decentralized blockchain
- [React](https://react.dev) - UI framework
- [Vite](https://vitejs.dev) - Build tool

---

## 📄 License

MIT License - Feel free to fork and build upon this!

---

## 🔮 Roadmap

- [ ] Mobile app (iOS/Android)
- [ ] Browser extension (Chrome/Firefox)
- [ ] Telegram bot integration
- [ ] Discord bot integration
- [ ] Multi-chain support (ETH, BSC, Arbitrum)
- [ ] $GDNX token launch & staking
- [ ] DAO governance
- [ ] Advanced portfolio tracking
- [ ] Real-time price alerts
- [ ] Historical scan analytics

---

## 🌟 Treasury Wallet

All payments flow to: `5uMqgwwLJEsBUWkcrRbhzphz8kzfsgVxdPYw2Z5p7mpy`

---

**Guardian X - Your Shield in the Decentralized World** 🛡️

*Protecting traders since 2025. One scan at a time.*