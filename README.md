# VPS 剩余价值计算器

一个好用的剩余价值计算器，帮助您快速计算续费周期内剩余天数及对应的货币价值，并支持多币种换算、交易溢价对比与分享链接生成。

![界面预览](https://hellooe.github.io/vps)

---

## ✨ 功能特点

- **纯 HTML + CSS + JavaScript**，无外部依赖。
- **数据存储**：使用 `localStorage` 和 `sessionStorage` 持久化大部分字段，避免重复输入。
- **汇率 API**：调用 [Exchange Rate API](https://open.er-api.com/) 的免费端点（`v6/latest/`），失败时提示手动输入。
- **日期处理**：完全基于 UTC 时间戳计算，避免本地时区影响。
- **URL 参数解析**：支持通过 `?price=...&end=...` 等参数预填表单，实现分享功能。

---

## 📄 许可

[MIT License](https://opensource.org/licenses/MIT) — 可自由使用、修改、分发。

---

## 🤝 贡献

欢迎提交 Issue 或 Pull Request 改进功能或修复问题。

---

**理性消费，从我做起** 💡
