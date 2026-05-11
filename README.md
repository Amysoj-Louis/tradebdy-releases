# tradebdy

**From market idea to live paper trade — without leaving your desk.**

TradingView shows you charts. Zerodha lets you trade. Nothing lets you *research, build, test, and run strategies* in one place — until now.

tradebdy is a free desktop app that puts a Python research notebook, a strategy backtester, and a live paper trading terminal side by side. No browser tabs. No copy-pasting between tools. No subscription.

---

## Why traders switch to tradebdy

| | tradebdy | TradingView | Streak / Algoji | Custom Python setup |
|---|---|---|---|---|
| Write Python freely | ✅ | ❌ | ❌ | ✅ |
| AI writes code for you | ✅ | ❌ | ❌ | ❌ |
| Backtest on real broker data | ✅ | ✅ | ✅ | ✅ |
| Paper trade live | ✅ | ✅ paid | ✅ paid | manual |
| Everything in one app | ✅ | ❌ | ❌ | ❌ |
| Runs fully offline | ✅ | ❌ | ❌ | ✅ |
| Free | ✅ | freemium | paid | ✅ |

---

## What you can do

### Research with AI
Open the notebook, describe what you want to see — *"plot RSI divergence on RELIANCE with volume overlay"* — and the AI writes and runs the code. Or write your own Python. Full pandas, numpy, pandas-ta, and 100+ technical indicators available.

### Backtest any strategy
Write or describe a strategy. tradebdy runs it on real historical OHLCV data from your broker and gives you:
- Total return, Sharpe ratio, max drawdown
- Win rate, profit factor, expectancy
- Full trade log and interactive equity curve

### Paper trade live
Deploy your strategy against real market prices with a ₹10,00,000 virtual portfolio. MTM updates in real time. Run multiple algos in parallel, each with its own stop-loss and take-profit. One-click circuit breaker if drawdown hits your limit.

### Watchlist
Track any equity with live prices, OHLCV, and volume — all streaming from your broker.

---

## Works with Dhan

Connect your [Dhan](https://dhanhq.co) account to unlock live data and real-time paper trading MTM. More brokers coming.

**tradebdy never places real orders. All trading is paper only.**

---

## Use any AI model

Bring your own API key — or run fully offline with Ollama.

| Provider | Cost |
|----------|------|
| [Groq](https://console.groq.com) | Free tier — fast, great for code |
| [OpenAI](https://platform.openai.com) | Pay-per-use — GPT-4o, o1 |
| [Mistral](https://mistral.ai) | Free tier |
| [Ollama](https://ollama.ai) | Free — runs 100% on your machine |
| Any OpenAI-compatible endpoint | Custom base URL supported |

---

## Download

**v0.1-beta** — [→ Latest release](https://github.com/Amysoj-Louis/tradebddy-releases/releases/latest)

| Platform | Installer |
|----------|-----------|
| 🐧 Linux (Ubuntu / Debian / Mint) | `.deb` package |
| 🍎 macOS — Intel | `.dmg` |
| 🍎 macOS — Apple Silicon (M1/M2/M3) | `.dmg` |
| 🪟 Windows 10 / 11 | `.exe` installer |

**Zero setup. No Python, no Node.js, no command line.**
Download, install, open.

**Linux**
```bash
sudo dpkg -i tradebdy_*.deb
```

**macOS** — open the `.dmg`, drag to Applications.
First launch: System Settings → Privacy & Security → Open Anyway.

**Windows** — run the `.exe`. SmartScreen: click **More info → Run anyway**.

---

## Your data stays yours

- No account required
- No telemetry, no analytics
- Nothing sent to the cloud
- All credentials stored locally on your machine
- Uninstall anytime — your strategies and data stay in your home folder

---

## Early access

v0.1-beta is the first public release. Core features are working. Paper trading only — real order execution is on the roadmap.

Found a bug or have a feature request? [Open an issue](https://github.com/Amysoj-Louis/tradebddy-releases/issues) — every report helps.
