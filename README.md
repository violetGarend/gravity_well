# 引力井 (Gravity Well) — 个人人生导航系统

> 基于开放的 [Agent Skills 协议](https://agentskills.io/specification)，可在 **Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode** 等 50+ 兼容运行时中运行。

## 能力

| 子系统 | 触发方式 | 功能 |
|--------|---------|------|
| 🧭 核心价值观勘探 | `开始勘探` | 苏格拉底式自我追问，逐层深挖，提炼 3 条铁律 |
| 🛰️ 航向偏移雷达 | 描述日常活动 | 6 维度对齐分析，输出结构化报告 |
| ⚡ 快速干预协议 | `我陷入了X` | 3 步骤，5 分钟内可完成的正向扭转 |
| 🏛️ 迭代委员会 | `召开季度委员会` | 多视角复盘，规则修订，季度目标制定 |

## 安装

```bash
# 用户级安装（全局可用）
cp -r 引力井/ ~/.claude/skills/gravity-well/

# 项目级安装
cp -r 引力井/ your-project/.claude/skills/gravity-well/
```

## 使用

```
启动引力井
```

首次使用会引导你选择数据存储目录，随后自动进入核心价值观勘探。

## 目录结构

```
gravity-well/
├── SKILL.md                         ← 入口：触发词调度 + 核心规则
├── README.md
├── references/                      ← 按需加载
│   ├── 勘探.md                      ← 子系统1 完整流程
│   ├── 雷达.md                      ← 子系统2 分析模板
│   ├── 干预.md                      ← 子系统3 三步骤协议
│   ├── 委员会.md                    ← 子系统4 议程+角色模拟
│   └── 人格skills/                  ← 5个人格视角文件
│       ├── steve-jobs-perspective.md
│       ├── munger-perspective.md
│       ├── elon-musk-perspective.md
│       ├── andrej-karpathy-perspective.md
│       └── ilya-sutskever-perspective.md
└── assets/                          ← 模板文件
    ├── 铁律模板.md
    ├── 运营日志模板.md
    └── 日志索引模板.md
```

## 致谢

本 Skill 内嵌的 5 个人格视角文件由 **[Nuwa（女娲）](https://github.com/alchaincyf)** 原创制作，基于各人物公开言论、授权传记和访谈提炼。每个文件文末均有完整署名和来源声明。

## 许可

MIT
