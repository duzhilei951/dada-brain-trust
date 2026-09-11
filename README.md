# 达达智囊团 (Dada Brain Trust)

> 专为 Cherry Studio 量身定制的多维大师决策推演工作台（MiniApp）。

本应用将曾国藩、爱德华·德·波诺、查理·芒格、范蠡、塞涅卡五路大师的底层心智模型与决策启发式融为一体，提供沉浸式的圆桌推演、实时 Markdown 排版渲染、分歧与共识大盘归纳，以及本地决策档案库。

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Cherry Studio MiniApp](https://img.shields.io/badge/Cherry%20Studio-MiniApp-red.svg)

---

## 一、核心特性

- 🏛 **大师圆桌席位**：集结 5 位古今中外战略与哲学大师（曾国藩、德波诺、芒格、范蠡、塞涅卡）。
- ⚡ **智能并发推演**：根据 Cherry Studio 规范自动进行双路流水线推演，实时流式输出，配合呼吸灯与状态流转。
- 📊 **宽屏黄金排版**：采用一排 3 个宽屏卡片设计，视野更舒展，阅读文字不局促。
- 📝 **Markdown 实时渲染**：各级标题、引用块、有序/无序列表、强调加粗等结构化内容优雅排版。
- 🎯 **综合决策大盘**：推演完成后自动萃取【五路共识】、【分歧与战略张力】、【特别警示】与【行动建议清单】。
- 💾 **Local-First 本地优先**：历史决策自动归档至客户端本地持久化存储，支持一键复盘调阅或复制完整 Markdown 报告。

---

## 二、安装与使用

### 方式一：网络一键安装（推荐，支持后续自动更新）

1. 打开 **Cherry Studio** 客户端；
2. 进入 **Mini Apps / 小程序管理**；
3. 点击 **“从网络安装”**（或通过 URL 安装）；
4. 粘贴下方清单地址并确认：
   ```text
   https://duzhilei951.github.io/dada-brain-trust/manifest.json
   ```

### 方式二：本地文件安装

1. 从本仓库的 `releases/1.0.0/` 目录下下载 `dada-brain-trust.miniapp`；
2. 在 Cherry Studio 小程序管理中选择 **“从本地文件安装”**，选取下载的 `.miniapp` 即可。

---

## 三、仓库文件结构

```text
dada-brain-trust/
├── manifest.json                  # 托管分发清单（供网络安装与自动更新）
├── index.html                     # 小程序主入口（含交互界面与大师知识库）
├── icon.png                       # 256x256 高清应用图标
├── README.md                      # 项目说明文档
└── releases/
    └── 1.0.0/
        └── dada-brain-trust.miniapp  # 1.0.0 标准安装包
```
