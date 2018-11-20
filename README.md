# taro-demos
A demo based on taro for show-case

## 官方资源

- [Taro 项目仓库](https://github.com/NervJS/taro)
- [Taro 官方文档](http://nervjs.github.io/taro)
- [Taro UI 项目仓库](https://github.com/NervJS/taro-ui)
- [Taro UI 官方文档](https://taro-ui.aotu.io)
- [微信小程序官方文档](https://developers.weixin.qq.com/miniprogram/dev/)
- [百度智能小程序官方文档](https://smartprogram.baidu.com/docs/introduction/register/index.html)
- [支付宝小程序官方文档](https://docs.alipay.com/mini/developer/getting-started)
- [字节跳动小程序官方文档](https://microapp.bytedance.com/)
- [dva开发文档](https://dvajs.com/)

## 文章教程

* [从0到1构建适配不同端（微信小程序、H5、React-Native 等）的taro + dva应用](https://juejin.im/post/5bb1766d5188255c3272cdd0)
* [【小程序taro最佳实践】http请求封装（方便使用，增加token，统一错误日志记录和上报）](https://segmentfault.com/a/1190000016533592)
* [【小程序taro 最佳实践】异步action优雅实践(简化流程)](https://segmentfault.com/a/1190000016534001)
* [使用Taro框架开发小程序](https://juejin.im/post/5ba0a53af265da0ab5037234)
* [Taro下利用Decorator快速实现小程序分享](https://juejin.im/post/5b99da5d5188255c6f1e084e)
* [微信小程序授权登陆方案以及在Taro下利用Decorator修饰器实现](https://juejin.im/post/5b97a762e51d450e9649a8fd)
* [试用React语法的多端框架Taro问题汇总](https://segmentfault.com/a/1190000016247153)
* [Taro 在京东购物小程序上的实践](https://juejin.im/entry/5b987859e51d450ea2465ddd)
* [Taro实践 - TOPLIFE小程序 开发体验](https://juejin.im/post/5b3b786a6fb9a04f89780a9f)
* [Taro 技术揭秘：taro-cli](https://juejin.im/post/5b3ce041e51d45194832aaf6)
* [为何我们要用 React 来写小程序 - Taro 诞生记](https://juejin.im/post/5b30b476518825749e4a1d91)
* [GitLab-CI微信小程序进行持续集成和持续部署](https://zacksleo.github.io/2018/04/08/GitLab-CI%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%A8%8B%E5%BA%8F%E8%BF%9B%E8%A1%8C%E6%8C%81%E7%BB%AD%E9%9B%86%E6%88%90%E5%92%8C%E6%8C%81%E7%BB%AD%E9%83%A8%E7%BD%B2/)
* [使用Taro和Typescript进行小程序开发](https://zacksleo.github.io/2018/06/16/%E4%BD%BF%E7%94%A8Taro%E5%92%8CTypescript%E8%BF%9B%E8%A1%8C%E5%B0%8F%E7%A8%8B%E5%BA%8F%E5%BC%80%E5%8F%91/)
* [微信小程序及h5,基于taro，zoro最佳实践探索](https://www.jianshu.com/p/7c27dbbc080f)

## 小程序开发奇技淫巧

* [微信小程序 wx.request 对于 JSON 含 \u2028 处理异常](https://segmentfault.com/a/1190000015443614)

## 建议

对于在 Taro 中使用 TypeScript 有一些建议：

* 使用 tslint 作为编辑器内置的 linter
* 使用 eslint 命令行工具配合 `typescript-eslint-parser` 和 `eslint-config-taro`(见 [.eslintrc](./eslintrc)) 作为 `precommit` 或者 `prepush` 的钩子，在提交或 commit 或编译出现问题时检查代码是否符合 Taro 规范
* 不要在 TypeScript 使用 Redux 的 `connect` 装饰器，使用普通的函数写法,详情见: [#9951](https://github.com/DefinitelyTyped/DefinitelyTyped/issues/9951)
* 当你的项目不那么复杂时，可以不使用 Redux

## License

[MIT](LICENSE)
