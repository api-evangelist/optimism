# Optimism

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

Optimism is an Ethereum Layer 2 scaling network and the originator of the OP Stack — an open-source, modular rollup framework that powers OP Mainnet and a growing Superchain of interoperable chains (Base, Mode, Zora, Worldchain, and others). Developers interact via standard Ethereum JSON-RPC, the Optimism (Viem-based) SDK, the canonical Optimism Bridge, OP Stack operator tooling (op-geth, op-node, op-deployer, op-batcher, op-proposer, op-challenger), and the Superchain Registry.

**Areas:** Layer 2 · Ethereum · OP Stack · Superchain · JSON-RPC · Rollup · Bridge · Optimism · Real-Time

## Optimism on APIs.io

Everything profiled for Optimism is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/optimism/](https://apis.io/providers/optimism/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [OP Mainnet JSON-RPC](https://apis.io/apis/optimism/mainnet-rpc/) — Public Ethereum JSON-RPC endpoint for OP Mainnet (chain ID 10). Supports standard eth_* methods plus Optimism extensions for L1 fee estimation, deposit…
- [OP Sepolia JSON-RPC](https://apis.io/apis/optimism/sepolia-rpc/) — Public Ethereum JSON-RPC endpoint for the OP Sepolia testnet (chain ID 11155420) used for development and integration testing.
- [Optimism Bridge (Standard Bridge)](https://apis.io/apis/optimism/bridge/) — Canonical cross-chain bridge for depositing and withdrawing ETH and ERC-20 tokens between Ethereum L1 and OP Mainnet, secured by the OP Stack StandardBridge…
- [OP Stack](https://apis.io/apis/optimism/op-stack/) — Open-source, modular Ethereum L2 rollup stack. The monorepo at github.com/ethereum-optimism/optimism contains op-geth (execution), op-node (consensus),…
- [Superchain Registry](https://apis.io/apis/optimism/superchain-registry/) — Source-of-truth index of chains that are part of the Optimism Superchain — genesis files, deployment addresses, RPC endpoints, explorers, and chain metadata…
- [Optimism SDK (Viem extension)](https://apis.io/apis/optimism/viem-sdk/) — Modern Optimism SDK exposed as a Viem extension (viem/op-stack) for L1<->L2 message tracking, deposit and withdrawal flows, fee estimation, and Superchain…
- [Supersim](https://apis.io/apis/optimism/supersim/) — Local Superchain simulator that spins up multiple OP Stack chains for developing and testing cross-chain interop messages (CrossL2Inbox /…
- [Optimism Etherscan](https://apis.io/apis/optimism/etherscan-explorer/) — Etherscan-family block explorer for OP Mainnet and OP Sepolia with REST API access for contracts, transactions, and addresses.
- [Optimism Blockscout](https://apis.io/apis/optimism/blockscout-explorer/) — Open-source Blockscout block explorer for OP Mainnet with REST and GraphQL APIs.
- [Optimism JSON-RPC API](https://apis.io/apis/optimism/optimism-json-rpc-api/) — Standard Ethereum JSON-RPC method invocation.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Optimism (OP Stack) WebSocket JSON-RPC API](https://apis.io/asyncapis/optimism/optimism-asyncapi/)

#### Event channels (5)

Individual events and webhooks the provider emits.

- [eth_subscribe.logs](https://apis.io/channels/optimism/eth-subscribe-logs/)
- [eth_subscribe.newHeads](https://apis.io/channels/optimism/eth-subscribe-newheads/)
- [eth_subscribe.newPendingTransactions](https://apis.io/channels/optimism/eth-subscribe-newpendingtransactions/)
- [eth_subscribe.syncing](https://apis.io/channels/optimism/eth-subscribe-syncing/)
- [eth_unsubscribe](https://apis.io/channels/optimism/eth-unsubscribe/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/optimism/](https://apis.io/graphqls/optimism/optimism-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [optimism](https://apis.io/servers/optimism/optimism/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Optimism Agentic Access](https://apis.io/agentic-access/optimism/optimism-agentic-access/)

#### Collections (2)

Postman and Open Collection request collections.

- [OP Mainnet JSON-RPC](https://apis.io/collections/optimism/open-optimism/)
- [OP Mainnet JSON-RPC API](https://apis.io/collections/optimism/open-optimism-json-rpc-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Optimism — asyncapi rules](https://apis.io/rules/optimism/optimism-asyncapi-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Optimism Domain Security](https://apis.io/security/optimism/optimism-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Optimism Plans Pricing](https://apis.io/plans/optimism/optimism-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Optimism Rate Limits](https://apis.io/rate-limits/optimism/optimism-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Optimism Finops](https://apis.io/finops/optimism/optimism-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.optimism.io)
- [Documentation](https://docs.optimism.io)
- [Blog](https://blog.oplabs.co)

## API Evangelist rating

**Kin Score 37.0** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 55.9 |
| Contract governance | 13.6 |
| Operational transparency | 36.8 |
| Developer ergonomics | 16.7 |
| Access clarity | 5.3 |

**Agent readiness 30.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 5.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/optimism/](https://apis.io/providers/optimism/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Optimism: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/optimism/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
