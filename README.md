# 白日梦引擎 · Daydream Engine

> A mind in three acts. A realistic idealist who finished the math.

这是一个把个人思考做成可交互叙事的单页网站。它用“三幕剧”讲清楚一个现实派理想主义者如何拆解约束、成本和概率，再把白日梦推进到可以落地的下一步。

## 项目概览

- 作者：唐代喆 / TANG DAIZHE
- 形态：纯前端、单文件、零依赖
- 入口：`index.html`
- 视觉：暖色深空、扫描线、Canvas 场景和细微交互
- 适合：个人主页、思想介绍、实验性叙事网页

## 实际演示

1. 打开页面，等待启动画面完成。
2. 沿着三幕内容向下阅读，查看“梦想—约束—落地”的叙事结构。
3. 移动鼠标或触摸页面，观察光标、扫描线和 Canvas 场景变化。
4. 在移动端直接滑动体验；页面不依赖账号、后端或构建工具。

当前还没有公开部署地址；仓库中的 [index.html](index.html) 就是完整成品。

## 本地运行

直接双击 `index.html` 即可。也可以在仓库目录启动静态服务器：

```bash
python -m http.server 5500
```

然后打开 `http://localhost:5500`。

## 设计与技术

- 单文件 HTML，便于分享和部署。
- Canvas 用于背景场景和氛围动画。
- CSS 负责深色暖色主题、排版、扫描线和响应式布局。
- 无数据库、无登录、无 API、无构建步骤。

## 当前状态

项目已经可以作为个人实验网站使用。下一步可以补充公开预览地址、移动端截图、三幕导航目录和无障碍键盘说明。

## 项目链接

- 仓库：[daizhetang-create/daydream-engine](https://github.com/daizhetang-create/daydream-engine)
- 入口：[index.html](index.html)
- 方向：个人叙事、思想表达、交互式主页