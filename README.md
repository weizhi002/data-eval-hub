# DataEval Hub

公开的数据评测与基准测试平台

**DataEval Hub** 是一个现代化、开放、透明的公开数据评测平台，支持社区共同贡献模型在各类公开数据集上的评测结果，建设透明可信的基准测试生态。

## 🌐 网站地址

https://weizhi002.github.io/data-eval-hub/

> 注：首次部署需要手动启用 GitHub Pages，见下方指南。

## ✨ 特点

- 📊 交互式 Leaderboard（可搜索、排序、筛选）
- 👩‍💻 简单提交评测结果（通过 GitHub Issue）
- 🌍 全开放、可复现的评测数据
- 🔄 支持多领域：语言、代码、多模态、数据质量等

## 🚀 如何启用 GitHub Pages（必须）

1. 进入仓库 **Settings** 设置
2. 在左侧菜单找到 **Pages**
3. **Source** 选择 **Deploy from a branch**
4. **Branch** 选择 `main`，**Folder** 选择 `/ (root)`
5. 点击 **Save**
6. 等待 1-2 分钟，网站就可以通过 https://weizhi002.github.io/data-eval-hub/ 访问

## 🤝 如何贡献

最简单的方式是通过 **GitHub Issue** 提交新的评测结果：

1. 在网站点击“提交评测结果”按钮
2. 填写表单后自动生成 Issue 模板
3. 提交即可

也可以直接提交 PR 到 `data/` 目录。

## 📄 技术栈

- 静态 HTML + Tailwind CSS (CDN)
- 原生 JavaScript 实现交互式表格
- 完全可托管于 GitHub Pages

---

由 weizhi002 使用 Grok 帮助创建 | 欢迎 Star 和贡献！