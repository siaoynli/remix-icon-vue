### vue 图标组件

图标官网 https://remixicon.com/

### 注意

- 4k-fill 和 4k-line 改为 video-4k-fill,video-4k-line
- 24-hours-fill 和 24-hours-line 改为 hours-24-fill hours-24-line
  其他图标名称跟官方网站一致

### 全局引入

```
import * as RemixIcons from '@remix-ui/icons-vue'

for (const [key, component] of Object.entries(RemixIcons)) {
  app.component(key, component)
}
```

### 局部引入

```
import {AncientGateFill} from 'remix-icons-vue'
```

### 使用方法

```
//naive ui
 <n-icon size="40" color="#0e7a0d" :depth="3">
   <AncientGateFill />
 </n-icon>

//element-ui
<el-icon> <AncientGateFill /></el-icon>

```
