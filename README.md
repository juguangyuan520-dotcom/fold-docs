# Fold 操作手册

这个仓库只维护 Fold 的官方操作手册。当前阶段不接官网、Cloudflare 或其他发布渠道，GitHub 上的 Markdown 就是唯一内容源。

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

## 反馈和处理

用户通过 GitHub Issue 提交文档问题，模板在 `.github/ISSUE_TEMPLATE/`。每周末处理一次：

1. 高频问题转成新文档或补充现有文档。
2. 界面入口变化直接修正步骤和截图。
3. 技术判断不确定时，先在 Issue 标注 `needs-verification`，确认后再改。

