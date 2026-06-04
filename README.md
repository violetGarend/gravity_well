# 引力井 — 个人人生导航系统

一个部署在 Claude Code 上的个人人生导航 Skill，代号「引力井」。

## 能力

| 子系统 | 触发方式 | 功能 |
|--------|---------|------|
| 🧭 核心价值观勘探 | `开始勘探` | 苏格拉底式自我追问，逐层深挖，提炼 3 条铁律 |
| 🛰️ 航向偏移雷达 | 描述日常活动 | 6 维度对齐分析，输出结构化报告 |
| ⚡ 快速干预协议 | `我陷入了X` | 3 步骤，5 分钟内可完成的正向扭转 |
| 🏛️ 迭代委员会 | `召开季度委员会` | 多视角复盘，规则修订，季度目标制定 |

## 安装

将本目录复制到 Claude Code 的 skills 路径：

```bash
# 用户级安装（全局可用）
cp -r 引力井/ ~/.claude/skills/引力井/

# 或项目级安装
cp -r 引力井/ your-project/.claude/skills/引力井/
```

## 使用

```
启动引力井
```

首次使用会引导你选择数据存储目录，随后自动进入核心价值观勘探。

## 致谢

本 Skill 内嵌的 5 个人格视角文件由 **Nuwa（女娲）技能作者** 原创制作：

- `references/人格skills/steve-jobs-perspective.md` — 史蒂夫·乔布斯视角
- `references/人格skills/munger-perspective.md` — 查理·芒格视角
- `references/人格skills/elon-musk-perspective.md` — 埃隆·马斯克视角
- `references/人格skills/andrej-karpathy-perspective.md` — Andrej Karpathy 视角
- `references/人格skills/ilya-sutskever-perspective.md` — Ilya Sutskever 视角

## 数据

所有勘探记录、分析报告、会议记录、干预记录存储在你选择的本地目录中，完全属于你。
