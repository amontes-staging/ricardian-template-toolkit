[ricardian-template-toolkit](../README.md) > ["specVersions/v0.1/RicardianContractProcessorImpl"](../modules/_specversions_v0_1_ricardiancontractprocessorimpl_.md) > [RicardianContractProcessorImpl](../classes/_specversions_v0_1_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md)

# Class: RicardianContractProcessorImpl

## Hierarchy

 [RicardianContractProcessorImpl](_specversions_v0_0_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md)

**↳ RicardianContractProcessorImpl**

## Implements

* [RicardianContractProcessor](../interfaces/_interfaces_.ricardiancontractprocessor.md)

## Index

### Constructors

* [constructor](_specversions_v0_1_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md#constructor)

### Properties

* [major](_specversions_v0_1_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md#major)
* [minor](_specversions_v0_1_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md#minor)

### Methods

* [getSpecVersion](_specversions_v0_1_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md#getspecversion)
* [process](_specversions_v0_1_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md#process)
* [registerWrappedHelper](_specversions_v0_1_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md#registerwrappedhelper)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new RicardianContractProcessorImpl**(): [RicardianContractProcessorImpl](_specversions_v0_1_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md)

*Overrides [RicardianContractProcessorImpl](_specversions_v0_0_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md).[constructor](_specversions_v0_0_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md#constructor)*

*Defined in [specVersions/v0.1/RicardianContractProcessorImpl.ts:9](https://github.com/EOSIO/ricardian-template-toolkit/blob/76dafef/src/specVersions/v0.1/RicardianContractProcessorImpl.ts#L9)*

**Returns:** [RicardianContractProcessorImpl](_specversions_v0_1_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md)

___

## Properties

<a id="major"></a>

### `<Private>` major

**● major**: *`0`* = 0

*Defined in [specVersions/v0.1/RicardianContractProcessorImpl.ts:8](https://github.com/EOSIO/ricardian-template-toolkit/blob/76dafef/src/specVersions/v0.1/RicardianContractProcessorImpl.ts#L8)*

___
<a id="minor"></a>

### `<Private>` minor

**● minor**: *`1`* = 1

*Defined in [specVersions/v0.1/RicardianContractProcessorImpl.ts:9](https://github.com/EOSIO/ricardian-template-toolkit/blob/76dafef/src/specVersions/v0.1/RicardianContractProcessorImpl.ts#L9)*

___

## Methods

<a id="getspecversion"></a>

###  getSpecVersion

▸ **getSpecVersion**(): `object`

*Implementation of [RicardianContractProcessor](../interfaces/_interfaces_.ricardiancontractprocessor.md).[getSpecVersion](../interfaces/_interfaces_.ricardiancontractprocessor.md#getspecversion)*

*Overrides [RicardianContractProcessorImpl](_specversions_v0_0_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md).[getSpecVersion](_specversions_v0_0_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md#getspecversion)*

*Defined in [specVersions/v0.1/RicardianContractProcessorImpl.ts:54](https://github.com/EOSIO/ricardian-template-toolkit/blob/76dafef/src/specVersions/v0.1/RicardianContractProcessorImpl.ts#L54)*

**Returns:** `object`

___
<a id="process"></a>

###  process

▸ **process**(config: *[RicardianContractConfig](../interfaces/_interfaces_.ricardiancontractconfig.md)*): [RicardianContract](../interfaces/_interfaces_.ricardiancontract.md)

*Implementation of [RicardianContractProcessor](../interfaces/_interfaces_.ricardiancontractprocessor.md).[process](../interfaces/_interfaces_.ricardiancontractprocessor.md#process)*

*Overrides [RicardianContractProcessorImpl](_specversions_v0_0_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md).[process](_specversions_v0_0_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md#process)*

*Defined in [specVersions/v0.1/RicardianContractProcessorImpl.ts:44](https://github.com/EOSIO/ricardian-template-toolkit/blob/76dafef/src/specVersions/v0.1/RicardianContractProcessorImpl.ts#L44)*

Process the RicardianContractConfig and return a RicardianContract.

**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| config | [RicardianContractConfig](../interfaces/_interfaces_.ricardiancontractconfig.md) |  A \`RicardianContractConfig\` object |

**Returns:** [RicardianContract](../interfaces/_interfaces_.ricardiancontract.md)

___
<a id="registerwrappedhelper"></a>

### `<Protected>` registerWrappedHelper

▸ **registerWrappedHelper**(name: *`string`*, fn: *`HelperDelegate`*): `void`

*Inherited from [RicardianContractProcessorImpl](_specversions_v0_0_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md).[registerWrappedHelper](_specversions_v0_0_ricardiancontractprocessorimpl_.ricardiancontractprocessorimpl.md#registerwrappedhelper)*

*Defined in [specVersions/v0.0/RicardianContractProcessorImpl.ts:56](https://github.com/EOSIO/ricardian-template-toolkit/blob/76dafef/src/specVersions/v0.0/RicardianContractProcessorImpl.ts#L56)*

**Parameters:**

| Param | Type |
| ------ | ------ |
| name | `string` |
| fn | `HelperDelegate` |

**Returns:** `void`

___

