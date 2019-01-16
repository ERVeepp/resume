# 个人简历

### 教育经历

###### 2011 - 2015
> 王伟
> 长治学院
> 电子工程
> 17600206327

### 工作经历

###### 2015.07 - 2015.10
> 公务员考试
> 一名之差而失之交臂

###### 2015.10 - 2016.10
> 中大英才网络教育科技有限公司
> 前端leader

###### 2016.11 - 至今
> Yeahmobi(北京sdk)
> 前端leader

### 项目经历

###### 2015.10 - 2016.10
> 移动端站点的开发，内含课程直播，题库练习，图书商城等功能。
> 相关技术栈：
> jquery, zepto, bootstrap, vue.js, flv.js, glup等
> ps, ai, axure等
> 熟练手写jquery相关组件，了解AMD和CMD规范
> 相关时间段阅读书籍：
> JavaScript权威指南

###### 2016.10 - 2017.05
> ssp平台的开发，使用渐进式框架vue进行开发，引入ElementUI，并基于UI库实现类似的模块封装和上层建造。比如定制化上传组件，开关组件，表单验证组件。由于历史遗留原因，无法做到完全的前后端分离。使用scss预处理语言实现类bootstrap库，比如栅格化，flex盒模型，BFC的利用，并应用到项目中。
> 相关技术栈：
> vue.js, ElementUI, axios.js, ES6, scss
> 熟练手写vue相关组件和js基类，使用scss搭建css样式基础库
> 相关时间段阅读书籍：
> 深入理解ES6
> 业务逻辑理解：
> 此时的ssp是同时面向上游广告主和下游运营商的集合平台，包含报表，Offer定制化，以及投放策略定制化。

###### 2017.06 - 2017.12
> jsTag广告模板的制作，由于是基于移动端，所以需要考虑到移动端兼容的问题，纯js实现多种广告形式的展现，但只是非视频类广告，所以只添加了曝光监测和点击监测，以及网盟的监测，百度推广的监测等。功能比较简单，模板样式繁多，并且适用于横竖屏切换。但由于维护效率较低，后弃用，同时继续进行ssp平台的开发和维护。

###### 2018.01 - 2018.03
> 官网的制作，使用vue-cli构建，以达到多平台的兼容以及模块的热插拔，同一个网站，同时兼容移动端和PC，轻量级的同时达到页面数据的实时宏替换，这时的需求普通的开发模式已难以实现，于是在平台样式类库的基础上，进行更加深层的定制，由于官网只是离线应用，所以使用了vuex来达到数据同步的目的，使用vue-router来实现热切换(history模式)。
> 相关技术栈：
> vue, vuex, vue-router, vue-cli, scss等。
> 熟练手写vue组件，以及组件间通信，使用slot分发来处理特定逻辑等。
> 相关时间段阅读书籍：
> vue官网

###### 2018.04 - 2018.10
> Mraid广告的实现
> 由于市场上较流行的是mraid+vast的实现形式，所以把mraid广告分成两个大的模块来开发，以应对ADX的模式。
> 由于mraid广告内嵌于sdk中，所以开发测试的重要性尤为突出，这时使用了微信的一个开源项目，vConsole以实现线上测试
> 需要实现客户端缓存模板，所以使用manifest实现硬缓存，图片视频资源实现软缓存，及304重定向到本地。
> 本地开发阶段需要完善的单元测试，使用jest实现功能性测试，使用cypress实现段对端测试。
> 由于开发周期较长，所以实行灰度发布，既测试和线上同属一个服务器，使用部分小量通过测试服务器下发，最后逐步替代的方式实现平滑过渡。
> 开发过程中需要实时更新和客户端的实时交互测试，所以需要搭建本地node服务器来进行开发测试，并且进行数据的模拟。
> 综上所述，我使用webpack来构建开发环境，以应对多平台的兼容问题和模块包的协作，使用Typescript来实现接口数据类型的统一，使用DPR技术来实现设计图的完美印拓。
> 由于vast广告会有重定向的形式，所以需要把多层的广告数据整合成一维的数据结构，这里使用栈的方式来替代递归，以节省内存空间，虽然浏览器有尾调用优化。
> 由于有视频广告的监测，所以需要自定义事件，这里需要发布订阅模式来实现
> 相关技术栈：
> webpack, ts, egg等。
> 相关时间段阅读书籍：
> 算法导论
> Javascript高级程序设计

###### 2018.10 - 2018.12
> dsp平台的制作，其实此前dsp的相关功能整合在ssp平台内，由于业务的需求需要把dsp平台单独提出来，数据库也要使用单独的数据库，所以重新开发一套平台来面向上游广告主。其实相当于ssp的部分功能的提取重构。这里使用了新的权限判断方法，以实现单页面面向多权限用户的展示，布局使用grid实现，更加得心应手。报表使用Echart.js来实现。由于Offer类型需要与iOS和Android商店的类型对应，所以需要爬虫爬取对应的信息，这里使用egg来实现，简便快捷。
> 相关技术栈：
> vue, Echart.js, moment.js等。
> 相关时间段阅读书籍：
> 正则指引

### 相关技术栈

算法, 设计模式, NodeJS, Typescript, webpack, vue全家桶, SCSS等

### 自我评价

热爱技术，喜欢读书，乐于健身，富有强烈的责任感，拥有强大的自制力，相信技术的力量。
由于个人原因，之前搭建的hexo博客已停用，现已转到掘金继续进行写作，[我的掘金地址](https://juejin.im/user/57ffa882da2f60004fbfc60f)

[github](https://github.com/ERVeepp)

### 
[![JavaScript Style Guide](https://user-gold-cdn.xitu.io/2018/12/18/167c004928e8dcea)](https://github.com/standard/standard)
