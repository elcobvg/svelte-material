## Dialog

### Markup

```html
<MDialog ref="dialog" on:accepted="dialogAccepted" on:canceled="dialogCanceled">
    <MHeadline slot="header"> Header </MHeadline>
    <span slot="body"> Body </span>
    <MButton slot="acceptButton"> Accept </MButton>
    <MButton slot="cancelButton"> Cancel </MButton>
    <MButton slot="dialogButton"> Anything </MButton>
</MDialog>
```

### Script
```javascript
this.refs.dialog.show()
```

### Props & events & methods

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| scrollable | Boolean | - | false | scrollable body |

| Event | Description |
|------|------|
| accepted | will be dispatched when the accept button will be clicked |
| canceled | will be dispatched when the cancel button will be clicked |

| Method | Description |
|--------|-------------|
| show | show the dialog |

### Slots

| Slot | Prop dependencies | Description |
|------|-------------------|-------------|
| header | - | header of dialog |
| body | - | body of dialog |
| acceptButton | - | accept button |
| cancelButton | - | cancel button |
| dialogButton | - | additional button(s) |

### Reference

- https://github.com/material-components/material-components-web/tree/master/packages/mdc-dialog
