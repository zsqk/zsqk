# zsqk

晋城市掌上乾坤网络科技有限公司

## 技术 ⚙️

关键字: 云原生, Web, TypeScript, Deno, React, PostgreSQL

团队使用开源技术, 也会向开源社区反馈.

以下是啰嗦的技术栈:

- [语言] JavaScript/ECMAScript 2020+
- [语言] TypeScript 5+
- [语言] HTML 5
- [语言] CSS 3
- [语言] Rust
- [运行环境] Web-APIs (Browser)
- [运行环境] 微信小程序
- [运行环境] Electron latest
- [运行环境] Node.js 22+
- [运行环境] Deno latest
- [运行环境] Bun latest
- [依赖] React 18+
- [依赖] Ant-Design (antd) 5
- [依赖] Ionic
- [依赖] [Postgres.js]
- [依赖] [Day.js]
- [依赖] [somefn]
- [框架] Next.js latest
- [框架] Taro 3
- [框架] [fresh]
- [技术] [CSS Modules]
- [数据库] PostgreSQL 14+
- [版本控制] Git
- [文档语法] Markdown
- [文档语法] reStructuredText
- [部署] 阿里云 函数计算 FC
- [部署] 阿里云 对象储存 OSS
- [部署] Aliyun ESA
- [部署] Vercel
- [云服务] Aliyun MNS
- [云服务] Aliyun EventBridge
- [工具] ESLint 9
- [工具] Prettier
- [工具] Babel
- [测试] Jest
- [测试] deno test

[Postgres.js]: https://github.com/porsager/postgres
[CSS Modules]: https://github.com/css-modules/css-modules
[fresh]: https://github.com/denoland/fresh
[Day.js]: https://day.js.org/
[somefn]: https://github.com/zsqk/deno-fn

逐步不再继续使用的:

- [运行环境] 钉钉小程序 (以前叫E应用, 现在基于支付宝小程序)
- [语言] Go 1
- [依赖] PouchDB
- [数据库] CouchDB
- [测试] Postman
- [语言] PHP 7
- [框架] Lumen (PHP)
- [前端工具] Webpack 4
- [工具] Yarn 1
- [Web 服务器] Nginx
- [运维] Docker
- [运维] AWS Lambda
- [运维] AWS API Gateway
- [运维] Deno Deploy
- [数据库] Amazon DynamoDB
- [Moment.js](https://momentjs.com/)
- [deno-postgres](https://github.com/denodrivers/postgres)

## 文化

- (分析) 将复杂问题拆分为多个简单问题. 将具体问题抽象为通用问题.
- (执行) 精益求精. 在细节上精确化, 标准化, 一致化.
- (决策) 追求平衡. 想到尽可能的多, 做到尽可能的少.
- (协作) 充分沟通, 坚决执行.
- (记录) 公开化, 文字化, 持久化.

在产品设计的时候我们要追求平衡,
在 "user first" 原则下, "more flexibility means more work",
一方面说的是设计及开发工作, 另一方面, 也是说用户对产品的学习曲线.

扩展倾向:

- 大道至简. 用尽可能简单的方法解决复杂的问题.
- 组合拼接. 拼积木而非做雕刻. 初期, 为解决每个具体问题做专用的解决方案, 而不是直接做一套兼容各种情况的通用方案.
- 有效参考. 优先查看官方文档, 看依赖的源代码, 尽量找一手的参考资料.
- 业内标准. 使用标准的东西, 因为标准是沉淀下来的共识或普遍认可的妥协. 比如使用 JWT 的时候参看 RFC 7519.
- 倾向使用 Web API 而不是 Node.js 的模块.
- 如何做到充分沟通? 避免讳疾忌医. 要承认每个人都会犯错, 然后在遇到错误时正视这个问题, 解决这个错误.
- 减少忌讳, 充分表达, 个人观点求同存异, 在多元视角中找到最终方案. 公开/文字/持久.
- 追求本源. 从需求出发, 从痛点出发, 从流程出发, 从业务出发. 以他人实例为参考, 找到充分的理由.
- 比如我们的 QR 码网址会尽量短, 域名短, 参数短, 从而在相同兼容性上提高识别度.
- 在抽象与业务之间找平衡, 在速度与质量之间找平衡.
- 精确化的例子如 uuid 是 string, 但不能用 string 替代 uuid.
- 标准化的例子如 uuid 能实现的需求, 我们不会再做随机字符串.
- 但标准化要在实现需求的前提下, 比如产品希望尽可能短的 ID, 就不应该使用 uuid.
- 一致化的例子如对同一数据不使用多个命名.
- 公开化是为了减少架构层面, 避免团队内部的信息壁垒.
- 文字化是为了方便储存和检索.
- 持久化是为了追本溯源, 以史为鉴.
- 和我们文化契合度较高的理论如 奥卡姆剃刀原理.
- 和我们文化契合度较高的理论如 第一性原理.
- 将错误前置, 静态分析 > 编译时错误 > 运行时错误 > 有错误但不报.
- 有错误但不报的情况如静默失败或产生错误结果, 比如过滤失败导致返回空数组,
  此时我们无法分析这是正常查询但的确无数据还是查询失败.
- 处理类型时要业务逻辑清晰, 比如手机号虽然都是 int 组成的, 但是不同手机号间没有大小之分, 应该作为 text 类型.
- 处理类型时要尽量准确, 比如用户标识符在 TS 中被额外定义为 `type UserID = string`.
- 命名要语义化清晰, 一致, 简洁.

## 招聘 💼

<https://zsqk.github.io/zsqk/hiring/>

## 工具 🛠️

macOS / Windows WSL 2

https://code.visualstudio.com/

https://www.jetbrains.com/resources/eap/
