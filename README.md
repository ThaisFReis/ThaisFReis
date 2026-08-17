# Thais Reis

Full-stack protocol engineer. I write the contract in Rust, the API behind it, the interface on top and the pipeline that puts it in production.

CTO at Plina Finance · sole engineer at [Yalla](https://yallaeveryday.com) · founder of [Karn](https://github.com/ThaisFReis/karn-protocol)

Rio de Janeiro, Brazil · [dalekthai.xyz](https://dalekthai.xyz) · [LinkedIn](https://www.linkedin.com/in/thaisfreis) · reis.thaisf@gmail.com

---

## Now

**Plina Finance** — CTO since May 2026. On-chain infrastructure for the institutional tokenization of credit rights on Stellar. Tokenizing credit rights is a regulated problem before it is a technical one, so the architecture puts native authorization controls and regulated anchors at the center: asset issuance on Stellar, USDC/EURC and anchor flows, Soroban contracts, Node.js backend, React institutional front end.

**Yalla** — only engineer since March 2026, in production in Brazil. B2B ticketing where tickets are issued on Stellar and the transfer policy is written on-chain and immutable, so the rules a buyer agreed to outlive any change of mind on the platform side. Two upgradeable Soroban contracts with a minter allowlist and the admin and upgrade authorities kept deliberately disjoint; Express/Prisma API; Next.js producer panel; Mercado Pago and Stripe Connect; five GitHub Actions workflows and ten runbooks, including rollback and the cutover for upgrading a live contract. Everything but the mobile app.

**Karn** — founder since January 2026. Open-source governance protocol on Stellar where voting power follows contribution instead of capital: soulbound credentials plus Mana, a reputation score with linear decay, so influence has to be re-earned rather than accumulated and parked. Three Soroban contracts in Rust, 53 tests, five security findings resolved and documented, and a typed TypeScript SDK published on npm.

## Public code

| Repo | What it is |
| --- | --- |
| [karn-protocol](https://github.com/ThaisFReis/karn-protocol) | Governance contracts on Soroban: Valocracy, Governor, Treasury. Rust, MIT. [Security hardening notes](https://github.com/ThaisFReis/karn-protocol/blob/main/docs/SECURITY_HARDENING.md). |
| [@karn_lat/protocol-sdk](https://www.npmjs.com/package/@karn_lat/protocol-sdk) | Typed TS SDK for those contracts, multi-wallet (Freighter, Lobstr, xBull) with React hooks. |
| [velum](https://github.com/ThaisFReis/velum) | Holder-attested compliance for confidential tokens on Stellar: proving a position sits under a regulatory threshold without revealing the amount. Noir circuits. |
| [monad-moments](https://github.com/ThaisFReis/monad-moments) | One photo a day as an ERC-721, with the one-per-UTC-day limit enforced by the contract rather than the UI. |
| [mise](https://github.com/ThaisFReis/mise) | Multi-store analytics for restaurants, with model-generated recommendations over the store data. |

## Record

| | |
| --- | --- |
| Jul 2026 | Selected for the [Stellar Builder Summit](https://livecoins.com.br/brasil-recebe-encontro-global-da-stellar-para-desenvolver-nova-geracao-de-aplicacoes-blockchain/), São Paulo. ~100 builders, eight days, invited on the strength of Plina Finance. |
| Jun 2026 | Stellar Instaward for Plina Finance, through [Stellar 37°](https://livecoins.com.br/stellar-37-graus-chega-ao-rio-de-janeiro-com-premiacao-inicial-20-mil-em-usdc-para-startups/), the acceleration program NearX runs with the Stellar Development Foundation. |
| May 2026 | Prelúdio, Yalla's first event run end to end in production: 113 tickets across 8 lots, 98 people through the door, 257 of 269 bar vouchers redeemed, none expired. |
| Mar 2026 | 1st place, Monad Blitz Rio de Janeiro, with Monad Moments. |
| Feb 2026 | Karn Protocol open-sourced under MIT. |
| Oct 2025 | 1st place, Hackathon Nola, with Mise. |
| Aug 2025 | 1st place, Morro Makers, with Jaspr: a multi-tenant AI concierge for hotels, answering from each hotel's own data rather than inventing it. |

## Before

**Nola** (Oct 2025 – Jan 2026) — automated testing across React, Node.js and React Native with Jest, Vitest and Cypress, plus cross-stack debugging that cut crash rates.

**CAPGov** (Jun 2023 – Aug 2026) — undergraduate research in ETL. Pipelines in Python and SQL over large public datasets, a containerized environment that comes up in one command, and validation at ingest so a bad row is caught before someone cites it.

**Beplauze** (Jul 2023 – Mar 2025) — led the migration to microfrontends with Astro so each surface could ship without waiting on the rest, and built a 40+ component React library documented in Storybook.

## Stack

**Languages** — TypeScript, Rust, Python, SQL
**Chain** — Stellar, Soroban, Solidity, Noir, Privy, USDC/EURC
**Product** — React, Next.js, Astro, Node.js, Express, Prisma, PostgreSQL, Redis, GraphQL
**Delivery** — Docker, AWS ECS, GitHub Actions, Prometheus, Turborepo
**Testing** — Jest, Vitest, Cypress

I write the tests, the runbooks and the docs alongside the code, not afterwards. What I deliver has to run without me.

---

BSc in Mathematical and Earth Sciences, UFRJ. Portuguese and English.
