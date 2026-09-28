# Meet Rathod

**Full Stack Blockchain Engineer** · Rust · Move · TypeScript · Ahmedabad, India

Full Stack Blockchain Developer at Codezeros. I build Move smart contracts on Aptos and Supra, Rust services and SDKs for indexing blockchain events, and the Node.js, NestJS and Next.js applications that use them. Before blockchain, three years of MERN applications and Kafka-based event-driven backends.

[LinkedIn](https://linkedin.com/in/themeetrathod) · [Medium](https://medium.com/@meetrathod420) · [crates.io](https://crates.io/crates/supra_indexer_sdk) · [X](https://x.com/mrathod0507) · [Email](mailto:mrathod05@outlook.com)

<!-- TODO: add the portfolio link once the Vercel deployment is live. -->

---

## Open source

### [supra-indexer-sdk-rs](https://github.com/mrathod05/supra-indexer-sdk-rs) · [crates.io](https://crates.io/crates/supra_indexer_sdk)

Rust crate for building Supra blockchain indexers. Typed, generic event collectors poll the Supra RPC with cursor pagination, hand events to your own storage code, and checkpoint progress in PostgreSQL so indexing resumes after a restart. One tokio task per event type.

`Rust` `Tokio` `PostgreSQL` `Diesel` `Supra`

### [Exam-Sync](https://github.com/mrathod05/Exam-Sync)

Keeps one exam timer in sync across multiple backend instances. NestJS Socket.IO gateway, shared state in Redis guarded by Redlock, and Kafka fan-out so every instance relays changes to its own clients.

`NestJS` `Next.js` `Socket.IO` `Redis` `Kafka`

### [bloom-allowlist-guard](https://github.com/mrathod05/bloom-allowlist-guard)

Allowlist check service for NFT mints and airdrops that rejects ineligible wallets with an in-memory Bloom filter before querying the database.

`Rust`

### [supra-merkle-airdrop](https://github.com/mrathod05/supra-merkle-airdrop)

Merkle-tree allowlist and airdrop reference: off-chain logic in Rust, on-chain verification in Move on Supra.

`Rust` `Move` `Supra`

### [central-limit-order-book](https://github.com/mrathod05/central-limit-order-book)

Central limit order book with a Rust backend and a Next.js frontend.

`Rust` `TypeScript` `Next.js`

---

## Smart contracts

| Project | What it does | Stack |
| --- | --- | --- |
| [StakeHaven](https://github.com/mrathod05/StakeHaven) | Staking for a custom coin (HVC) with time-based rewards, a minimum stake period and an early-exit penalty; funds held by a resource account | Move, Aptos |
| [RewardVerse](https://github.com/mrathod05/RewardVerse) | Reward distribution for a custom coin (RVC) where minting, whitelisting and rewards need a 2-of-2 Aptos multisig | Move, Aptos |
| [aptos-move-utils](https://github.com/mrathod05/aptos-move-utils) | Utility library: printing, type conversion, vector and math helpers with overflow checks and tests | Move, Aptos |
| [sui_escrow_trust](https://github.com/mrathod05/sui_escrow_trust) | Generic asset escrow protocol with a capability-based reputation system | Move, Sui |
| [sui_pass](https://github.com/mrathod05/sui_pass) | Ticketing that enforces resale price caps with Kiosk transfer policies | Move, Sui |
| [VoteSpark](https://github.com/mrathod05/VoteSpark) · [demo](https://votespark.netlify.app) | Polling dApp: Anchor program for creating polls and voting, Next.js frontend, Phantom wallet | Rust, Anchor, Solana |
| [NextDApp](https://github.com/mrathod05/NextDApp) · [demo](https://nextdapp.netlify.app) | Next.js 15 starter for Solana dApps with Phantom wallet, NextAuth v5 and Tailwind CSS | TypeScript, Solana |

---

## Writing

Articles on Rust, distributed systems and PostgreSQL, on [Medium](https://medium.com/@meetrathod420):

- [Kill the N+1 Query](https://medium.com/@meetrathod420/kill-the-n-1-query-babff63fb0ae)
- [Stop Using Redis for Distributed Locks](https://medium.com/@meetrathod420/stop-using-redis-for-distributed-locks-012a2093dbfe)
- [Idempotency Over Exactly-Once](https://medium.com/@meetrathod420/idempotency-over-exactly-once-ddafde111cce)
- [Retry Smarter, Not Harder](https://medium.com/@meetrathod420/retry-smarter-not-harder-c7fff3d2e312)
- [Circuit Breakers in Rust: Protecting Your System from Cascading Failures](https://medium.com/@meetrathod420/circuit-breakers-in-rust-protecting-your-system-from-cascading-failures-a6c27f24c684)
- [Type-Safe Generic Event Collectors in Rust](https://medium.com/@meetrathod420/type-safe-generic-event-collectors-in-rust-fcf7d0531d79)

---

## Stack

| Area | Technologies |
| --- | --- |
| Languages | Rust, TypeScript, JavaScript, Move |
| Backend | Node.js, NestJS, Express, REST, GraphQL, Socket.IO, Kafka, microservices |
| Databases | PostgreSQL, MongoDB, Redis |
| Blockchain | Aptos, Supra, Sui, Solana (Anchor) |
| Frontend | React, Next.js, Redux, Tailwind CSS |
| Infrastructure | Docker, AWS, Git, Nx monorepos |
