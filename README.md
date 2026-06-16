
<p align="center">
  <img src="https://placehold.co/600x150/ffffff/5b5fe7?text=Rigi+Expert+Panel&font=Montserrat" width="500">
</p>

<p align="center">
  <strong>Create AI experts in 3 minutes. Each expert browses, searches, fills forms — out of the box.</strong><br>
  <strong>3 分钟创建一个 AI 专家。每个专家天生会开浏览器、查数据、填表单。</strong>
</p>

<p align="center">
  <a href="https://github.com/xiaoyaotsyx-dotcom/expert-panel/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPLv3-blue"></a>
  <a href="#"><img src="https://img.shields.io/github/stars/xiaoyaotsyx-dotcom/expert-panel"></a>
</p>

---

## What It Does · 做什么

**Give your AI assistant a persona + professional knowledge + browser control = an expert that actually does things.** Not just chatting. Searching data. Filling forms. Posting on social media. Writing reports.

**给 AI 助手配一个人设 + 专业知识 + 浏览器操控 = 真的能干活的专家。** 不只是聊天。查数据、填表单、发社媒、写报告。

---

## vs. Plain Prompts · 对比普通 Prompt

| | Plain Prompt · 普通 Prompt | Rigi Expert · Rigi 专家 |
|------|:---:|:---:|
| Chats · 聊天 | ✅ | ✅ |
| Has a persona · 有人设 | ⚠️ DIY | ✅ Pre-built · 预置 |
| Searches the web · 查数据 | ❌ | ✅ Browser · 浏览器 |
| Fills forms · 填表单 | ❌ | ✅ CDP control · CDP 操控 |
| Posts on social · 发社媒 | ❌ | ✅ 6 platforms · 六平台 |
| Safety boundaries · 安全边界 | ❌ | ✅ Declared per expert · 每个专家声明 |

---

## Pre-built Experts · 预置专家

| Expert · 专家 | What it does · 能力 |
|------|------|
| 📈 **Investment Research**<br>📈 **投研分析** | Multi-source data → cross-validation → 4 research reports.<br>三源数据→交叉验证→四份研报 |
| 🔒 **Security Audit**<br>🔒 **安全审计** | Scrape frontend source → scan for API keys, phone numbers, cloud IDs → audit report.<br>扒前端源码→扫 API key/手机号/云 ID→出审计报告 |
| 🕵️ **Competitive Analysis**<br>🕵️ **竞品分析** | Reverse-engineer AI products → extract prompt architecture → analyze workflow design.<br>逆向 AI 产品→提取提示词架构→分析工作流设计 |

---

## Create Your Own · 创建你自己的专家

```bash
cp -r template/ your-expert-name/
# Edit 4 things: 改四个地方：
#   Persona · 人设
#   Capabilities · 能力
#   Command templates · 命令模板
#   Example dialogues · 示例对话
```

Each expert inherits browser automation by default — no extra config needed.
每个专家默认继承浏览器操控能力——无需额外配置。

---

## Quick Start · 快速开始

```bash
# Load a pre-built expert · 加载预置专家
"Load investment-research skill. Analyze Tesla."
"加载 investment-research skill，分析特斯拉"

# Or create a new one · 或创建新的
"Use the expert template to create a real estate evaluator."
"用专家模板创建一个房产评估专家"
```

> 💡 Works with **Hermes Agent / Claude Code / Cursor**.
> 💡 支持 **Hermes Agent / Claude Code / Cursor**。

---

## Structure · 目录结构

```
expert-panel/
├── template/              ← Creation framework (CDP built-in)
│                            创建框架（内嵌 CDP）
├── investment-research/   ← Pre-built: Investment analyst
│                            预置：投研分析师
├── security-audit/        ← Pre-built: Security auditor
│                            预置：安全审计师
└── competitive-analysis/  ← Pre-built: Competitive analyst
                             预置：竞品分析师
```

---

## License · 许可

**AGPLv3 Dual License · 双许可**

| Use Case · 使用场景 | License · 许可 |
|------|---------|
| Personal · 个人 | AGPLv3 ✅ Free · 免费 |
| Commercial · 商用 | [Contact us · 联系我们](mailto:xiaoyao@aibook.online) |

---

## Contact · 联系

- 📕 RedNote · 小红书: [@瑞吉AI人民公社](https://www.xiaohongshu.com/user/profile/42084313799)
- 📧 xiaoyao@aibook.online
