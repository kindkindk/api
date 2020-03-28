[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["accounts/indexes"](_accounts_indexes_.md)

# Module: "accounts/indexes"

## Index

### Functions

* [indexes](_accounts_indexes_.md#indexes)

## Functions

###  indexes

▸ **indexes**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/accounts/indexes.ts:72](https://github.com/polkadot-js/api/blob/7b8b4e8078/packages/api-derive/src/accounts/indexes.ts#L72)*

**`name`** indexes

**`description`** This is an unwieldly query since it loops through
all of the enumsets and returns all of the values found. This could be up to 32k depending
on the number of active accounts in the system

**`example`** 
<BR>

```javascript
api.derive.accounts.indexes((indexes) => {
  console.log('All existing AccountIndexes', indexes);
});
```

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

Returns all the indexes on the system.

▸ (): *Observable‹AccountIndexes›*