[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / FeeQuoteSource

# Type Alias: FeeQuoteSource

> **FeeQuoteSource** = `"simulation"` \| `"fallback"`

Defined in: [fee-estimator/fee-estimator.types.ts:10](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/fee-estimator/fee-estimator.types.ts#L10)

How the fee estimate was derived.
- `simulation` — live `simulateTransaction` RPC call (most accurate)
- `fallback`   — static heuristic used when simulation is unavailable
