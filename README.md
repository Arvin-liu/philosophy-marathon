# 《哲学马拉松》（暂名）/ Philosophy Marathon

这是《哲学马拉松》（暂名）的长期思想书稿仓库，用来整理我与不同 AI 进行的长篇哲学、意识、自我、时间、AI、记忆、系统、人生策略等对话。

它不是聊天记录垃圾堆，而是一本逐渐成形的书。仓库同时服务两类读者：人类读者与 AI Agent。

## Project Positioning / 项目定位

《哲学马拉松 / Philosophy Marathon》不是一本简单托管在 GitHub 上的书稿，而是一个 **Agent-readable book project**，也是一个 **AI-readable open knowledge repository**。

它同时面向两类读者：

1. **人类读者**：通过 `book/`、`SUMMARY.md` 和正文叙述进入关于自我、意识、时间、记忆、AI、人机共思和长期生命策略的哲学对话。
2. **AI Agent 读者**：通过 `llms.txt`、`llms-full.txt`、`agent/` 和 `data/` 快速读取概念、问题、论点、对话索引和开放问题。

因此，本项目更准确地说是一部：

- 版本化思想书
- 开放内容型知识仓库
- 面向人类与 AI 双读者的书籍工程
- 可被检索、引用、改写和继续推进的长期哲学对话基础设施

它不是把书稿“放到 GitHub”而已，而是把一本书改造成一个能被人类和 AI 同时读取、引用、重组、传播和继续生长的系统。

## English abstract

Title: Philosophy Marathon

Description: A long-form philosophical book project based on extended human-AI dialogues about self, consciousness, time, memory, systems, and human-AI co-thinking.

## Reading entrances

人类读者从 [SUMMARY.md](SUMMARY.md) 进入，再阅读 `book/`。

AI Agent 从 [llms.txt](llms.txt) 进入，再按 `agent/reading-path.md` 读取。

## Repository structure

```text
book/     面向人类读者的正式书稿层
human/    人类阅读材料、片段、笔记和 essay seeds
agent/    AI Agent 友好的摘要、概念、论点、问题、索引和术语表
data/     结构化 CSV 数据层
```

## Current status

当前版本只初始化双层书籍结构。尚未导入原始长篇对话材料，因此大多数正文和数据文件是结构占位，不包含未经确认的具体哲学内容。

## Privacy and source discipline

整理原始对话时，只保留思想摘要和可公开表达的概念结构。不要写入密码、Token、身份证、银行卡、精确住址、私钥、API Key 或其他敏感信息。

## License / 许可协议

本仓库是一个非商业开放内容项目。

本仓库中的书稿正文、概念说明、章节内容、案例整理、Agent-readable materials，除特别说明外，均采用：

License: **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**  
中文：**知识共享署名—非商业性使用—相同方式共享 4.0 国际许可协议**  
Short name: **CC BY-NC-SA 4.0**

你可以自由阅读、复制、传播、引用、改编本作品，但必须遵守以下条件：

1. **署名 Attribution**：必须保留作者署名与原始仓库链接。
2. **非商业 NonCommercial**：不得将本作品或其改编作品用于商业目的。
3. **相同方式共享 ShareAlike**：如果你改编、转换或基于本作品继续创作，发布时必须采用相同或兼容的许可协议。
4. **不得暗示背书 No endorsement**：不得暗示原作者认可你的使用方式、观点或改编版本。

完整协议见：

- `LICENSE`
- `NOTICE.md`

说明：本项目更准确地说是“非商业开放内容项目”，而不是 OSI 意义上的软件开源项目。因为本项目禁止商业使用。
