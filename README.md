# vue-flag-list

> A Vue.js project

## 使用组件

``` bash
# 安装npm包
npm install vue-flag-list-test --save-dev

# 易用vue-flag-list插件
import VueFlagList from 'vue-flag-list'

Vue.use(VueFlagList)

# 在组件中使用
<flagCode height="30" width="120" @getCode="getCode"></flagCode>

methods: {
    getCode(code){
        console.log(code);
    }
}
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
