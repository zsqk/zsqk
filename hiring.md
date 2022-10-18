---
title: 招聘
layout: page
permalink: /hiring/
comments: true
---

## 岗位 Job description

### 后端

基本要求:

- 掌握一门语言及其标准库 (TypeScript, Go)
- 使用版本控制系统 (Git)
- 熟悉至少一种 SQL 或 NoSQL 数据库
- 有 HTTP 相关常识
- 可以理解并实现需求

加分项:

- 良好的业务理解能力
- 良好的沟通能力
- 使用 Deno
- 使用 PostgreSQL
- 习惯从官方文档或源代码中获取信息
- 在 Stack Overflow 上有过收获
- 在 LeetCode 独立做过一些中等难度的题
- 对开源项目有过贡献 (比如在 GitHub 上参与 issues 讨论, PR review 等)
- 熟练掌握至少一门其他的后端语言
- 使用 WebAssembly

笔试题:

- 基于 <https://leetcode.com/problems/minimum-number-of-frogs-croaking/>,
  但我们的要求更进一步, 青蛙的蛙鸣 `croak` 不是一个常量, 而是一个变量, 比如 `abcdefg`.
- [获取数据的所有链条](https://www.typescriptlang.org/play?#code/MYewdgzgLgBAJgQygmBeGBtAUDGBvGASzgC4YBGAGhgAdiyAGGAX0p3yNJgCZq6umrdgXowAzH1HkWbXCK4AWSVzEzhnMgFZlZBWoC6AbixZQkWACcAphDSZ1UnTAbVgACwSEwZDPrVyNHicXGHdPb0w-IQDRCVpHUI8vH3Io2Q5RJXiVVySIjCpxNIcubWzdXPCU6jiFYqMTKABPGisYADEwOwAKADcybubWkAAzeCQEAEpJtAA+GCGrUZhrCGNTcGgYEYjOnpnUebx2AHoTmAAVAHkAESuyQBjtQAQjQFPowF-FQAdTLGYsIA) 在数组中, 我们不能假设数据一定按照某种顺序排列, 要考虑到符合类型要求的前提下, 真实数据的多种可能.
- 将以上两题的答案改为 TypeScript.
  如果有 TypeScript 经验, 可以选做.
- 注释与学习能力:
  <https://codepen.io/anon/pen/vREeae?editors=0011>
  答题时不必须注册或登录, 修改代码完成待办, 将修改后的代码保存在任意地方.

### 前端

基本要求:

- 掌握 ECMAScript 2015+
- 使用版本控制系统 (Git)
- 掌握 HTML 及 CSS 的基本用法
- 有 HTTP 相关常识
- 可以理解并实现需求

加分项:

- 良好的业务理解能力
- 良好的沟通能力
- 参与过使用 React 的项目
- 参与过有平台对接的项目 (比如微信公众平台等)
- 习惯从 MDN 获取信息
- 在 LeetCode 独立做过一些中等难度的题
- 在 Stack Overflow 上有过收获
- 对开源项目有过贡献 (比如在 GitHub 上参与 issues 讨论, PR review 等)
- 使用 TypeScript
- 了解 ECMAScript 2020

笔试题:

- 项目认识与完成能力:
  <https://codesandbox.io/s/zsqk-test-1-ti-mu-yoq2q?file=/index.html>
  答题时不必须注册或登录, 浏览器隐私模式打开后, 直接修改代码以完成待办, 保存后 URL 会变为修改后代码的唯一 URL.
- 将项目认识与完成能力中的功能用 React 重构一遍.
  如果有 React 经验, 可以选做. 不必考虑浏览器兼容, 使用 TypeScript 和 ES2021 均可, 使用 fetch 等 Web API.
- 注释与学习能力:
  <https://codepen.io/anon/pen/vREeae?editors=0011>
  答题时不必须注册或登录, 修改代码完成待办, 将修改后的代码保存在任意地方.
- JavaScript 基础与原型链:
  <https://jsbin.com/cehiziveri/1/edit?js,console>
  答题时不必须注册或登录, 浏览器隐私模式打开后, 直接修改代码以实现计划输出, 保存后 URL 会变为修改后代码的唯一 URL.

<script>const guide = `答题指南:

项目认识与完成能力, 共考察如下几点:

1. 前端基础结构理解. (看是否达成基本目的, 输入用户编号查到用户姓名)
2. CSS 基础. (.result.success 是否正确完成)
3. 项目数据结构理解. (可以根据编号显示姓名)
4. JS 数组基础操作. (从多人中找到符合要求的人)
5. Web API 基础操作, DOM 操作. (找到特定 DOM, 修改其 class)
6. JS 函数调用. (使用列出的一些函数)
7. 前端程序健壮性. (找不到人时, 也有相应的 DOM 变动)

React:

1. 使用函数组件. (更贴合团队习惯)
2. 使用 Hooks. (更贴合团队习惯)
3. 不要再进行 DOM 操作.

注释与学习能力, 共考察如下几点:

1. 如果使用过 JSDoc, 考察对 JSDoc 的认识.
2. 如果没使用过 JSDoc, 考察学习能力.
3. 合理的函数注释名称, 是否理解函数基础功能.
4. 函数参数的可选及默认值是否理解清楚.
5. 根据代码功能推断类型. (包括参数类型, 返回类型)
6. 完成后移除 @todo.
7. 完成过程中不要使用不必要的 tags.

JavaScript 基础与原型链, 共考察如下几点:

1. 功能实现能力. 要实现功能, 处理结果要与预期一致.
2. 避免 hardcode. 不能假设数据一定有三个属性, 也可以是两个, 也可能是四个, 每个属性中的值数量也是不固定的.
3. JS 基础用法. 看功能是如何实现的, 如何使用 JS 基础语法和常见方法.
4. 合理的函数拆分. 在实现功能的前提下, 是否对复杂功能进行合理的功能拆分.
5. JS 原型链基础理解. 是否通过原型链方法实现基本功能.
6. JS getter 的基础理解. 是否通过对象 getter 实现基本功能.
7. 细节是否完善, 比如最终字符串中的逗号和空格是否如预期中的要求.`</script>

### 产品

- 思考
- 沟通
- 决断
- 记录

## 地点

- 晋城 (城区, 国贸A栋), 山西

## 待遇

- 工作时间不超过 **35 小时/每周**
- 近五年加班时间不超过 **30 小时/每年**
- 良好的技术氛围
- 开发设备为 Mac mini (2020)
- 薪资根据能力面议, 在当地有竞争力

## 联系方式

- 邮箱: <lzr@go0356.com>
- 微信: zheren (请备注 zsqk)
