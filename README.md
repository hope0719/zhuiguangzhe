# 追光者 ☀️

> 追逐阳光，温暖前行

一个帮你寻找阳光目的地的天气应用。实时查询全球 100+ 城市的天气与 UV 指数，规划阳光明媚的旅行路线，在地图上直观查看全国各省晴好度。

## ✨ 功能

- **阳光城市** — 实时天气、UV 指数、7 日预报、日照时长，按晴好度排序
- **路线规划** — 选择出发地和目的地，自动推荐沿途阳光城市，支持飞机/高铁/自驾
- **阳光地图** — 中国地图各省份晴好度可视化，雨天区域淡蓝标注，可绘制追光路线
- **收藏与分享** — 收藏阳光目的地，一键生成精美海报分享

## 🛠 技术栈

- 纯前端 HTML / CSS / JavaScript（无构建依赖）
- [ECharts](https://echarts.apache.org/) 地图可视化
- [Open-Meteo](https://open-meteo.com/) 天气数据（CMA 中国气象局模型）
- 字体：Lora

## 📁 项目结构

\`\`\`
├── index.html          # 应用入口
├── _shared/
│   ├── fonts/           # Lora 字体
│   └── js/echarts.min.js
└── assets/
    └── splash-bg.jpg    # 开屏背景
\`\`\`

## 🚀 部署

纯静态站点，可直接部署到 Cloudflare Pages、GitHub Pages、Vercel 等。

### Cloudflare Pages

1. Fork 或推送本仓库到 GitHub
2. Cloudflare Pages → Connect to Git → 选择仓库
3. Build command：留空
4. Build output directory：`/`
5. Deploy

## 📜 许可

MIT
