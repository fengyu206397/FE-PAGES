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
https://mp.weixin.qq.com/s/Bh-nveCyLqkEDGQXri-8fg
https://cloud.tencent.com/developer/article/2081704

```

### 排序

```
https://juejin.cn/post/6844903582328717325#heading-35

```

#### bubble

```
    function bubble(arr) {
      for (let i = 0; i < arr.length - 1; i++) {
        for (let j = 0; j < arr.length - 1 - i; j++) {
          if (arr[j] > arr[j + 1]) {
            let temp = arr[j + 1]
            arr[j + 1] = arr[j]
            arr[j] = temp
          }
        }
      }
    }
```

#### selection

```
    function selectionSort2(arr) {
      let min
      for (let i = 0; i < arr.length; i++) {
        min = i;
        for (let j = i + 1; j < arr.length; j++) {
          if (arr[min] > arr[j]) {
            min = j
          }
        }
        arr[i] = arr[min]
      }
    }

```

#### insert

```
    function insertSort2(arr) {
      for (let i = 1; i < arr.length; i++) {
        let j = i - 1
        let temp = arr[i]
        while (j && arr[j] > arr[i]) {
          arr[j + 1] = arr[j]
          j--
        }
        arr[j + 1] = temp
      }
    }

```

#### merge

```
    function mergeSort2(arr) {
      if (arr.length < 2) {
        return arr
      }
      let middle = Math.floor(arr.length / 2)
      let left = arr.slice(0, middle)
      let right = arr.slice(middle)
      return merge2(mergeSort2(left), mergeSort2(right))
    }

    function merge2(left, right) {
      let result = []
      while (left.length && right.length) {
        if (left[0] < right[0]) {
          result.push(left.shift())
        } else {
          result.push(right.shift())
        }
      }

      while (left.length) {
        result.push(left.shift())
      }
      while (right.length) {
        result.push(right.shift())
      }

      return result
    }

```

#### qucik

```
      function quickSort(arr, left, right) {
      left = typeof left == 'number' ? left : 0
      right = typeof right == 'number' ? right : arr.length - 1
      if (left < right) {
        let pivot = quick(arr, left, right)
        quickSort(arr, left - 1, pivot)
        quickSort(arr, pivot + 1, right)
      }
    }

    function quick(arr, left, right) {
      let pivot = arr[left]
      while (left < right) {
        while (left < right && arr[right] > pivot) {
          right--
        }
        arr[left] = arr[right]
        left++
        while (left < right && arr[left] < pivot) {
          left++
        }
        arr[right] = arr[left]
        right--
      }
      arr[left] = pivot
      return left
    }


```

### 手写 debounce 和 throttle

function debounce(fn, delay, im) {
let timeId
return function() {
if(im && !timeId) fn.apply(this, argments)
if(timeId) clearTimeOut(timeId)
timeId = setTimeOut(() => {
fn.apply(this, argments)
},delay)
}
}

function throttle(fn, interval) {
let lastTime = 0
return function() {
let now = new Date.getIime()
let residualTime = now - lastTime - interval

    if(residualTime > 0) {
      lastTime = now
      fn.apply(this, argments)
    }

}
}

### vue 性能优化

#### 编码

data 中尽量放必要的数据
v-for key 值唯一
路由懒加载
防抖节流
按需加载
长列表虚拟滚动
图片懒加载

#### 渲染

预渲染
ssr

#### 打包

分析打包体积，去除相同依赖
gzib 压缩
treeshaking
cdn
缓存策略

#### 体验

骨架片
pwa

### 首屏优化

cdn
缓存
gzip
懒加载
HTTP2

#### http

```
  https://juejin.cn/post/7079936383925616653?searchId=202310091057597782F3FD0BA429AAAF59
```

0.9 使用 get 请求传输 html 文本内容，验证 web 服务可行性
1.0 可以传输其他类型的内容，增加了状态码和 http header，协议版本号，增加了 head 和 post 请求
1.1 默认 tcp 为长链接，增加了 put、delete、patch 方法，增加了 range 头支持了断点续传，响应数据支持了分块，利于大文件传输。服务器为统一
域名能分配多个 tcp 连接，一个 tcp 中有多个 http 请求，但是服务器响应跟请求的顺序有关。
chrome spdyZ 增强 http 协议
2.0 解决 1.1 并发问题，使用二进制传输数据，使用多路复用机制，基本上只用一个 tcp 进行连接，请求数据和响应数据都有唯一编号，解决了并发问题。除此之外，http 头部压缩、数据请求优先级、服务端推送功能

3.0 改用 udp 协议，解决 tcp 丢包或网络断开导致的数据阻塞问题

#### 手写

```
https://juejin.cn/post/6946136940164939813#heading-11
https://github.com/fengyu206397/fe-handwriting
```

#### new

function New(fn) {
let a = {}
if(fn.prototype != null) {
a.**proto** = fn.prototype
}
let res = fn.apply(a, Array.prototype.slice.call(argments, 1))
if(res) {
return res
} else {
return a
}
}

#### json.stringfy

function josnStringify(obj) {

let type = typeof obj
if(/string|number|boolean/.test(obj) || obj === null) {
return '"' + obj + '"'
} else if(type == 'object'){
let arr = Array.isArray(obj)
let json = []

    for(let key in obj){
      let val = obj[key]
      let type = typeof val
      if(/string|number|boolean/.test(val) || val === null) {
        val =  '"' + val + '"'
      } else if(type == 'object') {
        val = josnStringify(val)
      }
      if(val !== undefined) {
        json.push(arr ? val : '"'+key+'":' + val)
      }
    }
    if(arr) {
      return '[' + String(json) + ']'
    } else {
      return '{' + String(json) + '}'
    }

}
}

#### JSON.parse

1. eval('(' + str + ')')
2. new Function('return ' + str)

#### call allpy bind

Function.prototype.call2 = fucntion(context = window) {
context.fn = this
let args = Array.prototype.slice.call(1)
let result = context.fn(args)
delete context.fn
return result
}

Function.prototype.apply2 = function(context = window) {
context.fn = this
let arg = arguments[1]
let result
if(arg) {
result = context.fn(...arg)
} else {
result = context.fn()
}
delete context.fn
return result
}

Function.prototype.bind = function(context = window) {
return function() {

}
}

#### promise

https://juejin.cn/post/7043758954496655397

```
class myPromise {
  static PENDING = "pending"
  static FULFILLED = 'fulfilled'
  static REJECTED = 'rejected'
  constructor(excutor) {
    this.PromiseState = myPromise.PENDING
    this.PromiseResult = null
    this.onFulfilledCallbacks = []
    this.onRejectedCallbacks = []

    try {
      excutor(this.resolve.bind(this), this.reject.bind(this))
    } catch (error) {
      this.reject(error)
    }
  }

  resolve(value) {
    if (this.PromiseState === myPromise.PENDING) {
      this.PromiseState = myPromise.FULFILLED
      this.PromiseResult = value

      this.onFulfilledCallbacks.forEach(fn => {
        fn(value)
      })
    }

  }

  reject(reason) {
    if (this.PromiseState === myPromise.PENDING) {
      this.PromiseResult = reason
      this.PromiseState = myPromise.REJECTED

      this.onRejectedCallbacks.forEach(fn => {
        fn(reason)

      })
    }
  }

  then(onFulFilled, onRejected) {
    let promise2 = new myPromise((resolve, reject) => {
      if (this.PromiseState === myPromise.FULFILLED) {
        setTimeout(() => {
          try {
            if (typeof onFulFilled === 'function') {
              let x = onFulFilled(this.PromiseResult)
              resolvePromise(promise2, x, resolve, reject)
            } else {
              resolve(this.PromiseResult)
            }
          } catch (error) {
            reject(error)
          }
        })
      } else if (this.PromiseState === myPromise.REJECTED) {
        setTimeout(() => {
          try {
            if (typeof onRejected === 'function') {
              let x = onRejected(this.PromiseResult)
              resolvePromise(promise2, x, resolve, reject)
            } else {
              reject(this.PromiseResult)
            }
          } catch (error) {
            reject(error)
          }
        })
      } else {
        this.onFulfilledCallbacks.push((y) => {
          setTimeout(() => {
            try {
              if (typeof onFulFilled === 'function') {
                let x = onFulFilled(y)
                resolvePromise(promise2, x, resolve, reject)
              } else {
                resolve(y)
              }
            } catch (error) {
              reject(error)
            }
          })
        })

        this.onRejectedCallbacks.push(y => {
          setTimeout(() => {
            try {
              if (typeof onRejected === 'function') {
                let x = onRejected(y)
                resolvePromise(promise2, x, resolve, reject)
              } else {
                reject(y)
              }
            } catch (error) {
              reject(error)
            }
          })
        })
      }
    })
    return promise2
  }
}


function resolvePromise(promise2, x, resolve, reject) {
  if(promise2 === x) {
    throw TypeError('cycle detected ');
  } else if(x instanceof myPromise){
    try {
      x.then((y) => {
        resolvePromise(promise2, y, resolve, reject)
      },reject)
    } catch(error) {
      reject(error)
    }
  } else if(x !== null && ((typeof x === 'object') || (typeof x === 'function'))) {
    try {
      var then = x.then
    } catch(error) {
      return reject(error)
    }
    let called = false
    if(typeof then === 'function') {
      try {
        then.call(x, y => {
          resolvePromise(promise2, y, resolve, reject)
        }, r => {
          reject(r)
        })
      }catch(error) {
        reject(error)
      }
    } else {
      resolve(x)
    }
  } else {
    resolve(x)
  }
}
```

#### 柯里化

```
只传递给函数一部分参数来调用它，让它返回一个函数去处理剩下的参数,作用：参数复用，延迟执行，减少了代码冗余，增加了代码可读性
```

https://juejin.cn/post/6844903834456686605?searchId=2023101610005350A2514A26C0D2F437A4

####
