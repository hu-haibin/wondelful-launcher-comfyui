
<div align="center">

# ModelFinder

### 🚀 ComfyUI 一站式管理启动器

**一键部署 · 智能分析 · 模型匹配 · 极致体验**

[![GitHub Release](https://img.shields.io/github/v/release/hu-haibin/ModelFinder-Releases?style=for-the-badge&logo=github&label=最新版本)](https://github.com/hu-haibin/ModelFinder-Releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/hu-haibin/ModelFinder-Releases/total?style=for-the-badge&logo=github&label=下载量)](https://github.com/hu-haibin/ModelFinder-Releases/releases)
[![Platform](https://img.shields.io/badge/平台-Windows%2010%2F11-0078D6?style=for-the-badge&logo=windows)](https://github.com/hu-haibin/ModelFinder-Releases/releases/latest)

[**📥 立即下载**](https://github.com/hu-haibin/ModelFinder-Releases/releases/latest) · [**📋 更新日志**](https://github.com/hu-haibin/ModelFinder-Releases/releases) · [**🐛 反馈问题**](https://github.com/hu-haibin/ModelFinder-Releases/issues)

---

</div>

## ✨ 为什么选择 ModelFinder？

ModelFinder 是一款专为 **ComfyUI** 用户打造的 Windows 桌面启动器与管理工具。无论你是刚入门 AI 绘画的萌新，还是管理多个工作流的高阶玩家，ModelFinder 都能让你的 ComfyUI 使用体验更简单、更高效。

> 💡 **告别黑窗口，告别复杂配置，告别缺模型报错** —— 从部署到出图，一个工具全搞定。

---

## 🎯 核心功能

### 🖱️ 一键部署 ComfyUI

无需手动配置 Python 环境和下载 ComfyUI 源码，只需几次点击即可完成：

- **版本选择**：支持选择 ComfyUI 官方发布版本
- **CUDA/CPU 自动识别**：根据硬件自动匹配最佳运行模式
- **可视化安装进度**：下载、解压、配置全过程可视化，告别黑窗口焦虑
- **路径冲突检测**：智能提示目标路径问题，避免安装失败
- **失败重试与手动导入**：安装中断可恢复，已有便携包也能一键接管

### 📦 多实例管理

轻松管理多个 ComfyUI 便携包环境：

- **接管现有 ComfyUI 便携包**：已有的 ComfyUI 直接导入管理，不影响原有配置
- **一键切换默认实例**：在不同项目/工作流配置之间秒切
- **实例重命名 / 卸载**：自由管理，保持整洁
- **独立启动参数配置**：每个实例可设定不同的端口、显存策略、启动参数

### 🔍 工作流智能分析

加载 ComfyUI 工作流文件（JSON/PNG），ModelFinder 会自动帮你排查：

- **缺失自定义节点检测**：识别工作流所需的自定义节点插件，列出未安装项
- **缺失模型检测**：扫描工作流引用的模型文件，定位缺失项
- **生成补全清单**：一键跳转到模型匹配/插件安装，快速补齐依赖

> 🎯 **拿到别人的工作流再也不用挨个猜缺什么模型了！**

### 🔗 模型来源匹配与下载

找到工作流缺失的模型后，ModelFinder 帮你自动匹配下载源：

- **多源匹配**：支持 HuggingFace、HuggingFace Mirror（国内加速）、ModelScope 魔搭社区
- **智能入队**：匹配后一键加入下载队列，放入正确的模型目录
- **断点续传**：大模型下载中断也不怕，续传无压力

### 🧩 插件管理

ComfyUI 自定义节点插件的管理利器：

- **已安装插件浏览**：查看当前安装的所有自定义节点
- **依赖分析**：识别插件的 Python 依赖，定位安装问题
- **目录操作**：直接管理插件文件目录

### 📊 硬件监控

实时了解你的硬件运行状况：

- **GPU 显存 / 使用率监控**：直观查看显卡负载
- **CPU / 内存占用**：同步监控系统资源
- **网速监控**：了解下载/上传状态

### ⬇️ 下载中心

全局统一的下载任务管理：

- **集中管理**：所有下载任务统一排队、统一进度展示
- **断点续传**：网络波动、意外中断均可恢复
- **失败重试**：一键重试失败任务

---

## 🎨 用户界面

ModelFinder 采用 **Windows Fluent Design** 设计语言，深色主题为主，提供现代、沉浸式的操作体验：

- 🌙 **深色模式**：经过精心调校的深灰色调，长时间使用不疲劳
- 💎 **毛玻璃效果**：半透明悬浮操作岛，高级感拉满
- ✨ **流畅动画**：页面切换与交互动效丝滑流畅
- 📐 **紧凑/舒适密度模式**：可根据屏幕大小和个人偏好调节 UI 密度
- 🎮 **游戏启动器式交互**：借鉴 Starward 等优秀启动器的右下角悬浮操作岛设计，伸手就能操作

---

## 💻 系统要求

| 项目 | 要求 |
|------|------|
| **操作系统** | Windows 10 (22H2+) / Windows 11 |
| **运行时** | 无需额外安装（已内置） |
| **磁盘空间** | 启动器本体约 ~100 MB |
| **显卡** | 运行 ComfyUI 建议 NVIDIA GPU（已有 CUDA 支持） |

> 📌 ModelFinder 本身是启动器/管理工具，ComfyUI 的运行需求取决于你要跑的模型和工作流。

---

## 📥 安装与使用

### 下载安装

1. 前往 [**Releases 页面**](https://github.com/hu-haibin/ModelFinder-Releases/releases/latest) 下载最新版本
2. 解压到任意目录（建议非系统盘）
3. 运行 `ModelFinder.exe` 即可启动

> 💡 **免安装便携版**，解压即用，不写注册表，不污染系统环境。

### 快速上手

1. **首次启动** → 通过部署向导一键安装 ComfyUI
2. **加载实例** → 已有 ComfyUI 便携包？直接导入接管
3. **一键启动** → 在主界面点击启动按钮，控制台实时显示运行日志
4. **工作流分析** → 拖入工作流文件，自动检测缺失模型和插件
5. **补全依赖** → 按照分析结果一键下载缺失模型、安装缺失插件

---

## 🔄 从旧版升级

如果你之前使用的是 **ComfyLauncher**（v1.3.x 及更早版本）：

- ModelFinder 会**自动迁移**你的配置数据和实例信息
- 首次通过旧入口启动时会显示一次性品牌变更提示
- 新旧可执行文件名均可识别，升级无缝衔接

---

## 🗺️ 产品路线图

| 状态 | 功能 |
|------|------|
| ✅ 已完成 | 一键部署 ComfyUI |
| ✅ 已完成 | 多实例管理 |
| ✅ 已完成 | 工作流分析与缺失检测 |
| ✅ 已完成 | 模型来源匹配（HuggingFace / ModelScope） |
| ✅ 已完成 | 插件管理与依赖分析 |
| ✅ 已完成 | 硬件监控 |
| ✅ 已完成 | 下载中心（断点续传） |
| 🔄 开发中 | 模型管理（本地浏览/搜索/清理） |
| 🔄 开发中 | 资源透视（多盘空间管理） |
| 📋 计划中 | 批量任务队列 |

---

## ❓ 常见问题

<details>
<summary><b>Q: ModelFinder 和绘世启动器有什么区别？</b></summary>

ModelFinder 专注于 ComfyUI 的**智能管理**体验，核心差异化在于：
- **工作流智能分析**：自动识别工作流所需的模型和插件，减少「缺节点/缺模型」的排查时间
- **模型来源匹配**：支持从 HuggingFace / ModelScope 等多源匹配和下载缺失模型
- **现代 UI 设计**：Windows Fluent Design 风格，深色主题，毛玻璃效果，操作体验更沉浸

</details>

<details>
<summary><b>Q: 需要单独安装 Python 或 .NET 吗？</b></summary>

**不需要。** ModelFinder 是独立运行的便携程序，所有依赖已内置。ComfyUI 的 Python 环境由部署向导自动配置。

</details>

<details>
<summary><b>Q: 支持接管已有的 ComfyUI 便携包吗？</b></summary>

**支持。** 在实例/包管理页面可以直接导入你已有的 ComfyUI 目录，ModelFinder 不会修改你的原有文件。

</details>

<details>
<summary><b>Q: 是否支持 macOS 或 Linux？</b></summary>

目前仅支持 **Windows 10/11**。跨平台支持暂未列入近期计划。

</details>

<details>
<summary><b>Q: 这个工具免费吗？</b></summary>

**免费使用。** ModelFinder 当前版本完全免费。

</details>

---

## 🤝 反馈与交流

- **Bug 反馈 / 功能建议**：请在 [Issues](https://github.com/hu-haibin/ModelFinder-Releases/issues) 中提交
- **如果觉得好用**：请给个 ⭐ Star，这是对作者最大的鼓励！

---

## 📄 许可与声明

ModelFinder 是闭源软件，仅在此仓库发布编译后的可执行程序。  
本项目与 ComfyUI 官方无隶属关系，ComfyUI 是独立的开源项目。

---

<div align="center">

**ModelFinder** — 让 ComfyUI 的使用，从「部署地狱」变成「开箱即用」  

Made with ❤️ for the AI Art Community

</div>
