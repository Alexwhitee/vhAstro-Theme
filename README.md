# 🍥 Astro主题 vhAstro-Theme

## 🚀 vhAstro-Theme：一款基于 Astro 构建的优雅的响应式博客主题

**「当极简主义遇上工程之美」**

在线演示 ➡️ [https://www.vvhan.com](https://www.vvhan.com)
官方文档 ➡️ [vhAstro-Theme](https://www.vvhan.com/article/astro-theme-vhastro-theme)

![Astro主题 vhAstro-Theme](https://i0.wp.com/uxiaohan.github.io/v2/2025/03/1740899552.webp)

## ✨ 功能特性

- [x] 简洁的响应式设计
- [x] 流畅的动画和页面过渡
- [x] 两列布局
- [x] 阅读时间
- [x] 字数统计
- [x] 代码块
- [x] 语法高亮
- [x] 图片懒加载
- [x] 图片灯箱
- [x] Twikoo 评论
- [x] 本地搜索
- [x] 标签
- [x] 分类
- [x] 归档
- [x] 动态
- [x] 关于
- [x] 友情链接
- [x] 推荐文章
- [x] 谷歌广告
- [x] 内置 404 页面
- [x] Sitemap 支持
- [x] RSS 支持
- [x] 活跃的社区支持
- [x] 广泛的现代框架兼容性
- [x] 高效的性能优化
- [x] 优秀的开发体验

## 🚀 使用方法

- 使用此模板生成新仓库或 Fork 此仓库
- 进行本地开发，Clone 新的仓库，执行 `pnpm install` 以安装依赖
- 若未安装 pnpm，执行 `npm install -g pnpm`
- 通过配置文件 `src/config.ts` 自定义博客
- 执行 pnpm newpost '文章标题' 创建新文章，并在 src/content/posts/ 目录中编辑
- 参考官方指南将博客部署至 Vercel, Netlify,Cloudflare Pages, GitHub Pages 等
- 部署前需编辑 `astro.config.mjs` 中的站点设置。

## ⚙️ 文章格式

```md
---
title: 标题
categories: 分类
tags:
  - 标签1
  - 标签2
id: 文章ID
date: 文章创建日期
updated: 文章更新日期
cover: "封面图URL (为空默认随机内置封面 /public/assets/images/banner)"
recommend: false # 是否推荐文章
hide: false # 是否隐藏文章
---
```

## 💻 命令

```bash
# 安装依赖
pnpm install
# 本地开发
pnpm dev
# 构建静态文件
pnpm build
# 创建新文章
pnpm newpost '文章标题'
```