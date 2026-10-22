[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / RaffleTransition

# Type Alias: RaffleTransition

> **RaffleTransition** = `"open→drawing"` \| `"drawing→finalized"` \| `"open→cancelled"`

Defined in: [modules/raffle/raffle.types.ts:105](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/modules/raffle/raffle.types.ts#L105)

Valid state transitions in the raffle contract state machine:

 Open ──► Drawing  (trigger_draw)
 Drawing ──► Finalized (receive_randomness → internal finalization)
 Open ──► Cancelled (cancel_raffle)

Any other transition is rejected by the contract and surfaced as
`RaffleStateError`.
