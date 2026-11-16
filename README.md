# GameX · 监考模拟器插画首版

本仓库是插画首版的独立部署仓库，只测试、构建和发布本版本。

- 试玩：https://lep-ton.github.io/gamex-proctor-illustrated/
- 权威源码：[LeP-Ton/gamex-proctor-simulator 的 codex/illustrated 分支](https://github.com/LeP-Ton/gamex-proctor-simulator/tree/codex/illustrated)。
- 本次固定源码：`40616f584199eae1b49c44cbed0cbc7bdc30800b`。
- 运行时文件与上述源码一致；独立工作流、本文及发布来源说明属于部署适配。
- 发布来源详见 [deployment.json](public/deployment.json)。源码与需求文档在原仓库维护，本仓库历史提交保留同步记录。

Node.js 20.19+：`npm ci`、`npm test`、`npm run build`。本版本分支推送后自动在独立 `github-pages` 环境部署，另一版本不参与构建。
