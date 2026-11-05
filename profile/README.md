# open-trading-bot

An open-source algorithmic crypto trading bot for [Bybit](https://www.bybit.com), with the strategies as a separate package.

The bot runs your strategies at a fixed interval and applies your risk limits. You can test a strategy on historical data, then run it in paper mode or on the Bybit testnet.

- **Strategies**: MA crossover, RSI, MACD, Bollinger Bands and Wyckoff. They use closed candles only.
- **Backtests**: test a strategy on historical data, with fees and slippage.
- **Risk management**: stop loss, daily loss limit, maximum open positions and a kill switch.
- **Paper mode**: test the bot without real funds.
- **Dashboard**: see positions, strategies and backtests.
- **Backoffice**: manage users, roles, invitations and feature flags.

**[Quick start](https://github.com/open-trading-bot/open-trading-bot#quick-start-local)** · [Run with Docker](https://github.com/open-trading-bot/open-trading-bot#running-with-docker) · [Q&A](https://github.com/open-trading-bot/open-trading-bot/discussions/categories/q-a) · [Releases](https://github.com/open-trading-bot/open-trading-bot/releases)

## Open source

- [open-trading-bot](https://github.com/open-trading-bot/open-trading-bot): the bot, with the server, the dashboard and the backoffice (MIT).
- [strategies](https://github.com/open-trading-bot/strategies): the strategies and a backtester, with no server, database or exchange keys. Install it with `npm install @open-trading-bot/strategies` (MIT).

## Contribute

- Read the [contributing guide](https://github.com/open-trading-bot/open-trading-bot/blob/main/CONTRIBUTING.md).
- To find a small task, look at the [good first issues](https://github.com/open-trading-bot/open-trading-bot/labels/good%20first%20issue).
- Do not report security vulnerabilities in public issues. Read the [security policy](https://github.com/open-trading-bot/open-trading-bot/blob/main/SECURITY.md).

> **Disclaimer:** This software is **not financial advice**. Crypto trading has a high risk of loss. You use this software at your own risk. Always start in **paper mode** or on the **Bybit testnet**.
