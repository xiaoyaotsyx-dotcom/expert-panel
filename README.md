<p align="center">
  <strong>Auto Experts · 自动化 AI 专家</strong>
</p>

<p align="center">
  <strong>Not just another chatbot. A persona-driven AI expert that controls your browser,<br>
  fills forms, writes reports, posts to social media — and works while you sleep.</strong><br>
  <strong>不只是聊天。一个人设驱动的 AI 专家，能操控你的浏览器、填表单、写报告、发社媒——<br>
  在你睡觉的时候替你干活。</strong>
</p>

<p align="center">
  <a href="https://github.com/xiaoyaotsyx-dotcom/auto-experts/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPLv3-blue"></a>
  <a href="#"><img src="https://img.shields.io/github/stars/xiaoyaotsyx-dotcom/auto-experts"></a>
</p>

---

## The Problem · 痛点

You've tried every AI chatbot. They answer questions well enough. But they can't **do** anything.

Ask ChatGPT to "research Tesla stock and write me a report" — it tells you to go look it up yourself. Ask Claude to "post this to my six social accounts" — it apologizes and explains why it can't. The gap between "talking" and "doing" is where 90% of your actual work lives.

你试过各种 AI 聊天。它们聊得不错。但让它们**干活**——搜 10 个网站对比数据、填 ERP 表单、群发六个社媒——它们就歇了。它们只是文字。而你的真正工作，90% 都在"做"这一步。

---

## The Solution · 解决方案

**Auto Experts = AI persona + domain expertise + real browser control.**

**自动化专家 = 人设 + 行业知识 + 真实浏览器操控。**

You give it an identity. It doesn't just advise — it opens **your** Chrome browser with **your** login sessions, searches the web, extracts data, fills your ERP forms, writes structured reports, and publishes to your social accounts. All locally. All on your machine.

你给它一个人设。它不只是给建议——它打开**你的** Chrome 浏览器，用**你的**登录态，搜索网页、提取数据、填你的 ERP 表单、写结构化报告、发布到你的社媒账号。一切都在你电脑上跑。

---

## What Makes Auto Experts Different · 跟普通 AI 有什么不一样

| | Regular AI Chatbot · 普通 AI 聊天 | Auto Expert · 自动化专家 |
|---|---|---|
| Talks · 聊天 | ✅ | ✅ |
| Opens your browser · 开浏览器 | ❌ | ✅ |
| Uses your logins · 用你的登录态 | ❌ | ✅ |
| Fills forms · 填表单 | ❌ | ✅ |
| Posts to social media · 发社媒 | ❌ | ✅ |
| Cross-references 3+ data sources · 三源交叉验证 | ❌ | ✅ |
| Writes structured reports · 写结构化报告 | ❌ | ✅ |
| Works while you're away · 你不在也干活 | ❌ | ✅ |

---

## How It Works · 怎么工作的

```
You: "Analyze NVIDIA stock" · 你："分析英伟达"
          │
          ▼
┌─────────────────────────────────┐
│  Expert loads persona + domain  │
│  knowledge                      │
│  加载人设 + 行业知识库            │
└────────────┬────────────────────┘
             │
             ▼
┌─────────────────────────────────┐
│  Opens YOUR Chrome browser      │
│  (your logins, your sessions)   │
│  打开你的 Chrome 浏览器           │
│  （你的登录态，不过期）            │
└────────────┬────────────────────┘
             │
             ▼
┌─────────────────────────────────┐
│  Searches → Extracts → Fills    │
│  Writes → Posts                 │
│  搜索 → 提取 → 填表 → 写 → 发    │
└────────────┬────────────────────┘
             │
             ▼
       📊 Report ready · 报告好了
```

> 🔒 **Everything runs on your computer. Your logins, your data. Nothing leaves your machine.**
> 🔒 **一切跑在你的电脑上。你的登录态、你的数据。不出你的电脑。**

---

## Pre-built Experts · 预置专家（开箱即用）

| Expert · 专家 | What it does · 做什么 |
|---|---|
| 📈 **Investment Research · 投研分析** | Pulls data from 3 separate sources → cross-validates → produces 4 research reports with scoring, risk flags, and compliance review.<br>三源数据采集 → 交叉验证 → 四份评分研报 + 风险标注 + 合规审查 |
| 🔒 **Security Audit · 安全审计** | Scrapes any public website's frontend JS → scans for exposed API keys, phone numbers, cloud service IDs, infrastructure maps → detailed audit report with severity ratings.<br>扒任意网站前端 JS → 扫 API key / 手机号 / 云 ID / 架构拓扑 → 含严重等级的审计报告 |
| 🕵️ **Competitive Analysis · 竞品分析** | Reverse-engineers competitor AI products → extracts prompt architectures, workflow designs, system patterns via CDP interception + static JS analysis.<br>逆向竞品 AI 产品 → 通过 CDP 拦截 + 静态 JS 分析提取提示词架构、工作流设计、系统模式 |

---

## Build Your Own · 自己创建

Pick a domain. Define a persona. The browser control is already built in.

选一个领域。定一个人设。浏览器操控能力已内置。

```bash
cp -r template/ your-expert/
# Edit 3 files · 改三个文件:
#   SKILL.md      — persona + workflow · 人设 + 工作流
#   README.md     — what it does + who it's for · 做什么 + 谁适合
#   commands.md   — ready-to-paste prompts · 可直接粘贴的命令
```

| Investing · 投资 | Ecommerce · 电商 | Legal · 法律 | Recruiting · 招聘 |
|:---:|:---:|:---:|:---:|
| Real Estate · 房产 | Education · 教育 | Data Hunting · 数据猎手 | Content · 内容创作 |

---

## Quick Start · 快速开始

```bash
# Load a pre-built expert · 加载预置专家
"加载投研分析专家。分析英伟达。"

# Or build your own · 或者自己建
"用模板创建一个房产投资评估专家。"
```

> 💡 Works with **Hermes Agent / Claude Code / Cursor** — any AI that can run Python + control a browser via CDP.
> 💡 支持 **Hermes Agent / Claude Code / Cursor**——能跑 Python + CDP 操控浏览器的 AI 助手都行。

---

## Requirements · 环境要求

- AI assistant with Python + CDP browser control · 支持 Python + CDP 浏览器控制的 AI 助手
- Google Chrome · Chrome 浏览器
- That's it. No cloud. No API keys. No subscriptions.
- 就这些。不上云、不要 API key、不订阅。

---

## License · 许可

| Use Case · 使用场景 | License · 许可 |
|---|---|
| Personal, non-commercial · 个人非商业 | AGPLv3 ✅ Free · 免费 |
| Any business / commercial use · 任何企业/商用 | [Contact us · 联系我们](mailto:Walter.x@qq.com) |

---

## Contact · 联系

- 📕 RedNote · 小红书: [@瑞吉AI人民公社](https://www.xiaohongshu.com/user/profile/42084313799)
- 📧 Walter.x@qq.com

---

*Rigi AI Commons — Your AI can chat. Now make it work.*
*Rigi AI Commons — 你的 AI 会聊天。现在让它真的干活。*