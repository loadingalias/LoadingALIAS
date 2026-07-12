## Rust Systems Engineer

I build Rust infra that collapses traditional,fragmented stacks into simpler, faster systems.

My work spans distributed systems, storage engines, safe memory reclamation,embedded targets, and cryptographic primitives - w/ an emphasis on determinism, supply-chain safety, and architectures that eliminate failure modes entirely.

---

### Selected Open Source

**[cargo-rail](https://github.com/loadingalias/cargo-rail)** — **the Rust workspace toolchain, collapsed into one binary.**

`cargo-rail` replaces work typically spread across 10+ Cargo plugins, release tools, GitHub Actions, and bespoke scripts—with one graph-aware tool, one `rail.toml`, and just 14 direct dependencies.

- **Faster builds & dramatically less CI waste.**
- **A complete Rust release system.**
- **Split/Sync like Copybara w/o Copybara.**
- **One graph, one source of truth.**

**[rscrypto](https://github.com/loadingalias/rscrypto)** — **Pure-Rust cryptography built to outperform the incumbent stacks.**

One `no_std`/WASM-native primitive stack covering hashes, AEADs, MACs, KDFs, password hashing, signatures, key exchange, ML-KEM, RSA, and checksums—with zero default dependencies and no production C/FFI, OpenSSL, or system-library coupling.

- **1.59× faster by geomean**
- **5.18× for checksums, 1.56× for AEADs, 1.55× for RSA, 1.49× for ML-KEM, and 1.41× against the official BLAKE3 implementation**
- **Portable Rust is the authority; SIMD and ASM are accelerators.**
- **Security is proven by evidence; Pending Audit Financing Now**

Both of the above projects are requirements of the work I'm doing. I use them everyday. I will maintain them as part of my reputation and my ongoing work indefinitely.

---

### Current Work

Founder and engineer at [@alias-research](https://github.com/alias-research). This is a stealth startup and will remain as such until it reaches a stable first public release. 

---

### Contact

**X, Reddit, Crates, Rust Forum, Lobste.rs:** loadingalias

**Email:** thealiaslab@gmail.com
