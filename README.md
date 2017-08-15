# vue-material-checkbox

> Material design checkbox component for Vue

# Demo
[Here is demo with all features](https://romanrei.github.io/vue-material-checkbox/)

# Use
### With npm
- install plugin
```
npm install vue-material-checkbox --save
```
- import to the app and add to the Vue
```javascript
import checkbox from 'vue-material-checkbox'
Vue.use(checkbox)
```
- Use it as component:
```html
<checkbox id="mycheck1" v-model="someVar">My Checkbox</checkbox>
```

# Component
There is autogenerated id for label and checkbox, but you can specify it yourself.

You can specify label for checkbox inside checkbox tag:
```html
<checkbox id="mycheck1" v-model="someVar"> ThisIsLabel </checkbox>
```

You can set custom color for background of checkbox:
```html
<checkbox id="mycheck1" v-model="someVar" color="#f50057"> ThisIsLabel </checkbox>
```

You can set size of the checkbox! just add font-size inline style. Size should be `rem` or `em`.
```html
<checkbox id="mycheck1" v-model="someVar" style="font-size: 4rem"> ThisIsLabel </checkbox>
```

## Complete props table

| Prop | Type | Default | What For|
|:-:|:-:|:-:|---|
| `id` | `String` | `undefined` | **Recommended**. input id associated with label |
| `value` | `String` | `undefined` | Value for input, without it checkbox works as `true/false` |
| `color` | `String` | `undefined` | Pass the color string to change bg-color of checkbox |
| `checked` | `Boolean` | `false` | is checked by default? |
| `name` | `String` | `undefined` | Name for input |
| `required` | `Boolean` | `false` | HTML required attr |
| `disabled` | `Boolean` | `false` | HTML disabled attr |

## todo
- ripple effect