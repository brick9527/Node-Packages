<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
# 目录

- [目录](#%E7%9B%AE%E5%BD%95)
- [Node-Packages](#node-packages)
    - [框架](#%E6%A1%86%E6%9E%B6)
        - [应用框架](#%E5%BA%94%E7%94%A8%E6%A1%86%E6%9E%B6)
        - [游戏框架](#%E6%B8%B8%E6%88%8F%E6%A1%86%E6%9E%B6)
    - [工具](#%E5%B7%A5%E5%85%B7)
        - [网络](#%E7%BD%91%E7%BB%9C)
        - [CLI](#cli)
        - [图形化](#%E5%9B%BE%E5%BD%A2%E5%8C%96)
        - [数据/数据库](#%E6%95%B0%E6%8D%AE%E6%95%B0%E6%8D%AE%E5%BA%93)
        - [爬虫](#%E7%88%AC%E8%99%AB)
        - [性能](#%E6%80%A7%E8%83%BD)
        - [Windows编程](#windows%E7%BC%96%E7%A8%8B)
        - [时间](#%E6%97%B6%E9%97%B4)
        - [格式化](#%E6%A0%BC%E5%BC%8F%E5%8C%96)
        - [Git相关](#git%E7%9B%B8%E5%85%B3)
        - [Web3.0](#web30)
        - [其他](#%E5%85%B6%E4%BB%96)
    - [其他汇总](#%E5%85%B6%E4%BB%96%E6%B1%87%E6%80%BB)
    - [规范](#%E8%A7%84%E8%8C%83)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# 目录

<!-- toc -->

# Node-Packages

Node各类包、工具的汇总黄页

## 框架

### 应用框架

- [Egg](https://github.com/eggjs/egg)
- [Koa](https://github.com/koajs/koa)
- [Express](https://github.com/expressjs/express)
- [Hapi](https://github.com/hapijs/hapi)
- [midway](https://github.com/midwayjs/midway)

一款微服务框架

- [Nest](https://github.com/nestjs/nest)

一款基于TS的服务器端框架

### 游戏框架

- [pomelo](https://github.com/NetEase/pomelo)

## 工具

### 网络

- [axios](https://github.com/axios/axios)
- [lib-qqwry](https://github.com/cnwhy/lib-qqwry)
  
IP地址解析

- [Node-SSH](https://github.com/steelbrain/node-ssh)

SSH连接

- [Basic FTP](https://github.com/patrickjuchli/basic-ftp)

FTP连接

- [node-ldapjs](https://github.com/ldapjs/node-ldapjs)

基于Node的LDAP协议程序包，包括服务器API、客户端API，可以用于创建基于LDAP协议的服务器，或者创建连接到指定LDAP服务器的客户端

- [Nodemailer](https://github.com/nodemailer/nodemailer)

一个使用Node.js发送电子邮件的模块

- [socket.io](https://github.com/socketio/socket.io)

一个基于事件的实时双向通信模块

### CLI

- [clime](https://github.com/vilic/clime)
  
一款易上手的CLI应用框架

- [prettycli](https://github.com/siddharthkp/prettycli)

控制台输出美化工具

- [qoa](https://github.com/klaussinani/qoa)

- [cli-table](https://github.com/Automattic/cli-table)

`cli-table` 是一个适用于 Node.js 的命令行表格渲染工具，能够在终端中生成美观的 Unicode 辅助表格。

> 核心特性
- 支持自定义表格边框字符，可灵活调整表格外观
- 借助 `colors.js` 实现表头的颜色和背景样式美化
- 提供列宽自定义、文本截断（基于预设宽度）、文本对齐（左/右/居中）及填充（左右）等功能
- 支持多种表格类型：水平表格、垂直表格、交叉表格
- 拥有简洁易用的 API，可通过 `push` 等方法便捷地添加行数据

> 安装与使用

通过 npm 安装：`npm install cli-table`。使用时需引入模块，实例化表格并配置选项（如表头、列宽等），添加数据后调用 `toString()` 方法即可在终端输出表格。

该工具由 Automattic 维护，基于 MIT 许可证开源。

---

### 图形化

- [sharp](https://github.com/lovell/sharp)

图形库，可以用来做水印、验证码等的一个包

- [node-canvas](https://github.com/Automattic/node-canvas)

`node-canvas`是一款基于[Cairo](https://www.cairographics.org/)的Node.js图形接口库。

`node-canvas`是之前使用比较广的Node图形库之一，但是印象中`node-canvas`在跨平台方面以及大陆地区的依赖安装会有比较多的坑

### 数据/数据库

- [elasticsearch.js](https://github.com/elastic/elasticsearch-js-legacy)

用于连接ES的包

### 爬虫

- [puppeteer](https://github.com/puppeteer/puppeteer)

一个提供了chrome内核的包，爬虫只是一方面，还能用来做网站测试，浏览器能做的它几乎都能做

### 性能

- [Easy-Monitor](https://github.com/hyj1991/easy-monitor)

企业级 Node.js 应用性能监控与线上故障定位解决方案

- [v8-profiler](https://github.com/node-inspector/v8-profiler)

v8分析器

- [node-heapdump](https://github.com/bnoordhuis/node-heapdump)

v8堆快照工具

- [Benchmark.js](https://github.com/bestiejs/benchmark.js)

一个强大的基准测试库，支持高分辨率计时器并返回具有统计意义的结果。 如jsPerf

### Windows编程

- [node-node-process-windows](https://github.com/bryphe/node-process-windows)

windows进程管理

### 时间

- [moment](https://github.com/moment/moment)

一款用于解析、验证、操作和格式化日期的 JavaScript 日期库。（现在该库已经不再更新，推荐使用[dayjs](https://github.com/iamkun/dayjs)）

- [dayjs](https://github.com/iamkun/dayjs)

Day.js 是一个极简的 JavaScript 库，它使用与 Moment.js 兼容的 API 为现代浏览器解析、验证、操作和显示日期和时间。

### 格式化

- [xmlbuilder-js](https://github.com/oozcitak/xmlbuilder-js)

node.js的XML构建器，类似于java-xmlbuilder。新版本的xmlbuilder现在改为了[xmlbuilder2](https://github.com/oozcitak/xmlbuilder2)。

- [xmlbuilder2](https://github.com/oozcitak/xmlbuilder2)

node.js的XML构建器。

- [js-yaml](https://github.com/nodeca/js-yaml)

一款用于序列化/反序列化`yml`/`yaml`文件的解析器。

### Git相关

- [commitlint](https://github.com/conventional-changelog/commitlint)

能够检测`git commit`命令中`message`是否符合响应规范的工具

- [luoxue-victor/commitlint](https://github.com/luoxue-victor/commitlint)

基于`commitizen`,`commitlint`,`conventional-changelog-cli`,`husky`做的开箱即用的`Git commit`工具

- [AlloyLint](https://github.com/AlloyTeam/AlloyLint)

运行 eslint 的自动修复，但是保留最后修改人的信息的工具

### Web3.0

- [binance-connector-js](https://github.com/binance/binance-connector-js)

> binance-connector-js 仓库简介

**仓库地址**：[https://github.com/binance/binance-connector-js](https://github.com/binance/binance-connector-js)  
**核心定位**：Binance 官方推出的 TypeScript/JavaScript 连接器集合，专为对接 Binance 全品类 API 设计，替代旧版统一连接器（`@binance/connector`、`@binance/connector-typescript`），提供更灵活的模块化解决方案。


> 核心特性

1. **全业务场景覆盖**  
   包含 24 个细分领域连接器，覆盖 Binance 核心服务：  
   - 交易类：现货（`@binance/spot`）、币本位合约（`@binance/derivatives-trading-coin-futures`）、USDS-M 合约、期权、C2C、跟单交易等；  
   - 资产类：钱包（`@binance/wallet`）、质押（`@binance/staking`）、简单赚（`@binance/simple-earn`）、加密贷款、VIP 贷款等；  
   - 辅助类：NFT（`@binance/nft`）、支付（`@binance/pay`）、法币（`@binance/fiat`）、返佣（`@binance/rebate`）、子账户管理等。

2. **开发友好设计**  
   - 强类型支持：基于 TypeScript 构建，提供完整类型定义，减少接口调用错误；  
   - 按需安装：各连接器独立发布为 npm 包，避免冗余依赖（如仅需现货功能可单独安装 `@binance/spot`）；  
   - 迁移便捷：提供 `MIGRATION.md` 文档，指导从旧版统一连接器升级至模块化结构，旧版代码暂存于 `legacy` 分支。

3. **实时与可靠**  
   支持 WebSocket 实时行情与流服务，适配 Binance 测试网环境，满足高频交易、市场数据监控等场景需求。


### 其他

- [TypeORM](https://github.com/typeorm/typeorm)

一款基于TS的ORM框架

- [decimal.js](https://github.com/MikeMcl/decimal.js)

基于JS的数值精确计算的库

- [nvm](https://github.com/nvm-sh/nvm)

Node版本管理器，用于Linux

- [nvm-windows](https://github.com/coreybutler/nvm-windows)

Node版本管理器，用于Windows

- [Espree](https://github.com/eslint/espree)

兼容Esprima的JavaScript解析器

- [svg-term-cli](https://github.com/marionebl/svg-term-cli)

把svg转到终端控制台显示的CLI工具

- [yapi](https://github.com/YMFE/yapi)

YApi 是一个可本地部署的、打通前后端及QA的、可视化的接口管理平台

## 其他汇总

- [awesome-cli](https://github.com/Kikobeats/awesome-cli)

汇总了关于开发CLI的工具、包的一个仓库

- [hacker-laws-zh](https://github.com/nusr/hacker-laws-zh)

对开发人员有用的定律、理论、原则和模式（中文版）

- [hacker-laws](https://github.com/dwmkerr/hacker-laws)

对开发人员有用的定律、理论、原则和模式（英文版）

## 规范

- [AlloyTeam CodeGuide](https://github.com/AlloyTeam/CodeGuide)

腾讯 AlloyTeam 代码规范
