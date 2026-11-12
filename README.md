# 🐍 Neon Snake / 霓虹贪吃蛇

一个零依赖的开源网页贪吃蛇小游戏，使用 **HTML、CSS、原生 JavaScript 和 Canvas** 开发，支持电脑与手机。

## 在线试玩

https://aistudyy001-cpu.github.io/snake-game-lite/

## 功能

- 方向键 / WASD / 手机滑动与触屏方向键
- 食物随机生成、碰撞判定与计分
- 随分数增加自动加速
- 浏览器本地保存最高分
- 暂停、继续、重新开始与音效开关
- 响应式布局，不需要安装依赖

## 本地运行

下载仓库，双击 `index.html`，即可在现代浏览器中运行。

## 项目结构

```text
index.html  页面结构
style.css   响应式样式
game.js     游戏逻辑、计分和 Canvas 绘制
LICENSE     MIT 开源许可证
README.md   使用说明
```

## 原理

采用 20×20 网格存储蛇的身体坐标。每次时钟触发计算新头部、判定食物与碰撞并重绘。没有进食时可以进入上一帧尾巴所在的格子；最高分用 localStorage 保存。

## 开源协议

MIT License，详见 [LICENSE](LICENSE)。
