### https://interview.poetries.top/docs/base/high-frequency.html#async-await%E5%BC%82%E6%AD%A5%E6%80%BB%E7%BB%93

### 选择器权重计算方式

```
  选择器的权重：
  -内联样式：1,0,0,0
  -id选择器：0,1,0,0
  -类和伪类选择器：0,0,1,0
  -元素选择器：0,0,0,1
  -通配选择器：0,0,0,0
  选择器权重计算规则：
  -比较优先级时，需要将所有的选择器的优先级进行相加计算，优先级越高越先显示；
  -选择器的累加不会超过其最大的优先级，比如，类选择器再高也不会超过id选择器；
  -如果优先级计算值相同，则优先使用靠下的样式。
```

### 清除浮动

```
https://zhuanlan.zhihu.com/p/432529468
父级div定义overflow:hidden
结尾处加空div标签clear:both
结尾 after
推荐：父级div定义伪类:after和zoom
```

### 垂直居中

```
https://127.0.0.1:5502/fe-interview/blog-docs/css/-%E5%B1%85%E4%B8%AD%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88%E8%8D%9F%E8%90%83.html#%E5%9E%82%E7%9B%B4%E5%B1%85%E4%B8%AD%E6%96%B9%E6%A1%88

```

### css3 新特性

```
https://zhuanlan.zhihu.com/p/434788923
1.CSS3选择器

2.CSS3边框与圆角

3.CSS3背景与渐变

4.CSS3过渡

5.CSS3变换

6.CSS3动画

```

### css3 的过渡和动画

```
https://zhuanlan.zhihu.com/p/361590421
过渡针对元素的样式属性，从一种样式转变到另一种，样式按贝塞尔曲线随时间变化，动画针对元素本身，按关键帧改变元素的样式效果
```

### 有哪些方式(CSS)可以隐藏页面元素

https://blog.csdn.net/simple_Xsg/article/details/124065694
1、display:none;

display 翻译成中文是显示、展览的意思；将 display 的属性改为 none 可以实现元素的隐藏，元素和盒子模型也不生成，被隐藏的元素不占位置，看不见摸不着，它会导致浏览器的重排和重绘。

2、visibility:hidden;

visibility 翻译成中文是能见、可见性的意思；hidden 翻译成中文的是隐藏、不易察觉的意思。将 visibility 的属性改成 hidden 可以实现元素的隐藏，和 display:none 的区别是它占位置，看不见但是摸得着，所以它只会导致浏览器重绘而不会重排。

3、opacity:0;

opacity 翻译成中文是透明度、不透明的意思；将 opacity 的属性改成 0 那就是透明度等于 0 看不见元素，但是这种方法也是只能隐藏看不见元素，和 visibility:hidden 一样，元素依然存在页面中。

4、position；

利用定位将元素的 top 和 left 值设为足够大的负数，使它移出屏幕在屏幕上看不见。

5、overflow:hidden；

overflow 翻译成中文是漫出、溢出的意思；将 overflow 的属性设置 hidden 可以实现元素隐藏，但是这个是超出盒子的部分隐藏，有局限性。

6、clip: rect(0, 0, 0, 0);

使用"clip: rect(0, 0, 0, 0);"将元素裁剪到 0 大小，使其不可见，但元素依然存在页面中。

7、transform: scale(0)；

可以将一个元素缩放到 0，它会消失，缩放不会影响元素的位置或布局，因此如果你缩小一个元素，它仍然会占用与原始大小相同的空间，但这不是通过 CSS 缩放来隐藏元素的推荐方法。

### 说说 em/px/rem/vh/vw 区别

### flex 布局

```
http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html?utm_source=tuicool
flex 6个属性
item 6个 order flex-grow flex-basic flex-shrink flex align-self
```

### 如果要做优化，CSS 提高性能的方法有哪些？

```
https://juejin.cn/post/6844904006251184142#heading-1
```

### 画一条 0.5px 的线

```
https://blog.csdn.net/yiyueqinghui/article/details/121569181

box-shadow
scale
```

### 如何画一个三角形

```
https://blog.csdn.net/SqlloveSyn/article/details/127607854

```

### 两栏布局：左边定宽，右边自适应方案

```
https://juejin.cn/post/6844903783542030350

```

### typeof 类型判断

```
https://127.0.0.1:5502/fe-interview/docs/excellent.html#_2-%E7%B1%BB%E5%9E%8B%E8%BD%AC%E6%8D%A2

```

### typeof 类型转换

```
https://127.0.0.1:5502/fe-interview/docs/excellent.html#_2-%E7%B1%BB%E5%9E%8B%E8%BD%AC%E6%8D%A2

```

### 闭包

```
https://blog.csdn.net/weixin_56266471/article/details/125225998

```

### 原型与原型链

```
https://127.0.0.1:5502/fe-interview/docs/excellent.html#_7-%E5%8E%9F%E5%9E%8B

```

### 原型继承和 Class 继承

```
https://juejin.cn/post/6844903696111763470

```

### 模块化

```
https://127.0.0.1:5502/fe-interview/docs/excellent.html#_10-%E6%A8%A1%E5%9D%97%E5%8C%96

```

### 事件机制

```
https://127.0.0.1:5501/fe-interview/docs/excellent.html#_17-%E4%BA%8B%E4%BB%B6%E6%9C%BA%E5%88%B6
https://www.quirksmode.org/js/events_order.html#link4
.
0
```

### 箭头函数

```
https://www.cnblogs.com/sparkler/p/13683951.html

```

### JS 内存泄露如何检测？场景有哪些？

```
https://juejin.cn/post/6844904048961781774#heading-6

```

### async/await 异步总结

```
https://blog.csdn.net/Anwel/article/details/92845435

```

### promise 异步总结

```
https://juejin.cn/post/6844903539605504008

```

### Event Loop 执行机制过程

```
https://zhuanlan.zhihu.com/p/55511602
https://127.0.0.1:5501/fe-interview/docs/excellent.html#_12-3-%E6%B5%8F%E8%A7%88%E5%99%A8%E4%B8%AD%E7%9A%84-event-loop

```

### 存储

```
https://127.0.0.1:5501/fe-interview/docs/excellent.html#_18-4-postmessage

```

### serviceWorker

```
https://juejin.cn/post/7130833826783166471

```

### webworker

```
https://juejin.cn/post/7139718200177983524

```

### 浏览器缓存机制

```
https://127.0.0.1:5501/fe-interview/docs/excellent.html#_20-%E6%B5%8F%E8%A7%88%E5%99%A8%E7%BC%93%E5%AD%98%E6%9C%BA%E5%88%B6

```

### 从输入 URL 到网页显示的完整过程

```
浏览器缓存： chrome://net-internals
浏览器dns缓存： ipconfig /displaydns
https://blog.csdn.net/m0_48465196/article/details/128225441
https://juejin.cn/post/6905931622374342670

https讲解
https://zhuanlan.zhihu.com/p/43789231
https://juejin.cn/post/7036551179517558791
https://www.bilibili.com/video/BV1Sg411A79a?p=4&vd_source=253894f5e6055e4ae8a6c7fdc6cdac48
https://www.runoob.com/http/http2-tutorial.html

tcp ip
https://blog.csdn.net/zzzlueng/article/details/121274387
https://juejin.cn/post/6844903685563105293

```

### 常见的 web 前端攻击方式有哪些

```
https://juejin.cn/post/7201391887147401273#heading-5

```

### 常见的 web 前端攻击方式有哪些

```
https://juejin.cn/post/7201391887147401273#heading-5

```

### 跨域

```
https://127.0.0.1:5501/fe-interview/docs/excellent.html#_18-2-cors
https://blog.csdn.net/Crazykun/article/details/118365808

```

### 移动端 H5 点击有 300ms 延迟，该如何解决

```
https://juejin.cn/post/6844903633528553485

```

### 如何实现网页多标签 tab 通讯

```
https://juejin.cn/post/7112302144442613773
https://blog.csdn.net/qq_53931766/article/details/129079752?spm=1001.2101.3001.6650.3&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-3-129079752-blog-123701860.235%5Ev36%5Epc_relevant_default_base3&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-3-129079752-blog-123701860.235%5Ev36%5Epc_relevant_default_base3&utm_relevant_index=4

```

### requestIdleCallback 和 requestAnimationFrame 有什么区别

```
https://juejin.cn/post/6844904056457003015
https://juejin.cn/post/6844903592831238157

```
