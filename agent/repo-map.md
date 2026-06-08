---
canonical: false
status: repo-map
use_rule: 仓库地图与层级路由说明；不得替代 current-canon、稳定风格画像或主框架文件。
---
# Repository Map / 仓库地图

## 层级路由表

| 层级 | 路径 | 引用规则 |
|------|------|----------|
| 书稿层（当前正典） | `book/`, `manuscript/` | 可直接引用 |
| Agent 路由层 | `agent/` | 用于导航和索引 |
| **原文暂存层（入口层）** | `originals/` | ⚠️ 入口层，不得直接作为已完成哲学命题引用；等待 GPT 审阅 |
| **已处理历史数据层（追溯层）** | `source-history/` | ⚠️ 仅供追溯；不得重复作为未处理材料反复提炼 |
| 对话碎片层 | `human/` | 不得作为已完成哲学命题引用 |
| 编辑与项目元记录层 | `editor/` | 不得作为理论证据 |
| 结构化数据层 | `data/` | 可引用为结构化数据 |
| 历史归档层 | `archive/` | 不得作为当前结论引用 |

## Agent 流水线权限图

```
Flash  ──→  originals/           (只写入，不改写，不提炼)
GPT    ──→  审阅意见             (给提炼意见)
Pro    ──→  提炼结果 + 移动原文到 source-history/
```

## 流水线规则

1. **Flash**：只允许将新原文导入 `originals/`。不改写、不提炼、不修改 `book/` 或 `manuscript/`。
2. **GPT**：审阅 `originals/` 中的材料，给出提炼意见。
3. **Pro**：只在 GPT 给出提炼意见后执行结构化提炼。完成提炼后必须将对应原文移动到 `source-history/`，并在 frontmatter 中写明 `derived_to`。不得将原始对话碎片直接当成书稿结论。

## 入口文件优先级

1. AGENT_ENTRY.md
2. README.md
3. llms.txt
4. agent/repo-map.md（本文件）

updated_at: 2026-06-08
