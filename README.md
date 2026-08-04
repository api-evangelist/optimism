# Optimism (optimism)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Optimism is an Ethereum Layer 2 scaling network and the originator of the OP Stack — an open-source, modular rollup framework that powers OP Mainnet and a growing Superchain of interoperable chains (Base, Mode, Zora, Worldchain, and others). Developers interact via standard Ethereum JSON-RPC, the Optimism (Viem-based) SDK, the canonical Optimism Bridge, OP Stack operator tooling (op-geth, op-node, op-deployer, op-batcher, op-proposer, op-challenger), and the Superchain Registry.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/optimism/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/optimism/refs/heads/main/apis.yml)

## Tags

- Layer 2
- Ethereum
- OP Stack
- Superchain
- JSON-RPC
- Rollup
- Bridge

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### OP Mainnet JSON-RPC

Public Ethereum JSON-RPC endpoint for OP Mainnet (chain ID 10). Supports standard eth_* methods plus Optimism extensions for L1 fee estimation, deposit tracking, and withdrawal proving. Public endpoint is rate-limited and does not provide WebSockets; production teams front it with Alchemy, QuickNode, Infura, or self-hosted op-geth + op-node.

- **Human URL:** [https://docs.optimism.io/superchain/networks](https://docs.optimism.io/superchain/networks)
- **Base URL:** `https://mainnet.optimism.io`

#### Tags

- JSON-RPC
- Mainnet
- OP Mainnet

#### Properties

- [Documentation](https://docs.optimism.io/superchain/networks)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/optimism/refs/heads/main/asyncapi/optimism-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/optimism.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/optimism.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OP Sepolia JSON-RPC

Public Ethereum JSON-RPC endpoint for the OP Sepolia testnet (chain ID 11155420) used for development and integration testing.

- **Human URL:** [https://docs.optimism.io/superchain/networks](https://docs.optimism.io/superchain/networks)
- **Base URL:** `https://sepolia.optimism.io`

#### Tags

- JSON-RPC
- Testnet
- Sepolia

#### Properties

- [Documentation](https://docs.optimism.io/superchain/networks)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/optimism/refs/heads/main/asyncapi/optimism-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/optimism.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/optimism.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Optimism Bridge (Standard Bridge)

Canonical cross-chain bridge for depositing and withdrawing ETH and ERC-20 tokens between Ethereum L1 and OP Mainnet, secured by the OP Stack StandardBridge contracts. Available as a hosted app and via the Superbridge / Brid.gg interfaces for the full Superchain.

- **Human URL:** [https://app.optimism.io/bridge](https://app.optimism.io/bridge)
- **Base URL:** `https://app.optimism.io/bridge`

#### Tags

- Bridge
- Cross-Chain
- Canonical

#### Properties

- [Documentation](https://docs.optimism.io/app-developers/bridging/standard-bridge)
- [App](https://app.optimism.io/bridge)
- [Postman Collection](collections/optimism.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/optimism.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OP Stack

Open-source, modular Ethereum L2 rollup stack. The monorepo at github.com/ethereum-optimism/optimism contains op-geth (execution), op-node (consensus), op-batcher, op-proposer, op-challenger, op-deployer, op-validator, and fault-proof system used to launch and operate Superchain rollups.

- **Human URL:** [https://stack.optimism.io](https://stack.optimism.io)
- **Base URL:** `https://github.com/ethereum-optimism/optimism`

#### Tags

- OP Stack
- Rollup
- Open Source

#### Properties

- [Documentation](https://docs.optimism.io/stack/getting-started)
- [Repository](https://github.com/ethereum-optimism/optimism)
- [Specs](https://specs.optimism.io)
- [Postman Collection](collections/optimism.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/optimism.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Superchain Registry

Source-of-truth index of chains that are part of the Optimism Superchain — genesis files, deployment addresses, RPC endpoints, explorers, and chain metadata in machine-readable form.

- **Human URL:** [https://github.com/ethereum-optimism/superchain-registry](https://github.com/ethereum-optimism/superchain-registry)
- **Base URL:** `https://github.com/ethereum-optimism/superchain-registry`

#### Tags

- Superchain
- Registry
- Metadata

#### Properties

- [Repository](https://github.com/ethereum-optimism/superchain-registry)
- [Postman Collection](collections/optimism.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/optimism.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Optimism SDK (Viem extension)

Modern Optimism SDK exposed as a Viem extension (viem/op-stack) for L1<->L2 message tracking, deposit and withdrawal flows, fee estimation, and Superchain multi-chain helpers.

- **Human URL:** [https://docs.optimism.io/app-developers/tutorials/bridging/cross-dom-solidity](https://docs.optimism.io/app-developers/tutorials/bridging/cross-dom-solidity)
- **Base URL:** `https://viem.sh/op-stack`

#### Tags

- SDK
- TypeScript
- Viem
- Cross-Chain

#### Properties

- [Documentation](https://viem.sh/op-stack)
- [Postman Collection](collections/optimism.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/optimism.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Supersim

Local Superchain simulator that spins up multiple OP Stack chains for developing and testing cross-chain interop messages (CrossL2Inbox / L2ToL2CrossDomainMessenger) before mainnet rollout.

- **Human URL:** [https://docs.optimism.io/stack/interop/tools/supersim](https://docs.optimism.io/stack/interop/tools/supersim)
- **Base URL:** `https://github.com/ethereum-optimism/supersim`

#### Tags

- Supersim
- Interop
- Local Dev

#### Properties

- [Repository](https://github.com/ethereum-optimism/supersim)
- [Postman Collection](collections/optimism.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/optimism.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Optimism Etherscan

Etherscan-family block explorer for OP Mainnet and OP Sepolia with REST API access for contracts, transactions, and addresses.

- **Human URL:** [https://optimistic.etherscan.io](https://optimistic.etherscan.io)
- **Base URL:** `https://api-optimistic.etherscan.io/api`

#### Tags

- Block Explorer
- Etherscan
- API

#### Properties

- [Documentation](https://docs.optimism.etherscan.io)
- [Website](https://optimistic.etherscan.io)
- [Postman Collection](collections/optimism.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/optimism.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Optimism Blockscout

Open-source Blockscout block explorer for OP Mainnet with REST and GraphQL APIs.

- **Human URL:** [https://optimism.blockscout.com](https://optimism.blockscout.com)
- **Base URL:** `https://optimism.blockscout.com/api`

#### Tags

- Block Explorer
- Blockscout
- API

#### Properties

- [Website](https://optimism.blockscout.com)
- [Postman Collection](collections/optimism.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/optimism.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.optimism.io)
- [Documentation](https://docs.optimism.io)
- [Git Hub](https://github.com/ethereum-optimism)
- [Specs](https://specs.optimism.io)
- [Superchain Registry](https://github.com/ethereum-optimism/superchain-registry)
- [Governance](https://gov.optimism.io)
- [Status](https://status.optimism.io)
- [Twitter](https://x.com/Optimism)
- [Discord](https://discord.gg/optimism)
- [Blog](https://blog.oplabs.co)
- [L L Ms Txt](https://docs.optimism.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
