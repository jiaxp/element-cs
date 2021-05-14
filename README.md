## Instructions
```shell
基于element-ui@2.13.2定制开发的版本，主要用于服务云系统UIUE风格统一。
```

## Install
```shell
npm install element-ui -S
```

## Quick Start
``` javascript
import Vue from 'vue'
import Element from 'element-ui-cs'

Vue.use(Element)

// or
import {
  Select,
  Button
  // ...
} from 'element-ui-cs'

Vue.component(Select.name, Select)
Vue.component(Button.name, Button)
```

## Version
#### v1.0.0
```Optimization
一.Input
1.type=text maxlength默认值=20
2.type=textarea maxlength默认值=200

二.Table
1.tooltip默认风格=light

三.Select
1.filterable默认值改为true
```

#### v1.0.2
```Optimization
一.Input
1.type=text maxlength默认值=30
```
