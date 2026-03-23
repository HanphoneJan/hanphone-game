# 🎮 Hanphone Game Collection

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 简介 | Introduction

**中文:** 一个包含 12 个 HTML5 小游戏的 GitHub 开源项目，无需安装即可在浏览器中畅玩。所有游戏均采用原生 HTML5、CSS3 和 JavaScript 开发，支持 PC 和移动端。

**English:** A GitHub open-source project containing 12 HTML5 mini-games that can be played directly in the browser without installation. All games are built with native HTML5, CSS3, and JavaScript, supporting both PC and mobile devices.

## 游戏列表 | Games

<!-- GAMES-LIST:START -->
| 图标 | 游戏 | 描述 | 链接 |
|:---:|:---|:---|:---:|:---:|
| 🔢 | **2048** | 经典数字拼图游戏 | [开始游戏](https://hanphonejan.github.io/hanphone-game/2048/) |
| ⬛ | **Black Blocks** | 黑块挑战 | [开始游戏](https://hanphonejan.github.io/hanphone-game/blackblocks/) |
| 🧱 | **Breakout Bricks** | 打砖块 | [开始游戏](https://hanphonejan.github.io/hanphone-game/breakout-bricks/) |
| 🐔 | **Crossy Road** | 过马路大冒险 | [开始游戏](https://hanphonejan.github.io/hanphone-game/crossy-road/) |
| ⚫ | **Gomoku** | 五子棋对战 | [开始游戏](https://hanphonejan.github.io/hanphone-game/gomoku/) |
| 💣 | **Minesweeper** | 经典扫雷 | [开始游戏](https://hanphonejan.github.io/hanphone-game/minesweeper/) |
| 🏓 | **Ping Pong** | 乒乓球对战 | [开始游戏](https://hanphonejan.github.io/hanphone-game/ping-pong/) |
| 🐍 | **Snake** | 经典贪吃蛇 | [开始游戏](https://hanphonejan.github.io/hanphone-game/snake/) |
| 🔢 | **Sudoku** | 数独谜题 | [开始游戏](https://hanphonejan.github.io/hanphone-game/shudu/) |
| 🎮 | **Tetris** | 俄罗斯方块 | [开始游戏](https://hanphonejan.github.io/hanphone-game/tetris/) |
| 🏗️ | **Tower Blocks** | 堆塔挑战 | [开始游戏](https://hanphonejan.github.io/hanphone-game/tower-blocks/) |
| 🧸 | **Toy Claw** | 抓娃娃机 | [开始游戏](https://hanphonejan.github.io/hanphone-game/toy-claw/) |
<!-- GAMES-LIST:END -->

## 快速开始 | Quick Start

### 在线游玩
直接访问 GitHub Pages 或打开任意游戏目录下的 `index.html` 文件即可游玩。

### 本地运行
```bash
# 克隆仓库
git clone https://github.com/hanphonejan/hanphone-game.git

# 进入项目目录
cd hanphone-game

# 使用任意本地服务器运行，例如 Python 的 http.server
python -m http.server 8000

# 或使用 Node.js 的 http-server
npx http-server

# 然后在浏览器中打开
# http://localhost:8000
```

## 项目结构 | Project Structure

```
hanphone-game/
├── 2048/               # 2048 数字拼图游戏
├── blackblocks/        # 黑块挑战
├── breakout-bricks/    # 打砖块
├── crossy-road/        # 过马路大冒险
├── gomoku/             # 五子棋
├── minesweeper/        # 扫雷
├── ping-pong/          # 乒乓球
├── shudu/              # 数独
├── snake/              # 贪吃蛇
├── tetris/             # 俄罗斯方块
├── tower-blocks/       # 堆塔挑战
├── toy-claw/           # 抓娃娃机
├── index.html          # 游戏导航主页
└── README.md           # 项目说明文档
```

## 技术栈 | Tech Stack

- **HTML5** - 页面结构与 Canvas 绘图
- **CSS3** - 样式设计与动画效果
- **JavaScript** - 游戏逻辑与交互

## 贡献指南 | Contributing

欢迎提交 Pull Request 来改进游戏或添加新功能！

1. Fork 本仓库
2. 创建你的功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'feat: add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 打开一个 Pull Request

## License

[MIT](LICENSE) © Hanphone
