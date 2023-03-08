# Scrollbar
> 灵感来源于element-ui的el-scrollbar组件
> 
> 作为Web Components，不依赖任何前端框架，即便是最普通的html页面也可以使用

## 使用方法

#### script标签

```html
<scroll-bar wrap-style="height: 100vh;">
  <!-- 内容块 -->
</scroll-bar>

<script src="/dist/scrollbar.iife.js"></script>
<script>
  window.CustomElement.register('scroll-bar') // register方法设置自定义标签名，默认 scroll-bar
</script>
```

#### vue

```vue
import { register } from '/dist/scrollbar.es.js'
register('scroll-bar')

<scroll-bar wrap-style="height: 100vh;">
<!-- 内容块 -->
</scroll-bar>
```

#### react

```react

```