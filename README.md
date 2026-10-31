# Crypto API Directory

A curated starting point for crypto market-data, exchange, and blockchain APIs. This directory links to provider documentation and highlights the details developers should verify before building. API plans, endpoints, terms, and limits can change; confirm them with the provider before use.

## Market data

| Provider | Official docs | Use cases |
| --- | --- | --- |
| [CoinGecko](https://www.coingecko.com/en/api/) | [API documentation](https://docs.coingecko.com/) | Crypto asset metadata, prices, market data, and historical endpoints. Review attribution, plan terms, and endpoint-specific rate limits. |

## Exchange APIs

| Provider | Official docs | Use cases |
| --- | --- | --- |
| [Coinbase Advanced](https://www.coinbase.com/developer-platform/products/advanced-trade-api) | [Developer documentation](https://docs.cdp.coinbase.com/advanced-trade/docs/welcome) | Exchange products, market data, and advanced trading endpoints. Confirm API permissions and supported features for your account. |
| [Kraken](https://www.kraken.com/features/api) | [API documentation](https://api.docs.kraken.tech/) | Spot and futures REST/WebSocket APIs and related developer resources. Check the relevant API family, authentication, and account permissions. |

## Blockchain explorers and indexed data

| Provider | Official docs | Use cases |
| --- | --- | --- |
| [Etherscan](https://etherscan.io/) | [API documentation](https://docs.etherscan.io/) | Ethereum and supported-chain account, transaction, contract, and token data. Verify supported chains, plan limits, and attribution terms. |

This is a starter directory, not a ranking. Provider names identify their own products; inclusion does not imply endorsement. Add more chains and providers only with current documentation links.

## Evaluate an API

For each listing, record:

- Data coverage, supported chains, assets, endpoints, and freshness
- REST, WebSocket, streaming, or other access methods; version and deprecation policy
- Authentication model, required scopes, key creation, rotation, and revocation steps
- Rate limits, quotas, pagination, usage metering, pricing, and overage terms
- Availability/status page, service-level commitments, incident history, and support channel
- Data licensing, redistribution rights, attribution requirements, and retention constraints
- Official SDKs and examples, with their maintenance status and repository links

## API key hygiene

- Never commit API keys, signing secrets, credentials, or `.env` files to a public repository.
- Use environment variables or a secrets manager; apply least-privilege scopes and IP restrictions when offered.
- Keep read-only and trading permissions separate. Avoid withdrawal permission for application keys unless a narrowly justified design requires it.
- Rotate and revoke exposed keys immediately using the provider's official account interface. Treat keys in Git history as exposed even after deleting the visible line.
- Add timeouts, retries with backoff, response validation, and safe handling of rate limits. Never assume an API response is complete or current.

## Inclusion criteria

1. Link to a provider-owned documentation page, not an affiliate landing page.
2. Describe use cases at a high level; avoid claims about uptime, accuracy, or “free” tiers without a dated source.
3. Cite plan, rate-limit, and licensing claims to the current official page and include a `Last checked` date.
4. Disclose commercial relationships. No paid rankings or referral codes.

## Contribute

Open a pull request with the provider's official docs, relevant product/API name, concise use cases, and date checked. Include corrections when docs move or an API is deprecated. Do not include working API keys or credentials in examples.

## Related projects

- [KryptoWatch profile](https://github.com/KryptoWatch)
- [Exchange directory](https://github.com/KryptoWatch/awesome-crypto-exchanges)
- [Swap directory](https://github.com/KryptoWatch/awesome-crypto-swaps)
- [Security toolkit](https://github.com/KryptoWatch/crypto-security-toolkit)

---

For developer reference only; not financial, legal, or security advice.


## Explore on Krypto.Watch

Visit the live [crypto developer and API resources](https://krypto.watch/developers) on [Krypto.Watch](https://krypto.watch/).
