<p align="center">
  <img src="assets/logo.svg" alt="Orbit Logo" width="160" />
</p>

<h1 align="center">Orbit Package Manager</h1>

<p align="center">
  <b>The Official Package Manager & Build Toolchain for the Nova Systems Programming Language</b>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-PolyForm%20Noncommercial-blueviolet?style=for-the-badge" alt="License" /></a>
  <a href="https://github.com/novasystems-dev/nova"><img src="https://img.shields.io/badge/Nova-Systems%20Lang-00F0FF?style=for-the-badge" alt="Nova" /></a>
  <img src="https://img.shields.io/badge/Version-v0.2.0-FF548F?style=for-the-badge" alt="Version" />
</p>

---

## 🚀 Overview

**Orbit** is the official package manager, dependency resolver, and build orchestration engine for the **Nova Systems Programming Language**. Written in 100% Pure Nova, Orbit provides:

- Deterministic dependency resolution via `Orbit.lock` cryptographic hash pinning.
- One-command project scaffolding (`orbit new <project>`, `orbit init`).
- Zero-overhead compilation and running (`orbit build`, `orbit run`).
- Integrated test runner (`orbit test`).
- Capability-based security auditing (`orbit audit`).
- Remote package registry search and publishing (`orbit search`, `orbit publish`).
- Local vendoring of dependencies (`orbit vendor`).
- Dependency visualization (`orbit tree`).

---

## 🛠️ Usage

```bash
# Create a new Nova project
orbit new my_service

# Build and optimize
orbit build

# Execute package binary
orbit run

# Run test suite
orbit test

# Inspect dependency tree
orbit tree

# Vendor dependencies locally
orbit vendor
```

---

## ⚖️ License

Orbit is released under the **PolyForm Noncommercial License 1.0.0**. Copyright (c) 2026 Fyew999 (Nova Systems).
