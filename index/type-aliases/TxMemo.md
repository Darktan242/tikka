[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / TxMemo

# Type Alias: TxMemo

> **TxMemo** = \{ `type`: `"text"`; `value`: `string`; \} \| \{ `type`: `"id"`; `value`: `string`; \} \| \{ `type`: `"hash"`; `value`: `Buffer`; \}

Defined in: [contract/lifecycle.ts:45](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/contract/lifecycle.ts#L45)

Transaction memo — attach tracking data or external references.
Mirrors the three Stellar memo types the protocol supports.
