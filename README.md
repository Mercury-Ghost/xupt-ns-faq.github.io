# 西邮计算机学院 · 新生 FAQ 网站

> 西安邮电大学计算机学院 2026 级新生常见问题汇总  
> 在线查阅 · 亮色/暗色主题 · 全平台适配

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-在线访问-1a5cff?logo=github)](https://Mercury-Ghost.github.io/xupt-ns-faq/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📌 项目简介

本项目是为 **西邮计算机学院 2026 级新生** 整理的常见问题（FAQ）网站，内容基于 QQ 新生群的真实提问整理而成，涵盖：

- 🏠 宿舍（床位、空调、门禁等）
- 🎖️ 军训
- 📚 学习（晚自习、实验班、编程语言等）
- 🍜 食堂与生活
- 🚌 校园交通与环境
- 🧪 社团与实验室
- ⭐ 团员与入党
- 📦 报到与分班
- 🔒 防骗提醒
- 📌 其他常见问题

**共收录 58 个问题**，持续更新中。

---

## ✨ 功能特点

- **🔍 实时搜索** – 输入关键词快速定位问题
- **🌓 亮色/暗色主题** – 手动切换或跟随系统偏好
- **📱 全平台适配** – 完美支持手机、平板、电脑
- **⌨️ 键盘快捷键** – `Ctrl/Cmd + K` 聚焦搜索，`ESC` 清空搜索
- **📄 纯静态页面** – 无需后端，托管于 GitHub Pages

---

## 🚀 在线访问

[https://Mercury-Ghost.github.io/xupt-ns-faq/](https://Mercury-Ghost.github.io/xupt-ns-faq/)

---

## 📂 项目结构

```
.
├── index.html          # 主页面（包含所有 HTML + CSS + JavaScript）
├── README.md           # 项目说明文档
└── (可选) CNAME        # 自定义域名文件
```

---

## 🛠️ 如何维护与更新

所有 FAQ 数据都存储在 `index.html` 中的 `faqData` 数组里，**无需修改任何其他代码**。

### 添加/修改/删除问题

1. 在 `index.html` 中找到 `faqData` 数组（位于 JavaScript 区域开头）：
   ```javascript
   const faqData = [
       { category: "分类名", q: "你的问题", a: "你的答案" },
       // ...
   ];
   ```

2. 按以下格式操作：
   - **新增**：复制一行，修改 `category`、`q`、`a` 内容。
   - **修改**：直接编辑对应字段。
   - **删除**：删掉整行。

3. 保存文件并推送到 GitHub 仓库，网站会自动更新。

### 支持 HTML 标签

答案（`a` 字段）支持 `<strong>`、`<b>`、`<span class="highlight">` 等标签，可用于强调重点。

---

## 🤝 贡献指南

欢迎提出改进建议或补充新问题！

- **报告问题**：请在 GitHub Issues 中提交，说明具体问题或建议。
- **提交修改**：Fork 本仓库，修改后提交 Pull Request。

---

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE)，你可以自由使用、修改和分发。

---

## 📬 联系方式

如有任何疑问，可以在 QQ 新生群中联系班助，或通过 GitHub Issues 反馈。

---

**持续更新中** · 最后更新：2026 年 8 月 9 日
