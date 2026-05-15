# QuantDinger

**Open-source AI-native quant infrastructure for crypto, stocks, forex.**

Market data → Backtest → Execution. One system.

[https://www.quantdinger.com](https://www.quantdinger.com) | [Live Demo](https://ai.quantdinger.com)

---

## Why

Most quant tools are disconnected. You write indicators in one place, backtest in another, then hack together a live execution script that falls over at 2am.

QuantDinger connects the loop. That’s it.

- AI-assisted research (agents, not hype)
- Strategy dev in Python
- Backtest with realistic slippage/fees
- Live trading via CCXT (100+ exchanges)
- Docker deploy, self-hosted

No SaaS lock-in. No black boxes.

---

## What it does

```
Idea → Indicator → Backtest → Optimize → Execute → Monitor
```

Everything from research to live trades, in one codebase.

- Multi-market: crypto, stocks, forex
- Multi-agent market analysis
- Strategy optimization (hyperparams)
- Alerts: email, webhook, Telegram, Discord
- PostgreSQL + Redis + Vue frontend

---

## Tech stack

- Python (Flask) for backend
- Vue 3 for frontend
- CCXT for exchange connectivity
- Docker for deployment
- Lightweight Charts for UI

Nothing fancy. Just works.

---

## Repositories

- [QuantDinger](https://github.com/brokermr810/QuantDinger) – core backend & engine
- [QuantDinger-Vue](https://github.com/brokermr810/QuantDinger-Vue) – frontend
- [QuantDinger-Mobile](https://github.com/brokermr810/QuantDinger-Mobile) – mobile app

---

## Get started

```bash
git clone https://github.com/brokermr810/QuantDinger.git
cd QuantDinger
docker-compose up -d
```

Then open `http://localhost:3000`.

Or try the live demo: [ai.quantdinger.com](https://ai.quantdinger.com)

---

## Philosophy

- Open source > closed SaaS
- Own your infrastructure
- Inspect, modify, break, fix
- No telemetry, no tracking, no vendor lock

If you trade seriously, you should run your own stack.

---

## License

Apache 2.0

---

**Research → Backtest → Execute.**
