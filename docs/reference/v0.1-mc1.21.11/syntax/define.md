# `define`

The `define` codeblock is used to define various types of NetherScript and Minecraft data.

## Entity Selectors

Entity selectors can be defined with

```ntscript
define @NAME = @FULL_SELECTOR
```

or

```ntscript
define @NAME : @FULL_SELECTOR
```

where `@NAME` represents an `@` followed by a valid id, and `@FULL_SELECTOR` is a valid Minecraft entity selector.

:::info Example
```ntscript
define @ExplodingCow : @e[type=cow,tag=exploding_cow]
```
:::

### `create`