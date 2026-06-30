# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repo Is

个人作品集网站，基于 GitHub Pages 部署。纯静态 HTML/CSS/JS，零依赖。

## 开发

- **本地预览:** 直接用浏览器打开 `index.html`，或用 `python3 -m http.server 8000` 启动服务器
- **部署:** 推送到 `main` 分支，GitHub Pages 自动生效
- **新增页面/内容:** 编辑 `index.html` 或 `assets/` 下的文件

## 项目结构

```
index.html            — 主页面（单页作品集）
assets/
  css/style.css       — 所有样式
  js/main.js          — 交互脚本（导航菜单、滚动效果）
_config.yml           — Jekyll 配置（GitHub Pages 构建用）
README.md             — 项目说明
CLAUDE.md             — 本文件
```

## Git 工作流

- 默认分支: `main`
- 直接推送 `main` 触发生产部署
- 试验性改动请新建分支
