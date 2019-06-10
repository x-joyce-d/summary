日常总结
---
websocket 编译原理
===
1. 入口文件app.js(Commonjs风格)
1. 分析所有文件依赖关系并读取，每个模块的源代码都被组织在一个立即执行的函数
1. 最后生成一个bundle文件，可实现动态加载(按需加载)模块，并将结果返回给APP。

vuex-状态管理
===
1. 命名空间 (namespaced:true)
1. state(状态),getters,mutations(同步),actions(异步),mapState(computed),mapMutation
1. 不能直接修改prop的值，可将其赋给一个data值。
1. 服务端获取图片不显示时，设置一个默认图片
```js
@error="handleError"
handleError(){
  return './images/error.png'
}
```

form表单提交方式
===
1. submit与button的区别：@submit可直接键入enter，button必须点击 @click，在form上定义行为action="javascript:void(0)",阻止跳转。

事件
===
**事件冒泡**
**事件委托**
  利用事件冒泡，避免dom事件绑定事件太多，影响内存，在其父元素上绑定事件
  （列表）
**事件源** target
**事件对象** window.event

浏览器内部工作原理
===
* 介绍
* 渲染引擎
* 解析与dom树构建
* 布局
* 绘制
* 动态变化
* 渲染引擎的线程
* 浏览器引擎
* js解释器
* 网络
* 数据存储
* UI后端

cordava 打包
fluter
前端服务框架
fiddler 测试
banner轮播
