
![cover](screenshots/github_cover.jpg)


# Lifein — 让 Obsidian 长成你喜欢的样子

[English](./README.md) | [中文](./README_ZH.md)

[![Downloads](https://img.shields.io/badge/dynamic/json?logo=obsidian&color=%237c3aed&label=downloads&query=%24%5B%22Lifein%22%5D.download&url=https%3A%2F%2Freleases.obsidian.md%2Fstats%2Ftheme)](https://github.com/ichris007/Lifein-theme) ![Obsidian](https://img.shields.io/badge/dynamic/json?query=%24.minAppVersion&url=https%3A%2F%2Fraw.githubusercontent.com%2Fichris007%2FLifein-theme%2Fmain%2Fmanifest.json&label=Obsidian&color=7c3aed&prefix=v) [![GitHub stars](https://img.shields.io/github/stars/ichris007/Lifein-theme?style=flat&color=%237c3aed)](https://github.com/ichris007/Lifein-theme/stargazers) [![License](https://img.shields.io/github/license/ichris007/Lifein-theme?color=%237c3aed)](https://github.com/ichris007/Lifein-theme/blob/main/LICENSE)

[Report a bug](https://github.com/ichris007/Lifein-theme/issues/new) · [Request a feature](https://github.com/ichris007/Lifein-theme/issues/new)

> Lifein 不是一套「换色」主题，而是一整套可调的界面系统——配色、布局、侧栏、排版、属性面板、插件外观，全部收进同一个设置面板。想极简就极简，想有质感就有质感。
>
> 它以「玻璃拟态（Glassmorphism）」为视觉语言，深度集成 Style Settings，为专注内容而生。少即是多：把界面安静地退到内容后面，让笔记本身成为主角。

---

## 1 ✨ 核心特性

### 1.1 🪟 统一的玻璃拟态视觉

菜单、命令面板、弹窗、提示框，以及 Style Settings 设置面板，全部采用统一的「毛玻璃」处理：  
半透明背景 + 背景模糊（blur）+ 轻微饱和提升 + 1px 发丝描边 + 圆角。  
只做一层玻璃，避免「卡中卡」的廉价感；模糊强度与透明度可通过 Style Settings 微调。

### 1.2 🎛 深度集成的 Style Settings

主题内置两大设置块、十余个分组，几乎每个细节都可调，且设置面板本身也经过重排版（横向布局 + Lucide 图标 + 主题绿按钮），好看又好用：

- **配色与主题**：主题色板、背景玻璃浓度 / 模糊 / 饱和度等。
- **界面布局与导航**：标题与状态栏、Banner、侧边栏、侧边栏悬停。
- **编辑与排版**：文本、行内元素（引用竖线 · 标签 · 链接）、列表、表格。
- **弹窗与交互**：命令面板、菜单、页面预览框。
- **核心视图与组件**：属性面板、Bases。
- **社区插件样式**：Dataview、Calendar、Dust Calendar、Tasks、Kanban等。

> 推荐安装社区插件 **Style Settings** 以解锁全部调节项；不装也能正常使用默认外观。

### 1.3 🎨 十套配色方案（一键换肤）

内置一套「派生引擎」：整套界面的背景、文字、侧栏、色块、代码高亮、语义色，全部由一枚「种子色」+ 一组「彩度上限」派生而来。换方案 = 换种子色相，整套主题跟着重新着色，无需手工调几十个变量。

- **10 套预设**：跟随强调色（= 默认行为）/ 素白 / 暖砂 / 森野 / 青碧 / 靛蓝 / 墨玉 / 玫红 / 石墨 / 纯黑 AMOLED。
- **亮暗独立**：亮色与暗色方案分开选（社区主流做法），同一种颜色在亮底和暗底观感差别大，分开才调得准；「纯黑 · AMOLED」会在暗色下把背景压到纯黑，省电又纯粹。
- **连强调色一起换**：除「跟随强调色」外，其余方案会接管全局主强调色——按钮、链接、选中态整体跟方案走；若你在「设置 → 外观 → 强调色」里显式选过颜色，那个选择优先、方案自动让位。

### 1.4 🧘 两种专注模式（互不干扰）

- **Full Focus Mode**：开启 Obsidian 原生「专注模式」即触发。自动隐藏主区标签页 / 每页标题栏 / 状态栏（悬停可显形），编辑区居中（720px + 顶部留白），并淡化非活动窗格，把干扰降到最低。
- **Light Focus Mode**：独立的轻量专注模式。隐藏标签页 / 标题栏 / 状态栏 / 属性标题 / 标题栏按钮 / 滚动条，**带平滑的淡入淡出过渡动画**，可在 Style Settings 中绑定快捷键一键开关。

### 1.5 📱 cupertino 风格漂浮侧栏

受 macOS 启发的半透明漂浮侧栏，可自定义侧栏背景色与开关，毛玻璃质感与主题整体一致。

### 1.6 🌗 深浅主题自动反转

完整支持浅色 / 深色，深色模式通过整组变量反转实现，无需单独维护两套配色。

### 1.7 🧩 社区插件适配

对常用社区插件做了样式收纳：Dataview、Calendar、Dust Calendar、Tasks、Kanban，开箱即用、不突兀。

### 1.8 🗂 Bases 视图适配

核心视图与组件分组中对 Obsidian Bases 做了专门样式支持。

---

## 2 📸 截图


![浅色模式](screenshots/full_light.png)
![深色模式](screenshots/full_dark.png)
![玻璃拟态](screenshots/glass_all.png)


---

## 3 📦 安装

### 3.1 方式一：Obsidian 社区主题

1. 打开 Obsidian → 设置 → 外观。
2. 点击「管理」→ 在主题列表中找到 **Lifein** → 启用。

### 3.2 方式二：手动安装

1. 下载本仓库的 `theme.css`。
2. 在你的 vault 中创建目录 `.obsidian/themes/Lifein/`。
3. 将 `theme.css` 放入该目录即可（最终路径：`你的 vault/.obsidian/themes/Lifein/theme.css`）。
4. 重启 Obsidian → 设置 → 外观 → 主题 → 选择 **Lifein**。

### 3.3 自定义（可选）

1. 在「社区插件」中安装 **Style Settings**。
2. 设置 → 第三方插件 → Style Settings（或命令面板「Style Settings」）中即可看到 Lifein 的全部调节项。

### 3.4 阅读源码（可选）

本仓库的 `theme.css` 是刻意压缩过的 —— 它以一整行 CSS 的形式发布（Style Settings 的 `@settings` 块按原样保留），为的是把体积压到主题审核线以内。**这不影响你可调的范围**：所有选项仍然完整出现在 Style Settings 面板里。

如果你想读代码，带完整注释的源文件就放在它旁边 —— **[`theme.source.css`](./theme.source.css)**，16,000 多行，几乎每个代码段上方都有分区标题和说明。安装用 `theme.css`，阅读与二次开发请打开 `theme.source.css`。

---

## 4 🔧 兼容性与注意事项

- 建议 Obsidian **v1.7 及以上**（Bases、新版 Style Settings 需要）。
- 主题本身不依赖任何插件即可使用；**Style Settings** 仅用于解锁可视化调节。

---

## 5 📄 许可证

本主题以 **MIT License** 发布。完整的许可条款见仓库根目录的 [LICENSE](LICENSE) 文件。

Copyright © 2026 Chris

---

## 6 🙏 致谢

- **[Underwater](https://github.com/seniblue/Underwater)** 主题：Light Focus Mode 的思路与实现参考自此。
- **[Baseline](https://github.com/svnaxis/obsidian-baseline)** 主题：精细的布局、悬浮侧边栏参考。
- **[Border](https://github.com/akifyss/obsidian-border)** 主题：标题样式参考。
- **[Minimal](https://github.com/kepano/obsidian-minimal)** 主题：Style Settings 多设置块结构、Dataview 样式与进度条参考。
- **[Obsidian](https://obsidian.md)** 官方默认主题与社区，为本主题提供了基础与灵感。

---

<p align="center">用 Lifein，让界面退后一步，让文字向前一步。</p>

---
<div align="center">

### ☕ 支持作者

如果这个项目给你带来了帮助，欢迎请我喝杯咖啡 ☕

微信扫码↓

<img src="https://github.com/ichris007/ichris007/blob/main/images/wechat_donate_qrcode0.png" width="300" alt="微信赞赏码">

感谢每一份支持！

</div>
