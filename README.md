# AI 交互体验集

三个实验产品的公开入口：实时语音助手、主动交互和数字生命档案。

## 发布范围

- 数字生命档案：公开静态网页，数据只保存在当前浏览器；公开构建不包含云端 AI 对话。
- 实时语音助手：macOS Apple Silicon 开发者 Beta 下载包；需要使用者自行配置 Azure GPT-Live 服务。
- 主动交互：macOS 发布候选包保存在 `packages/`，在专利与发布审批解除前不进入公开 `dist/`。

## 目录

- `dist/`：公开站点与已批准的下载文件。
- `packages/`：本轮生成的本地发布包和候选包。
- `.openai/hosting.json`：Sites 部署配置。

实时语音助手的大文件下载由 GitHub Releases 托管；站点源码只保存对应的 SHA-256 校验文件。
