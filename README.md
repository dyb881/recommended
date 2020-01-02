# 开发规范

- [Airbnb JavaScript 代码规范](https://juejin.im/entry/5b2211afe51d4558ba1a4e52)
- [TypeScript 代码整洁之道](https://juejin.im/post/5cfb2b4951882576be276247)

# React 知识准备

以下知识点不需要追求完全精通，但是需要大致了解<br>

- web 基础 - [MDN](https://developer.mozilla.org/zh-CN/)，[W3C](http://www.w3school.com.cn/)
- ES Next - [JavaScript 完整手册](https://juejin.im/post/5bff57fee51d45021a167991)
- TypeScript(可选，直接使用 js/jsx 文件开发亦可) - [官方文档](https://www.tslang.cn/docs/handbook/basic-types.html)
- React - [入门教程](http://www.ruanyifeng.com/blog/2015/03/react.html)
- 路由 react-router-dom - [官方文档](https://reacttraining.com/react-router/web/guides/quick-start)，[中文文档](https://www.jianshu.com/p/b117b437dc5a)
- 预处理 less/scss/sass - [less 文档](https://www.html.cn/doc/less/)，[scss/sass 文档](http://sass.bootcss.com/docs/sass-reference)，选一即可。
- 模块化 CSS Modules - [CSS Modules 用法教程](http://www.ruanyifeng.com/blog/2016/06/css_modules.html)
- 状态管理 Mobx/Redux 二选一，大型项目推荐采用 Redux，中小型项目推荐采用 mobx 降低开发成本
  - [Mobx 中文文档](https://cn.mobx.js.org)
  - [Redux 中文文档](http://cn.redux.js.org)
    - [redux-saga 中文文档](http://leonshi.com/redux-saga-in-chinese/docs/api/index.html)
- UI 组件 ant-design
  - [PC 端](https://ant.design/docs/react/introduce-cn)
  - [移动端](https://mobile.ant.design/docs/react/introduce-cn)
- 包管理，选一即可
  - yarn [中文文档](https://yarnpkg.com/zh-Hant)
  - npm [菜鸟教程](https://www.runoob.com/nodejs/nodejs-npm.html)
- 打包工具
  - webpack [中文文档](https://www.webpackjs.com)

# 推荐依赖

## React UI 组件，用于主要针对视图展示

- ant-design - 阿里体系
  - antd - [PC 端](https://ant.design/docs/react/introduce-cn)
  - antd-mobile - [移动端](https://mobile.ant.design/docs/react/introduce-cn)
  - antV - [数据可视化](https://antv.vision/zh)
- react-json-view - [json 展示组件](https://github.com/mac-s-g/react-json-view)

## React 工具组件，不展示视图，仅提供功能支持

- react-transition-group - [组件进出动画](https://juejin.im/entry/5b3e14e86fb9a04fc4369f1e)
- react-media - [响应式](https://github.com/ReactTraining/react-media)
- 状态管理
  - Mobx - [Mobx 中文文档](https://cn.mobx.js.org)
  - Redux - [Redux 中文文档](https://www.redux.org.cn)
    - redux-saga - [redux-saga 中文文档](http://leonshi.com/redux-saga-in-chinese/docs/api/index.html)

## 视图工具，用于视图展示的工具

- qrcode - [二维码生成](https://www.npmjs.com/package/qrcode)
- photoswipe - [图片预览](https://www.npmjs.com/package/photoswipe)
- 数据可视化
  - chartjs - [chartjs 官网](https://chartjs.bootcss.com)
- 图像绘制
  - pixi.js 2D 绘制引擎 - [官网](https://www.pixijs.com/)，[中文文档](https://github.com/Zainking/LearningPixi)
  - Three.js 3D 绘制引擎 - [中文文档](https://techbrood.com/threejs/docs/)
- 移动端调试工具
  - vconsole - [vconsole npm](https://www.npmjs.com/package/vconsole)
  - eruda - [eruda npm](https://www.npmjs.com/package/eruda)
- screenfull 全屏工具 - [简书](https://www.jianshu.com/p/cfbb13c32c9c)

## 工具，提供各种强大的功能

- axios - [请求工具](https://www.kancloud.cn/yunye/axios/234845)
- classNames - [快速组合 CSS 类](https://www.npmjs.com/package/classnames)
- lrz - [图片压缩处理](https://www.npmjs.com/package/lrz)
- file-saver - [客户端保存文件](https://github.com/eligrey/FileSaver.js)
- ua-parser-js - [userAgent 解析工具](https://github.com/faisalman/ua-parser-js)
- lodash - [高性能实用工具库](http://lodash.net/docs/4.16.1.html)
- 时间处理
  - moment - [官方文档](http://momentjs.cn/docs)
  - date-fns - [date-fns npm](https://www.npmjs.com/package/date-fns)
- js-cookie - [cookie 操作](https://github.com/js-cookie/js-cookie)
- any-rule - [正则大全](https://any86.github.io/any-rule)
- rxjs - [响应式流程管理](https://cn.rx.js.org/manual/installation.html)
- name-styles - [命名格式转换(如下划线转驼峰)](https://gitee.com/jamesfancy/name-styles)

## 编译工具，编译过程中提供各种帮助

- react-snap - [预渲染HTML](https://github.com/stereobooster/react-snap)
- webpack-parallel-uglify-plugin - [多进程代码压缩](https://www.npmjs.com/package/webpack-parallel-uglify-plugin)
- filemanager-webpack-plugin - [文件操作和压缩](https://www.npmjs.com/package/filemanager-webpack-plugin)
- core-js - [低版本浏览器兼容方案](https://github.com/zloirock/core-js)

## Node.js，常用工具

- fs-extra - [文件操作](https://www.npmjs.com/package/fs-extra)
- inquirer - [命令行表单](https://www.npmjs.com/package/inquirer)
- reconnecting-websocket - [自动重连websocket](https://www.npmjs.com/package/reconnecting-websocket)

## 个人封装的常用工具

由于兼容问题，目前只能在以下三种方式搭建的开发环境中引用<br>
[官方 create-react-app](https://github.com/facebook/create-react-app)<br>
https://github.com/dyb881/create-react-app<br>
https://github.com/dyb881/react-app

- 个人封装
  - @dyb881/auto-rem [自动计算 rem](https://www.npmjs.com/package/@dyb881/auto-rem)
  - @dyb881/fetch-request - [请求工具](https://www.npmjs.com/package/@dyb881/fetch-request)
  - @dyb881/file - [文件以及图片处理工具](https://www.npmjs.com/package/@dyb881/file)
  - @dyb881/img - [增强 img 标签](https://www.npmjs.com/package/@dyb881/img)
  - @dyb881/json - [json 处理工具](https://www.npmjs.com/package/@dyb881/json)
  - @dyb881/mock-server - [模拟数据服务器](https://www.npmjs.com/package/@dyb881/mock-server)
  - @dyb881/router - [配置注册路由，带跳转动画](https://www.npmjs.com/package/@dyb881/router)
  - @dyb881/transition - [动画组件](https://www.npmjs.com/package/@dyb881/transition)
  - @dyb881/tab-bar - [移动端 tabbar](https://www.npmjs.com/package/@dyb881/tab-bar)
