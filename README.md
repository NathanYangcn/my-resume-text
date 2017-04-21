# 个人简历

## 基本信息
- 姓名：杨扬
- 性别：男
- 电话：15210515211
- 邮箱：nathanyang1991@163.com
- 求职意向：前端开发
- github：[NathanYangcn](https://github.com/NathanYangcn)
- 简书博客：[NathanYangcn](http://www.jianshu.com/u/8106ed4aae34)

## 专业技能
- 熟悉HTML,CSS，能够使用和编译less，熟悉常见布局方式，熟悉编码规范和语义化。
- 熟悉原生JS、jQuery，能够使用jQuery改写原生JS文件，能够使用面向对象的方式编程。
- 熟悉HTTP协议、Ajax、跨域等技术，能够依据约定的接口与服务端进行数据交互、协同开发。
- 基本掌握npm、webpack、gulp，能够自行配置前端工程化开发环境。
- 熟悉commonJS、AMD规范，了解CMD规范，对模块化开发有一定认识，能够使用requireJS实现模块化。
- 了解nodeJS、express、ejs、sequelize，并使用这些技术开发了线上便签网站的项目。


## 个人项目

### 1. 在线随机音乐播放器（一个月）
##### 简介
- 这款音乐播放器实现的功能有：播放、暂停、歌曲切换、频道切换、音量调控、歌曲进程调控、滚动展示歌词、同步更新歌曲进程,歌词,时间
##### 使用技术
1. 使用原生JS实现基础功能
2. 使用jQuery库改写代码并拓展更多功能
3. 使用jsonp跨域获取数据库资源
4. 使用HTML、CSS编写代码更新UI界面
5. 使用组件化的方式将各个功能抽离成组件
6. 使用面向对象编程方式改写JS文件
7. 使用less语法改写css文件
8. 使用webpack对文件进行编译、打包
9. 使用npm script促使命令执行方便智能
##### 项目收获
- 该项目大致经历三个版本：第一个版本注重实现播放器的各种功能，第二个版本更新播放器UI界面，第三个版本主要精力在于使用更多技术进行内部代码优化。其中一个问题就是歌词功能的实现，经过资料查阅与思考我认为读懂歌词数据、并将每句歌词按照规律拆分开来是实现歌词展示的重点。当与服务器交互涉及到跨域问题时，便深入理解了浏览器的同源策略和跨域获取数据的原理，并将其总结为[简书文章](http://www.jianshu.com/p/0446b5bcdbab)。在对代码进行优化时，使用面向对象的编程方式对代码进行了封装，避免污染全局变量，增加代码的复用性和可维护性。开发过程中，使用webpack和npm script搭建自动化流程，当使用less修改css文件时，不需手动执行编译命令即可自动编译，使得开发过程变得简单智能。
##### 项目预览
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/fm-music-player/blob/master/index.html)]   [[代码地址](https://github.com/NathanYangcn/fm-music-player)]

### 2. 线上便签网站（一个月）
##### 简介
- 这是一个线上的便签网站，目前支持的功能有：添加、删除、修改便签、操作提醒、回到顶部、自动瀑布流布局、github登录功能、以及数据库存储所有便签数据
##### 使用技术
1. 使用express搭建网站整体框架
2. 使用webpack实现模块化、编译、打包
3. 使用npm script使网站启动、命令执行更加方便
4. 使用面向对象方式进行编程
5. 使用组件化的方式进行开发
6. 使用瀑布流进行布局
7. 使用事件发布订阅模式解耦代码
8. 使用sequelize数据库存储便签数据
9. 使用OAuth2协议和passport工具实现第三方登录功能
##### 项目收获
- 该项目使我对网站的整体框架、前后端整体开发流程、前后端协同开发、前端工程化有了一定的认识。前后端唯一交互便是接口，所以约定接口和开发联调是重要步骤。使用express的中间件和路由进行后端开发，使我明白了后端处理请求的逻辑；使用数据库存储数据，了解到模型以及如何定义一个数据表结构；以及使用模板引擎，从而理解MVC的概念。当使用webpack配置自动化流程时，引入的jQuery不起作用，通过对比排查得知jQuery.1.9.1等较低版本是不支持webpack的，需要引入新版本方可生效。
##### 项目预览
- [[预览地址](http://yangyoung.top/)]   [[代码地址](https://github.com/NathanYangcn/sticky-notes)]

### 3. npm天气预报工具包
### 4. npm中英互译工具包
##### 简介
- 这是两个项目是关于nodeJS的命令行工具
- npm天气预报工具，输入命令可查询当天详细天气状况以及第二天简略天气状况
- npm中英互译工具，输入命令可查询单词翻译，支持中英互译
##### 使用技术
1. 使用axios模块发送请求，该模块功能类似于Ajax
2. 使用package.json记录开发信息和集成命令
3. 使用npm相关命令对工具包进行管理
4. 使用process的argv获取输入参数
##### 项目收获
- 本项目经历了开发一个npm包的整个过程，包括创建、安装、引用、发布。npm类似于组件化的开发方式，在开发工具包时，可以引用他人已经发布的工具包进行开发，这样就减少了重复性，使开发过程变得简便快捷。在packa.json中记录了开发信息，包括依赖的模块和集成的命令，这样通过npm install就可以下载所有依赖模块、使用简单命令就能开始执行。
##### 项目预览
- 天气预报工具：[[npm地址](https://www.npmjs.com/package/report-weather)] 	[[git地址](https://github.com/NathanYangcn/report-weather)]
- 中英互译工具：[[npm地址](https://www.npmjs.com/package/yy-fanyi)] 	[[git地址](https://github.com/NathanYangcn/yy-fanyi)]

### 5. 常用组件
##### 简介
- 这是一个组件库，目前包括一些常用组件：轮播、事件中心、回到顶部、懒加载、tab、toast、瀑布流，组件基本都是以面向过程和面向对象两种方式进行编写
##### 项目收获
- 使用组件化的开发方式可以很大程度上提高代码的复用性，减少重复编程；使用面向对象的方式编程可以将代码进行封装，达到隐藏细节的目的。可以使用AMD或CMD规范定义模块，将某个单独功能抽离成模块，当使用某个模块时，可以使用require将模块引入当前代码即可直接使用引入的模块，然后再通过事件中心模块解耦代码，降低代码耦合度，使代码变得简单易懂，利于维护。
##### 项目预览
1. 轮播
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/wheels/blob/master/carousel/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/carousel.html)]   [[JS代码地址](https://github.com/NathanYangcn/wheels/blob/master/carousel/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/carousel.js)]
2. 事件中心
- [[JS代码地址](https://github.com/NathanYangcn/wheels/blob/master/eventCenter/eventCenter.js)]
3. 回到顶部goTop
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/wheels/blob/master/goTop/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/goTop.html)]   [[JS代码地址](https://github.com/NathanYangcn/wheels/blob/master/goTop/%E9%9D%A2%E5%90%91%E8%BF%87%E7%A8%8B/goTop.js)]
4. 懒加载lazyload
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/wheels/blob/master/lazyload/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/exposure.html)]   [[JS代码地址](https://github.com/NathanYangcn/wheels/blob/master/lazyload/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/exposure.js)]
5. tab
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/wheels/blob/master/tab/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/tab.html)]   [[JS代码地址](https://github.com/NathanYangcn/wheels/blob/master/tab/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/tab.js)]
6. toast
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/wheels/blob/master/toast/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/toast.html)]   [[JS代码地址](https://github.com/NathanYangcn/wheels/blob/master/toast/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/toast.js)]
7. 瀑布流
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/wheels/blob/master/waterfall/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/waterfall.html)]   [[JS代码地址](https://github.com/NathanYangcn/wheels/blob/master/waterfall/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1/waterfall.js)]

### 6. 小项目展示
1. 新闻展示：jsonp跨域获取资源、瀑布流布局、懒加载
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/effect-set/blob/master/newsList/newList.html)]   [[代码地址](https://github.com/NathanYangcn/effect-set/tree/master/newsList)]
2. 加载更多
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/effect-set/blob/master/loadMore-goTop/loadMore.html)]   [[代码地址](https://github.com/NathanYangcn/effect-set/tree/master/loadMore-goTop)]
3. 切换展示
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/effect-set/blob/master/tab/tab-two/tab.html)]   [[代码地址](https://github.com/NathanYangcn/effect-set/tree/master/tab/tab-two)]
4. WOW魔兽静态页面
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/static-page/blob/master/wow-home-page/wow.html)]   [[代码地址](https://github.com/NathanYangcn/static-page/tree/master/wow-home-page)]
5. 简历模板静态页面
- [[预览地址](http://htmlpreview.github.io/?https://github.com/NathanYangcn/static-page/blob/master/resume-template/resume.html)]   [[代码地址](https://github.com/NathanYangcn/static-page/tree/master/resume-template)]