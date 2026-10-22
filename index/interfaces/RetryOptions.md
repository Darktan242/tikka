[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / RetryOptions

# Interface: RetryOptions

Defined in: [utils/retry.ts:1](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/utils/retry.ts#L1)

## Properties

### baseDelayMs?

> `optional` **baseDelayMs?**: `number`

Defined in: [utils/retry.ts:3](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/utils/retry.ts#L3)

***

### maxAttempts?

> `optional` **maxAttempts?**: `number`

Defined in: [utils/retry.ts:2](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/utils/retry.ts#L2)

***

### maxDelayMs?

> `optional` **maxDelayMs?**: `number`

Defined in: [utils/retry.ts:4](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/utils/retry.ts#L4)

***

### onRetry?

> `optional` **onRetry?**: (`attempt`, `error`, `delay`) => `void`

Defined in: [utils/retry.ts:6](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/utils/retry.ts#L6)

#### Parameters

##### attempt

`number`

##### error

`any`

##### delay

`number`

#### Returns

`void`

***

### retryOn?

> `optional` **retryOn?**: (`string` \| `number`)[]

Defined in: [utils/retry.ts:5](https://github.com/Darktan242/tikka/blob/9414ef8f17da20b6333868f7802e6d47ea9434a8/sdk/src/utils/retry.ts#L5)
