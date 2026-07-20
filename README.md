# Agent Card Editor

> Visually design A2A-compliant Agent Cards with live JSON preview.
> 可视化设计符合 A2A 规范的 Agent Card，实时预览 JSON。

A web-based editor for creating [A2A Protocol](https://github.com/a2a-ai/A2A) Agent Cards without writing JSON by hand. Fill in forms, see the JSON update in real-time, validate, and export.

一个用于创建 [A2A 协议](https://github.com/a2a-ai/A2A) Agent Card 的 Web 编辑器，不用手写 JSON。填表 → 实时预览 → 校验 → 导出。

---

## Quick Start | 快速开始

Just open `index.html` in a browser. No build, no install.

直接在浏览器中打开 `index.html`，无需构建或安装。

Or serve it locally:
```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

Then open http://localhost:8000 in your browser.

---

## Features | 功能

- **Form-based editor** — fill in fields, no JSON syntax errors
- **Live JSON preview** — see the output as you type
- **Skills management** — add/remove multiple skills with examples
- **Validation** — required fields highlighted, URL format check
- **Import / Export** — load existing JSON, copy or download
- **Bilingual (EN/ZH)** — toggle language on the fly
- **Syntax highlighting** — JSON preview with color coding
- **Dark theme** — comfortable for long editing sessions
- **No dependencies** — single HTML file, works offline

---

## Supported Fields | 支持的字段

| Section | Field | EN | 中文 |
|---------|-------|----|----|
| Basic | name | Agent name | Agent 名称 |
| Basic | description | Description | 描述 |
| Basic | url | Endpoint URL | 端点 URL |
| Basic | version | Version | 版本 |
| Basic | iconUrl | Icon URL | 图标 URL |
| Provider | organization | Org name | 组织名称 |
| Provider | url | Org URL | 组织 URL |
| Capabilities | capabilities | streaming / pushNotifications / stateTransitionHistory / extensions | 能力开关 |
| Capabilities | defaultInputModes | text / file / data | 默认输入模式 |
| Capabilities | defaultOutputModes | text / file / data | 默认输出模式 |
| Skills | id, name, description, examples | per-skill config | 单技能配置 |

---

## License

MIT
