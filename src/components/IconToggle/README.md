## IconToggle

### Markup

```html
<MIconToggle value="{{iconToggle}}" iconOn="favorite" iconOff="favorite_border" on:input="iconEvent(event.value)" />
```

### Script 

```javascript
data() {
    return {
        iconToggle: false
    }
}
```

### Props

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| iconOn | String | - | true | material icon name when toggle is true |
| iconOff | String | - | true | material icon name when toggle is false |
| disabled | Boolean | - | false | not toggleable icon |
| primary | Boolean | - | false | primary theme color |
| accent | Boolean | - | false | secondary theme color |

### Reference

- https://material.io/icons
- https://github.com/material-components/material-components-web/tree/master/packages/mdc-icon-toggle