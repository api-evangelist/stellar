# Stellar (stellar)

Stellar is an open-source, decentralized blockchain network designed for fast, low-cost cross-border payments and asset issuance. The Stellar Development Foundation (SDF) maintains the core protocol and the Horizon REST API, which provides HTTP access to ledger data including accounts, transactions, operations, effects, offers, trades, claimable balances, and liquidity pools. Horizon is the primary data gateway for the Stellar network, re-serving ledger data in a developer-friendly format. The network supports native XLM transfers, custom asset issuance, a built-in decentralized exchange (DEX), Soroban smart contracts, and anchor integrations for fiat on/off-ramps. Authentication is not required for read queries; transaction submission requires signing with a Stellar keypair.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/stellar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stellar/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Blockchain
- Cryptocurrency
- Decentralized Exchange
- Ledger
- Payments
- Smart Contracts
- Web3

## Timestamps

- **Created:** 2026-06-14
- **Modified:** 2026-06-14

## APIs

### Stellar Horizon API

The Stellar Horizon API is an HTTP REST interface to the Stellar network providing developer-friendly access to accounts, transactions, operations, effects, ledgers, offers, trades, claimable balances, liquidity pools, assets, and order books. Available at https://horizon.stellar.org (mainnet) and https://horizon-testnet.stellar.org (testnet). No API key required for read-only queries.

- **Base URL:** https://horizon.stellar.org
- **Human URL:** https://developers.stellar.org/docs/data/apis/horizon

### Stellar RPC API

The Stellar RPC API is a JSON-RPC 2.0 interface for interacting with Soroban smart contracts on the Stellar network. It supports simulating and submitting contract invocations, reading contract state, and streaming network events.

- **Base URL:** https://soroban-testnet.stellar.org
- **Human URL:** https://developers.stellar.org/docs/data/rpc

## Common Resources

- **Documentation:** https://developers.stellar.org/docs
- **Blog:** https://stellar.org/blog
- **Status Page:** https://status.stellar.org
- **GitHub:** https://github.com/stellar
- **SDKs:** https://developers.stellar.org/docs/tools/sdks/client-sdks
