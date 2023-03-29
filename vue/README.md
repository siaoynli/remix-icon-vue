### remix icon vue 图标组件

https://remixicon.com/

### 注意

- 4k-fill 和 4k-line 改为 video-4k-fill,video-4k-line
- 24-hours-fill 和 24-hours-line 改为 hours-24-fill hours-24-line

其他跟官方网站一致

### 使用方法课参考 element-icon

```
//全局引入
import * as RemixIcons from '@remix-ui/icons-vue'

for (const [key, component] of Object.entries(RemixIcons)) {
  app.component(key, component)
}

//使用组件
 <AncientGateFill />
```
