# Leviathan SDK

Official public SDK repository for supported Leviathan developer interfaces.

## Navigation

See the [public guide](GUIDE.md) for availability, usage boundaries, and topic-by-topic documentation. Read [SECURITY.md](SECURITY.md) before reporting a security issue.

- [Purpose and availability](GUIDE.md#purpose-and-availability)
- [Supported integrations](GUIDE.md#supported-integrations)
- [Installation](GUIDE.md#installation)
- [Authentication](GUIDE.md#authentication)
- [API clients](GUIDE.md#api-clients)
- [Error handling](GUIDE.md#error-handling)
- [Webhook handling](GUIDE.md#webhook-handling)
- [Examples](GUIDE.md#examples)
- [Compatibility and versioning](GUIDE.md#compatibility-and-versioning)
- [License and security](GUIDE.md#license-and-security)

## Purpose

The SDK is intended to make supported Leviathan APIs and integrations easier to use from applications, plugins, tools, and services.

As the platform develops, SDK work may include:

- Typed API clients
- Authentication helpers for supported public flows
- Request and response models
- Error handling
- Pagination helpers
- Webhook verification helpers
- Version and compatibility utilities
- Integration-focused developer tooling

## Status

The SDK is being prepared. This repository currently contains documentation and licensing, with no distributable SDK implementation or verified installation command.

## Security

The SDK must not embed production credentials, client secrets, private keys, signing material, private endpoints, database credentials, or personal information.

Applications using the SDK are responsible for protecting their own secrets and following the authentication requirements of the services they use.

## Documentation and examples

See:

- [Leviathan API Docs](https://github.com/Lapinite/Leviathan-API-Docs)
- [Leviathan Examples](https://github.com/Lapinite/Leviathan-Examples)
- [Leviathan Integrations](https://github.com/Lapinite/Leviathan-Integrations)
- [Leviathan Docs](https://github.com/Lapinite/Leviathan-Docs)

## License

This repository currently uses the Apache License 2.0. See [LICENSE](LICENSE).
