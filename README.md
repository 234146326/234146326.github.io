# ⚡ XUGUO ｜ Jerry - 极客标签导航与管理站

> 纯静态、高颜值、支持 GitHub PAT 验证与在线实时云端管理的个人标签导航系统。

[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?style=flat-square&logo=github)](https://234146326.github.io/)
[![Tailwind CSS](https://img.shields.io/badge/Styled%20with-Tailwind%20CSS-38bdf8?style=flat-square&logo=tailwindcss)](https://tailwindcss.com/)
[![Alpine.js](https://img.shields.io/badge/Powered%20by-Alpine.js-8bc500?style=flat-square&logo=alpinedotjs)](https://alpinejs.dev/)

---

## ✨ 核心特性

- **极客暗黑风 UI**：基于 Tailwind CSS 与 Alpine.js 打造，响应式布局，支持多分类筛选与实时关键字检索。
- **无服务器云端同步**：摆脱传统数据库，利用 GitHub Pages 作为静态托管，通过前端直接调用 GitHub REST API 实现数据持久化。
- **安全零落盘机制**：后台管理采用 GitHub Personal Access Token (PAT) 动态验证，密钥仅暂存于浏览器会话内存中（关闭页面即销毁），绝对安全。
- **一键全网生效**：在网页后台轻点“同步”，即可自动提交并更新仓库中的 `data.json`，由 GitHub Pages 自动重新部署上线。

---

## 🛠️ 快速部署与使用指南

1. **克隆或将源码放入根目录**：
   确保你的 `234146326.github.io` 仓库根目录下包含以下核心文件：
   - `index.html`（前台展示与后台管理主程序）
   - `data.json`（标签与网址数据源）
   - `README.md`（说明文档）

2. **开启 GitHub Pages 服务**：
   - 进入你的仓库 -> 点击 **Settings** -> **Pages**。
   - 在 **Build and deployment** 下方，选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/ (root)`，点击 **Save**。

3. **配置并使用后台管理**：
   - 访问你的线上网址：[https://234146326.github.io/](https://234146326.github.io/)
   - 点击右上角的 **“后台管理”** 按钮。
   - 输入具备 `Contents: Read and write` 权限的 GitHub Personal Access Token 验证解锁。
   - 自由添加或删除网址，点击同步即可！

---

## 📄 License

&copy; 2026 **XUGUO ｜ Jerry**. Open source under the MIT License.
