<!-- TOC -->

- [一、HTML和CSS](#一html和css)
    - [1、浏览器的内核](#1浏览器的内核)
        - [2、Doctype的作用](#2doctype的作用)
        - [3、div+css 布局的优点](#3divcss-布局的优点)
        - [4、 img 的 alt 与 title 异同？](#4-img-的-alt-与-title-异同)
        - [5、渐进增强和优雅降级的区别](#5渐进增强和优雅降级的区别)
        - [6、为什么利用多个域名来存储网站资源会更有效？](#6为什么利用多个域名来存储网站资源会更有效)
        - [7、请谈一下你对网页标准和标准制定机构重要性的理解。](#7请谈一下你对网页标准和标准制定机构重要性的理解)
        - [8、 cookies，sessionStorage 和 localStorage 的区别](#8-cookiessessionstorage-和-localstorage-的区别)
        - [9、简述一下 src 与 href 的区别](#9简述一下-src-与-href-的区别)
        - [11、知道的网页制作会用到的图片格式有哪些？](#11知道的网页制作会用到的图片格式有哪些)
        - [12、微格式](#12微格式)
        - [13、从用户刷新网页开始，一次 js 请求一般情况下有哪些地方会有缓存处理？](#13从用户刷新网页开始一次-js-请求一般情况下有哪些地方会有缓存处理)
        - [14、优化图片的加载的方法](#14优化图片的加载的方法)
        - [15、你如何理解 HTML的语义化？](#15你如何理解-html的语义化)
        - [16、前端需要注意哪些SEO？](#16前端需要注意哪些seo)
        - [17、设置 CSS 样式的方式](#17设置-css-样式的方式)
        - [18、CSS 选择器、优先级](#18css-选择器优先级)
        - [19、使DOM 元素隐藏的方法](#19使dom-元素隐藏的方法)
        - [20、超链接访问的四个属性](#20超链接访问的四个属性)
        - [21、css hack原理及常用hack？](#21css-hack原理及常用hack)
        - [22、内联元素、块级元素、行内块元素、空元素](#22内联元素块级元素行内块元素空元素)
        - [23、外边距重叠](#23外边距重叠)
        - [24、rgba()和 opacity 的透明效果有什么不同？](#24rgba和-opacity-的透明效果有什么不同)
        - [25、css 中可以让文字在垂直和水平方向上重叠的两个属性是什么？](#25css-中可以让文字在垂直和水平方向上重叠的两个属性是什么)
        - [26、px 、 em 、rem的区别](#26px--em-rem的区别)
        - [27、自己定义的重置样式reset.css和 normalize.css 的区别](#27自己定义的重置样式resetcss和-normalizecss-的区别)
        - [28、什么是CSS 预处理器？](#28什么是css-预处理器)
        - [29、CSS 中 link 和@import 的区别](#29css-中-link-和import-的区别)
        - [30、简介盒子模型](#30简介盒子模型)
        - [31、为什么要初始化样式？](#31为什么要初始化样式)
        - [32、BFC 是什么?](#32bfc-是什么)
        - [33、HTML 与 XHTML二者有什么区别？](#33html-与-xhtml二者有什么区别)
        - [34、 浏览器常见兼容性问题](#34-浏览器常见兼容性问题)
        - [35、对 WEB 标准以及 W3C 的理解与认识](#35对-web-标准以及-w3c-的理解与认识)
        - [36、属性继承](#36属性继承)
        - [37、CSS3 新增伪类](#37css3-新增伪类)
        - [38、position定位absolute、fixed 、relative](#38position定位absolutefixed-relative)
        - [39、两栏等高布局(多列等高)](#39两栏等高布局多列等高)
        - [40、简述 readyonly 与 disabled 的区别](#40简述-readyonly-与-disabled-的区别)
        - [41、字体图标的使用](#41字体图标的使用)
        - [42、css的 content 属性](#42css的-content-属性)
        - [43、css 动画和 js 动画的差异](#43css-动画和-js-动画的差异)
        - [44、什么是SVG？](#44什么是svg)
        - [45、浏览器渲染机制](#45浏览器渲染机制)
        - [46、浮动和清除浮动](#46浮动和清除浮动)
        - [47、无样式内容闪烁问题](#47无样式内容闪烁问题)
        - [48、如何为有功能限制（低版本IE, 手机浏览）的浏览器提供网页？](#48如何为有功能限制低版本ie-手机浏览的浏览器提供网页)
        - [49、HTML全局属性(global attribute)有哪些？](#49html全局属性global-attribute有哪些)
        - [50、css sprite（精灵图）](#50css-sprite精灵图)
        - [51、如何水平居中一个元素？](#51如何水平居中一个元素)
        - [52、iframe有那些缺点？](#52iframe有那些缺点)
        - [53、Label的作用是什么？是怎么用的？](#53label的作用是什么是怎么用的)
        - [54、如何在页面上实现一个圆形的可点击区域？](#54如何在页面上实现一个圆形的可点击区域)
        - [55、display有哪些值？说明他们的作用](#55display有哪些值说明他们的作用)
        - [56、用纯CSS创建一个三角形的原理是什么？](#56用纯css创建一个三角形的原理是什么)
        - [57、visibility：collapse](#57visibilitycollapse)
        - [58、元素竖向的百分比设定是相对于容器的高度吗？](#58元素竖向的百分比设定是相对于容器的高度吗)
        - [59、全屏滚动的原理是什么？](#59全屏滚动的原理是什么)
        - [60、视差滚动效果，如何给每页做不同的动画？](#60视差滚动效果如何给每页做不同的动画)
        - [61、::before 和 :after中双冒号和单冒号有什么区别？](#61before-和-after中双冒号和单冒号有什么区别)
        - [62、溢出文字隐藏(使用css截取指定文字长度)](#62溢出文字隐藏使用css截取指定文字长度)
- [二、JavaScript](#二javascript)
    - [1、javascript 的数据类型](#1javascript-的数据类型)
        - [2、强制类型转换和隐式类型转换](#2强制类型转换和隐式类型转换)
        - [3.数组方法](#3数组方法)
        - [4、call 、 apply 、bind的区别](#4call--apply-bind的区别)
        - [5、继承](#5继承)
        - [6、this的指向](#6this的指向)
        - [7、闭包](#7闭包)
        - [8、作用域和作用域链](#8作用域和作用域链)
        - [9、IE 和标准下有哪些兼容性的写法](#9ie-和标准下有哪些兼容性的写法)
        - [10、事件绑定](#10事件绑定)
        - [11、事件冒泡和事件捕获](#11事件冒泡和事件捕获)
        - [12、事件委托（事件代理）](#12事件委托事件代理)
        - [13、如何阻止事件冒泡和默认事件](#13如何阻止事件冒泡和默认事件)
        - [14、元素创建、追加、查找](#14元素创建追加查找)
        - [15、 本地对象，内置对象和宿主对象](#15-本地对象内置对象和宿主对象)
        - [16、window.onload 和 document.ready 的区别？](#16windowonload-和-documentready-的区别)
        - [17、”==”和“===”的不同](#17和的不同)
        - [18、编写一个数组去重的方法](#18编写一个数组去重的方法)
        - [19、JavaScript 是一门什么样的语言?](#19javascript-是一门什么样的语言)
        - [20、undefined与null](#20undefined与null)
        - [21、冒泡排序和快排](#21冒泡排序和快排)
        - [22、格式化当前时间](#22格式化当前时间)
        - [23、字符串相关方法](#23字符串相关方法)
        - [24、url地址对象化](#24url地址对象化)
        - [25、正则表达式](#25正则表达式)
        - [26、 callee 和 caller 的作用？](#26-callee-和-caller-的作用)
        - [27、创建函数的方式](#27创建函数的方式)
        - [28、创建对象的方法](#28创建对象的方法)
        - [29、Script标签位置](#29script标签位置)
        - [30、js 延迟加载的方式有哪些？](#30js-延迟加载的方式有哪些)
        - [31、内存泄漏问题](#31内存泄漏问题)
        - [32、获取非行间样式的函数](#32获取非行间样式的函数)
        - [33、BOM常用对象](#33bom常用对象)
        - [34、遍历DOM树](#34遍历dom树)
        - [35、伪数组](#35伪数组)
        - [36、原生js实现拖拽](#36原生js实现拖拽)
        - [37、严格模式`use strict`](#37严格模式use-strict)
        - [38、Object 对象的常用方法](#38object-对象的常用方法)
        - [39、原型和原型链](#39原型和原型链)
        - [40、自定义事件实现](#40自定义事件实现)
        - [41、浅拷贝和深拷贝](#41浅拷贝和深拷贝)
        - [42、请用js去除字符串空格？](#42请用js去除字符串空格)
        - [43、DOM元素e的e.getAttribute(propName)和e.propName有什么区别和联系？](#43dom元素e的egetattributepropname和epropname有什么区别和联系)
        - [44、offset/client/scrollWidth三大系列属性的区别](#44offsetclientscrollwidth三大系列属性的区别)
        - [45、focus/blur与focusin/focusout的区别与联系](#45focusblur与focusinfocusout的区别与联系)
        - [46、mouseover/mouseout与mouseenter/mouseleave的区别与联系](#46mouseovermouseout与mouseentermouseleave的区别与联系)
        - [47、函数内部arguments](#47函数内部arguments)
        - [48、函数节流和防抖](#48函数节流和防抖)
        - [49、如何实现数组的随机排序？](#49如何实现数组的随机排序)
        - [50、hasOwnProperty](#50hasownproperty)
        - [51、Object.is() 与原来的比较操作符“ ===”、“ ==”的区别？](#51objectis-与原来的比较操作符--的区别)
        - [52、列举IE与其他浏览器不一样的特性？](#52列举ie与其他浏览器不一样的特性)
        - [53、预解析](#53预解析)
        - [54、其他](#54其他)
- [三、HTTP和Ajax](#三http和ajax)
    - [1、同步和异步的区别?](#1同步和异步的区别)
        - [2、Ajax](#2ajax)
        - [3、Ajax跨域](#3ajax跨域)
        - [4、GET 和 POST 有什么区别？](#4get-和-post-有什么区别)
        - [5、HTTP 常用状态码](#5http-常用状态码)
        - [6、HTTP 协 议 中 ，last-modified,cache-control,Expires 分别代表什么？](#6http-协-议-中-last-modifiedcache-controlexpires-分别代表什么)
        - [7、页面编码和被请求的资源编码如果不一致如何处理？](#7页面编码和被请求的资源编码如果不一致如何处理)
        - [8、阐述一下异步加载](#8阐述一下异步加载)
        - [9、一个页面从输入 URL 到页面加载显示完成，这个过程中都发生了什么？](#9一个页面从输入-url-到页面加载显示完成这个过程中都发生了什么)
        - [10、ajax 请求时，如何解释 json 数据](#10ajax-请求时如何解释-json-数据)
        - [12、HTTP method](#12http-method)
        - [13、请求报文和响应报文结构](#13请求报文和响应报文结构)
        - [15、XMLHttpRequest通用属性和方法？](#15xmlhttprequest通用属性和方法)
        - [16、http和https的区别](#16http和https的区别)
        - [17、http1.0、1.1、2.0的区别](#17http101120的区别)
        - [18、Cookie 隔离](#18cookie-隔离)
        - [19、Ajax 解决浏览器缓存问题？](#19ajax-解决浏览器缓存问题)
- [四、jQuery](#四jquery)
    - [1、bind(), live(), delegate()、on的区别](#1bind-live-delegateon的区别)
        - [2、jQuery 框架中$.ajax()的常用参数有哪些？](#2jquery-框架中ajax的常用参数有哪些)
        - [3、动画滞后问题](#3动画滞后问题)
        - [4、jQuery 一个对象可以同时绑定多个事件，这是如何实现的？](#4jquery-一个对象可以同时绑定多个事件这是如何实现的)
        - [5、jQuery 与 jQuery UI 有啥区别？](#5jquery-与-jquery-ui-有啥区别)
        - [6、jquery 中如何将数组转化为 json 字符串，然后再转化回来？](#6jquery-中如何将数组转化为-json-字符串然后再转化回来)
        - [7、jQuery.fn 的 init 方法返回的 this 指的是什么对象？为什么要返回 this？](#7jqueryfn-的-init-方法返回的-this-指的是什么对象为什么要返回-this)
        - [8、jQuery 的属性拷贝(extend)的实现原理是什么，如何实现深拷贝？](#8jquery-的属性拷贝extend的实现原理是什么如何实现深拷贝)
        - [9、jQuery.extend 与 jQuery.fn.extend 的区别？](#9jqueryextend-与-jqueryfnextend-的区别)
        - [10、jQuery 和 Zepto 的区别？](#10jquery-和-zepto-的区别)
        - [11、针对 jQuery 的优化方法？](#11针对-jquery-的优化方法)
        - [12、Zepto 的点透问题如何解决？](#12zepto-的点透问题如何解决)
        - [13、JQuery有几种选择器?](#13jquery有几种选择器)
        - [14、如何用jQuery禁用浏览器的前进后退按钮？](#14如何用jquery禁用浏览器的前进后退按钮)
        - [15、serialize() 方法](#15serialize-方法)
        - [16、jQuery 的队列是如何实现的？队列可以用在哪些地方？](#16jquery-的队列是如何实现的队列可以用在哪些地方)
        - [17、jQuery里的fire函数是什么意思，什么时候用？](#17jquery里的fire函数是什么意思什么时候用)
- [五、HTML5和CSS3](#五html5和css3)
    - [1、CSS3 有哪些新特性？](#1css3-有哪些新特性)
        - [2、HTML5 有哪些新特性？](#2html5-有哪些新特性)
        - [3、如何实现浏览器内多个标签页之间的通信?](#3如何实现浏览器内多个标签页之间的通信)
        - [4、HTML5 Canvas](#4html5-canvas)
        - [5、HTML5几种存储方式的总结](#5html5几种存储方式的总结)
        - [6、实现动画的反方式](#6实现动画的反方式)
        - [7、如何在 HTML5 页面中嵌入音频和视频?](#7如何在-html5-页面中嵌入音频和视频)
        - [8、data-*属性的作用](#8data-属性的作用)
        - [9、如果把 HTML5 看作做一个开放平台，那它的构建模块有哪些？](#9如果把-html5-看作做一个开放平台那它的构建模块有哪些)
        - [10、应用程序存储和离线web应用？](#10应用程序存储和离线web应用)
        - [11、webSocket](#11websocket)
- [六、移动web](#六移动web)
    - [1、什么是响应式设计？](#1什么是响应式设计)
        - [2、移动端常用类库及优缺点](#2移动端常用类库及优缺点)
        - [3、移动端最小触控区域是多大？](#3移动端最小触控区域是多大)
        - [4、移动端的点击事件](#4移动端的点击事件)
        - [5、主流适配方案：流式布局+viewport](#5主流适配方案流式布局viewport)
        - [6、响应式布局](#6响应式布局)
        - [7、rem布局](#7rem布局)
        - [8、flex弹性布局（css3）](#8flex弹性布局css3)
        - [9、三栏式布局（两边两栏宽度固定，中间栏宽度自适应）](#9三栏式布局两边两栏宽度固定中间栏宽度自适应)
        - [10、两栏自适应（左边定宽，右边自适应）](#10两栏自适应左边定宽右边自适应)
        - [11、box-sizing属性](#11box-sizing属性)
        - [12、媒体查询](#12媒体查询)
        - [13、position:fixed;在android下无效怎么处理？](#13positionfixed在android下无效怎么处理)
        - [14、如果需要手动写动画，你认为最小时间间隔是多久，为什么？](#14如果需要手动写动画你认为最小时间间隔是多久为什么)
- [七、Node.js](#七nodejs)
    - [1、对 Node 的优点和缺点提出了自己的看法：](#1对-node-的优点和缺点提出了自己的看法)
        - [2、Node.js 的适用场景？](#2nodejs-的适用场景)
        - [3、node相关概念](#3node相关概念)
        - [4、前端路由](#4前端路由)
        - [5、Node 事件循环，js 事件循环差异](#5node-事件循环js-事件循环差异)
        - [6、关于前后端分离](#6关于前后端分离)
        - [7、如何判断当前脚本运行在浏览器还是node环境中？](#7如何判断当前脚本运行在浏览器还是node环境中)
- [八、其他](#八其他)
    - [1、你所了解到的Web攻击技术](#1你所了解到的web攻击技术)
        - [3、如何测试前端代码?](#3如何测试前端代码)
        - [4、Web 模板引擎](#4web-模板引擎)
        - [5、模块化开发怎么做？](#5模块化开发怎么做)
        - [6、AMD和CMD规范区别](#6amd和cmd规范区别)
        - [7、如何编写高性能的 Javascript？](#7如何编写高性能的-javascript)
        - [8、JSON 的了解](#8json-的了解)
        - [9、WEB 应用从服务器主动推送 Data 到客户端有那些方式？](#9web-应用从服务器主动推送-data-到客户端有那些方式)
        - [10、如何实现一个组件封装?](#10如何实现一个组件封装)
        - [11、线程、进程、多线程](#11线程进程多线程)
        - [12、负载均衡](#12负载均衡)
        - [13、babel把ES6转成ES5或者ES3之类的原理是什么？](#13babel把es6转成es5或者es3之类的原理是什么)
        - [15、webpack的一些原理和机制，怎么实现的？](#15webpack的一些原理和机制怎么实现的)
        - [16、ES6新特性](#16es6新特性)
        - [16、web开发中会话跟踪的方法有哪些？](#16web开发中会话跟踪的方法有哪些)
        - [17、PNG,GIF,JPG的区别及如何选？](#17pnggifjpg的区别及如何选)
        - [18、Webpack热更新实现原理?](#18webpack热更新实现原理)
        - [19、css-loader的原理？](#19css-loader的原理)
        - [20、Vue组件的书写方式](#20vue组件的书写方式)
        - [21、vue的生命周期](#21vue的生命周期)
        - [23、**react和vue有哪些不同，说说你对这两个框架的看法**](#23react和vue有哪些不同说说你对这两个框架的看法)
        - [24、**MVVM、MVC、MVP原理**](#24mvvmmvcmvp原理)
        - [25、网页验证码是干嘛的，是为了解决什么安全问题。](#25网页验证码是干嘛的是为了解决什么安全问题)
        - [26、是否了解公钥加密和私钥加密](#26是否了解公钥加密和私钥加密)
        - [27、PHP操作数据库](#27php操作数据库)
        - [28、node的基本使用](#28node的基本使用)
        - [29、express框架](#29express框架)
        - [30、node操作数据库](#30node操作数据库)
        - [31、vue-router](#31vue-router)
        - [32、axios](#32axios)
        - [33、vue-cli](#33vue-cli)
        - [34、webpack和babel](#34webpack和babel)
        - [35、接口设计](#35接口设计)
        - [35、react](#35react)
        - [36、其他参考](#36其他参考)
- [九、开放性问题](#九开放性问题)
    - [1、你如何优化自己的代码？](#1你如何优化自己的代码)
        - [2、优化 WEB 页面加载速度的方法(网站性能优化)](#2优化-web-页面加载速度的方法网站性能优化)
        - [3、常用的 web 页面开发工具](#3常用的-web-页面开发工具)
        - [4、列举常用的 js 框架以及分别适用的领域](#4列举常用的-js-框架以及分别适用的领域)
        - [5、怎么来实现页面设计图？](#5怎么来实现页面设计图)
        - [6、前端开发的优化问题（看雅虎 14 条性能优化原则）](#6前端开发的优化问题看雅虎-14-条性能优化原则)
        - [7、平时如何管理你的项目，如何设计突发大规模并发架构？](#7平时如何管理你的项目如何设计突发大规模并发架构)
        - [8、最近前端最流行的一些东西吧？常去的网站？](#8最近前端最流行的一些东西吧常去的网站)
        - [9、移动端怎么做好用户体验?](#9移动端怎么做好用户体验)
        - [10、谈谈你认为怎样做能使项目做的更好？](#10谈谈你认为怎样做能使项目做的更好)
        - [11、你对前端界面工程师这个职位是怎么样理解的？它的前景会怎么样？](#11你对前端界面工程师这个职位是怎么样理解的它的前景会怎么样)
        - [12、你认为前端应该如何高质量完成工作?](#12你认为前端应该如何高质量完成工作)
        - [13、设计模式 知道什么是singleton, factory, strategy, decrator么?](#13设计模式-知道什么是singleton-factory-strategy-decrator么)
        - [14、页面重构怎么操作？](#14页面重构怎么操作)
        - [15、你用的得心应手用的熟练地编辑器&开发环境是什么样子？](#15你用的得心应手用的熟练地编辑器开发环境是什么样子)
        - [16、你怎么看待Web App 、hybrid App、Native App？](#16你怎么看待web-app-hybrid-appnative-app)
        - [17、你的学习来源是什么？](#17你的学习来源是什么)
        - [18、原来公司工作流程是怎么样的，如何与其他人协作的？如何跨部门合作的？](#18原来公司工作流程是怎么样的如何与其他人协作的如何跨部门合作的)
        - [19、你遇到过比较难的技术问题是？你是如何解决的？](#19你遇到过比较难的技术问题是你是如何解决的)
        - [20、你的优点是什么？缺点是什么？](#20你的优点是什么缺点是什么)
        - [21、最近在学什么？能谈谈你未来3，5年给自己的规划吗？](#21最近在学什么能谈谈你未来35年给自己的规划吗)
        - [22、先自我介绍一下，说一下项目的技术栈，以及项目中遇到的一些问题](#22先自我介绍一下说一下项目的技术栈以及项目中遇到的一些问题)
        - [23、从整体中，看你对项目的认识，框架的认识和自己思考](#23从整体中看你对项目的认识框架的认识和自己思考)
        - [24、项目中有没有遇到什么难点，怎么解决](#24项目中有没有遇到什么难点怎么解决)
        - [25、其他](#25其他)
- [十、项目经验（略）](#十项目经验略)
- [十一、自我介绍（略）](#十一自我介绍略)

<!-- /TOC -->

## 一、HTML和CSS

#### 1、浏览器的内核

- 浏览器的内核主要分成两部分：渲染引擎(layout engineer或Rendering Engine)和JS引擎。 
  -  渲染引擎：负责取得网页的内容（HTML、XML、图像等等）、整理讯息（例如加入CSS等），以及计算网页的显示方式，然后会输出至显示器或打印机。浏览器的内核的不同对于网页的语法解释会有不同，所以渲染的效果也不相同。所有网页浏览器、电子邮件客户端以及其它需要编辑、显示网络内容的应用程序都需要内核。
  -  JS引擎则：解析和执行javascript来实现网页的动态效果。
  - 最开始渲染引擎和JS引擎并没有区分的很明确，后来JS引擎越来越独立，内核就倾向于只指渲染引擎。

- IE: **trident** 内核
- Firefox：**gecko** 内核
- Safari:**webkit** 内核
- Opera:以前是 **presto** 内核，Opera 现已改用 Google Chrome 的 Blink 内核
- Chrome:**Blink**(基于 webkit，Google 与 Opera Software 共同开发)

#### 2、Doctype的作用

- **作用:** doctype声明位于文档中最前面的位置，处于标签之前，告知浏览器使用的是哪种规范。

  - 写了doctype，采用w3c方式解析，浏览器呈现页面,页面排版及 JS 解析是以该浏览器支持的最高标准来执行，即strict mode（标准模式）

  - 不写doctype，浏览器不引入w3c的标准，浏览器会进入quirks mode （怪异模式），浏览器采用自身方式解析页面
  - 对于那些浏览器不能识别的doctype ,浏览器采用怪异模式；
  - 没有声明DTD或者html版本声明低于4.0采用怪异模式，其他使用标准模式

- **类型:** （Strict、Transitional 以及 Frameset ）

  - **HTML4.01 strict**：不允许使用表现性、废弃元素（如font）以及frameset。声明：`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">`

  - **HTML4.01 Transitional**:允许使用表现性、废弃元素（如font），不允许使用frameset。声明：`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">`

  - **HTML4.01 Frameset**:允许表现性元素，废气元素以及frameset。声明：`<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">`

  - **XHTML1.0 Strict**:不使用允许表现性、废弃元素以及frameset。文档必须是结构良好的XML文档。声明：`<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">`

  - **XHTML1.0 Transitional**:允许使用表现性、废弃元素，不允许frameset，文档必须是结构良好的XMl文档。声明： `<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">`

  - **XHTML 1.0 Frameset**:允许使用表现性、废弃元素以及frameset，文档必须是结构良好的XML文档。声明：`<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd">`

  - **HTML 5**: `<!doctype html>`

    > HTML5 不基于 SGML，因此不需要对DTD进行引用，但是需要doctype来规范浏览器的行为（让浏览器按照它们应该的方式来运行）；而HTML4.01基于SGML,所以需要对DTD进行引用，才能告知浏览器文档所使用的文档类型。

- 标准模式与怪异模式的区别（布局、样式解析和脚本执行三个方面的区别）：

  - 盒模型：在 W3C 标准中，如果设置一个元素的宽度和高度，指的是元素内容的宽度和高度，而在怪异模式下，盒模型为IE盒模型，IE 的宽度和高度还包含了 padding 和 border

  - 行内元素的宽高：在标准模式下，给行内元素设置 wdith 和 height 都不会生效，而在怪异模式下，则会生效

  - 元素的百分比高度：在标准模式下，一个元素的高度是由其包含的内容来决定的，而在怪异模式下，如果父元素没有设置百分比的高度，子元素设置一个百分比的高度是无效的

  - margin:0 auto 设置水平居中：使用 margin:0 auto 在 标准模式下可以使元素水平居中，但在 怪异模式下却会失效

- 判断标准模式还是怪异模式： 

  ```javascript
  alert(window.top.document.compatMode) ;//BackCompat:怪异模式 CSS1Compat:标准模式
  alert($.boxModel|$.support.boxModel);//jquery的方法
  ```

#### 3、div+css 布局的优点

- 改版的时候更方便，只要改 css 文件
- 结构清晰、页面显示简洁、页面加载速度更快
- 结构与表现相分离
- 易于优化（seo）搜索引擎更友好，排名更容易靠前

#### 4、 img 的 alt 与 title 异同？ 

- `title`是global attributes之一，用于为元素提供附加的信息，通常当鼠标滑动到元素上的时候显示。
- `alt`是img的特有属性，是图片内容的等价描述，可提高图片可访问性。用于图片无法加载时显示、读屏器阅读图片。除了纯装饰图片外都必须设置有意义的值，搜索引擎会重点分析。


#### 5、渐进增强和优雅降级的区别

- 渐进增强 progressive enhancement：针对低版本浏览器进行构建页面，保证最基本的功能，然后再针对高级浏览器进行效果、交互等改进和追加功能达到更好的用户体验。

- 优雅降级 graceful degradation：一开始就构建完整的功能，然后再针对低版本浏览器进行兼容。

- 区别：优雅降级是从复杂的现状开始，并试图减少用户体验的供给，而渐进增强则是从一个非常基础的，能够起作用的版本开始，并不断扩充，以适应未来环境的需要。优雅降级（功能衰减）意味着往回看；而渐进增强则意味着朝前看，同时保证其根基处于安全地带。

#### 6、为什么利用多个域名来存储网站资源会更有效？

- CDN 缓存更方便，突破浏览器并发限制，节约 cookie 带宽，节约主域名的连接数，优化页面响应速度防止不必要的安全问题

- 确保用户在不同地区能用最快的速度打开网站，其中某个域名崩溃用户也能通过其他域名访问网站，并且不同的资源放到不同的服务器上有利于减轻单台服务器的压力

#### 7、请谈一下你对网页标准和标准制定机构重要性的理解。

- 网页标准和标准制定机构都是为了能让 web 发展的更健康
- 开发者遵循统一的标准，降低开发难度，开发成本，SEO 也会更好做
- 也不会因为滥用代码导致各种 BUG、安全问题，最终提高网站易用性

#### 8、 cookies，sessionStorage 和 localStorage 的区别

- **位置和传输**

  - cookie是网站为了标示用户身份而储存在用户本地终端（Client Side）上的数据（通常经过加密）cookie数据始终在同源的http请求中携带（即使不需要），记会在浏览器和服务器间来回传递。
  - sessionStorage和localStorage不会自动把数据发给服务器，仅在本地保存。

- **存储大小**：

  - cookie数据大小不能超过4k。
  - sessionStorage和localStorage 虽然也有存储大小的限制，但比cookie大得多，可以达到5M或更大。

- **有效时间：**

  - localStorage    存储**持久数据**，浏览器关闭后数据不丢失除非主动删除数据；
  - sessionStorage  数据在当前浏览器窗口关闭后自动删除。
  - cookie  设置的cookie**过期时间之前**一直有效，即使窗口或浏览器关闭

- **作用域 :**

  - sessionStorage不在不同的浏览器窗口中共享，即使是同一个页面；
  - localStorage 在所有同源窗口中都是共享的；
  - cookie也是在所有同源窗口中都是共享的。

- 三者相同点：localStorage、sessionStorage、Cookie共同点：都是保存在浏览器端，且同源的

- **其他补充：**

  - cookie的弊端：

    - 数量和长度的限制。每个 domain 最多只能有 20 条 cookie，每个 cookie 长度不能超过 4KB，否则会被截掉。
    - 安全性问题。如果 cookie 被人拦截了，就可以取得所有的 session 信息。即使加密也与事无补，因为拦截者并不需要知道 cookie 的意义，他只要原样转发 cookie 就可以达到目的了。
    - 有些状态不可能保存在客户端。例如，为了防止重复提交表单，我们需要在服务器端保存一个计数器。如果我们把这个计数器保存在客户端，那么它起不到任何作用。

  - Web Storage 支持事件通知机制，可以将数据更新的通知发送给监听者。Web Storage 的 api 接口使用更方便。

    > sessionStorage 和 localStorage 是HTML5 Web Storage API 提供的，这两种方式都允许开发者使用js设置的键值对进行操作，在重新加载不同的页面的时候读出它们。这一点与cookie类似。可以方便的在web请求之间保存数据。使用 local storage和session storage主要通过在js中操作这两个对象来实现，分别为window.localStorage和window.sessionStorage. 这两个对象均是Storage类的两个实例，自然也具有Storage类的属性和方法。有了本地数据，就可以避免数据在浏览器和服务器间不必要地来回传递，好处如下：
    >
    > - 减少网络流量：一旦数据保存在本地后，就可以避免再向服务器请求数据，因此减少不必要的数据请求，减少数据在浏览器和服务器间不必要地来回传递。
    > - 快速显示数据：性能好，从本地读数据比通过网络从服务器获得数据快得多，本地数据可以即时获得。再加上网页本身也可以有缓存，因此整个页面和数据都在本地的话，可以立即显示。
    > - 临时存储：很多时候数据只需要在用户浏览一组页面期间使用，关闭窗口后数据就可以丢弃了，这种情况使用sessionStorage非常方便

#### 9、简述一下 src 与 href 的区别

- src 用于替换当前元素，href 用于在当前文档和引用资源之间确立联系。

- src 是 source 的缩写，指向外部资源的位置，指向的内容将会嵌入到文档中当前标签所在位置；在请求 src 资源时会将其指向的资源下载并应用到文档内，例如 js 脚本，img 图片和 frame 等元素。当浏览器解析到该元素时会暂停其他资源的下载和处理，直到将该资源加载、编译、执行完毕，图片和框架等元素也如此，类似于将所指资源嵌入当前标签内。这也是为什么将js 脚本放在底部而不是头部。

- href 是 Hypertext Reference 的缩写，指向网络资源所在位置，建立和当前元素（锚点）或当前文档（链接）之间的链接，如果浏览器识别该元素属性时，就会并行下载资源并且不会停止对当前文档的处理。这也是为什么建议使用 link 方式来加载 css，而不是使用@import 方式（link标签引入的 CSS 被同时加载，@import引入的 CSS 将在页面加载完毕后被加载）

#### 11、知道的网页制作会用到的图片格式有哪些？

- 常用：**png-8**，**png-24**，**jpeg**，**gif**，**svg**。

- 现在流行：**WebP** 格式，谷歌开发的一种旨在加快图片加载速度的图片格式。图片压缩体积大约只有 JPEG 的 2/3，并能节省大量的服务器带宽资源和数据空间。在质量相同的情况下，WebP 格式图像的体积要比 JPEG 格式图像小 40%

#### 12、微格式

- **定义**：微格式（Microformats）是一种让机器可读的语义化 XHTML 词汇的集合，是结构化数据的开放标准。是为特殊应用而制定的特殊格式。微格式主要包括hCard，hCalendar，hAtom等

- **优点：**将数据添加到网页上，让网站内容在搜索引擎结果界面可以显示额外的提示。（应用范例：豆瓣，有兴趣自行 google）

#### 13、从用户刷新网页开始，一次 js 请求一般情况下有哪些地方会有缓存处理？

- **DNS缓存**，短时间内多次访问某个网站，在限定时间内，不用多次访问DNS服务器

- **CDN 缓存**，内容分发网络（人们可以在就近的代售点取火车票了，不用非得到火车站去排队）

  > CDN 是一种部署策略，包括分布式存储、负载均衡、网络请求的重定向和内容管理4个要件，根据不同的地区部署类似nginx 这种服务服务，会缓存静态资源。前端在项目优化的时候，习惯在静态资源上加上一个 hash 值，每次更新的时候去改变这个 hash，hash 值变化的时候，服务会去重新取资源。
  >

- **浏览器缓存**，浏览器在用户磁盘上，对最新请求过的文档进行了存储

  > 浏览器的缓存问题，主要指的是http的缓存——即协议层
  >
  > h5新增的storage和数据库(webSQL、indexedDB）缓存，是应用层缓存

- **服务器缓存**，将需要频繁访问的Web页面和对象保存在离用户更近的系统中，当再次访问的时候加快了速度

#### 14、优化图片的加载的方法

- **图片懒加载**，图片都是“按需加载”，即用户滚动页面时显示出来的时候才加载图片。当网速非常快的时候，用户并不能感知懒加载的动作，既省流量又不影响用户浏览。当页面滚动时，如果图片出现在屏幕中，就利用jQuery把`<img>`的`src`属性替换为`data-src`的内容，浏览器就会实时加载。

- **图片预加载**技术，即提前加载图片，可保证图片快速、无缝地发布，用户需要查看时可直接从本地缓存中渲染，适用于图片占据很大比例的网站。如果为幻灯片、相册等可以将当前展示图片的前一张和后一张优先下载。

  > 参考：http://www.cnblogs.com/haoyijing/p/5818236.html#imgLoad1
  >
  > - 使用jQuery图片预加载插件Lazy Load
  > - 使用js实现图片加载: 就是绑定onload函数,new一个图片对象, 赋值url
  > - 用CSS实现图片的预加载
  >   - 写一个CSS样式设置一批背景图片，然后将其隐藏，增加了页面的整体加载时间
  >   - 改进: 使用js来推迟预加载时间, 防止与页面其他内容一起加载
  > - 用Ajax实现预加载：其实就是通过ajax请求图片地址. 还可以用这种方式加载css,js文件等

- 如果图片为 css 图片，可以使用 **CSSsprite**，SVGsprite，Iconfont、Base64 等技术

- 如果图片过大，可以使用特殊编码的图片，加载时会先加载一张压缩的特别厉害的**缩略图**，以提高用户体验

#### 15、你如何理解 HTML的语义化？

- what?
  - 根据内容的结构（内容语义化：当页面样式加载失败的时候能够让页面呈现出清晰的结构，使 html 代码更具有可读性，便于其他设备解析）
  - 选择合适的标签（代码语义化：便于开发者阅读和写出更优雅的代码的同时让浏览器的爬虫和机器很好地解析）
- why?
  - 为了在没有CSS的情况下，页面也能呈现出很好地内容结构、代码结构；
  - 用户体验：例如title、alt用于解释名词或解释图片信息、label标签的活用；
  - 有利于SEO：和搜索引擎建立良好沟通，有助于爬虫抓取更多的有效信息，爬虫依赖于标签来确定上下文和各个关键字的权重
  - 方便其他设备解析（如屏幕阅读器、盲人阅读器、移动设备）以意义的方式来渲染网页；
  - 便于团队开发和维护，语义化更具可读性，遵循W3C标准的团队都遵循这个标准，可以减少差异化。
- how?
  - 尽可能少的使用无语义的标签div和span；
  - 在语义不明显时，既可以使用div或者p时，尽量用p, 因为p在默认情况下有上下间距，对兼容特殊终端有利；
  - 不要使用纯样式标签，如：b、font、u等，改用css设置。
  - 需要强调的文本，可以包含在strong或者em标签中（浏览器预设样式，能用CSS指定就不用他们），strong默认样式是加粗（不要用b），em是斜体（不用i）；
  - 使用表格时，标题要用caption，表头用thead，主体部分用tbody包围，尾部用tfoot包围。表头和一般单元格要区分开，表头用th，单元格用td；
  - 表单域要用fieldset标签包起来，并用legend标签说明表单的用途；
  - 每个input标签对应的说明文本都需要使用label标签，并且通过为input设置id属性，在lable标签中设置for=someld来让说明文本和相对应的input关联起来。

#### 16、前端需要注意哪些SEO？

- 合理的title、description、keywords：搜索对着三项的权重逐个减小，
  - title值强调重点即可，重要关键词出现不要超过2次，而且要靠前，不同页面title要有所不同；
  - description把页面内容高度概括，长度合适，不可过分堆砌关键词，不同页面description有所不同；
  - keywords列举出重要关键词即可；
- 语义化的HTML代码，符合W3C规范：语义化代码让搜索引擎容易理解网页
- 重要内容HTML代码放在最前：搜索引擎抓取HTML顺序是从上到下，有的搜索引擎对抓取长度有限制，保证重要内容一定会被抓取
- 重要内容不要用js输出：爬虫不会执行js获取内容
- 少用iframe：搜索引擎不会抓取iframe中的内容
- 非装饰性图片必须加alt
- 提高网站速度：网站速度是搜索引擎排序的一个重要指标

#### 17、设置 CSS 样式的方式

- 外部样式表，引入一个外部 css 文件

- 内部样式表，将 css 代码放在style标签内部

- 内联样式，将 css 样式直接定义在 HTML 元素内部

#### 18、CSS 选择器、优先级

- id 选择器（ # myid）
  类选择器（.myclassname）
  标签选择器（div, h1, p）
  相邻选择器（h1 + p）
  子选择器（ul > li）
  后代选择器（li a）
  通配符选择器（ * ）
  属性选择器（a[rel = "external"]）
  伪类选择器（a: hover, li: nth - child）
- 优先级
  - 优先级就近原则，同权重情况下样式定义最近者为准;
  - 载入样式以最后载入的定位为准；
  - 同权重: 内联样式表（标签内部）> 嵌入样式表（当前文件中）> 外部样式表（外部文件中）
  - `!important >内联样式> id > class > tag>浏览器默认样式`
  - 继承的样式没有权值

#### 19、使DOM 元素隐藏的方法

- 设置 display 属性为 none（隐藏对应的元素但不挤占该元素原来的空间，不占位）

- 设置 visibility 属性为 hidden（隐藏对应的元素并且挤占该元素原来的空间，占位）

  > - display:none会让元素完全从渲染树中消失，渲染的时候不占据任何空间；visibility: hidden不会让元素从渲染树消失，渲染的元素继续占据空间，只是内容不可见
  > - display: none是非继承属性，子孙节点消失由于元素从渲染树消失造成，通过修改子孙节点属性无法显示；visibility: hidden是继承属性，子孙节点消失由于继承了hidden，通过设置visibility: visible可以让子孙节点显示
  > - 修改常规流中元素的display通常会造成文档重排；修改visibility属性只会造成本元素的重绘。
  > - 读屏器不会读取display: none元素内容；会读取visibility: hidden元素内容

- 设置宽高为 0

- 设置透明度为 0

- 使用相对定位或者绝定位，然后偏移-999em

- 缩放：

  ```css
  zoom: 0.001; 
  -moz-transform: scale(0); 
  -webkit-transform: scale(0); 
  -o-transform: scale(0); 
  transform: scale(0); 
  ```

#### 20、超链接访问的四个属性

- 排列顺序: L-V-H-A（link,visited,hover,active）

  ```css
  a:link{属性:值;}       /*链接默认状态*/     
  a:visited{属性:值;}     /*链接访问之后的状态*/
  a:hover{属性:值;}      /*鼠标放到链接上显示的状态*/     
  a:active{属性:值;}      /*链接激活的状态*/
  ```

- 注意：被点击访问过的超链接样式不在具有 hover 和 active 了，所以需要按照排序设置


#### 21、css hack原理及常用hack？

原理：利用不同浏览器对CSS的支持和解析结果不一样编写针对特定浏览器样式。

常见的hack有：

- IE条件注释：适用于[IE5, IE9]常见格式如下

```html
<!--[if IE]>此处内容只有IE可见<![endif]--> 
<!--[if IE 6]>此处内容只有IE6.0可见<![endif]--> 
<!--[if IE 7]>此处内容只有IE7.0可见<![endif]--> 
<!--[if !IE 7]>此处内容只有IE7不能识别，其他版本都能识别，当然要在IE5以上。<![endif]-->
<!--[if gt IE 6]> IE6以上版本可识别,IE6无法识别 <![endif]-->
<!--[if gte IE 7]> IE7以及IE7以上版本可识别 <![endif]-->
<!--[if lt IE 7]> 低于IE7的版本才能识别，IE7无法识别。 <![endif]-->
<!--[if lte IE 7]> IE7以及IE7以下版本可识别<![endif]-->
<!--[if !IE]>此处内容只有非IE可见<![endif]-->
```

- 选择器hack：不同浏览器对选择器的支持不一样

```css
*html #demo { color:red;} /* 仅IE6 识别 */
*+html #demo { color:red;} /* 仅IE7 识别 */
body:nth-of-type(1) #demo { color:red;} /*IE9+、FF3.5+、Chrome、Safari、Opera可以识别 */
:root #demo { color:red9; } : /* 仅IE9识别 */
```

- 属性hack：不同浏览器解析bug或方法

```css
 background-color:#f1ee18;/*For latest Firefox, chrome, Safari*/
 background-color:#00deff\9; /*IE6、7、8 识别*/
 +background-color:#a200ff;/*IE6、7 识别*/
 _background-color:#1e0bd1;/*IE6 识别*/
```

#### 22、内联元素、块级元素、行内块元素、空元素

- CSS 规范规定，每个元素都有 display 属性，确定该元素的类型，每个元素都有默认的 display 值，比如 div 默认display 属性值为“block”，成为“块级”元素；span 默认display 属性值为“inline”，是“行内”元素
- 块级元素(block)特性：总是独占一行，表现为另起一行开始，而且其后的元素也必须另起一行显示;宽度(width)、高度(height)、内边距(padding)和外边距(margin)都可控制；常见div p h1~h6 form ul li

- 行内元素(inline)特性：和相邻的内联元素在同一行;宽度(width)、高度(height)、内边距top/bottom(padding-top/padding-bottom)和外边距的 top/bottom(margin-top/margin-bottom)都不可改变（也就是 padding 和 margin 的left 和 right 是可以设置的），就是里面文字或图片的大小，常见a span em strong del ins
- 浏览器还有默认的天生 inline-block 元素（拥有内在尺寸，可设置高宽，但不会自动换行），常见的有`<input>` 、`<img>` 、`button` 、`<texterea>` 、`<label>` 、`input` 
- 空元素：br、hr、img、input、link、meta、area、base、col、command、embed、keygen、source、track、wbr等
- 转换：
  - display转换：display:block 行内元素转换为块级元素；display:inline 块级元素转换为行内元素；display:inline-block 转为内联元素
  - 隐式转换：使用浮动和定位以后，内联元素会隐式转换为行内块元素


#### 23、外边距重叠

- 定义： margin-collapse，在 CSS 当中，相邻的两个盒子（可能是兄弟关系也可能是祖先关系）的外边距可以结合成一个单独的外边距。这种合并外边距的方式被称为折叠，并且因而所结合成的外边距称为折叠外边距。

- 折叠结果遵循的计算规则：两个相邻的外边距都是正数时，折叠结果是它们两者之间较大的值；两个相邻的外边距都是负数时，折叠结果是两者绝对值的较大值；两个外边距一正一负时，折叠结果是两者的相加的和。


#### 24、rgba()和 opacity 的透明效果有什么不同？

- opacity 作用于元素，以及元素内的所有内容的透明度

- rgba()只作用于元素的颜色或其背景色。（设置 rgba 透明的元素的子元素不会继承透明效果！）

#### 25、css 中可以让文字在垂直和水平方向上重叠的两个属性是什么？

- 垂直方向：line-height

- 水平方向：letter-spacing（技巧：可以用于消除 inline-block 元素间的换行符空格间隙问题）

#### 26、px 、 em 、rem的区别

- px 是长度单位，区别是，px 的值是固定的，指定是多少就是多少，计算比较容易。

- em 也是长度单位，但是值不是固定的，并且 em 会继承父级元素的字体大小。浏览器的默认字体高都是16px。所以未经调整的浏览器都符合: 1em=16px，那么12px=0.75em,10px=0.625em。
- rem是相对单位，r是root的意思，在html页面上就是html标签，所以rem的大小是基于html元素的字体大小

#### 27、自己定义的重置样式reset.css和 normalize.css 的区别

- 自己定义的重置样式reset.css是为了统一是不同的浏览器对一些元素有不同的默认样式

- normalize.css既能让众多浏览器达到一致和合理，但又不扰乱其他的东西（如粗体的标题）

- 都是重置样式库，都是为了增强浏览器的表现一致性，但是normalize不会重置已经一致的元素，比如：ul，reset.css 因为需求会设置list-style:none ，但是normalize.css 不会重置ul样式 ，因为本身已经在每个浏览器表现一致的元素

#### 28、什么是CSS 预处理器？

- 定义： CSS 预处理器，是 CSS 上的一种抽象层，是一种特殊的语法/语言编译成 CSS。比如 Less 是一种动态样式语言. 将 CSS 赋予了动态语言的特性，如变量，继承，运算， 函数. LESS 既可以在客户端上运行 (支持 IE 6+, Webkit, Firefox)，也可一在服务端运行(借助 Node.js)。
- Less和SaSS的区别：
  - 变量符不一样，less 是@，而 Sass 是$;
  - Sass 支持条件语句，可以使用 if{}else{},for{}循环等等。而 Less 不支持;
  - Sass 是基于 Ruby 的，是在服务端处理， Less 是需要引入 less.js 来处理 Less 代码输出 Css 到浏览器
- 使用 CSS 预处理器，结构清晰，便于扩展。可以方便地屏蔽浏览器私有语法差异。这个不用多说，封装对浏览器语法差异的重复处理，减少无意义的机械劳动。可以轻松实现多重继承。完全兼容 CSS 代码，可以方便地应用到老项目中。LESS 只是在 CSS 语法上做了扩展，所以老的 CSS 代码也可以与 LESS 代码一同编译。
- 扩展：后处理器例如PostCSS，通常被视为在完成的样式表中根据CSS规范处理CSS，让其更有效；目前最常做的是给CSS属性添加浏览器私有前缀，实现跨浏览器兼容性的问题。

#### 29、CSS 中 link 和@import 的区别

- link 是 XHTML 标签，除了加载 CSS 外，还可以定义 RSS 等其他事务；@import属于 CSS 范畴，只能加载 CSS。

- link 引用 CSS 时，在页面载入时同时加载；@import 需要页面网页完全载入以后加载。

- link 是 XHTML 标签，无兼容问题；@import 是在 CSS2.1 提出的，低版本的浏览器不支持。

- link 支持使用 Javascript 控制 DOM 去改变样式；而@import 不支持

- link 引入样式的权重大于@import 的引用（@import 是将引用的样式导入到当前的页面中）

#### 30、简介盒子模型

CSS 的盒子模型有两种：IE 盒子模型、标准的 W3C 盒子模型

- W3C盒模型：内容width、内边距padding、外边距margin（一般不计入盒子实际宽度）、边框border

- IE 盒模型：width包括内容、内边距、边框

#### 31、为什么要初始化样式？

- 由于浏览器兼容的问题，不同的浏览器对标签的默认样式值不同，若不初始化会造成不同浏览器之间的显示差异

- 但是初始化 CSS 会对搜索引擎优化造成小影响，不要写`*`

- 淘宝的样式初始化代码：

  ```css
   body, h1, h2, h3, h4, h5, h6, hr, p, blockquote, dl, dt, dd, ul, ol, li, pre, form, fieldset, legend, button, input, textarea, th, td { margin:0; padding:0; }
    body, button, input, select, textarea { font:12px/1.5tahoma, arial, \5b8b\4f53; }
    h1, h2, h3, h4, h5, h6{ font-size:100%; }
    address, cite, dfn, em, var { font-style:normal; }
    code, kbd, pre, samp { font-family:couriernew, courier, monospace; }
    small{ font-size:12px; }
    ul, ol { list-style:none; }
    a { text-decoration:none; }
    a:hover { text-decoration:underline; }
    sup { vertical-align:text-top; }
    sub{ vertical-align:text-bottom; }
    legend { color:#000; }
    fieldset, img { border:0; }
    button, input, select, textarea { font-size:100%; }
    table { border-collapse:collapse; border-spacing:0; }
  ```

#### 32、BFC 是什么?

- 定义：

  - FC(Formatting Context): 指的是页面中的一个渲染区域, 并且拥有一套渲染规则, 它决定了其子元素如何定位, 以及与其他元素的相互关系和作用

  - BFC指的是Block Formatting Context，块级格式化上下文，指的是一个独立的块级渲染区域, 只有block-level box参与, 该区域拥有一套渲染规则来约束块级盒子的布局, 且与区域外部无关。它提供了一个环境, html元素在这个环境中按照一定规则进行布局， 一个环境中的元素不会影响到其他环境中的布局，决定了元素如何对其内容进行定位, 以及和其他元素的关系和相互作用.

- BFC的生成:
  - 根元素
  - float的值不为none
  - overflow的值不为visible
  - display的值为 inline-block, table-cell, table-caption
  - position的值为absolute或fixed
- BFC的约束规则
  - 生成BFC元素的子元素会一个接一个的放置。垂直方向上他们的起点是一个包含块的顶部，两个相邻子元素之间的垂直距离取决于元素的margin特性。在BFC中相邻的块级元素外边距会折叠。
  - 生成BFC元素的子元素中，每一个子元素做外边距与包含块的左边界相接触，（对于从右到左的格式化，右外边距接触右边界），即使浮动元素也是如此（尽管子元素的内容区域会由于浮动而压缩），除非这个子元素也创建了一个新的BFC（如它自身也是一个浮动元素）。
  - 分解:
    - 内部的Box会在垂直方向上一个接一个的放置
    - 垂直方向上的距离由margin决定。（完整的说法是：属于同一个BFC的两个相邻Box的margin会发生重叠，与方向无关。）
    - 每个元素的左外边距与包含块的左边界相接触（从左向右），即使浮动元素也是如此。（这说明BFC中子元素不会超出他的包含块，而position为absolute的元素可以超出他的包含块边界）
    - BFC的区域不会与float的元素区域重叠
    - 计算BFC的高度时，浮动子元素也参与计算
    - BFC就是页面上的一个隔离的独立容器，容器里面的子元素不会影响到外面元素，反之亦然
- BFC在布局中的应用
  - 不和浮动元素重叠:
    - 如果一个浮动元素后面跟着一个非浮动元素, 就会产生覆盖
  - 防止margin重叠:
    - 同一个BFC中的两个相邻Box才会发生重叠与方向无关，不过由于上文提到的第一条限制，我们甚少看到水平方向的margin重叠。这在IE中是个例外，IE可以设置write-mode
  - 解决浮动相关问题
    - 父元素: overflow:hidden    IE: zoom:1(hasLayout)
    - 根本原因在于创建BFC的元素，子浮动元素也会参与其高度计算，即不会产生高度塌陷问题。实际上只要让父元素生成BFC即可，并不只有这两种方式。
  - 多栏布局
    - 比如左右两栏宽度固定, 中间栏自适应 则中间栏设置 overflow:hidden生成BFC

#### 33、HTML 与 XHTML二者有什么区别？

- XHTML 元素必须被正确地嵌套
- XHTML 元素必须被关闭，空标签也必须被关闭，如` <br>` 必须写成 `<br />`
- XHTML 标签名必须用小写字母
- XHTML 文档必须拥有根元素
- XHTML 文档要求给所有属性赋一个值
- XHTML 要求所有的属性必须用引号""括起来
- XHTML 文档需要把所有 < 、>、& 等特殊符号用编码表示
- XHTML 文档不要在注释内容中使“--”
- XHTML 图片必须有说明文字
- XHTML 文档中用id属性代替name属性

#### 34、 浏览器常见兼容性问题

- 针对不同浏览器

  - 使用meta标签来调节浏览器的渲染方式，告诉浏览器用哪种内核渲染，360双核浏览器就是在ie和chrome之间来回切换，现在使用meta标签来强制使用最新的内核渲染页面

    ```html
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"/>
    ```

  - CSS3前缀

    ```css
    -webkit- webkit渲染引擎  chrome/safari
    -moz     gecko引擎      firefox
    -ms-     trident渲染引擎 IE
    -o-      presto渲染引擎  opera
    ```

  - 浏 览 器 默 认 的 margin 和 padding 不 同 。 解 决 方 案 是 加 一 个 全 局 的`*{margin:0;padding:0;}`来统一（不推荐）

  - css hack,IE浏览器兼容解决

    ```css
    /*渐进识别的方式，从总体中逐渐排除局部*/
    /*首先，巧妙的使用“\9”这一标记，将 IE 游览器从所有情况中分离出来*/
    /*接着，再次使用“+”将 IE8 和 IE7、IE6 分离开来，这样 IE8 已经独立识别*/
    .bb{
        background-color:#f1ee18;/*For latest Firefox, chrome, Safari*/
        background-color:#00deff\9; /*IE6、7、8 识别*/
        +background-color:#a200ff;/*IE6、7 识别*/
        _background-color:#1e0bd1;/*IE6 识别*/
    }
    ```

- 针对HTML

  - 识别HTML5元素，IE中可能无法识别`nav/footer`，使用`html5shiv`
  - 始终为按钮button添加type属性，IE下的默认类型是button，其他浏览器下的默认类型是submit
  - 火狐下表单阻止表单默认提交事件：在form中添加 `<form action=”javascript:;”>`,阻止上述所有默认行为;
  - select 在 IE6 下遮盖： 使用 iframe 嵌套(在IE6下，浏览器将select元素视为窗口级元素，这时div或者其它的普通元素无论z-index设置的多高都是无法遮住select元素的)
  - Chrome 中文界面下默认会将小于 12px 的文本强制按照 12px 显示, 可通过加入CSS 属性·解决
  - IE ol的序号全为1, 不递增，解决: li设置样式`{display: list-item}`

- 针对css

  - rgba不支持IE8 解决，使用opacity，但是IE5-8 不支持 opacity

    ```css
    .opacity {
    	opacity: 0.4
    	filter: alpha(opacity=60); /*filter 过滤器   兼容IE678 */
    ```

  - 过渡不兼容IE8，可以用JS动画实现

  - background-size（css3）不支持IE8，可以用img

  - ie8不支持nth-child( )，但支持first-child和last-child，可以通过转化写法来处理问题,使用毗邻选择器代替（+），比如：li:nth-child(3)    代替写法：li:first-child+li+li  或者  li+li+li

  - 双边距BUG(IE6)： float 引起的 ，使用 display：inline

    > 块级元素 float 后设置横向 margin，ie6 显示的 margin比设置的大两倍。元素向左浮动并且设置了左侧的外边距出现了这样的双边距bug。同理，元素向右浮动并且设置右边距也会出现同样的情况。同一行如果有 多个浮动元素，第一个浮动元素会出现这个双边距bug，其它的浮动元素则不会

  - 3像素文本偏移bug（IE6）：当一个浮动元素与一个非浮动元素相邻时，在非浮动元素中，会莫名的为靠近浮动元素的内容添加 3 像素的间隙，这是使用 float 引起的，使用 `margin-right: -3px`

  - Min-height 最小高度：`!important` 解决

  - IE z-index 问题 ：给父级添加 `position:relative`

  - 超链接 hover 点击后失效: 使用正确的书写顺序 link visited hover active（LVHA）

  - 无法定义1px左右的宽度容器 （ IE6 默 认 的 行 高 造 成 的 ， 使 用`over:hidden|zoom:0.08 |line-height:1px`）

  - ie6,7不支持display:inline-block，解决：`display:inline-block; *display:inline; *zoom:1` 

- 针对js

  - IE下删除所有不必要的console语句，IE下当遇到console时不识别之后报错，代码不会执行，或者全局自定义一个window.console方法

    ```js
    if(typeof window.console === "undefined") {
    	//浏览器不支持或未启用console，则禁用日志
    	window.console = {
    		log:function(){}
    	};
    }
    ```

  - IE 下,可以使用获取常规属性的方法(点出来的属性)来获取自定义属性, 也可以使用 getAttribute()获取自定义属性,Firefox 下,只能使用 getAttribute()获取自定义属性. 解决方法:统一通过 getAttribute()获取自定义属性

  - IE 下,event 对象有 x,y 属性,但是没有 pageX,pageY 属性;Firefox 下,event 对象有 pageX,pageY 属性,但是没有 x,y 属性

- 其他：

  - IE浏览器下由于参数过长导致通过GET请求下载文件方法报错，解决改为POST请求
  - IE浏览器下iframe弹窗中输入框光标丢失（无法输入）问题，解决清一下frame
  - Png 透明： 使用 js 代码 改,IE6 下使用 gif 图片
  - png24 为的图片在 iE6 浏览器上出现背景，解决方案是做成 PNG8

- 参考自: [常见浏览器兼容性问题与解决方案](http://blog.csdn.net/chuyuqing/article/details/37561313)　　

#### 35、对 WEB 标准以及 W3C 的理解与认识

- 标签闭合、标签小写、不乱嵌套、提高搜索机器人搜索几率
- 使用外 链 css 和 js 脚本、结构行为表现的分离、文件下载与页面速度更快、内容能被更多的用户所访问、内容能被更广泛的设备所访问
- 更少的代码和组件，容易维护、改版方便，不需要变动页面内容
- 提供打印版本而不需要复制内容、提高网站易用性

#### 36、属性继承

可继承就是父节点设置了这个属性后，子节点就可以继承他的属性

- 所有元素可继承：visibility和cursor

- 内联元素可继承：letter-spacing、word-spacing、white-space、line-height、color、font、 font-family、font-size、font-style、font-variant、font-weight、text- decoration、text-transform、direction

- 块状元素可继承：text-indent和text-align

- 列表元素可继承：list-style、list-style-type、list-style-position、list-style-image

- 表格元素可继承：border-collapse

- 不可继承的：display、margin、border、padding、background、height、min-height、max- height、width、min-width、max-width、overflow、position、left、right、top、 bottom、z-index、float、clear、table-layout、vertical-align、page-break-after、 page-bread-before和unicode-bidi

#### 37、CSS3 新增伪类

```css
p:first-of-type /*选择属于其父元素的首个 <p> 元素的每个 <p> 元素*/
p:last-of-type /*选择属于其父元素的最后 <p> 元素的每个 <p> 元素*/
p:only-of-type /*选择属于其父元素唯一的 <p> 元素的每个 <p> 元素*/
p:only-child /*选择属于其父元素的唯一子元素的每个 <p> 元素*/
p:nth-child(2) /*选择属于其父元素的第二个子元素的每个 <p> 元素*/
:enabled、:disabled /*控制表单控件的禁用状态*/
:checked /*单选框或复选框被选中*/
```

#### 38、position定位absolute、fixed 、relative

- static 默认值。没有定位，元素出现在正常的流中（忽略 top, bottom, left, right z-index 声明）

- relative相对定位

  - 脱标，但是保留原来位置（下面的盒子上不来，也可以说是半脱标）,
  - 偏移从以自己标准流中的位置为原点

- absolute 绝对定位

  - 完全脱标，不保留原来位置

  - 父元素没有定位的情况，子盒子以当前屏幕为基准点进行移动

  - 父元素有定位（相对，固定，绝对）的情况，子盒子以父元素（有定位的最近祖元素）为基准点进行移动

- fixed （老 IE 不支持）固定定位

  - 盒子完全脱标，不占位置
  - 父盒子不管有无定位，都是以浏览器为基准点进行移动

#### 39、两栏等高布局(多列等高)

```html
<div>
	<p id="p1">hello<br/>hello<br/>hello<br/>hello</p>
	<p id="p2">world</p>
</div
```

- 方法一：div设置`overfolw：hidden`，p元素浮动并`margin-bottom:-9999px;padding-bottom:9999px;`
- 方法二（表格）：div设置`display:table-row;`p设置 `display:table-cell`
- 方法三（flex）：div设置`display:flex`，p设置`flex:1`(p有宽度不设置也可以)

#### 40、简述 readyonly 与 disabled 的区别

- 元素：readonly 只针对 input(text / password)和 textarea 有效，disabled 对于所有的表单元素都有效，

- 传递：当表单元素在使用了 disabled 后，当我们将表单以POST 或 GET 的方式提交的话，这个元素的值不会被传递出去，而 readonly 会将该值传递出去

#### 41、字体图标的使用

- 图标字体具有矢量效果，放大缩小不失真，而且可以使用CSS任意更改图标字体的颜色,能够缩小源文件的体积，减少http的请求，提高页面的性能

- 网站下载,引入文件，使用

  ```css
  @font-face{
  	font-family: myFirstFont;
  	src: url('Sansation_Light.ttf'),
  	url('Sansation_Light.eot'); /* IE9+ */
  }
  ```

- 使用类库：Font-Awesome等等，MUI、bootstrap都带有字体图标

#### 42、css的 content 属性

- css 的 content 属性专门应用在 before/after 伪元素上，用来插入生成内容。当插入的内容定义宽高和其他属性时，其实就是一个盒子（必须通过display转换，因为默认是一个行内元素）

- 最常见的应用是利用伪类清除浮动

  ```css
  .clearfix:after{
              content: "";
              height: 0;
              overflow: hidden;
              visibility: hidden;
              display: block;
              clear: both;
          } 
  .clearfix {
              zoom: 1;/*兼容IE*/
          }
  
  ```

- css 计数器是通过设置 counter-reset 、counter-increment 两个属性 、及counter()/counters()一个方法配合 after / before 伪类实现。

  ```css
  #demo1 ol { counter-reset: section; list-style-type: none; }
  #demo1 ol li { counter-increment: section; }
  #demo1 ol li:before { content: counters(section, ".") ". "; }
  ```

#### 43、css 动画和 js 动画的差异

- 代码复杂度，js 动画代码相对复杂一些

- 动画运行时，对动画的控制程度上，js 能够让动画，暂停，取消，终止，css动画不能添加事件

- 动画性能看，js 动画多了一个js 解析的过程，性能不如 css 动画好

####  44、什么是SVG？

- SVG 指可伸缩矢量图形 (Scalable Vector Graphics)
- SVG 用来定义用于网络的基于矢量的图形
- SVG 使用 XML 格式定义图形
- SVG 图像在放大或改变尺寸的情况下其图形质量不会有所损失
- SVG 是万维网联盟的标准
- SVG 与诸如 DOM 和 XSL 之类的 W3C 标准是一个整体

#### 45、浏览器渲染机制

- 运行机制：
  - 构建DOM树（parse）：渲染引擎解析HTML文档，首先将标签转换成DOM树中的DOM node（包括js生成的标签）生成内容树（Content Tree/DOM Tree）
  - 构建渲染树（construct）：解析对应的CSS样式文件信息（包括js生成的样式和外部css文件），而这些文件信息以及HTML中可见的指令（如<b></b>），构建渲染树（Rendering Tree/Frame Tree）；
  - 布局渲染树（reflow/layout）：从根节点递归调用，计算每一个元素的大小、位置等，给出每个节点所应该在屏幕上出现的精确坐标；
  - 绘制渲染树（paint/repaint）：遍历渲染树，使用UI后端层来绘制每个节点

- 重绘（repaint或redraw）：

  - 当盒子的位置、大小以及其他属性，例如颜色、字体大小等都确定下来之后，浏览器便把这些原色都按照各自的特性绘制一遍，将内容呈现在页面上。
  - 重绘是指一个元素外观的改变所触发的浏览器行为，浏览器会根据元素的新属性重新绘制，使元素呈现新的外观。
  - 触发重绘的条件：改变元素外观属性。如：color，background-color等。
  - 注意：table及其内部元素可能需要多次计算才能确定好其在渲染树中节点的属性值，比同等元素要多花两倍时间，这就是我们尽量避免使用table布局页面的原因之一。

- 重排（重构/回流/reflow）

  - 当渲染树中的一部分(或全部)因为元素的规模尺寸，布局，隐藏等改变而需要重新构建, 这就称为回流(reflow)。每个页面至少需要一次回流，就是在页面第一次加载的时候。
  - 重绘和重排的关系：在回流的时候，浏览器会使渲染树中受到影响的部分失效，并重新构造这部分渲染树，完成回流后，浏览器会重新绘制受影响的部分到屏幕中，该过程称为重绘。所以，重排必定会引发重绘，但重绘不一定会引发重排。
  - 触发重排的条件：任何页面布局和几何属性的改变都会触发重排，比如：
    - 页面渲染初始化；(无法避免)
    - 添加或删除可见的DOM元素；
    - 元素位置的改变，或者使用动画；
    - 元素尺寸的改变——大小，外边距，边框；
    - 浏览器窗口尺寸的变化（resize事件发生时）；
    - 填充内容的改变，比如文本的改变或图片大小改变而引起的计算值宽度和高度的改变；
    - 读取某些元素属性：（offsetLeft/Top/Height/Width,　clientTop/Left/Width/Height,　scrollTop/Left/Width/Height,　width/height,　getComputedStyle(),　currentStyle(IE)　)

- 重绘重排的代价：耗时，导致浏览器卡慢，优化措施如下：

  - 浏览器自己的优化：浏览器会维护1个队列，把所有会引起回流、重绘的操作放入这个队列，等队列中的操作到了一定的数量或者到了一定的时间间隔，浏览器就会flush队列，进行一个批处理。这样就会让多次的回流、重绘变成一次回流重绘。

  - 我们要注意的优化：我们要减少重绘和重排就是要减少对渲染树的操作，则我们可以合并多次的DOM和样式的修改。并减少对style样式的请求。

    - 直接改变元素的className

    - display：none；先设置元素为display：none；然后进行页面布局等操作；设置完成后将元素设置为display：block；这样的话就只引发两次重绘和重排

    - 不要经常访问浏览器的flush队列属性；如果一定要访问，可以利用缓存。将访问的值存储起来，接下来使用就不会再引发回流；

    - 使用cloneNode(true or false) 和 replaceChild 技术，引发一次回流和重绘

    - 将需要多次重排的元素，position属性设为absolute或fixed，元素脱离了文档流，它的变化不会影响到其他元素；

    - 如果需要创建多个DOM节点，可以使用DocumentFragment创建完后一次性的加入document；

      ```js
      var fragment = document.createDocumentFragment();
       
      var li = document.createElement('li');
      li.innerHTML = 'apple';
      fragment.appendChild(li);
       
      var li = document.createElement('li');
      li.innerHTML = 'watermelon';
      fragment.appendChild(li);
       
      document.getElementById('fruit').appendChild(fragment);
      ```

    - 尽量不要使用table布局

#### 46、浮动和清除浮动

- 浮动可以理解为让某个div元素脱离标准流，漂浮在标准流之上，和标准流不是一个层次。

- 假如某个div元素A是浮动的，如果A元素上一个元素也是浮动的，那么A元素会跟随在上一个元素的后边(如果一行放不下这两个元素，那么A元素会被挤到下一行)；如果A元素上一个元素是标准流中的元素，那么A的相对垂直位置不会改变，也就是说A的顶部总是和上一个元素的底部对齐。

- 清除浮动是为了清除使用浮动元素产生的影响。浮动的元素，高度会塌陷，而高度的塌陷使我们页面后面的布局不能正常显示。

- 关于清除浮动:清除浮动可以理解为打破横向排列。对于CSS的清除浮动(clear)，一定要牢记：这个规则只能影响使用清除的元素本身，不能影响其他元素。

  - 盒子内容固定的情况：给父盒子设置高度（大多数情况下，因为盒子的内容会经常改变）

  - 额外标签法：在最后一个浮动的标签后面增加一个盒子并设置clear：both

  - 父级盒子设置overflow：hidden；触发bfc

  - 单伪元素标签法，需要给父盒子一个类名clearfix

    ```css
    .clearfix:after{
                content: "";
                height: 0;
                overflow: hidden;
                visibility: hidden;
                display: block;
                clear: both;
            } 
    .clearfix {
                zoom: 1;/*兼容IE*/
            }
    ```

  - 双伪元素标签法，需要给父盒子一个类名clearfix

    ```css
    .clearfix :before,.clearfix:after{
                content: "";
                display: table;
            }
    .clearfix:after{
                clear: both;
            } 
    .clearfix {
                zoom: 1;/*兼容IE*/
            }
    ```

- zoom:1的清除浮动原理：
  - 清除浮动，触发hasLayout。Zoom属性是IE浏览器的专有属性，它可以设置或检索对象的缩放比例。解决ie下比较奇葩的bug，譬如外边距（margin）的重叠，浮动清除，触发ie的haslayout属性等。
  - 当设置了zoom的值之后，所设置的元素就会就会扩大或者缩小，高度宽度就会重新计算了，这里一旦改变zoom值时其实也会发生重新渲染，运用这个原理，也就解决了ie下子元素浮动时候父元素不随着自动扩大的问题
  - Zoom属是IE浏览器的专有属性，火狐和老版本的webkit核心的浏览器都不支持这个属性。然而，zoom现在已经被逐步标准化，出现在 CSS 3.0 规范草案中
  - 目前非ie由于不支持这个属性，可以通过css3里面的动画属性scale进行缩放

#### 47、无样式内容闪烁问题

- 概念：如果使用import方法对CSS进行导入,会导致某些页面在Windows 下的Internet Explorer出现一些奇怪的现象:以无样式显示页面内容的瞬间闪烁,这种现象称之为文档样式短暂失效(Flash of Unstyled Content),简称为FOUC。

- 出现：

  - import导入样式表

  - 将样式表放在页面底部

  - 有几个样式表,放在页面不同位置

- 原因:当样式表晚于结构性html加载，当加载到此样式表时，页面将停止之前的渲染。此样式表被下载和解析后，将重新渲染页面，也就出现了短暂的花屏现象

- 解决：使用link标签将样式表放在文档head中

#### 48、如何为有功能限制（低版本IE, 手机浏览）的浏览器提供网页？

- 只提供符合Web标准的页面，提供另一个符合那些浏览器标准的页面
- 兼容: 
  - 渐进增强: 提供一个可用的原型，后来再为高级浏览器提供优化
  - 优雅降级: 据高级浏览器提供一个版本，然后有功能限制的浏览器只需要一个刚好能用的版本
- 相关技术:
  - Media Query针对不同的分辨率的设备；
  - CSS hack针对不同的浏览器；
  - 条件判断`<! --[if !IE]><!-->除IE外都可识别<!--<![endif]-->`

#### 49、HTML全局属性(global attribute)有哪些？

- `accesskey`:设置快捷键，提供快速访问元素（Alt + *accessKey* (或者 Shift + Alt + *accessKey*) 使用快捷键）
- `class`:为元素设置类标识，多个类名用空格分开，CSS和javascript可通过class属性获取元素
- `contenteditable`: 指定元素内容是否可编辑，富文本编辑器的原理
- `contextmenu`: 自定义鼠标右键弹出菜单内容
- `data-*`: 为元素增加自定义属性
- `dir`: 设置元素文本方向
- `draggable`: 设置元素是否可拖拽，HTML5新增的拖拽事件需要先设置这个
- `dropzone`: 设置元素拖放类型： copy, move, link
- `hidden`:样式上会导致元素不显示，不能用这个属性实现样式效果
- `id`: 元素id，文档内唯一
- `lang`: 元素内容的的语言
- `spellcheck`: 是否启动拼写和语法检查
- `style`: 行内css样式
- `tabindex`: 属性规定元素的 tab 键控制次序（当 tab 键用于导航时）
- `title`: 元素相关的建议信息
- `translate`:  规定是否应该翻译元素内容,yes或者no

#### 50、css sprite（精灵图）

概念：将多个小图片拼接到一个图片中，通过background-position和元素尺寸调节需要显示的背景图案。

优点：

- 减少HTTP请求数，极大地提高页面加载速度
- 增加图片信息重复度，提高压缩比，减少图片大小
- 更换风格方便，只需在一张或几张图片上修改颜色或样式即可实现

缺点：

- 图片合并麻烦
- 维护麻烦，修改一个图片可能需要从新布局整个图片，样式

#### 51、如何水平居中一个元素？

- 如果需要居中的元素为常规流中inline元素，为父元素设置`text-align: center;`即可实现

- 如果需要居中的元素为常规流中block元素，1）为元素设置宽度，2）设置左右margin为auto。3）IE6下需在父元素上设置`text-align: center;`,再给子元素恢复需要的值

  ```css
  div{
   	width:200px;
   	margin:0 auto;
    }
  ```

- 如果需要居中的元素为浮动元素，1）为元素设置宽度，2）`position: relative;`，3）浮动方向偏移量（left或者right）设置为50%，4）浮动方向上的margin设置为元素宽度一半乘以-1

  ```css
  div {
      width: 200px;
      height: 200px;
      background: #ff00ff;
      float: left;
      position: relative;
      left: 50%;
      margin-left: -100px;
  }
  ```

- 如果需要居中的元素为绝对定位元素，1）为元素设置宽度，2）偏移量设置为50%，3）偏移方向外边距设置为元素宽度一半乘以-1

  ```css
  /*确定容器的宽高 宽500 高 300 的层,设置层的外边距*/
   div {
   	position: relative;		/* 相对定位或绝对定位均可 */
   	width:500px;
   	height:300px;
   	top: 50%;
   	left: 50%;
   	margin: -150px 0 0 -250px;     	/* 外边距为自身宽高的一半 */
   	background-color: pink;	 	/* 方便看效果 */
  
    }
  ```

  ```css
   /*未知容器的宽高，利用 `transform` 属性*/
   div {
   	position: absolute;		/* 相对定位或绝对定位均可 */
   	top: 50%;
   	left: 50%;
   	transform: translate(-50%, -50%);
   	background-color: pink;	 	/* 方便看效果 */
   }
  ```

  ```css
  /*另外一种方法*/
  div {
   	position: absolute;
   	width: 300px;
   	height: 300px;
   	margin: auto;
   	top: 0;
   	left: 0;
   	bottom: 0;
   	right: 0;
   	background-color: pink;	/* 方便看效果 */
   }
  ```

- 水平垂直居中：利用 flex 布局,实际使用时应考虑兼容性

  ```css
  .container {
   	display: flex;
   	align-items: center; 		/* 垂直居中 */
   	justify-content: center;	/* 水平居中 */
  
   }
   .container div {
   	width: 100px;
   	height: 100px;
   	background-color: pink;		/* 方便看效果 */
   }  
  ```

- 如何垂直居中一个img?（,把img换成行内块元素同样有效）

  ```css
  #container /*<img>的容器设置如下*/
  {
      display:table-cell;
      text-align:center;
      vertical-align:middle;
  }
  ```

- 补充：jQuery实现水平和垂直居中

  ```js
  $(window).resize(function(){
      $(".myblock").css({
          position: "absolute",
          left: ($(window).width() - $(".myblock").outerWidth())/2,
          top: ($(window).height() - $(".myblock").outerHeight())/2     
      });        
  });
  ```

#### 52、iframe有那些缺点？

- iframe会阻塞主页面的onload事件；
- 搜索引擎的检索程序无法解读这种页面，不利于SEO;
- iframe和主页面共享连接池，而浏览器对相同域的连接有限制，所以会影响页面的并行加载

- 使用iframe之前需要考虑这两个缺点。如果需要使用iframe，最好是通过javascript动态给iframe添加src属性值，这样可以绕开以上两个问题

#### 53、Label的作用是什么？是怎么用的？

label标签来定义表单控制间的关系,当用户选择该标签时，浏览器会自动将焦点转到和标签相关的表单控件上。

```html
<label for="Name">Number:</label>
<input type=“text“name="Name" id="Name"/>

<label>Date:<input type="text" name="B"/></label>
```

#### 54、如何在页面上实现一个圆形的可点击区域？

- map+area

  ```html
  <img src="task6.jpg" width="1366" height="768" border="0" usemap="#Map" />  
  <map name="Map" id="Map">  
   	<area shape="circle" coords="100,100,50" href="https://www.baidu.com" 		           target="_blank" />  
  </map>
  ```

- svg

- border-radius

  ```css
  <style>  
   .disc{  
       width:100px;  
       height:100px;  
       background-color:dimgray;  
       border-radius: 50%;  
       cursor: pointer;  
       position: absolute;  
       left:50px;  
       top:50px;    
       line-height: 100px;  
       text-align: center;  
       color: white;  
   }  
  </style>
  
  <div class="disc">点击区域</div>  
  ```

- 纯js实现 需要求一个点在不在圆上简单算法、获取鼠标坐标等等

  ```js
  document.onclick = function(e){
      var r = 50;  //圆的半径
      var x1 = 100,  y1 = 100;  
      var x2 = e.clientX, y2 = e.clientY;
      var len=Math.abs(Math.sqrt(Math.pow(x2-x1,2)+Math.pow(y2-y1,2)));  
      if(len<=50){
          console.log("Inner");
      }else{
          console.log("Outer");
      }
  }
  ```

#### 55、display有哪些值？说明他们的作用

- block       	块类型，默认宽度为父元素宽度，可设置宽高，换行显示
- none        	元素不显示，并从文档流中移除
- inline      	行内元素类型，默认宽度为内容宽度，不可设置宽高，同行显示
- inline-block   默认宽度为内容宽度，可以设置宽高，同行显示
- list-item   	像块类型元素一样显示，并添加样式列表标记
- table       	此元素会作为块级表格来显示
- inherit     	规定应该从父元素继承 display 属性的值

> 如果元素的display为none,那么元素不被渲染,position,float不起作用,
>
> 如果元素拥有position:absolute;或者position:fixed;属性那么元素将为绝对定位,float不起作用.
>
> 如果元素float属性不是none,元素会脱离文档流,根据float属性值来显示.有浮动,绝对定位,inline-block属性的元素,margin不会和垂直方向上的其他元素margin折叠.

#### 56、用纯CSS创建一个三角形的原理是什么？

 把上、左、右三条边隐藏掉（颜色设为 transparent）

```css
#demo {
    width: 0;
    height: 0;
    border-width: 20px;
    border-style: solid;
    border-color: transparent transparent red transparent;
  }
```

#### 57、visibility：collapse

- 对于普通元素visibility:collapse会将元素完全隐藏，不占据页面布局空间,与display:none表现相同
- 如果目标元素为table，visibility:collapse将table隐藏，但是会占据页面布局空间，仅在Firefox、Chrome下起作用，IE会显示元素

#### 58、元素竖向的百分比设定是相对于容器的高度吗？

- 如果是height的话，是相对于容器高度
- 如果是padding-height,margin-height则是相对于容器的宽度

#### 59、全屏滚动的原理是什么？

```js
window.onmousewheel=function(){
    //代码
}
```

fullPage.js 是一个基于 jQuery 的插件，它能够很方便、很轻松的制作出全屏网站，主要功能有支持鼠标滚动、支持前进后退和键盘控制多个回调函数、支持手机平板触摸事件、支持 CSS3 动画、支持窗口缩放、窗口缩放时自动调整、可设置滚动宽度、背景颜色、滚动速度、循环选项、回调、文本对齐方式等等。兼容 jQuery 1.7+，兼容IE8+。下载和了解更多可以点击[这里](http://www.dowebok.com/77.html)。

#### 60、视差滚动效果，如何给每页做不同的动画？

- background-attachment属性设置背景图像是否固定或者随着页面的其余部分滚动。scroll默认值。背景图像会随着页面其余部分的滚动而移动。fixed当页面的其余部分滚动时，背景图像不会移动。
- 视差滚动指网页滚动过程中，多层次的元素进行不同程度的移动，视觉上形成立体运动效果的网页展示技术。主要核心就是前景和背景以不同速度移动，从而创造出3D效果。利用background-attachment属性实现。[stellar.js](https://github.com/markdalgleish/stellar.js)是一个jQuery插件，能很容易地给网站添加视差滚动效果

#### 61、::before 和 :after中双冒号和单冒号有什么区别？

-  想让插入的内容出现在其它内容前，使用`::before`，否者，使用`::after`；
-  在代码顺序上，`::after`生成的内容也比`::before`生成的内容靠后。如果按堆栈视角，`::after`生成的内容会在`::before`生成的内容之上
-  单冒号(:)用于CSS3伪类，双冒号(::)用于CSS3伪元素。（伪元素由双冒号和伪元素名称组成） 双冒号是在当前规范中引入的，用于区分伪类和伪元素。不过浏览器需要同时支持旧的已经存在的伪元素写法，比如:first-line、:first-letter、:before、:after等，而新的在CSS3中引入的伪元素则不允许再支持旧的单冒号的写法。

#### 62、溢出文字隐藏(使用css截取指定文字长度)

```css
div{
    border: 1px solid #000;
    width: 250px;
    white-space: nowrap;/*  强制一行*/
    overflow: hidden;/* 隐藏溢出部分 */
    text-overflow: ellipsis;/* 使用省略号 */
}
```

## 二、JavaScript

#### 1、javascript 的数据类型

- 基本数据类型：String，Boolean，number，undefined，Null，symbol(ES6，创建后独一无二且不可变的数据类型)基本类型值在内存中占据固定大小的空间，属于被频繁使用数据,因此被保存在栈内存中

- 引用数据类型：Object(Array,Date,RegExp,Function)，引用类型的值是对象, 保存在堆内存中. 包含引用类型的变量实际上包含的并不是对象本身, 而是一个指向改对象的指针

- 判断

  - tyepof判断

    ```javascript
    //返回object number function boolean underfind string symbol(ES6)
    //typeof (引用类型) 除了函数, 都是 'object'
    typeof null;//object
    typeof isNaN;//function
    typeof isNaN(123);//boolean
    typeof [];//object
    typeof new String("abc") === 'object';
    ```

  - obj instanceof Array （在某些 IE 版本中不正确）

    ```javascript
    //instanceof 用于判断一个变量是否某个对象的实例,或用于判断一个变量是否某个对象的实例
    //instanceof 后面一定要是对象类型，并且大小写不能错，该方法适合一些条件选择或分支
    console.log(Object instanceof Object);//true 
    console.log(Function instanceof Function);//true 
    console.log(Number instanceof Number);//false 
    console.log(String instanceof String);//false 
    console.log(Function instanceof Object);//true 
    console.log(null instanceof Object);//false
    console.log(undefined instanceof Object);//false
    console.log(Array instanceof Object);//true
    console.log(Array instanceof Array);//false
    ```

  - Object.prototype.toString.call( ) 常用于判断数组、正则这些复杂类型，不能识别自定义对象类型

    ```js
    console.log(Object.prototype.toString.call(123)) //[object Number]
    console.log(Object.prototype.toString.call('123')) //[object String]
    console.log(Object.prototype.toString.call(undefined)) //[object Undefined]
    console.log(Object.prototype.toString.call(true)) //[object Boolean]
    console.log(Object.prototype.toString.call({})) //[object Object]
    console.log(Object.prototype.toString.call([])) //[object Array]
    console.log(Object.prototype.toString.call(function(){})) //[object Function]
    ```

  - constructor 用于判断一个变量的原型，constructor 属性返回对创建此对象的数组函数的引用

    ```js
    var c= [1,2,3];
    var d = new Date();
    var e = function(){alert(111);};
    alert(c.constructor === Array) // true
    alert(d.constructor === Date) //true
    alert(e.constructor === Function) // true
    //注意： constructor 在类继承时会出错
    ```

  - jQuery中的方法$.type()

    ```js
    //如果对象是undefined或null，则返回相应的“undefined”或“null”。
    jQuery.type( undefined ) // "undefined"
    jQuery.type() // "undefined"
    jQuery.type( window.notDefined ) // "undefined"
    jQuery.type( null ) // "null"
    //如果对象有一个内部的[[Class]]和一个浏览器的内置对象的 [[Class]] 相同，返回相应的[[Class]] 名字。 
    jQuery.type( true ) // "boolean"
    jQuery.type( 3 ) // "number"
    jQuery.type( "test" ) // "string"
    jQuery.type( function(){} ) // "function"
    jQuery.type( [] ) // "array"
    jQuery.type( new Date() ) // "date"
    jQuery.type( new Error() ) // "error" // as of jQuery 1.9
    jQuery.type( /test/ )// "regexp"
    //其他一切都将返回它的类型“object”
    ```

- 比如：判断一个变量是不是数组
  - Array.isArray(arr)
  - arr instanceof Array
  - Object.prototype.toString.call(arr) //[object Array]

#### 2、强制类型转换和隐式类型转换

```javascript
//强制转换
parseInt('xxx');parseFloat('xxx');Number('xxx');
String('xxx');xxx.toString()
Boolean('xxx')
//隐式转换
1==”1”//true
null==undefined//true
!!2 ;//true --双向非操作可以把字符串和数字转换为布尔值
```

#### 3.数组方法

```javascript
//1.数组连接符join，返回一个字符串
arr.join("&");

//2. Array.from() 方法复制,克隆一个新的数组
Array.from(arr);

//3.concat() 方法用于合并两个或多个数组。此方法不会更改现有数组，而是返回一个新数组。
arr1.concat(arr2));

//4.every(函数) 方法测试数组的所有元素是否都通过了指定函数的测试,返回布尔值
arr.every(function(element,index,arr){
   return element>100;
});

//5.filter(函数) 方法返回一个新数组, 其包含通过所提供函数实现的测试的所有元素。
arr.filter(function(ele){
    return ele>100;
});

//6.push() 方法将一个或多个元素添加到数组的末尾，并返回新数组的长度。
arr.push(50)；

//7.pop()方法从数组中删除最后一个元素，并返回该元素的值。
arr.pop();

//8.shift() 方法从数组中删除第一个元素，并返回该元素的值。
arr.shift();

//9.unshift() 方法将一个或多个元素添加到数组的开头，并返回新数组的长度。
arr.unshift(50);

//10.forEach(函数) 方法对数组的每个元素执行一次提供的函数。相当于for循环
var arr=[1,5,"html","前端"];
var flag=arr.forEach(function(ele){
    console.log(ele+"abc");
});//1abc 5abc  htmlabc 前端abc-------没有返回一个新数组! & 没有返回值!

//11.indexOf()方法返回给定元素的第一个索引，如果不存在，则返回-1。
var arr=[1,5,"html","前端"];
console.log(arr.indexOf(5));//1
console.log(arr.indexOf("css"));//-1

//12. map(函数) 方法创建一个新数组，该数组中的每个元素都执行函数,返回结果的新数组
var arr=[1,10,100,1000];
var flag=arr.map(function(ele){
    return ele+1;
})
console.log(flag);//[2, 11, 101, 1001];

//13.reverse() 方法将数组中元素的位置颠倒。反转数组
var arr=[1,10,100,1000]; 
console.log(arr.reverse());//[1000, 100, 10, 1]

//14.sort() 方法对数组的元素进行排序，并返回数组。(有可能不稳定,加MDN固定代码)
var arr=[100,50,20,2000,6];
console.log(arr.sort());//默认排序顺序是根据字符串Unicode码点。

//15. slice(开始的索引,结束的索引)截取,不包括最后一个索引的值,返回新数组
var arr=[100,50,20,2000,6];
console.log(arr.slice(2,4));// [20, 2000]-----不包括arr[4]

//16.splice(a,b,c) 方法通过删除现有元素和/或添加新元素来更改一个数组的内容。
//第一个参数a---开始的位置
//第二个参数b---要删除的个数
//第三个参数c---替换的元素的值
var arr=["html","css","JavaScript"];
console.log(arr.splice(1,0));//[]  ----没有删除的,返回空数组
console.log(arr.splice(1,1));//-----返回被删除的["css"]
console.log(arr.splice(1,1,"new"));//----返回被删除的数组["css"],
//但是此时在输出arr)是["html", "new", "JavaScript"]
```

#### 4、call 、 apply 、bind的区别

- apply和call

  ```javascript
  //写法：只要想使用别的对象的方法，并且希望这个方法是当前对象
  //函数名字/方法.apply(对象,[参数1,参数2,.....])
  //函数名字/方法.call(对象,参数1,参数2,.......)
  //方法中如果没传入参数，或者是null，那么调用该方法的函数对象中的this就是默认的window
  //作用，调用函数，改变this的指向
  function Person(age){
      this.age=age;
  }
  Person.prototype.sayHi=function(x,y){
      console.log((x+y)+"=======>"+this.age);
  };
  function Student(age){
      this.age=age;
  }
  var per=new Person(10);//Person的实例对象
  var stu=new Student(100);//Student的实例对象
  //sayHi方法是per实例对象原型里面的方法，
  //通过apply和call方法,stu调用了这个方法
  //sayHi方法里面的this,由原来的per变成了stu
  per.sayHi.apply(stu,[10,20]);//30=======>100
  per.sayHi.call(stu,10,20);//30=======>100
  
  //apply和call方法并不在函数这个实例对象中，而是在Function的原型prototype中
  ```

- bind

  ```javascript
  //bind方法是复制的意思,参数可以在复制的时候传进去,也可以在复制之后调用的时候传入进去
  //bind是在复制的时候改变this指向的,而apply和call是在调用的时候改变this指向的
  //使用方法:
  //1.函数名字.bind(对象,参数1,参数2,...)------>返回复制后的函数
  function f1(x,y){
      console.log(x+y);
  }
  var f2=f1.bind(null,10,20);
  f2();//30
  //2.方法名字.bind(对象,参数1,参数2,...)------>返回复制后的方法
  function Person(age){
      this.age=age;
  }
  Person.prototype.show=function(){
      console.log(this+"======"+this.age);
  };
  function Student(age){
      this.age=age;
  }
  var per=new Person(10);
  var stu=new Student(20);
  //stu对象使用bind复制了一份per的方法
  var ff=per.show.bind(stu);
  ff();//[object Object]======20
  ```

- call 和 apply 相同点：都是为了用一个本不属于一个对象的方法，让这个对象去执行

  ```javascript
  toString.call([],1,2,3);//"[object Array]"
  toString.apply([],[1,2,3]);//"[object Array]"
  Object.call(this,obj1,obj2,obj3);//
  Object.apply(this,arguments)
  ```


#### 5、继承

- 原型链继承

  ```javascript
  //为了数据共享，改变原型指向，做到了继承（通过改变原型指向的继承）
  //缺陷：因为改变原型指向的同时实现的继承，直接初始化了属性，继承过来的值都是一样的
  function Person(name,age){
      this.name=name;
      this.age=age;
  }
  Person.prototype.eat=function(){
      console.log("吃饭");
  };
  function Student(score){
      this.score=score;
  }
  Student.prototype=new Person("小明",10);
  //Student添加原型方法(必须在指向改变之后)
  Student.prototype.study=function(){
      console.log("学习");
  };
  var stu=new Student(100);
  console.log(stu.score);//100
  console.log(stu.name);//小明
  console.log(stu.age);//10
  stu.study();//学习
  stu.eat();//吃饭
  ```

- 借用构造函数继承

  ```javascript
  //解决办法就是使用借用构造函数的方法（构造函数.call（对象,属性1,属性2,......））
  function Person(name,age,weight,sex){
      this.name=name;
      this.age=age;
      this.weight=weight;
      this.sex=sex;
      this.show=function(){
          console.log("人");
      };
  }
  Person.prototype.sayHi=function(){
      console.log("你好");
  };
  function Student(name,age,weight,sex,score){
      Person.call(this,name,age,weight,sex);
      this.score=score;
  }
  var stu=new Student("小明",18,"50kg","男",100);
  console.log(stu.name);//小明
  console.log(stu.age);//18
  console.log(stu.weight);//50kg
  console.log(stu.sex);//男
  console.log(stu.score);//100
  stu.show();//人(实例对象的方法可以继承)
  stu.sayHi();//报错(原型添加的方法不能继承)
  ```

- 组合继承（原型+借用构造函数）

  ```javascript
  //借用构造函数的方法无法继承原型添加的方法,解决办法是使用组合继承：原型继承+借用构造函数继承
  function Person(name,age,weight,sex){
      this.name=name;
      this.age=age;
      this.weight=weight;
      this.sex=sex;
      this.show=function(){
          console.log("人");
      };
  }
  Person.prototype.sayHi=function(){
      console.log("你好");
  };
  function Student(name,age,weight,sex,score){
      Person.call(this,name,age,weight,sex);
      this.score=score;
  }
  Student.prototype=new Person();
  var stu=new Student("小明",18,"50kg","男",100);
  console.log(stu.name);//小明
  console.log(stu.age);//18
  console.log(stu.weight);//50kg
  console.log(stu.sex);//男
  console.log(stu.score);//100
  stu.show();//人
  stu.sayHi();//你好
  
  ```

- 拷贝继承

  ```javascript
  //把一个对象中的属性或者方法，通过遍历的方法，直接复制到另外一个对象中
  function Person(name){
      this.name=name;
  }
  Person.prototype.age=10;
  Person.prototype.sex="男";
  Person.prototype.weight="60kg";
  Person.prototype.sayHi=function(){
      console.log("你好");
  };
  var obj2={};
  //Person的构造函数中有原型对象prototype,prototype就是一个对像
  //那么age,sex,weight,sayHi都是该对象的属性和方法
  for(var key in Person.prototype){
      obj2[key]=Person.prototype[key];
  }
  console.log(obj2.age);//10
  console.log(obj2.sex);//男
  console.log(obj2.weight);//60kg
  obj2.sayHi();//你好
  ```

- 寄生式继承

  ```javascript
  function createAnother(original){
   	var clone = Object.create(original); //通过调用函数创建一个新对象
   	clone.sayHi = function(){    //以某种方式来增强这个对象
   	 	alert("Hi");
   	};
   	return clone;      //返回这个对象
  }
  
  var person = {
   	name: "Bob",
   	friends: ["Shelby", "Court", "Van"]
  };
  var anotherPerson = createAnother(person);
  anotherPerson.sayHi();
  ```

- 寄生组合继承

  ```javascript
  function inheritPrototype(subType, superType){
   	var protoType = Object.create(superType.prototype); //创建对象
   	protoType.constructor = subType;     //增强对象
   	subType.prototype = protoType;      //指定对象
  }
  function SuperType(name){
   	this.name = name;
   	this.colors = ["red", "blue", "green"];
  }
  SuperType.prototype.sayName = function(){
   	alert(this.name);
  }
  
  function SubType(name, age){
   	SuperType.call(this, name);　　//第二次调用SuperType()
   	this.age = age;
  }
  inheritPrototype(SubType, SuperType)
  	SubType.prototype.sayAge = function(){
   	alert(this.age);
  }
  var instance = new SubType("Bob", 18);
  instance.sayName();
  instance.sayAge();
  ```

#### 6、this的指向

- 指向：

  - 作为函数调用，this 绑定全局对象，浏览器环境全局对象为 window 

  - 内部函数的 this 也绑定全局对象，应该绑定到其外层函数对应的对象上

  - 作为构造函数使用，this 绑定到新创建的对象

  - 作为对象方法使用，this 绑定到该对象

  - 使用apply或call调用 this 将会被显式设置为函数调用的第一个参数

  - 箭头函数 箭头函数的this绑定看的是this所在函数定义在哪个对象下，就绑定哪个对象。如果有嵌套的情况，则this绑定到最近的一层对象上

    > this指向的固定化，并不是因为箭头函数内部有绑定this的机制，实际原因是箭头函数根本没有自己的this，导致内部的this就是外层代码块的this。正是因为它没有this，所以也就不能用作构造函数。

  - 在事件中，this指向触发这个事件的对象，特殊的是，IE中的attachEvent中的this总是指向全局对象Window

  - 举例：

    ```js
    //1.普通函数中的this------------window
    function f1(){
        console.log(this);
    }
    f1();//Window
    
    //2.定时器中的this---------------window
        setInterval(function(){
             console.log(this);//Window
         },1500)
    
    //3.构造函数中的this------------实例对象
    //4.对象.方法中的this----------当前的实例对象(谁调用就是谁)
    //5.原型方法中的this----------实例对象
    function Person(){
        this.name=name;
        this.show1=function(){
            console.log(this);
        }
    }
    Person.prototype.show2=function(){
        console.log(this);
    }
    var per=new Person("小明");
    per.show1();//Person {name: "", show1: ƒ}
    per.show2();//Person {name: "", show1: ƒ}
    
    //6.严格模式下的this-----------undefined
    function f2(){
        "use strict";
        console.log(this);
    }
    f2();//undefined
    
    //7、此处的this是按钮元素
    var btn = document.getElementById("text");
        btn.onclick = function() {
            alert(this.value);    
    }
    ```

- 怎么改变this的指向呢？
  - 使用es6的箭头函数
  - 在函数内部使用that = this
  - 使用apply，call，bind
  - new实例化一个对象

#### 7、闭包

理解：函数嵌套函数，内部函数可以访问定义他们外部函数的参数和变量。在本质上，闭包就是将函数内部和函数外部连接起来的一座桥梁。作用域链的向上查找，把外围的作用域中的变量值存储在内存中而不是在函数调用完毕后销毁）设计私有的方法和变量，避免全局变量的污染。使用闭包的目的是隐藏变量，间接访问一个变量，在定义函数的词法作用域外，调用函数。

特性：

- 函数内再嵌套函数
- 内部函数可以引用外层的参数和变量
- 参数和变量不会被垃圾回收机制回收

```javascript
function outer(){
	var num = 1;
	return function inner(){
        var n = 2;
        num++;
		console.log(n + num);
	}
}
var res = outer();
res();//4
res();//5
res();//6
```

缺点：滥用闭包函数会造成内存泄露，因为闭包中引用到的包裹函数中定义的变量都永远不会被释放，所以我们应该在必要的时候，及时释放这个闭包函数

```javascript
window.onload = function(){
　　var oLis = document.getElementById("test").getElementsByTagName("li");
　　for(var i = 0;i < oLis.length;i ++){
　　　　oLis[i].onclick = function(){
　　　　　　alert(i); //每次都是4
　　　　}
　　}
}
//方法一：通过过自执行函数，将变量i保存到这个自执行函数的参数中
window.onload = function(){
　　var oLis = document.getElementById("test").getElementsByTagName("li");
　　for(var i = 0;i < oLis.length;i ++){
　　　　(function(i){
　　　　　　oLis[i].onclick = function(){
　　　　　　　　alert(i); //0123
　　　　　　}
　　　　})(i);
　　}
}
//方法二：赋值给oLis[i]对象的index属性，在通过this指向，取出点击当前对象的index的值
window.onload = function(){
　　var oLis = document.getElementById("test").getElementsByTagName("li");
　　for(var i = 0;i < oLis.length;i ++){
　　　　oLis[i].index = i;
　　　　oLis[i].onclick = function(){
　　　　　　alert(this.index); //0123
　　　　}
　　}
}

//方法三：let允许声明一个作用域被限制在块级中的变量、语句或者表达式。
window.onload = function(){
　　var oLis = document.getElementById("test").getElementsByTagName("li");
　　for(let i = 0;i < oLis.length;i ++){
　　　　oLis[i].onclick = function(){
　　　　　　alert(i); //0123
　　　　}
　　}
}
```

#### 8、作用域和作用域链

作用域：

- 定义一个函数就开辟了一个局部作用域，整个 js 执行环境有一个全局作用域

- JavaScript（ES5）中没有块作用域，函数的嵌套形成不同层次的作用域，嵌套的层次形成链式形式，通过作用域链查找属性

- 内部环境可以通过作用域链访问所有的外部环境中的变量对象，但外部环境无法访问内部环境。每个环境都可以向上搜索作用域链，以查询变量和函数名，反之向下则不能。

```javascript
function changeObjectProperty (o) {
    o.siteUrl = "http://www.csser.com/";
    o = new Object();
    o.siteUrl = "http://www.popcg.com/";
}
var CSSer = new Object();
changeObjectProperty(CSSer);
console.log(CSSer.siteUrl);//http://www.csser.com/
```

作用域链：

- 作用域链是函数被创建的作用域中对象的集合。函数变量是从本作用域开始寻找,从里到外，当需要从局部函数查找某一属性或方法时，如果当前作用域没有找到，就会上溯到上层作用域查找，直至全局函数，这种组织形式就是作用域链
- 作用域链可以保证对执行环境有权访问的所有变量和函数的有序访问。作用域链的最前端始终是当前执行的代码所在环境的变量对象（如果该环境是函数，则将其活动对象作为变量对象），下一个变量对象来自包含环境，全局执行环境的变量对象始终是作用域链中的最后一个对象。

#### 9、IE 和标准下有哪些兼容性的写法

```javascript
//事件参数对象
var e = e || window.event
//获取页面宽高
document.documentElement.clientWidth || document.body.clientWidth
//当前事件源
var target = e.srcElement||e.target
```

#### 10、事件绑定

- 事件绑定是指把事件注册到具体的元素之上，普通事件指的是可以用来注册的事件

- 如果说给同一个元素绑定了两次或者多次相同类型的事件，那么后面的绑定会覆盖前面的绑定,、不支持 DOM 事件流 事件捕获阶段=>目标元素阶段=>事件冒泡阶段

  ```html
  div1.onclick=function(){};
  <button onmouseover=””></button>
  ```

- 如果说给同一个元素绑定了两次或者多次相同类型的事件，所有的绑定将会依次触发,支持 DOM 事件流，进行事件绑定传参不需要 on 前缀

  ```javascript
  //多个元素嵌套，有层次关系，这些元素都注册了相同的事件,子元素触发,父元素跟着触发
  addEventListener(“click”,function(){});//默认值是false,即从里到外触发,冒泡阶段
  addEventListener(“click”,function(){},true);//设置为true，从外到里触发，捕获阶段
  ```

- IE的事件绑定：进行事件类型传参需要带上 on 前缀； 这种方式只支持事件冒泡，不支持事件捕获；

  ```javascript
  //ie9 以前：attachEvent/detachEvent
  //ie9 开始，ie11 edge,开始跟 DOM 事件流是一样的：addEventListener
  ```

#### 11、事件冒泡和事件捕获

- DOM事件流模型

  - “事件冒泡”：事件开始由最具体的元素接受，然后逐级向上传播

  - “事件捕获”：事件由最不具体的节点先接收，然后逐级向下，一直到最具体的

  - “DOM 事件流”：三个阶段：事件捕捉，目标阶段，事件冒泡

    > 多个元素嵌套，有层次关系，这些元素都注册了相同的事件,子元素触发,父元素跟着触发
    >
    > addEventListener("type",fn,bool),第三个参数是控制事件阶段的,默认是冒泡阶段,很少用捕获阶段
    >
    > 通过e.eventPhase这个属性可以知道当前这个事件是什么阶段的
    > ​    *如果属性的值是1----->事件捕获阶段(从外到里)----第三个参数值是true
    > ​    *如果属性的值是2----->事件目标阶段
    > ​    *如果属性的值是3----->事件冒泡阶段(从里到外)-----第三个参数值是false
    > ​    *事件一般都是捕获阶段和目标阶段结合,或者冒泡阶段和目标阶段结合,不会出现捕获阶段和冒泡阶段结合

- 在JS中，绑定的事件默认的执行时间是在冒泡阶段执行，而非在捕获阶段（重要），这也是为什么当父类和子类都绑定了某个事件，会先调用子类绑定的事件，后调用父类的事件。

#### 12、事件委托（事件代理）

定义：在元素的父节点注册事件，通过事件冒泡，在父节点捕获事件，即把一个或者一组元素的事件委托到它的父层或者更外层元素上

优点：减少内存消耗，动态绑定事件

> 在JavaScript中，添加到页面上的事件处理程序数量将直接关系到页面的整体运行性能。导致这一问题的原因是多方面的。首先，每个函数都是对象，都会占用内存；内存中的对象越多，性能就越差。其次，必须事先指定所有事件处理程序而导致的DOM访问次数，会延迟整个页面的交互就绪时间。对“事件处理程序过多”问题的解决方案就是事件委托。事件委托利用了事件冒泡，只指定一个事件处理程序，就可以管理某一类型的所有事件。例如，click事件会一直冒泡到document层次。也就是说，我们可以为整个页面指定一个onclick事件处理程序，而不必给每个可单击的元素分别添加事件处理程序。

使用：target 是触发事件的最具体的元素，currenttarget是绑定事件的元素(在函数中一般等于this)

- js原生

  ```html
  <ul id = "lists">
           <li>列表1</li>
           <li>列表2</li>
           <li>列表3</li>
           <li>列表4</li>
  </ul>
  <script>
  	var lists = document.getElementById("lists");
      lists.addEventListener("click",function(e){
          var event = e || window.event;
  		var target = event.target || event.srcElement;
          //防止父元素ul也触发事件
          if(target.nodeName == "LI"){
               target.style.backgroundColor = "red";
           }
       })
  </script>
  ```

- jQuery(推荐使用on)

  ```js
  $(function(){
      $("#lists").on("click","li",function(event){
          var target = $(event.target);
          target.css("background-color","red");
      })
  })
  ```

#### 13、如何阻止事件冒泡和默认事件

- 阻止事件冒泡

  ```javascript
  e.stopPropagation();//标准浏览器.谷歌和火狐支持,e是火狐的标准,也是事件参数对象
  
  window.event.cancelBubble=true;//ie9 之前,谷歌支持,火狐不支持,window.event是IE中的标准
  ```

- 阻止默认事件

  ```javascript
  //为了不让 a 点击之后跳转，我们就要给他的点击事件进行阻止
  return false;//javascript的return false只会阻止默认行为，而是用jQuery的话则既阻止默认行为又防止对象冒泡
  e.preventDefault();//w3c方法
  window.event.returnValue == false;//IE
  ```

#### 14、元素创建、追加、查找

- 创建

  ```js
  createDocumentFragment() //创建一个 DOM 片段
  createElement() //创建一个具体的元素
  createTextNode() //创建一个文本节点
  ```

- 追加

  ```javascript
  obj.appendChild() //添加
  obj.insertBefore()//插入，原生的 js 中不提供 insertAfter();
  obj.replaceChild()//替换
  obj.removeChild()//删除
  ```

- 查找

  ```javascript
  document.getElementsByTagName() //通过标签名称
  document.getElementsByName() //通过元素的 Name 属性的值
  document.getElementById() //通过元素 Id，唯一性
  document.getElementsByClassName('class');//通过类名
  ```

#### 15、 本地对象，内置对象和宿主对象

- 本地对象（内部对象、原生对象）为 Object、Function、Array、String、Boolean、Number、Date、RegExp 等可以 new 实例化的，

- 内置对象为 Global（全局对象）、Math 、JSON等不可以实例化的

  > Global即为全局对象，Global对象是ECMAScript中最特别的对象，因为实际上它根本不存在！在ECMAScript中，不存在独立的函数，所有函数都必须是某个对象的方法。类似于isNaN()、parseInt()和parseFloat()方法等，看起来都是函数，而实际上，它们都是Global对象的方法

- 宿主对象为浏览器自带的 document，window 等

#### 16、window.onload 和 document.ready 的区别？

- window.onload

  - 要等到图片和包含的文件都加在进来之后执行；
  - window.onload事件多个只会执行最下面的一个，前面的会被覆盖
  - jQuery(window).load(简写(window).load)可以使事件在页面加载完毕再执行，效果和window.onload一样，但是多个会执行多个，这一点和window.onload不一样

- document.ready

  - jQuery里的方法，不是js原生的，jQuery(document).ready(简写$(document).ready)是不包含图片和非文字文件的文档结构准备好就执行，也多个会执行多个
  - jQuery( )(简写$( ))可以使事件在页面基本加载完毕再执行，和jQuery(document).ready一样，也是多个会执行多个

- 原生js

  ```js
  //当初始的 HTML 文档被完全加载和解析完成之后，
  //DOMContentLoaded 事件被触发，而无需等待样式表、图像和子框架的完成加载
  document.ready = function(callback) {
      //兼容FF,Google
     if (document.addEventListener){
         document.addEventListener('DOMContentLoaded', function(){
             document.removeEventListener('DOMContentLoaded',arguments.callee, false);
              callback();
          }, false)
      }
       //兼容IE
      else if (document.attachEvent) {
          document.attachEvent('onreadystatechange', function (){
                if (document.readyState == "complete"){
                     document.detachEvent("onreadystatechange", arguments.callee);
                     callback();
                 }
          })
      }
      else if (document.lastChild == document.body) {
          callback();
      }
  }
  ```

#### 17、”==”和“===”的不同

前者会自动转换类型，1==”1”，null==undefined

> 1. 如果两个值类型相同，按照===比较方法进行比较
> 2. 如果类型不同，使用如下规则进行比较
> 3. 如果其中一个值是null，另一个是undefined，它们相等
> 4. 如果一个值是**数字**另一个是**字符串**，将**字符串转换为数字**进行比较
> 5. 如果有布尔类型，将**true转换为1，false转换为0**，然后用==规则继续比较
> 6. 如果一个值是对象，另一个是数字或字符串，将对象转换为原始值然后用==规则继续比较
> 7. **其他所有情况都认为不相等**

后者不会，先判断左右两边的数据类型，如果数据类型不一致，直接返回 false，之后才会进行两边值的判断

> 1. 如果两个值不是相同类型，它们不相等
> 2. 如果两个值都是null或者都是undefined，它们相等
> 3. 如果两个值都是布尔类型true或者都是false，它们相等
> 4. 如果其中有一个是**NaN**，它们不相等
> 5. 如果都是数值型并且数值相等，他们相等， -0等于0
> 6. 如果他们都是字符串并且在相同位置包含相同的16位值，他它们相等；如果在长度或者内容上不等，它们不相等；两个字符串显示结果相同但是编码不同==和===都认为他们不相等
> 7. 如果他们指向相同对象、数组、函数，它们相等；如果指向不同对象，他们不相等

#### 18、编写一个数组去重的方法

```javascript
//1.利用对象属性存在的特性，如果没有该属性则存入新数组。
function arrRemoval(arr) {
    var obj ={};
    var newArr=[];
    for(var i=0;i<arr.length;i++){
    	if(!obj[arr[i]]) {//!obj[arr[i]]=true，obj[arr[i]]=false即表示对象里没有整个值
    		obj[arr[i]]=1;
            newArr.push([arr[i]]);
    	}
    }
    return newArr
}
//2.定义一个新数组，并存放原数组的第一个元素，然后将元素组和新数组的元素对比，若不同则存放在新数组中
function arrRemoval(arr) {
    var newArr = [arr[0]];
    for (var i = 1; i < arr.length; i++) {
        var flag = false;
        for (var j = 0; j < newArr.length; j++) {
            if (arr[i] === newArr[j]) {
                flag = true;
                break;
            }
        }
        if (!flag) {
            newArr.push(arr[i]);
        }
    }
    return newArr;
}
//3.利用数组的indexOf下标属性来查询
function arrRemoval(arr) {
    var newArr = [];
    for (var i = 0; i < arr.length; i++) {
        if (newArr.indexOf(arr[i]) == -1) {
            newArr.push(arr[i]);
        }
    }
    return newArr;
}
//4.使用includes(),有返回true，没有返回false
function arrRemoval(arr) {
    var newArr = [];
    for (var i = 0; i < arr.length; i++) {
        if (!newArr.includes(arr[i])) { // 如果newArr新数组包含当前循环item
            newArr.push(arr[i]);
        }
    }
    return newArr;
}
//5.利用ES6的set数据结构，它类似于数组，其成员的值都是唯一的,没有重复的值
function arrRemoval(arr) {
    return Array.from(new Set(arr)); // 利用Array.from将Set结构转换成数组
}
```

#### 19、JavaScript 是一门什么样的语言?

- JS是一款运行在客户端的网页编程语言，js最初是一门为了网页交互而设计的语言，一个完整的Javascript实现由下列三个部分组成，严格来说，js是ECMAScript的实现，是ECMAScript+BOM+DOM组成的一种web开发技术。

- js是一门弱类型语言，其变量类型采用弱类型，并未使用严格的数据类型 （灵活性）
- js是一门解释型脚本语言，在程序运行中被逐行的解释，不像（C/C++/Java）这些语言需要先编译，所以它运行起来非常快
- js是一门动态语言， 它可以直接对用户或客户输入做出响应，无须经过Web服务程序。它对用户的反映响应，是采用以事件驱动的方式进行的。所谓事件驱动，就是指在主页(Home Page)中执行了某种操作所产生的动作，就称为“事件”(Event)。比如按下鼠标、移动窗口、选择菜单等都可以视为事件，当事件发生后，可能会引起相应的事件响应
- JavaScript具有跨平台性，JavaScript依赖于浏览器本身，与操作环境无关，只要设备有浏览器，就可以运行js语言
- 基于对象的语言，js不是面向对象的语言，但是可以模拟面向对象的思想，面向对象有三个特性：封装、继承、多态  ，继承是指类与类之间的关系，JS中没有类的概念，JS中有构造函数的概念，是可以继承的，是基于原型
- JavaScript是一种安全性语言，它不允许访问本地的硬盘，并不能将数据存入到服务器上，不允许对网络文档进行修改和删除，只能通过浏览器实现信息浏览或动态交互，从而有效地防止数据的丢失。

#### 20、undefined与null

> javaScript权威指南： null 和 undefined 都表示“值的空缺”，你可以认为undefined是表示系统级的、出乎意料的或类似错误的值的空缺，而null是表示程序级的、正常的或在意料之中的值的空缺。undefined的类型(typeof)是undefined；null的类型(typeof)是object
>

**undefined**

- 在变量提升（预解析）阶段，只声明未定义，默认值就是undefined
- 在JS的严格模式下（”use strict”），没有明确的主体，this指的就是undefined
- 函数定义没有返回值（return或者return后面什么也不带），默认的返回值就是undefined
- 函数定义形参不传值，默认就是undefined
- 对象没有这个属性名，属性值默认就是undefined
- 在数组的find方法中，没有找到的情况下是undefined

**null**

- 手动设置变量的值或者对象某一个属性值为null（此时不赋值，会在后面的代码中进行赋值，相当于初始化）
- 在JS的DOM元素获取中，如果没有获取到指定的元素对象，结果一般是null
- `Object.prototype.__proto__`的值也是null
- 在正则捕获的时候，如果没有捕获到结果，默认也是null

####  21、冒泡排序和快排

```javascript
 // 冒泡排序（从小到大）
var arr=[40,30,50,10,20];
for(i=0;i<arr.length-1;i++){
    //比较的轮数循环
    for(var j=0;j<arr.length-1-i;j++){
        //比较的次数循环 
       if(arr[j]>arr[j+1]){
           //交换变量
           var temp=arr[j];
           arr[j]=arr[j+1];
           arr[j+1]=temp;
        }
    }
}
//快排：快速排序（Quicksort）是对冒泡排序的一种改进
function quickSort(arr){
    if(arr.length<=1){return arr;}//如果数组<=1,则直接返回
    var pivotIndex=Math.floor(arr.length/2);//找基准，使用向下取整
    var pivot=arr.splice(pivotIndex,1)[0];//原数组删除基准值，得到基准值
    var left=[];//定义左数组
    var right=[];//定义右数组
    for(var i=0;i<arr.length;i++){ //比基准小的放在left，比基准大的放在right
        if(arr[i]<=pivot){
            left.push(arr[i]);
        }
        else{
            right.push(arr[i]);
        }
    }
    //递归
    return quickSort(left).concat([pivot],quickSort(right));
}                
```

#### 22、格式化当前时间

```javascript
function getDate(){
    var dt = new Date(Date.now());
    var year=dt.getFullYear();//获取年
    var month=dt.getMonth();//获取月
    var day=dt.getDate()+1;//获取日
    var hour=dt.getHours();//获取小时
    var minute=dt.getMinutes();//获取分钟
    var second=dt.getSeconds();//获取秒
    //当一些数小于10的时候,前面添加一个0
    month=month<10?"0"+month:month;
    day=day<10?"0"+day:day;
    hour= hour<10?"0"+ hour: hour;
    minute=minute<10?"0"+minute:minute;
    second=second<10?"0"+second:second;
    //返回格式化后的日期和时间
    return year+"年"+month+"月"+day+"日"+hour+":"+minute+":"+second;
}
console.log(getDate());
```

#### 23、字符串相关方法

- replace() 方法用于在字符串中用一些字符替换另一些字符，或替换一个与正则表达式匹配的子串

  ```javascript
  //stringObject.replace(regexp/substr,replacement)
  "服务开发者2018".replace(/\d{4}/g,"2018");
  
  function escapeHtml(str) {
      //[<>”&]:中括号中字符只要其中的一个出现就代表满足条件
      //给 replace 第二个参数传递一个回调函数，参数就是匹配结果，如果匹配不到就是 null
      return str.replace(/[<>”&]/g, function (match) {
          switch (match) {
              case '<':
                  return '&lt;';
              case '>':
                  return '&gt;';
              case '&':
                  return '&amp;';
              case '”':
              return '&quot;';
          }
      });
  }
  ```

- split()(要干掉的字符串,留下的个数)返回一个新的字符串组成的数组

  ```javascript
  var str="JavaScript|HTML|CSS|java|c|python";
  console.log(str.split("|",3));//(3) ["JavaScript", "HTML", "CSS"]
  console.log(str.split("",3));//(3) ["J", "a", "v"]----空则每个切分
  ```

- charCodeAt() 方法可返回指定位置的字符的 Unicode 编码

  ```javascript
  var str="Hello world!"
  document.write(str.charCodeAt(1));//101
  //字符串中第一个字符的下标是 0。
  //如果 index 是负数，或大于等于字符串的长度，则 charCodeAt() 返NaN
  ///汉字的Unicode码大于255bit是两个字节,英文的是一个字节
  ```

- charAt() 方法可返回指定位置的字符,返回字符串

  ```javascript
  var str="Hello world!"
  document.write(str.charAt(1));//e
  //字符串中第一个字符的下标是 0。
  //如果参数 index 不在 0 与 string.length 之间，该方法将返回一个空字符串。
  ```

- substring() 方法返回一个字符串在开始索引到结束索引之间的一个子集

  ```javascript
  var str="JavaScript";
  console.log(str.substrinf(0,4));//Java----不包括最后那个,两个参数都是索引值
  ```
#### 24、url地址对象化

```javascript
function serilizeUrl (url) {
    var search = url.split('?')[1];
    var searchArr = search.split('&');
    var obj = {};
    for (let i = 0; i < searchArr.length; i++) {
        arr = searchArr[i].split('=');
        obj[arr[0]]=arr[1];
    }
    return obj;
}
```

#### 25、正则表达式

- 当使用 RegExp()构造函数的时候，不仅需要转义引号（即\”表示”），并且还需要双反斜杠（即\\表示一个\）。使用正则表达字面量的效率更高

  ```js
  //1.创建正则表达式对象:通过构造函数的方式
  //var reg=new RegExp("\d{5}");----这种写法错误
  //var reg=new RegExp("\\d{5}");----正确,也可以下面这样写
  var reg=new RegExp(/\d{5}/);
  var str="我的手机号码是:10010"
  var flag=reg.test(str);
  console.log(flag);//true-----有则为真
  
  //2.创建正则表达式对象:字面量的方式
  var reg=/\d{1,5}/;
  var flag=reg.test("我的手机号码是:10086");
  console.log(flag);//true
  ```

- 正则表达式相关方法

  ```js
  //1.match()方法----字符串的方法.既可以传入字符串,也可以传入正则,返回的是数组
  var str1="中国移动:10086,中国联通10010,中国电信:10000";
  var arr1=str1.match(/\d{5}/g);//g表示全局
  console.log(arr1);//["10086", "10010", "10000"]
  
  //2.如何提取组
  var str2="2018-5-27";
  var arr2=str2.match(/(\d{4})[-](\d{1})[-](\d{2})/g);
  console.log(arr2);//["2018-5-27"]
  console.log(RegExp.$1);//2018
  console.log(RegExp.$2);//5
  console.log(RegExp.$3);//27
  
  //3.replace()方法------字符串的方法
  var str3="源于开发者2017，服务开发者2017";
  var arr3=str3.replace(/\d{4}/g,"2018");
  console.log(arr3);//源于开发者2018，服务开发者2018
  var str4="ahdfHgFhgHHgh";
  var arr4=str4.replace(/h/gi,"Z");//i表示忽略字母大小写
  console.log(arr4);//aZdfZgFZgZZgZ
  
  //4.exec()方法-----正则表达式调用的方法,不是字符串
  //如果匹配成功，exec() 方法返回一个数组，并更新正则表达式对象的属性。
  //返回的数组将完全匹配成功的文本作为第一项，将正则括号里匹配成功的作为数组填充到后面。
  //如果匹配失败，exec() 方法返回 null。
  var str5="中国移动:10086,中国联通10010,中国电信:10000";
  var reg=/\d{5}/g;
  var arr5= reg.exec(str5);
  console.log(arr5);//["10086", index: 5, input: "中国移动:10086,中国联通10010,中国电信:10000", groups: undefined]
  ```

- 邮箱的正则

  ```js
  var regMail = /^([a-zA-Z0-9_-])+@([a-zA-Z0-9_-])+((.[a-zA-Z0-9_-]{2,3}){1,2})$/;
  ```

#### 26、 callee 和 caller 的作用？

caller 是返回一个对函数的引用，该函数调用了当前函数；

```javascript
//f3函数在f4函数中调用的,此时调用者是f4
function f3(){
    console.log(f3.caller);
}
function f4(){
    f3();
}
f4();
```

callee 是返回正在被执行的 function 函数，也就是所指定的 function 对象的正文。

arguments.callee：获得当前函数的引用

```javascript
function fn () {
return arguments.callee;
}
console.log(fn());
//返回函数自身，arguments.callee相当于fn
//也就是说arguments.callee()相当于fn()
```

#### 27、创建函数的方式

```javascript
//第一种（函数声明）：
function sum1(num1,num2){
	return num1+num2;
}
//第二种（函数表达式）：
var sum2 = function(num1,num2){
	return num1+num2;
}
//第三种（函数对象方式）：
var sum3 = new Function("num1","num2","return num1+num2");
```

#### 28、创建对象的方法

- 调用系统的构造函数创建对象

  ```javascript
  var obj=new Object();//关键词Object,大写首字母
  obj.name="小明";
  obj.age=20;
  obj.sex="男";
  obj.play=function(){
      console.log("我在玩游戏");
  };
  obj.showName=function(){
      console.log("我叫"+this.name)
  }
  console.log(obj.name);//小明
  console.log(obj.age);//20
  console.log(obj.sex);//男
  obj.play();//我在玩游戏
  obj.showName();//我叫小明
  ```

- 工厂模式:一次性创建多个对象——工厂模式创建对象：利用函数封装起来，后面调用

  - 原始版本

    ```javascript
    function creatObj(){
        var obj= new Object();
        obj.name="关羽";
        obj.age=30;
        obj.showName=function(){
            console.log("我叫"+this.name);
        };
        obj.showAge=function(){
            console.log("我今年"+this.age);
        };
        return obj;
    }
    var obj1=creatObj();
    var obj2=creatObj();
    obj1.showName();//我叫关羽
    obj1.showAge();//我今年30
    obj2.showName();//我叫关羽
    obj2.showAge();//我今年30
    ```

  - 改进版本

    ```javascript
    function creatObj(name,age){
        var obj= new Object();
        obj.name=name;
        obj.age=age;
        obj.showName=function(){
            console.log("我叫"+this.name);
        };
        obj.showAge=function(){
            console.log("我今年"+this.age);
        };
        return obj;
    }
    var obj1= new creatObj("刘备",32);
    var obj2= new creatObj("关羽",30);
    obj1.showName();//我叫刘备
    obj1.showAge();//我今年32
    obj2.showName();//我叫关羽
    obj2.showAge();//我今年30
    ```

  - 最终版本

    ```javascript
    function creatObj(name,age){
        var obj= new Object();
        obj.name=name;
        obj.age=age;
        obj.showName=showName;
        obj.showAge=showAge;
        return obj;
    }
    showName=function(){
            console.log("我叫"+this.name);
        };
    showAge=function(){
            console.log("我今年"+this.age);
        };
    var obj1=new creatObj("刘备",32);
    var obj2=new creatObj("关羽",30);
    obj1.showName();//我叫刘备
    obj1.showAge();//我今年32
    obj2.showName();//我叫关羽
    obj2.showAge();//我今年30
    ```

- 自定义构造函数创建对象(结合第一种和需求,通过工厂模式创建)

    ```javascript
    function Person(name,age){
        this.name=name;
        this.age=age;
        this.showName=function(){
            console.log("我叫"+this.name);
        };
        this.showAge=function(){
            console.log("我今年"+this.age);
        };
     };
     var obj1=new Person("刘备","32");
     var obj2=new Person("关羽","30");
     obj1.showName();//我叫刘备
     obj1.showAge();//我今年32
     obj2.showName();//我叫关羽
     obj2.showAge();//我今年30
    
    /*自定义构造函数创建对象做了四件事：
    1.在内存中开辟（申请）空间，存储新的对象
    2.把this设置新的对象
    3.设置对象的属性和方法的值
    4.把this这个对象返回*/
    ```

- 字面量创建对象

    ```javascript
    var obj={
       name:"刘备",
       age:32,
       height:"180cm"
    }
    console.log(obj.name);//刘备
    console.log(obj.age);//32
    console.log(obj.height);//180cm
    console.log(obj instanceof Object);//true
    ```

#### 29、Script标签位置

- 将script放在`<head>`里

  > 浏览器解析HTML，发现script标签时，会先下载完所有这些script文件，再往下解析其他的HTML。但是浏览器在下载JS时，是不能多个JS并发一起下载的，不管JS是不来来自同一个host，浏览器最多只能同时下载两个JS，且浏览器下载JS时，就block掉解析其他HTML的工作。将script放在头部，会让网页内容呈现滞后，导致用户感觉到卡。

- 如果说放在 `</body>` 之前，将会阻塞其他资源的加载；如果放在 `</body>`封闭之后，不会影响 body 内元素的加载，但是这已经不符合h5的规范

  > 将script放在尾部的缺点，是浏览器只能先解析完整个HTML页面，再下载JS。而对于一些高度依赖于JS的网页，就会显得慢了

- 使用`async`和`defer`

  ```html
  <script type="text/javascript" src="path/to/script1.js" async></script>
  <script type="text/javascript" src="path/to/script2.js" async></script>
  ```

  > 80%的现代浏览器都认识async和defer属性，这两个属性能让浏览器做到一边下载JS(还是只能同时下载两个JS)，一边解析HTML。他的优点不是增加JS的并发下载数量，而是做到下载时不block解析HTML。带async属性的script会异步执行，只要下载完就执行，这会导致script2.js可能先于script1.js执行（如果script2.js比较大，下载慢）。defer就能保证script有序执行，script1.js先执行，script2.js后执行。如果可以不考虑支持<IE9的IE，最好的做法是将script标签放在head中，并使用async/defer属性。这样浏览器就能一边下载JS，一边解析其他的HTML。

#### 30、js 延迟加载的方式有哪些？

- 方案一：`<script>`标签的async='async'属性

  > - 用于改变处理脚本的行为。同样，只适用于外部脚本文件。不让页面等待脚本下载和执行，从而异步加载页面其他内容。异步脚本一定会在页面 load 事件前执行。 不能保证脚本会按顺序执行
  > - async和defer一样，都不会阻塞其他资源下载，所以不会影响页面的加载。 缺点：不能控制加载的顺序

  ```html
   <!DOCTYPE html>
  <html>
  <head>
      <script src="test1.js" async></script>
      <script src="test2.js" async></script>
  </head>
  <body>
  <!-- 这里放内容 -->
  </body>
  </html>  
  ```

- 方案二：`<script>`标签的的defer="defer"属性

  > - 用途：表明脚本在执行时不会影响页面的构造。也就是说，脚本会被延迟到整个页面都解析完毕之后再执行。在`<script>` 元素中设置 `defer` 属性，等于告诉浏览器立即下载，但延迟执行
  > - 虽然`<script>` 元素放在了`<head>`元素中，但包含的脚本将延迟浏览器遇到`</html>`标签后再执行。`HTML5`规范要求脚本按照它们出现的先后顺序执行。在现实当中，延迟脚本并不一定会按照顺序执行。`defer`属性只适用于外部脚本文件。支持 HTML5 的实现会忽略嵌入脚本设置的 `defer`属性

  ```html
  <!DOCTYPE html>
  <html>
  <head>
      <script src="test1.js" defer="defer"></script>
      <script src="test2.js" defer="defer"></script>
  </head>
  <body>
  <!-- 这里放内容 -->
  </body>
  </html> 
  ```

- 方案三：动态创建 DOM 方式（创建 script，插入到 DOM 中，加载完毕后 callback）

  ```js
  //这些代码应被放置在</body>标签前(接近HTML文件底部)
  <script type="text/javascript">  
     function downloadJSAtOnload() {  
         varelement = document.createElement("script");  
         element.src = "defer.js";  
         document.body.appendChild(element);  
     }  
     if (window.addEventListener){  
        window.addEventListener("load",downloadJSAtOnload, false);  
     }else if (window.attachEvent){  
        window.attachEvent("onload",downloadJSAtOnload;  
     }else{ 
        window.onload =downloadJSAtOnload;
     }
  </script>
  ```

- 方案四：使用jQuery的getScript()方法

  ```js
  $.getScript("outer.js",function(){//回调函数，成功获取文件后执行的函数  
        console.log("脚本加载完成")  
  });
  ```

- 方案五：使用`setTimeout`延迟方法

  ```html
  <script type="text/javascript" >
      function A(){
          $.post("/lord/login",{name:username,pwd:password},function(){
              alert("Hello");
          });
      }
      $(function (){
          setTimeout('A()', 1000); //延迟1秒
      })
  </script>
  ```

- 方案六：让JS最后加载。

  > 例如引入外部js脚本文件时，如果放入html的head中,则页面加载前该js脚本就会被加载入页面，而放入body中，则会按照页面从上倒下的加载顺序来运行javascript的代码， 所以我们可以把js外部引入的文件放到页面底部，来让js最后引入，从而加快页面加载速度

#### 31、内存泄漏问题
定义：内存泄漏指一块被分配的内存既不能使用，又不能回收，直到浏览器进程结束。内存泄露会导致一系列问题，比如：运行缓慢，崩溃，高延迟。

垃圾回收机制：垃圾回收器定期扫描对象，并计算引用了每个对象的其他对象的数量。如果一个对象的引用数量为 0（没有其他对象引用过该对象），或对该对象的唯一引用是循环的，那么该对象的内存即可回收。

```javascript
//一般了解
var a = "before";
var b = "override a";
var a = b; //重写a

//现代浏览器采用的是标记清除
function test(){
 var a = 10 ; //被标记 ，进入环境 
 var b = 20 ; //被标记 ，进入环境
}
test(); //执行完毕 之后 a、b又被标离开环境，被回收。

//老浏览器(IE9以下)采用的是引用计数
function test(){
 var a = {} ; //a的引用次数为0 
 var b = a ; //a的引用次数加1，为1 
 var c =a; //a的引用次数再加1，为2
 var b ={}; //a的引用次数减1，为1
}
//test执行完后，全部变量会自动定义为undefined
//c = undefined后a的引用次数也变为0了
```

造成内存泄漏的操作：

- setTimeout 的第一个参数使用字符串而非函数的话，会引发内存泄漏；

  ```javascript
  function display(obj){
      obj.style.display='none';
      window.setTimeout("obj.style.display='inline'", 5000);
  }
  //当setTimeout第一个参数为字符串代码时，执行这段代码会报obj未定义，
  //原因是因为setTimeout方法是window的方法，是个全局方法。执行这个方法的代码的作用域环境是window
  //解决：把obj声明成全局变量；第一个参数写成function，这样形成一个闭包来访问局部变量
  ```

- 被遗忘的定时器或者回调

  ```javascript
  var someResouce=getData();
  setInterval(function(){
      var node=document.getElementById('Node');
      if(node){
          node.innerHTML=JSON.stringify(someResouce)
      }
  },1000)
  ```

- 闭包

  ```javascript
  function bindEvent(){
    var obj=document.createElement("XXX");
    obj.onclick=function(){
      //Even if it's a empty function
    }
  }
  ```

- 没有清理的DOM元素引用

  ```javascript
  var elements={
      button: document.getElementById("button"),
      image: document.getElementById("image"),
      text: document.getElementById("text")
  };
  function doStuff(){
      image.src="http://some.url/image";
      button.click():
      console.log(text.innerHTML)
  }
  function removeButton(){
      document.body.removeChild(document.getElementById('button'))
  }
  ```

- 循环（在两个对象彼此引用且彼此保留时，就会产生一个循环）

  ```javascript
  function fn1(){
      obj_a = obj_b;
      obj_b.attr = obj_a;
  function fn2(){
      obj_c = {};
      obj_c.attr = obj_c;
  }
  //IE中产生了内存泄露，由于IE的内存回收机制，导至会长期占用内存而不能释放
  ```

- 意外的全局变量引起的内存泄露

  ```javascript
  function foo(arg) {
      bar = "this is a hidden global variable";
  }
   
  // 上面的函数等价于
  function foo(arg) {
      window.bar = "this is an explicit global variable";
  }
  ```

如何避免：

- 减少不必要的全局变量，或者生命周期较长的对象，及时对无用的数据进行垃圾回收
- 注意程序逻辑，避免“死循环”之类的
- 避免创建过多的对象  原则：不用了的东西要及时归还

#### 32、获取非行间样式的函数

```javascript
//获取行间样式或设置样式
function css(obj,sty,val) {    
//obj：元素节点、sty：样式属性、val：属性值
    if(arguments.length == 2) {   
        return obj.style[sty];//传两个值，获取
    } else if(arguments.length == 3) {
        return obj.style[sty] = val;//传三个值，设置
    }
}
//获取非行间样式
function getsStyle(obj,sty){
    if(obj.currentStyle){
        return obj.currentStyle[sty]; //IE下兼容
    }else{
        return getComputedStyle(obj,null)[sty];   //非IE下兼容
    }
}
```

#### 33、BOM常用对象

- window 

  ```js
  alert() confirm() prompt() //系统对话框
  open() close() //打开关闭
  setInterval()  setTimeout() clearInterval() clearTimeout()//定时器
  widow.onload //页面加载完成后才触发执行
  window.onunload //页面关闭后触发事件
  window.onbeforeunload //页面关闭之前触发事件
  ```

- location 

  ```js
  window.location.hash //#及后面的内容
  window.location.host //主机及端口号
  window.location.hostname //主机名
  window.location.pathname //文件路径(相对路径)
  window.location.port //端口号
  window.location.protocl //协议(比如http)
  window.location.search //查询部分，参数部分，？后面的
  window.location.href="网址" //跳转页面
  window.location.assign("网址") //跳转页面(同上)
  window.location.replace("网址") //跳转页面,没有历史记录
  window.location.reload() ；//可以刷新当前页面
  ```

- history 

  ```js
  window.history.forward()//向前跳转
  window.history.go()//-向前跳转,等同于上面
  window.history.back()//向后跳转
  //注意,这几个方法都必须产生了历史记录才可以向前或向后跳转网页
  ```

- navigator

  ```js
  navigator.platform//获取系统类型
  navigator.userAgent//获取浏览器类型,可以检测浏览器版本有
  ```


#### 34、遍历DOM树

```javascript
//获取页面中的根节点---根标签
var root=document.documentElement;//html
//根据根节点,调用fn的函数,显示的是根节点的名字
function forDOM(root1){
    //调用f1,显示的是节点的名字
    f1(root1);
    //获取根节点所有的子节点
    var children=root1.children;
    //调用遍历所有子节点的函数
    forChildren(children);
}
//给我子节点,把子节点的所有子节点显示出来
function forChildren(children){
    //遍历所有的子节点
    for(var i=0;i<children.length;i++){
        //每个子节点
        var child=children[i];
        //显示每个子节点的名字
        f1(child);
        //判断child下面有没有子节点,如果有子节点,那么就继续遍历
        child.children&&forDOM(child);
    }
}
function f1(root){
    console.log("节点名字:======"+root.nodeName);
}
forDOM(root);
```

#### 35、伪数组

伪数组（类数组）：无法直接调用数组方法或期望 length 属性有什么特殊的行为，但仍可以对真正数组遍历方法来遍历它们。

```js
var trueArr=[1,2,3,4,5];
var flaseArr={
    0:1,
    1:2,
    2:3,
    3:4,
    4:5,
    length:5
}
//长度是否可变
trueArr[5]=6;
flaseArr[5]=6;
console.log(trueArr.length);//6
console.log(flaseArr.length);//5
//是否可以使用方法
console.log(trueArr.push(6));//7----push方法返回长度
console.log(false.push(6));//报错
```

典型的是函数的 argument 参数，还有像调用getElementsByTagName,document.childNodes 之类的,它们都返回 NodeList 对象都属于伪数组。

可以使用 Array.prototype.slice.call(fakeArray)将数组转化为真正的 Array 对象。

#### 36、原生js实现拖拽

给需要拖拽的节点绑定 mousedown, mousemove, mouseup 事件

mousedown 事件触发后，开始拖拽

mousemove 时，需要通过 event.clientX 和 clientY 获取拖拽位置，并实时更新位置

mouseup 时，拖拽结束

需要注意浏览器边界的情况

```html
<html>
<head>
    <meta charset="utf-8" />
    <title></title>
    <style>*{margin: 0;padding: 0;}</style>
</head>
<body>
<div id="demo" style="position:absolute;width: 100px;height: 100px;background: #ccc;border:solid 1px #ccc;">按住左键拖动</div>
</body>
<script>
    window.onload = function() {
        //用于确定是否是拖拽的对象
        var drag;
        //鼠标位于目标元素上的时候距离目标元素的位置
        var x,y;
        //取得元素
        var ele = document.getElementById('demo');
 
        //鼠标按下去
        ele.onmousedown = function(evt) {
            //取得事件对象
            _event = evt || window.event;
            //设置drag元素
            target = _event.target || _event.srcElement;
            x = _event.clientX - target.offsetLeft;
            y = _event.clientY - target.offsetTop;
            drag = target;
        }
 
        //鼠标移动
        document.onmousemove = function(evt) {
            //确定鼠标是在目标元素上按下去后才开始移动
            if(drag) {
                _event = evt || window.event;
 
                //设置边界
                var left = _event.clientX - x;
                var top = _event.clientY - y;
                body = document.documentElement || document.body;
                if (left < 0) left = 0;
                if (left > body.offsetWidth - drag.offsetWidth) left = body.offsetWidth - drag.offsetWidth;
                if (top < 0) top = 0;
                if (top > (body.offsetHeight - drag.offsetHeight)) top = (body.offsetHeight - drag.offsetHeight);
 
                //设置样式
                drag.style.cursor = 'move';
                drag.style.border = 'dashed 1px red';
                drag.style.left = left + 'px';
                drag.style.top = top + 'px';
            }
        }
 
        //松开鼠标
        document.onmouseup = function(evt) {
            if(drag) {
                //卸载样式
                drag.style.cursor = '';
                drag.style.border = 'dashed 1px #ccc';
            }
            drag = null;
        }
 
    }
</script>
</html>
```

#### 37、严格模式`use strict`

>  use strict是一种ECMAscript 5 添加的（严格）运行模式,这种模式使得 Javascript 在更严格的条件下运行,提高编译器效率，增加运行速度； 为未来新版本的Javascript标准化做铺垫

禁止 this 关键字指向全局对象

禁止使用 with 语句

全局变量显式声明

严格模式下无法删除变量。只有 configurable 设置为 true 的对象属性，才能被删除

严格模式下，对一个对象的只读属性进行赋值将报错

严格模式下，对一个使用 getter 方法读取的属性进行赋值，会报错。

严格模式下，对禁止扩展的对象添加新属性，会报错。

严格模式下，删除一个不可删除的属性，会报错。

严格模式下，对象有多个重名属性，这属于语法错误

严格模式下，如果函数有多个重名的参数，这属于语法错误。

严格模式禁止整数的第一位如果是 0，表示这是八进制数这种表示法，整数第一位为 0，将报错

不允许对 arguments 赋值，arguments 不再追踪参数的变化，禁止使用 arguments.callee

严格模式只允许在全局作用域或函数作用域的顶层声明函数。也就是说，不允许在非函数的
代码块内声明函数

严格模式新增了一些保留字：implements, interface, let, package, private, protected, public, static, yield

#### 38、Object 对象的常用方法

Object.hasOwnProperty( ) 检查属性是否被继承
Object.isPrototypeOf( ) 一个对象是否是另一个对象的原型
Object.propertyIsEnumerable( ) 是否可以通过 for/in 循环看到属性
Object.toLocaleString( ) 返回对象的本地字符串表示
Object.toString( ) 定义一个对象的字符串表示
Object.valueOf( ) 指定对象的原始值

#### 39、原型和原型链

- 原型：
  - `prototype`是构造器的一个属性。在JS中，每一个对象的构造器都有一个`prototype`属性。`prototype`在JS中用于原型继承，可以使构造器构造出来的多个对象可以共享原型的对象。其实无论使我们自己自定义的构造器还是原生的构造器都有`prototype`属性。
  - 实例对象中有个属性，`__proto__`，也是对象，叫原型，不是标准的属性，在IE8中可能不支持，主要给是给浏览器使用的，构造函数中有个属性，prototype，也是对象，叫原型，是标准属性，主要给程序开发人员使用，所以原型就是`__proto__`或者prototype，都是原型对象
- 原型链
  - 原型链是由一些用来继承和共享属性的对象组成的（有限的）对象链。每个继承父函数的子函数的对象都包含一个内部属性`__proto__`。该属性包含一个指针，指向父函数的prototype。若父函数的原型对象的`__proto__`属性为再上一层函数。在此过程中就形成了原型链。
  - 原型链实现了继承。原型链存在两个问题：
    - 包含引用类型值的原型属性会被所有实例共享
    - 在创建子类型时，无法向超类型的构造函数中传递参数
  - 如何判断属性来自自身对象还是原型链：hasOwnPrototype
- 特点：
  - JavaScript对象是通过引用来传递的，我们创建的每个新对象实体中并没有一份属于自己的原型副本。当修改原型时，与之相关的对象也会继承这一改变。
  - 当我们需要一个属性的时，Javascript引擎会先看当前对象中是否有这个属性， 如果没有的话，就会查找他的Prototype对象是否有这个属性，如此递推下去，一直检索到 Object 内建对象。

#### 40、自定义事件实现

原生提供了3个方法实现自定义事件:

- **Event()** 构造函数, 创建一个新的事件对象 `Event`

  > ```js
  > var selfEvent = new Event('self',{
  >       "bubbles" : true,//Boolean类型，默认值为 false，表示该事件是否冒泡
  >       "cancelable" : false,//Boolean类型，默认值为 false， 表示该事件能否被取消
  >       "composed" : false//Boolean类型，默认值为 false，指示事件是否会在阴影根之外
  > });
  > ```

- **CustomEvent()**  创建一个自定义事件

- **document.createEvent()** `创建一个新的事件（Event），随之必须调用自身的 init 方法进行初始化。`

模拟鼠标事件:

```js
var btn = document.getElementsByTagNames("button")[0];
var event = document.createEvent("MouseEvents");
event.initMouseEvent("click", true, true, document.defaultView, 0, 0, 0, 0, 0, false, false, false, 0, null);
btn.dispatchEvent(event);
```

模拟键盘事件：

```js
var text = document.getElementsByTagNames("input")[0];
if (document.implementation.hasFeature("KeyboardEvents", 3.0) {
	var event = document.createEvent("KeyboardEvent");
	event.initKeyboardEvent("keydown", true, true, document.defaultView, "a", 0, "Shift", 0);
}
text.dispatchEvent(event);

```

IE中的事件模拟(模拟click事件):

```js
var btn = document.getElementsByTagNames("button")[0];
var event = document.createEventObject();
event.screenX = 100;
event.screenY = 0;
event.clientX = 0;
event.clientY = 0;
event.strlKey = false;
event.altKey = false;
event.shiftKey = false;
Event.button = 0;
btn.fireEvent("onclick", event);
```

#### 41、浅拷贝和深拷贝

- 深拷贝和浅拷贝是只针对Object和Array这样的复杂类型的

- 浅拷贝：

  - 指的是拷贝一个对象时，仅仅拷贝对象的引用进行拷贝，但是拷贝对象和源对象还是引用同一份实体。此时，其中一个对象的改变都会影响到另一个对象。

    ```js
    var obj1={
        age:24,
        sex:"男",
        name:"Eric"
    }
    var obj2={};
    //定义一个函数,把a对象中的所有属性复制到对象b中
    function extend(a,b){
        for(var key in a){
            b[key]=a[key];
        }
    }
    extend(obj1,obj2);
    console.log(obj2.name);//Eric
    console.log(obj2.sex);//男
    console.log(obj2.age);//24
    ```

  - Object.assign() 方法用于将所有可枚举的属性的值从一个或多个源对象复制到目标对象。它将返回目标对象。

    ```js
    //Object.assign进行的拷贝是浅拷贝。
    //也就是说，如果拷贝过来的属性的值是对象等复合属性，那么只能拷贝过来一个引用
    const obj1 = {a: {b: 1}};
    const obj2 = Object.assign({}, obj1);
    console.log(a.b);//1
    obj1.a.b = 2;
    obj2.a.b // 2
    ```

- 深拷贝

  - 对于一个引用类型，如果直接将它赋值给另一个变量，由于这两个引用指向同一个地址，这时改变其中任何一个引用，另一个都会受到影响。这时就引出了深拷贝。

  - 实现深拷贝可以使用递归递归去复制所有层级属性

    ```js
    var obj1={
        age:25,
        sex:"男",
        car:["奥迪","特斯拉","五菱"],
        dog:{
            name:"小白",
            age:6,
            color:"黄色"
        }
    };
    var obj2={};
    //通过函数,把对象a中的所有数据拷贝到对象b中
    function extend(a,b){
        for(var key in a){
            //先获取a对象中每个属性的值
            var item=a[key];
            //判断这个值是不是数组
            if(item instanceof Array){
                //如果是数组,在对象b中添加一个新的属性,并且这个属性值也是数组
                b[key]=[];
                //调用这个方法,把a对象的这个数组的属性值一个一个的复制到b对象这个数组属性中
                extend(item,b[key]);
            }else if(item instanceof Object){//判断这个值是不是对象类型的
                //如果是对象类型的,那么在b对象中添加一个属性,也是对象
                b[key]={};
                //调用这个方法,把a对象中的属性对象的值.一个一个的复制到b对象的这个属性对象中
                extend(item,b[key]);
            }else{
                //如果是普通的数据,直接复制到b对象这个属性中
                b[key]=item;
            }
        }
    }
    extend(obj1,obj2);
    ```

  - 深拷贝对象还有另一个解决方法，在对象中不含有函数的时候(但是函数不能被正确处理)，使用JSON解析反解析(JSON.parse()和JSON.stringify())就可以得到一个深拷贝对象

    ```js
    function deepClone(obj){
        let _obj = JSON.stringify(obj),
            objClone = JSON.parse(_obj);
        return objClone
    }    
    let a=[0,1,[2,3],4],
        b=deepClone(a);
    a[0]=1;
    a[2][0]=1;
    console.log(a,b);
    ```

  - 除了上面两种方法之外，我们还可以借用JQ的extend方法。

    ```js
    /**
    *$.extend( [deep ], target, object1 [, objectN ] )
    *deep表示是否深拷贝，为true为深拷贝，为false，则为浅拷贝
    *target Object类型 目标对象，其他对象的成员属性将被附加到该对象上。
    *object1  objectN可选。 Object类型 第一个以及第N个被合并的对象。
    */
    let a=[0,1,[2,3],4],
        b=$.extend(true,[],a);
    a[0]=1;
    a[2][0]=1;
    console.log(a,b);
    ```

#### 42、请用js去除字符串空格？

方法一：使用replace正则匹配的方法` str.replace(/\s*/g,"") `

```js
var str = " 6 6 ";
var str_1 = str.replace(/\s*/g,"");//去除字符串内所有的空格
console.log(str_1); //66
var str = " 6 6 ";
var str_1 = str.replace(/^\s*|\s*$/g,"");//去除字符串内两头的空格
console.log(str_1); //6 6
var str = " 6 6 ";
var str_1 = str.replace(/^\s*/,"");//去除字符串内左侧的空格
console.log(str_1); //6 6 
var str = " 6 6 ";
var str_1 = str.replace(/(\s*$)/g,"");//去除字符串内右侧的空格
console.log(str_1); // 6 6
```

方法二：使用str.trim()方法,无法去除中间的空格`str.trim()`

```js
//使用自带方法，str.trim(),考虑兼容性
if(!String.prototype.trim){
    String.prototype.trim = function () { 
        //\s 匹配空白字符：回车、换行、制表符 tab 空格
        return this.replace('/\s+/','').replace(/\s+$/,'');
    }
}
var str = " \t\n test string ".trim();
console.log(str == 'test string');//true
```

方法三：使用jquery,$.trim(str)方法,无法去除中间的空格`$.trim(str)`

```js
var str = " 6 6 ";
var str_1 = $.trim(str);
console.log(str_1); //6 6//输出左右侧均无空格
```

#### 43、DOM元素e的e.getAttribute(propName)和e.propName有什么区别和联系？

- e.getAttribute()，是标准DOM操作文档元素属性的方法，具有通用性可在任意文档上使用，返回元素在源文件中**设置的属性**
- e.propName通常是在HTML文档中访问特定元素的**特性**，浏览器解析元素后生成对应对象（如a标签生成HTMLAnchorElement），这些对象的特性会根据特定规则结合属性设置得到，对于没有对应特性的属性，只能使用getAttribute进行访问
- e.getAttribute()返回值是源文件中设置的值，类型是字符串或者null（有的实现返回""）
- e.propName返回值可能是字符串、布尔值、对象、undefined等
- 大部分attribute与property是一一对应关系，修改其中一个会影响另一个，如id，title等属性
- 一些布尔属性`<input hidden/>`的检测设置需要hasAttribute和removeAttribute来完成，或者设置对应property
- 像`<a href="../index.html">link</a>`中href属性，转换成property的时候需要通过转换得到完整URL
- 一些attribute和property不是一一对应如：form控件中`<input value="hello"/>`对应的是defaultValue，修改或设置value property修改的是控件当前值，setAttribute修改value属性不会改变value property

#### 44、offset/client/scrollWidth三大系列属性的区别

- offsetWidth/offsetHeight返回值包含**content + padding + border**，效果与e.getBoundingClientRect()相同

  ```html
  <div id="dv"></div>
  <!-- 已在style标签里设置div宽高各100px -->
  <script>
      //在style标签里面的样式属性无法获取,但是在style属性中设置的样式可以获取
      console.log(document.getElementById("dv").style.width);//为空---无法获取
  
      //所以引出了offset系列,总共有四个属性如下:
      //1.可以通过offsetWidth获取元素的宽（带边框）
      console.log(document.getElementById("dv").offsetWidth);//100
  
      //2.可以通过offsetHeight获取元素的高（带边框）
      console.log(document.getElementById("dv").offsetHeight);//100
  
      //3.可以通过offsetLeft获取元素距离左边的值
      //注意:
      //没有脱离文档流,值=父级元素的margin和padding和border+自己的margin
      //脱离文档流,值=自己的left+自己的margin
      console.log(document.getElementById("dv").offsetLeft);//8---没有清除边距
  
      //4.可以通过offsetLeft获取元素距离上边的值
      console.log(document.getElementById("dv").offsetTop);//8---没有清除边距
      //注意:
      //没有脱离文档流,值=父级元素的margin和padding和border+自己的margin
      //脱离文档流,值=自己的left+自己的margin
  </script>
  ```

- clientWidth/clientHeight返回值只包含**content + padding**，如果有滚动条，也**不包含滚动条**

  ```html
  <div id="dv">设置了宽高各500px,10px边框</div>
  <script>
      //clientWidth:获取可视区域的宽(没有边框)
      console.log(document.getElementById("dv").clientWidth);//500
      //clientHeight:获取可视区域的高(没有边框)
      console.log(document.getElementById("dv").clientHeight);//500
      //clientLeft:获取左边边框的宽度
      console.log(document.getElementById("dv").clientLeft);//10
      //clientTop:获取上边边框的宽度
      console.log(document.getElementById("dv").clientTop);//10
  </script>
  ```

- scrollWidth/scrollHeight返回值包含**content + padding + 溢出内容的尺寸**

  ```html
  <div id="dv"></div>
  <!-- 已在style标签里设置div宽高各100px -->
  <script>
      //scrollWidth:获取元素实际内容的宽(不带边框),如果元素里面没有内容,就是元素的宽
      console.log(document.getElementById("dv").scrollWidth);//100
      //scrollHeight:获取元素中内容的实际高度(不带边框),
      //如果元素里面没有内容或者内容高度没有超过元素的高就是元素的高,超过以后就是内容的高度
      console.log(document.getElementById("dv").scrollHeight);//100
      //scrollTop:获取向上卷曲的距离-----当出现滚动条时
      console.log(document.getElementById("dv").scrollTop);//0
      //scrollLeft:获取向上卷曲的距离------当出现滚动条时
      console.log(document.getElementById("dv").scrollLeft);//0
  </script>
  ```

#### 45、focus/blur与focusin/focusout的区别与联系

- focus/blur不冒泡，focusin/focusout冒泡
- focus/blur兼容性好，focusin/focusout在除FireFox外的浏览器下都保持良好兼容性，如需使用事件托管，可考虑在FireFox下使用事件捕获elem.addEventListener('focus', handler, true)
- 可获得焦点的元素：
  - window
  - 链接被点击或键盘操作
  - 表单空间被点击或键盘操作
  - 设置`tabindex`属性的元素被点击或键盘操作

#### 46、mouseover/mouseout与mouseenter/mouseleave的区别与联系

- mouseover/mouseout是标准事件，**所有浏览器都支持**；mouseenter/mouseleave是IE5.5引入的特有事件后来被DOM3标准采纳，现代标准浏览器也支持

- mouseover/mouseout是**冒泡**事件；mouseenter/mouseleave**不冒泡**。需要为**多个元素监听鼠标移入/出事件时，推荐mouseover/mouseout托管，提高性能**

- 标准事件模型中event.target表示发生移入/出的元素,**event.relatedTarget**对应移出/如元素；在老IE中event.srcElement表示发生移入/出的元素，**event.toElement**表示移出的目标元素，**event.fromElement**表示移入时的来源元素

- mouseover事件：不论鼠标指针穿过被选元素或其子元素，都会触发 mouseover 事件。

  mouseenter事件：只有在鼠标指针穿过被选元素时，才会触发 mouseenter 事件

#### 47、函数内部arguments

- arguments所有函数中都包含的一个局部变量，是一个类数组对象，对应函数调用时的实参。如果函数定义同名参数会在调用时覆盖默认对象
- arguments[index]分别对应函数调用时的实参，并且通过arguments修改实参时会同时修改实参
- arguments.length为实参的个数（Function.length表示形参长度）
- arguments.callee为当前正在执行的函数本身，使用这个属性进行递归调用时需注意this的变化
- arguments.caller为调用当前函数的函数（已被遗弃）
- 转换为数组：`var args = Array.prototype.slice.call(arguments, 0);`

#### 48、函数节流和防抖

都为解决高频事件而来， scroll mousewhell mousemover touchmove onresize。比如在监听浏览器滚动条的scroll事件时该事件会触发很多次，这样当快速滚动时会有很差的性能，所以要限制事件触发的频率，可以防抖和节流。

防抖：让在用户动作停止后延迟x ms再执行回调。短时间内多次触发同一个事件，只执行最后一次，或者在开始时执行，中间不执行。比如公交车上车，要等待最后一个乘客上车

```js
// 函数防抖
var timer = false;
document.getElementById("debounce").onscroll = function(){
    clearTimeout(timer); // 清除未执行的代码，重置回初始化状态

    timer = setTimeout(function(){
        console.log("函数防抖");
    }, 300);
};  
```

节流：在用户动作时没隔一定时间（如200ms）执行一次回调。节流是连续触发事件的过程中以一定时间间隔执行函数。节流会稀释你的执行频率，比如每间隔1秒钟，只会执行一次函数，无论这1秒钟内触发了多少次事件

```js
var canRun = true;
document.getElementById("throttle").onscroll = function(){
    if(!canRun){
        // 判断是否已空闲，如果在执行中，则直接return
        return;
    }

    canRun = false;
    setTimeout(function(){
        console.log("函数节流");
        canRun = true;
    }, 300);
};
```

#### 49、如何实现数组的随机排序？

```js
//方法一：
  	var arr = [1,2,3,4,5,6,7,8,9,10];
  	function randSort1(arr){
  		for(var i = 0,len = arr.length;i < len; i++ ){
  			var rand = parseInt(Math.random()*len);
  			var temp = arr[rand];
  			arr[rand] = arr[i];
  			arr[i] = temp;
  		}
  		return arr;
  	}
  	console.log(randSort1(arr));
  	
  //方法二：
  	var arr = [1,2,3,4,5,6,7,8,9,10];
  	function randSort2(arr){
  		var mixedArray = [];
  		while(arr.length > 0){
  			var randomIndex = parseInt(Math.random()*arr.length);
  			mixedArray.push(arr[randomIndex]);
  			arr.splice(randomIndex, 1);
  		}
  		return mixedArray;
  	}
  	console.log(randSort2(arr));

  //方法三：
  	var arr = [1,2,3,4,5,6,7,8,9,10];
  	arr.sort(function(){
  		return Math.random() - 0.5;
  	})
  	console.log(arr);
```

#### 50、hasOwnProperty

javaScript中hasOwnProperty函数方法是返回一个布尔值，指出一个对象是否具有指定名称的属性。此方法无法检查该对象的原型链中是否具有该属性；该属性必须是对象本身的一个成员。
使用方法：`object.hasOwnProperty(proName)`
 其中参数object是必选项。一个对象的实例。
 proName是必选项。一个属性名称的字符串值。

 如果 object 具有指定名称的属性，那么JavaScript中hasOwnProperty函数方法返回 true，反之则返回 false。

#### 51、Object.is() 与原来的比较操作符“ ===”、“ ==”的区别？

- 两等号判等，会在比较时进行类型转换；
-   三等号判等(判断严格)，比较时不进行隐式类型转换,（类型不同则会返回false）；
- Object.is 在三等号判等的基础上特别处理了 NaN 、-0 和 +0 ，保证 -0 和 +0 不再相同，但 Object.is(NaN, NaN) 会返回 true.  Object.is 应被认为有其特殊的用途，而不能用它认为它比其它的相等对比更宽松或严格。

#### 52、列举IE与其他浏览器不一样的特性？

- 触发事件的元素被认为是目标（target）。而在 IE 中，目标包含在 event 对象的 srcElement 属性；
- 获取字符代码、如果按键代表一个字符（shift、ctrl、alt除外），IE 的 keyCode 会返回字符代码（Unicode），DOM 中按键的代码和字符是分离的，要获取字符代码，需要使用 charCode 属性；

- 阻止某个事件的默认行为，IE 中阻止某个事件的默认行为，必须将 returnValue 属性设置为 false，Mozilla 中，需要调用 preventDefault() 方法；
- 停止事件冒泡，IE 中阻止事件进一步冒泡，需要设置 cancelBubble 为 true，Mozzilla 中，需要调用 stopPropagation()；

#### 53、预解析

- 理解:在解析代码之前做的事,把变量的声明和函数的声明提前到当前所在作用域的最前面。
- 步骤：
  - 把变量的声明提升到当前作用域的最前面，只提升声明，不会提升赋值
  - 把函数的声明提升到当前作用域的最前面，只提升声明，不会提升调用
  - 先提升var ，再提升function
  - 只有用函数声明方式定义的函数才会提升function，函数表达式定义的函数是一个变量，提升var

#### 54、其他

- Javascript 事件处理器在线程空闲之前不会运行

  > 因为js是单线程的。浏览器遇到etTimeout和setInterval会先执行完当前的代码块，在此之前会把定时器推入浏览器的待执行时间队列里面，等到浏览器执行完当前代码之后会看下事件队列里有没有任务，有的话才执行定时器里的代码

```javascript
for(var i=1;i<=3;i++){
	setTimeout(function(){
		console.log(i);//4 4 4 
	},0);
};
for(var i=1;i<=3;i++){
	setTimeout((function(a){ //改成立即执行函数
		console.log(a);// 1 2 3
	})(i),0);
};
```

- 希望获取到页面中所有的 checkbox 怎么做？(不使用第三方框架)

```javascript
var domList = document.getElementsByTagName(‘input’)
var checkBoxList = [];//返回的所有的 checkbox
var len = domList.length; //缓存到局部变量
while (len--) { //使用 while 的效率会比 for 循环更高
	if (domList[len].type == ‘checkbox’) {
		checkBoxList.push(domList[len]);
	}
}
```

- new 操作符具体干了什么呢?

  - 创建一个空对象，并且 this 变量引用该对象，同时还继承了该函数的原型

  - 属性和方法被加入到 this 引用的对象中

  - 新创建的对象由 this 所引用，并且最后隐式的返回 this 

- ECMAScript6 怎么写 class 

    ```javascript
    class Point {
    	constructor(x, y) {
    	this.x = x;
    	this.y = y;
    }
    	toString() {
    		return '('+this.x+', '+this.y+')';
    	}
    }
    ```

- eval()的作用：把字符串参数解析成JS代码并运行，并返回执行的结果

  ```js
  //应该避免使用eval，不安全，非常耗性能（2次，一次解析成js语句，一次执行）。
  eval("2+3");//执行加运算，并返回运算值。  
  eval("varage=10");//声明一个age变量  
  
  //eval的作用域
  functiona(){  
  	1eval("var x=1"); //等效于 var x=1;  
  	console.log(x);  
  }  
  a();   //输出1
  console.log(x);//错误 x没有定
  ```

- 判断一个字符串中出现次数最多的字符，统计这个次数

  ```js
  var str = 'asdfssaaasasasasaa';
  var json = {};
  for (var i = 0; i < str.length; i++) {
      if(!json[str.charAt(i)]){
         json[str.charAt(i)] = 1;
      }else{
         json[str.charAt(i)]++;
      }
  }
  var iMax = 0;
  var iIndex = '';
  for(var i in json){
      if(json[i]>iMax){
           iMax = json[i];
           iIndex = i;
      }
  }        
  console.log('出现次数最多的是:'+iIndex+'出现'+iMax+'次');
  ```


## 三、HTTP和Ajax

#### 1、同步和异步的区别?

> javascript是单线程，单线程就意味着，所有任务需要排队，前一个任务结束，才会执行后一个任务。如果前一个任务耗时很长，后一个任务就不得不一直等着。于是就有一个概念——任务队列。如果排队是因为计算量大，CPU忙不过来，倒也算了，但是很多时候CPU是闲着的，因为IO设备（输入输出设备）很慢（比如Ajax操作从网络读取数据），不得不等着结果出来，再往下执行。于是JavaScript语言的设计者意识到，这时主线程完全可以不管IO设备，挂起处于等待中的任务，先运行排在后面的任务。等到IO设备返回了结果，再回过头，把挂起的任务继续执行下去。
>

- 同步和异步：
  - 同步：阻塞的，浏览器向服务器请求数据，服务器比较忙，浏览器一直等着（页面白屏），直到服务器返回数据，浏览器才能显示页面
  - 异步：非阻塞的，浏览器向服务器请求数据，服务器比较忙，浏览器可以自如的干原来的事情（显示页面），服务器返回数据的时候通知浏览器一声，浏览器把返回的数据再渲染到页面，局部更新

- 同步任务和异步任务：
  - 同步任务指的是，在主线程上排队执行的任务，只有前一个任务执行完毕，才能执行后一个任务
  - 异步任务指的是，不进入主线程、而进入"任务队列"（task queue）的任务，只有等主线程任务执行完毕，"任务队列"开始通知主线程，请求执行任务，该任务才会进入主线程执行

- 设置：open（）方法第三个参数是传入一个bool值，其作用就是设置此次请求是否采用异步方式执行 ，默认为true，如果需要同步执行可以通过传递false实现

  ```js
  console.log('before ajax');
  var xhr=new XMLHttpRequest();
  xhr.open('GET','http://localhost/test.php',true);
  xhr.send(null);
  xhr.onreadystatechange=function(){
      if(this.readyState===4){
          console.log('加载完成');
      }
  }
  console.log('after ajax');
  //控制台输出:
  //before ajax
  //after ajax
  //加载完成
  ```

#### 2、Ajax

- Ajax 并不算是一种新的技术，全称是 asynchronous javascript and xml，可以说是已有技术的组合，主要用来实现客户端与服务器端的异步通信效果，实现页面的局部刷新，早期的浏览器并不能原生支持 ajax，可以使用隐藏帧（iframe）方式变相实现异步效果，后来的浏览器提供了对 ajax 的原生支持。使 用 ajax 原 生 方 式 发 送 请 求 主 要 通 过 XMLHttpRequest( 标 准 浏 览 器 ) 、ActiveXObject(IE 浏览器)对象实现异步通信效果

  ```javascript
  var xhr =null;//创建对象
  if(window.XMLHttpRequest){
  	xhr = new XMLHttpRequest();
  }else{
  	xhr = new ActiveXObject("Microsoft.XMLHTTP");
  }
  xhr.open(“方式”,”地址”,”标志位”);//初始化请求
  xhr.setRequestHeader(“”,””);//设置 http 头信息
  xhr.onreadystatechange =function(){}//指定回调函数
  xhr.send();//发送请求
  ```

- 工作原理：

  - Ajax 的原理简单来说通过 XmlHttpRequest 对象来向服务器发异步请求，从服务器获得数据，
    然后用javascript来操作DOM而更新页面。这其中最关键的一步就是从服务器获得请求数据。
    要清楚这个过程和原理，必须对 XMLHttpRequest 有所了解。
  - XMLHttpRequest 是 ajax 的核心机制，它是在 IE5 中首先引入的，是一种支持异步请求的
    技术。简单的说，也就是 javascript 可以及时向服务器提出请求和处理响应，而不阻塞用户。
    达到无刷新的效果

- 优点：

  - 减轻服务器的负担,按需取数据,最大程度的减少冗余请求

  - 局部刷新页面,减少用户心理和实际的等待时间,带来更好的用户体验

  - 基于xml标准化,并被广泛支持,不需安装插件等,进一步促进页面和数据的分离

- 缺点：

  - AJAX大量的使用了javascript和ajax引擎,这些取决于浏览器的支持.在编写的时候考虑对浏览器的兼容性.

  - AJAX只是局部刷新,所以页面的后退按钮是没有用的，要实现 ajax 下的前后退功能成本较大

  - 对流媒体还有移动设备的支持不是太好等
  - 安全问题 AJAX 暴露了与服务器交互的细节
  - 对搜索引擎的支持比较弱
  - 破坏了程序的异常机制
  - 可能造成请求数的增加跨域问题限制

- Ajax原生

  ```javascript
  //1.get
  var xhr=new XMLHttpRequest()
  xhr.open('GET','http://localhost/test.php')
  xhr.send(null)
  xhr.onreadystatechange=function(){
      if(this.readyState===4){
          console.log(this.responseText);//1529894573
      }
  }
  //2.post
  var xhr=new XMLHttpRequest();
  xhr.open('POST','http://localhost/test.php');
  xhr.setRequestHeader('Content-Type','application/x-www-form-urlencoded');
  xhr.send('key1=value1 & key2=value2');
  xhr.onreadystatechange=function(){
      if(this.readyState!==4) return;
      console.log(this.responseText);
  }
  /*
  1. 创建 XMLHttpRequest 对象,也就是创建一个异步调用对象
  2. 创建一个新的 HTTP 请求,并指定该 HTTP 请求的方法、URL 及验证信息
  3. 设置响应 HTTP 请求状态变化的函数
  4. 发送 HTTP 请求
  5. 获取异步调用返回的数据
  6. 使用 JavaScript 和 DOM 实现局部刷新
  */
  ```

- 封装

  ```javascript
  /**
   *发送一个ajax请求
   *@param (string)   method 请求方法,可以是get，post
   *@param (string)   url    请求地址
   *@param (object)   params 请求参数
   *@param (Function) done   请求完成后需要做的事情(委托/回调)
   */
  function ajax(method, url, params,done) {
      //统一转换为大写便于后续判断 
      method = method.toUpperCase();
      //将对象类型的参数转换为urlencoded格式
      var tempArr = [];
      for (var key in params) {
          tempArr.push(key + "=" + params[key]);
      }
      var querystring = tempArr.join('&');
      var xhr = window.XMLHttpRequest ? 
          new XMLHttpRequest() : new ActiveXObject('Miscrosoft:XMLHTTP');
      xhr.addEventListener('readystatechange',function(){
          if(this.readyState!==4) return;
          //尝试通过JSON格式解析响应体
          try{
              done(JSON.parse(this.responseText))
          }catch(e){
              done(this.responseText)
          }
      });
      //如果是GET请求设置URL地址问号参数
      if(method==='GET'){
          url+='?'+querystring;
      }
      xhr.open(method,url);
      //如果是POST请求就设置请求体
      var data=null;
      if(method==="POST"){
          xhr.setRequestHeader('Content-Type','application/x-www-form-urlencoded');
          data=querystring;
      }
      xhr.send(data);
  }
  //调用举例
  ajax('POST', 'test.php', {key1: 'value1',key2: 'value2'},function(data){
      console.log(data);
  });
  ```

#### 3、Ajax跨域

- 理解跨域的概念：协议、域名、端口都相同才同域，否则都是跨域，浏览器的同源策略导致了跨域

  > 一段脚本只能读取来自于同一来源的窗口和文档的属性，这里的同一来源指的是域名、协议和端口号的组合。同源策略是浏览器的一种安全策略，所谓同源是指域名、协议、端口完全相同，只有同源的地址才可以相互通过AJAX的方式请求。同源策略带来的麻烦：ajax 在不同域名下的请求无法实现，如果说想要请求其他来源的 js 文件，或者 json 数据，那么可以通过 跨域手段来解决。
  >

- 如果是log之类的简单**单项通信**，新建`<img>`,`<script>`,`<link>`,`<iframe>`元素，通过src，href属性设置为目标url。实现跨域请求

- jsonp：动态创建 script 标签，使用标签的 src 属性访问 js 文件的形式获取 js脚本，并且这个 js 脚本中的内容是函数调用，该函数调用的参数是服务器返回的数据，为了获取这里的参数数据，需要事先在页面中定义回调函数，在回调函数中处理服务器返回的数据。JSONP需要服务端的配合，服务端按照客户端的要求返回一段JavaScript调用客户端的函数，只能发送GET请求，因为JSONP用的是script标签，跟AJAX提供的XMLHttpRequest没有任何的关系

- nginx 反向代理（nginx 服务内部配置 Access-Control-Allow-Origin ）

  > 定义和用法：proxy代理用于将请求发送给后台服务器，通过服务器来发送请求，然后将请求的结果传递给前端。实现方法：通过nginx代理；注意点：1、如果你代理的是https协议的请求，那么你的proxy首先需要信任该证书（尤其是自定义证书）或者忽略证书检查，否则你的请求无法成功。
  >

- cors 前后端协作设置请求头部，Access-Control-Allow-Origin 等头部信息

  ```php
  header('Access-Control-Allow-Origin: *')
  ```

- iframe 嵌套通讯

  - 通过修改docment.domain来实现跨域：该方法必须是在同主域，不同子域的情况下才生效

    只要把两个页面 的document.domain都指向主域就可以了，比如document.domain='morningstar.com'

  - ```html
    <!-- morningstar.com/parent.html -->
    <iframe id="ifr" 	                    src="http://test.morningstar.com/MarketBarometer/html/test.html"  width="200px">
    </iframe>
    <script>
        document.domain = 'morningstar.com';
    	function aa(str){
        	console.log(str);
    	}
    	window.onload = function(){
        	document.getElementById('ifr').contentWindow.bb('aaa');
    	}
    </script>
    
    <!--test.morningstar.com/test.html -->
    <script>
        document.domain = 'morningstar.com';
    	function bb(str){
        	console.log(str);
    	}
    	parent.aa('bbb');
    </script>
    ```

  - iframe+location.hash解决跨域

    ```html
    <!-- chart.com/parent.html -->
    <iframe 
         id="test1" src="http://test.com/test.html" width="100%" height="200px"></iframe>
    <script>
        function callback(data) {
            console.log(data);
        }
    </script>
    
    <!-- chart.com/poxy.html -->
    <script type="text/javascript">
        window.onload = function () {
            var data = location.hash.substr(1);
            data = eval("(" + decodeURIComponent(data) + ")");
            top.document.getElementById("test1").style.height = data.height + 'px';
            //调用父页面方法，可不写
            top.callback(data);
        }
    </script>
    
    <!-- test.com/child.html -->
    <div style="height:400px">
         <p>我是子页面</p>
    </div>
    <script type="text/javascript">
        window.onload = function () {
            if (!document.getElementById("crossFrame")) {
                var iframe = document.createElement('iframe');
                iframe.setAttribute('style', 'width:100%');
                iframe.setAttribute('src', 'http://chart.com/poxy.html');
                var height = document.documentElement.scrollHeight;
                var data = '{height:' + height + '}';
                //通过参数传递高度heights
                iframe.src = 'http://chart.com/poxy.html#' + data;
                document.body.appendChild(iframe);
            } else {
                document.getElementById("crossFrame").src = url;
            }
        }
    </script>
    ```

- postmessage，现代浏览器中多窗口通信使用HTML5规范的

  - targetWindow.postMessage(data, origin) 其中data是需要发送的对象，origin是目标窗口的origin。
  - window.addEventListener('message', handler, false) 其中handler的event.data是postMessage发送来的数据，event.origin是发送窗口的origin，event.source是发送消息的窗口引用

  ```html
  <!-- qsstage.morningstar.com.com/parent.html -->
  <iframeid="ifr" src="http://bar.com/b.html"></iframe>
  <script>window.onload = function(){
      var ifr = document.querySelector('#ifr');
      ifr.contentWindow.postMessage({a: 1}, '*');
  }
  window.addEventListener('message', function(e){
      console.log('bar say: '+e.data);
  }, false);
  </script>
  
  <!-- test.com/test.html -->
  window.addEventListener('message', function(e){
      console.log('foo say: ' + e.data.a);
      e.source.postMessage('get', '*');
  }, false)
  ```

####  4、GET 和 POST 有什么区别？

数据传递：

- get 传送的数据长度（浏览器规定的）有限制，post 没有

- get 通过 url 传递，在浏览器地址栏可见，post 是在报文中传递

使用场景：

- post 一般用于表单提交，需要对数据进行修改

- get 一般用于简单的数据查询，严格要求不是那么高的场景

- 在以下情况中，请使用 POST 请求：
  - 无法使用缓存文件（更新服务器上的文件或数据库）；
  - 向服务器发送大量数据（POST 没有数据量限制）;
  - 发送包含未知字符的用户输入时，POST 比 GET 更稳定也更可靠

#### 5、HTTP 常用状态码

> 100-199 用于指定客户端应相应的某些动作。
>
> 200-299 用于表示请求成功。
>
> 300-399 用于已经移动的文件并且常被包含在定位头信息中指定新的地址信息。
>
> 400-499 用于指出客户端的错误。
>
> 500-599 用于支持服务器错误。

100  Continue	继续，一般在发送post请求时，已发送了http header之后服务端将返回此信息，表示确认，之后发送具体参数信息

200：请求已成功，正常返回信息请求所希望的响应头或数据体将随此响应返回。

201：  Created  	请求成功并且服务器创建了新的资源

202 ： Accepted 	服务器已接受请求，但尚未处理

301 ：资源（网页等）被永久转移到其它 URL（永久重定向）

302：请求的资源临时从不同的 URI 响应请求（临时性重定向。）。由于这样的重定向是临时的，客户端应当继续向原有地址发送以后的请求。只有在 Cache-Control 或 Expires 中进行了指定的情况下，这个响应才是可缓存的

304：如果客户端发送了一个带条件的 GET 请求且该请求已被允许，而文档的内容（自上次访问以来或者根据请求的条件）并没有改变，则服务器应当返回这个状态码。304 响应禁止包含消息体，因此始终以消息头后的第一个空行结尾。

400：客户端请求有语法错误，不能被服务器所理解

401：当前请求需要用户验证

403：服务器已经理解请求，但是拒绝执行它。

404：请求失败，请求所希望得到的资源未被在服务器上发现。

500：服务器遇到了一个未曾预料的状况，导致了它无法完成对请求的处理。一般来说，这个问题都会在服务器端的源代码出现错误时出现。

503 Server Unavailable 503 Service Unavailable 服务器端暂时无法处理请求（可能是过载或维护）。

#### 6、HTTP 协 议 中 ，last-modified,cache-control,Expires 分别代表什么？

last-modified：文 档的最后改动时间。客户可以通过 If-Modified-Since 请求头提供一个日期，该请求将被视为一个条件 GET，只有改动时间迟于指定时间的文档才会返回，否则返回一个 304（Not Modified）状态。Last-Modified 也可用 setDateHeader 方法来设置

Expires：需和Last-Modified结合使用。用于控制请求文件的有效时间，当请求数据在有效期内时客户端浏览器从缓存请求数据而不是服务器端.当缓存中数据失效或过期，才决定从服务器更新数据

Expires和Cache-Control控制浏览器是否做缓存，如果缓存，缓存的有效期为多久。Expires值为-1和0不缓存。Cache-Control的值为no-cache不缓存.

#### 7、页面编码和被请求的资源编码如果不一致如何处理？

给请求的资源设置charset

对于 ajax 请求传递的参数，如果是 get 请求方式，参数如果传递中文，在有些浏览器会乱码，不同的浏览器对参数编码的处理方式不同，所以对于 get 请求的参数需要使用encodeURIComponent 函数对参数进行编码处理，后台开发语言都有相应的解码 api。

对于 post 请求不需要进行编码

#### 8、阐述一下异步加载

https://www.cnblogs.com/rik28/p/5950190.html

> 同步模式，又称阻塞模式，会阻止浏览器的后续处理，停止了后续的解析，因此停止了后续的文件加载（如图像）、渲染、代码执行。 js 之所以要同步执行，是因为 js 中可能有输出 document 内容、修改dom、重定向等行为，所以默认同步执行才是安全的。以前的一般建议是把<script>放在页面末尾</body>之前，这样尽可能减少这种阻塞行为，而先让页面展示出来。异步加载又叫非阻塞，浏览器在下载执行 js 同时，还会继续进行后续页面的处理。简单说：加载的网络 timeline 是瀑布模型，而异步加载的 timeline 是并发模型。

异步加载的方案： 动态插入 script 标签

```js
(function() {
     function async_load(){
         var s = document.createElement('script');
         s.type = 'text/javascript';
         s.async = true;
         s.src = 'http://yourdomain.com/script.js';
         var x = document.getElementsByTagName('script')[0];
         x.parentNode.insertBefore(s, x);
     }
     if (window.attachEvent)
         window.attachEvent('onload', async_load);
     else
         window.addEventListener('load', async_load, false);
 })();
```

通过 ajax 去获取 js 代码，然后通过 eval 执行

```js
var xhrObj = getXHRObject(); 
 xhrObj.onreadystatechange =  
   function() {  
     if ( xhrObj.readyState != 4 ) return; 
     eval(xhrObj.responseText); 
   }; 
 xhrObj.open('GET', 'A.js', true); 
 xhrObj.send('');
```

script 标签上添加 defer（IE） 或者 async 属性

- defer属性声明这个脚本中将不会有 document.write 或 dom 修改。浏览器将会并行下载 file.js 和其它有 defer 属性的script，而不会阻塞页面后续处理。defer属性在IE 4.0中就实现了，超过13年了！Firefox 从 3.5 开始支持defer属性 。所有的defer 脚本保证是按顺序依次执行的。

  ```html
  <script src="file.js" defer></script> 
  ```

- async属性是HTML5新增的。作用和defer类似，但是它将在下载后尽快执行，**不能保证脚本会按顺序执行**。它们将在onload 事件之前完成。Firefox 3.6、Opera 10.5、IE 9 和 最新的Chrome 和 Safari 都支持 async 属性。

- 可以同时使用 async 和 defer，这样IE4之后的所有 IE 都支持异步加载。如果没有 async 属性 但是有 defer 属性，那么script 将在页面parse之后执行，如果同时设置了二者，那么 defer 属性主要是为了让不支持 async 属性的老浏览器按照原来的 defer 方式处理，而不是同步方式

创建并插入 iframe，让它异步执行 js

```js
 var iframe = document.createElement('iframe'); 
 document.body.appendChild(iframe); 
 var doc = iframe.contentWindow.document; 
 doc.open().write('<body onload="insertJS()">'); 
 doc.close();
```

#### 9、一个页面从输入 URL 到页面加载显示完成，这个过程中都发生了什么？

> https://www.cnblogs.com/EricZLin/p/9189531.html

- 用户在浏览器地址栏输入URL

- 浏览器查看缓存，如果请求资源在缓存中并且新鲜，跳转到转码步骤:

  1. 如果资源未缓存，发起新请求

  2. 如果已缓存，检验是否足够新鲜，足够新鲜直接提供给客户端，否则与服务器进行验证。

  3. 检验新鲜通常有两个HTTP头进行控制`Expires`和`Cache-Control`：

     > HTTP1.0提供Expires，值为一个绝对时间表示缓存新鲜日期
     >
     > HTTP1.1增加了Cache-Control: max-age=,值为以秒为单位的最大新鲜时间

- 浏览器解析URL获取协议，主机，端口，path

- 浏览器组装一个HTTP（GET）请求报文

- 浏览器获取主机ip地址，过程如下：

  > 浏览器缓存----本机缓存----hosts文件----路由器缓存----ISP DNS缓存---DNS递归查询（可能存在负载均衡导致每次IP不一样）

- 浏览器打开一个socket与目标IP地址指定的端口建立TCP链接，三次握手如下：

  1. 客户端发送一个TCP的**SYN=1，Seq=X**的包到服务器端口
  2. 服务器发回**SYN=1， ACK=X+1， Seq=Y**的响应包
  3. 客户端发送**ACK=Y+1， Seq=Z**

- TCP链接建立后**发送HTTP请求**

- 服务器接受请求并解析，将请求转发到服务程序，如虚拟主机使用HTTP Host头部判断请求的服务程序

- 服务器检查**HTTP请求头是否包含缓存验证信息**如果验证缓存新鲜，返回**304**等对应状态码

- 处理程序读取完整请求并准备HTTP响应，可能需要查询数据库等操作

- 服务器将**响应报文通过TCP连接发送回浏览器**

- 浏览器接收HTTP响应，然后根据情况选择关闭TCP连接或者保留重用，关闭TCP连接的四次挥手如下：

  1. 主动方发送**Fin=1， Ack=Z， Seq= X**报文
  2. 被动方发送**ACK=X+1， Seq=Z**报文
  3. 被动方发送**Fin=1， ACK=X， Seq=Y**报文
  4. 主动方发送**ACK=Y， Seq=X**报文

- 浏览器检查响应状态吗：是否为1XX，3XX， 4XX， 5XX，这些情况处理与2XX不同

- 如果资源可缓存，**进行缓存**

- 对响应进行**解码**（例如gzip压缩）

- 根据资源类型决定如何处理（假设资源为HTML文档）

- **解析HTML文档，构件DOM树，下载资源，构造CSSOM树，执行js脚本**，这些操作没有严格的先后顺序，以下分别解释

- 构建DOM树：

  1. **Tokenizing**：根据HTML规范将字符流解析为标记
  2. **Lexing**：词法分析将标记转换为对象并定义属性和规则
  3. **DOM construction**：根据HTML标记关系将对象组成DOM树

- 解析过程中遇到图片、样式表、js文件，**启动下载**

- 构建CSSOM树：

  1. **Tokenizing**：字符流转换为标记流
  2. **Node**：根据标记创建节点
  3. **CSSOM**：节点创建CSSOM树

- 根据DOM树和CSSOM树构建渲染树:

  1. 从DOM树的根节点遍历所有**可见节点**，不可见节点包括：1）`script`,`meta`这样本身不可见的标签。2)被css隐藏的节点，如`display: none`
  2. 对每一个可见节点，找到恰当的CSSOM规则并应用
  3. 发布可视节点的内容和计算样式

- js解析如下：

  1. 浏览器创建Document对象并解析HTML，将解析到的元素和文本节点添加到文档中，此时**document.readystate为loading**
  2. HTML解析器遇到**没有async和defer的script时**，将他们添加到文档中，然后执行行内或外部脚本。这些脚本会同步执行，并且在脚本下载和执行时解析器会暂停。这样就可以用document.write()把文本插入到输入流中。**同步脚本经常简单定义函数和注册事件处理程序，他们可以遍历和操作script和他们之前的文档内容**
  3. 当解析器遇到设置了**async**属性的script时，开始下载脚本并继续解析文档。脚本会在它**下载完成后尽快执行**，但是**解析器不会停下来等它下载**。异步脚本**禁止使用document.write()**，它们可以访问自己script和之前的文档元素
  4. 当文档完成解析，document.readState变成interactive
  5. 所有**defer**脚本会**按照在文档出现的顺序执行**，延迟脚本**能访问完整文档树**，禁止使用document.write()
  6. 浏览器**在Document对象上触发DOMContentLoaded事件**
  7. 此时文档完全解析完成，浏览器可能还在等待如图片等内容加载，等这些**内容完成载入并且所有异步脚本完成载入和执行**，document.readState变为complete,window触发load事件

- **显示页面**（HTML解析过程中会逐步显示页面）

####  10、ajax 请求时，如何解释 json 数据

使用 eval() 或者 JSON.parse() 

鉴于安全性考虑，推荐使用 JSON.parse()更靠谱，对数据的安全性更好

#### 12、HTTP method

- **GET**是最常用的方法，通常用于请求服务器发送某个资源。
- **HEAD**与GET类似，但服务器在响应中值返回首部，不返回实体的主体部分
- **PUT**让服务器用请求的主体部分来创建一个由所请求的URL命名的新文档，或者，如果那个URL已经存在的话，就用这个主体替代它
- **POST**起初是用来向服务器输入数据的。实际上，通常会用它来支持HTML的表单。表单中填好的数据通常会被送给服务器，然后由服务器将其发送到要去的地方。
- **TRACE**会在目的服务器端发起一个环回诊断，最后一站的服务器会弹回一个TRACE响应并在响应主体中携带它收到的原始请求报文。TRACE方法主要用于诊断，用于验证请求是否如愿穿过了请求/响应链。
- **OPTIONS**方法请求web服务器告知其支持的各种功能。可以查询服务器支持哪些方法或者对某些特殊资源支持哪些方法。
- **DELETE**请求服务器删除请求URL指定的资源

#### 13、请求报文和响应报文结构

- 请求报文

  1. 首行是**Request-Line**包括：**请求方法**，**请求URI**，**协议版本**，**CRLF**

  2. 首行之后是若干行**请求头**，包括**general-header**，**request-header**或者**entity-header**，每个一行以CRLF结束

  3. 请求头和消息实体之间有一个**CRLF分隔**

     ```http
     GET /Protocols/rfc2616/rfc2616-sec5.html HTTP/1.1
     Host: www.w3.org
     Connection: keep-alive
     Cache-Control: max-age=0
     Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
     User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.153 Safari/537.36
     Referer: https://www.google.com.hk/
     Accept-Encoding: gzip,deflate,sdch
     Accept-Language: zh-CN,zh;q=0.8,en;q=0.6
     Cookie: authorstyle=yes
     If-None-Match: "2cc8-3e3073913b100"
     If-Modified-Since: Wed, 01 Sep 2004 13:24:52 GMT
     
     name=qiu&age=25
     ```

- 响应报文

  1. 首行是状态行包括：**HTTP版本，状态码，状态描述**，后面跟一个CRLF

  2. 首行之后是**若干行响应头**，包括：**通用头部，响应头部，实体头部**

  3. 响应头部和响应实体之间用**一个CRLF空行**分隔

     ```http
     HTTP/1.1 200 OK
     Date: Tue, 08 Jul 2014 05:28:43 GMT
     Server: Apache/2
     Last-Modified: Wed, 01 Sep 2004 13:24:52 GMT
     ETag: "40d7-3e3073913b100"
     Accept-Ranges: bytes
     Content-Length: 16599
     Cache-Control: max-age=21600
     Expires: Tue, 08 Jul 2014 11:28:43 GMT
     P3P: policyref="http://www.w3.org/2001/05/P3P/p3p.xml"
     Content-Type: text/html; charset=iso-8859-1
     
     {"name": "qiu", "age": 25}
     ```


#### 15、XMLHttpRequest通用属性和方法？

- `readyState`:表示请求状态的整数，取值：
  - UNSENT（0）：对象已创建
  - OPENED（1）：open()成功调用，在这个状态下，可以为xhr设置请求头，或者使用send()发送请求
  - HEADERS_RECEIVED(2)：所有重定向已经自动完成访问，并且最终响应的HTTP头已经收到
  - LOADING(3)：响应体正在接收
  - DONE(4)：数据传输完成或者传输产生错误

- `onreadystatechange`：readyState改变时调用的函数
- `status`：服务器返回的HTTP状态码（如，200， 404）
- `statusText`:服务器返回的HTTP状态信息（如，OK，No Content）
- `responseText`:作为字符串形式的来自服务器的完整响应
- `responseXML`: Document对象，表示服务器的响应解析成的XML文档
- `abort()`:取消异步HTTP请求
- `getAllResponseHeaders()`: 返回一个字符串，包含响应中服务器发送的全部HTTP报头。每个报头都是一个用冒号分隔开的名/值对，并且使用一个回车/换行来分隔报头行
- `getResponseHeader(headerName)`:返回headName对应的报头值
- `open(method, url, asynchronous [, user, password])`:初始化准备发送到服务器上的请求。method是HTTP方法，不区分大小写；url是请求发送的相对或绝对URL；asynchronous表示请求是否异步；user和password提供身份验证
- `setRequestHeader(name, value)`:设置HTTP报头
- `send(body)`:对服务器请求进行初始化。参数body包含请求的主体部分，对于POST请求为键值对字符串；对于GET请求，为null

#### 16、http和https的区别

- http：

  - 是互联网上应用最为广泛的一种网络协议，是一个客户端和服务器端请求和应答的标准（TCP），用于从WWW服务器传输超文本到本地浏览器的传输协议，它可以使浏览器更加高效，使网络传输减少。

  - 运行在TCP之上，所有传输的内容都是明文，客户端和服务器端都无法验证对方的身份。

- https：
  - 是以安全为目标的HTTP通道，简单讲是HTTP的安全版本，通过SSL加密
  - 运行在SSL/TLS之上，SSL/TLS运行在TCP之上。所有传输的内容都经过加密，加密采用对称加密，但对称加密的密钥用服务器方的证书进行了非对称加密。
  - 此外客户端可以验证服务器端的身份，如果配置了客户端验证，服务器方也可以验证客户端的身份
  - http和https使用的是完全不同的连接方式，用的端口也不一样，前者是80，后者是443

#### 17、http1.0、1.1、2.0的区别

- 1.0跟1.1的区别：
  - 长连接：HTTP1.0需要使用keep-alive参数来告知服务器建立一个长连接，而HTP1.1默认支持长连接
  -  节约宽带：HTTP1.1支持只发送一个header信息（不带任何body信息）
  -  host域（设置虚拟站点，也就是说，webserver上的多个虚拟站点可以共享同一个ip端口）：HTTP1.0没有host域

- 1.1跟2.0的区别：
  - http2.0采用的二进制文本传输数据，而非http1.1文本格式，二进制在协议的解析和扩展更好
  - 数据压缩：对信息头采用了HPACK进行压缩传输，节省了信息头带来的网络流量
  - 多路复用：一个连接可以并发处理多个请求
  - 服务器推送：我们对支持HTTP2.0的webserver请求数据的时候，服务器会顺便把一些客户端需要的资源一起推送到客户端，免得客户端再次创建连接发送请求到服务器端获取。这种方式非常合适加载静态资源

#### 18、Cookie 隔离

- 因为cookie有域的限制，因此不能跨域提交请求，故使用非主要域名的时候，请求头中就不会带有cookie数据，这样可以降低请求头的大小，降低请求时间，从而达到降低整体请求延时的目的。
- 同时这种方式不会将cookie传入Web Server，也减少了Web Server对cookie的处理分析环节， 提高了webserver的http请求的解析速度如果静态文件都放在主域名下，那静态文件请求的时候都带有的cookie的数据提交给server的，非常浪费流量， 所以不如隔离开。

#### 19、Ajax 解决浏览器缓存问题？

- 在ajax发送请求前加上 anyAjaxObj.setRequestHeader("If-Modified-Since","0")
- 在ajax发送请求前加上 anyAjaxObj.setRequestHeader("Cache-Control","no-cache")
- 在URL后面加上一个随机数： "fresh=" + Math.random();
- 在URL后面加上时间戳："nowtime=" + new Date().getTime();
- 如果是使用jQuery，直接这样就可以了 $.ajaxSetup({cache:false})。这样页面的所有ajax都会执行这条语句就是不需要保存缓存记录。

## 四、jQuery

#### 1、bind(), live(), delegate()、on的区别

- bind： 绑定事件，对新添加的事件不起作用，方法用于将一个处理程序附加到每个匹配元素的事件上并返回 jQuery 对象。

- live： 方法将一个事件处理程序附加到与当前选择器匹配的所有元素（包含现有的或将来添加的）的指定事件上并返回 jQuery 对象。

- delegate： 方法基于一组特定的根元素将处理程序附加到匹配选择器的所有元素（现有的或将来的）的一个或多个事件上。

- on：1.7版本整合了之前的三种方式的新事件绑定机制，on方法是当前JQuery推荐使用的事件绑定方法，附加只运行一次就删除函数的方法是one()

#### 2、jQuery 框架中$.ajax()的常用参数有哪些？

```javascript
/**
*type:get/type,：其它 HTTP 请求方法，如 PUT 和 DELETE 也可以使用，但仅部分浏览器支持
*url:String、当前页地址、发送请求的地址
*success:Function请求成功后的回调函数，并根据 dataType 参数进行处理后的数据
*options：Object AJAX 请求设置。所有选项都是可选的。
*async：Boolean，默认值: true，所有请求均为异步请求。如果需要发送同步请求，设置为 false。
*data：{}发送到服务器的数据。将自动转换为请求字符串格式
*dataType：预期服务器返回的数据类型
*error：请求失败时调用此函数
*/
```

#### 3、动画滞后问题

jQuery中slideUp 、slideDown、animate等动画运用时，如果目标元素是被外部事件驱动, 当鼠标快速地连续触发外部元素事件, 动画会滞后的反复执行，其表现不雅。

解决办法：

- 在触发元素上的事件设置为延迟处理, 即可避免滞后反复执行的问题（使用setTimeout）

- 在触发元素的事件时预先停止所有的动画，再执行相应的动画事件（使用stop）

  ```js
  jquery stop(): 如：$("#div").stop().animate({width:"100px"},100);
  ```

#### 4、jQuery 一个对象可以同时绑定多个事件，这是如何实现的？

jQuery 可以给一个对象同时绑定多个事件，低层实现方式是使用 addEventListner 或attachEvent 兼容不同的浏览器实现事件的绑定，这样可以给同一个对象注册多个事件。

####  5、jQuery 与 jQuery UI 有啥区别？

- jQuery 是一个 js 库，主要提供的功能是选择器，属性修改和事件绑定等等

- jQuery UI 则是在 jQuery 的基础上，利用 jQuery 的扩展性，设计的插件。提供了一些常用的界面元素，诸如对话框、拖动行为、改变大小行为等等

#### 6、jquery 中如何将数组转化为 json 字符串，然后再转化回来？

jQuery 中没有提供这个功能，所以你需要先编写两个 jQuery 的扩展：

```javascript
$.fn.stringifyArray = function(array) {
	return JSON.stringify(array)
}
$.fn.parseArray = function(array) {
	return JSON.parse(array)
}
//然后调用：
$("").stringifyArray(array)
```

#### 7、jQuery.fn 的 init 方法返回的 this 指的是什么对象？为什么要返回 this？
this 执行 init 构造函数自身，其实就是 jQuery 实例对象，返回 this 是为了实现 jQuery的链式操作

#### 8、jQuery 的属性拷贝(extend)的实现原理是什么，如何实现深拷贝？

- 原理：递归赋值

```js
$.extend( [deep ], target, object1 [, objectN ] )；

 deep 类型: Boolean 如果是true，合并成为递归（又叫做深拷贝）。
 target 类型: Object 对象扩展。这将接收新的属性。
 object1 类型: Object 一个对象，它包含额外的属性合并到第一个参数。
 objectN 类型: Object 包含额外的属性合并到第一个参数。
```

- $.extend浅拷贝：

  ```js
  var obj1 = {name:xx,age:18,sex:man};
  var obj2 = {name:cc,age:18};
  $.extend(obj1,obj2);
  obj1----->{name:cc,age:18} //被obj2覆盖
  ```

- $.extend深拷贝：

  ```js
  var obj1 = {name:xx,age:18,sex:man};
  var obj2 = {name:cc,age:18};
  $.extend(true,obj1,obj2);
  obj1----->{name:cc,age:18，sex:man}
  ```

#### 9、jQuery.extend 与 jQuery.fn.extend 的区别？
jQuery.extend 用来扩展 jQuery 对象本身；jQuery.fn.extend  用来扩展 jQuery 实例

```js
//1.fn的jQuery的源码
jQuery.fn = jQuery.prototype ={ 
　　　init: function( selector, context ){//....　 
　　　//...... 
}; 
    
//2.如果希望jQuery的实例对象能够调用某个方法,开始使用jQuery.fn.extend(object)
$.fn.sayHi=function(){console.log('hello')} //添加
$('#btn').click(function(){$('#btn').sayHi()}) //使用

//3.如更希望jQuery的实例对象添加类(静态方法)，可以使用jQuery.extend(object)
$.extend({ 
　　add:function(a,b){return a+b;} 
}); //添加
console.log($.add(3,7)) //10
```

#### 10、jQuery 和 Zepto 的区别？

- 应用平台：jQuery 主要用于 pc 端，当然有对应的 jQuerymobile 用于移动端，zepto 比 jQuery 更加小巧，主要用于移动端

- 体积：jQuery mobile 相对于 zepto 功能强大，但是体积也很庞大，zepto 非常的轻量

- 具体：

  - Zepto对象没有addEventListener事件
  - Zepto选择器表达式中value值必须用单引号或双引号扩起来
  - Zepto根据标准浏览器，只有width()，height（），没有innerHeight,outerHeight等，返回值与jquery不同
  - Zepto each不能遍历对象


#### 11、针对 jQuery 的优化方法？

- 优先使用 ID 选择器
- jquery 获取到的 DOM 元素如果需要多次使用，建议使用一个变量将其保存起来，因为操作 DOM 的过程是非常耗费性能的
- 在 class 前使用 tag(标签名)
- 给选择器一个上下文
- 慎用 .live()方法（应该说尽量不要使用）
- 使用 data()方法存储临时变量

#### 12、Zepto 的点透问题如何解决？

问题：点透主要是由于两个 div 重合，例如：一个 div 调用 show()，一个 div 调用 hide()；这个时候当点击上面的 div 的时候就会影响到下面的那个 div；
解决办法主要有 2 种：

- github 上有一个叫做 fastclick 的库，它也能规避移动设备上 click 事件的延迟响应，https://github.com/ftlabs/fastclick；将它用 script 标签引入页面（该库支持 AMD，于是你也可以按照 AMD 规范，用诸如require.js 的模块加载器引入），并且在 dom ready 时初始化在 body 上
- 根据分析，如果不引入其它类库，也不想自己按照上述 fastclcik 的思路再开发一套东西，需要 1.一个优先于下面的“divClickUnder”捕获的事件；2.并且通过这个事件阻止掉默认行为（下面的“divClickUnder”对 click 事件的捕获，在 ios 的 safari，click 的捕获被认为和滚屏、点击输入框弹起键盘等一样，是一种浏览器默认行为，即可以被 event.preventDefault()阻止的行为）。

#### 13、JQuery有几种选择器?

(1)、基本选择器：#id，class,element,*;

(2)、层次选择器：parent > child，prev + next ，prev ~ siblings

(3)、基本过滤器选择器：:first，:last ，:not ，:even ，:odd ，:eq ，:gt ，:lt

(4)、内容过滤器选择器： :contains ，:empty ，:has ，:parent

(5)、可见性过滤器选择器：:hidden ，:visible

(6)、属性过滤器选择器：[attribute] ，[attribute=value] ，[attribute!=value] ，[attribute^=value] ，[attribute$=value] ，[attribute*=value]

(7)、子元素过滤器选择器：:nth-child ，:first-child ，:last-child ，:only-child

(8)、表单选择器： :input ，:text ，:password ，:radio ，:checkbox ，:submit 等；

(9)、表单过滤器选择器：:enabled ，:disabled ，:checked ，:selected

#### 14、如何用jQuery禁用浏览器的前进后退按钮？

```html
<script type="text/javascript" language="javascript">
　　$(document).ready(function() {
　　　　window.history.forward(1);
  　　　　//OR window.history.forward(-1);
　　});
</script>
```

#### 15、serialize() 方法

通过序列化表单值，创建 URL 编码文本字符串。可以选择一个或多个表单元素（比如 input 及/或 文本框），或者 form 元素本身。序列化的值可在生成 AJAX 请求时用于 URL 查询字符串中。

```js
$(selector).serialize() 
//a=1&b=2&c=3&d=4&e=5
```

serializeArray() 方法通过序列化表单值来创建对象数组（名称和值），您可以选择一个或多个表单元素（比如 input 及/或 textarea），或者 form 元素本身。

#### 16、jQuery 的队列是如何实现的？队列可以用在哪些地方？

jQuery核心中, 有一组队列控制方法, 这组方法由queue()/dequeue()/clearQueue()三个方法组成, 它对需要连续按序执行的函数的控制可以说是简明自如, 主要应用于animate ()方法, ajax以及其他要按时间顺序执行的事件中

- queue(name,[callback]): 当只传入一个参数时, 它返回并指向第一个匹配元素的队列(将是一个函数数组,队列名默认是fx); 当有两个参数传入时, 第一个参数还是默认为fx的的队列名, 第二个参数又分两种情况, 当第二个参数是一个函数时, 它将在匹配的元素的队列最后添加一个函数. 当第二个参数是一个函数数组时,它将匹配元素的队列用新的一个队列来代替(函数数组).

- dequeue(name): 这个好理解, 就是从队列最前端移除一个队列函数, 并执行它

- clearQueue([queueName]):这是1.4新增的方法. 清空对象上尚未执行的所有队列. 参数可选,默认为fx.  用queue()方法传入两个参数的第二种参数即可实现clearQueue方法

  ```js
  // 第一个ajax请求
  $(document).queue("ajaxRequests", function(){
      //全局变量，储存第一个ajax请求数据
      var a_data;
      $.ajax({
          success: function(data){
              a_data = data;
              $(document).dequeue("myName");
          }
      });
  });
  // 第二个ajax请求
  $(document).queue("ajaxRequests", function() {
    $.ajax({
      success: function(data) {
        alert(a_data);
        $(document).dequeue("myName");
      }
    });
  });
  // 触发queue往下执行
  $(document).dequeue("ajaxRequests");
  ```

#### 17、jQuery里的fire函数是什么意思，什么时候用？

callbacks.fire() 函数用于传入指定的参数调用所有的回调。此方法返回一个回调对象到它绑定的回调列表

```js
$(function () { 
    // 将被添加到列表的一个简单的函数
    var foo = function( value ) {
          alert( "foo:" + value );
    };     
    var callbacks = $.Callbacks(); 
    // 添加函数 "foo" 到列表
    callbacks.add( foo ); 
    // 传入参数调用所有回调列表
    callbacks.fire( "hello" ); // 输出: "foo: hello"
    callbacks.fire( "world" ); // 输出: "foo: world"     
    // 添加另一个函数到列表
    var bar = function( value ){
      alert( "bar:" + value );
    };
    // 添加这个函数到列表
    callbacks.add( bar ); 
    // 传入参数调用所有回调列表
    callbacks.fire( "hello again" );
    // 输出:
    // "foo: hello again"
    // "bar: hello again"
})
```

## 五、HTML5和CSS3

#### 1、CSS3 有哪些新特性？

- 圆角（border-radius），
- 阴影（box-shadow）和反射（Reflect）

- 文字特效（text-shadow、），文字渲染（Text-decoration）
- 线性渐变（gradient）
- transform 旋转、缩放、位移、倾斜，然后过渡效果transition
- 动画

- 多背景

- 媒体查询，多栏布局

- border-image边框图片

- 增加了更多的 CSS 选择器，新增伪类，在 CSS3 中唯一引入的伪元素是 ::selection

```css
p:first-of-type	选择属于其父元素的首个 <p> 元素的每个 <p> 元素。
p:last-of-type	选择属于其父元素的最后 <p> 元素的每个 <p> 元素。
p:only-of-type	选择属于其父元素唯一的 <p> 元素的每个 <p> 元素。
p:only-child	选择属于其父元素的唯一子元素的每个 <p> 元素。
p:nth-child(2)	选择属于其父元素的第二个子元素的每个 <p> 元素。

::after			在元素之前添加内容,也可以用来做清除浮动。
::before		在元素之后添加内容
:enabled  		
:disabled 		控制表单控件的禁用状态。
:checked        单选框或复选框被选中。
```

#### 2、HTML5 有哪些新特性？

- 新特性
  - 拖拽释放(Drag and drop) API   https://www.cnblogs.com/EricZLin/p/9267640.html
  - 语义化更好的内容标签（header,nav,footer,aside,article,section）https://www.cnblogs.com/EricZLin/p/8854807.html
  - 音频、视频 API(audio,video) https://www.cnblogs.com/EricZLin/p/8856170.html
  - 画布(Canvas) API https://www.cnblogs.com/EricZLin/p/9269404.html
  - 地理(Geolocation) API https://www.cnblogs.com/EricZLin/p/9267543.html
  - 本地离线存储 localStorage 长期存储数据，浏览器关闭后数据不丢失，sessionStorage 的数据在浏览器关闭后自动删除 https://www.cnblogs.com/EricZLin/p/9261445.html
  - 表单控件，Datalist datetime  keygen date month week time number range emailurl  https://www.cnblogs.com/EricZLin/p/8855567.html
  -  webworker http://www.w3school.com.cn/html5/html_5_webworkers.asp
  - websocket  http://www.runoob.com/html/html5-websocket.html

- 移除的元素
  - 纯表现的元素：basefont，big，center，font, s，strike，tt，u；
  - 对可用性产生负面影响的元素：frame，frameset，noframes

- 兼容处理：

  - IE8/IE7/IE6 支持通过 document.createElement 方法产生的标签，可以利用这一特性
    让这些浏览器支持 HTML5 新标签，浏览器支持新标签后，还需要添加标签默认的样式

  - 当然最好的方式是直接使用成熟的框架、使用最多的是 html5shim 框架

    ```html
    <!--[if lt IE 9]>
    <script> src="http://html5shim.googlecode.com/svn/trunk/html5.js"</script>
    <![endif]-->
    ```

#### 3、如何实现浏览器内多个标签页之间的通信?

https://www.jianshu.com/p/31facd4934d7

- WebSocket
- SharedWorker
- 也可以调用localstorge、cookies等本地存储方式；

  > localstorge另一个浏览上下文里被添加、修改或删除时，它都会触发一个事件，我们通过监听事件，控制它的值来进行页面信息通信； 注意quirks：Safari 在无痕模式下设置localstorge值时会抛出 QuotaExceededError 的异常；

#### 4、HTML5 Canvas 
Canvas 元素用于在网页上绘制图形，该元素标签强大之处在于可以直接在 HTML 上进行图形操作。

https://www.cnblogs.com/EricZLin/p/9269404.html

https://www.cnblogs.com/EricZLin/p/9271606.html

https://www.cnblogs.com/EricZLin/p/9276197.html

#### 5、HTML5几种存储方式的总结

https://blog.csdn.net/s164828378/article/details/52747032

- 本地存储localstorage
- 本地存储sessionstorage
- 离线缓存（application cache）
- 关系数据库 Web SQL
- 索引数据库 IndexedDB

#### 6、实现动画的反方式

- js动画: 使用定时器，https://www.cnblogs.com/EricZLin/p/9004798.html

- CSS :

  - transition 包含4种属性：`transition：width 3s ease 0s`，对应动画的4种属性：对应css属性、持续时间、 缓动函数、延迟时间，https://www.cnblogs.com/EricZLin/p/8867377.html
  - transform 包含6种属性：动画名称 花费时间 运动曲线 何时开始 循环次数 是否反方向https://www.cnblogs.com/EricZLin/p/8873564.html

- HTML5 动画

  - canvas：https://www.cnblogs.com/EricZLin/p/9276197.html
  - svg：https://www.zhangxinxu.com/wordpress/2014/08/so-powerful-svg-smil-animation/
  - webgl：（Web图形库) 是一种JavaScript API，用于在任何兼容的Web浏览器中呈现交互式3D和2D图形，而无需使用插件。

#### 7、如何在 HTML5 页面中嵌入音频和视频?

HTML 5 包含嵌入音频文件的标准方式，支持的格式包括 MP3、Wav 和 Ogg

```html
<audio controls>
	<source src="jamshed.mp3" type="audio/mpeg">
	Your browser does'nt support audio embedding feature.
</audio>
```

HTML5 定义了嵌入视频的标准方法，支持的格式包括：MP4、WebM 和 Ogg

```html
<video width="450" height="340" controls>
	<source src="jamshed.mp4" type="video/mp4">
	Your browser does'nt support video embedding feature.
</video>
```

####  8、data-*属性的作用

https://www.cnblogs.com/EricZLin/p/9256666.html

- html5规范里增加了一个自定义data属性

- > ```
  > 为前端开发者提供自定义的属性，这些属性集可以通过对象的dataset属性获取，不支持该属性的浏览器可以通过 getAttribute方法获取
  > <div data-author="david" data-time="2011-06-20" data-comment-num="10">...</div>
  > div.dataset.commentNum; // 可通过js获取 10
  > ```

- data-为前端开发者提供自定义的属性，这些属性集可以通过对象的dataset属性获取，不支持该属性的浏览器可以通过 getAttribute方法获取。

- 需要注意的是，data-之后的以连字符分割的多个单词组成的属性，获取的时候使用驼峰风格。

#### 9、如果把 HTML5 看作做一个开放平台，那它的构建模块有哪些？

-  Web Storage API
- 基于位置服务LBS
- 无插件播放音频视频
- 调用相机和GPU图像处理单元等硬件设备
- 拖拽和Form API

#### 10、应用程序存储和离线web应用？

HTML5新增应用程序缓存，允许web应用将应用程序自身保存到用户浏览器中，用户离线状态也能访问。

> 原理：HTML5的离线存储是基于一个新建的.appcache文件的缓存机制(不是存储技术)，通过这个文件上的解析清单离线存储资源，这些资源就会像cookie一样被存储了下来。之后当网络在处于离线状态下时，浏览器会通过被离线存储的数据进行页面展示。
>
> 在线的情况下，浏览器发现html头部有manifest属性，它会请求manifest文件，如果是第一次访问app，那么浏览器就会根据manifest文件的内容下载相应的资源并且进行离线存储。如果已经访问过app并且资源已经离线存储了，那么浏览器就会使用离线的资源加载页面，然后浏览器会对比新的manifest文件与旧的manifest文件，如果文件没有发生改变，就不做任何操作，如果文件改变了，那么就会重新下载文件中的资源并进行离线存储。离线的情况下，浏览器就直接使用离线存储的资源。

- 为html元素设置manifest属性:`<html manifest="myapp.appcache">`，其中后缀名只是一个约定，真正识别方式是通过`text/cache-manifest`作为MIME类型。所以需要配置服务器保证设置正确 。在离线状态时，操作window.applicationCache进行需求实现。

- manifest文件首行为`CACHE MANIFEST`，其余就是要缓存的URL列表，每个一行，相对路径都相对于manifest文件的url。注释以#开头 

- url分为三种类型：`CACHE`:为默认类型。`NETWORK`：表示资源从不缓存。 `FALLBACK`:每行包含两个url，第二个URL是指需要加载和存储在缓存中的资源， 第一个URL是一个前缀。任何匹配该前缀的URL都不会缓存，如果从网络中载入这样的URL失败的话，就会用第二个URL指定的缓存资源来替代。以下是一个文件例子：

```js
CACHE MANIFEST

CACHE:
myapp.html
myapp.css
myapp.js

FALLBACK:
videos/ offline_help.html

NETWORK:
cgi/
```

#### 11、webSocket

- 参考：https://www.cnblogs.com/fuqiang88/p/5956363.html

- 如何兼容低浏览器？
  -  Adobe Flash Socket 
  -   ActiveX HTMLFile (IE) 
  -   基于 multipart 编码发送 XHR 
  -   基于长轮询的 XHR

## 六、移动web

#### 1、什么是响应式设计？

它是关于网页制作的过程中让不同的设备有不同的尺寸和不同的功能。响应式设计是让所有的人能在这些设备上让网站运行正常

#### 2、移动端常用类库及优缺点

- Zepto 库：https://www.cnblogs.com/EricZLin/p/9359288.html
- MUI

#### 3、移动端最小触控区域是多大？

44pt x 44pt

#### 4、移动端的点击事件

click 有300ms 延迟,为了实现 safari 的双击事件的设计，浏览器要知道你是不是要双击操作。

https://www.cnblogs.com/EricZLin/p/9334821.html

#### 5、主流适配方案：流式布局+viewport

- 网页内容的宽度必须和浏览器保持一致
- 默认显示的缩放比例和PC端保持一致（缩放比例1.0）
- 不允许用户自行缩放网页

```html
<meta name="viewport" content="width=device-width,initial-sacle=1.0,user-scalable=no">
```

#### 6、响应式布局

通过媒体查询可以为不同大小和尺寸的媒体定义不同的css，适合相应的设备显示；即响应式布局

```css
/* 超小屏设备(768px以下):  */
@media screen and (max-width:768px){.....}
/* 小屏设备  (768px-992px): */
@media screen and (max-width:992px) and (min-width:768px){.....}
/* 超小屏设备(992px-1200px):*/
@media screen and (max-width:1200px) and (min-width:992px){.....}
/*  超小屏设备(1200px以上):  */
@media screen and (min-width:1200px){.....}
```

#### 7、rem布局

- 使用flex的伸缩布局、使用百分比的流式布局、使用媒体查询的响应式布局，共同点就是元素只能做宽度的适配（图片除外)

- rem适配可以实现宽度和高度都能做到适配，相当于等比缩放,通过控制HTML上的字体大小去控制页面上所有以rem为单位的基准值控制的尺寸

- 配合使用less实现适配

  ```less
  @charset "UTF-8";
  // 变量模块（定义变量）
  @adapterDeviceList:750px,640px,540px,420px,320px;// 适配设备
  @psdWidth:750px;// 设计稿尺寸
  @baseFontSize:100px;// 预设基准值
  @len:length(@adapterDeviceList);// 需要适配设备的数组长度
  // 混入模块（进行适配）
  .adapterMixin(@index) when ( @index > 0){
      @media (min-width: extract(@adapterDeviceList,@index)){
        html{
          font-size: @baseFontSize / @psdWidth * extract(@adapterDeviceList,@index);
        }
      }
      .adapterMixin( @index - 1);
    }
  // 适配模块(调用)
  .adapterMixin(@len);
  ```

#### 8、flex弹性布局（css3）

可以简单的使一个元素居中（包括水平和垂直居中）栅格式系统布局

>  一个用于页面布局的全新CSS3功能，Flexbox可以把列表放在同一个方向（从上到下排列，从左到右），并让列表能延伸到占用可用的空间。较为复杂的布局还可以通过嵌套一个伸缩容器（flex container）来实现。
>  采用Flex布局的元素，称为Flex容器（flex container），简称"容器"。它的所有子元素自动成为容器成员，称为Flex项目（flex item），简称"项目"。常规布局是基于块和内联流方向，而Flex布局是基于flex-flow流可以很方便的用来做局中，能对不同屏幕大小自适应。在布局上有了比以前更加灵活的空间。

- dispaly:flex用在父元素上

- flex-direction属性决定主轴的方向（即项目的排列方向）。flex-direction: row | row-reverse | column | column-reverse;

- min/max-width/height 可限制小盒子的宽度和高度范围

```html
 <div class="box">
        <div></div>
        <div></div>
        <div></div>
</div>
```

```css
.box{
    width: 1000px;
    height: 300px;
    margin: 0 auto;
    display: flex;/* 用在父元素上，弹性布局 */
    flex-direction: row;/* 默认row，垂直用column */
}
.box div {
    background: rgb(218, 189, 189);
    margin: 1px;
    flex: 1;/* 三个盒子三等分 */
    min-width:100px;
    max-height: 500px;/* 可用于限制小盒子的宽度和高度范围 */
}
.box div:last-child {
    flex: 2;/*分成四份，最后一个盒子2份，剩下两个盒子平均剩下两份  */
}
```

#### 9、三栏式布局（两边两栏宽度固定，中间栏宽度自适应）

方案一：position（绝对定位法） center的div需要放在最后面
 绝对定位法原理将左右两边使用absolute定位，因为绝对定位使其脱离文档流，后面的center会自然流动到他们下面，然后margin属性，留出左右两边的宽度。就可以自适应了。

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>vue</title>
    <style>
        #box{
            position: relative;
        }
        .leftbox{
            position: absolute;
            left: 0;
            top: 0;
            width: 200px;
            height: 200px;
            background: #00ff00;
        }
        .rightbox{
            position: absolute;
            right: 0;
            top: 0;
            width: 300px;
            height: 200px;
            background: #ff0000;
        }
        .centerbox{
            width: 100%;
            height: 200px;
            margin-left: 0 300px 0 200px;
            background: #0000ff;
        }
    </style>
</head>
<body>
    <div id="box">
        <div class="leftbox"></div>
        <div class="rightbox"></div>
        <div class="centerbox"></div>
    </div>
</body>
</html>
```

方案二：float 自身浮动法 center的div需要放到后面
 自身浮动法的原理就是对左右使用float:left和float：right，float使左右两个元素脱离文档流，中间的正常文档流中，使用margin指定左右外边距对其进行一个定位。

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>vue</title>
    <style>
        #box{
            position: relative;
        }
        .leftbox{
            float: left;
            width: 200px;
            height: 200px;
            background: #00ff00;
        }
        .rightbox{
            float: right;
            width: 300px;
            height: 200px;
            background: #ff0000;
        }
        .centerbox{
            width: 100%;
            height: 200px;
            margin-left: 0 300px 0 200px;
            background: #0000ff;
        }
    </style>
</head>
<body>
    <div id="box">
        <div class="leftbox"></div>
        <div class="rightbox"></div>
        <div class="centerbox"></div>
    </div>
</body>
</html>
```

方案三(圣杯布局、双飞翼布局)：原理就是margin负值法。使用圣杯布局首先需要在center元素外部包含一个div,包含的div需要设置float属性使其形成一个BFC，并且这个宽度和margin的负值进行匹配

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>双飞翼布局</title>
    <style type="text/css">
        *{
            margin: 0;padding: 0;
        }
        body{
            min-width: 700px;
        }
        .sub,.main,.extra{ 
            float: left;
            min-height: 130px;
        }
        .sub{
            margin-left: -100%;
            width: 200px;
            background: red;
        }
        .extra{
            margin-left: -220px;
            width: 220px;
            background: blue;
        }
        .main{ 
            width: 100%;
        }
        .main-inner{ 
            margin-left: 200px;
            margin-right: 220px;
            min-height: 130px;
            background: green;
            word-break: break-all;
        }
        .footer{ 
            clear: both;
        }
    </style>
</head>
<body>
    <div class="main">
        <div class="main-inner"></div>
    </div> 
    <div class="sub"></div>
    <div class="extra"></div>
</body>
</html>
```

#### 10、两栏自适应（左边定宽，右边自适应）

方案一：左边设置浮动，右边宽度overflow：hidden或者width100%

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>vue</title>
    <style>
        .left{
            float: left;
            width: 200px;
            height: 200px;
            background: #00ff00;
        }
        .right{
            height: 200px;
            overflow: hidden;
            background: #ff0000;
        }
    </style>
</head>
<body>
    <div class="left"></div>
    <div class="right"></div>
</body>
</html>
```

方案二：左设置浮动，右用cacl去补宽度计算 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>vue</title>
    <style>
        *{
            padding: 0;
            margin: 0;
        }
        .left{
            float: left;
            width: 200px;
            height: 200px;
            background: #00ff00;
        }
        .right{
            height: 200px;
            float: right;
            width: calc(100vw - 200px);
            background: #ff0000;
        }
    </style>
</head>
<body>
    <div class="left"></div>
    <div class="right"></div>
</body>
</html>
```

方案三：父容器设置display：flex right部分是设置flex：1

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>vue</title>
    <style>
        *{
            padding: 0;
            margin: 0;
        }
        .left{
            width: 200px;
            height: 200px;
            background: #00ff00;
        }
        .right{
            height: 200px;
            flex: 1;
            background: #ff0000;
        }
        #box{
            display: flex;
        }
    </style>
</head>
<body>
    <div id="box">
        <div class="left"></div>
        <div class="right"></div>
    </div>
</body>
</html>
```

#### 11、box-sizing属性

兼容问题 ：首先，box-sizing属性在FireFox中存在兼容问题，所以需要使用-moz-box-sizing做一下兼容。

属性值：

- box-sizing：content-box（外加模式）

  - 这是box-sizing的默认属性值

  - 是CSS2.1中规定的宽度高度的显示行为

  - 在CSS中定义的宽度和高度就对应到元素的内容框

  - 在CSS中定义的宽度和高度之外绘制元素的内边距和边框
- box-sizing：border-box（内减模式）

  - 在CSS中微元素设定的宽度和高度就决定了元素的边框盒
  - 即为元素在设置内边距和边框是在已经设定好的宽度和高度之内进行绘制
  - CSS中设定的宽度和高度减去边框和内间距才能得到元素内容所占的实际宽度和高度
  - 在移动端中，因为宽高需要自适应，所以会使用流式布局，即宽度设置为100%，这样如果使用外加模式，当添加内边距和边框的时候，左右就会出现滚动条，如果使用内减模式的话，就可以避免这样的情况
- box-sizing：inherit

#### 12、媒体查询

- 假设你现在正用一台显示设备来阅读这篇文章，同时你也想把它投影到屏幕上，或者打印出来， 而显示设备、屏幕投影和打印等这些媒介都有自己的特点，CSS就是为文档提供在不同媒介上展示的适配方法

- 当媒体查询为真时，相关的样式表或样式规则会按照正常的级联规被应用。 当媒体查询返回假， 标签上带有媒体查询的样式表 仍将被下载 （只不过不会被应用）

  ```html
  <style> @media (min-width: 700px) and (orientation: landscape){ .sidebar { display: none; } } </style>
  ```

- 包含了一个媒体类型和至少一个使用 宽度、高度和颜色等媒体属性来限制样式表范围的表达式。 CSS3加入的媒体查询使得无需修改内容便可以使样式应用于某些特定的设备范围。

#### 13、position:fixed;在android下无效怎么处理？

fixed的元素是相对整个页面固定位置的，你在屏幕上滑动只是在移动这个所谓的viewport，原来的网页还好好的在那，fixed的内容也没有变过位置， 所以说并不是iOS不支持fixed，只是fixed的元素不是相对手机屏幕固定的。

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no"/>
```

#### 14、如果需要手动写动画，你认为最小时间间隔是多久，为什么？

多数显示器默认频率是60Hz，即1秒刷新60次，所以理论上最小间隔为1/60＊1000ms ＝ 16.7ms

## 七、Node.js

#### 1、对 Node 的优点和缺点提出了自己的看法：
优点：因为 Node 是基于事件驱动和无阻塞的，所以非常适合处理并发请求，因此构建在 Node 上的代理服务器相比其他技术实现（如 Ruby）的服务器表现要好得多。此外，与 Node 代理服务器交互的客户端代码是由 javascript 语言编写的，因此客户端和服务器端都用同一种语言编写，这是非常美妙的事情。

缺点：Node 是一个相对新的开源项目，所以不太稳定，它总是一直在变

#### 2、Node.js 的适用场景？
- 实时应用：如在线聊天，实时通知推送等等（如 socket.io）
- 分布式应用：通过高效的并行 I/O 使用已有的数据
- 工具类应用：海量的工具，小到前端压缩部署（如 grunt），大到桌面图形界面应用程序
- 游戏类应用：游戏领域对实时和并发有很高的要求（如网易的 pomelo 框架）
- 利用稳定接口提升 Web 渲染能力
- 前后端编程语言环境统一：前端开发人员可以非常快速地切入到服务器端的开发（如著名的纯 Javascript 全栈式 MEAN 架构）

#### 3、node相关概念

- route 路由

- middleware 中间件

- cluster 集群，Node.js给我们提供了cluster模块，它可以生成多个工作线程来共享同一个TCP连接

- nodemon是一个基于nodejs开发的一个第三方命令行工具，通过nodemon.js启动的服务,则会监视文件变化,当文件发生变化的时候,会自动重启服务器

- pm2 可以使node服务在后台运行（类似于linux的nohup），另外它们可以在服务因异常或其他原因被杀掉后进行自动重启

- rendering 渲染

#### 4、前端路由

路由是根据不同的 url 地址展示不同的内容或页面，前端路由就是把不同路由对应不同的内容或页面的任务交给前端来做，之前是通过服务端根据 url 的不同返回不同的页面实现的。

在单页面应用，大部分页面结构不变，只改变部分内容的使用前端路由

优点：用户体验好，不需要每次都从服务器全部获取，快速展现给用户

缺点：使用浏览器的前进，后退键的时候会重新发送请求，没有合理地利用缓存，单页面无法记住之前滚动的位置，无法在前进，后退的时候记住滚动的位置

#### 5、Node 事件循环，js 事件循环差异

Node.js 的事件循环分为6个阶段
浏览器和Node 环境下，microtask 任务队列的执行时机不同
Node.js中，microtask 在事件循环的各个阶段之间执行
浏览器端，microtask 在事件循环的 macrotask 执行完之后执行
递归的调用process.nextTick()会导致I/O starving，官方推荐使用setImmediate()

####  6、关于前后端分离

- 前端：负责View和Controller层。
- 后端：只负责Model层，业务处理/数据等
- 后端以开发接口为主，不再参与页面开发，统一以接口形式返回，前端通过js渲染数据以及处理逻辑
- WEB 前后端分离三个最大的优点在于：
  - 最大的好处就是前端JS可以做很大部分的数据处理工作，对服务器的压力减小到最小
  - 后台错误不会直接反映到前台，错误接秒较为友好
  - 由于后台是很难去探知前台页面的分布情况，而这又是JS的强项，而JS又是无法独立和服务器进行通讯的。所以单单用后台去控制整体页面，又或者只靠JS完成效果，都会难度加大，前后台各尽其职可以最大程度的减少开发难度

#### 7、如何判断当前脚本运行在浏览器还是node环境中？

```js
 this === window ? 'browser' : 'node';

  通过判断Global对象是否为window，如果不为window，当前脚本没有运行在浏览器中
```

## 八、其他

#### 1、你所了解到的Web攻击技术

- xss 跨站脚本攻击

  - 主要是前端层面的，用户在输入层面插入攻击脚本，改变页面的显示，或则窃取网站 cookie，
  - 预防方法：
    - 不相信用户的所有操作，对用户输入进行一个转义，
    - 不允许 js 对 cookie 的读，httponly 设置bool值，为true,只能在服务端获取,JavaScript无法操作，可以防止xxs脚本攻击

- SQL注入攻击：

  - 主要是就是通过把SQL命令插入到`Web`表单提交或输入域名或页面请求的查询字符串，最终达到欺骗服务器执行恶意的SQL命令，比如select * from test where username="wuxu" or 1=1，这样会使用户跳过密码直接登录，
  - 具体解决方案：
    - 特殊字符过滤，不要用拼接字符串的方法来凑sql语句
    - 对sql语句进行预编译，比如java的preparedstatement
    - 关闭错误信息，攻击者可能会通过不断的尝试来得到数据库的一些信息，所以关闭错误信息变得重要起来
    - 客户端对数据进行加密，使原来传进来的参数因为加密而被过滤掉
    - 控制数据库的权限，比如只能select，不能insert，防止攻击者通过select * from test ；drop tables这种操作

- csrf 跨站请求伪造，

  - 攻击者盗用了你的身份，以你的名义发送恶意请求

  - 具体方案：
    - 验证referer字段，这个字段主要是反映了访问某个网页只能有referer发起请求，所以通过referer验证，可以抵御一部分csrf攻击。
    - 在请求地址中加token验证，攻击者发送恶意请求时，通过token验证来进行身份验证，而token必须是一个攻击者猜不到的，很难去模拟出来的，具体来说可以放在表单的hidden字段中。
    - 在htttp请求头中定义字段，其实就是将2中说得token字段放入请求头，解决了每次在请求头中加入token的不便，同时在其也不会记录在地址栏里，降低了token泄露的风险

- os命令注入攻击：

  - 系统提供命令执行类函数主要方便处理相关应用场景的功能.而当不合理的使用这类函数，同时调用的变量未考虑安全因素，就会执行恶意的命令调用，被攻击利用。主要原因是服务端在调用系统命令时采用的是字符串连接的方式，比如a="a.txt;rm -rf *",system("rm -rf {$a}")，这会给服务端带去惨痛的代价，
  - 具体解决方案：
    - 在程序开发时少用系统命令，执行命令的参数尽量不要从外部获取。
    - 参数特殊字符过滤

- 邮件首部注入攻击：

  - 它允许恶意攻击者注入任何邮件头字段,BCC、CC、主题等,它允许黑客通过注入手段从受害者的邮件服务器发送垃圾邮件。主要是利用邮件系统传参的bug来进行攻击，
  - 解决方法：
    - 使用正则表达式来过滤用用户提交的数据。例如,我们可以在输入字符串中搜索(r 或 n)。
    - 永远不要信任用户的输入。
    - 使用外部组建和库

- 目录遍历攻击：

  - 目录遍历是Http所存在的一个安全漏洞，它使得攻击者能够访问受限制的目录，并在Web服务器的根目录以外执行命令。比如　`http://test.webarticles.com/show.asp?view=../../../../../Windows/system.ini`，这种url会返回／windows／system.ini给用户，所以服务器上的重要文件就会遭到泄漏，
  - 解决方法：根目录访问，现在主流服务器，比如nginx，都会有www根目录，是网站的根目录，所以用户只能访问该根目录下的文件，不能访问其他目录下的文件，从而实现了权限控制。而目录遍历并不是一个漏洞，而是服务器的一个功能，而因为管理员的疏忽从而变成了漏洞

- 远程目录包含攻击，

  - 原理就是注入一段用户能控制的脚本或代码，并让服务端执行。比如php中的include($filename)，而此filename由用户传入，用户即可传入一段恶意脚本，从而对服务其造成伤害，
  - 解决方法：当采用文件包含函数的时候，不应动态传入，而应该有具体的文件名，如果动态传入，要保证动态变量不被用户所控制

- 会话劫持：

  - 这是一种通过获取用户Session ID后，使用该Session ID登录目标账号的攻击方法，此时攻击者实际上是使用了目标账户的有效Session。会话劫持的第一步是取得一个合法的会话标识来伪装成合法用户，因此需要保证会话标识不被泄漏，通俗一点就是用户在登录时，唯一标示用户身份的session id被劫持，使得攻击者可以用这个session id来进行登录后操作，而攻击者主要是通过 窃取：使用网络嗅探，XSS攻击等方法获得。
  - 解决办法：
    - 第一种方式网络嗅探，我们可以通过ssl加密，也就是https来对报文进行加密，从而防止报文被截获
    - 第二种方式xss攻击，方式在第一种已经给出，不再赘述。此外通过就是设置token验证。关闭透明化Session ID。透明化Session ID指当浏览器中的Http请求没有使用Cookie来存放Session ID时，Session ID则使用URL来传递

#### 3、如何测试前端代码? 

测试定义成：是一段检测你的应用代码（也叫“ 生产代码 ”）是否按预期执行的代码。有些人称之为 TDD（Test-Driven Development 或者 Test-Driven Design），但是 TDD 是一种特定的测试方法，它先写测试，然后用测试来驱动产品的设计和实现。

Unit Test 单元测试，代码以单元为单位进行测试。单元可以是一个函数、一个模块、一个包或者一个类，甚至是一个对象。在 JavaScript 中，通常是以类或者模块作为一个单元

mocha, sinon,jasmin, qUnit.测试框架

#### 4、Web 模板引擎

Web 模板引擎是为了使用户界面与业务数据（内容）分离而产生的，实际上就是一个API，目的是更容易的将数据渲染到HTML中

- [artTemplate](https://aui.github.io/art-template/zh-cn/index.html)，它采用作用域预声明的技术来优化模板渲染速度，同时支持 NodeJS 和浏览器

- Mustache 是一个 logic-less （轻逻辑）模板解析引擎，它的优势在于可以应用在Javascript、PHP、Python、Perl 等多种编程语言中

- Underscore 封装了常用的 JavaScript 对象操作方法，用于提高开发效率

- Handlebars 是 JavaScript 一个语义模板库，通过对 view 和 data 的分离来快速构建Web 模板

#### 5、模块化开发怎么做？

- 概念：模块化开发是为了解决多人合作项目时，使用同一个变量名等造成的冲突，以及项目依赖文件等引用顺序。模块化开发使代码耦合度降低，以最少的模块、零部件满足更多的个性需求，更方便地使用别人的代码。

- 模块化开发分为服务端规范和浏览器规范。
  - 服务器端规范：CommonJS ：nodejs
  - 浏览器端规范：
    - AMD：RequireJS，对于依赖提前执行，依赖前置，API一个当多个用，模块加载完成后马上执行，用户体验好
    - CMD：SeaJS，对于依赖延后执行，依赖就近，API严格区分，职责单一，模块加载完成后没有立即执行而是等到require再执行，性能好

- 使用模块式开发：
  - 页面A引入js1，调用js1中的方法。js1引入js2，调用js2中module.export的方法，以此类推
  - AMD和CMD
    - 需要使用export和import，但是浏览器没有完全支持，因此需要使用babel。实现这个转换到有browserify和webpack（gulp+browserify , node+webpack）
    - Browserify能够转换export、import是因为将所有模块放入一个数组，id为模块编号，source是模块的源码，deps是模块的依赖。
    - 由于require是同步的，必须等上行代码加载完成后才能执行，服务器端不是问题，浏览器端需要使用异步，产生了AMD。因此，CommonJS主要是为了js再后端的表现制定的，AMD主要为前端js制定规范
    - AMD的require需要两个参数，module和callback。require([module],callback)
    - RequireJS的诞生是为了实现js文件异步加载，避免网页失去响应，与管理模块间的依赖性。
  - CommonJS规范：
    - 如果在a.js使用b.js，一定要在a.js中require（'b.js'），在b.js中提供module.exports
    - CommonJS定义的模块分为:{模块引用(require)} {模块定义(exports)} {模块标识(module)}
    - 浏览器不兼容CommonJS是因为缺少module 、exports、require、global四个变量
    - Browserify能够转换export、import是因为将所有模块放入一个数组，id为模块编号，source是模块的源码，deps是模块的依赖。
  - CMD：define(function(require,exports,module){...});

#### 6、AMD和CMD规范区别

- 理解这两种规范的差异，主要通过 requirejs 与 seajs 的对比，理解模块的定义与引用方式
  的差异以及这两种规范的设计原则
  参考链接 1：https://www.zhihu.com/question/20351507/answer/14859415
  参考链接 2：https://github.com/seajs/seajs/issues/277

- requireJS 的核心原理：是 js 的加载模块，通过正则匹配模块以及模块的依赖关系，保证文件加载的先后顺序，根据文件的路径对加载过的文件做了缓存

- 区别：
  - 对于依赖的模块，AMD 是提前执行，CMD 是延迟执行。不过 RequireJS 从 2.0 开始，也改成可以延迟执行（根据写法不同，处理方式不同）。CMD 推崇 as lazy as possible.
  - CMD 推崇依赖就近，AMD 推崇依赖前置。
  - AMD 的 API 默认是一个当多个用，CMD 的 API 严格区分，推崇职责单一。比如 AMD 里，require 分全局 require 和局部 require，都叫 require。CMD 里，没有全局 require，而是根据模块系统的完备性，提供 seajs.use 来实现模块系统的加载启动。CMD 里，每个API 都简单纯粹

#### 7、如何编写高性能的 Javascript？

- 使用 DocumentFragment 优化多次 append
- 通过模板元素 clone ，替代 createElement
- 使用一次 innerHTML 赋值代替构建 dom 元素
- 使用 firstChild 和 nextSibling 代替 childNodes 遍历 dom 元素
- 使用 Array 做为 StringBuffer ，代替字符串拼接的操作
- 将循环控制量保存到局部变量
- 顺序无关的遍历时，用 while 替代 for
- 将条件分支，按可能性顺序从高到低排列
- 在同一条件子的多（ >2 ）条件分支时，使用 switch 优于 if
- 使用三目运算符替代条件分支
- 需要不断执行的时候，优先考虑使用 setInterval

#### 8、JSON 的了解

- JSON(JavaScript Object Notation) 是一种轻量级的数据交换格式。它是基于 JavaScript的一个子集。数据格式简单, 易于读写, 占用带宽小{'age':'12', 'name':'back'}
- Json有对象和数组两种格式，对象调用key,数组调用通过索引值。json转字符串使用JSON.stringify，字符串转对象用JSON.parse
- IE6\7对json的兼容性问题（“JSON”未定义），使用https://github.com/douglascrockford/JSON-js (josn2.js)

#### 9、WEB 应用从服务器主动推送 Data 到客户端有那些方式？

- Javascript数据推送：都是客户端通过JavaScript操作不断的向服务器发起请求。
- commet：基于HTTP长连接的服务器推送技术，能使服务器实时地将更新的信息传送到客户端，而无须客户端发出请求
  - 长轮询 (long polling) 是在打开一条连接以后保持，等待服务器推送来数据再关闭，可以采用HTTP长轮询和XHR长轮询两种方式
  - HTTP 和JSONP方式的长轮询：把 script 标签附加到页面上以让脚本执行。服务器会挂起连接直到有事件发生，接着把脚本内容发送回浏览器，然后重新打开另一个 script 标签来获取下一个事件，从而实现长轮询的模型
- XHR长轮询：客户端打开一个到服务器端的 AJAX 请求然后等待响应；服务器端需要一些特定的功能来允许请求被挂起，只要一有事件发生，服务器端就会在挂起的请求中送回响应并关闭该请求。客户端 JavaScript 响应处理函数会在处理完服务器返回的信息后，再次发出请求，重新建立连接；如此循环。现在浏览器已经支持CROS的跨域方式请求
- iframe是很早就存在的一种 HTML 标记， 通过在 HTML 页面里嵌入一个隐蔵帧，然后将这个隐蔵帧的 SRC 属性设为对一个长连接的请求，服务器端就能源源不断地往客户端输入数据
- WebSocket是HTML5开始提供的一种在单个 TCP 连接上进行全双工通讯的协议。WebSocket通讯协议于2011年被IETF定为标准RFC 6455，WebSocketAPI被W3C定为标准。在WebSocket API中，浏览器和服务器只需要做一个握手的动作，然后，浏览器和服务器之间就形成了一条快速通道。两者之间就直接可以数据互相传送。

#### 10、如何实现一个组件封装?

组件封装的目的是为了重用，提高开发效率和代码质量

组件封装的优点：低耦合，单一职责，可复用性，可维护性

实现：

- js前端组件的封装方法
  - 定义一个类
  - 类中增加一个方法
  - body中定义一个dom节点
  - 脚本中把dom节点和类定义结合起来 , 实现特定的组件功能
- vue组件封装
  - 建立组件的模板，先把架子搭起来，写写样式，考虑你的组件的基本逻辑
  - 然后在引用得组件中 用import引入组件
  - 通过component定义组件名称
  - 在把组件以标签的形式写出来。
- react组件封装
  - 创建一个react文件 , 搭建模板
  - 把组件内的内容写清楚
  - 使用export 把组件曝光
  - 使用import把组件导入

####  11、线程、进程、多线程

- 进程：进程是一个具有一定独立功能的程序关于某个数据集合的一次运行活动。它是操作系统动态执行的基本单元，在传统的操作系统中，进程既是基本的分配单元，也是基本的执行单元。

- 程序：程序是指令和数据的有序集合，其本身没有任何运行的含义，是一个静态的概念。而进程则是在处理机上的一次执行过程，它是一个动态的概念。这个不难理解，其实进程是包含程序的，进程的执行离不开程序，进程中的文本区域就是代码区，也就是程序。

- 线程：通常在一个进程中可以包含若干个线程，当然一个进程中至少有一个线程，不然没有存在的意义。线程可以利用进程所拥有的资源，在引入线程的操作系统中，通常都是把进程作为分配资源的基本单位，而把线程作为独立运行和独立调度的基本单位，由于线程比进程更小，基本上不拥有系统资源，故对它的调度所付出的开销就会小得多，能更高效的提高系统多个程序间并发执行的程度。

- 多线程：在一个程序中，这些独立运行的程序片段叫作“线程”（Thread），利用它编程的概念就叫作“多线程处理”。多线程是为了同步完成多项任务，不是为了提高运行效率，而是为了提高资源使用效率来提高系统的效率。线程是在同一时间需要完成多项任务的时候实现的。

- 区别：

  - 一个程序至少有一个进程,一个进程至少有一个线程

  - 线程是最小的执行单元，进程是最小的资源管理单元
  - 进程在执行过程中拥有独立的内存单元，而多个线程共享内存，从而极大地提高了程序的运行效率
  - 每个独立的线程有一个程序运行的入口、顺序执行序列和程序的出口。但是线程不能够独立执行，必须依存在应用程序中，由应用程序提供多个线程执行控制
  - 多线程的意义在于一个应用程序中，有多个执行部分可以同时执行。但操作系统并没有将多个线程看做多个独立的应用，来实现进程的调度和管理以及资源分配

#### 12、负载均衡

概念：当系统面临大量用户访问，负载过高的时候，通常会使用增加服务器数量来进行横向扩展，使用集群和负载均衡提高整个系统的处理能力

实现：

- http重定向：当http代理（比如浏览器）向web服务器请求某个URL后，web服务器可以通过http响应头信息中的Location标记来返回一个新的URL。这意味着HTTP代理需要继续请求这个新的URL，完成自动跳转。
- DNS负载均衡：DNS负责提供域名解析服务，当访问某个站点时，实际上首先需要通过该站点域名的DNS服务器来获取域名指向的IP地址，在这一过程中，DNS服务器完成了域名到IP地址的映射，同样，这样映射也可以是一对多的，这时候，DNS服务器便充当了负载均衡调度器，它就像http重定向转换策略一样，将用户的请求分散到多台服务器上，但是它的实现机制完全不同。
- 反向代理负载均衡：相比前面的HTTP重定向和DNS解析，反向代理的调度器扮演的是用户和实际服务器中间人的角色，任何对于实际服务器的HTTP请求都必须经过调度器，调度器必须等待实际服务器的HTTP响应，并将它反馈给用户（前两种方式不需要经过调度反馈，是实际服务器直接发送给用户）

#### 13、babel把ES6转成ES5或者ES3之类的原理是什么？

它就是个编译器，输入语言是ES6+，编译目标语言是ES5

babel 官方工作原理:

- 解析：将代码字符串解析成抽象语法树AST(abstract syntax tree)
- 变换：对抽象语法树进行变换操作
- 再建：根据变换后的抽象语法树再生成代码字符串

具体过程如下：以es6转es5为例

- es6代码的输入
- babelon(js的词法解析器)进行解析
- 得到AST
- plugin用babel-traverse对AST树进行遍历
- 得到新的AST树 
- 使用babel-genertor通过AST树生成es5代码

#### 15、webpack的一些原理和机制，怎么实现的？

- webpack是一个打包模块化js的工具，可以通过loader转换文件，通过plugin扩展功能

- 核心概念：

  - `entry` 一个可执行模块或库的入口文件。
  - `chunk` 多个文件组成的一个代码块，例如把一个可执行模块和它所有依赖的模块组合和一个 `chunk` 这体现了webpack的打包机制。
  - `loader` 文件转换器，例如把es6转换为es5，scss转换为css。
  - `plugin` 插件，用于扩展webpack的功能，在webpack构建生命周期的节点上加入扩展hook为webpack加入功能。

- 流程：

  - 解析webpack配置参数，合并从shell传入和webpack.config.js文件里配置的参数，生产最后的配置结果。

  - 注册所有配置的插件，好让插件监听webpack构建生命周期的事件节点，以做出对应的反应。

  - 从配置的entry入口文件开始解析文件构建AST语法树，找出每个文件所依赖的文件，递归下去。

  - 在解析文件递归的过程中根据文件类型和loader配置找出合适的loader用来对文件进行转换。

  - 递归完后得到每个文件的最终结果，根据entry配置生成代码块chunk。

  - 输出所有chunk到文件系统

- 示例：

  ```js
  // 该文件其实最终是要在node环境下执行的
  const path = require('path')
  const htmlWebpackPlugin = require('html-webpack-plugin')
  
  // 导出一个具有特殊属性配置的对象
  module.exports = {
      entry:'./src/main.js',/* 入口文件模块路径 */
      output:{
          path:path.join(__dirname,'./dist/'),/* 出口文件模块所属目录，必须是一个绝对路径 */
          filename:'bundle.js'/* 打包的结果文件名称 */
      },
      plugins:[
          // 该插件可以把index.html打包到bundle.js文件所属目录，跟着bundle走
          // 同时也会自动在index.html中注入script引用链接，并且引用的资源名称
          new htmlWebpackPlugin({
              template:'./index.html'
          })
      ],
      module:{
          rules:[
              {
                  test:/\.css$/,
                  use:[
                      'style-loader',
                      'css-loader'
                  ]
              },
              {
                  test:/(jpg|png|gif|svg)$/,
                  use:[
                      'file-loader'
                  ]
              }
          ]
      }
  }
  ```

#### 16、ES6新特性

- **箭头操作符** inputs=>outputs: 操作符左边是输入的参数，而右边则是进行的操作以及返回的值

- **支持类**, 引入了**class**关键字. ES6提供的类实际上就是JS原型模式的包装

- **增强的对象字面量**
  - 可以在对象字面量中**定义原型  __proto__**: xxx  //设置其原型为xxx,相当于继承xxx
  - 定义方法可以**不用function**关键字
  - 直接调用父类方法

- **字符串模板**: ES6中允许使用反引号 ` 来创建字符串，此种方法创建的字符串里面可以包含由美元符号加花括号包裹的变量${vraible}。

- **自动解析数组或对象中的值**。比如若一个函数要返回多个值，常规的做法是返回一个对象，将每个值做为这个对象的属性返回。但在ES6中，利用解构这一特性，可以直接返回一个数组，然后数组中的值会自动被解析到对应接收该值的变量中。

- **默认参数值:** 现在可以在定义函数的时候指定参数的默认值了，而不用像以前那样通过逻辑或操作符来达到目的了。

- **不定参数**是在函数中使用命名参数同时接收不定数量的未命名参数。在以前的JavaScript代码中我们可以通过arguments变量来达到这一目的。不定参数的格式是三个句点后跟代表所有不定参数的变量名。比如下面这个例子中，…x代表了所有传入add函数的参数。

- **拓展参数**则是另一种形式的语法糖，它允许传递数组或者类数组直接做为函数的参数而不用通过apply。

- **let和const关键字:** 可以把let看成var，只是它定义的变量被限定在了特定范围内才能使用，而离开这个范围则无效。const则很直观，用来定义常量，即无法被更改值的变量。

- **for of值遍历** 每次循环它提供的不是序号而是值。

- **iterator, generator**

- **模块**：导出 import，导出export

- **Map, Set, WeakMap, WeakSet**数据结构

  - Set类似于数组，但是成员的值都是唯一的，没有重复的值。
  - WeakSet 结构与 Set 类似，也是不重复的值的集合。与 Set 有两个区别：
    - WeakSet 的成员只能是对象，而不能是其他类型的值，
    - WeakSet 中的对象都是弱引用，即垃圾回收机制不考虑 WeakSet 对该对象的引用
  - Map 类似于对象，也是键值对的集合，但是“键”的范围不限于字符串，各种类型的值（包括对象）都可以当作键
  - `WeakMap`结构与`Map`结构类似，也是用于生成键值对的集合，区别在于：
    - `weakMap`只接受对象作为键名（`null`除外），不接受其他类型的值作为键名
    - `WeakMap`的键名所指向的对象，不计入垃圾回收机制

- **Proxy**可以监听对象身上发生了什么事情，并在这些事情发生后执行一些相应的操作。一下子让我们对一个对象有了很强的追踪能力，同时在数据绑定方面也很有用处。

- **Symbols** Symbol 通过调用symbol函数产生，它接收一个可选的名字参数，该函数返回的symbol是唯一的。之后就可以用这个返回值做为对象的键了。Symbol还可以用来创建私有属性，外部无法直接访问由symbol做为键的属性值。

- **Math, Number, String, Object的新API**
  - Number.parseInt()、Number.isInteger()
  - Math.trunc、Math.sign、Math.cbrt
  - str.includes()、str.endsWith()、str.includes()、str.repeat()
  - Object.is()、Object.assign（）、Object.keys（）、Object.values()、Object.entries（）

- **promise对象**、 **async函数**

  - Promise 是异步编程的一种解决方案

  ```js
  let promise = new Promise(function(resolve, reject) {
    console.log('Promise');
    resolve();
  });
  
  promise.then(function() {
    console.log('resolved.');
  });
  
  console.log('Hi!');
  
  // Promise
  // Hi!
  // resolved
  ```

  - 在async函数内部使用await的方式来操作异步API，awit是一种新的语法，只能在asysc函数中使用，await一般是在其后跟一个promise操作API

  ```js
  // a.txt 的内容是 ‘hello aaa’
  
  // 在node中提供了一个一个根据函数，专门用来把一些callback形式的API包装成promise的方法
  var util = require('util')
  var fs = require('fs') 
  var readFile = util.promisify(fs.readFile)
  
  async function read() {
      const a = 1
      const b = await readFile('./data/a.txt','utf8')
      const c = 2
      console.log(a,b,c)
  }
  console.log(3)
  read()
  console.log(4)
  ```

参考[ES6新特性概览](http://www.cnblogs.com/Wayou/p/es6_new_features.html)

#### 16、web开发中会话跟踪的方法有哪些？

- 概念：Web服务器使用Http协议。Http是无状态协议。Http的web服务器不能保持与客户端的关联。会话(session)定义为在一段时间内，单一客户与web服务器之间的一系列的交互。在一个会话中，跟踪请求之间的数据成为会话跟踪。当用户发出请求时，服务器就会做出响应，客户端与服务器之间的联系是离散的、非连续的。当用户在同一网站的多个页面之间转换时，根本无法确定是否是同一个客户，会话跟踪技术就可以解决这个问题。当一个客户在多个页面间切换时，服务器会保存该用户的信息

- 方法：

  - Cookies

    > 是最常用的跟踪用户会话的方式。Cookies是一种由服务器发送给客户端的片段信息，存储在客户端的内存或者硬盘上，在客户随后对该服务器的请求中发回它。其实主要就是把服务器为客户端分配的session ID保存在Cookies中，每次发送请求时把Cookies附加到请求对象中一起发过去，服务器得到这个唯一的session ID，从而可以唯一的标识一个客户端

  - SSL会话

    > 安全套接字层，是一种运行在TCP/IP之上和像HTTP这种应用层协议之下的加密技术。SSL是在HTTPS协议中使用的加密技术。SSL可以让采用SSL的服务器认证采用SSL的客户端，并且在客户端和服务器之间保持一种加密了连接，在建立了加密连接的过程中，客户端和服务器都可以产生一种名为“会话密钥”的东西，它是一种用于加密和解密的对称密钥。基于HTTPS协议的服务器可以使用这个客户端的对称密钥来建立会话.

  - url重写

    > 如果客户端禁用了Cookies，那么就只能用URL重写机制了。就是在URL中附加标识客户端的session 
    > ID，web容器解析URL，取出session ID，根据这个session ID将请求与特定的session关联起来。 
    > 注意如果采用了URL重写，那么代码里面的所有url都要经过编码，response.sendRedirect(url)中的urlresponse.encodeRedirectURL(url)编码，其他的用response.encodeURL(url)来编码

  - 隐藏input

    > 是一种最简单的方式，将字段隐藏在HTML表单中，但不在客户端显示。比如在第一张页面中输入用户名和密码登陆，服务器生成响应返回第二张页面。当第二张页面提交时可能仍然需要知道来自第一张页面中的用户名。 
    > 那么就可以通过隐藏表单域来实现这一连续的过程。当第一张页面提交后，服务器端作出响应返回第二张页面，此页面中用隐藏域记录了来自登陆时的用户名。通俗说就是当服务器回发给客户端的响应中，就同时把用户名再次回发到客户端，用隐藏域隐藏起来，是不可见的。当第二张页面提交时，此隐藏域中的用户名一并随表单提交。这样服务器就仍然可以判断此用户是否与以前的用户相同。于是，再次处理完结果后继续将响应回发给客户端，且此响应中也仍然包含了用户名，在客户端中仍然用隐藏域将这一信息隐藏。这样就完成了一个连续请求的动作，但是对于用户，这是不可见的。

  - ip地址

#### 17、PNG,GIF,JPG的区别及如何选？

**GIF**:

- 8位像素，256色
- 无损压缩
- 支持简单动画
- 支持boolean透明
- 适合简单动画

**JPEG**：

- 颜色限于256
- 有损压缩
- 可控制压缩质量
- 不支持透明
- 适合照片

**PNG**：

- 有PNG8和truecolor PNG
- PNG8类似GIF颜色上限为256，文件小，支持alpha透明度，无动画
- 适合图标、背景、按钮

#### 18、Webpack热更新实现原理?

热更新：热更新就是动态下发代码，它可以使开发者在不发布新版本的情况下，修复 BUG 和发布功能。

浏览器的网页通过websocket协议与服务器建立起一个长连接，当服务器的css/js/html进行了修改的时候，服务器会向前端发送一个更新的消息，如果是css或者html发生了改变，网页执行js直接操作dom，局部刷新，如果是js发生了改变，只好刷新整个页面。

- Webpack编译期，为需要热更新的 entry 注入热更新代码(EventSource通信)
- 页面首次打开后，服务端与客户端通过 EventSource 建立通信渠道，把下一次的 hash 返回前端
- 客户端获取到hash，这个hash将作为下一次请求服务端 hot-update.js 和 hot-update.json的hash
- 修改页面代码后，Webpack 监听到文件修改后，开始编译，编译完成后，发送 build 消息给客户端
- 客户端获取到hash，成功后客户端构造hot-update.js script链接，然后插入主文档
- hot-update.js 插入成功后，执行hotAPI 的 createRecord 和 reload方法，获取到 Vue 组件的 render方法，重新 render 组件， 继而实现 UI 无刷新更新。

#### 19、css-loader的原理？

Css-loader:将js中的css加载进模块，处理css中路径引用等问题

里面的每一个对象都用正则表达式，对应着一种配对方案。loader加载器用于将不同的文件加载到js文件中

#### 20、Vue组件的书写方式

**第一种**使用script标签

```html
<!DOCTYPE html>
<html>
  <body>
    <p id="app">
      <my-component></my-component>
    </p>
    <-- 注意：使用<script>标签时，type指定为text/x-template，意在告诉浏览器这不是一段js脚本，浏览器在解析HTML文档时会忽略<script>标签内定义的内容。-->
    <script type="text/x-template" id="myComponent">//注意 type 和id。
      <p>This is a component!</p>
    </script>
  </body>
  <script src="js/vue.js"></script>
  <script>
    //全局注册组件
    Vue.component('my-component',{
      template: '#myComponent'
    })
    new Vue({
      el: '#app'
    })
  </script>
</html>
```

**第二种**使用template标签

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title></title>
  </head>
  <body>
    <p id="app">
      <my-component></my-component>
    </p>
    <template id="myComponent">
      <p>This is a component!</p>
    </template>
  </body>
  <script src="js/vue.js"></script>
  <script>
    Vue.component('my-component',{
      template: '#myComponent'
    })
    new Vue({
      el: '#app'
    })
  </script>
</html>
```

**第三种** 单文件组件:创建.vue后缀的文件,组件Hello.vue，放到components文件夹中

```html
<template>
 <p class="hello">
  <h1>{{ msg }}</h1>
 </p>
</template>
<script>
export default {
 name: 'hello',
 data () {
  return {
   msg: '欢迎！'
  }
 }
}
</script>
```

```vue
<!-- 展示模板 -->
<template>
 <p id="app">
  <img src="./assets/logo.png">
  <hello></hello>
 </p>
</template>
<script>
// 导入组件
import Hello from './components/Hello'
export default {
 name: 'app',
 components: {
  Hello
 }
}
</script>
<!-- 样式代码 -->
<style>
#app {
 font-family: 'Avenir', Helvetica, Arial, sans-serif;
 -webkit-font-smoothing: antialiased;
 -moz-osx-font-smoothing: grayscale;
 text-align: center;
 color: #2c3e50;
 margin-top: 60px;
}
</style>
```

#### 21、vue的生命周期

```html
<div id="app">
        <h1>{{message}}</h1>
    </div>
    <script src="node_modules/vue/dist/vue.js"></script>
    <script>
        new Vue({
            el:'#app',
            data:{
                message:'hello vue'
            },
            // 在实例初始化之后调用，这里拿不到el,data数据。
            beforeCreate(){
                console.log('beforeCreate',this.$el,this.$data);
            },
            // 在实例化创建之后，这里可以访问data中的数据了。适用于开发请求修改data数据。这里还没有被挂载，还拿不到el
            created(){
                console.log('created',this.$el,this.$data);
            },
            // 在挂载元素开始之前被调用，还没有渲染DOM。
            beforeMount(){
                console.log('beforeMount',this.$el,this.$data);
            },
            // 挂载渲染已经完成，DOM数据已经完成更新
            mounted(){
                console.log('mounted',this.$el,this.$data);
            },
            // 数据更新时调用，DOM还没有得到更新
            beforeUpdate(){
                console.log('beforeUpdate',this.$el,this.$data);
            },
            // 数据更新之后调用，DOM已经得到更新
            updated(){
                console.log('updated',this.$el,this.$data);
            },
            // keep-alive(动态组件) 组件激活时调用。
            activated(){
                console.log('activated',this.$el,this.$data);
            },
            // keep-alive(动态组件) 组件停用时调用。
            deactivated(){
                console.log('deactivated',this.$el,this.$data);
            },
            // 实例销毁之前调用。在这一步，实例仍然完全可用。
            beforeDestroy(){
                console.log('beforeDestroy',this.$el,this.$data);
            },
            // Vue 实例销毁后调用。调用后，Vue 实例指示的所有东西都会解绑定，所有的事件监听器会被移除，所有的子实例也会被销毁。
            destroyed(){
                console.log('destroyed',this.$el,this.$data);
            },
            // 钩子级别的错误捕获，捕获组件中发生错误的
            errorCaptured(){
                console.log('errorCaptured',this.$el,this.$data);
            },
        });
    </script>
```

#### 23、**react和vue有哪些不同，说说你对这两个框架的看法**

相同点

- ·都支持服务器端渲染

- ·都有Virtual DOM,组件化开发,通过props参数进行父子组件数据的传递,都实现webComponent规范

-  数据驱动视图

- ·都有支持native的方案,React的React native,Vue的weex


不同点

- React严格上只针对MVC的view层,Vue则是MVVM模式

- virtual DOM不一样,vue会跟踪每一个组件的依赖关系,不需要重新渲染整个组件树.而对于React而言,每当应用的状态被改变时,全部组件都会重新渲染,所以react中会需要shouldComponentUpdate这个生命周期函数方法来进行控制

- 组件写法不一样, React推荐的做法是 JSX + inline style, 也就是把HTML和CSS全都写进JavaScript了,即'all in js'; Vue推荐的做法是webpack+vue-loader的单文件组件格式,即html,css,jd写在同一个文件;

- 数据绑定: vue实现了数据的双向绑定,react数据流动是单向的

- state对象在react应用中不可变的,需要使用setState方法更新状态;在vue中,state对象不是必须的,数据由data属性在vue对象中管理


#### 24、**MVVM、MVC、MVP原理**

- 常见架构方式：
  - MVC
    - 视图（View），指用户界面；控制器（Controller），指业务逻辑；模型（Model），指数据保存
    - View传送指令到Controller，Controller完成业务逻辑后，要求Model改变状态，Model将新的数据发送到View，用户得到反馈
  - MVP
    - 将 Controller 改名为 Presenter，同时改变了通信方向
    - 各部分之间的通信，都是双向的，View与Model不发生关系，都通过Presenter传递，View非常薄，不部署任何业务逻辑，称为被动视图，即没有任何的主动性，而Presenter非常厚，所有的逻辑都部署在那里
  - MVVM
    - M，即Model 业务数据模型，指操作数据的类；V，即View 视图界面，HTML用户界面；VM，ViewModel 视图数据模型，指驱动视图改变的data数据。核心思想就是数据驱动视图。
    - 将Presenter改为ViewModel ，基本上与MVP模式保持一致，唯一的区别是，它采用双向绑定，View的变动，自动反映在ViewModel ，反之亦然
- MVVM的优点
  - 低耦合。视图（View）可以独立于Model变化和修改，一个ViewModel可以绑定到不同的"View"上，当View变化的时候Model可以不变，当Model变化的时候View也可以不变。
  - 可重用性。你可以把一些视图逻辑放在一个ViewModel里面，让很多view重用这段视图逻辑。
  - 独立开发。开发人员可以专注于业务逻辑和数据的开发（ViewModel），设计人员可以专注于页面设计，使用Expression Blend可以很容易设计界面并生成xml代码。
  - 可测试。界面素来是比较难于测试的，而现在测试可以针对ViewModel来写。

#### 25、网页验证码是干嘛的，是为了解决什么安全问题。

 区分用户是计算机还是人的公共全自动程序。可以防止恶意破解密码、刷票、论坛灌水；
  有效防止黑客对某一个特定注册用户用特定程序暴力破解方式进行不断的登陆尝试。

#### 26、是否了解公钥加密和私钥加密

一般情况下是指私钥用于对数据进行签名，公钥用于对签名进行验证;
HTTP网站在浏览器端用公钥加密敏感数据，然后在服务器端再用私钥解密

#### 27、PHP操作数据库

https://www.cnblogs.com/EricZLin/p/9208338.html

#### 28、node的基本使用

https://www.cnblogs.com/EricZLin/p/9281987.html

#### 29、express框架

https://www.cnblogs.com/EricZLin/p/9295888.html

#### 30、node操作数据库

https://www.cnblogs.com/EricZLin/p/9307599.html

####  31、vue-router

https://www.cnblogs.com/EricZLin/p/9398937.html

#### 32、axios

https://www.cnblogs.com/EricZLin/p/9380406.html

#### 33、vue-cli

https://www.cnblogs.com/EricZLin/p/9427928.html

#### 34、webpack和babel

https://www.cnblogs.com/EricZLin/p/9404626.html

https://www.cnblogs.com/EricZLin/p/9405413.html

https://www.cnblogs.com/EricZLin/p/9409235.html

https://www.cnblogs.com/EricZLin/p/9411114.html

#### 35、接口设计

https://www.cnblogs.com/EricZLin/p/9427582.html

#### 35、react

https://www.cnblogs.com/EricZLin/p/9433984.html

https://www.cnblogs.com/EricZLin/p/9434428.html

https://www.cnblogs.com/EricZLin/p/9434475.html

https://www.cnblogs.com/EricZLin/p/9436537.html

#### 36、其他参考

- https://github.com/qiu-deqing/FE-interview
- http://wiki.jikexueyuan.com/project/fend_note/
- https://github.com/markyun/My-blog/tree/master/Front-end-Developer-Questions/Questions-and-Answers

## 九、开放性问题

#### 1、你如何优化自己的代码？

- 代码重用
- 避免全局变量（命名空间，封闭空间，模块化 mvc..）
- 拆分函数避免函数过于臃肿：单一职责原则
- 适当的注释，尤其是一些复杂的业务逻辑或者是计算逻辑，都应该写出这个业务逻辑的具体过程
- 内存管理，尤其是闭包中的变量释放

#### 2、优化 WEB 页面加载速度的方法(网站性能优化)

- content方面
  - 减少HTTP请求：合并文件、CSS精灵、inline Image
  - 减少DNS查询：DNS查询完成之前浏览器不能从这个主机下载任何任何文件。方法：DNS缓存、将资源分布到恰当数量的主机名，平衡并行下载和DNS查询
  - 避免重定向：多余的中间访问
  - 使Ajax可缓存
  - 非必须组件延迟加载
  - 未来所需组件预加载
  - 减少DOM元素数量
  - 将资源放到不同的域下：浏览器同时从一个域下载资源的数目有限，增加域可以提高并行下载量
  - 减少iframe数量
  - 不要404
- Server方面
  - 使用CDN
  - 添加Expires或者Cache-Control响应头
  - 对组件使用Gzip压缩
  - 配置ETag
  - Flush Buffer Early
  - Ajax使用GET进行请求
  - 避免空src的img标签
- Cookie方面
  - 减小cookie大小
  - 引入资源的域名不要包含cookie
- css方面
  - 将样式表放到页面顶部
  - 不使用CSS表达式
  - 使用不使用@import
  - 不使用IE的Filter
- Javascript方面
  - 将脚本放到页面底部
  - 将javascript和css从外部引入
  - 压缩javascript和css
  - 删除不需要的脚本
  - 减少DOM访问
  - 合理设计事件监听器
- 图片方面
  - 优化图片：根据实际颜色需要选择色深、压缩
  - 优化css精灵
  - 不要在HTML中拉伸图片
  - 保证favicon.ico小并且可缓存
- 移动方面
  - 保证组件小于25k
  - Pack Components into a Multipart Document

#### 3、常用的 web 页面开发工具

- 编辑器：sublime vscode webstorm hbuilder dw
- 调试工具：httpwatch、firebug，chrome dev
- 其他：postman、Photoshop、firework、git、sqlyog、typora等等

#### 4、列举常用的 js 框架以及分别适用的领域

> 使用率较高的框架有 jQuery、YUI、Prototype、Dojo、Ext.js、Mootools 等。尤其是jQuery，超过 91%。
>
> 轻量级框架有 Modernizr、underscore.js、backbone.js、Raphael.js 等。

- jquery：简化了 js 的一些操作，并且提供了一些非常好用的 API

- jquery ui、jquery-easyui：在 jqeury 的基础上提供了一些常用的组件 日期，下拉框，表格这些组件

- require.js、sea.js模块化开发使用的

- zepto：精简版的 jquery，常用于手机 web 前端开发 提供了一些手机页面实用功能,touch

- ext.js：跟 jquery 差不多，但是不开源，也没有 jquery 轻量

- angular、backbone、knockoutjs、avalon：适合用于单页应用开发(SPA)
- Prototype 最成熟的框架；定义了JS的面向对象扩展，Dom操作API，事件等等，以prototype为核心，形成一个外围的各种各样的JS扩展库

#### 5、怎么来实现页面设计图？

- 首先划分成头部、主体、尾部；

- 实现效果图是最基本的工作，精确到 2px；

- 与设计师，产品经理的沟通和项目的参与

- 做好的页面结构，页面重构和用户体验

- 处理 hack，兼容、写出优美的代码格式

- 针对服务器的优化、拥抱 HTML5

#### 6、前端开发的优化问题（看雅虎 14 条性能优化原则）

（1） 减少 http 请求次数：CSS Sprites, JS、CSS 源码压缩、图片大小控制合适；网页Gzip，CDN 托管，data 缓存 ，图片服务器。

（2） 前端模板 JS+数据，减少由于 HTML 标签导致的带宽浪费，前端用变量保存 AJAX请求结果，每次操作本地变量，不用请求，减少请求次数

（3） 用 innerHTML 代替 DOM 操作，减少 DOM 操作次数，优化 javascript 性能。

（4） 当需要设置的样式很多时设置 className 而不是直接操作 style。

（5） 少用全局变量、缓存 DOM 节点查找的结果。减少 IO 读取操作。

（6） 避免使用 CSS Expression（css 表达式)又称 Dynamic properties(动态属性)。

（7） 图片预加载，将样式表放在顶部，将脚本放在底部 加上时间戳。

（8） 避免在页面的主体布局中使用 table，table 要等其中的内容完全下载之后才会显示出来，显示比 div+css 布局慢。

#### 7、平时如何管理你的项目，如何设计突发大规模并发架构？

- 先期团队必须确定好全局样式（globe.css），编码模式(utf-8) 等
- 编写习惯必须一致（例如都是采用继承式的写法，单样式都写成一行）
- 标注样式编写人，各模块都及时标注（标注关键样式调用的地方）；
- 页面进行标注（例如 页面 模块 开始和结束）；
- CSS 跟 HTML 分文件夹并行存放，命名都得统一（例如 style.css）
- JS 分文件夹存放 命民以该 JS 功能为准,最好使用英文翻译；
- 图片采用整合的 images.png png8 格式文件使用 尽量整合在一起使用方便将来的管理

#### 8、最近前端最流行的一些东西吧？常去的网站？
- 热门：
  - Node.js：是一个JavaScript运行环境，简单点来讲就是Node.js可以解析执行JavaScript代码，也就是说JavaScript可以完全脱离浏览器来运行
  - Mongodb：是一种非关系型数据库，可以不像MySQL一样创建数据库，创建数据表，设计表结构，只需当插入数据的时候，指定某个数据库的某个集合进行操作就行了，一切都是自动完成建库、建表
  - npm：是开发者查找包（package）、设置参数以及管理 npm 使用体验的主要途径注册表（registry），是一个巨大的数据库，保存了每个包（package）的信息，命令行工具 (CLI)：通过命令行或终端运行。开发者通过 CLI 与 npm 打交道
  - MVVM：M，即Model 业务数据模型，指操作数据的类；V，即View 视图界面，HTML用户界面；VM，ViewModel 视图数据模型，指驱动视图改变的data数据。核心思想就是数据驱动视图
  - MEAN：是一个Javascript平台的现代Web开发框架总称，它是MongoDB + Express +AngularJS + NodeJS 四个框架的第一个字母组合。它与传统LAMP一样是一种全套开发工具的简称
  - vuejs：是一套用于构建用户界面的渐进式框架。与其它大型框架不同的是，Vue 被设计为可以自底向上逐层应用。Vue 的核心库只关注视图层，不仅易于上手，还便于与第三方库或既有项目整合。另一方面，当与现代化的工具链以及各种支持类库结合使用时，Vue 也完全能够为复杂的单页应用提供驱动
  - react、react -native：起源于 Facebook 的内部项目。React主要用于构建UI。在React里传递多种类型的参数，如声明代码，帮助你渲染出UI、也可以是静态的HTML DOM元素、也可以传递动态变量、甚至是可交互的应用组件。
  - angularjs：是一款优秀的前端JS框架。AngularJS有着诸多特性，最为核心的是：MVW（Model-View-*Whatever*）、模块化、自动化双向数据绑定、语义化标签、依赖注入等等
  - browserify：Browserify 可以让你使用类似于 node 的 require() 的方式来组织浏览器端的 Javascript 代码，通过预编译让前端 Javascript 可以直接使用 Node NPM 安装的一些库
  - webpack：是一个现代 JavaScript 应用程序的*静态模块打包器(module bundler)*。当 webpack 处理应用程序时，它会递归地构建一个*依赖关系图(dependency graph)*，其中包含应用程序需要的每个模块，然后将所有这些模块打包成一个或多个 *bundle*
  - babel：Babel 是一个 JavaScript 编译器，可以把ES6的语法转为兼容浏览器的ES5语法，Babel可以单独使用，但是一般都是和webpack结合一起使用
  - Weex：框架能够完美兼顾性能与动态性，让移动开发者通过简捷的前端语法写出Native级别的性能体验，并支持iOS、安卓、YunOS及Web等多端部署

常去的网站：

- 博客园、CSDN、掘金、简书
- segmentFault、Stack Overflow、GitHub、awesomes、开源中国
- MDN、菜鸟教程、leetcode、慕课网、网易云课堂
- 技术文档、张鑫旭博客、阮一峰博客

#### 9、移动端怎么做好用户体验?

融入自己的设计理念，注重用户体验，选择合适的技术

- 减少混乱：每一个屏幕应该仅保存一个重要的动作
- 导航连贯、保持一致、明确
- 创建一个跨平台的无缝体验
- 设计对手指操作友好的控件，基于手指的触控点设计控件的布局和位置
- 文本内容应足够清晰：文本大小应该至少在11pt左右
- 保持界面元素清晰可见
- 减少对打字输入的需要

#### 10、谈谈你认为怎样做能使项目做的更好？

考虑问题的深入，不仅仅停留在完成任务上，要精益求精

#### 11、你对前端界面工程师这个职位是怎么样理解的？它的前景会怎么样？

看待：

- 前端是最贴近用户的程序员，实现界面交互，提升用户体验
- 在开发过程中需要和UI、产品经理、后端、测试协调合作
- 有了Node.js，前端可以实现服务端的一些事情

前景：

- 第一个趋势是入口应用会小程序化。类似腾讯、阿里、滴滴、美团这样作为入口的应用，会自己做自己的一套小程序体系，在自己的app内通行。这里的意思不是说大家都会去用微信小程序，而是会效仿微信小程序这套体系，搬到自己的app内。主要原因是，这些入口应用容纳自己公司各类业务线，已经臃肿不堪，使用原生开发迭代效率跟不上，使用HTML又难以做到高性能，因此使用类似小程序的方案，可以做到畅享HTML多年来积累的开发模式，同时裁撤大量平时用不到的API，降低渲染页面的复杂度。这个趋势会涉及到移动端开发
- 第二个趋势是Web前后端融合为全栈开发。Node.js已经给前端开发很好地开了个头，这个头就是让前端人员了解HTTP协议的细节，了解常规的API开发。我相信很多人已经看明白了，为什么我们要做前后端分离，这里面主要原因除了代码开发部署上的分离，还有一部分是，让不懂HTTP协议的人不要在接口层瞎鼓捣，因为这里面细节太多了，你都不了解HTTP缓存，你怎么知道哪个API的HTTP header应该用什么呢。因此了解HTTP协议的前端，会慢慢吃掉这部分后端开发的任务，而了解HTTP协议的后端，也会因为三大框架开发模式的成熟而学会前端开发。进而，这些两类人演化为全栈开发。
- 第三个趋势是营销类页面小程序化。这个指的就是大家平时在微信里看到的各类营销网页，因为主要入口在微信，因此变成微信小程序。这个大家比较好理解吧，就不多说了。小程序现在可能BUG多，功能跟不上，但是要替代这类网页可能也就是2年不到的时间。
- 第四个趋势才是大家看到的[PWA](https://segmentfault.com/a/1190000012353473)（渐进式WEB应用）、WASM代表的HTML内的技术改进，这个能影响到的范围看起来很大，但其实场景比较有限，主要是排除掉上面说的1和3之外的空间。空间就在于这两大技术目前都没有成熟的最佳实践，还需要探索。

#### 12、你认为前端应该如何高质量完成工作?

- 参与项目，快速高质量完成实现效果图，精确到 1px；
- 与团队成员，UI 设计，产品经理的沟通；
- 做好的页面结构，页面重构和用户体验；
- 处理 hack，兼容、写出优美的代码格式；
- 针对服务器的优化、拥抱最新前端技术。

#### 13、设计模式 知道什么是singleton, factory, strategy, decrator么?

**设计模式主要分三个类型:创建型、结构型和行为型。**

- 创建型有：
  - Singleton，[单例模式](https://link.jianshu.com?t=https://www.baidu.com/s?wd=%E5%8D%95%E4%BE%8B%E6%A8%A1%E5%BC%8F&tn=44039180_cpr&fenlei=mv6quAkxTZn0IZRqIHckPjm4nH00T1d9nvnznAm3uHbvmHn1m1ns0ZwV5Hcvrjm3rH6sPfKWUMw85HfYnjn4nH6sgvPsT6KdThsqpZwYTjCEQLGCpyw9Uz4Bmy-bIi4WUvYETgN-TLwGUv3EnHDLPWbsrjDsnjmzrj0krH04rf)：保证一个类只有一个实例，并提供一个访问它的全局访问点
  - Abstract Factory，抽象工厂：提供一个创建一系列相关或相互依赖对象的接口，而无须指定它们的具体类。
  - Factory Method，工厂方法：定义一个用于创建对象的接口，让子类决定实例化哪一个类，Factory Method使一个类的实例化延迟到了子类。
  - Builder，建造模式：将一个复杂对象的构建与他的表示相分离，使得同样的构建过程可以创建不同的表示。
  - Prototype，[原型模式](https://link.jianshu.com?t=https://www.baidu.com/s?wd=%E5%8E%9F%E5%9E%8B%E6%A8%A1%E5%BC%8F&tn=44039180_cpr&fenlei=mv6quAkxTZn0IZRqIHckPjm4nH00T1d9nvnznAm3uHbvmHn1m1ns0ZwV5Hcvrjm3rH6sPfKWUMw85HfYnjn4nH6sgvPsT6KdThsqpZwYTjCEQLGCpyw9Uz4Bmy-bIi4WUvYETgN-TLwGUv3EnHDLPWbsrjDsnjmzrj0krH04rf)：用原型实例指定创建对象的种类，并且通过拷贝这些原型来创建新的对象。

- 行为型有：
  - Iterator，[迭代器模式](https://link.jianshu.com?t=https://www.baidu.com/s?wd=%E8%BF%AD%E4%BB%A3%E5%99%A8%E6%A8%A1%E5%BC%8F&tn=44039180_cpr&fenlei=mv6quAkxTZn0IZRqIHckPjm4nH00T1d9nvnznAm3uHbvmHn1m1ns0ZwV5Hcvrjm3rH6sPfKWUMw85HfYnjn4nH6sgvPsT6KdThsqpZwYTjCEQLGCpyw9Uz4Bmy-bIi4WUvYETgN-TLwGUv3EnHDLPWbsrjDsnjmzrj0krH04rf)：提供一个方法顺序访问一个聚合对象的各个元素，而又不需要暴露该对象的内部表示。
  - Observer，[观察者模式](https://link.jianshu.com?t=https://www.baidu.com/s?wd=%E8%A7%82%E5%AF%9F%E8%80%85%E6%A8%A1%E5%BC%8F&tn=44039180_cpr&fenlei=mv6quAkxTZn0IZRqIHckPjm4nH00T1d9nvnznAm3uHbvmHn1m1ns0ZwV5Hcvrjm3rH6sPfKWUMw85HfYnjn4nH6sgvPsT6KdThsqpZwYTjCEQLGCpyw9Uz4Bmy-bIi4WUvYETgN-TLwGUv3EnHDLPWbsrjDsnjmzrj0krH04rf)：定义对象间一对多的依赖关系，当一个对象的状态发生改变时，所有依赖于它的对象都得到通知自动更新。
  - Template Method，模板方法：定义一个操作中的算法的骨架，而将一些步骤延迟到子类中，TemplateMethod使得子类可以不改变一个算法的结构即可以重定义该算法得某些特定步骤。     
  - Command，[命令模式](https://link.jianshu.com?t=https://www.baidu.com/s?wd=%E5%91%BD%E4%BB%A4%E6%A8%A1%E5%BC%8F&tn=44039180_cpr&fenlei=mv6quAkxTZn0IZRqIHckPjm4nH00T1d9nvnznAm3uHbvmHn1m1ns0ZwV5Hcvrjm3rH6sPfKWUMw85HfYnjn4nH6sgvPsT6KdThsqpZwYTjCEQLGCpyw9Uz4Bmy-bIi4WUvYETgN-TLwGUv3EnHDLPWbsrjDsnjmzrj0krH04rf)：将一个请求封装为一个对象，从而使你可以用不同的请求对客户进行参数化，对请求排队和记录请求日志，以及支持可撤销的操作。    
  -  State，[状态模式](https://link.jianshu.com?t=https://www.baidu.com/s?wd=%E7%8A%B6%E6%80%81%E6%A8%A1%E5%BC%8F&tn=44039180_cpr&fenlei=mv6quAkxTZn0IZRqIHckPjm4nH00T1d9nvnznAm3uHbvmHn1m1ns0ZwV5Hcvrjm3rH6sPfKWUMw85HfYnjn4nH6sgvPsT6KdThsqpZwYTjCEQLGCpyw9Uz4Bmy-bIi4WUvYETgN-TLwGUv3EnHDLPWbsrjDsnjmzrj0krH04rf)：允许对象在其内部状态改变时改变他的行为。对象看起来似乎改变了他的类。
  - Strategy，[策略模式](https://link.jianshu.com?t=https://www.baidu.com/s?wd=%E7%AD%96%E7%95%A5%E6%A8%A1%E5%BC%8F&tn=44039180_cpr&fenlei=mv6quAkxTZn0IZRqIHckPjm4nH00T1d9nvnznAm3uHbvmHn1m1ns0ZwV5Hcvrjm3rH6sPfKWUMw85HfYnjn4nH6sgvPsT6KdThsqpZwYTjCEQLGCpyw9Uz4Bmy-bIi4WUvYETgN-TLwGUv3EnHDLPWbsrjDsnjmzrj0krH04rf)：定义一系列的算法，把他们一个个封装起来，并使他们可以互相替换，本模式使得算法可以独立于使用它们的客户。
  - China of Responsibility，职责链模式：使多个对象都有机会处理请求，从而避免请求的送发者和接收者之间的[耦合关系](https://link.jianshu.com?t=https://www.baidu.com/s?wd=%E8%80%A6%E5%90%88%E5%85%B3%E7%B3%BB&tn=44039180_cpr&fenlei=mv6quAkxTZn0IZRqIHckPjm4nH00T1d9nvnznAm3uHbvmHn1m1ns0ZwV5Hcvrjm3rH6sPfKWUMw85HfYnjn4nH6sgvPsT6KdThsqpZwYTjCEQLGCpyw9Uz4Bmy-bIi4WUvYETgN-TLwGUv3EnHDLPWbsrjDsnjmzrj0krH04rf)
  - Mediator，中介者模式：用一个中介对象封装一些列的对象交互。
  - Visitor，[访问者模式](https://link.jianshu.com?t=https://www.baidu.com/s?wd=%E8%AE%BF%E9%97%AE%E8%80%85%E6%A8%A1%E5%BC%8F&tn=44039180_cpr&fenlei=mv6quAkxTZn0IZRqIHckPjm4nH00T1d9nvnznAm3uHbvmHn1m1ns0ZwV5Hcvrjm3rH6sPfKWUMw85HfYnjn4nH6sgvPsT6KdThsqpZwYTjCEQLGCpyw9Uz4Bmy-bIi4WUvYETgN-TLwGUv3EnHDLPWbsrjDsnjmzrj0krH04rf)：表示一个作用于某对象结构中的各元素的操作，它使你可以在不改变各元素类的前提下定义作用于这个元素的新操作。
  - Interpreter，解释器模式：给定一个语言，定义他的文法的一个表示，并定义一个解释器，这个解释器使用该表示来解释语言中的句子。
  - Memento，[备忘录模式](https://link.jianshu.com?t=https://www.baidu.com/s?wd=%E5%A4%87%E5%BF%98%E5%BD%95%E6%A8%A1%E5%BC%8F&tn=44039180_cpr&fenlei=mv6quAkxTZn0IZRqIHckPjm4nH00T1d9nvnznAm3uHbvmHn1m1ns0ZwV5Hcvrjm3rH6sPfKWUMw85HfYnjn4nH6sgvPsT6KdThsqpZwYTjCEQLGCpyw9Uz4Bmy-bIi4WUvYETgN-TLwGUv3EnHDLPWbsrjDsnjmzrj0krH04rf)：在不破坏对象的前提下，捕获一个对象的内部状态，并在该对象之外保存这个状态。
- 结构型有：
  - Composite，组合模式：将对象组合成树形结构以表示部分整体的关系，Composite使得用户对单个对象和组合对象的使用具有一致性。
  - Facade，外观模式：为子系统中的一组接口提供一致的界面，fa?ade提供了一高层接口，这个接口使得子系统更容易使用。
  - Proxy，代理模式：为其他对象提供一种代理以控制对这个对象的访问
  - Adapter,适配器模式：将一类的接口转换成客户希望的另外一个接口，Adapter模式使得原本由于接口不兼容而不能一起工作那些类可以一起工作。
  - Decrator，装饰模式：动态地给一个对象增加一些额外的职责，就增加的功能来说，Decorator模式相比生成子类更加灵活。
  - Bridge，桥模式：将抽象部分与它的实现部分相分离，使他们可以独立的变化。
  - Flyweight，享元模式

#### 14、页面重构怎么操作？

概念：在不改变代码对外的表现的情况下，修改代码的内部特征。说白了，就是我们的测试用例不变，然后我们对既有的代码的结构进行修改

重构是项目做到一定程度后必然要做的事情。代码重构，可以改善既有的代码设计，增强既有工程的可扩充、可维护性。随着项目需求的不断迭代，需求的不断更新，我们在项目中所写的代码也在时时刻刻的在变化之中。在一次新的需求中，你添加了某些功能模块，但这些功能模块有可能在下一次需求中不在适用。或者你因为需求迭代与变更，使你原有的方法或者类变得臃肿，以及各个模块或者层次之间耦合度增加。此时，你要考虑重构了。

- 对于传统的网站来说重构通常是：
  - 表格(table)布局改为DIV+CSS，
  - 使网站前端兼容于现代浏览器(针对于不合规范的CSS、如对IE6有效的)，
  - 对于移动平台的优化，针对于SEO进行优化

- 深层次的网站重构应该考虑的方面
  - 减少代码间的耦合
  -   让代码保持弹性
  -   严格按规范编写代码
  -   设计可扩展的API
  -   代替旧有的框架、语言(如VB)
  -   增强用户体验

- 通常来说对于速度的优化也包含在重构中
  - 压缩JS、CSS、image等前端资源(通常是由服务器来解决)
  -   程序的性能优化(如数据读写)
  -   采用CDN来加速资源加载
  -   对于JS DOM的优化
  -   HTTP服务器的文件缓存

#### 15、你用的得心应手用的熟练地编辑器&开发环境是什么样子？

 VScode + 插件
  Google chrome 查看页面UI、动画效果和交互功能，Firebug 兼容测试
  Node.js + webpack
  Git 版本控制和Code Review

#### 16、你怎么看待Web App 、hybrid App、Native App？

https://www.jianshu.com/p/24bf070a4dcb

#### 17、你的学习来源是什么？

- 兴趣，精神需求
- 人生要求、职业规划
- 经济

#### 18、原来公司工作流程是怎么样的，如何与其他人协作的？如何跨部门合作的？

#### 19、你遇到过比较难的技术问题是？你是如何解决的？

#### 20、你的优点是什么？缺点是什么？

#### 21、最近在学什么？能谈谈你未来3，5年给自己的规划吗？

#### 22、先自我介绍一下，说一下项目的技术栈，以及项目中遇到的一些问题

#### 23、从整体中，看你对项目的认识，框架的认识和自己思考

#### 24、项目中有没有遇到什么难点，怎么解决

#### 25、其他

- 区块链：https://kb.cnblogs.com/page/573614/

## 十、项目经验（略）

## 十一、自我介绍（略）


































