[libmev](../README.md) / [Exports](../modules.md) / FlashbotsBundleRawTransaction

# Interface: FlashbotsBundleRawTransaction

## Table of contents

### Properties

- [signedTransaction](flashbotsbundlerawtransaction.md#signedtransaction)

## Properties

### signedTransaction

• **signedTransaction**: *string*

Defined in: [src/index.ts:21](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L21)
[libmev](../README.md) / [Exports](../modules.md) / FlashbotsBundleTransaction

# Interface: FlashbotsBundleTransaction

## Table of contents

### Properties

- [signer](flashbotsbundletransaction.md#signer)
- [transaction](flashbotsbundletransaction.md#transaction)

## Properties

### signer

• **signer**: *Signer*

Defined in: [src/index.ts:26](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L26)

___

### transaction

• **transaction**: TransactionRequest

Defined in: [src/index.ts:25](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L25)
[libmev](../README.md) / [Exports](../modules.md) / FlashbotsOptions

# Interface: FlashbotsOptions

## Table of contents

### Properties

- [maxTimestamp](flashbotsoptions.md#maxtimestamp)
- [minTimestamp](flashbotsoptions.md#mintimestamp)

## Properties

### maxTimestamp

• `Optional` **maxTimestamp**: *number*

Defined in: [src/index.ts:31](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L31)

___

### minTimestamp

• `Optional` **minTimestamp**: *number*

Defined in: [src/index.ts:30](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L30)
[libmev](../README.md) / [Exports](../modules.md) / FlashbotsTransactionResponse

# Interface: FlashbotsTransactionResponse

## Table of contents

### Properties

- [bundleTransactions](flashbotstransactionresponse.md#bundletransactions)
- [receipts](flashbotstransactionresponse.md#receipts)
- [simulate](flashbotstransactionresponse.md#simulate)
- [wait](flashbotstransactionresponse.md#wait)

## Properties

### bundleTransactions

• **bundleTransactions**: [*TransactionAccountNonce*](transactionaccountnonce.md)[]

Defined in: [src/index.ts:42](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L42)

___

### receipts

• **receipts**: () => *Promise*<TransactionReceipt[]\>

#### Type declaration:

▸ (): *Promise*<TransactionReceipt[]\>

**Returns:** *Promise*<TransactionReceipt[]\>

Defined in: [src/index.ts:45](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L45)

Defined in: [src/index.ts:45](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L45)

___

### simulate

• **simulate**: () => *Promise*<[*SimulationResponse*](../modules.md#simulationresponse)\>

#### Type declaration:

▸ (): *Promise*<[*SimulationResponse*](../modules.md#simulationresponse)\>

**Returns:** *Promise*<[*SimulationResponse*](../modules.md#simulationresponse)\>

Defined in: [src/index.ts:44](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L44)

Defined in: [src/index.ts:44](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L44)

___

### wait

• **wait**: () => *Promise*<[*FlashbotsBundleResolution*](../enums/flashbotsbundleresolution.md)\>

#### Type declaration:

▸ (): *Promise*<[*FlashbotsBundleResolution*](../enums/flashbotsbundleresolution.md)\>

**Returns:** *Promise*<[*FlashbotsBundleResolution*](../enums/flashbotsbundleresolution.md)\>

Defined in: [src/index.ts:43](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L43)

Defined in: [src/index.ts:43](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L43)
[libmev](../README.md) / [Exports](../modules.md) / GetUserStatsResponseSuccess

# Interface: GetUserStatsResponseSuccess

## Table of contents

### Properties

- [avg\_gas\_price\_gwei](getuserstatsresponsesuccess.md#avg_gas_price_gwei)
- [avg\_gas\_price\_gwei\_last\_5m](getuserstatsresponsesuccess.md#avg_gas_price_gwei_last_5m)
- [avg\_gas\_price\_gwei\_last\_7d](getuserstatsresponsesuccess.md#avg_gas_price_gwei_last_7d)
- [avg\_gas\_price\_gwei\_last\_numberd](getuserstatsresponsesuccess.md#avg_gas_price_gwei_last_numberd)
- [avg\_gas\_price\_gwei\_last\_numberh](getuserstatsresponsesuccess.md#avg_gas_price_gwei_last_numberh)
- [blocks\_won\_last\_5m](getuserstatsresponsesuccess.md#blocks_won_last_5m)
- [blocks\_won\_last\_7d](getuserstatsresponsesuccess.md#blocks_won_last_7d)
- [blocks\_won\_last\_numberd](getuserstatsresponsesuccess.md#blocks_won_last_numberd)
- [blocks\_won\_last\_numberh](getuserstatsresponsesuccess.md#blocks_won_last_numberh)
- [blocks\_won\_total](getuserstatsresponsesuccess.md#blocks_won_total)
- [bundles\_error\_5m](getuserstatsresponsesuccess.md#bundles_error_5m)
- [bundles\_error\_7d](getuserstatsresponsesuccess.md#bundles_error_7d)
- [bundles\_error\_numberd](getuserstatsresponsesuccess.md#bundles_error_numberd)
- [bundles\_error\_numberh](getuserstatsresponsesuccess.md#bundles_error_numberh)
- [bundles\_error\_total](getuserstatsresponsesuccess.md#bundles_error_total)
- [bundles\_submitted\_last\_5m](getuserstatsresponsesuccess.md#bundles_submitted_last_5m)
- [bundles\_submitted\_last\_7d](getuserstatsresponsesuccess.md#bundles_submitted_last_7d)
- [bundles\_submitted\_last\_numberd](getuserstatsresponsesuccess.md#bundles_submitted_last_numberd)
- [bundles\_submitted\_last\_numberh](getuserstatsresponsesuccess.md#bundles_submitted_last_numberh)
- [bundles\_submitted\_total](getuserstatsresponsesuccess.md#bundles_submitted_total)
- [signing\_address](getuserstatsresponsesuccess.md#signing_address)

## Properties

### avg\_gas\_price\_gwei

• **avg\_gas\_price\_gwei**: *number*

Defined in: [src/index.ts:89](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L89)

___

### avg\_gas\_price\_gwei\_last\_5m

• **avg\_gas\_price\_gwei\_last\_5m**: *number*

Defined in: [src/index.ts:105](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L105)

___

### avg\_gas\_price\_gwei\_last\_7d

• **avg\_gas\_price\_gwei\_last\_7d**: *number*

Defined in: [src/index.ts:93](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L93)

___

### avg\_gas\_price\_gwei\_last\_numberd

• **avg\_gas\_price\_gwei\_last\_numberd**: *number*

Defined in: [src/index.ts:97](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L97)

___

### avg\_gas\_price\_gwei\_last\_numberh

• **avg\_gas\_price\_gwei\_last\_numberh**: *number*

Defined in: [src/index.ts:101](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L101)

___

### blocks\_won\_last\_5m

• **blocks\_won\_last\_5m**: *number*

Defined in: [src/index.ts:102](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L102)

___

### blocks\_won\_last\_7d

• **blocks\_won\_last\_7d**: *number*

Defined in: [src/index.ts:90](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L90)

___

### blocks\_won\_last\_numberd

• **blocks\_won\_last\_numberd**: *number*

Defined in: [src/index.ts:94](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L94)

___

### blocks\_won\_last\_numberh

• **blocks\_won\_last\_numberh**: *number*

Defined in: [src/index.ts:98](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L98)

___

### blocks\_won\_total

• **blocks\_won\_total**: *number*

Defined in: [src/index.ts:86](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L86)

___

### bundles\_error\_5m

• **bundles\_error\_5m**: *number*

Defined in: [src/index.ts:104](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L104)

___

### bundles\_error\_7d

• **bundles\_error\_7d**: *number*

Defined in: [src/index.ts:92](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L92)

___

### bundles\_error\_numberd

• **bundles\_error\_numberd**: *number*

Defined in: [src/index.ts:96](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L96)

___

### bundles\_error\_numberh

• **bundles\_error\_numberh**: *number*

Defined in: [src/index.ts:100](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L100)

___

### bundles\_error\_total

• **bundles\_error\_total**: *number*

Defined in: [src/index.ts:88](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L88)

___

### bundles\_submitted\_last\_5m

• **bundles\_submitted\_last\_5m**: *number*

Defined in: [src/index.ts:103](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L103)

___

### bundles\_submitted\_last\_7d

• **bundles\_submitted\_last\_7d**: *number*

Defined in: [src/index.ts:91](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L91)

___

### bundles\_submitted\_last\_numberd

• **bundles\_submitted\_last\_numberd**: *number*

Defined in: [src/index.ts:95](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L95)

___

### bundles\_submitted\_last\_numberh

• **bundles\_submitted\_last\_numberh**: *number*

Defined in: [src/index.ts:99](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L99)

___

### bundles\_submitted\_total

• **bundles\_submitted\_total**: *number*

Defined in: [src/index.ts:87](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L87)

___

### signing\_address

• **signing\_address**: *string*

Defined in: [src/index.ts:85](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L85)
[libmev](../README.md) / [Exports](../modules.md) / RelayResponseError

# Interface: RelayResponseError

## Table of contents

### Properties

- [error](relayresponseerror.md#error)

## Properties

### error

• **error**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`code` | *number* |
`message` | *string* |

Defined in: [src/index.ts:68](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L68)
[libmev](../README.md) / [Exports](../modules.md) / SimulationResponseSuccess

# Interface: SimulationResponseSuccess

## Table of contents

### Properties

- [bundleHash](simulationresponsesuccess.md#bundlehash)
- [coinbaseDiff](simulationresponsesuccess.md#coinbasediff)
- [firstRevert](simulationresponsesuccess.md#firstrevert)
- [results](simulationresponsesuccess.md#results)
- [totalGasUsed](simulationresponsesuccess.md#totalgasused)

## Properties

### bundleHash

• **bundleHash**: *string*

Defined in: [src/index.ts:75](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L75)

___

### coinbaseDiff

• **coinbaseDiff**: *BigNumber*

Defined in: [src/index.ts:76](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L76)

___

### firstRevert

• `Optional` **firstRevert**: [*TransactionSimulation*](../modules.md#transactionsimulation)

Defined in: [src/index.ts:79](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L79)

___

### results

• **results**: [*TransactionSimulation*](../modules.md#transactionsimulation)[]

Defined in: [src/index.ts:77](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L77)

___

### totalGasUsed

• **totalGasUsed**: *number*

Defined in: [src/index.ts:78](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L78)
[libmev](../README.md) / [Exports](../modules.md) / TransactionAccountNonce

# Interface: TransactionAccountNonce

## Table of contents

### Properties

- [account](transactionaccountnonce.md#account)
- [hash](transactionaccountnonce.md#hash)
- [nonce](transactionaccountnonce.md#nonce)
- [signedTransaction](transactionaccountnonce.md#signedtransaction)

## Properties

### account

• **account**: *string*

Defined in: [src/index.ts:37](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L37)

___

### hash

• **hash**: *string*

Defined in: [src/index.ts:35](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L35)

___

### nonce

• **nonce**: *number*

Defined in: [src/index.ts:38](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L38)

___

### signedTransaction

• **signedTransaction**: *string*

Defined in: [src/index.ts:36](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L36)
[libmev](../README.md) / [Exports](../modules.md) / TransactionSimulationBase

# Interface: TransactionSimulationBase

## Hierarchy

* **TransactionSimulationBase**

  ↳ [*TransactionSimulationSuccess*](transactionsimulationsuccess.md)

  ↳ [*TransactionSimulationRevert*](transactionsimulationrevert.md)

## Table of contents

### Properties

- [gasUsed](transactionsimulationbase.md#gasused)
- [txHash](transactionsimulationbase.md#txhash)

## Properties

### gasUsed

• **gasUsed**: *number*

Defined in: [src/index.ts:50](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L50)

___

### txHash

• **txHash**: *string*

Defined in: [src/index.ts:49](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L49)
[libmev](../README.md) / [Exports](../modules.md) / TransactionSimulationRevert

# Interface: TransactionSimulationRevert

## Hierarchy

* [*TransactionSimulationBase*](transactionsimulationbase.md)

  ↳ **TransactionSimulationRevert**

## Table of contents

### Properties

- [error](transactionsimulationrevert.md#error)
- [gasUsed](transactionsimulationrevert.md#gasused)
- [revert](transactionsimulationrevert.md#revert)
- [txHash](transactionsimulationrevert.md#txhash)

## Properties

### error

• **error**: *string*

Defined in: [src/index.ts:59](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L59)

___

### gasUsed

• **gasUsed**: *number*

Inherited from: [TransactionSimulationBase](transactionsimulationbase.md).[gasUsed](transactionsimulationbase.md#gasused)

Defined in: [src/index.ts:50](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L50)

___

### revert

• **revert**: *string*

Defined in: [src/index.ts:60](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L60)

___

### txHash

• **txHash**: *string*

Inherited from: [TransactionSimulationBase](transactionsimulationbase.md).[txHash](transactionsimulationbase.md#txhash)

Defined in: [src/index.ts:49](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L49)
[libmev](../README.md) / [Exports](../modules.md) / TransactionSimulationSuccess

# Interface: TransactionSimulationSuccess

## Hierarchy

* [*TransactionSimulationBase*](transactionsimulationbase.md)

  ↳ **TransactionSimulationSuccess**

## Table of contents

### Properties

- [gasUsed](transactionsimulationsuccess.md#gasused)
- [txHash](transactionsimulationsuccess.md#txhash)
- [value](transactionsimulationsuccess.md#value)

## Properties

### gasUsed

• **gasUsed**: *number*

Inherited from: [TransactionSimulationBase](transactionsimulationbase.md).[gasUsed](transactionsimulationbase.md#gasused)

Defined in: [src/index.ts:50](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L50)

___

### txHash

• **txHash**: *string*

Inherited from: [TransactionSimulationBase](transactionsimulationbase.md).[txHash](transactionsimulationbase.md#txhash)

Defined in: [src/index.ts:49](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L49)

___

### value

• **value**: *string*

Defined in: [src/index.ts:55](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L55)
