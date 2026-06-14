# LBank

LBank is a global cryptocurrency exchange providing REST and WebSocket APIs for spot trading, ETF/leveraged token products, market data, order management, account information, and wallet operations.

## APIs

- **Spot Market REST API** - Public endpoints for ticker, depth, K-line, and trade history data
- **Spot Trading REST API** - Authenticated endpoints for order placement, cancellation, and queries
- **Wallet REST API** - Authenticated endpoints for deposits, withdrawals, and asset management
- **WebSocket Market Data API** - Real-time streaming for K-line, depth, trades, and ticker data
- **WebSocket Account and Order API** - Real-time push notifications for order fills and balance changes

## Base URLs

- `https://api.lbkex.com/`
- `https://www.lbkex.net/`
- `https://api.lbank.info/`

## WebSocket

- `wss://www.lbkex.net/ws/V2/`

## Authentication

Supports RSA (asymmetric) and HmacSHA256 (symmetric) signature schemes. API keys are obtained from the LBank account settings panel.

## Rate Limits

- Order create/cancel: 500 requests per 10 seconds
- All other endpoints: 200 requests per 10 seconds

## Documentation

- [API Documentation](https://www.lbank.com/en-US/docs/)
- [GitHub API Docs](https://github.com/LBank-exchange/lbank-official-api-docs)
