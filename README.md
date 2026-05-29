# 🎮 坦克大战 (Tank Battle)

一个使用纯 HTML5 Canvas 开发的经典坦克大战网页游戏。

## 🎯 玩法介绍

- 控制你的坦克，消灭所有敌方坦克即可过关
- 收集道具增强自身能力
- 随着关卡推进，敌人会越来越多、越来越强

## 🕹️ 操作方式

| 操作 | 按键 |
|------|------|
| 移动 | `W A S D` 或 `↑ ↓ ← →` |
| 瞄准 | 鼠标移动 |
| 射击 | 鼠标左键 或 `空格键` |

## ✨ 特性

- 🎨 Canvas 渲染，流畅的 60fps 游戏体验
- 🔊 Web Audio API 音效系统
- 💥 粒子爆炸效果
- 🧱 可破坏的砖墙和不可破坏的钢板墙
- 🎁 道具系统（生命恢复、加速、快速射击）
- 👾 多种敌人类型（普通坦克、Boss 坦克）
- 📈 随关卡递增的难度
- 🖥️ 支持桌面端和移动端触屏操作
- 🎯 屏幕震动反馈

## 🚀 如何运行

直接用浏览器打开 `index.html` 文件即可开始游戏。

或者在项目目录下启动一个本地服务器：

```bash
# 使用 Python
python -m http.server 8000

# 使用 Node.js
npx serve .
```

然后在浏览器中访问 `http://localhost:8000`

## 📂 项目结构

```
tank-battle/
├── index.html    # 游戏主文件（包含 HTML/CSS/JS）
└── README.md     # 项目说明
```

## 🛠️ 技术栈

- HTML5 Canvas
- CSS3 动画
- 原生 JavaScript (ES6+)
- Web Audio API

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
