<p align="center">
  <img src="assets/header_large_git.png" alt="loadingalias" width="100%" style="max-width: 800px;">
</p>

## Rust Systems Engineer

I design and ship **deterministic, supply-chain-safe systems in Rust** — focusing on performance, correctness, and architectures that eliminate failure modes rather than mitigate them.

4+ years building and deploying Rust across **distributed systems, storage engines, embedded targets, and cryptographic primitives**. I care deeply about mechanical sympathy, auditability, and long-term maintainability.

---

### Selected Open Source

**[cargo-rail](https://github.com/loadingalias/cargo-rail)**  
Monorepo orchestration for serious Rust workspaces.

- Replaces `cargo-hakari`, `cargo-udeps`, `cargo-machete`, `cargo-release`, `git-cliff`, `Google Copybara`,and `cargo-msrv`
- 190+ stars · 14 total dependencies
- Used and tested on `tikv`, `tokio`, `polars`, `helix`, `meilisearch`, `ripgrep`
- Official [GitHub Action](https://github.com/loadingalias/cargo-rail-action)

**[rscrypto](https://github.com/loadingalias/rscrypto)**  
Pure-Rust cryptographic primitives with **zero C dependencies**.

- High-performance CRC implementations (16/24/32/32C/64XZ/64NVME)
- Pure Rust Blake3 impl across all supported platforms at parity with or surpassing the official Blake3 implementation.
- Portable across x86-64, ARM64, RISC-V, s390x, POWER9/P10
- Accepted by **IBM** for CI/CD usage on mainframe architectures

These projects exist because I needed them for my own work.

---

### Current Work

I’m building a **distributed storage engine** at [@alias-research](https://github.com/alias-research), approaching its first public release in the next few months.

The system is centered around a novel **epoch-based reclamation primitive** that enables:

- Sub-10ns MVCC operations
- Deterministic O(1) garbage collection
- O(1) crash recovery

This allows a unified architecture where **KV, OLAP, vector, graph, and streaming workloads** operate over the same epoch-versioned data model — not separate engines stitched together.

The implementation is heavily validated using Loom, Shuttle, Kani, and Stateright before anything ships. It's not a toy database. 

Private for now. The open-source work above exists to support and harden this system.

---

### Availability

None. I'm not currently looking for work.

**Contact:** thealiaslab@gmail.com

---

<p align="center">
  <a href="https://dev.to/loadingalias">Blog</a> ·
  <a href="https://crates.io/users/loadingalias">Crates</a> ·
  <a href="https://mastodon.social/@loadingalias">Mastodon</a>
</p>
