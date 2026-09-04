# Selected Projects

A collection of blockchain protocols, smart contracts, infrastructure, and experimental projects I've worked on over the years.

My work has covered **EVM / Solidity**, **DeFi protocols**, **Solana programs**, **Rollups / L2 infrastructure**, and **blockchain execution layers**.

---

## 🔷 EVM / Solidity

### [Orbal Contracts](https://github.com/Neuralogy/orbal-contracts)

Yield-aggregating ERC-4626 vault infrastructure.

The protocol allocates deposited assets across external lending and yield protocols including **Aave V3, Morpho, Euler, and Compound V3**, with built-in mechanisms for strategy rebalancing, fees, allocation caps, timelocks, and emergency deallocation.

**Focus:** Solidity · ERC-4626 · DeFi · Yield Aggregation · Protocol Security

---

### [RSS3 Network Contracts](https://github.com/RSS3-Network/RSS3-Network-Contracts)

Staking and settlement infrastructure for the RSS3 Network node ecosystem.

Supports staking, delegation, unstaking, withdrawals, epoch-based settlement, slashing, and ERC-721-based staking positions.

The system also includes NFT position merging and on-chain SVG metadata.

**Focus:** Solidity · Staking · Settlement · ERC-721 · Protocol Design

[Mainnet Contract](https://scan.rss3.io/address/0x28F14d917fddbA0c1f2923C406952478DfDA5578)

---

### [Crossbell Protocol](https://github.com/Crossbell-Box/Crossbell-Contracts)

Protocol infrastructure for decentralized social data ownership.

Supports on-chain identities, content ownership, social graph relationships, operator-signed transactions, and configurable modules for linking and minting.

**Focus:** Solidity · Social Protocols · NFTs · Modular Smart Contracts

---

### [Crossbell Bridge](https://github.com/Crossbell-Box/crossbell-bridge-contracts)

Bridge infrastructure connecting the EVM mainchain with the Crossbell network.

Implements deposits, withdrawals, validator multi-signature verification, cross-chain confirmation, withdrawal limits, pausing, and reentrancy protection.

**Focus:** Solidity · Bridges · Multisig Verification · Cross-chain Security

---

### [Crossbell xShop](https://github.com/Crossbell-Box/xShop-contracts)

NFT marketplace contracts for the Crossbell ecosystem.

Supports asks, bids, trade matching, royalty payments, and ERC-777-based payment flows.

**Focus:** Solidity · NFT Marketplace · ERC-777 · Trading

---

### [RSS3 Pre-Staking](https://github.com/NaturalSelectionLabs/Pre-Staking/tree/dividends)

Pre-staking protocol launched before the RSS3 mainnet.

Supports multiple staking periods with rewards unlocking linearly over time.

**Focus:** Solidity · Staking · Token Economics

[Mainnet Contract](https://etherscan.io/address/0x5301cbbedc048abac7e213184132cf982d593563)

---

### [Folo — PowerToken](https://github.com/RSSNext/follow-contracts)

Upgradeable ERC-20 utility-token infrastructure for content and feed-related use cases.

Includes role-based permissions, non-transferable points, taxation mechanisms, and feed-based tipping.

**Focus:** Solidity · Upgradeable Contracts · ERC-20 · Token Design

[Mainnet Contract](https://scan.rss3.io/address/0xE06Af68F0c9e819513a6CD083EF6848E76C28CD8)

---

### EVM Bonding Curves

Token issuance and liquidity-migration mechanisms based on bonding curves.

Supports configurable virtual reserves, dynamic curve parameters, price discovery, and automatic migration to Uniswap V2 liquidity.

* [Bonding Curve EVM](https://github.com/iavl/bondingcurve-evm)
* [Dynamic Bonding Curve Contracts](https://github.com/iavl/dynamic-bonding-curve-contracts)

**Focus:** Solidity · AMMs · Bonding Curves · Token Launches · DeFi

---

## 🟣 Solana / Rust / Anchor

### [Smart Account](https://github.com/iavl/smart-account-solana)

Passkey / WebAuthn smart account implemented with Anchor.

Uses **secp256r1** signature verification and supports allowlists for contacts, programs, and token mints, together with constrained delegated execution.

**Focus:** Rust · Anchor · Smart Accounts · Passkeys · WebAuthn · secp256r1

---

### [Bonding Curve Launchpad](https://github.com/iavl/bondingcurve-solana)

Solana token-launch infrastructure based on bonding-curve pricing.

Supports curve creation, token purchases and sales, parameter updates, and liquidity migration.

**Focus:** Rust · Anchor · Bonding Curves · Token Launchpad · DeFi

---

## 🔴 Rollups / L2 / Execution Layer

### [RSS3 Chain](https://github.com/RSS3-Network/op-geth)

Customized L2 infrastructure built on the **OP Stack**.

Work includes support for RSS3 as the native gas token and integration with alternative data-availability systems.

Repositories:

* [op-geth](https://github.com/RSS3-Network/op-geth)
* [Optimism / NEAR DA](https://github.com/RSS3-Network/optimism)
* [Optimism / Celestia DA](https://github.com/RSS3-Network/optimism/tree/feat/celestia-da)

**Focus:** Go · OP Stack · Rollups · Alt-DA · Execution Layer

---

### [Crossbell op-geth](https://github.com/iavl/crossbell-op-geth)

Customized EVM execution layer for the Crossbell blockchain.

Includes developer allowlists, free-gas transaction support, and state-migration mechanisms used during chain upgrades and launches.

**Focus:** Go · EVM · Geth · Execution Layer · State Migration

---

## ⛓️ Earlier Blockchain Work

### [NetCloth Chain](https://github.com/netcloth/netcloth-chain)

BPoS public blockchain built with **Go, Cosmos SDK, and EVM**.

Includes an integrated EVM execution environment supporting smart contracts together with governance-driven protocol upgrades.

**Focus:** Go · Cosmos SDK · EVM · Consensus · Public Chain

---
