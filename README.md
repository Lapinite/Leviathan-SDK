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

<p align="center"><img width="100%" src="assets/sdk-flow.svg" alt="Animated Leviathan SDK public interface flow"></p>

<p align="center"><sub>Public developer interfaces sit between supported applications and deliberately exposed Leviathan contracts.</sub></p>

## Capability map

<p align="center"><img width="100%" src="assets/capability-map.svg" alt="Animated Leviathan SDK capability map"></p>

<p align="center"><sub>The SDK is being prepared. Capabilities shown above are the intended public developer surface and may evolve before implementation is published.</sub></p>

## External service boundaries

Where a public SDK flow touches Microsoft, Xbox, Minecraft, Discord or another third-party platform, those systems remain external service boundaries. Leviathan SDK helpers expose only the documented behavior required for supported integrations and do not bypass third-party authentication, entitlement, permission or security requirements.

## Security boundaries

The SDK must not embed production credentials, client secrets, access tokens, refresh tokens, private keys, signing material, private endpoints, database credentials, personal information or administrative secrets.

Applications using the SDK remain responsible for protecting their own credentials and following the security requirements of the services they use.

## Compatibility and versioning

Compatibility information will be documented as implementations become available. Public releases should identify supported API versions, breaking changes, migration requirements and platform assumptions clearly.

## Developer resources

<p align="center">
<a href="GUIDE.md"><strong>Public Guide</strong></a> ·
<a href="https://github.com/Lapinite/Leviathan-API-Docs"><strong>API Docs</strong></a> ·
<a href="https://github.com/Lapinite/Leviathan-Examples"><strong>Examples</strong></a> ·
<a href="https://github.com/Lapinite/Leviathan-Integrations"><strong>Integrations</strong></a> ·
<a href="https://github.com/Lapinite/Leviathan-Docs"><strong>Docs</strong></a>
</p>

## License

This repository uses the Apache License 2.0. See [LICENSE](LICENSE).
