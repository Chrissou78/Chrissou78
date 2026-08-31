<h1 align="center">Christopher — Blockchain Engineer & Full-Stack Builder</h1>

<p align="center">
  <em>Smart contracts on EVM, Move and Rust chains — wrapped in products people can actually use.</em>
</p>

<p align="center">
  <a href="https://onchainlabs.ch"><img alt="OnChainLabs" src="https://img.shields.io/badge/OnChainLabs-0B0F19?style=for-the-badge&logo=ethereum&logoColor=white"></a>
  <img alt="Switzerland" src="https://img.shields.io/badge/Based%20in-Switzerland-D52B1E?style=for-the-badge">
  <img alt="Open to work" src="https://img.shields.io/badge/Open%20to-Collaborations-2ea44f?style=for-the-badge">
</p>

---

## 👋 About

I build **on-chain systems end to end** — from the contract that holds the value, to the API that orchestrates it, to the interface a non-crypto user can navigate without ever hearing the word "wallet".

---

## 🧭 Specialities

<p align="center">
  <img src="assets/specialties.svg" alt="Specialities: Solidity/EVM contracts, tokenomics and treasury design, Move (Aptos/Sui), Rust (Solana/CosmWasm), TypeScript/Node backends, Next.js/React frontends, Flutter/Dart mobile, infra and CI, AI agents and automation" width="100%">
</p>

<p align="center">
  <img src="assets/radar.svg" alt="Radar chart across smart contracts, backend, frontend, mobile, infra and AI automation" width="70%">
</p>

---

## 🧱 How a project fits together

The layers I work across on a typical build — I own the seams, not just one box.

```mermaid
flowchart LR
    subgraph CHAIN["⛓️ On-chain"]
        A["Solidity / Move / Rust<br/>contracts"]
        B["Treasury multisig<br/>· burn · audit trail"]
    end
    subgraph SVC["🔧 Services"]
        C["Node / TypeScript API"]
        D["Indexer &<br/>event listeners"]
        E["AI agents<br/>· automation"]
    end
    subgraph APP["🖥️ Product"]
        F["Next.js / React<br/>web app"]
        G["Flutter<br/>mobile + wallet"]
    end
    subgraph OPS["🚀 Delivery"]
        H["CI · tests · coverage"]
        I["Vercel / Railway<br/>Docker"]
    end

    A --> D --> C
    B --> A
    C --> F
    C --> G
    E --> C
    H --> A
    H --> C
    I --> F
    I --> C

    classDef chain fill:#3b2a06,stroke:#f0b429,color:#f5e6c8
    classDef svc   fill:#0b2a45,stroke:#60a5fa,color:#d8e9ff
    classDef app   fill:#07333a,stroke:#22d3ee,color:#d3f6fb
    classDef ops   fill:#05332a,stroke:#34d399,color:#d6f7ec
    class A,B chain
    class C,D,E svc
    class F,G app
    class H,I ops
```

---

## 🧪 What I actually ship in

Aggregated from the source in my public repositories:

```mermaid
pie showData
    title Bytes of code by language across my repos
    "TypeScript" : 60.9
    "JavaScript" : 16.9
    "HTML" : 16.2
    "CSS" : 1.8
    "Solidity" : 1.5
    "Dart" : 1.4
    "Nunjucks" : 1.2
    "Other" : 0.1
```

> Contract code is small by volume and large by consequence — a 200-line vault carries more risk than 20k lines of UI.

---

## 🔍 Deep dive

<details>
<summary><b>⛓️ Smart contracts & protocol</b></summary>

<br>

Upgradeable proxies, treasury multisigs, deflationary burn mechanics, on-chain audit trails and token standards. Tests and coverage before mainnet, not after — custody and upgrade paths are designed per product, never copy-pasted.

![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Move](https://img.shields.io/badge/Move-4A90D9?style=flat-square)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![EVM](https://img.shields.io/badge/EVM-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![Polygon](https://img.shields.io/badge/Polygon-7B3FE4?style=flat-square&logo=polygon&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-14F195?style=flat-square&logo=solana&logoColor=black)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF100?style=flat-square&logo=hardhat&logoColor=black)
![Foundry](https://img.shields.io/badge/Foundry-000000?style=flat-square)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=flat-square&logo=openzeppelin&logoColor=white)
![ethers.js](https://img.shields.io/badge/ethers.js-2535A0?style=flat-square&logo=ethers&logoColor=white)

</details>

<details>
<summary><b>🔧 Backend & APIs</b></summary>

<br>

TypeScript monorepos, REST and webhook-driven services, payment rails, event indexers, background jobs and the glue that keeps off-chain state honest about on-chain state.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</details>

<details>
<summary><b>🖥️ Frontend & mobile</b></summary>

<br>

Next.js dashboards, multilingual product sites, checkout flows, and Flutter apps with offline-first key handling — BIP39/BIP32 generation, challenge signing, balances and minting behind a UI that never says "gas".

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

</details>

<details>
<summary><b>🚀 Infra, delivery & AI automation</b></summary>

<br>

Monorepo pipelines, CI with real coverage gates, deploys across Vercel and Railway — plus LLM agents wired into actual workflows with human-in-the-loop approval rather than autonomous posting.

![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white)

</details>

---

## 💡 How I work

- **Contracts first, then everything around them.** Tests, coverage and upgrade paths before mainnet.
- **Custody is a design decision.** Key generation, storage and recovery get thought through per product.
- **Ship the whole thing.** Contract, indexer, API, dashboard, mobile app, deploy pipeline.
- **Boring UX for exotic tech.** If a merchant needs to understand gas, the product isn't finished.

---

## 📊 GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Chrissou78&show_icons=true&hide_border=true&theme=tokyonight" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Chrissou78&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages">
</p>

---

## 📬 Get in touch

- 🌐 [onchainlabs.ch](https://onchainlabs.ch)
- ✉️ christopher.fourquier@onchainlabs.ch
- 💬 Open to protocol work, smart-contract development and audits, tokenization projects, and full-stack builds.

<p align="center"><sub>Building on-chain infrastructure that people use without knowing it's on-chain.</sub></p>
