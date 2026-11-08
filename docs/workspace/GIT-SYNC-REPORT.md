# 本地更新、匿名化与远程提交记录

核对时间：2026-11-08T23:59:30+08:00。范围为chovy下23个Git仓库。

## 结果

- 23个仓库均已完成远程获取和本地提交，工作区干净；22个已推送并通过远程分支哈希核对。
- Telegram模板的远程更新已合并，包括构建忽略规则、环境模板和宿主运行要求；README冲突保留双方有效内容。
- Pump前端的本地提交已保留，原远程仓库返回403，当前账号没有写权限，未强制推送或改投其他仓库。
- 本地根目录不是Git仓库，总导航与README检查清单已另存为本文所在文档仓库的远程副本。

## 当前版本匿名化与验证

指定品牌及大小写变体共替换117个文本文件、707处引用，使用DemoExchange、某数字资产平台和中性示例路径。源码、简历和多语言文案在本次扫描范围内；未改写已有Git历史。

| 检查 | 实际结果 |
|---|---|
| 可提交文本扫描 | 扫描2461个文件，替换后目标字段残留0；合并后再次扫描无残留 |
| 多语言JSON | 97份解析通过，键/类型结构不变，1259处插值占位符保持一致 |
| 修改的JS/TS/JSX | 10份Next源码语法检查通过；其余改动为注释、正则配置及文档 |
| 配置行为 | 本地图标回退、配置静态域名、缺省WS不连接、配置WS连接、可配置语言字段检查通过 |
| Next完整类型检查 | tsc --noEmit --pretty false，退出0、诊断0 |
| README静态检查 | 52份原修改文档，最终219处本地链接、91段Shell语法、47个脚本入口通过 |

字体已改为系统字体。图标优先使用STATIC_URL，缺省提供本地SVG；WS通过WEBSOCKET_URL接入，缺省不主动连接；请求语言参数默认language，可用LANGUAGE_PARAM_NAME适配。示例链接不是已经上线的业务服务。

本轮更新指Git远程提交同步，没有批量升级框架或npm依赖，也没有运行真实业务服务、设备、模型或部署。

## 仓库提交与远程状态

| 本地目录 | 分支 | 提交 | 远程状态 |
|---|---|---|---|
| QA-Automation | `main` | [068babae](https://github.com/nemo-crypto/QA-Automation/commit/068babae1797dfcc28dd26a6de8f4d92a467eeea) | 已推送且哈希一致 |
| SignalAtlas | `main` | [149d52b0](https://github.com/nemo-crypto/SignalAtlas/commit/149d52b02654017f811ec4695e1bbe9de3a3f8dc) | 已推送且哈希一致 |
| activity-dev-plug-in | `main` | [06e08d18](https://github.com/nemo-crypto/activity-dev-plug-in/commit/06e08d1807cc548033f6751aeacbada09ba9ef03) | 已推送且哈希一致 |
| agent | `main` | [6677be94](https://github.com/nemo-crypto/agent/commit/6677be94d6adb0a5746d1ee97e00d33524d9a6c3) | 已推送且哈希一致 |
| angular6-material | `master` | [772ce718](https://github.com/nemo-crypto/angular6-material/commit/772ce718d6bc55f2249c338ecbffb7a32e38e448) | 已推送且哈希一致 |
| bit-request | `main` | [b402cce9](https://github.com/nemo-crypto/bit-request/commit/b402cce958a10121771593089c020f46dbafd5c8) | 已推送且哈希一致 |
| bit-utils | `main` | [395602b3](https://github.com/nemo-crypto/bit-utils/commit/395602b393571f3b17092a348b7fd0d423cfca59) | 已推送且哈希一致 |
| comment-app | `master` | [522402d1](https://github.com/nemo-crypto/uni-app/commit/522402d1d16abbefff9db305ac8065ec5e53af2f) | 已推送且哈希一致 |
| common-interview-coding-questions | `main` | [9b888f99](https://github.com/nemo-crypto/SmartContract/commit/9b888f9928ff37abf210e7bbd5cbd760ebe04b8c) | 已推送且哈希一致 |
| express | `master` | [a2361854](https://github.com/nemo-crypto/express/commit/a2361854957be6b7abfc9b19b6d7a886cabcd5f5) | 已推送且哈希一致 |
| face-recognition-app | `master` | [f6771518](https://github.com/nemo-crypto/face-recognition-app/commit/f6771518d8e8f646898a2310e71daabe42b0c9f2) | 已推送且哈希一致 |
| flutter-app | `main` | [5f865aa3](https://github.com/nemo-crypto/flutter-app/commit/5f865aa37bee4bd22287dcd68e5dbaf2790eee7e) | 已推送且哈希一致 |
| monorepo | `main` | [5bfe75f7](https://github.com/nemo-crypto/monorepo/commit/5bfe75f7d09f8966450d898a24b5f6fb51d6bd05) | 已推送且哈希一致 |
| nemo-crypto | `main` | [当前报告分支](https://github.com/nemo-crypto/nemo-crypto/tree/main) | 已推送且哈希一致 |
| next-react | `main` | [49daf7b7](https://github.com/nemo-crypto/Next.js/commit/49daf7b7ed8c9f16838994318ba5491a9091bbbf) | 已推送且哈希一致 |
| nuxt-vue3 | `main` | [e74246bf](https://github.com/nemo-crypto/Nuxt.js/commit/e74246bffe27fe8e0fa4f8dd5a9d640a51df291b) | 已推送且哈希一致 |
| openlayers | `master` | [9663a8f4](https://github.com/nemo-crypto/openlayers/commit/9663a8f48aabbb3ec530bdf6c611ec11eb093243) | 已推送且哈希一致 |
| pump-fun-frontend 17.05.23 | `main` | `dde9bf78` | 本地已提交，远程403 |
| qiankun | `main` | [299e4fb5](https://github.com/nemo-crypto/qiankun/commit/299e4fb5e285c50aa2249a35b6a76b74e4746305) | 已推送且哈希一致 |
| react-grid-layout | `nemo-test` | [ef9f1860](https://github.com/nemo-crypto/react-grid-layout/commit/ef9f18600b2a81609a001a2645c04623c9e80ac6) | 已推送且哈希一致 |
| resume | `main` | [59c49883](https://github.com/nemo-crypto/resume/commit/59c49883ffc9b73bb5c238321e70eff430f461b1) | 已推送且哈希一致 |
| sentry-react | `main` | [b48996b0](https://github.com/nemo-crypto/sentry-react/commit/b48996b0226851ee00f9899758cca78f75fc2b5f) | 已推送且哈希一致 |
| tg-dapp-frontend-template | `main` | [3317efc8](https://github.com/nemo-crypto/tg-dapp-frontend-template/commit/3317efc83242f40f7514eb36070d9a8b844e02c4) | 已推送且哈希一致 |

报告所在仓库会追加文档提交，表内使用当前分支链接；其他提交哈希按上述核对时刻记录。

## 已迁移远程地址

| 本地目录 | 当前origin |
|---|---|
| comment-app | [https://github.com/nemo-crypto/uni-app.git](https://github.com/nemo-crypto/uni-app) |
| common-interview-coding-questions | [https://github.com/nemo-crypto/SmartContract.git](https://github.com/nemo-crypto/SmartContract) |
| nuxt-vue3 | [https://github.com/nemo-crypto/Nuxt.js.git](https://github.com/nemo-crypto/Nuxt.js) |
| next-react | [https://github.com/nemo-crypto/Next.js.git](https://github.com/nemo-crypto/Next.js) |

## 尚未完成的远程推送

Pump前端：原目标为 `https://github.com/m8s-lab/pump-fun-frontend.git`，当前账号nemo-crypto收到Permission denied / HTTP403。本地提交 `dde9bf78` 与工作区均已保留，需要原仓库写权限或用户指定有权限的远程目标后才能完成该项推送。
