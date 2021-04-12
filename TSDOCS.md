libmev / [Exports](modules.md)

# [libmev](#)

[![CI](https://github.com/sambacha/libmev/actions/workflows/main.yml/badge.svg)](https://github.com/sambacha/libmev/actions/workflows/main.yml)

> miner extracted value library

### Overview 

> [libmev overview](https://sambacha.github.io/libmev/modules.html)

## License

SPDX-License-Identifier: MIT AND SSPL-1.0
[libmev](../README.md) / [Exports](../modules.md) / FlashbotsBundleResolution

# Enumeration: FlashbotsBundleResolution

## Table of contents

### Enumeration members

- [AccountNonceTooHigh](flashbotsbundleresolution.md#accountnoncetoohigh)
- [BlockPassedWithoutInclusion](flashbotsbundleresolution.md#blockpassedwithoutinclusion)
- [BundleIncluded](flashbotsbundleresolution.md#bundleincluded)

## Enumeration members

### AccountNonceTooHigh

• **AccountNonceTooHigh**: = 2

Defined in: [src/index.ts:17](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L17)

___

### BlockPassedWithoutInclusion

• **BlockPassedWithoutInclusion**: = 1

Defined in: [src/index.ts:16](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L16)

___

### BundleIncluded

• **BundleIncluded**: = 0

Defined in: [src/index.ts:15](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L15)
[libmev](README.md) / Exports

# libmev

## Table of contents

### Enumerations

- [FlashbotsBundleResolution](enums/flashbotsbundleresolution.md)

### Classes

- [FlashbotsBundleProvider](classes/flashbotsbundleprovider.md)

### Interfaces

- [FlashbotsBundleRawTransaction](interfaces/flashbotsbundlerawtransaction.md)
- [FlashbotsBundleTransaction](interfaces/flashbotsbundletransaction.md)
- [FlashbotsOptions](interfaces/flashbotsoptions.md)
- [FlashbotsTransactionResponse](interfaces/flashbotstransactionresponse.md)
- [GetUserStatsResponseSuccess](interfaces/getuserstatsresponsesuccess.md)
- [RelayResponseError](interfaces/relayresponseerror.md)
- [SimulationResponseSuccess](interfaces/simulationresponsesuccess.md)
- [TransactionAccountNonce](interfaces/transactionaccountnonce.md)
- [TransactionSimulationBase](interfaces/transactionsimulationbase.md)
- [TransactionSimulationRevert](interfaces/transactionsimulationrevert.md)
- [TransactionSimulationSuccess](interfaces/transactionsimulationsuccess.md)

### Type aliases

- [GetUserStatsResponse](modules.md#getuserstatsresponse)
- [SimulationResponse](modules.md#simulationresponse)
- [TransactionSimulation](modules.md#transactionsimulation)

### Variables

- [DEFAULT\_FLASHBOTS\_RELAY](modules.md#default_flashbots_relay)

## Type aliases

### GetUserStatsResponse

Ƭ **GetUserStatsResponse**: [*GetUserStatsResponseSuccess*](interfaces/getuserstatsresponsesuccess.md) \| [*RelayResponseError*](interfaces/relayresponseerror.md)

Defined in: [src/index.ts:108](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L108)

___

### SimulationResponse

Ƭ **SimulationResponse**: [*SimulationResponseSuccess*](interfaces/simulationresponsesuccess.md) \| [*RelayResponseError*](interfaces/relayresponseerror.md)

Defined in: [src/index.ts:82](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L82)

___

### TransactionSimulation

Ƭ **TransactionSimulation**: [*TransactionSimulationSuccess*](interfaces/transactionsimulationsuccess.md) \| [*TransactionSimulationRevert*](interfaces/transactionsimulationrevert.md)

Defined in: [src/index.ts:63](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L63)

## Variables

### DEFAULT\_FLASHBOTS\_RELAY

• `Const` **DEFAULT\_FLASHBOTS\_RELAY**: *https://relay.flashbots.net*= 'https://relay.flashbots.net'

Defined in: [src/index.ts:12](https://github.com/sambacha/libmev/blob/cd0dbf2/src/index.ts#L12)
