# Cornerstone China 欧信英才 — Website Redesign DEMO

> **⚠️ This is a design DEMO / prototype, not the production website.**
> **⚠️ 本仓库为设计 DEMO 原型，非正式生产网站。**

**Live Preview 在线预览：** https://private200516.github.io/cornerstone-demo/

---

## About | 关于

An interactive front-end redesign concept for the Cornerstone China corporate websites —
[cornerstone-china.com](https://cornerstone-china.com/) (EN) and
[欧信英才.com](https://欧信英才.com/) (中文) — exploring a bilingual (中文 / English)
single-site experience with full-page scroll storytelling, in the visual language of a
top-tier consulting firm.

Cornerstone 中国官网（英文站 cornerstone-china.com 与中文站 欧信英才.com）的
前端改版概念原型：中英双语单站架构、整页滚动叙事，呈现顶级咨询公司的视觉语言。
文案与事实信息（1989 集团创立 / 1996 进入中国、五大业务线、所获奖项、
全球 40 国 60 办公室 250+ 顾问）均与现有两个官网对齐。

## Key Features | 设计要点

- **Bilingual single site** — one codebase, language switcher in the top navigation
  （单一站点承载中英双语，顶部导航一键切换）
- **Full-page scroll experience** — one screen per section, snap scrolling
  （整屏翻页式浏览，每次滚动呈现完整一页）
- **Brand film integration** — auto-plays when scrolled into view, pauses when leaving
  （品牌视频进入视口自动播放，离开自动暂停）
- **Brand color system** — built on the Cornerstone logo's red, blue, and white
  （配色源自 LOGO 的红、蓝、白）
- **Bilingual SEO-ready** — Open Graph, hreflang alternates (zh-CN / en) and canonical
  tags included, ready to carry over the existing sites' SEO equity
  （已内置双语 SEO 要素：Open Graph、中英 hreflang 互链、canonical 标签，
  可承接现有网站的 SEO 资产）
- **Responsive & performance-conscious** — designed to translate into a WordPress
  implementation without affecting existing functionality or SEO
  （可落地为 WordPress 实施，不影响现有功能与 SEO）

## Tech Stack | 技术栈

- React + TypeScript + Vite
- Tailwind CSS
- GSAP + Lenis (scroll animation)
- Deployed via GitHub Pages

## Project Structure | 目录结构

```
├── index.html          # Entry page (bilingual SEO meta) | 入口页面（双语 SEO 元信息）
├── assets/             # Compiled CSS / JS | 编译产物
└── images/             # Brand assets & media | 品牌素材与媒体文件
```

## Context | 背景

This DEMO serves as a visual reference for the planned upgrade of the Cornerstone China
websites, to be reviewed and implemented together with the web development partner.

本 DEMO 作为 Cornerstone 中国官网升级改版的视觉参考，将与网站技术合作方共同评审并实施。

---

*Cornerstone International Group · 欧信英才（中国）— Group since 1989, in China since 1996*
