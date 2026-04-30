<div align="center">

# Abhishek Deshmukh · ZEFu
### Quant Developer · Algorithmic Trading Systems · AI Infrastructure
**Pune, Maharashtra, India**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abhishek_Deshmukh-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/abhishek-deshmukh-03a908270)
[![GitHub](https://img.shields.io/badge/GitHub-a1shmuk-181717?style=flat&logo=github)](https://github.com/a1shmuk)
[![GohanQuant](https://img.shields.io/badge/Initiative-GohanQuant_(Build_Phase)-gold?style=flat)](https://github.com/a1shmuk)

</div>

---

## Executive Summary

Abhishek Deshmukh is a quant developer and systems builder focused on **algorithmic trading** and **AI-driven trading infrastructure**.

Background in Civil Engineering with a self-directed specialisation in quantitative finance, systematic strategy development, and agentic AI systems.

Currently building **GohanQuant** — a developing quantitative trading system targeting XAUUSD, with a phased expansion roadmap into crypto and indices.

**Approach:**
- Engineering-first. No hype, no unverified claims.
- Strategy validation before capital deployment.
- Risk-first architecture at every layer.

---

## GohanQuant — Current Build State

```
Status: Active Development (Phase 1 — XAUUSD)
Capital:  Proprietary only. No external AUM.
Target:   25–30% annualised return · Sharpe > 2.0 · Max DD < 10%
```

**System Architecture (Layered)**

| Layer | Desk | Status |
|-------|------|--------|
| Alpha Engine | SMC / Market Structure | ✅ Active |
| Alpha Engine | Technical Filters (Phase 1) | ✅ Complete |
| Alpha Engine | ML / Regime Detection | 🔧 In Progress |
| Data Layer | MT5 Tick Pipeline | ✅ Active |
| Risk Layer | VaR + Drawdown Controls | 🔧 In Progress |
| Execution | Python–MT5 Bridge | ✅ Active |
| Portfolio | Kelly + MVO Sizing | 📋 Planned |

**Tech Stack**

```python
Languages : Python 3.14, Pine Script v5, MQL5
Execution : MetaTrader 5 (Python bridge), MT5 EA
Data      : MT5 tick feed, COT reports, macro events
Analysis  : pandas, numpy, scipy, statsmodels
ML        : scikit-learn, XGBoost (planned: PyTorch)
Dev Env   : VS Code, Windows 11, Git
```

---

## Projects

### [xauusd-algo-trader](https://github.com/a1shmuk/xauusd-algo-trader)
Python-based algorithmic trading system for XAUUSD via MetaTrader 5.

- Phase 1: Multi-factor technical engine (EMA, RSI, ATR, spread filters)
- Phase 2: SMC engine — CHoCH, BOS, W1→D1→H1 trend hierarchy
- Phase 3–6: Fundamental, unified signal, and ML engines (planned)
- Live execution via MT5 Python API

**Stack:** `Python` `MetaTrader5` `pandas` `MQL5`

---

### Pine Script Market Structure Indicator *(TradingView)*
Layered indicator combining SMC market structure with MarketCycle Pro logic.

- HH / HL / LH / LL detection across timeframes
- BOS and CHoCH confirmation with 2-CR entry logic
- Supply & demand zone plotting
- Live trend dashboard (HTF → LTF bias)

**Stack:** `Pine Script v5` `TradingView`

---

### AgentBot Trading Assistant *(Paused — API Credits)*
5-agent Claude-powered system for trade filtering and analysis.

- Modular agent architecture (signal → filter → risk → execute → report)
- Anthropic API integration
- Paused pending API credit allocation

**Stack:** `Python` `Claude API` `Anthropic SDK`

---

### OpenClaw — Local LLM Setup *(Windows Native)*
Local AI environment for trading research and automation.

- Ollama + Kimi K2.5 on Windows (no WSL2)
- Web UI at `localhost:18789`
- Used for private strategy research and prompt development

**Stack:** `Ollama` `Kimi K2.5` `Windows 11`

---

## Domain Focus

```
Quantitative Trading        Algorithmic Strategy Development
Smart Money Concepts (SMC)  AI in Trading Systems
Risk Management             Market Structure Analysis
Agentic AI Systems          Python Automation
```

---

## Learning Roadmap

- [x] Phase 1 — Technical trading engine (Python + MT5)
- [x] Phase 2 — SMC engine (CHoCH, BOS, structure hierarchy)
- [ ] Phase 3 — Fundamental engine (COT, macro, sentiment)
- [ ] Phase 4 — Unified signal aggregation layer
- [ ] Phase 5 — ML regime detection + adaptive sizing
- [ ] Phase 6 — Full portfolio construction + risk dashboard
- [ ] Phase 7 — GohanQuant AIF Cat III registration (India)

---

## GitHub Activity

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=a1shmuk&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=d4a017&icon_color=d4a017)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=a1shmuk&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=d4a017)

</div>

---

## Philosophy

> *"Build systems. Validate edge. Scale only when proven."*

---

<div align="center">

**GohanQuant is in development phase.**  
No external capital. No public performance claims. Engineering only.

</div>
