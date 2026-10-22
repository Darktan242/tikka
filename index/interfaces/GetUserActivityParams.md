[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / GetUserActivityParams

# Interface: GetUserActivityParams

Defined in: [modules/user/user.types.ts:114](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/modules/user/user.types.ts#L114)

Parameters for fetching the aggregated user activity summary.

## Properties

### address

> **address**: `string`

Defined in: [modules/user/user.types.ts:115](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/modules/user/user.types.ts#L115)

***

### includeIndexerData?

> `optional` **includeIndexerData?**: `boolean`

Defined in: [modules/user/user.types.ts:121](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/modules/user/user.types.ts#L121)

When true, the SDK will also attempt to fetch indexer-backed data
(refunds, purchase timestamps). Requires `indexerUrl` to be configured.
Defaults to false.
