# 🧩 人才发展管理系统 · 高保真交互原型

### *Talent Development Management System — Hi-Fi Interactive Prototype*

> **把散落在 Excel 和聊天记录里的人才信息，收拢成一个 HR 自己能演示、能讲清楚的可视化系统。**  
> 一套 **0 依赖、纯前端、单文件 HTML** 的人才发展管理原型 —— 覆盖工作台、员工档案、阶段评估、委培培养、人才分层矩阵与管理简报，适合 HR / OD / 干部管理同学拿去向内做方案演示、交互评审与交流参考。

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5\&logoColor=white)

![Live Demo](https://img.shields.io/badge/Live_Demo-zoeyan--aihr.github.io-579aca?logo=githubpages\&logoColor=white)

![Stars](https://img.shields.io/github/stars/ZoeYan-AIHR/talent-development-management-system?style=social)

![Last Commit](https://img.shields.io/github/last-commit/ZoeYan-AIHR/talent-development-management-system)

---

## 🔥 为什么会有这个项目？

人才发展 / 干部梯队管理，最难的不是"有没有数据"，而是"能不能一眼看懂、讲给别人听"：

| 😩 常见痛点                | ✅ 这个原型怎么做                        |
| ---------------------- | -------------------------------- |
| 人才信息散在 Excel、花名册、聊天记录里 | 🧩 一个**发展管理工作台**把员工档案、评估、培养动作串起来 |
| 干部梯队 / 继任规划靠脑子记、开会现找   | 🟰 **人才分层矩阵**把分层与缺口可视化，一眼看清板凳深度  |
| 评估记录与后续培养动作脱节          | 📝 阶段评估表单 + **委培 / 培养信息管理**形成闭环  |
| 管理简报每次手工拼 PPT          | 📄 **管理简报**一键生成、预览、导出            |

> 不是要取代 HRIS / 人才系统，而是给 HR 一个**低门槛、可演示、能引发讨论**的方案样本。

## ✨ 特性

- 🖥️ **发展管理工作台** — 核心业务入口，信息一屏掌控
- 👤 **员工列表与员工档案** — 结构化管理人才基础信息与履历
- 📝 **阶段性评估** — 评估记录留痕 + 评估表单，支持持续跟踪
- 🎓 **委培 / 培养信息管理** — 把培养动作和人才绑定，形成发展闭环
- 🟰 **人才分层矩阵** — 可视化人才分层与梯队缺口，辅助继任规划
- 📄 **管理简报** — 生成、预览、导出，汇报不再手工拼装
- 🔐 **系统权限管理** — 演示多角色视角的权限边界
- 🧩 **0 依赖** — 纯 HTML，双击 `index.html` 就能跑，无需构建

## 📂 项目结构

```
talent-development-management-system/
└── cadre-pro-talent-development/   # 干部专业人才发展高保真原型
    ├── index.html                  # 🖥️ 交互原型入口（打开即看）
    ├── README.md                   # 📘 项目说明
    └── NOTICE.md                   # ⚖️ 公开分享与使用说明
```

## 🚀 快速开始

**方式一 · 在线体验（推荐）**  
仓库已启用 GitHub Pages，直接访问：  
👉 <https://zoeyan-aihr.github.io/talent-development-management-system/cadre-pro-talent-development/>

**方式二 · 本地运行**

```bash
# 进入原型目录
cd cadre-pro-talent-development
# 起一个静态服务
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000
```

或直接双击 `index.html`。

## 🗺 路线图（Roadmap）

- [ ] 多维人才画像与九宫格 / 人才地图视图
- [ ] 继任计划的「板凳深度」自动测算
- [ ] 评估模板可配置化（不同序列 / 层级）
- [ ] 管理简报导出为 PDF / 可编辑模板
- [ ] 数据从示例数据切换到可导入的 CSV / JSON

👉 有想法？开 Issue 或 PR，一起把人才发展可视化玩出花。

## 🤝 适合谁看 / 怎么参与

- 👩‍💼 **HRBP / OD / 干部管理** — 拿去对内做方案演示、交互评审
- 🚀 **HR 科技 / 人才系统产品** — 参考信息架构与页面设计思路
- 🎓 **学界 / 学生** — 人才发展、组织发展课程的演示样本

**If you find this useful:**  
⭐ **Star** it · 🍴 **Fork** to make your own · 🐛 **Open an Issue** to give feedback

## ⚠️ 免责声明

- 本仓库为**公开展示的交互原型**，页面内容仅代表设计与原型方案，**不代表已上线的生产系统**。
- 当前 Demo 使用**示例数据**，发布前请确认示例数据、图片、名称及第三方资源均适合公开展示。
- 本原型仅用于**演示、学习、方案交流**，**不应**作为录用、晋升、继任、薪酬等高风险决策的唯一依据。
- 静态审查下，当前 Demo 为纯前端原型，无外部数据传输；如需接入真实数据，请自行评估合规与安全。

## 📄 版权

© 2026 ZoeYan-AIHR. 基于 [MIT License](./LICENSE) 开源。详见 [NOTICE.md](./cadre-pro-talent-development/NOTICE.md)。

---

👤 **关于作者** · [ZoeYan-AIHR](https://github.com/ZoeYan-AIHR) — AI+HR 实践者，10 年金融行业经验，专注用游戏化与 AI 重塑员工体验。
