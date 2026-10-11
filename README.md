# 🎮 WeCAT 演示 - HTML 小游戏 Demo 合集

<div align="center">

**一系列开箱即玩的网页小游戏 Demo** —— 无需安装、无需构建，点开链接即可游玩 🚀

[![在线体验](https://img.shields.io/badge/🎮_在线体验-GitHub_Pages-58a6ff?style=for-the-badge)](https://yangxbao.github.io/wecat-demo/)
[![License](https://img.shields.io/badge/📜_License-MIT-3fb950?style=for-the-badge)](./LICENSE)
[![Language](https://img.shields.io/badge/🧩_技术-纯前端_HTML-e3b341?style=for-the-badge)](#-目录结构)

</div>

---

## 📖 项目简介

**WeCAT 演示** 是一个纯前端 HTML 小游戏 Demo 合集，收录了多个独立完整的网页小游戏与界面演示。所有游戏均为**单文件实现**（HTML + CSS + JavaScript 内嵌），零依赖、零构建，可直接部署在 GitHub Pages 上在线游玩，也可以下载后在本地直接打开。

适合用于：🎉 休闲娱乐、📚 前端学习参考、🎮 小游戏原型借鉴。

## 🕹️ 游戏目录

> 点击「在线游玩」即可直接开玩，无需任何配置。

| 游戏 | 类型 | 简介 | 在线游玩 |
|---|---|---|---|
| ✈️ 雷霆1942 · 幸存者版 | 飞行射击 | 纵版飞行射击生存游戏，直触操控，弹幕中求生 | [▶ 立即游玩](https://yangxbao.github.io/wecat-demo/games/thunder-1942/) |
| 🐟 深海进化 · 大鱼吃小鱼 | 休闲益智 | 吞食小鱼不断成长进化，称霸深海食物链 | [▶ 立即游玩](https://yangxbao.github.io/wecat-demo/games/fish-evolution/) |
| ⛏️ 摸金突围 · Loot Raid | 地宫夺宝 | 深入地宫搜刮宝物、捡装备、突围而出 | [▶ 立即游玩](https://yangxbao.github.io/wecat-demo/games/loot-raid/) |
| 🦢 抓大鹅 · 搞怪版 | 整蛊互动 | 火遍全网的抓大鹅搞怪版，内置照片彩蛋 | [▶ 立即游玩](https://yangxbao.github.io/wecat-demo/games/catch-goose/) |
| 💬 微信叛逆版 | 界面演示 | 微信界面高仿演示：朋友圈 / 钱包 / 扫码 / 支付流程 | [▶ 查看演示](https://yangxbao.github.io/wecat-demo/demos/wechat-rebel/) |

## 📁 目录结构

```text
wecat-demo/
├── index.html              # 🏠 游戏导航主页（GitHub Pages 入口）
├── games/                  # 🎮 小游戏合集（一个游戏一个目录）
│   ├── thunder-1942/       # ✈️ 雷霆1942 · 幸存者版（飞行射击）
│   ├── fish-evolution/     # 🐟 深海进化 · 大鱼吃小鱼
│   ├── loot-raid/          # ⛏️ 摸金突围 · Loot Raid
│   └── catch-goose/        # 🦢 抓大鹅 · 搞怪版（含 p/ 图片资源）
├── demos/                  # 🧪 非游戏类界面演示
│   └── wechat-rebel/       # 💬 微信叛逆版（含 manifest.json）
├── README.md               # 📄 项目说明文档
└── LICENSE                 # 📜 MIT 开源协议
```

## 🚀 使用说明

### 方式一：GitHub Pages 在线访问（推荐）

1. 打开项目主页入口：**<https://yangxbao.github.io/wecat-demo/>**
2. 在导航页点击任意游戏卡片即可开始游玩；
3. 也可以通过上表中的直达链接直接进入单个游戏。

> 💡 本仓库已开启 GitHub Pages（部署 `main` 分支根目录）。推送代码后会自动重新部署，稍等 1~2 分钟即可看到最新版本。

### 方式二：本地打开

**方法 A —— 直接双击**

所有游戏均为单文件实现，直接双击对应目录下的 `index.html` 即可在浏览器中运行（除「抓大鹅」需通过本地服务器启动，见下）。

**方法 B —— 本地服务器（推荐）**

```bash
# 1. 克隆仓库
git clone https://github.com/Yangxbao/wecat-demo.git
cd wecat-demo

# 2. 任选一种方式启动本地服务器
python -m http.server 8080        # Python
npx serve .                       # Node.js

# 3. 浏览器访问
# http://localhost:8080
```

> 💡 「抓大鹅」需要加载 `p/` 目录下的图片资源，请务必使用本地服务器方式打开。

## 📸 截图展示

> 🚧 截图陆续补充中，敬请期待……

<!-- 📷 截图预留区：截好游戏画面后，保存到 docs/screenshots/ 目录（文件名见下），
     然后删除本注释即可自动显示。

| ✈️ 雷霆1942 | 🐟 深海进化 |
|:---:|:---:|
| ![雷霆1942](docs/screenshots/thunder-1942.png) | ![深海进化](docs/screenshots/fish-evolution.png) |
| **⛏️ 摸金突围** | **🦢 抓大鹅** |
| ![摸金突围](docs/screenshots/loot-raid.png) | ![抓大鹅](docs/screenshots/catch-goose.png) |

-->


## 🛠️ 技术栈

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=flat-square)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?logo=githubpages&logoColor=white&style=flat-square)

- 🧩 纯原生 HTML / CSS / JavaScript，单文件自包含，无框架依赖
- 📱 适配桌面与移动端（触屏操作）
- 🔓 全部源码开放，欢迎学习与二次创作

## 🤝 贡献

欢迎提交 [Issue](https://github.com/Yangxbao/wecat-demo/issues) 和 [Pull Request](https://github.com/Yangxbao/wecat-demo/pulls)！新增游戏请遵循现有结构：**一个游戏一个独立目录**，并同步更新 README 游戏目录表。

## 📜 开源协议

本项目基于 [MIT License](./LICENSE) 开源，你可以自由地使用、修改和分发本项目代码，请保留原始协议声明。

> ⚠️ 注意：游戏中的美术素材、品牌名称（如「微信」界面演示）仅用于学习与演示目的，版权归原作者所有，请勿用于商业用途。

---

<div align="center">

**觉得不错的话，给个 Star ⭐ 支持一下吧！**

Made with ❤️ by [Yangxbao](https://github.com/Yangxbao)

</div>
