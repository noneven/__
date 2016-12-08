# -
想到什么写什么

## next
* ajax跨子域 解决方案及适用场景
* 遇到问题的态度/处理问题的思路/总结问题的收获
* grunt/gulp和webpack/browserify对比
* 听说过/看过 < demo过 < 实际项目中用过 < 实际项目中被坑过 < 实际项目中被多次坑过 < 被多次坑过并且深入研究过
* 全局变量被修改的修复方法
* 设计模式原则
* 尾递归 尾递归优化 函数柯厘化 函数节流


* 切词算法 SEO 搜索引擎工作原理
* switch语句浅谈(case的值类型/case的匹配原则)
* javascript JS文件的加载执行
* HTML5新特性
* 代码抽象的三个原则
* 设置input的placeholder样式 input::input-placeholder{}
* 函数length和arguments的length
* JS连等赋值
* Koa + Koa-Middleware vs Express + Bluebird

* 看清BUG的本质, 不要猜想BUG应该是由于什么引起的, 如果和页面相关追踪元素的熟悉改变(页面展现<==>dom属性)
* h5路由(pushState路由)和hash路由的选择

* MVP 最简可用产品
* API测试

* Hash路由和H5路由
* 单页面应用 前端渲染带来的性能问题(后端渲染实践)

* 对rem的理解(相对根元素font-size大小的倍数，根元素font-size动态计算[屏幕宽度/320*16px]，做到设计图在手机上的缩放)
* 1px解决方案
* webp解决方案
* 前端一体化(node做接入层/和前端相关的都揽过来(模板/路由)) 模板发布机制

* node接入层全面使用
* 同构直出 路由体系 => hash路由不能传给服务端/路由整体换成H5路由  node接入层路由和前端路由对应
* 增量更新(diff+apply)

* fontmin(特殊字体子集)
* 随机洗牌算法 knuthShuffle
* cookie 同源不关心协议名和端口号
* native跨webview通信
* CORS兼容性
* IOS10 user-scalable=no/0禁止用户双击/手势缩放不生效了

```
To improve accessibility on websites in Safari, users can now pinch-to-zoom even when a website sets user-scalable=no in the viewport.
为了提高Safari中网站的辅助功能，即使网站在视口中设置了user-scalable = no，用户也可以手动缩放。
```
* display: -webkit-box/flex-box/flex其实都是flex布局

```
// flex 兼容性代码
display: -webkit-box; /* Chrome 4+, Safari 3.1, iOS Safari 3.2+ */
display: -moz-box; /* Firefox 17- */
display: -webkit-flex; /* Chrome 21+, Safari 6.1+, iOS Safari 7+, Opera 15/16 */
display: -moz-flex; /* Firefox 18+ */
display: -ms-flexbox; /* IE 10 */
display: flex; /* Chrome 29+, Firefox 22+, IE 11+, Opera 12.1/17/18, Android 4.4+ */
```

* WeakSet弱引用
* js在处理大整数时也会丢失精度[infoid server端下发的是一个Number类型]
