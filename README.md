# Awesome-Blockchain-Analytics

## Top Blockchain Analytics Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Transaction Monitoring, Address Attribution & On-Chain Intelligence*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Blockchain Analytics**. These tools analyze on-chain data to trace fund flows, attribute addresses to real-world entities, detect illicit activity, and provide market intelligence for compliance teams, investigators, traders, and researchers.



**Examples** include Chainalysis, TRM Labs, Elliptic, Nansen, Arkham, Dune, Bitquery, Flipside, Covalent, and Glassnode (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom forensics, and transparent data pipelines — ideal for researchers, compliance teams, and developers building vendor-independent blockchain intelligence. The open-source ecosystem is anchored by **GraphSense** (cryptoasset forensics) and **BRK** (Bitcoin analytics), with strong coverage in transaction monitoring engines, indexing frameworks, and data warehouses.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Chainalysis](https://www.chainalysis.com/)**  

  The dominant blockchain intelligence platform for compliance and investigations. Provides transaction monitoring, sanctions screening, entity attribution, and Reactor investigation software. Widely used by government agencies and financial institutions.



- **[TRM Labs](https://www.trmlabs.com/)**  

  Blockchain intelligence platform for risk management, compliance, and investigations. Offers transaction monitoring, wallet screening, and cross-chain forensics.



- **[Elliptic](https://www.elliptic.co/)**  

  Cryptoasset risk management platform providing transaction monitoring, wallet screening, and forensics across major blockchains. One of the earliest entrants in the space with extensive entity attribution databases .



- **[Nansen](https://www.nansen.ai/)**  

  On-chain analytics platform with wallet labels and Smart Money tracking. Provides dashboards for DeFi activity, NFT markets, and token flows .



- **[Arkham](https://www.arkhamintelligence.com/)**  

  Blockchain intelligence platform focusing on deanonymizing entities and providing real-time intelligence on wallet activity.



- **[Dune](https://dune.com/)**  

  Blockchain analytics platform with SQL interface for querying on-chain data. Enables custom dashboards and community-shared queries without requiring indexing infrastructure .



- **[Bitquery](https://bitquery.io/)**  

  Blockchain data platform providing APIs for on-chain data across multiple chains with GraphQL support.



- **[Flipside](https://flipsidecrypto.xyz/)**  

  Blockchain analytics platform with SQL interface, similar to Dune, focusing on community-driven analytics and data science bounties .



- **[Covalent](https://www.covalenthq.com/)**  

  Unified blockchain data API providing structured data across 100+ chains for wallets, tokens, NFTs, and transactions.



- **[Glassnode](https://glassnode.com/)**  

  On-chain market intelligence platform providing 200+ metrics for Bitcoin, Ethereum, and other assets, with a focus on investor and trader insights .



## Open-Source GitHub Projects



- **[GraphSense](https://github.com/graphsense)**  

  The leading open-source cryptoasset analytics and forensics platform, developed through Austrian KIRAS projects and the EU Horizon TITANIUM project . Supports Bitcoin, Bitcoin Cash, Litecoin, Zcash, and Ethereum. Provides address- and entity-based transaction graphs, anomaly detection, and visualization for law enforcement, compliance, and research. Uses open-source components throughout for maximum transparency and control. Designed for coordinated national and European-level investigations .



- **[BRK (Bitcoin Research Kit)](https://github.com/bitcoinresearchkit/brk)**  

  High-performance open-source toolchain for extracting, computing, and visualizing data from a Bitcoin Core node. Positioned as a free alternative to Glassnode, mempool.space, and electrs in one package . Provides a public API and website with no authentication or rate limits, an MCP bridge for LLM access, CLI for self-hosting, and Rust crates for developers. Built for accessibility regardless of budget or background .



- **[ofi-chain-forensics](https://github.com/Ciprian-LocalPulse/ofi-chain-forensics-en)**  

  Open-source Python library for blockchain fraud and money-laundering detection through transaction graph analysis. MIT licensed with no account, API key, or usage limits . Implements established heuristics from research literature: address clustering via Common-Input-Ownership, change-address detection, suspicious pattern detectors (peeling chain, fan-out, fan-in, rapid pass-through), and explainable risk scoring where every point comes with a natural-language explanation . Explicitly designed as a complement to commercial tools like Chainalysis and Elliptic for independent researchers, NGOs, and investigative journalists .



- **[Marble](https://github.com/checkmarble/marble)**  

  Open-source real-time decision engine for fraud and AML, used by 100+ fintechs, banks, and crypto exchanges in 15+ countries . Provides transaction monitoring, customer and company screening against sanctions/PEP/adverse media lists, continuous monitoring, investigation suite with unified case manager, AI automation for rule building and investigation, and audit trail . Flexible architecture connects to any internal system or third-party data provider. Free self-hosted option with enterprise features available .



- **[Chainslake](https://chainslake.com/)**  

  Self-hosted blockchain data warehouse enabling on-premise analytics stacks for on-chain data. Positions as a Dune Analytics alternative for local SQL querying . Built on HDFS, Apache Spark, Delta Lake, Hive Metastore, Trino, Airflow, and Metabase — fully containerized with Docker . Supports multi-chain EVM pipelines with AI Agent Team for automated pipeline lifecycle management from requirements through dashboard creation .



- **[HyperIndex (Envio)](https://github.com/enviodev/hyperindex)**  

  Ultra-fast multichain blockchain indexer with independently benchmarked performance. HyperSync data engine delivers up to 2000x faster data access than traditional RPC, with 25,000+ events per second historical backfills . Index EVM, SVM, and Fuel chains from a single indexer. Auto-generates indexers from contract addresses or ABIs. Powers production applications including v4.xyz (Uniswap V4 analytics across 10 chains), Stable Volume, Liqo, and Oracle Wars .



- **[Ape Wisdom](https://github.com/apewisdom/apewisdom)**  

  Open-source alternative to Arkham and Nansen for wallet tracking and smart money analysis (early-stage, limited documentation).



- **[Ethernal](https://github.com/tryethernal/ethernal)**  

  Self-hostable open-source block explorer for any EVM chain with API and UI hooks for faucets, DEX widgets, custom post-processing, NFT galleries, and verification flows .



- **[Blockscout](https://github.com/blockscout/blockscout)**  

  Open-source, self-hostable EVM block explorer providing contract verification, APIs, and developer tools for chains and rollups .



- **[Otterscan](https://github.com/otterscan/otterscan)**  

  Ultra-fast local Ethereum block explorer built on Erigon for EVM chains .



- **[TrueBlocks](https://github.com/TrueBlocks/trueblocks-core)**  

  Local-first tool for improving access to blockchain data for EVM chains, particularly Ethereum mainnet, while remaining entirely local .



- **[DipDup](https://github.com/dipdup-io/dipdup)**  

  Python framework for building selective smart contract indexers with faster indexing times and reduced API load .



- **[Ponder](https://github.com/ponder-sh/ponder)**  

  Open-source framework for blockchain application backends and indexing .



- **[SubQuery](https://github.com/subquery/subql)**  

  Open-source data indexer providing custom APIs for web3 projects across supported chains .



### Additional Strong Open-Source Options



- **Shovel** — Ethereum to Postgres indexer for structured on-chain data storage .

- **Cryo** — CLI tool for extracting blockchain data to parquet, CSV, JSON, or Python dataframes .

- **Spice** — Client for extracting data from the Dune Analytics API .

- **Paradigm Data Portal** — Open-source crypto datasets collection for researchers and tool builders .

- **Flair** — Reusable indexing primitives with fault-tolerant RPC ingestors, custom processors, and re-org aware database integrations .

- **Sourcify** — Decentralized open-source smart contract verification service .

- **Blobscan** — Explorer and API for EIP-4844 blobs with decoding, analytics, and deployment charts .



**Frameworks for building custom blockchain analytics solutions**: Combine **GraphSense** for forensic-grade entity-based transaction graphs across major chains . Use **BRK** for self-hosted Bitcoin analytics with API, CLI, and LLM access . Integrate **ofi-chain-forensics** for transparent, explainable AML risk scoring from transaction graph heuristics . Deploy **Marble** for real-time transaction monitoring and case investigation workflows . Build **Chainslake** for a full on-premise Dune-like SQL analytics stack . Use **HyperIndex** for high-performance multichain indexing powering custom dashboards and applications . Note that true enterprise blockchain analytics with comprehensive entity attribution databases, cross-chain tracing, and regulatory-grade compliance reporting remains primarily commercial territory; open-source stacks provide strong forensic foundations, AML engines, and indexing infrastructure that require integration for complete intelligence platforms.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Blockchain analytics tools must comply with applicable regulations (AML/CFT, sanctions, data privacy) and legal requirements for surveillance and investigation.

- Self-hosted open-source solutions require proper infrastructure, blockchain node access, and ongoing maintenance. Risk scores are prioritization tools for human analysts, not legal proof of fraud .

- The open-source ecosystem provides strong forensic foundations, AML engines, and indexing infrastructure, but comprehensive entity attribution and cross-chain intelligence remain primarily commercial offerings.



---



**Made for compliance analysts, investigators, researchers, traders, and blockchain intelligence professionals.**  

Let's make blockchain analytics more open, transparent, and accessible.
