[@puppeteer/replay](../README.md) / [Schema](../modules/Schema.md) / UserFlow

# Interface: UserFlow

[Schema](../modules/Schema.md).UserFlow

## Table of contents

### Properties

- [selectorAttribute](Schema.UserFlow.md#selectorattribute)
- [steps](Schema.UserFlow.md#steps)
- [timeout](Schema.UserFlow.md#timeout)
- [title](Schema.UserFlow.md#title)

## Properties

### selectorAttribute

• `Optional` **selectorAttribute**: `string`

The name of the attribute to use to generate selectors instead of regular
CSS selectors. For example, specifying `data-testid` would generate the
selector `[data-testid=value]` for the element `<div data-testid=value>`.

#### Defined in

[Schema.ts:312](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L312)

---

### steps

• **steps**: [`Step`](../modules/Schema.md#step)[]

#### Defined in

[Schema.ts:313](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L313)

---

### timeout

• `Optional` **timeout**: `number`

Timeout in milliseconds.

#### Defined in

[Schema.ts:306](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L306)

---

### title

• **title**: `string`

Human-readble title describing the recorder user flow.

#### Defined in

[Schema.ts:302](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L302)
