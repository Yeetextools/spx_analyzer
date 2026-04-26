# YeetEX SPX500 US Open Analyzer

Bloomberg-style S&P500 trading dashboard for US Open strategy (9:30–10:30 ET).

**Live demo:** https://YOUR-USERNAME.github.io/spx-analyzer

## Features
- Real SPX price from Yahoo Finance ^GSPC (no key needed)
- Economic calendar via TradingEconomics
- Signal Engine: Gap & Go / Gap Fill / V-Recovery / OR Fade
- Directional Bias Score (0–100%)
- Opening Range visualizer with Manual Override
- 8 Sector ETFs via Finnhub (free key)
- Position sizer: SPY / MES / ES
- Pre-trade checklist (26 items)
- Trade journal with P&L tracking

## Deploy to GitHub Pages

1. Fork this repo
2. Go to Settings → Pages → Source: `main` branch, `/ (root)`
3. Your app will be live at `https://USERNAME.github.io/REPO-NAME`

## Data Sources
| Data | Source | Key needed |
|------|--------|-----------|
| SPX price, OHLC | Yahoo Finance ^GSPC | No |
| Economic calendar | TradingEconomics | No |
| Sector ETFs (×8) | Finnhub | Free |

## Usage
Open the app → SPX price loads automatically.
For sector ETFs: get free key at finnhub.io/register → paste in banner → Connect.
