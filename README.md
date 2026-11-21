# Fold 操作手册 / Fold User Guide

[![访问官网](docs/assets/buttons/visit-website.svg)](https://foldmac.top)
[![立即下载](docs/assets/buttons/download.svg)](https://github.com/juguangyuan520-dotcom/fold-docs/releases)

Fold 是面向长期使用的 Mac 文件管理器，帮助你收拢分散文件、管理文件夹、使用全局暂存箱、快速搜索和整理微信文件，并内置 Fold AI 辅助摘要与文件处理。当前正式版仅支持 Apple Silicon（M 系列芯片）。

这个仓库维护 Fold 的官方操作手册。

## 语言 / Language

- [中文手册](docs/index.md)
- [English guide](docs/en/index.md)

## 阅读入口

- [手册首页](docs/index.md)
- [安装与首次使用](docs/getting-started/install.md)
- [界面与导航](docs/getting-started/interface.md)
- [文件操作](docs/files/file-operations.md)
- [文件托盘](docs/files/file-tray.md)
- [搜索](docs/files/search.md)
- [Fold AI](docs/ai/index.md)
- [设置](docs/settings/index.md)
- [更新与版本记录](docs/maintenance/update.md)
- [故障排查](docs/maintenance/troubleshooting.md)

## 内容规则

1. 手册按用户任务组织，不按代码模块组织。
2. 每篇必须写清入口、步骤、预期结果和失败处理。
3. 涉及界面变化的修改必须附当前正式版截图，截图放在 `docs/assets/screenshots/`。
4. 功能行为变化时，先改手册，再发布软件版本。
5. 文档只描述正式版行为；未发布功能放入对应页面的“待发布”小节，发布当天移入正文。

## 目录结构

```text
docs/
├── index.md                  # 手册首页和阅读路径
├── getting-started/          # 安装、首次使用、界面
├── files/                    # 浏览、选择、拖拽、托盘、搜索
├── ai/                       # Fold AI、摘要、文件编辑
├── settings/                 # 通用、外观、AI 能力、权限
├── maintenance/              # 更新、数据位置、故障排查
└── assets/screenshots/       # 版本截图
```

英文手册位于 `docs/en/`，目录与中文手册一一对应。修改中文页面时必须同步检查对应英文页；行为已经变化但英文翻译未确认时，先在 PR 标注 `needs-translation`。

## 反馈和处理

用户通过 GitHub Issue 提交文档问题，模板在 `.github/ISSUE_TEMPLATE/`。每周末处理一次：

1. 高频问题转成新文档或补充现有文档。
2. 界面入口变化直接修正步骤和截图。
3. 技术判断不确定时，先在 Issue 标注 `needs-verification`，确认后再改。

