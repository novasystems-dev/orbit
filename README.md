<div align="center">

# 🪐 Orbit Package Manager

**The Official Package Manager & Build Toolchain for the Nova Systems Programming Language**

<br />

[![Release](https://img.shields.io/badge/version-v0.31.00-8b5cf6?style=flat&labelColor=0f172a&logo=semver&logoColor=white)](https://github.com/novasystems-dev/orbit/releases)
[![Nova](https://img.shields.io/badge/language-Nova_0.31.00-38bdf8?style=flat&labelColor=0f172a&logo=starship&logoColor=white)](https://github.com/novasystems-dev/nova)
[![License](https://img.shields.io/badge/license-PolyForm-a855f7?style=flat&labelColor=0f172a&logo=open-source-initiative&logoColor=white)](LICENSE)
[![Source](https://img.shields.io/badge/source-100%25%20pure%20nova-ec4899?style=flat&labelColor=0f172a&logo=github&logoColor=white)](src/main.nova)

<br />

</div>

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
