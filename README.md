## vue-alert-component 
* 基于 vue 2.0 开发的alert弹框插件
* 占用内存小，性能好，样式好看




## Other

* 仿照一位Vue大牛的代码（全盘借鉴）捂脸 (github地址: [wc-messagebox](https://github.com/helicopters/wc-messagebox))
* 另外推荐一个Vue轮播图插件。占用内存小、流畅、api友好、更新维护快。(轮播图github地址: [wc-swiper](https://github.com/helicopters/wc-swiper))


## Install
```shell
npm i vue-alert-component --save
```

## Quick Start  Usage
```javascript
//main.js中引入
import Alert from 'vue-alert-component'
Vue.use(Alert)

在某个vue文件中使用
this.$alert(content);

//举例  点击之后有回调函数的
this.$alert("你好").then(function(){
	console.log("点击确定")
})

