# Cryptuon Research

**Blockchain theory, shipped as protocols.**

We turn peer-reviewed research into deployable infrastructure. Cross-chain composability, smart contract compilers, and protocol design — built in Rust and Zig, grounded in formal methods.

Our paper *"Towards Universal Atomic Composability"* was recognised by a16z Crypto Startup School.

---

## Projects

### solscript

**Write Solidity. Deploy to Solana.** A transpiler that compiles familiar Solidity syntax to native Solana programs with automatic PDA derivation, account validation, and full Anchor compatibility. No Rust required.

```
solscript init my-token
solscript build-bpf
solana program deploy target/deploy/my_token.so
```

Two compilation backends: Rust/Anchor codegen for ecosystem compatibility, and direct LLVM-to-BPF for faster iteration.

`Rust` · [Repository](https://github.com/cryptuon/solscript)

---

### zig-evm

**An experimental EVM implementation in Zig.** Clean-room Ethereum Virtual Machine built for auditability and research. Designed for teams that need to reason about execution semantics, not just run them.

`Zig` · [Repository](https://github.com/cryptuon/zig-evm)

---

### stxscript

**StxScript-to-Clarity transpiler.** Write smart contracts for Stacks in a friendlier syntax, compile to Clarity.

`Python` · [Repository](https://github.com/cryptuon/stxscript)

---

### tesseract

**Multi-rollup environments on Ethereum.** Enabling atomic transactions across rollups. The protocol implementation behind our universal atomic composability research.

[Repository](https://github.com/cryptuon/tesseract) · [Paper](https://github.com/cryptuon/tesseract-paper)

---

## Research

Published work driving our protocol design:

- **Towards Universal Atomic Composability** — Cross-chain atomic transactions across Ethereum rollups
- **Generalised DePIN Protocol** — Infrastructure networks
- **FairFlow Protocol** — Equitable MEV mitigation
- **Decentralized Deepfake Detection Network** — Content verification
- **Centralized Intermediation in a Decentralized Web3 Economy** — Economic analysis

---

## Philosophy

Blockchain infrastructure has a gap between what gets published and what gets deployed. Most protocol papers end at simulation. We take them to production: real compilers, real VMs, real transaction pipelines.

Every tool here is designed so you don't need to read the paper to use the protocol — but the paper is there if you want to verify our work.

---

## Contributing

Open source under MIT. See individual repositories for setup.

## Contact

Led by [@dipankar](https://github.com/dipankar) · Scotland · [cryptuon.com](https://cryptuon.com)
