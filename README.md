<div align="center">

# Dora Skill Hub

**面向学习与软件开发的可复用 AI Agent 技能与工作流合集**

[![Markdown](https://img.shields.io/badge/Markdown-2563EB?style=flat-square)](./README.md)
[![Codex Skills](https://img.shields.io/badge/Codex%20Skills-0F766E?style=flat-square)](./learning)
[![Focus](https://img.shields.io/badge/Focus-%E5%AD%A6%E4%B9%A0%20%26%20%E5%B7%A5%E7%A8%8B%E5%AE%9E%E8%B7%B5-7C3AED?style=flat-square)](#%E6%8A%80%E8%83%BD%E4%B8%8E%E5%B7%A5%E4%BD%9C%E6%B5%81%E7%9B%AE%E5%BD%95)

</div>

---

## 📌 项目简介

**Dora Skill Hub** 收录面向日常**学习规划、知识管理、学科辅导**与**软件开发工程实践**的可复用 Agent 技能与工作流，支持在 Codex 或其他兼容 `SKILL.md` 规范的智能体环境中按需载入。

## 🧩 技能与工作流目录

### 📚 学习技能（Learning）

| 技能 | 核心方向 | 能力说明 |
| :--- | :--- | :--- |
| [**数学辅导（Mathematics Tutor）**](learning/math-tutor/SKILL.md) | 习题复盘与推导 | 结合过程与依据逐步批改习题、讲透推导细节与易错点。 |
| [**政治辅导（Politics Tutor）**](learning/politics-tutor/SKILL.md) | 概念理解与记忆 | 核验权威来源、拆解核心概念、分析典型题型并辅助主动回忆。 |
| [**专业课辅导（Professional-Course Tutor）**](learning/professional-course-tutor/SKILL.md) | 课程学习与评估 | 讲解课程核心知识、评估独立作答并制定阶段性复习计划。 |
| [**词汇辅导（Vocabulary Tutor）**](learning/vocabulary-tutor/SKILL.md) | 语境记忆与巩固 | 通过语境练习与进度追踪，系统化学习并复习英语词汇。 |

### 💻 软件开发（Software Development）

| 工作流 | 核心方向 | 能力说明 |
| :--- | :--- | :--- |
| [**通用开发工作流（Development Workflow）**](software-development/README.md) | 端到端工程实践 | 覆盖代码库调研、变更规划、代码审查与自动化验证的通用流程。 |

## 📁 项目结构

```text
dora-skillhub/
├── learning/                                # 通用学习与学科辅导技能
│   ├── math-tutor/SKILL.md
│   ├── politics-tutor/SKILL.md
│   ├── professional-course-tutor/SKILL.md
│   └── vocabulary-tutor/SKILL.md
└── software-development/                    # 软件开发工作流与工程实践
    └── README.md
```

## 🚀 快速开始

1. **选择技能**：进入 `learning/` 或 `software-development/` 目录，查看对应 `SKILL.md` 或说明文档。
2. **安装载入**：将所需技能目录复制到 Codex 的技能目录，或按所使用 Agent 工具的规范进行适配。
3. **结合上下文使用**：实际使用时以当前仓库规范与最新学习资料为准，按需微调提示词与复盘节奏。

## 🔒 隐私与开源说明

本仓库所有内容均已面向公开复用进行通用化处理，不包含任何个人学习记录、私有工作区路径、账号信息或个人测验历史。
