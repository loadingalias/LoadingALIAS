<p align="center">
  <img src="assets/header_large_edited.png" alt="loadingalias" width="100%" style="max-width: 800px;">
</p>

## Rust Systems Engineer

I build Rust infra that collapses traditional,fragmented stacks into simpler, faster systems.

My work spans distributed systems, storage engines, safe memory reclamation,embedded targets, and cryptographic primitives - w/ an emphasis on determinism, supply-chain safety, and architectures that eliminate failure modes entirely.

---

### Selected Open Source

**[cargo-rail](https://github.com/loadingalias/cargo-rail)** — **the Rust workspace toolchain, collapsed into one binary.**

`cargo-rail` replaces work typically spread across 10+ Cargo plugins, release tools, GitHub Actions, and bespoke scripts—with one graph-aware tool, one `rail.toml`, and just 14 direct dependencies.

- **Faster builds and dramatically less CI waste.** `unify` removes version drift, fragmented features, unused dependencies, dead features, and workspace-hack overhead. `plan` traces every change through the Cargo dependency graph so CI executes only the builds, tests, docs, benchmarks, and infrastructure work actually affected.
- **A complete Rust release system.** Reviewed changesets, version inference, dependency cascades, changelogs, graph-ordered publishing, release PRs, tags, and resumable finalization replace `release-plz`, `cargo-release`, and `git-cliff`.
- **Copybara without Copybara.** `split` and `sync` publish individual crates from a monorepo and synchronize changes in both directions—without exposing the rest of the repository, adopting a custom DSL, or running a separate Java toolchain.
- **One graph, one source of truth.** Dependency cleanup, CI selection, releases, and repository synchronization all consume the same resolved Cargo graph and Git history.

200+ stars · [crates.io](https://crates.io/crates/cargo-rail) · [docs.rs](https://docs.rs/cargo-rail) · [GitHub Action](https://github.com/loadingalias/cargo-rail-action)

**[rscrypto](https://github.com/loadingalias/rscrypto)** — **Pure-Rust cryptography built to outperform the incumbent stacks.**

One `no_std`/WASM-native primitive stack covering hashes, AEADs, MACs, KDFs, password hashing, signatures, key exchange, ML-KEM, RSA, and checksums—with zero default dependencies and no production C/FFI, OpenSSL, or system-library coupling.

- **1.59× faster by geomean** than the fastest matched external implementation across 6,750 Linux CI comparisons on nine architectures. `rscrypto` wins or ties 90.4% of those comparisons.
- **5.18× for checksums, 1.56× for AEADs, 1.55× for RSA, 1.49× for ML-KEM, and 1.41× against the official BLAKE3 implementation**—measured against `aws-lc-rs`, `ring`, RustCrypto, `blake3`, `libcrux`, and specialized checksum crates.
- **Portable Rust is the authority; SIMD and ASM are accelerators.** The same implementations scale across x86-64, AArch64, IBM Z, POWER, RISC-V, WASM, embedded, and freestanding targets.
- **Security claims are evidence-bound.** Constant-time work is evaluated with BINSEC, DudeCT, generated-code heuristics, and manual artifact review, scoped to exact versions, targets, profiles, and feature sets. Third-party audit grant applications are underway.

[Benchmarks and raw evidence](https://github.com/loadingalias/rscrypto/blob/main/benchmark_results/OVERVIEW.md) · [docs.rs](https://docs.rs/rscrypto) · [security model](https://github.com/loadingalias/rscrypto/blob/main/THREAT_MODEL.md)

Neither project is a portfolio exercise. I built them because the storage system below required a smaller, faster, and more auditable foundation than the existing ecosystem could provide.

---

### Current Work

Founder and engineer at [@alias-research](https://github.com/alias-research). This is a stealth startup and will remain as such until it reaches a stable first public release. 

---

### Availability

Contact Me. 

**Contact:** thealiaslab@gmail.com

---

<p align="center">
  <a href="https://dev.to/loadingalias">Blog</a> ·
  <a href="https://crates.io/users/loadingalias">Crates</a> ·
  <a href="https://x.com/@loadingalias">X</a>
</p>
