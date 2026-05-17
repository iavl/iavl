<h1 align="center">👋 Hi, I'm <strong>Albert </strong></h1>

<p align="center">
  <strong>Senior Blockchain Engineer · Smart Contract Developer · Rollup / L2 Builder</strong>
</p>

<p align="center">
  <a href="https://github.com/iavl">
    <img src="https://img.shields.io/badge/Blockchain-EVM%20%7C%20-6f42c1?style=flat-square" />
  </a>
  <img src="https://img.shields.io/badge/Smart%20Contracts-Solidity%20%7C%20Rust+Anchor-orange?style=flat-square" />
</p>

---

## 🧑🏻‍💻 Summary

- 9+ years of **blockchain development experience**
- Expert in **EVM / Solidity** smart contract development and security
- Expert in **Solana programs (Rust + Anchor)**
- Expert in **Ethereum**, **Rollup architecture**, and **L2 systems**

---

## **Selected Projects**

### **Smart Contracts — EVM (Solidity)**

- **Orbal Contracts**
  Yield-aggregating ERC4626 Vault. After users deposit underlying assets into the Orbal main vault, an allocator distributes funds through adapters to external protocols such as Aave V3, Morpho Vault V1, Euler Vault, and Compound V3, rebalancing strategies for better yield. The system supports protocol-level fees and built-in risk controls including roles, caps, timelocks, and force deallocation.
  * GitHub: https://github.com/Neuralogy/orbal-contracts

- **RSS3 Network**
  Staking and settlement system for the RSS3 Network node ecosystem, covering staking, delegation, unstaking, withdrawal, epoch-based settlement, and slashing. Uses ERC-721 staking positions and supports NFT merge, on-chain SVG metadata generation, supporting security-scanning tooling, and Foundry / Fork tests.
  * Mainnet: https://scan.rss3.io/address/0x28F14d917fddbA0c1f2923C406952478DfDA5578
  * GitHub: https://github.com/RSS3-Network/RSS3-Network-Contracts

- **Crossbell Protocol**
  Protocol contracts for social data ownership, supporting on-chain identity, content assetization, social graph relationships, multiple link types such as ERC-721 / Address / URI / Note, and configurable LinkModule / MintModule extensions.
  * GitHub: https://github.com/Crossbell-Box/Crossbell-Contracts

- **Crossbell Bridge**
  Core bridge contracts for Crossbell, implementing deposit, withdrawal, validator multi-signature verification, and cross-chain confirmation between the EVM mainchain and the Crossbell network, with withdrawal limits, pause controls, and reentrancy protection.
  * GitHub: https://github.com/Crossbell-Box/crossbell-bridge-contracts

- **Crossbell xShop**
  Core NFT marketplace contracts for the Crossbell ecosystem, covering asks, bids, matching, royalty payments, and ERC-777-based payment flows.
  * GitHub: https://github.com/Crossbell-Box/xShop-contracts

- **RSS3 Pre-Staking**
  Pre-staking product launched before the RSS3 mainnet, supporting ERC-20 staking across multiple lock-up periods (90 / 180 / 270 / 360 days), with each position unlocking rewards linearly over time.
  * Mainnet: https://etherscan.io/address/0x5301cbbedc048abac7e213184132cf982d593563
  * GitHub: https://github.com/NaturalSelectionLabs/Pre-Staking/tree/dividends

- **Folo — PowerToken**
  Utility token for content / feed use cases, built on OpenZeppelin upgradeable ERC-20 and extended with role-based permissions, non-transferable points, taxes, and feed-based tipping flows.
  * Mainnet: https://scan.rss3.io/address/0xE06Af68F0c9e819513a6CD083EF6848E76C28CD8
  * GitHub: https://github.com/RSSNext/follow-contracts

- **EVM Bonding Curve**
  Bonding-curve token issuance and liquidity migration mechanism on EVM, supporting customizable virtual reserves and price discovery, with automatic migration to Uniswap V2; the dynamic version supports multiple curve parameter sets.
  * Repo 1: https://github.com/iavl/bondingcurve-evm
  * Repo 2: https://github.com/iavl/dynamic-bonding-curve-contracts

### **Solana (Rust / Anchor)**

- **Smart Account**
  Anchor-based Passkey / WebAuthn smart account using **secp256r1** verification. Supports contact, program, and token-mint allowlists, with delegated execution of on-chain instructions under explicit constraints.
  * GitHub: https://github.com/iavl/smart-account-solana

- **Bonding Curve Launchpad**
  Solana bonding-curve issuance mechanism supporting automated token issuance and pricing, covering curve creation, buy / sell flows, parameter updates, and liquidity migration.
  * GitHub: https://github.com/iavl/bondingcurve-solana

### **Chain / Execution Layer (Go)**

- **RSS3 Chain**
  Modular L2 customization based on OP Stack, supporting RSS3 as the gas token and Alt-DA integration with NEAR DA / Celestia DA.
  * op-geth: https://github.com/RSS3-Network/op-geth
  * optimism / NEAR DA: https://github.com/RSS3-Network/optimism
  * optimism / Celestia DA: https://github.com/RSS3-Network/optimism/tree/feat/celestia-da

- **Crossbell op-geth**
  EVM execution-layer fork for the Crossbell chain, supporting free-gas transactions.
  * GitHub: https://github.com/iavl/crossbell-op-geth

### **Earlier public chains**

- **NetCloth Chain** · *Go, Cosmos SDK, EVM*
  BPoS public chain: full in-app EVM (state transition and interpreter), supporting smart contracts and governance-driven upgrades.
  * GitHub: https://github.com/netcloth/netcloth-chain

---

<p align="center">
  <i>Building secure, scalable, and elegant blockchain systems.</i>
</p>
