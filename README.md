# tradebdy

**From market idea to live paper trade — without leaving your desk.**

tradebdy is a free desktop app for traders who want to research, build, test, and run strategies in one place. Write Python or describe what you want in plain English — the AI writes and runs the code for you. Backtest on real broker data. Paper trade live with a virtual portfolio. Everything on your machine, nothing in the cloud.

---

## What you get

### AI Research Notebook
A Python notebook with an AI co-author. Describe what you want to analyse — *"show RSI divergence on RELIANCE with volume"* — and the AI writes and runs the code. Or write your own. Full pandas, numpy, and 100+ technical indicators (via pandas-ta) available out of the box. The AI self-corrects if the code fails — up to 5 fix attempts before asking you.

### Strategy Studio
Describe your strategy in plain English. The AI writes the Python, validates it on synthetic data, fixes any errors, then hands you working code ready to backtest. A visual logic diagram shows exactly what the strategy does — no guessing.

### Backtesting
Run any strategy on real historical OHLCV data from your broker. Every backtest gives you total return, Sharpe ratio, max drawdown, win rate, profit factor, a full trade log, and an interactive equity curve.

### Paper Trading Terminal
Deploy strategies live against real market prices with a ₹10,00,000 virtual portfolio. Mark-to-market P&L updates in real time. Run multiple algos in parallel, each with its own stop-loss and take-profit. Circuit breaker pauses everything if drawdown hits your limit.

### Watchlist
Track any equity with live prices, OHLCV, and volume — streaming from your broker.

---

## Works with Dhan

Connect your [Dhan](https://dhanhq.co) account to get live quotes and historical data for backtesting and paper trading MTM. More broker integrations coming.

**tradebdy never places real orders. All trading is paper only.**

---

## Use any AI model

Bring your own API key — or run fully offline with Ollama. Works with any OpenAI-compatible endpoint.

| Provider | Cost |
|----------|------|
| [Groq](https://console.groq.com) | Free tier — fast, great for code |
| [OpenAI](https://platform.openai.com) | Pay-per-use — GPT-4o, o1, o3 |
| [Mistral](https://mistral.ai) | Free tier |
| [Ollama](https://ollama.ai) | Free — runs 100% on your machine |

---

## Download

**v0.1-beta** — [→ Latest release](https://github.com/Amysoj-Louis/tradebdy-releases/releases/latest)

| Platform | Installer |
|----------|-----------|
| 🐧 Linux — Ubuntu / Debian / Mint | `.deb` |
| 🍎 macOS — Intel | `.dmg` |
| 🍎 macOS — Apple Silicon (M1/M2/M3) | `.dmg` |
| 🪟 Windows 10 / 11 | `.exe` |

**No Python. No Node.js. No setup.** Download, install, open.

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
- No telemetry or analytics
- Nothing sent to the cloud
- All credentials stored locally on your machine
- Uninstall anytime — your strategies and data stay in your home folder

---

## Disclaimer

tradebdy is for research and paper trading only. No real orders are placed. Past backtest performance does not guarantee future results. Use at your own risk.

---

## Early access

v0.1-beta is the first public release. Core features are working. Found a bug or have a suggestion? [Open an issue](https://github.com/Amysoj-Louis/tradebdy-releases/issues).
