# KB Plugin for Claude Code

个人知识库管理 skills 集合，覆盖：复盘归档、文章提炼、知识写入、健康检查。

## 安装

```
/plugin install jason1314ai/kb
```

## 包含的 Skills

| Skill | 触发词 | 功能 |
|-------|--------|------|
| kb-review | 处理复盘、归档复盘 | 从 `收纳箱/reviews/` 提炼经验洞察 |
| kb-article | 处理文章、总结文章 | 从 `收纳箱/articles/` 提炼核心知识 |
| kb-import | 导入、写入、归档 | 将提炼内容写入个人系统子模块 |
| kb-healthcheck | 检查知识库、有没有冲突 | 扫描知识库冲突、遗漏、结构问题 |

## 知识库结构要求

```
Knowledge Base/
├── 个人系统/[领域]/[子模块].md
└── 收纳箱/
    ├── reviews/    复盘文件
    └── articles/   文章文件
```

使用前需参考知识库 README 初始化目录结构。
