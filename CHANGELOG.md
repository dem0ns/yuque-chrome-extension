# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.3.5](https://github.com/yuque/yuque-chrome-extension/compare/v0.3.2...v0.3.5) (2023-08-02)


### Features

* 更换应用图标 ([#59](https://github.com/yuque/yuque-chrome-extension/issues/59)) ([0c2fd92](https://github.com/yuque/yuque-chrome-extension/commit/0c2fd92e109394e6c4cd43c5015a904867f93faf))
* 仅离线版本 crx 做更新检查 ([11bae3f](https://github.com/yuque/yuque-chrome-extension/commit/11bae3ff7ee22770db06bad05bb5c0bf29e40819))
* 使用 lake 编辑器 ([#67](https://github.com/yuque/yuque-chrome-extension/issues/67)) ([0d19b22](https://github.com/yuque/yuque-chrome-extension/commit/0d19b220bd2d29b35911aa54dfc190bfbf1415a2))
* 支持构建 crx 文件产物以支持离线使用场景 ([#65](https://github.com/yuque/yuque-chrome-extension/issues/65)) ([6713b8f](https://github.com/yuque/yuque-chrome-extension/commit/6713b8f6496efbbd76d3652fd2744ceb842a1540))
* ui 组件库升级到 antd 5 ([#56](https://github.com/yuque/yuque-chrome-extension/issues/56)) ([aa71988](https://github.com/yuque/yuque-chrome-extension/commit/aa719882c332e2769d331a34b6635baab0838e0f))


### Bug Fixes

* 调整插件版本号展示位置 ([#60](https://github.com/yuque/yuque-chrome-extension/issues/60)) ([6c4398a](https://github.com/yuque/yuque-chrome-extension/commit/6c4398a9156a22be71c3b80688fbc386516370dc))
* 过滤掉非文档类型的知识库 ([#61](https://github.com/yuque/yuque-chrome-extension/issues/61)) ([ee0f261](https://github.com/yuque/yuque-chrome-extension/commit/ee0f261a0d03966385ea17dac7db14c4edbdf9ee))
* 修复暗黑模式下的遮罩问题 & 修改插件名称 ([#72](https://github.com/yuque/yuque-chrome-extension/issues/72)) ([e9cc641](https://github.com/yuque/yuque-chrome-extension/commit/e9cc641de3174723207bd2a25ed34ee4ffbbd473))
* 修复确认选取按钮点击失效 ([#58](https://github.com/yuque/yuque-chrome-extension/issues/58)) ([5516c7e](https://github.com/yuque/yuque-chrome-extension/commit/5516c7e86423a26609711327d8867dc96fad3b3d))
* 修复组件 props 传参错误 ([#63](https://github.com/yuque/yuque-chrome-extension/issues/63)) ([fb325a2](https://github.com/yuque/yuque-chrome-extension/commit/fb325a223fa602019b736b04dc2f2a5d6f65197c))
* 移除无用的 forwardRef ([#64](https://github.com/yuque/yuque-chrome-extension/issues/64)) ([f995bb2](https://github.com/yuque/yuque-chrome-extension/commit/f995bb283cc83e7e7149c3cc213f8732e79b5bda))
* 优化 content-script 实现避免出现注入按钮被原有站点的样式覆盖 ([#62](https://github.com/yuque/yuque-chrome-extension/issues/62)) ([1b905b9](https://github.com/yuque/yuque-chrome-extension/commit/1b905b9004396303b0e48a900b8a40211de5bfed))

### [0.3.2](https://github.com/yuque/yuque-chrome-extension/compare/v0.3.1...v0.3.2) (2023-07-25)


### Bug Fixes

* 更新 feedback url ([#52](https://github.com/yuque/yuque-chrome-extension/issues/52)) ([737f1ee](https://github.com/yuque/yuque-chrome-extension/commit/737f1eed7aeb3da765be73f41bd412a61a1f02f2))

### [0.3.1](https://github.com/yuque/yuque-chrome-extension/compare/v0.3.0...v0.3.1) (2023-07-25)


### Features

* 保存成功后收起整个剪藏工具面板 ([#49](https://github.com/yuque/yuque-chrome-extension/issues/49)) ([0f8f320](https://github.com/yuque/yuque-chrome-extension/commit/0f8f320cce76196ebe9690cd32df2cc2427da30c))
* 支持 h1 到 h6 的剪藏 ([#46](https://github.com/yuque/yuque-chrome-extension/issues/46)) ([9133777](https://github.com/yuque/yuque-chrome-extension/commit/9133777cc2e326399ce008aadb06fe7c15cac902))


### Bug Fixes

* 清理掉 manifest.json 中未使用的 permission ([#50](https://github.com/yuque/yuque-chrome-extension/issues/50)) ([744bf21](https://github.com/yuque/yuque-chrome-extension/commit/744bf2147eaf567bb0d6ed4f9872545d42d9fa2b))
* 继续选取时不再提取当前页面的信息 ([#51](https://github.com/yuque/yuque-chrome-extension/issues/51)) ([666e46a](https://github.com/yuque/yuque-chrome-extension/commit/666e46a0a4bb2146834d1f347cf9d844896a933b))
* 解决反序列化导致节点丢失块信息出现任意键入后回删文本和图片的问题 ([#45](https://github.com/yuque/yuque-chrome-extension/issues/45)) ([895bd97](https://github.com/yuque/yuque-chrome-extension/commit/895bd97f8d7c6cda400e3b64340a8dac3f3ddba1))
* 请求 updates.xml 时使用 no-cache 策略 ([#47](https://github.com/yuque/yuque-chrome-extension/issues/47)) ([11b9187](https://github.com/yuque/yuque-chrome-extension/commit/11b91872bf98ee41009400fca551c04d054b393c))
* 调整 继续选取 到多选剪藏下 ([#48](https://github.com/yuque/yuque-chrome-extension/issues/48)) ([b321903](https://github.com/yuque/yuque-chrome-extension/commit/b321903102e20e46b88df1202e0a40857478ce20))

## [0.3.0](https://github.com/yuque/yuque-chrome-extension/compare/v0.2.1...v0.3.0) (2023-07-25)


### Bug Fixes

* 调整 book 选择器实现避免类型问题 ([#42](https://github.com/yuque/yuque-chrome-extension/issues/42)) ([a6cfc78](https://github.com/yuque/yuque-chrome-extension/commit/a6cfc788f4040e7592ab4b11cca8e479e1bbdc7f))

### [0.2.1](https://github.com/yuque/yuque-chrome-extension/compare/v0.2.0...v0.2.1) (2023-07-24)


### Features

* 保存后复原编辑器 ([#19](https://github.com/yuque/yuque-chrome-extension/issues/19)) ([3d208dd](https://github.com/yuque/yuque-chrome-extension/commit/3d208ddeb9688ba84f1e3b746c2747b038ad3d67))
* 去掉整页剪藏 ([#35](https://github.com/yuque/yuque-chrome-extension/issues/35)) ([1670e78](https://github.com/yuque/yuque-chrome-extension/commit/1670e7811271166ac5083c6663d4d3b8703bc4e3))
* 右键选择文字剪藏添加引用 ([#18](https://github.com/yuque/yuque-chrome-extension/issues/18)) ([657572c](https://github.com/yuque/yuque-chrome-extension/commit/657572c7cd57efb62c29ecb17c39874e327c07fb))
* 将 js 改为 ts ([#28](https://github.com/yuque/yuque-chrome-extension/issues/28)) ([659dcf5](https://github.com/yuque/yuque-chrome-extension/commit/659dcf5774bd600053f9d69cef4ad1a2449450ed))
* 支持自动检查新版本 ([#34](https://github.com/yuque/yuque-chrome-extension/issues/34)) ([3390af3](https://github.com/yuque/yuque-chrome-extension/commit/3390af39389a9d3333ddfd9d1f90014e0a299287))
* 新增剪藏编辑器工具栏 ([#12](https://github.com/yuque/yuque-chrome-extension/issues/12)) ([59a4cbb](https://github.com/yuque/yuque-chrome-extension/commit/59a4cbb80c028e0ca40419de2294ee5485579d26))
* 添加登录提示信息 ([#22](https://github.com/yuque/yuque-chrome-extension/issues/22)) ([fc01c7e](https://github.com/yuque/yuque-chrome-extension/commit/fc01c7e9030a3a02381b4ff876cc342d9d6cf4a2))
* 请求头增加 runtime.id ([#29](https://github.com/yuque/yuque-chrome-extension/issues/29)) ([e009a25](https://github.com/yuque/yuque-chrome-extension/commit/e009a252933cc376bd16f3e3af6ecd44c0cf44e1))


### Bug Fixes

* ci failed ([#33](https://github.com/yuque/yuque-chrome-extension/issues/33)) ([1d12843](https://github.com/yuque/yuque-chrome-extension/commit/1d1284382f59b2cfe27351d6f1a54d765fbab7db))
* 新增文档目录不展示问题 ([#21](https://github.com/yuque/yuque-chrome-extension/issues/21)) ([0a2e0b8](https://github.com/yuque/yuque-chrome-extension/commit/0a2e0b8f52e292bb6b5bb69774eca5057befab5b))
* 确保剪藏内容保存到文档去除网页引用标题 ([#20](https://github.com/yuque/yuque-chrome-extension/issues/20)) ([ee6a415](https://github.com/yuque/yuque-chrome-extension/commit/ee6a4155ce7d2d5c689a37c8a1e63af4ffc91991))
* 补充升级新版本的翻译 ([#36](https://github.com/yuque/yuque-chrome-extension/issues/36)) ([65b5ff5](https://github.com/yuque/yuque-chrome-extension/commit/65b5ff5f4c56983fd8193eca4a1b86200c0e3f9e))
* 解决 content-script 中全局 app 变量冲突的问题 ([#30](https://github.com/yuque/yuque-chrome-extension/issues/30)) ([e32cd90](https://github.com/yuque/yuque-chrome-extension/commit/e32cd90690cc52cfd51c262da6d6a4cd93d54fd5))
