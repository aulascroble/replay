[@puppeteer/replay](../README.md) / [Schema](../modules/Schema.md) / EmulateNetworkConditionsStep

# Interface: EmulateNetworkConditionsStep

[Schema](../modules/Schema.md).EmulateNetworkConditionsStep

## Hierarchy

- [`StepWithTarget`](Schema.StepWithTarget.md)

  ↳ **`EmulateNetworkConditionsStep`**

## Table of contents

### Properties

- [assertedEvents](Schema.EmulateNetworkConditionsStep.md#assertedevents)
- [download](Schema.EmulateNetworkConditionsStep.md#download)
- [latency](Schema.EmulateNetworkConditionsStep.md#latency)
- [target](Schema.EmulateNetworkConditionsStep.md#target)
- [timeout](Schema.EmulateNetworkConditionsStep.md#timeout)
- [type](Schema.EmulateNetworkConditionsStep.md#type)
- [upload](Schema.EmulateNetworkConditionsStep.md#upload)

## Properties

### assertedEvents

• `Optional` **assertedEvents**: [`NavigationEvent`](Schema.NavigationEvent.md)[]

#### Inherited from

[StepWithTarget](Schema.StepWithTarget.md).[assertedEvents](Schema.StepWithTarget.md#assertedevents)

#### Defined in

[Schema.ts:63](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L63)

---

### download

• **download**: `number`

#### Defined in

[Schema.ts:155](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L155)

---

### latency

• **latency**: `number`

#### Defined in

[Schema.ts:157](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L157)

---

### target

• `Optional` **target**: `string`

Defaults to main

#### Inherited from

[StepWithTarget](Schema.StepWithTarget.md).[target](Schema.StepWithTarget.md#target)

#### Defined in

[Schema.ts:70](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L70)

---

### timeout

• `Optional` **timeout**: `number`

#### Inherited from

[StepWithTarget](Schema.StepWithTarget.md).[timeout](Schema.StepWithTarget.md#timeout)

#### Defined in

[Schema.ts:62](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L62)

---

### type

• **type**: [`EmulateNetworkConditions`](../enums/Schema.StepType.md#emulatenetworkconditions)

#### Overrides

[StepWithTarget](Schema.StepWithTarget.md).[type](Schema.StepWithTarget.md#type)

#### Defined in

[Schema.ts:154](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L154)

---

### upload

• **upload**: `number`

#### Defined in

[Schema.ts:156](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L156)
