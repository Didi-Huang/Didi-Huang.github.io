# Didi-Huang.github.io

黄宏迪的个人主页 · Physics @ Tokyo University of Science

👉 https://didi-huang.github.io

---

## 简介

个人主页 + 简介页。深色主题、3D 波函数背景、三语切换（中 / EN / 日）。

- **首页** — 个人信息、项目展示、联系方式
- **关于页** — 研究兴趣、Side Projects、日常

## 功能

| 特性 | 说明 |
|------|------|
| 三语切换 | 中文 / English / 日本語，localStorage 记忆偏好 |
| 入场动画 | anime.js timeline — 头像旋转缩放、打字机逐字、元素 stagger |
| 动态背景 | Canvas 3D 波函数曲面旋转 + 粒子场 |
| 滚动触发 | 区块进入视口时渐入动画 |
| 响应式 | 适配手机 / 平板 / 桌面 |
| 无障碍 | prefers-reduced-motion 降级 |

## 技术栈

- 纯 HTML / CSS / JavaScript — 无框架
- [anime.js](https://animejs.com) — 入场动画
- Canvas 2D — 3D 透视投影 + 波函数渲染 + 粒子系统
- IntersectionObserver — 滚动触发与导航高亮
- GitHub Pages — 部署

## 项目结构

```
├── index.html      # 首页
├── about.html      # 关于页
├── README.md
└── figures/        # 图片资源（可放头像等）
```

## 本地运行

```bash
# 克隆仓库
git clone https://github.com/Didi-Huang/Didi-Huang.github.io.git
cd Didi-Huang.github.io

# 启动 HTTP 服务器
python3 -m http.server 8765
# 浏览器打开 http://localhost:8765
```

## 部署

推送至 `main` 分支后，GitHub Pages 自动部署于：
https://didi-huang.github.io

---

_Last updated: 2026-05-26_
