# SDK developer guide

[SDK overview](README.md)

## Purpose and availability

The SDK is intended to simplify public Leviathan integrations. The current repository contains documentation and its Apache-2.0 license; it does not yet contain a distributable SDK implementation. Languages, package coordinates, and supported runtime versions are not specified.

## Supported integrations

Public API clients, Minecraft plugins, Discord adapters, and webhook consumers are planned areas. None is claimed as supported by a released SDK here. Each future adapter needs a documented service contract and compatibility entry.

## Installation

There is no verified package installation command to provide. Do not install a package merely because it uses a similar name. A release should publish its official package coordinates, version, supported runtime, license notices, and an independently usable getting-started example.

## Authentication

Authentication helpers are planned. Credentials belong to the application using the SDK and must be supplied securely at runtime. The SDK must not embed the launcher's application identifiers or forward Microsoft/Minecraft credentials to unrelated services. Public contracts will define supported flows and scopes.

## API clients

Typed clients, pagination, timeouts, and cancellation are planned capabilities. A client must target a documented public service and version. This guide deliberately supplies no base URL or callable method name.

## Error handling

Future clients should distinguish invalid input, missing authentication, insufficient permission, throttling, and transient failures. Retry only when the published contract allows it. Logging must omit credentials, sensitive headers, and raw personal payloads.

## Webhook handling

Verification helpers remain planned until a webhook contract defines signing and delivery behavior. Callers must authenticate events before processing them and handle repeat deliveries safely. Do not use an invented signature algorithm as a substitute for the eventual contract.

## Examples

[Leviathan Examples](https://github.com/Lapinite/Leviathan-Examples) contains guidance for safe examples. Examples must state the package and API versions they use once implementations are released. A placeholder configuration is not a working SDK integration.

## Compatibility and versioning

No stable compatibility matrix is available. A release must state SDK version, API version, language/runtime support, and adapter support, with migration notes for breaking changes. Do not infer stability from the repository name.

## License and security

The existing [Apache License 2.0](LICENSE) is preserved. Service access and third-party terms remain separate from the SDK license. See [SECURITY.md](SECURITY.md).
