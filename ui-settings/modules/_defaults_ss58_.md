[Polkadot JS UI libraries](../README.md) › [Globals](../globals.md) › ["defaults/ss58"](_defaults_ss58_.md)

# Module: "defaults/ss58"

## Index

### Variables

* [PREFIXES](_defaults_ss58_.md#const-prefixes)
* [PREFIX_DEFAULT](_defaults_ss58_.md#const-prefix_default)

## Variables

### `Const` PREFIXES

• **PREFIXES**: *[Option](_types_.md#option)[]* = [
  {
    info: 'default',
    text: 'Default for the connected node',
    value: -1
  },
  // keep as first (well, after default)
  {
    info: 'substrate',
    text: 'Substrate (generic)',
    value: 42
  },
  // all in ascending order based on value
  {
    info: 'polkadot',
    text: 'Polkadot (live)',
    value: 0
  },
  {
    info: 'kusama',
    text: 'Kusama (canary)',
    value: 2
  },
  {
    info: 'edgeware',
    text: 'Edgeware (live)',
    value: 7
  }
]

*Defined in [defaults/ss58.ts:9](https://github.com/polkadot-js/ui/blob/47fa7f9f0/packages/ui-settings/src/defaults/ss58.ts#L9)*

___

### `Const` PREFIX_DEFAULT

• **PREFIX_DEFAULT**: *-1* = -1

*Defined in [defaults/ss58.ts:7](https://github.com/polkadot-js/ui/blob/47fa7f9f0/packages/ui-settings/src/defaults/ss58.ts#L7)*