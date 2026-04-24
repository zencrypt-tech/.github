# Zencrypt Tech

> **Keeping It Simple and Secure.**

Zencrypt Tech is a collection of encryption and privacy-focused tools built across CLI, desktop, web, and Web3 environments.

The Zencrypt ecosystem is organized as a product family rather than a single monolithic codebase. Each product is separated by platform and purpose, while still sharing the same broader direction: making encryption tooling easier to access, easier to use, and easier to keep organized over time.

---

## Products

| Product | Type | Description | Status |
|---|---|---|---|
| **Zencrypt CLI (Python)** | CLI | Python-based command-line encryption toolkit for local workflows and direct source-based usage. |✅|
| **Zencrypt CLI (Java)** | CLI | Java-based Zencrypt CLI packaged for portable and cross-platform use. |  🚫 |
| **Zencrypt GUI** | Desktop App | Desktop interface for users who want Zencrypt functionality without relying on the terminal. |🚫|
| **Zencrypt Webapp** | Web App | Browser-accessible Zencrypt platform focused on practical encryption workflows, authentication, and key handling. |🚫|
| **Zencrypt dApp** | Web3 dApp | Solana-connected application focused on wallet authentication, gated access, and Web3-oriented identity and permissions. |✅|

---

## Repository Layout

This organization is structured so each major product has its own repository, release history, and documentation.

| Repository | Purpose |
|---|---|
| `zencrypt-tech` | Landing page / public-facing website |
| `zencrypt-cli-python` | Python CLI source |
| `zencrypt-cli-java` | Java CLI source |
| `zencrypt-gui` | Desktop GUI application |
| `zencrypt-webapp` | Web application |
| `zencrypt-dapp` | Solana-connected dApp |
| `.github` | Organization profile, shared docs, and defaults |

---

## Where To Start

If you are new to Zencrypt Tech:

- Start with **Zencrypt GUI** if you want the easiest desktop experience.
- Start with **Zencrypt CLI (Python)** if you want the most direct source-based workflow.
- Start with **Zencrypt Webapp** if you want browser-based access.
- Start with **Zencrypt dApp** if you want wallet-based authentication and Web3-oriented access control.

---

## Core Functionality

Zencrypt Tech is centered around practical encryption and privacy workflows.

Across the Zencrypt product line, the core functionality includes:

- generating hashes
- encrypting and decrypting text
- encrypting and decrypting files
- PGP-based encryption workflows
- Argon2-based advanced functionality
- key export and key import handling
- authenticated access and session-based usage flows
- wallet-based access models in the Web3 layer

The CLI products are built around the same core encryption workflow as the webapp, while the dApp extends Zencrypt into Solana-based and gated-access functionality.

---

## Core Focus

Zencrypt Tech is built around a few consistent ideas:

- practical encryption tooling
- privacy-first workflows
- multiple access paths depending on user preference
- clean separation between products and releases
- modular design that can keep growing without collapsing into one codebase
- steady iteration instead of one-off builds

The goal is not just to build one tool, but to maintain a family of tools that stay organized as they evolve.

---

## Platform Differences

Each product serves a different delivery path:

- **CLI** is for local-first and terminal-based workflows.
- **GUI** is for desktop users who want Zencrypt without command-line friction.
- **Webapp** is for browser-based access to the main encryption workflow.
- **dApp** is for wallet-connected access, Solana integrations, and Web3-specific gating.

This separation keeps each codebase easier to maintain while still preserving the shared Zencrypt identity.

---

## Technology

The Zencrypt ecosystem spans multiple languages, frameworks, and delivery models.

**Current stack includes:**

- Python
- Java
- Flask
- SQLAlchemy
- JWT-based authentication
- CSRF protection
- rate limiting
- cryptographic key handling
- Argon2-related functionality
- HTML / CSS / JavaScript
- desktop GUI tooling
- Solana wallet integration
- Web3 authentication and gated-access patterns

---

## Releases

Each major product is maintained in its own repository so version history, binaries, and documentation stay separate.

General release model:

- source code lives in each product repository
- packaged builds belong in **GitHub Releases**
- product-specific setup and usage live in each repo README
- screenshots, demos, and platform notes stay with the relevant repo

This keeps Zencrypt easier to navigate and easier to maintain as the platform grows.

---

## Status

Zencrypt Tech is under active development.

Some products are more mature than others, but the organization structure is designed to keep each version separated, documented, and easier to maintain over time. The focus is on preserving clear product boundaries while continuing to improve the shared Zencrypt ecosystem.

---

## Documentation

Each repository should contain its own:

- platform-specific notes relevant to that product
- product-specific details and documentation
- installation instructions **or** usage examples
- release notes or changelogs
- screenshots or demos

The organization README exists to show the overall ecosystem at a glance.

---

## Notes

Zencrypt Tech is intentionally organized as a product family rather than a single monolithic application.

That separation is part of the design:

- each product can stand on its own
- each repo can keep its own release cycle
- each codebase can be improved without cluttering the rest
- the broader Zencrypt identity stays consistent across all platforms
