---
category: Components
type: Form Controls
title: Checkbox
---

Checkbox.

## When To Use

- Used to select serveral values in multiple options.
- If you just use only one checkbox, it is the same as `Switch` to switch between two states. The difference is that `Switch` will trigger state change directly, but `Checkbox` just marks state changed and need to be submitted.

## API

### Checkbox

| Property      | Description             | Type      | Default  |
|----------|------------------|----------|--------|
| checked | Specifies whether the current is selected | Boolean  | false |
| defaultChecked | Initial whether or not selected | Boolean | false |
| onChange | The callback function when the state change | Function(e:Event) | - |

### Checkbox Group

| Property      | Description             | Type      | Default  |
|----------|------------------|----------|--------|
| defaultValue | Default selected value | Array | [] |
| value | Used to set the current selected value| Array | [] |
| options  | Specifies options | Array | [] |
| onChange | The callback function when the options change | Function(checkedValue) | - |
