# Chovy · 项目与技术资料索引

本目录收纳23个应用、工具库、工程实践与技术资料目录。各项目保留自己的依赖、运行配置和文档，不是共享同一构建命令的统一工作区。

本页用于选择项目；运行、接入和维护以对应README及实际配置为准。逐项检查记录见 [README-AUDIT.md](README-AUDIT.md)。

## 项目导航

| 项目 | 定位 | 主要实现/资料 |
|---|---|---|
| [QA-Automation](https://github.com/nemo-crypto/QA-Automation/blob/main/readme.md) | UI/API/App自动化 | 两套独立工程与共享Agent调用器 |
| [SignalAtlas](https://github.com/nemo-crypto/SignalAtlas/blob/main/README.md) | 行情与策略前端 | React、Vite、市场数据适配 |
| [activity-dev-plug-in](https://github.com/nemo-crypto/activity-dev-plug-in/blob/main/README.md) | 交互插件资料 | 文档、截图、第三方接入片段 |
| [agent](https://github.com/nemo-crypto/agent/blob/main/readme.md) | AI全栈开发实践 | Next.js、Go、OpenAPI、Skills |
| [angular6-material](https://github.com/nemo-crypto/angular6-material/blob/master/README.md) | 管理控制台 | Angular 6、Material、ECharts |
| [bit-request](https://github.com/nemo-crypto/bit-request/blob/main/README.md) | 请求与React Hook库 | Axios、dumi、father |
| [bit-utils](https://github.com/nemo-crypto/bit-utils/blob/main/README.md) | JS/TS工具库 | Rollup、TypeDoc、缓存和队列 |
| [comment-app](https://github.com/nemo-crypto/comment-app/blob/master/README.md) | 静态测评/任务页面 | MUI、jQuery、H5页面 |
| [common-interview-coding-questions](https://github.com/nemo-crypto/common-interview-coding-questions/blob/main/README.md) | 编程与合约笔记 | Markdown学习资料 |
| [express](https://github.com/nemo-crypto/express/blob/master/README.md) | Web与MySQL示例 | Express 4、EJS、MySQL |
| [face-recognition-app](https://github.com/nemo-crypto/face-recognition-app/blob/master/README.md) | H5任务与核验界面 | MUI、H5+、Demo客户端 |
| [flutter-app](https://github.com/nemo-crypto/flutter-app/blob/main/ReadMe.md) | 抽卡与收藏Demo | Flutter、Mock/远端Repository |
| [monorepo](https://github.com/nemo-crypto/monorepo/blob/main/README.md) | 业务组件与模块集合 | Lerna 3、Xatom源码包 |
| [nemo-crypto](https://github.com/nemo-crypto/nemo-crypto/blob/main/README.md) | 双语个人介绍 | README、SVG与文档资源 |
| [next-react](https://github.com/nemo-crypto/next-react/blob/main/README.md) | 多语言业务前端 | Next 13 Pages、MobX |
| [nuxt-vue3](https://github.com/nemo-crypto/nuxt-vue3/blob/main/README.md) | 链浏览器前端 | Nuxt 3、Pinia、Keplr |
| [openlayers](https://github.com/nemo-crypto/openlayers/blob/master/README.md) | 地图标注示例 | 原生页面、OpenLayers |
| [pump-fun-frontend 17.05.23](https://github.com/m8s-lab/pump-fun-frontend/blob/main/README.md) | Solana代币前端 | Next 14、Wallet Adapter、Anchor |
| [qiankun](https://github.com/nemo-crypto/qiankun/blob/main/README.md) | 多框架微前端 | Vue 2基座、React/Vue/HTML子应用 |
| [react-grid-layout](https://github.com/nemo-crypto/react-grid-layout/blob/nemo-test/README.md) | 网格布局组件源码 | React、Flow、Webpack、Make |
| [resume](https://github.com/nemo-crypto/resume/blob/main/readme.md) | 简历文档 | 独立Markdown版本 |
| [sentry-react](https://github.com/nemo-crypto/sentry-react/blob/main/README.md) | 监控配置片段 | React Sentry初始化示例 |
| [tg-dapp-frontend-template](https://github.com/nemo-crypto/tg-dapp-frontend-template/blob/main/README.md) | Telegram Mini App前端 | Next 14、Telegram SDK、TON |

## 如何开始

1. 从上表进入项目README，先确认它是应用、库还是文档集合。
2. 在对应工程目录安装依赖，不要在chovy根目录执行统一npm命令。
3. 按工程说明准备后端、数据库、链网络、设备或原生宿主。
4. 核对实际脚本、环境变量和业务数据，再执行开发或验收流程。

跨目录组合的项目包括agent/ai-fullstack-lab、QA-Automation和qiankun；它们的子工程运行入口由各自根文档说明。Monorepo中的源码包也有单独接入条件，不能把目录存在等同于可独立发布的包。

## 文档检查与维护

本轮检查覆盖23个一级目录及22份第一方子工程/模块文档，同时补充语言与开发指南、保留3份历史笔记。保留已有API文档、许可说明与原作者信息，第三方图表SDK、字体、构建缓存和简历正文不作改写。

本轮只执行静态文档核对：源码/配置对应、文件链接、Shell片段语法和命令清单；没有批量安装依赖、启动应用、访问业务服务、运行模型或执行发布。各README中的原有测试数字与线上地址仍按历史记录理解。

已知运行前提包括历史工具链、缺失的业务包或脚本、链网络不一致及数据库启动副作用，均记录在项目README中。详细处理与校验结果见 [逐项检查清单](README-AUDIT.md)。


本页为本地多仓库文档索引的远程副本，跨项目链接按各仓库当前分支生成；不要求读者拥有原本地目录。
