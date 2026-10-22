[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / FeeQuoteWarning

# Interface: FeeQuoteWarning

Defined in: [fee-estimator/fee-estimator.types.ts:24](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/fee-estimator/fee-estimator.types.ts#L24)

User-visible warnings attached to a fee quote.
Consumers should surface at least the `message` in their UI.

## Properties

### code

> **code**: `"STALE_QUOTE"` \| `"FALLBACK_ESTIMATE"` \| `"MAX_FEE_EXCEEDED"` \| `"SIMULATION_ERROR"`

Defined in: [fee-estimator/fee-estimator.types.ts:26](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/fee-estimator/fee-estimator.types.ts#L26)

Machine-readable code for programmatic handling

***

### message

> **message**: `string`

Defined in: [fee-estimator/fee-estimator.types.ts:28](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/fee-estimator/fee-estimator.types.ts#L28)

Human-readable explanation
