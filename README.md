<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1500&color=58A6FF&center=true&vCenter=true&random=false&width=650&lines=systems+%26+research+engineer;compiler+%26+language+designer;cryptography+implementor;kernel+developer;building+from+the+metal+up" alt="Typing SVG" />

<br/>

<p align="center"><i>"I don't use abstractions I don't understand. I build them."</i></p>

<br/>

[![Rust](https://img.shields.io/badge/Rust-000?style=for-the-badge&logo=rust&logoColor=CE422B)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-000?style=for-the-badge&logo=typescript&logoColor=3178C6)](#)
[![Python](https://img.shields.io/badge/Python-000?style=for-the-badge&logo=python&logoColor=3776AB)](#)
[![Go](https://img.shields.io/badge/Go-000?style=for-the-badge&logo=go&logoColor=00ADD8)](#)
[![Solidity](https://img.shields.io/badge/Solidity-000?style=for-the-badge&logo=solidity&logoColor=636890)](#)
[![x86_64](https://img.shields.io/badge/x86__64-000?style=for-the-badge&logo=assemblyscript&logoColor=007AAC)](#)

</div>

---

### About me

Self-taught software engineer from Brazil. I build things from scratch to truly understand how they work — compilers, kernels, cryptographic protocols, AI models, trading systems, smart contracts. I don't fit neatly into conventional job titles because I move across low-level systems, applied cryptography, blockchain, AI research, and full-stack development without asking permission.

My approach is simple: if I need to use something, I want to know how it works at the deepest level. That usually means implementing it myself first. This isn't stubbornness — it's how I learn, and it's how I've ended up with a toolbox that spans from bare-metal assembly to React frontends.

---

### What I build

<table>
<tr>
<td width="50%">

**`COMPILERS & SYSTEMS`**

Built a complete programming language with an LLVM 18 backend — lexer, parser, type checker, IR, codegen. ~25K lines of Rust, 184 tests, LSP server for IDE integration. It compiles a microkernel I also wrote from scratch in x86_64 assembly (bootloader, paging, IRQ handling, heap allocator).

> If you build the compiler, you understand how code becomes machine instructions — and where that process can go wrong.

</td>
<td width="50%">

**`APPLIED CRYPTOGRAPHY`**

I don't call `encrypt()` from a library and move on. I implement the protocols: AES-256-GCM, Argon2id, ECDSA secp256k1, BIP32/39/44, EIP-712, RLP encoding, HMAC-SHA256, Keccak256, constant-time comparisons, zeroize-on-drop. 12+ protocols, all from scratch.

> Whoever implements the protocol knows where it breaks. Whoever just consumes the API doesn't.

</td>
</tr>
<tr>
<td width="50%">

**`AI / NLP — NO FRAMEWORKS, NO GPU`**

Two research-grade NLP projects built entirely in Rust, zero external dependencies. One implements SVD via manual power iteration, PPMI, union-find, and morphological induction (~10.5K LOC). The other uses Hyperdimensional Computing with 10,000-dimensional vectors, achieving perplexity competitive with GPT-2 at 174,000x less energy (~13.7K LOC). 6 theorems formalized with proofs.

> I don't depend on abstractions. I build and audit them.

</td>
<td width="50%">

**`BLOCKCHAIN & DeFi`**

Smart contracts on Solana (Anchor) and Ethereum (Solidity). PDAs, VRF, multisig, timelock, staking tiers, full tokenomics. DEX integrations (Jupiter, Hyperliquid), operational trading bots, copy-trading with multi-layer risk management, order flow aggregation across exchanges processing 75M+ candles (13GB).

> Understanding MEV, slippage, liquidation mechanics, and how value flows through protocols — not just the interface, but the incentive layer underneath.

</td>
</tr>
</table>

---

### How deep the stack goes

Most engineers specialize in one or two layers. I've built production systems across all of them:

| Layer | What I built |
|:------|:-------------|
| **Compiler / VM** | Complete language with LLVM 18 backend (25K LOC) — Lexer, Parser, Types, IR, Codegen |
| **Kernel / OS** | Microkernel x86_64 — boot sequence, paging, memory management, interrupts |
| **Cryptography** | 12+ protocols implemented from scratch. Not consumed — *implemented.* |
| **AI / Research** | 2 NLP models in pure Rust, 24K+ LOC, zero deps. 6 theorems with formal proofs |
| **Blockchain** | Smart contracts on Solana + Ethereum. RLP encoder, EIP-712, BIP44, DEX integrations |
| **Trading / Quant** | Operational bots, grid strategies, copy-trading. 75M candles, multi-exchange aggregation |
| **Full-Stack** | 7 desktop apps (Tauri + Svelte + Rust), 18+ web projects (Next.js, React, Go) |

---

### Numbers

<div align="center">

| | |
|:--|:--|
| Original projects | **70+** |
| Lines of code | **200K+** |
| Languages used | **8+** (Rust, TS, Python, Go, x86_64 ASM, MQL4, Solidity, SQL) |
| Algorithms implemented from scratch | **20+** |
| Automated tests written | **280+** |
| Desktop apps (Tauri + Svelte + Rust) | **7** |
| Crypto protocols implemented | **12+** |
| Largest dataset processed | **75M records / 13GB** |
| Theorems formalized with proofs | **6** |

</div>

---

### Stack

<details>
<summary><b>Languages & tools I use day-to-day</b></summary>
<br/>

**Systems & Low-Level**

![Rust](https://img.shields.io/badge/Rust-CE422B?style=flat-square&logo=rust&logoColor=white)
![Assembly](https://img.shields.io/badge/x86__64_ASM-007AAC?style=flat-square&logo=assemblyscript&logoColor=white)
![LLVM](https://img.shields.io/badge/LLVM_18-262D3A?style=flat-square&logo=llvm&logoColor=white)

**Web & Desktop**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte_5-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri_2-FFC131?style=flat-square&logo=tauri&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**Blockchain**

![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![Anchor](https://img.shields.io/badge/Anchor-1E1E2E?style=flat-square)
![Solidity](https://img.shields.io/badge/Solidity-636890?style=flat-square&logo=solidity&logoColor=white)

</details>

---

### Security — a natural consequence

When you've built compilers, kernels, crypto protocols, and DeFi systems from scratch, security isn't a separate skill — it's a byproduct of understanding every layer deeply enough to know where it fails. I actively research vulnerabilities in DeFi protocols and smart contracts, bringing a builder's perspective to security: I've implemented the systems others try to audit.

<details>
<summary><b>Attack surface I can cover</b></summary>
<br/>

| Layer | Coverage |
|-------|----------|
| **Smart Contracts** | Solana (Anchor/BPF), Ethereum (Solidity/EVM) — PDAs, CPIs, authority checks, reentrancy, overflow, logic bugs |
| **Cryptography** | Signature validation, key derivation, nonce management, domain separation, timing attacks, entropy quality |
| **Protocol / DeFi** | Order flow, oracle manipulation, flash loans, MEV, liquidation logic, tokenomics, governance attacks |
| **Application** | API security, auth bypass, input validation, WebSocket injection, CORS, client-side crypto |
| **Systems** | Memory safety, integer overflow, buffer overflows, serialization bugs, compiler optimizations, side-channels |

</details>

---

### How I think

I'm a **first-principles** person. When I need SVD, I implement power iteration. When I need to sign a transaction, I implement EIP-712. When I need BPE, I code it from scratch. Not because I enjoy reinventing wheels, but because understanding the internals is what lets me build — and break — things that others can't.

I also value intellectual honesty. I document limitations, failed experiments, and trade-offs openly. None of my projects are perfect and I don't pretend they are. Every repo has a section on what didn't work and why.

---

### Private work

Beyond what's public here, I maintain **20+ private repositories** covering proprietary trading systems, air-gapped security tools, financial data infrastructure, SaaS platforms, and DeFi protocol research.

> Details available under NDA or in a hiring context.

---

<div align="center">

<p align="center"><i>"I don't build at one layer of the stack. I build the stack."</i></p>

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-UnbiasedCodex-181717?style=for-the-badge&logo=github)](https://github.com/UnbiasedCodex)

</div>
