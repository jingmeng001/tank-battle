# 🎮 坦克大战 (Tank Battle)

一个使用 HTML5 Canvas 和 JavaScript 实现的经典坦克大战游戏。

## 🚀 在线试玩

直接在浏览器中打开 `index.html` 即可开始游戏！

## 🎮 游戏操作

| 按键 | 功能 |
|------|------|
| `W` / `↑` | 向上移动 |
| `S` / `↓` | 向下移动 |
| `A` / `←` | 向左移动 |
| `D` / `→` | 向右移动 |
| `空格键` | 射击 |
| `P` | 暂停/继续 |

## ✨ 游戏特色

- 🟢 **玩家坦克**：绿色坦克，由你控制
- 🔴 **敌方坦克**：红色坦克，自动AI控制
- 🧱 **砖墙**：可被子弹摧毁
- ⬜ **钢墙**：坚不可摧
- ⭐ **基地**：金色星星，保护它！
- 💥 **爆炸特效**：击中坦克时的炫酷效果

## 📝 游戏规则

1. 使用方向键或WASD移动坦克
2. 按空格键发射子弹
3. 击毁敌方坦克获得100分
4. 避免被敌方坦克击中
5. 你有3条生命，生命耗尽游戏结束

## 🛠️ 技术栈

- HTML5 Canvas
- 原生 JavaScript (ES6+)
- CSS3

## 📂 项目结构

```
tank-battle/
├── index.html    # 主游戏文件
└── README.md     # 项目说明
```

## 🔧 本地运行

```bash
# 克隆仓库
git clone <repository-url>

# 进入目录
cd tank-battle

# 用浏览器打开
open index.html
```

或者使用本地服务器：

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .
```

然后访问 `http://localhost:8000`

## 📄 开源协议

MIT License
