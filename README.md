
<p align="center">
  <img src="https://placehold.co/600x150/ffffff/5b5fe7?text=Rigi+Expert+Builder&font=Montserrat" width="500">
</p>

<p align="center">
  <strong>AI Automation Expert Builder — Define the persona. We handle the rest.</strong><br>
  <strong>AI 自动化专家工坊 — 你定人设，我们搞定浏览器操控、查数据、填表单、发社媒。</strong>
</p>

<p align="center">
  <a href="https://github.com/xiaoyaotsyx-dotcom/expert-panel/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPLv3-blue"></a>
  <a href="#"><img src="https://img.shields.io/github/stars/xiaoyaotsyx-dotcom/expert-panel"></a>
</p>

---

## What It Does · 做什么

**You define the persona. The expert automatically gets browser control, web search, form filling, and social media posting.** Not a chatbot. An agent that actually does things in the real world.

**你定人设，专家自动获得浏览器操控、网页搜索、表单填写、社媒发布能力。** 不是聊天机器人。是能在真实世界干活的 Agent。

---

## How It Works · 原理

```
  👤 Your Persona           🔧 Our Engine              🤖 Result
  你定义的人设               我们的引擎                   产物

  ┌──────────────┐      ┌──────────────────┐      ┌──────────────┐
  │ 身份 · 性格   │      │ CDP 浏览器操控    │      │              │
  │ 专业知识      │  ×   │ 搜索 · 填表      │  =   │  AI 自动化专家 │
  │ 行业规则      │      │ 抓取 · 发帖      │      │  能聊更能干    │
  └──────────────┘      └──────────────────┘      └──────────────┘
```

---

## What Kind of Experts Can You Build? · 能造什么专家？

> Each use case is a starting point. Copy the template, fill in your persona, and your expert is born with full automation capability.
> 每个场景都是一个起点。复制模板、填入你的人设，专家就自动具备全套自动化能力。

| Domain · 领域 | Example Expert · 示例专家 | What They Can Do · 能干什么 |
|------|------|------|
| 📈 投资 | 投研分析师 | 拉三源数据→交叉验证→出研报 / Multi-source data → research reports |
| ⚖️ 法律 | 法律顾问 | 审合同→标风险点→查法规 / Review contracts → flag risks |
| 💼 招聘 | HR 猎头 | 筛简历→匹配 JD→出评估 / Screen resumes → match requirements |
| 🌍 跨境 | 跨境电商顾问 | 选品分析→竞品调研→趋势判断 / Product research → competitor analysis |
| 🏠 房产 | 房产评估师 | 查挂牌价→比成交价→出估值 / Check listings → compare prices → valuation |
| 🎓 教育 | 学习教练 | 出题→批改→个性化辅导 / Create exercises → grade → personalized tutoring |
| 🔍 数据 | 数据猎手 | 全网搜索→结构化提取→分析报告 / Web search → structured extraction → analysis |
| 🕵️ 竞品 | 竞品侦探 | 逆向 AI 产品→提取提示词→分析架构 / Reverse-engineer → extract prompts |

---

## Pre-built Examples · 预置示例（开箱即用）

> 3 fully-built experts you can load immediately. Study them to learn the pattern, then build your own.
> 3 个完整专家可直接加载。先看它们怎么做的，然后造你自己的。

| Expert · 专家 | What they do · 能力 | Load it · 加载 |
|------|------|------|
| 📈 **Investment Research · 投研分析** | 三源数据→交叉验证→四份研报 | `investment-research/` |
| 🔒 **Security Audit · 安全审计** | 扒前端源码→扫敏感信息→出报告 | `security-audit/` |
| 🕵️ **Competitive Analysis · 竞品分析** | 逆向AI产品→提取提示词架构 | `competitive-analysis/` |

---

## Create Your Own · 创建你自己的专家（3 分钟）

```bash
# 1. Copy the template · 复制模板
cp -r template/ my-expert/

# 2. Fill in 4 things · 改四个地方：
#    SKILL.md      → Persona + capabilities · 人设 + 能力
#    README.md     → Introduction + safety rules · 介绍 + 安全边界
#    命令模板.md    → 6-9 copy-paste commands for users · 用户可直接粘贴的命令
#    examples/     → 2 real conversation examples · 两个真实对话示例

# 3. Done. Your expert automatically has:
#    搞定。你的专家自动具备：
#    ✅ Browser control · 浏览器操控
#    ✅ Web search · 网页搜索
#    ✅ Form filling · 表单填写
#    ✅ Social posting · 社媒发布 (X/微博/知乎/头条/小红书)
```

> 💡 All automation capabilities are inherited from `shared/` — zero extra config.
> 💡 所有自动化能力继承自 `shared/`——零额外配置。

---

## Quick Start · 快速开始

```bash
# Use a pre-built expert · 用预置专家
"Load investment-research skill. Analyze Tesla."
"加载 investment-research skill，分析特斯拉"

# Build your own · 自己造一个
"Use the expert template. Create a 房产评估专家 that checks Beijing housing prices."
"用专家模板创建一个房产评估专家，能查北京房价"
```

> 支持 Hermes Agent / Claude Code / Cursor。任何能跑 Python + CDP 的 AI 助手。

---

## Requirements · 环境要求

- AI assistant with Python execution + CDP browser control · 支持 Python + CDP 的 AI 助手
- Google Chrome (your own login) · Chrome 浏览器（你自己的登录态）

---

## License · 许可

**AGPLv3 Dual License · 双许可**

| Use Case · 使用场景 | License · 许可 |
|------|---------|
| Personal, non-commercial · 个人非商业 | AGPLv3 ✅ Free · 免费 |
| Any company or commercial use · 任何企业/商用 | [Contact us · 联系我们](mailto:Walter.x@qq.com) |

---

## Contact · 联系

- 📕 RedNote · 小红书: [@瑞吉AI人民公社](https://www.xiaohongshu.com/user/profile/42084313799)
- 📧 Walter.x@qq.com

---

*Rigi AI Commons — Reject AI echo chambers. Democratize practical AI for everyone.*
*Rigi AI Commons — 拒绝 AI 小圈子自嗨，推动实用 AI 全面普惠。*
