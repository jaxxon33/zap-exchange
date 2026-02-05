# Zap Exchange - Xnet

Crypto cross-chain swap quote tool powered by THORChain.

## 🚀 Quick Deploy to GitHub Pages

1. **Create Repository** (if you haven't already)
   - Go to GitHub.com → Click **+** → **New repository**
   - Name it: `zap-exchange`
   - Make it **Public**
   - Click **Create repository**

2. **Upload Files**
   - Click **Upload files**
   - Drag and drop these files from your Desktop:
     - `zap-exchange.html` (or `index.html`)
     - `README.md`

3. **Enable GitHub Pages**
   - Go to **Settings** → **Pages**
   - Under **Branch**, select `main`
   - Click **Save**
   - Wait 1-2 minutes

4. **Access Your Site**
   - Visit: `https://YOUR_USERNAME.github.io/zap-exchange/`

## 🔗 Custom Domain Setup

Once deployed:

1. **In GitHub Settings → Pages:**
   - Add custom domain: `yourdomain.com`
   - GitHub shows you an A/CNAME record

2. **In DreamHost DNS:**
   - Find your domain's DNS settings
   - Add the GitHub DNS record
   - Wait for propagation (5-10 minutes)

## ✨ Features

- BTC → ETH swap quotes
- Mainnet THORChain integration
- Rate limiting (1 second between requests)
- Error handling and debugging

## 🤖 API Issues

**THORChain has strict rate limiting.** If you see errors:
1. Wait 30-60 seconds between requests
2. Check browser console (F12) for CORS details
3. Use the bot script for testing: `zap-bot.js`

## 📝 For Developers

See `demo-simple.html` for the complete source with rate limiting logic.

## 🏢 Business

**Xnet** - Cross-chain crypto exchange tools

---

**Deployed with:** GitHub Pages (free)
**API:** THORChain Ninerealms Mainnet
**Last Updated:** 2026-02-05
