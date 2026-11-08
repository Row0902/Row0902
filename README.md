<div align="center">

# Rowell Urbáez Reyes

**I build release engineering and developer tooling.**
Versioning, changelogs, signed artifacts and cross-platform distribution.

[LinkedIn](https://www.linkedin.com/in/row0902/) · [Cutver](https://github.com/cutver) · [crates.io](https://crates.io/crates/cutver)

</div>

---

### Cutver — a release engine in Rust

Author and maintainer of [**Cutver**](https://github.com/cutver/cutver) ([crates.io](https://crates.io/crates/cutver),
MIT): a standalone, format-preserving release engine that synchronizes versions across
polyglot manifests, runs preflight checks, renders MiniJinja changelogs, commits, tags and
publishes — driven by one `cutver.toml`.

What's inside it: a microkernel with four typed capability slots, WASM plugins sandboxed by
default behind a verified digest gate, two-phase atomic transactions, cosign-signed
cross-platform binaries, and distribution through a Homebrew tap, a Scoop bucket, winget
manifests and OCI images. It versions, tests and publishes itself.

### Published work

| Artifact | Where |
| :--- | :--- |
| `cutver` — release orchestration engine (Rust, MIT) | [crates.io](https://crates.io/crates/cutver) · cosign-signed binaries |
| `aiowx` — asyncio ↔ wxPython bridge (Python) | [PyPI](https://pypi.org/project/aiowx/) |
| `aria2-sdk` — async JSON-RPC client for aria2 (Python) | [PyPI](https://pypi.org/project/aria2-sdk/) |
| `@row0902/ngx-gsap` — GSAP + Signals directives (Angular 22+) | [npm](https://www.npmjs.com/package/@row0902/ngx-gsap) |
| `Setup Cutver` · `Cutver Release` — GitHub Actions (TypeScript) | [GitHub Marketplace](https://github.com/marketplace/actions/setup-cutver) |

### Selected projects

- **[aiowx](https://github.com/Row0902/aiowx)** — runs asyncio coroutines under a wxPython
  event loop, so async code coexists with a GUI toolkit that owns the main thread.
- **[build-wx](https://github.com/Row0902/build-wx)** — CI-built wxPython wheels for Windows
  and Linux, so nobody waits 30 minutes for a source build.
- **[ngx-gsap](https://github.com/Row0902/ngx-gsap)** — zoneless, signal-based GSAP directives
  with reactive accessibility utilities for Angular 22+.
- **[pi-adb](https://github.com/Row0902/pi-adb)** — 21 typed ADB actions for an agent harness:
  devices, installs, screenshots, log streaming, port forwarding.

### Kairos (private, commercial)

Multiplatform academic management suite: a **Rust core** exposed through UniFFI as the single
source of truth, Angular 22 (zoneless + signals) in a Tauri 2 desktop shell, and Kotlin/Compose
on Android. Source is private.

### Upstream contributions

`metalalchemist/VeTube` (8 merged PRs) · `microsoft/winget-pkgs` (manifests accepted upstream) ·
`Gentleman-Programming/gentle-dot` (native Windows port work)

### Stack

Rust · Python · TypeScript · Kotlin · Shell · WASM/Extism · UniFFI · Tauri · GitHub Actions ·
MiniJinja · Docker/OCI · Scoop · Homebrew · winget

---

Open to roles in developer tooling, release engineering and systems programming.
