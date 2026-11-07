# Orbit — The Official Package Manager for Nova Systems Language

> **Ultra-Fast | Deterministic Dependency Graphs | Capability Sandboxing | Zero-Cost In-Place Resolution**

Orbit is the official build system and package manager for the **Nova Systems Programming Language**, modeled after the precision and ergonomics of Rust's Cargo and Go's module system.

---

## Key Features

- **Blazing Fast**: Written in 100% pure Nova, compiling to native binaries in milliseconds.
- **Deterministic Lockfiles**: `Orbit.lock` tracks exact SHA-256 cryptographic hashes for reproducible zero-tamper builds.
- **Security & Capability Auditing**: `orbit audit` inspects packages for memory safety, isolation flags, and bare-metal pointer dereferences.
- **Workspace Support**: Multi-crate monorepos with inherited dependencies and workspace-wide build matrices.

---

## Quickstart

```bash
# Create a new Nova project
orbit new my_service

# Build executable
orbit build

# Run application
orbit run

# Audit dependency capability security
orbit audit

# Generate cryptographic lockfile
orbit lock
```

---

## License

PolyForm Noncommercial License 1.0.0. Copyright (c) 2026 Fyew999 (Nova Systems).
Permits free personal, educational, and open-source use, modification, and recoding. Commercial sale, commercial distribution, or closed-source incorporation is strictly prohibited without a commercial license. See [LICENSE](LICENSE) for details.
