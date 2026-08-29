## Rust Systems Engineer

I focus mainly on collapsing fragmented, legacy systems into smaller, faster, more efficient ones. This is the work that makes me happiest. I enjoy thinking about old problems from a modern perspective; I enjoy unraveling the reasons behind why a system does what it does.

I prefer to write Rust; every once in a while I'll pick up Typescript. My work spans dev tooling, cryptography, storage engines, query engines, and distributed systems. I am a performance oriented engineer and I believe code should be maximally portable.

### Most Important OSS Work

**[cargo-rail](https://github.com/loadingalias/cargo-rail)** — **A Cargo-native workspace engine for Rust monorepos.**

Built to improve my dev velocity. Built to make complex Rust workspaces faster to change and harder to mess up. Built to replace the mountain of Cargo plugins, release bots, cache wrappers, and glue that had accumulated in just a few weeks.

Cargo-Rail scopes local builds, tests, checks... and through the [GHA](https://github.com/loadingalias/cargo-rail-action), CI, to what a change actually affects. It restores compiler work Cargo and sccache leave behind, significantly cutting rebuild time; finds code that never needed to be public; keeps deps coherent and the graph unified; turns changesets into customizable releases; and splits/syncs crates between a canonical dev monorepo and standalone OSS repos w/o dragging in Copybara or it's DSL.

Cargo-Rail fills the gaps I feel exist within Cargo w/o trying to replace it. It's powered by a single shared `WorkspaceContext1, so every feature works from the same captured view of the workspace instead of rediscovering, or worse - disagreeing about the state.

**[rscrypto](https://github.com/loadingalias/rscrypto)** — **Portable pure-Rust cryptographic primitives.**

A pure-Rust cryptography lib that scales from bare-metal no_std and WASM to server systems, w/ one feature model for compiling only what we need. Portable Rust defines behavior, SIMD and ASM deliver perf, and security claims ship only with signed releases backed by published validation evidence.

Both projects exist because I needed them myself. These aren't portfolio pieces. They're important to my work and will be maintianed until my ticket gets punched.

### Current Work

Founder and lead engineer at [@alias-research](https://github.com/alias-research), privaetly building the future of storage, query, and data infra.

### All the Things

[My Engineering Diary](https://loadingalias.dev)

[Email](mailto:thealiaslab@gmail.com)

[Twitter/X](https://x.com/loadingalias)

[Lobste.rs](https://lobste.rs/@loadingalias)

[Rust Forum](https://users.rust-lang.org/u/loadingalias/summary)
