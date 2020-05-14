[Polkadot JS UI libraries](../README.md) › [Globals](../globals.md) › ["icons/Jdenticon"](_icons_jdenticon_.md)

# Module: "icons/Jdenticon"

## Index

### Variables

* [Jdenticon](_icons_jdenticon_.md#const-jdenticon)

## Variables

### `Const` Jdenticon

• **Jdenticon**: *VueConstructor‹Data & object & object & Vue‹››* = Vue.extend({
  created: function (): void {
    this.createSvgHtml();
  },
  data: function (): Data {
    return {
      // eslint-disable-next-line quotes
      svgHtml: `<svg viewBox="0 0 64 64" />`
    };
  },
  methods: {
    createSvgHtml: function (): void {
      this.svgHtml = jdenticon.toSvg(this.publicKey.substr(2), this.size);
    }
  },
  props: ['publicKey', 'size'],
  // eslint-disable-next-line quotes
  template: `<div v-html="svgHtml" />`
})

*Defined in [icons/Jdenticon.ts:16](https://github.com/polkadot-js/ui/blob/be5ee1a71/packages/vue-identicon/src/icons/Jdenticon.ts#L16)*

**`name`** Jdenticon

**`description`** The substrate default via Jdenticon