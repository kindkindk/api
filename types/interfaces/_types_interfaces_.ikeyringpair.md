[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["types/interfaces"](../modules/_types_interfaces_.md) › [IKeyringPair](_types_interfaces_.ikeyringpair.md)

# Interface: IKeyringPair

## Hierarchy

* **IKeyringPair**

## Index

### Properties

* [address](_types_interfaces_.ikeyringpair.md#address)
* [publicKey](_types_interfaces_.ikeyringpair.md#publickey)
* [sign](_types_interfaces_.ikeyringpair.md#sign)

## Properties

###  address

• **address**: *string*

*Defined in [packages/types/src/types/interfaces.ts:20](https://github.com/polkadot-js/api/blob/7b8b4e8078/packages/types/src/types/interfaces.ts#L20)*

___

###  publicKey

• **publicKey**: *[Uint8Array](../classes/_codec_raw_.raw.md#static-uint8array)*

*Defined in [packages/types/src/types/interfaces.ts:21](https://github.com/polkadot-js/api/blob/7b8b4e8078/packages/types/src/types/interfaces.ts#L21)*

___

###  sign

• **sign**: *function*

*Defined in [packages/types/src/types/interfaces.ts:22](https://github.com/polkadot-js/api/blob/7b8b4e8078/packages/types/src/types/interfaces.ts#L22)*

#### Type declaration:

▸ (`data`: [Uint8Array](../classes/_codec_raw_.raw.md#static-uint8array), `options?`: SignOptions): *[Uint8Array](../classes/_codec_raw_.raw.md#static-uint8array)*

**Parameters:**

Name | Type |
------ | ------ |
`data` | [Uint8Array](../classes/_codec_raw_.raw.md#static-uint8array) |
`options?` | SignOptions |