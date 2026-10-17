# GROM Exchange

[![GROM](https://grom.exchange/assets/grom-mark-nord.png)](https://grom.exchange/)

**A non-custodial DeFi interface for swaps, trading, prediction markets and tokenized stocks.**

[Open GROM Exchange](https://grom.exchange/) · [Swap](https://grom.exchange/swap) · [Trade](https://grom.exchange/futures) · [Markets](https://grom.exchange/markets)

This is GROM's public project overview for users, ecosystem directories and integration partners. It contains product documentation and links to the live application.

## Products

| Product | What it does | Open |
| --- | --- | --- |
| Instant Swap | Compare available token exchange routes, including supported cross-chain routes. | [Swap](https://grom.exchange/swap) |
| Trade | Access Hyperliquid spot and perpetual markets through a wallet-connected interface. | [Trade](https://grom.exchange/futures) |
| Markets | Explore market prices and supported trading instruments. | [Markets](https://grom.exchange/markets) |
| Prediction markets | Explore event markets and their available trading routes. | [Predictions](https://grom.exchange/predict) |
| Tokenized stocks | Explore supported tokenized equity instruments and purchase routes. | [Stocks](https://grom.exchange/stocks) |

## Wallet and transaction flow

Connect a compatible wallet, choose a product and review the amount, network, destination and quoted costs. Transaction signatures are requested in the user's wallet. Availability depends on the selected assets, network and upstream provider.

Cross-chain transactions can have separate source and destination stages. A submitted transaction is not the same as a completed destination transfer; use the transaction and route status to check settlement.

## Networks and integrations

GROM supports routes on BNB Smart Chain and other supported EVM networks, with Solana routes where available. Its live swap configuration includes LI.FI, ParaSwap, Kyber, Squid and Jupiter integrations. A configured provider does not guarantee a route for every pair or amount.

The current public configuration is available at [grom.exchange/api/swap/public-config](https://grom.exchange/api/swap/public-config). The application quote is the reference for the selected route, fees and estimated output. Network gas and provider fees can differ between routes.

Wallet connections use WalletConnect SignClient and supported injected wallets. Trading integrations and product availability may change as providers and networks evolve.

## Links

- Website: [grom.exchange](https://grom.exchange/)
- Russian landing page: [grom.exchange/ru/](https://grom.exchange/ru/)
- Brand mark: [GROM PNG](https://grom.exchange/assets/grom-mark-nord.png)
- Public project information: [this repository](https://github.com/gevo771-hue/grom-exchange-public)

## Feedback

Use this repository's Issues for public documentation corrections and reproducible interface reports. Include the page, browser, network and steps to reproduce. Never include a seed phrase, private key or authentication token.
