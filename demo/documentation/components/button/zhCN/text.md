# 文本按钮
```html
<n-button text size="large">
  <template v-slot:icon>
    <n-icon>
      <cash-outline />
    </n-icon>
  </template>
  Default
</n-button>
<n-button text type="primary" ghost size="large">
  <template v-slot:icon>
    <n-icon>
      <cash-outline />
    </n-icon>
  </template>
</n-button>
<n-button text type="info" loading size="small">Info</n-button>
<n-button text type="success">Success</n-button>
<n-button text type="warning">Warning</n-button>
<n-button text type="error" icon-placement="right">
  <template v-slot:icon>
    <n-icon>
      <cash-outline />
    </n-icon>
  </template>
  Error
</n-button>
```
```js
import cashOutline from 'naive-ui/lib/icons/cash-outline'

export default {
  components: {
    cashOutline
  }
}
```
```css
.n-button {
  margin: 0 12px 8px 0;
}
```