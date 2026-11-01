# Stellar

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Stellar is an open-source, decentralized blockchain network designed for fast, low-cost cross-border payments and asset issuance. The Stellar Development Foundation (SDF) maintains the core protocol and the Horizon REST API, which provides HTTP access to ledger data including accounts, transactions, operations, effects, offers, trades, claimable balances, and liquidity pools. Horizon is the primary data gateway for the Stellar network, re-serving ledger data in a developer-friendly format. The network supports native XLM transfers, custom asset issuance, a built-in decentralized exchange (DEX), Soroban smart contracts, and anchor integrations for fiat on/off-ramps. Authentication is not required for read queries; transaction submission requires signing with a Stellar keypair.

**Areas:** Blockchain · Cryptocurrency · Decentralized Exchange · Ledger · Payments · Smart Contracts · Web3 · Stellar · Cross-Border Payments

## Stellar on APIs.io

Everything profiled for Stellar is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/stellar/](https://apis.io/providers/stellar/)** — or go straight to one of the APIs or properties below.

### APIs (33)

- [Stellar RPC API](https://apis.io/apis/stellar/stellar-rpc-api/) — The Stellar RPC API (formerly Soroban RPC) is a JSON-RPC interface for interacting with Soroban smart contracts deployed on the Stellar network. It supports…
- [Stellar Accounts API](https://apis.io/apis/stellar/stellar-accounts-api/) — Users interact with the Stellar network through accounts. Everything else in the ledger—assets, offers, trustlines, etc. are owned by accounts, and accounts…
- [Stellar Admin API](https://apis.io/apis/stellar/stellar-admin-api/) — The Admin API oversees the management of tenants within the system, facilitating tasks such as provisioning new tenants, updating their information, and…
- [Stellar API Keys API](https://apis.io/apis/stellar/stellar-api-keys-api/) — API Keys functionality allows to create access key with granular permissions and resource management.
- [Stellar Assets API](https://apis.io/apis/stellar/stellar-assets-api/) — Assets are representations of value issued on the Stellar network. An asset consists of a type, code, and issuer.
- [Stellar Authentication API](https://apis.io/apis/stellar/stellar-authentication-api/) — Authentication controls the log in/log out process for all SDP users, as well as the token refresh process. Authentication uses a JWT approach signed with…
- [Stellar Balances API](https://apis.io/apis/stellar/stellar-balances-api/) — Endpoints related to balances. A balance is an amount of a particular asset held by an organization, tenant, or account.
- [Stellar Bridge Integration API](https://apis.io/apis/stellar/stellar-bridge-integration-api/) — Bridge integration endpoints for connecting organizations with Bridge services. **Integration Flow:** 1. Organization opts into Bridge (OPTED_IN status) 2.…
- [Stellar Claimable Balances API](https://apis.io/apis/stellar/stellar-claimable-balances-api/) — A Claimable Balance represents the transfer of ownership of some amount of an asset. Claimable balances provide a mechanism for setting up a payment which…
- [Stellar Customers API](https://apis.io/apis/stellar/stellar-customers-api/) — [SEP-12](https://github.com/stellar/stellar-protocol/blob/master/ecosystem/sep-0012.md) requests made from client applications.
- [Stellar Disbursements API](https://apis.io/apis/stellar/stellar-disbursements-api/) — Endpoints related to disbursements. A disbursement is a group of payments sent to multiple individuals at once. An SDP user with the appropriate role…
- [Stellar Effects API](https://apis.io/apis/stellar/stellar-effects-api/) — Effects represent specific changes that occur in the ledger as a result of successful operations, but are not necessarily directly reflected in the ledger…
- [Stellar Events API](https://apis.io/apis/stellar/stellar-events-api/) — The Events API from Stellar — 1 operation(s) for events.
- [Stellar Exports API](https://apis.io/apis/stellar/stellar-exports-api/) — The Exports API from Stellar — 3 operation(s) for exports.
- [Stellar Fee Stats API](https://apis.io/apis/stellar/stellar-fee-stats-api/) — Fee stats are used to predict what fee to set for a transaction before submitting it to the network.
- [Stellar Ledgers API](https://apis.io/apis/stellar/stellar-ledgers-api/) — Each ledger stores the state of the network at a point in time and contains all the changes - transactions, operations, effects, etc. - to that state.
- [Stellar Liquidity Pools API](https://apis.io/apis/stellar/stellar-liquidity-pools-api/) — Liquidity Pools provide a simple, non-interactive way to trade large amounts of capital and enable high volumes of trading.
- [Stellar Offers API](https://apis.io/apis/stellar/stellar-offers-api/) — Offers are statements about how much of an asset an account wants to buy or sell.
- [Stellar Operations API](https://apis.io/apis/stellar/stellar-operations-api/) — Operations are objects that represent a desired change to the ledger: payments, offers to exchange currency, changes made to account options, etc.…
- [Stellar Order Books API](https://apis.io/apis/stellar/stellar-order-books-api/) — An order book is a collections of offers for a specific pair of assets.
- [Stellar Organization API](https://apis.io/apis/stellar/stellar-organization-api/) — Organization endpoints manage the process of getting and updating organizational profile information. The organization's profile has basic information set…
- [Stellar Paths API](https://apis.io/apis/stellar/stellar-paths-api/) — Paths provide information about potential path payments. A path can be used to populate the necessary fields for a path payment operation.
- [Stellar Payments API](https://apis.io/apis/stellar/stellar-payments-api/) — Endpoints related to payments. An SDP payment is an individual payment from an organization to a receiver. Each payment is part of a disbursement and occurs…
- [Stellar Profile API](https://apis.io/apis/stellar/stellar-profile-api/) — Profiles endpoints manage the process of getting and updating individual profile information. Profile information is set when the account is created and can…
- [Stellar Rates API](https://apis.io/apis/stellar/stellar-rates-api/) — Requests containing data that can be used to provide exchange rates between on & off-chain assets.
- [Stellar Receivers API](https://apis.io/apis/stellar/stellar-receivers-api/) — Endpoints related to receivers. A receiver is an individual receiving a payment in a disbursement. The receiver is tracked by phone number to reduce the…
- [Stellar Registration API](https://apis.io/apis/stellar/stellar-registration-api/) — The registration endpoints guide the process for a receiver to verify their identity and link their wallet address to an SDP. The registration process only…
- [Stellar Statistics API](https://apis.io/apis/stellar/stellar-statistics-api/) — Statistics endpoints return general aggregated data per organization, as well as disbursement-specific metrics. SDP users can use this data to monitor their…
- [Stellar Trade Aggregations API](https://apis.io/apis/stellar/stellar-trade-aggregations-api/) — A trade aggregation represents aggregated statistics on an asset pair (base and counter) for a specific time period. Trade aggregations are useful to…
- [Stellar Trades API](https://apis.io/apis/stellar/stellar-trades-api/) — When an offer is fully or partially fulfilled, a trade happens. Trades can also be caused by successful path payments, because path payments involve…
- [Stellar Transactions API](https://apis.io/apis/stellar/stellar-transactions-api/) — Transactions initiated by client applications via SEP APIs
- [Stellar Users API](https://apis.io/apis/stellar/stellar-users-api/) — The users endpoints facilitate the creation of new SDP users - including setting the appropriate role, sending an email invitation, and activating a user -…
- [Stellar Wallets API](https://apis.io/apis/stellar/stellar-wallets-api/) — The Wallets API from Stellar — 2 operation(s) for wallets.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Stellar Agentic Access](https://apis.io/agentic-access/stellar/stellar-agentic-access/)

#### JSON Schema (122)

The data models the API reads and writes.

- [Account](https://apis.io/schemas/stellar/stellar-horizon-account/)
- [AccountMerge](https://apis.io/schemas/stellar/stellar-horizon-accountmerge/)
- [address](https://apis.io/schemas/stellar/stellar-horizon-address/)
- [Asset](https://apis.io/schemas/stellar/stellar-horizon-asset/)
- [asset_balance_change](https://apis.io/schemas/stellar/stellar-horizon-asset_balance_change/)
- [AsyncTransactionSubmissionResponse](https://apis.io/schemas/stellar/stellar-horizon-asynctransactionsubmissionresponse/)
- [BalanceLineAsset](https://apis.io/schemas/stellar/stellar-horizon-balancelineasset/)
- [BalanceLineLiquidityPool](https://apis.io/schemas/stellar/stellar-horizon-balancelineliquiditypool/)
- [BalanceLineNative](https://apis.io/schemas/stellar/stellar-horizon-balancelinenative/)
- [BaseAsset](https://apis.io/schemas/stellar/stellar-horizon-baseasset/)
- [BaseFeeDistribution](https://apis.io/schemas/stellar/stellar-horizon-basefeedistribution/)
- [ChargedFeeDistribution](https://apis.io/schemas/stellar/stellar-horizon-chargedfeedistribution/)
- [ClaimableBalance](https://apis.io/schemas/stellar/stellar-horizon-claimablebalance/)
- [ClaimableBalances](https://apis.io/schemas/stellar/stellar-horizon-claimablebalances/)
- [CreateAccount](https://apis.io/schemas/stellar/stellar-horizon-createaccount/)
- [currency](https://apis.io/schemas/stellar/stellar-horizon-currency/)
- [Effect](https://apis.io/schemas/stellar/stellar-horizon-effect/)
- [FeeBumpTransaction](https://apis.io/schemas/stellar/stellar-horizon-feebumptransaction/)
- [FeeStats](https://apis.io/schemas/stellar/stellar-horizon-feestats/)
- [flags](https://apis.io/schemas/stellar/stellar-horizon-flags/)
- [hash](https://apis.io/schemas/stellar/stellar-horizon-hash/)
- [host_function_parameter](https://apis.io/schemas/stellar/stellar-horizon-host_function_parameter/)
- [id](https://apis.io/schemas/stellar/stellar-horizon-id/)
- [InnerTransaction](https://apis.io/schemas/stellar/stellar-horizon-innertransaction/)
- [InvokeHostFunction](https://apis.io/schemas/stellar/stellar-horizon-invokehostfunction/)
- …and 97 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Stellar Context](https://apis.io/jsonld/stellar/stellar-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Stellar Vocabulary](https://apis.io/vocabularies/stellar/stellar-vocabulary/)

#### Examples (52)

Example requests and responses.

- [Stellar Horizon Cbretrieverelatedoperations 200](https://apis.io/examples/stellar/stellar-horizon-cbretrieverelatedoperations-200/)
- [Stellar Horizon Cbretrieverelatedtransactions 200](https://apis.io/examples/stellar/stellar-horizon-cbretrieverelatedtransactions-200/)
- [Stellar Horizon Getalloffers 200](https://apis.io/examples/stellar/stellar-horizon-getalloffers-200/)
- [Stellar Horizon Getalltrades 200](https://apis.io/examples/stellar/stellar-horizon-getalltrades-200/)
- [Stellar Horizon Getdatabyaccountid 200](https://apis.io/examples/stellar/stellar-horizon-getdatabyaccountid-200/)
- [Stellar Horizon Geteffectsbyaccountid 200](https://apis.io/examples/stellar/stellar-horizon-geteffectsbyaccountid-200/)
- [Stellar Horizon Getofferbyofferid 200](https://apis.io/examples/stellar/stellar-horizon-getofferbyofferid-200/)
- [Stellar Horizon Getoffersbyaccountid 200](https://apis.io/examples/stellar/stellar-horizon-getoffersbyaccountid-200/)
- [Stellar Horizon Getoperationsbyaccountid 200](https://apis.io/examples/stellar/stellar-horizon-getoperationsbyaccountid-200/)
- [Stellar Horizon Getpaymentsbyaccountid 200](https://apis.io/examples/stellar/stellar-horizon-getpaymentsbyaccountid-200/)
- [Stellar Horizon Gettradesbyaccountid 200](https://apis.io/examples/stellar/stellar-horizon-gettradesbyaccountid-200/)
- [Stellar Horizon Gettradesbyofferid 200](https://apis.io/examples/stellar/stellar-horizon-gettradesbyofferid-200/)
- [Stellar Horizon Gettransactionsbyaccountid 200](https://apis.io/examples/stellar/stellar-horizon-gettransactionsbyaccountid-200/)
- [Stellar Horizon Listallaccounts 200](https://apis.io/examples/stellar/stellar-horizon-listallaccounts-200/)
- [Stellar Horizon Listallassets 200](https://apis.io/examples/stellar/stellar-horizon-listallassets-200/)
- [Stellar Horizon Listallclaimablebalances 200](https://apis.io/examples/stellar/stellar-horizon-listallclaimablebalances-200/)
- [Stellar Horizon Listalleffects 200](https://apis.io/examples/stellar/stellar-horizon-listalleffects-200/)
- [Stellar Horizon Listallledgers 200](https://apis.io/examples/stellar/stellar-horizon-listallledgers-200/)
- [Stellar Horizon Listalloperations 200](https://apis.io/examples/stellar/stellar-horizon-listalloperations-200/)
- [Stellar Horizon Listallpayments 200](https://apis.io/examples/stellar/stellar-horizon-listallpayments-200/)
- [Stellar Horizon Listalltransactions 200](https://apis.io/examples/stellar/stellar-horizon-listalltransactions-200/)
- [Stellar Horizon Listliquiditypools 200](https://apis.io/examples/stellar/stellar-horizon-listliquiditypools-200/)
- [Stellar Horizon Liststrictreceivepaymentpaths 200](https://apis.io/examples/stellar/stellar-horizon-liststrictreceivepaymentpaths-200/)
- [Stellar Horizon Liststrictsendpaymentpaths 200](https://apis.io/examples/stellar/stellar-horizon-liststrictsendpaymentpaths-200/)
- [Stellar Horizon Listtradeaggregations 200](https://apis.io/examples/stellar/stellar-horizon-listtradeaggregations-200/)
- …and 27 more published on APIs.io

#### Collections (32)

Postman and Open Collection request collections.

- [Platform Server Accounts API](https://apis.io/collections/stellar/open-stellar-accounts-api/)
- [Platform Server Accounts Admin API](https://apis.io/collections/stellar/open-stellar-admin-api/)
- [Platform Server Accounts API Keys API](https://apis.io/collections/stellar/open-stellar-api-keys-api/)
- [Platform Server Accounts Assets API](https://apis.io/collections/stellar/open-stellar-assets-api/)
- [Platform Server Accounts Authentication API](https://apis.io/collections/stellar/open-stellar-authentication-api/)
- [Platform Server Accounts Balances API](https://apis.io/collections/stellar/open-stellar-balances-api/)
- [Platform Server Accounts Bridge Integration API](https://apis.io/collections/stellar/open-stellar-bridge-integration-api/)
- [Platform Server Accounts Claimable Balances API](https://apis.io/collections/stellar/open-stellar-claimable-balances-api/)
- [Platform Server Accounts Customers API](https://apis.io/collections/stellar/open-stellar-customers-api/)
- [Platform Server Accounts Disbursements API](https://apis.io/collections/stellar/open-stellar-disbursements-api/)
- [Platform Server Accounts Effects API](https://apis.io/collections/stellar/open-stellar-effects-api/)
- [Platform Server Accounts Events API](https://apis.io/collections/stellar/open-stellar-events-api/)
- [Platform Server Accounts Exports API](https://apis.io/collections/stellar/open-stellar-exports-api/)
- [Platform Server Accounts Fee Stats API](https://apis.io/collections/stellar/open-stellar-fee-stats-api/)
- [Platform Server Accounts Ledgers API](https://apis.io/collections/stellar/open-stellar-ledgers-api/)
- [Platform Server Accounts Liquidity Pools API](https://apis.io/collections/stellar/open-stellar-liquidity-pools-api/)
- [Platform Server Accounts Offers API](https://apis.io/collections/stellar/open-stellar-offers-api/)
- [Platform Server Accounts Operations API](https://apis.io/collections/stellar/open-stellar-operations-api/)
- [Platform Server Accounts Order Books API](https://apis.io/collections/stellar/open-stellar-order-books-api/)
- [Platform Server Accounts Organization API](https://apis.io/collections/stellar/open-stellar-organization-api/)
- [Platform Server Accounts Paths API](https://apis.io/collections/stellar/open-stellar-paths-api/)
- [Platform Server Accounts Payments API](https://apis.io/collections/stellar/open-stellar-payments-api/)
- [Platform Server Accounts Profile API](https://apis.io/collections/stellar/open-stellar-profile-api/)
- [Platform Server Accounts Rates API](https://apis.io/collections/stellar/open-stellar-rates-api/)
- [Platform Server Accounts Receivers API](https://apis.io/collections/stellar/open-stellar-receivers-api/)
- …and 7 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Stellar — jsonschema rules](https://apis.io/rules/stellar/stellar-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Stellar Authentication](https://apis.io/security/stellar/stellar-authentication/)
- [Stellar Domain Security](https://apis.io/security/stellar/stellar-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Stellar Plans Pricing](https://apis.io/plans/stellar/stellar-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Stellar Rate Limits](https://apis.io/rate-limits/stellar/stellar-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Stellar Finops](https://apis.io/finops/stellar/stellar-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.stellar.org/)
- [Documentation](https://developers.stellar.org/docs)
- [Blog](https://stellar.org/blog)
- [GitHub](https://github.com/stellar)
- [Status](https://status.stellar.org)

## API Evangelist rating

**Kin Score 41.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 55.8 |
| Contract governance | 23.5 |
| Operational transparency | 26.3 |
| Developer ergonomics | 42.9 |
| Access clarity | 7.9 |

**Agent readiness 29.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 15.2** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/stellar/](https://apis.io/providers/stellar/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Stellar: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/stellar/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
