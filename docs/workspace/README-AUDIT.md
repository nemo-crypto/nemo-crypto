# README逐项检查与完善记录

范围：23个一级目录、22份第一方子工程/模块文档；新增或修改共52份Markdown文档，包含总导航、本文、补充指南及3份保留的历史笔记。

状态：逐项检查、文档修改与最终静态校验全部完成。本轮没有运行项目安装、业务请求或发布命令。

## 一级项目处理结果

| 项目 | 主要源码/清单依据 | 实际处理 |
|---|---|---|
| [QA-Automation](https://github.com/nemo-crypto/QA-Automation/blob/main/readme.md) | 两套独立工程与共享Agent调用器 | 补充根目录运行边界，保留原测试记录 |
| [SignalAtlas](https://github.com/nemo-crypto/SignalAtlas/blob/main/README.md) | React、Vite、市场数据适配 | 补齐事件、A股/港股路由、降级数据与脚本范围 |
| [activity-dev-plug-in](https://github.com/nemo-crypto/activity-dev-plug-in/blob/main/README.md) | 文档、截图、第三方接入片段 | 明确无应用源码，补充宿主前提并替换示例widget值 |
| [agent](https://github.com/nemo-crypto/agent/blob/main/readme.md) | Next.js、Go、OpenAPI、Skills | 核实导航层/工作区边界，补齐Go与Web子工程入口 |
| [angular6-material](https://github.com/nemo-crypto/angular6-material/blob/master/README.md) | Angular 6、Material、ECharts | 重写功能、服务配置、4201端口和历史工具链说明 |
| [bit-request](https://github.com/nemo-crypto/bit-request/blob/main/README.md) | Axios、dumi、father | 补充真实导出、默认参数、重试与业务接口适配 |
| [bit-utils](https://github.com/nemo-crypto/bit-utils/blob/main/README.md) | Rollup、TypeDoc、缓存和队列 | 补充入口、缺失postinstall文件及构建错误处理边界 |
| [comment-app](https://github.com/nemo-crypto/uni-app/blob/master/README.md) | MUI、jQuery、H5页面 | 纠正仅标uni-app的描述，补齐登录与实验入口 |
| [common-interview-coding-questions](https://github.com/nemo-crypto/SmartContract/blob/main/README.md) | Markdown学习资料 | 明确没有执行工程，补充导航与示例权限缺口 |
| [express](https://github.com/nemo-crypto/express/blob/master/README.md) | Express 4、EJS、MySQL | 补充路由、数据库前提和加载时写入副作用 |
| [face-recognition-app](https://github.com/nemo-crypto/face-recognition-app/blob/master/README.md) | MUI、H5+、Demo客户端 | 新增根入口并重写Demo说明，区分模拟核验与真实识别 |
| [flutter-app](https://github.com/nemo-crypto/flutter-app/blob/main/ReadMe.md) | Flutter、Mock/远端Repository | 修正标题、Dart约束、设备命令模板与编译期参数 |
| [monorepo](https://github.com/nemo-crypto/monorepo/blob/main/README.md) | Lerna 3、Xatom源码包 | 区分实际工作区与教程，逐项补充13个模块接入条件 |
| [nemo-crypto](https://github.com/nemo-crypto/nemo-crypto/blob/main/README.md) | README、SVG与文档资源 | 保留作者内容，补充双语和资源维护边界 |
| [next-react](https://github.com/nemo-crypto/Next.js/blob/main/README.md) | Next 13 Pages、MobX | 重写真实路由/环境/9000与5000端口，另存学习笔记 |
| [nuxt-vue3](https://github.com/nemo-crypto/Nuxt.js/blob/main/README.md) | Nuxt 3、Pinia、Keplr | 补齐9090端口、网络映射缺口和外部索引服务依赖 |
| [openlayers](https://github.com/nemo-crypto/openlayers/blob/master/README.md) | 原生页面、OpenLayers | 补充静态预览、资源、坐标与HTTP瓦片说明 |
| [pump-fun-frontend 17.05.23](https://github.com/m8s-lab/pump-fun-frontend/blob/main/README.md) | Next 14、Wallet Adapter、Anchor | 补齐页面与后端边界，指出Mainnet/Devnet连接不一致 |
| [qiankun](https://github.com/nemo-crypto/qiankun/blob/main/README.md) | Vue 2基座、React/Vue/HTML子应用 | 重写主说明并补齐5份子模块说明，核实entry和构建路径 |
| [react-grid-layout](https://github.com/nemo-crypto/react-grid-layout/blob/nemo-test/README.md) | React、Flow、Webpack、Make | 保留原API，新增中文指南和4002开发入口 |
| [resume](https://github.com/nemo-crypto/resume/blob/main/readme.md) | 独立Markdown版本 | 补充交付与版本检查，不修改简历正文 |
| [sentry-react](https://github.com/nemo-crypto/sentry-react/blob/main/README.md) | React Sentry初始化示例 | 明确非独立应用、多次初始化与环境配置适配 |
| [tg-dapp-frontend-template](https://github.com/nemo-crypto/tg-dapp-frontend-template/blob/main/README.md) | Next 14、Telegram SDK、TON | 补齐宿主mock/真实会话边界及缺失构建依赖 |

## 第一方子工程与模块

- agent：ai-fullstack-lab总说明及apps/api、apps/web，核对Go模块、workspace与契约规则。
- face-recognition-app：Demo说明，核对manifest启动路径、MUI公共请求与H5+前提。
- qiankun：main、sub-vue、sub-react、sub-html、common共5份，核对生命周期、entry、UMD、跨域与打包。
- monorepo：translation、translang、bridge、abtest、4个组件包及5个src/modules，共13份，核对main、export、别名与宿主依赖。

## 重要事实修正

- Angular开发服务端口为4201；Next业务项目开发9000、生产5000；Nuxt开发9090；网格源码开发4002。
- Express加载首页路由模块时即进行数据库连接与写入，启动前需要独立测试库和表。
- bit-utils缺少postinstall.js，构建脚本捕获错误后仅打印日志；文档不将其描述为已完成安装/构建。
- Solana钱包Provider使用Mainnet，而交易模块使用独立Devnet连接；设置RPC变量不会自动修复所有连接。
- Nuxt网络映射保留了读取未启用地址字段的分支，需要对齐域名与实际网络。
- Telegram模板Next配置引用@svgr/webpack，但package.json没有直接声明；mock会话不是后端认证。
- Monorepo根README原为另一套搭建教程，已与实际Lerna工作区区分；语言包聚合入口为空，CLI不自动建输出目录。

## 保留内容与范围边界

原始学习/流程记录另存于monorepo/docs/monorepo-design-notes.md、next-react/docs/nextjs-notes.md、bit-utils/docs/original-release-notes.md。这些历史笔记中的模板命令不作为当前工程已实现能力。

React-Grid-Layout英文API、许可和作者说明保留，中文开发指南单独新增；上游Wiki链接改为原仓库绝对地址，只验证链接格式，不验证网络可达性。Flutter flavor模板改标为文本，实际设备命令使用明确的占位标识，须替换后运行。

未检查或改写原始简历正文、环境变量文件的值、第三方SDK源码及其附带README、系统缓存或生成目录。外部地址没有联网验证。

## 校验结果

| 检查 | 结果 |
|---|---|
| 23个一级目录覆盖 | 全部有对应README，并已记录处理结果 |
| 文档修改范围 | 52份Markdown文件，包含第一方子工程及归档笔记 |
| 本地链接与HTML图片路径 | 217项通过 |
| bash/sh/shell代码块语法 | 91段通过，仅使用bash -n检查，不执行命令 |
| npm/yarn/pnpm脚本名称 | 47处与实际package.json匹配 |
| Markdown代码围栏与UTF-8 | 检查通过 |

第一次静态校验发现Flutter设备占位符语法、上游Wiki相对地址、Agent导航层命令目录，均已修正。历史设计笔记的模板命令不作为当前包脚本检查对象。

文档校验通过不代表依赖安装、构建、端到端、设备或生产部署通过；这些需要在对应环境另行执行。


本页为本地多仓库文档索引的远程副本，跨项目链接按各仓库当前分支生成；不要求读者拥有原本地目录。
