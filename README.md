# Awesome Polymarket Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, libraries, bots, and resources for the Polymarket prediction market ecosystem.

Polymarket is a decentralized information markets platform where users can trade on the outcome of future events. This list compiles the best tools and resources for traders, developers, and researchers.

## Contents

- [Official Resources](#official-resources)
- [Browser Extensions](#browser-extensions)
- [Productivity Platform Extensions](#productivity-platform-extensions)
- [Analytics & Tracking](#analytics--tracking)
- [Trading Bots & Automation](#trading-bots--automation)
- [API Libraries & SDKs](#api-libraries--sdks)
- [Telegram Bots](#telegram-bots)
- [Data APIs & Aggregators](#data-apis--aggregators)
- [Infrastructure & Integrations](#infrastructure--integrations)
- [Educational Resources](#educational-resources)
- [Community](#community)

## Official Resources

- [Polymarket](https://polymarket.com/) - Official platform
- [Polymarket Documentation](https://docs.polymarket.com/) - Developer documentation and API references
- [Polymarket Blog](https://polymarket.com/blog) - Official announcements and insights
- [Polymarket GitHub](https://github.com/Polymarket) - Official repositories
- [CLOB API Documentation](https://docs.polymarket.com/#clob-api) - Central Limit Order Book API
- [Gamma API Documentation](https://docs.polymarket.com/#gamma-api) - Market metadata and event data API

## Browser Extensions

### Chrome Extensions

- [PolyPulse](https://chromewebstore.google.com/detail/polypulse) - AI-powered news insights with Perplexity AI integration, auto market detection, and secure API storage
- [Polyteller](https://chromewebstore.google.com/detail/polyteller) - Essential trading tools including real-time countdowns, smart notifications, and privacy mode
- [Polyhelper](https://chromewebstore.google.com/detail/polyhelper) - Enhanced Polymarket experience with countdowns, notifications, and privacy features
- [Nevua Markets Plugin](https://chromewebstore.google.com/detail/nevua-markets-plugin) - Price alerts with over/under thresholds and real-time monitoring

### Firefox Extensions

- [PolymarketOddsConverter](https://addons.mozilla.org/en-US/firefox/addon/polymarketoddsconverter/) - Converts probabilities to decimal odds (also available for Chrome)

## Productivity Platform Extensions

- [Polymarket Extension for Raycast](https://www.raycast.com/extensions/polymarket) - Search and view Polymarket markets directly from Raycast with price charts, volume tracking, and real-time data

## Analytics & Tracking

### Whale Tracking

- [PolyTrack](https://polytrack.org/) - Comprehensive whale tracking with real-time alerts, leaderboards, P&L tracking, and detailed trader profiles
- [Polywhaler](https://polywhaler.com/) - Track $10k+ trades with insider activity detection and AI-powered predictions
- [Poly Whales Tracker](https://polywhalestracker.com/) - Elite trader monitoring with real-time alerts and historical performance analysis

### General Analytics

- [Polymarket Analytics](https://polymarket-analytics.com/) - Market search, activity monitoring, and portfolio tracking across multiple platforms
- [loki.red Polymarket Stats](https://www.loki.red/polymarket/) - Comprehensive Polymarket statistics and market insights
- [Dune Analytics - Polymarket Dashboards](https://dune.com/browse/dashboards?q=polymarket) - Multiple community-created dashboards for volume tracking, open interest, and user analytics
- [Bitquery Polymarket API](https://bitquery.io/) - Blockchain data and on-chain analytics for Polymarket smart contracts

## Trading Bots & Automation

### Official & Featured

- [Polymarket Agents](https://github.com/Polymarket/agents) - Official AI agents framework with LLM integration, autonomous trading capabilities, and modular architecture
- [poly-market-maker](https://github.com/Polymarket/poly-market-maker) - Official CLOB market maker with bands or AMM strategy and Docker support

### Market Making Bots

- [poly-maker](https://github.com/dev-0x7C6/poly-maker) - Automated market making bot with Google Sheets configuration and position merging
- [polymarket-marketmaking](https://github.com/0xMel/polymarket-marketmaking) - Band-based market making bot with automated order management

### Trading & Execution

- [polymarket-spike-bot](https://github.com/username/polymarket-spike-bot) - High-frequency spike detection bot with real-time monitoring and automated execution
- [polymarket-trading](https://github.com/username/polymarket-trading) - Command-line trading tool with simple CLI interface

### Copy Trading

- [polymarket-copy-trading-bot](https://github.com/username/polymarket-copy-trading-bot) - Automated copy trading with real-time monitoring of top traders
- [polymarket-trade-copier](https://github.com/username/polymarket-trade-copier) - Enterprise-grade trade copier with blockchain event tracking

## API Libraries & SDKs

### Python

- [polymarket-apis](https://pypi.org/project/polymarket-apis/) - Unified Polymarket APIs with Pydantic models for CLOB, Gamma, Data, Web3, WebSocket, and GraphQL clients
- [py-clob-client](https://pypi.org/project/py-clob-client/) - Official Python client for Polymarket's CLOB with order execution and market data

### JavaScript/TypeScript

#### Official SDKs

- [@polymarket/sdk](https://www.npmjs.com/package/@polymarket/sdk) - Official Polymarket SDK for proxy wallet interactions and trading operations
- [@polymarket/clob-client](https://www.npmjs.com/package/@polymarket/clob-client) - Official CLOB client with order placement, market data, and WebSocket support
- [@polymarket/embeds](https://www.npmjs.com/package/@polymarket/embeds) - Official embeddable web components for Polymarket markets

#### Community Libraries

- [@polybased/sdk](https://www.npmjs.com/package/@polybased/sdk) - Comprehensive TypeScript toolkit with real-time data and WebSocket streams
- [@dicedhq/polymarket](https://jsr.io/@dicedhq/polymarket) - TypeScript client with CLOB and Gamma client support
- [polymarket-data](https://www.npmjs.com/package/polymarket-data) - Community TypeScript client for public data access with type safety

#### Integrations & Plugins

- [@theschein/plugin-polymarket](https://www.npmjs.com/package/@theschein/plugin-polymarket) - ElizaOS agent integration for AI agent trading
- [@goat-sdk/plugin-polymarket](https://www.npmjs.com/package/@goat-sdk/plugin-polymarket) - GOAT SDK plugin for market data and betting

## Telegram Bots

- [Polycule](https://t.me/polyculebot) - Telegram trading bot with group trading, copy trading, wallet tracking, and mobile-first design
- [PolyFocus](https://t.me/polyfocusbot) - Trading bot with copy trading, multi-chain wallet, market search, and position tracking
- [Polysight](https://t.me/polysightbot) - Real-time market insights bot with fast alerts and actionable summaries
- [PolyxBot](https://t.me/polyxbot) - AI-powered intelligence tool with whale tracking and predictive signals
- [Polycool Bot](https://t.me/polycoolbot) - Copy-trading tool for following winning wallets and profitable whales
- [PolyAlertHub](https://t.me/polyalerthub) - Alert system with whale tracking, volatility monitoring, and multi-channel alerts

## Data APIs & Aggregators

- [FinFeedAPI - Prediction Markets](https://finfeed.io/api/prediction-markets) - Unified API for Polymarket, Kalshi, Myriad, and Manifold with OHLCV data
- [Polymarket Gamma API](https://gamma-api.polymarket.com/) - Official market metadata and event data API
- [Polymarket CLOB API](https://clob.polymarket.com/) - Official trading API with order book data and execution
- [Bitquery Polymarket GraphQL](https://graphql.bitquery.io/) - Blockchain data and smart contract events for on-chain analytics

## Infrastructure & Integrations

### AI Agent Integrations (MCP)

- [Sim.ai - Polymarket](https://sim.ai/mcp/polymarket) - MCP integration for AI agents with market listing, price data, and order book access

### API Marketplaces

- [Polymark.et](https://polymark.et/) - Comprehensive directory of Polymarket tools and products

## Educational Resources

### Guides & Tutorials

- [Polymarket Trading Guide](https://polymarket.com/guide) - Official beginner's guide to trading on Polymarket
- [How to Use the Polymarket API](https://docs.polymarket.com/api-guide) - API integration tutorials

### Research & Analysis

- [Prediction Market FAQ](https://astralcodexten.substack.com/p/prediction-market-faq) - Comprehensive FAQ by Scott Alexander
- [The Passage of Polymarket](https://astralcodexten.substack.com/p/the-passage-of-polymarket) - Deep dive into Polymarket's rise
- [Market Mechanics](https://manifoldmarkets.substack.com/p/above-the-fold-market-mechanics) - Understanding prediction market mechanics

### News & Aggregators

- [BaseRateTimes](https://www.baseratetimes.com/) - News through the lens of prediction markets including Polymarket

## Community

### Social Media

- [Polymarket Twitter](https://twitter.com/Polymarket) - Official Twitter account
- [Polymarket Discord](https://discord.gg/polymarket) - Official Discord community
- [0xperp's Polymarket List](https://twitter.com/i/lists/1684720466500431872) - Curated Twitter list of Polymarket traders and analysts

### Forums & Discussion

- [r/Polymarket](https://reddit.com/r/polymarket) - Reddit community for discussions and analysis
- [Polymarket Telegram](https://t.me/polymarket) - Official Telegram channel

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

## Author

List Compliled by [Harish Garg](https://harishgarg.com)
