### Alejandro Auquilla (`@CrowAleksito`)

Software Engineer focused on **Rust**, **TypeScript / React / Next.js**, **C++**, and **Python** — with an emphasis on correctness fixes, static analysis, security hardening, and reproducible test coverage.

#### Security Advisories & Open-Source Work
- **Security Hardening & Rust CLI:** Credited finder on [`GHSA-956v-fr77-frx4`](https://github.com/clickswave/crossfyre-toolchain/security/advisories/GHSA-956v-fr77-frx4) (network trust, redirect credential leaks, daemon input bounds, and mobile update verification across `<= 0.1.46`), and merged hidden roff `man` page generation + CLI regression tests across `ambulo`, `toolmark`, and `plessor` in [`clickswave/crossfyre-toolchain`](https://github.com/clickswave/crossfyre-toolchain) ([PR #53](https://github.com/clickswave/crossfyre-toolchain/pull/53), [PR #57](https://github.com/clickswave/crossfyre-toolchain/pull/57), [PR #58](https://github.com/clickswave/crossfyre-toolchain/pull/58))
- **Rust / Compilers & Static Analysis:** Open fixes for ownership, closure-scoped moves, and generic type unification in [`limitlessprojects/Go-Hybrid`](https://github.com/limitlessprojects/Go-Hybrid) ([PR #3942](https://github.com/limitlessprojects/Go-Hybrid/pull/3942), [PR #4611](https://github.com/limitlessprojects/Go-Hybrid/pull/4611), [PR #4612](https://github.com/limitlessprojects/Go-Hybrid/pull/4612))
- **Systems, C++ & Rendering:** Built [`kajiya-path-tracer`](https://github.com/CrowAleksito/kajiya-path-tracer) (C++ Monte Carlo path tracer), plus open operator validation/reduction fixes in [`tenstorrent/tt-metal`](https://github.com/tenstorrent/tt-metal) ([PR #64731](https://github.com/tenstorrent/tt-metal/pull/64731), [PR #64741](https://github.com/tenstorrent/tt-metal/pull/64741)), settlement/listener hardening in [`paraloom-labs/paraloom-core`](https://github.com/paraloom-labs/paraloom-core) ([PR #1444](https://github.com/paraloom-labs/paraloom-core/pull/1444)), and endpoint routing in [`arakoodev/EdgeChains`](https://github.com/arakoodev/EdgeChains) ([PR #817](https://github.com/arakoodev/EdgeChains/pull/817))

#### How I Contribute
- Trace root causes in source before proposing changes
- Keep diffs tightly scoped with clear reproduction steps and regression tests (`cargo test`, `clippy`, `vitest`, `pytest`)
- Follow repository conventions, linters, and DCO/CLA requirements from the first commit
