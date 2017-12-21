## Button

### Markup

```html
<MButton raised on:click="onClick">Button</MButton>
<MButton unelevated icon="cloud">Button</MButton>
<MButton disabled>Button</MButton>
<MButton href="https://github.com/elcobvg/svelte-material">Github</MButton>
```
### Props

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| icon | String | - | false | icon button
| raised | Boolean | - | false | raised button
| unelevated | Boolean | - | false | unelevated button
| stroked | Boolean | - | false | stroked button
| dense | Boolean | - | false | dense button
| compact | Boolean | - | false | compact button
| href | String | - | false | link button

Non prop attributes and events are mapped to the inner button element.

### Slots

| Slot | Prop dependencies | Description |
|------|-------------------|-------------|
| default | - | button label |

### Reference

- https://github.com/material-components/material-components-web/tree/master/packages/mdc-button
