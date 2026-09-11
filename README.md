<div align="center">

<img width="100%" src="assets/readme-hero.svg" alt="Leviathan SDK">

<br>

<img src="https://img.shields.io/badge/status-preparing-06131d?style=flat-square" alt="Preparing">
<img src="https://img.shields.io/badge/license-Apache--2.0-06131d?style=flat-square" alt="Apache 2.0">
<img src="https://img.shields.io/badge/interfaces-public%20only-06131d?style=flat-square" alt="Public interfaces only">

**Developer interfaces for supported Leviathan APIs, integrations, tools and services.**

[Guide](GUIDE.md) · [API Docs](https://github.com/Lapinite/Leviathan-API-Docs) · [Examples](https://github.com/Lapinite/Leviathan-Examples) · [Integrations](https://github.com/Lapinite/Leviathan-Integrations) · [Security](SECURITY.md)

</div>

## SDK architecture

<p align="center">
  <img width="100%" src="assets/sdk-flow.svg" alt="Animated Leviathan SDK public interface flow">
</p>

The SDK is intended to make intentionally public Leviathan contracts easier to consume from applications, plugins, server tools and integration projects. It should provide typed clients, public models, error handling, pagination, webhook verification, compatibility helpers and safe defaults without exposing private platform internals.

## Status

The SDK is being prepared. This repository currently contains documentation and licensing, with no distributable SDK implementation or verified installation command yet.

Planned SDK work may include:

- typed API clients
- authentication helpers for supported public flows
- request and response models
- error handling
- pagination helpers
- webhook verification helpers
- version and compatibility utilities
- integration-focused developer tooling

Planned capabilities are not production promises and may change before implementation is published.

## External service boundaries

Where a public SDK flow touches Microsoft, Xbox, Minecraft, Discord or another third-party platform, those systems remain external service boundaries. Leviathan SDK helpers should expose only the minimum documented public behavior required for supported integrations and must not attempt to hide or bypass third-party authentication, entitlement, permission or security requirements.

## Security boundaries

The SDK must not embed production credentials, client secrets, access tokens, refresh tokens, private keys, signing material, private endpoints, database credentials, personal information, or administrative secrets.

Applications using the SDK are responsible for protecting their own credentials and following the security and authentication requirements of the services they use.

## Compatibility and versioning

Compatibility information will be documented as implementations become available. Public releases should identify supported API versions, breaking changes, migration requirements, and platform assumptions clearly.

## Developer resources

| Resource | Purpose |
| --- | --- |
| [Public Guide](GUIDE.md) | SDK scope, availability and supported concepts |
| [API Docs](https://github.com/Lapinite/Leviathan-API-Docs) | Public API contracts |
| [Examples](https://github.com/Lapinite/Leviathan-Examples) | Small implementation patterns |
| [Integrations](https://github.com/Lapinite/Leviathan-Integrations) | Supported platform integration patterns |
| [Leviathan Docs](https://github.com/Lapinite/Leviathan-Docs) | Ecosystem-level documentation |

## License

This repository uses the Apache License 2.0. See [LICENSE](LICENSE).
