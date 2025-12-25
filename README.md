# 墨影文枢: AI 创意写作助手

<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

## 项目简介

**墨影文枢** 是一款基于 Gemini API 的 AI 创意写作辅助工具，旨在帮助创作者激发灵感、优化内容并提升写作效率。

## 功能特性

- **智能续写**：利用 AI 帮助你克服写作瓶颈。
- **创意润色**：提供多种风格的文案优化建议。
- **实时反馈**：快速生成内容，即时预览。

## 快速开始

### 前置要求

- Node.js (推荐 v18 或更高版本)
- 一个有效的 Google Gemini API Key

### 安装与运行

1.  **克隆项目或下载代码**

2.  **安装依赖**
    ```bash
    npm install
    ```

3.  **配置环境变量**
    在项目根目录创建 `.env.local` 文件，并填入你的 API Key：
    ```env
    VITE_GEMINI_API_KEY=your_api_key_here
    GEMINI_API_KEY=your_api_key_here
    ```

4.  **启动开发服务器**
    ```bash
    npm run dev
    ```
    打开浏览器访问显示的地（通常是 `http://localhost:3000`）。

## 部署指南

本项目配置了 GitHub Actions 自动部署。

1.  确保你的 GitHub 仓库 Settings -> Pages 中，Build and deployment source 选择 **GitHub Actions**。
2.  推送到 `main` 分支时，将自动触发构建并部署到 GitHub Pages。

## 目录结构

```
.
├── src/                # 源代码
│   ├── components/     #通过组件
│   ├── services/       # API 服务
│   ├── utils/          # 工具函数
│   ├── App.tsx         # 主应用组件
│   └── main.tsx        # 入口文件
├── public/             # 静态资源
├── .github/workflows/  # CI/CD 配置
├── package.json        # 项目配置
└── vite.config.ts      # Vite 配置
```
