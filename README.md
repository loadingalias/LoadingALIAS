<p align="center">
  <img src="assets/header_large_git.png" alt="loadingalias" width="100%" style="max-width: 800px;">
</p>

## Rust Systems Engineer

Building supply-chain-safe tooling and high-performance crypto primitives.
4+ years shipping Rust across distributed systems, embedded platforms, and storage engines.
Particularly interested in low-level systems, databases, and crypto... but working on a better alternative to industry standard observability, as well.

**Open to:** Contract, temporary, or full-time Rust roles · Remote preferred · USA (open to global relocation)
**Contact:** thealiaslab@gmail.com

---

### Open Source Work (Side Quests)

**[cargo-rail](https://github.com/loadingalias/cargo-rail)** — Monorepo orchestration for Rust workspaces
190+ stars · Replaces cargo-hakari, cargo-udeps, cargo-machete, cargo-release, git-cliff, cargo-msrv with 11 deps
Tested on tikv, polars, helix, tokio, meilisearch, ripgrep · [GitHub Action](https://github.com/loadingalias/cargo-rail-action)

**[rscrypto](https://github.com/loadingalias/rscrypto)** — Pure Rust cryptography, zero external dependencies and/or C-libs
The most performant, portable, and sound checksums (CRC 16/24/32/32C/64XZ/64NVME) on the planet
x86-64, ARM64, RISC-V, s390x, POWER9/P10 · Accepted by IBM for CI/CD usage on mainframe architectures

---

### What I'm Building

Distributed storage engine at [@alias-research](https://github.com/alias-research) — 2 years in development, approaching v1.

The work is anchored in a novel epoch-based reclamation primitive that enables sub-10ns MVCC operations with deterministic O(1) garbage collection. This has unlocked an architecture traditional databases can't achieve: true multi-model storage (KV, OLAP, Vector, Graph, Streaming) over unified epoch-versioned segments — not separate engines bolted together.

Key properties: same bytes everywhere (memory = disk = wire = consensus), one GC rule for the entire system, O(1) crash recovery. Verification via Loom, Shuttle, Kani, and Stateright before anything ships.

Private for now; v1 is not far. The OSS above was built to support it.

---

<p align="center">
  <a href="https://dev.to/loadingalias">Blog</a> ·
  <a href="https://twitter.com/loadingalias">Twitter</a> ·
  <a href="https://crates.io/users/loadingalias">Crates</a> ·
  <a href="https://mastodon.social/@loadingalias">Mastodon</a>
</p>

<p align="center">
  <a href="https://www.eff.org/pages/other-ways-give-and-donor-support#crypto"><img src="https://img.shields.io/badge/EFF-bb1a34?style=flat-square" alt="EFF"></a>
  <a href="https://donate.torproject.org/cryptocurrency/"><img src="https://img.shields.io/badge/Tor_Project-7D4698?style=flat-square&logo=torproject&logoColor=white" alt="Tor Project"></a>
</p>
