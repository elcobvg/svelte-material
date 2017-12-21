## Card

### Markup

```html
<MCard>
    <MCardMediaItem slot="media" height="1" src="..." />
    <MTitle slot="title">Title</MTitle>
    <MSubheading level="1" slot="subtitle">
        Subtitle
    </MSubheading>
    <MBody level="1" slot="supportingText">
        Text
    </MBody>
    <MButton slot="actions">Action</MButton>
</MCard>
```

### Props

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| verticalActions | Boolean | - | false | renders actions vertical |
| largeTitle | Boolean | - | false | larger title (without typography component)| 
| horizontal | Boolean | -| false | renders media, title & subtitle horizontal

### Slots

| Slot | Prop dependencies | Description |
|------|-------------------|-------------|
| horizontalMedia | horizontal | horizontal card media item |
| horizontalTitle | horizontal, largeTitle | horizontal card title |
| horizontalSubtitle | horizontal | horizontal card subtitle |
| media | - | card media item |
| title | largeTitle | card title |
| subtitle | - | card subtitle |
| supportingText | - | card text |
| actions | verticalActions | card actions

## CardMediaItem

### Props

| Prop | Type | Default | Required | Description |
|------|------|---------|----------|-------------|
| height | Number | - | false | image scale between 1 and 3


### Reference
- https://github.com/material-components/material-components-web/tree/master/packages/mdc-card
