[English](./README_EN.md) | 中文

---

# Agent Card Editor

> Visually design A2A-co mpliant Agent Cards with live JSON preview.
>  可视化设计符合 A2A 规范的 Agent Ca rd，实时预览 JSON。

[![CI](https://git hub.com/Erich956389473/agent-card-editor/acti ons/workflows/ci.yml/badge.svg)](https://gith ub.com/Erich956389473/agent-card-editor/actio ns/workflows/ci.yml)
[![License: MIT](https:/ /img.shields.io/badge/License-MIT-blue.svg)]( LICENSE)
[![npm version](https://img.shields. io/npm/v/agent-card-editor)](https://www.npmj s.com/package/agent-card-editor)

A web-based  editor for creating [A2A Protocol](https://g ithub.com/a2a-ai/A2A) Agent Cards without wri ting JSON by hand. Fill in forms, see the JSO N update in real-time, validate, and export.
 
一个用于创建 [A2A 协议](https://gith ub.com/a2a-ai/A2A) Agent Card 的 Web 编辑� ��，不用手写 JSON。填表 → 实时预 览 → 校验 → 导出。

---

## Quick S tart | 快速开始

Just open `index.html` i n a browser. No build, no install.

直接在 浏览器中打开 `index.html`，无需构� �或安装。

Or serve it locally:
```bash
#  Python
python -m http.server 8000

# Node
np x serve .
```

Then open http://localhost:800 0 in your browser.

---

## Features | 功能 

- **Form-based editor** — fill in fields,  no JSON syntax errors
- **Live JSON preview* * — see the output as you type
- **Skills m anagement** — add/remove multiple skills wi th examples
- **Validation** — required fie lds highlighted, URL format check
- **Import  / Export** — load existing JSON, copy or do wnload
- **Bilingual (EN/ZH)** — toggle lan guage on the fly
- **Syntax highlighting** � � JSON preview with color coding
- **Dark the me** — comfortable for long editing session s
- **No dependencies** — single HTML file,  works offline

---

## Supported Fields | � �持的字段

| Section | Field | EN | 中� � |
|---------|-------|----|----|
| Basic | n ame | Agent name | Agent 名称 |
| Basic | d escription | Description | 描述 |
| Basic |  url | Endpoint URL | 端点 URL |
| Basic |  version | Version | 版本 |
| Basic | iconUr l | Icon URL | 图标 URL |
| Provider | orga nization | Org name | 组织名称 |
| Provid er | url | Org URL | 组织 URL |
| Capabilit ies | capabilities | streaming / pushNotifica tions / stateTransitionHistory / extensions |  能力开关 |
| Capabilities | defaultInput Modes | text / file / data | 默认输入模� �� |
| Capabilities | defaultOutputModes | te xt / file / data | 默认输出模式 |
| Ski lls | id, name, description, examples | per-s kill config | 单技能配置 |

---

## Lice nse

MIT
 