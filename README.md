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


## **Selected Projects (open source / on-chain verifiable)**

### **Smart contracts — EVM (Solidity)**

- **RSS3 Network**  
  On-chain lifecycle for indexer nodes (creation, deposits, unbonding, rewards, and slashing) and user stake/redeem with settlement.  
  * Core reward, slashing, and node-pool logic is split into library contracts so main flows stay within clear audit boundaries.  
  * GitHub: https://github.com/RSS3-Network/RSS3-Network-Contracts  

- **RSS3 Pre-Staking**  
  Mainnet-verifiable pre-staking: tiered lock-ups for deposit/redeem, with rewards released over time (`dividends` branch).  
  * Mainnet: https://etherscan.io/address/0x5301cbbedc048abac7e213184132cf982d593563  
  * GitHub: https://github.com/NaturalSelectionLabs/Pre-Staking/tree/dividends  

- **Folo — PowerToken**  
  Utility token for content / feed scenarios: OpenZeppelin-based upgradeable ERC-20 with roles, non-transferable points, tipping and feed balances, daily mint caps, and more.  
  * On-chain: https://scan.rss3.io/address/0xE06Af68F0c9e819513a6CD083EF6848E76C28CD8  
  * GitHub: https://github.com/RSSNext/follow-contracts  

- **EVM Bonding Curve**  
  Bonding-curve launches and liquidity migration: virtual-reserve pricing, fee distribution, and migration; the dynamic variant supports multiple curve configs and AMM-style pricing parameters (implementation informed by Meteora).  
  * https://github.com/iavl/bondingcurve-evm · https://github.com/iavl/dynamic-bonding-curve-contracts  

- **Crossbell — protocol, bridge, NFT marketplace**  
  Social protocol (identity, links, and content with mint/link policies), asset bridge between Ethereum and Crossbell (dual gateways + validator + quotas and mapping), and an NFT marketplace (listings, ERC-2981 royalties, ERC-777).  
  * https://github.com/Crossbell-Box/Crossbell-Contracts  
  * https://github.com/Crossbell-Box/crossbell-bridge-contracts  
  * https://github.com/Crossbell-Box/xShop-contracts  

### **Solana (Rust / Anchor)**

- **Smart Account** · *secp256r1 / WebAuthn*  
  Passkey-centric smart account: program and mint allowlists, authenticated contact changes, and delegated execution of arbitrary instructions under whitelist rules (reducing blind signing and malicious-program risk).  
  * GitHub: https://github.com/iavl/smart-account-solana  

- **Bonding Curve Launchpad**  
  On-chain curve creation, trading, parameters, and withdrawals, with a built-in AMM submodule.  
  * GitHub: https://github.com/iavl/bondingcurve-solana  

### **Rollup / execution layer (Go)**

- **RSS3 VSL — OP Stack customization** · *Go, op-geth, OP Stack*  
  Modular L2 on the Optimism stack, with **RSS3 as the gas token** and **NEAR DA** / **Celestia DA** data-availability integration.  
  * Execution: https://github.com/RSS3-Network/op-geth (`rss3-main`)  
  * Coordination & components: https://github.com/RSS3-Network/optimism (`rss3-main`)  
  * Celestia DA (example branch): https://github.com/RSS3-Network/optimism/tree/feat/celestia-da  

- **Crossbell op-geth**  
  EVM execution-layer fork for Crossbell, with **free gas transaction** support.  
  * GitHub: https://github.com/iavl/crossbell-op-geth  

### **Earlier public chains**

- **NetCloth Chain** · *Go, Cosmos SDK, EVM*  
  BPoS public chain: full in-app EVM (state transition and interpreter), supporting smart contracts and governance-driven upgrades.  
  * GitHub: https://github.com/netcloth/netcloth-chain  

---

<p align="center">
  <i>Building secure, scalable, and elegant blockchain systems.</i>
</p>
