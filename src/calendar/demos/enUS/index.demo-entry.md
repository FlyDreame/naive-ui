<!--single-column-->

# Calendar

How time flies.

## Demos

```demo
basic
```

## Props

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| default-value | `number` | `null` | Default selected date's timestamp. |
| is-date-disabled | `(timestamp: number) => boolean` | `undefined` |  |
| value | `number \| null` | `undefined` | Selected date's timestamp. |
| on-update:value | `(timestamp: number, { year: number, month: number, date: number }) => void` | `undefined` | Callback when date is selected. |

## Slots

| Name | Parameters | Description |
| --- | --- | --- |
| default | `({ year: number, month: number, date: number })` | Content to be rendered in each date. |