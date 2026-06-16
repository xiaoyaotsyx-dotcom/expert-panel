
<p align="center">
  <img src="https://placehold.co/600x150/ffffff/5b5fe7?text=Auto+Experts&font=Montserrat" width="500">
</p>

<p align="center">
  <strong>AI experts that don't just chat — they operate your browser, fill forms, crunch data, and work while you sleep.</strong><br>
  <strong>不只是聊天的 AI 专家。它能操控你的浏览器、填表单、分析数据、在你休息时替你干活。</strong>
</p>

<p align="center">
  <a href="https://github.com/xiaoyaotsyx-dotcom/auto-experts/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPLv3-blue"></a>
  <a href="#"><img src="https://img.shields.io/github/stars/xiaoyaotsyx-dotcom/auto-experts"></a>
</p>

---

## The Problem · 痛点

You've tried AI chatbots. They give decent answers. But they can't **do** anything.

You've tried AI chatbots. They talk. But when you need them to actually search 10 websites, cross-reference data, fill an ERP form, or post to six social platforms — they stop. They're just text.

你试过各种 AI 聊天。它们聊得不错。但当你让它们**真的动手**——搜 10 个网站、交叉对比数据、填 ERP 表单、群发六个社媒平台——它们就歇了。只是文字。

---

## The Solution · 解决方案

**Auto Experts = AI persona + domain knowledge + browser control.**

每个专家 = 人设 + 行业知识 + 浏览器操控能力。

Give your AI an identity (investment analyst, security auditor, content strategist) and it doesn't just give advice — it opens Chrome, searches, fills forms, downloads data, writes reports, and posts on your behalf.

给它一个人设，它不只是给建议——它打开你的 Chrome，搜索、填表、下载数据、写报告、替你发帖。

---

## Who Is This For · 谁适合用

| You are a... · 你是... | You need... · 你需要... | An Auto Expert can... · 自动化专家能... |
|------|------|------|
| 📈 Independent investor · 独立投资者 | Research reports · 研报 | Pull 3 data sources → cross-validate → write report · 三源交叉验证出研报 |
| 🛒 Cross-border seller · 跨境卖家 | Product listings · 上架 | 1688 sourcing → ERP forms → publish · 采集填表发布 |
| 🔒 Security researcher · 安全研究员 | Site audits · 审计 | Scrape frontend → scan for leaks → audit report · 扒源码扫漏洞 |
| 🕵️ Product manager · 产品经理 | Competitor analysis · 竞品分析 | Reverse-engineer AI products → extract architecture · 逆向 AI 产品 |
| 📱 Content creator · 内容创作者 | Multi-platform posting · 多平台发布 | Write once → post to 6 platforms · 一次写六平台发 |

---

## How It Works · 怎么工作的

```
You say: "Analyze Tesla stock" · 你说："分析特斯拉"
          │
          ▼
┌─────────────────────────────────┐
│  Auto Expert loads persona +    │
│  domain knowledge               │
│  加载人设 + 行业知识              │
└────────────┬────────────────────┘
             │
             ▼
┌─────────────────────────────────┐
│  Opens YOUR Chrome browser      │
│  (your login, your session)     │
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
       📊 Report ready
       报告写好了
```

> 🔒 **Everything runs on your computer. Your logins, your data. Nothing leaves your machine.**
> 🔒 **一切跑在你的电脑上。你的登录态、你的数据。不出你的电脑。**

---

## Pre-built Experts · 预置专家

| Expert · 专家 | What it does · 做什么 |
|------|------|
| 📈 **Investment Research** · 投研分析 | Pull data from 3 sources → cross-validate → 4 research reports with scoring.<br>三源数据采集 → 交叉验证 → 四份评分研报 |
| 🔒 **Security Audit** · 安全审计 | Scrape any website's frontend → scan for exposed API keys, phone numbers, cloud IDs → audit report.<br>扒任意网站前端源码 → 扫 API key / 手机号 / 云 ID → 审计报告 |
| 🕵️ **Competitive Analysis** · 竞品分析 | Reverse-engineer AI products → extract prompt engineering architecture → workflow design.<br>逆向 AI 产品 → 提取提示词架构 → 工作流设计分析 |

---

## Build Your Own · 自己创建

Pick a domain. Define the persona. The browser capability is built-in.

选一个领域。定一个人设。浏览器操控能力已内置。

```bash
cp -r template/ your-expert-name/
# Edit: persona · 能力 · 命令模板 · 示例对话
```

**8 domains you can build for · 8 个可选领域：**

| Investing · 投资 | Ecommerce · 电商 | Legal · 法律 | Recruiting · 招聘 |
|:---:|:---:|:---:|:---:|
| Real Estate · 房产 | Education · 教育 | Data Hunting · 数据猎手 | Content · 内容创作 |

---

## Quick Start · 快速开始

```bash
# Load a pre-built expert · 加载预置专家
"Load investment-research. Analyze NVIDIA stock."
"加载 investment-research。分析英伟达。"

# Or build one · 或者自己建
"Use the template. I need a real estate investment evaluator."
"用模板创建一个房产投资评估专家。"
```

> 💡 Works with **Hermes Agent / Claude Code / Cursor** — any AI that can run Python + control a browser via CDP.
> 💡 支持 **Hermes Agent / Claude Code / Cursor**——能跑 Python + CDP 操控浏览器的 AI 助手都行。

---

## Requirements · 环境要求

- AI assistant with Python execution + CDP browser control · 支持 Python + CDP 的 AI 助手
- Google Chrome · Chrome 浏览器
- That's it. No cloud. No API keys. No subscriptions.
- 就这些。不上云、不要 API key、不订阅。

---

## License · 许可

**AGPLv3 Dual License · 双许可**

| Use Case · 使用场景 | License · 许可 |
|------|---------|
| Personal, non-commercial · 个人非商业 | AGPLv3 ✅ Free · 免费 |
| Any business / commercial use · 任何企业/商用 | [Contact us · 联系我们](mailto:Walter.x@qq.com) |

---

## Contact · 联系

- 📕 RedNote · 小红书: [@瑞吉AI人民公社](https://www.xiaohongshu.com/user/profile/42084313799)
- 📧 Walter.x@qq.com

---

*Rigi AI Commons — Your AI can chat. Now make it work.*
*Rigi AI Commons — 你的 AI 会聊天。现在让它真的干活。*
