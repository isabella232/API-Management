# Self-hosted API gateway changelog

## Release - self-hosted gateway: 1.1.2

*December 18, 2020*

New **stable** version of the [self-hosted gateway](https://aka.ms/apim/shgw/overview) is now available. Full list of container versions can be found [here](https://mcr.microsoft.com/v2/azure-api-management/gateway/tags/list).

### New

None

### Bug fixes

1. Rate limit policy throttling at a lower than configured rate.

### Breaking changes

None

## Release - self-hosted gateway: 1.1.1

*November 3, 2020*

New **stable** version of the [self-hosted gateway](https://aka.ms/apim/shgw/overview) is now available. Full list of container versions can be found [here](https://mcr.microsoft.com/v2/azure-api-management/gateway/tags/list).

### New

None

### Bug fixes

1. TLS connection to upstream is unexpectedly terminated under certain conditions.

### Breaking changes

None

## Release - self-hosted gateway: 1.1.0

*October 14, 2020*

New **stable** version of the [self-hosted gateway](https://aka.ms/apim/shgw/overview) is now available. Full list of container versions can be found [here](https://mcr.microsoft.com/v2/azure-api-management/gateway/tags/list).

### New

1. Migrated to [.NET Core 3.1](https://docs.microsoft.com/dotnet/core/whats-new/dotnet-core-3-1).
2. Migrated to [mcr.microsoft.com/dotnet/core/aspnet:3.1.8-alpine3.12]() base image.

### Bug fixes

1. Connection closed (not re-used) when empty response is received from the upstream.
2. External cache selection is not updated when self-hosted gateway location is changed.

### Breaking changes

None
