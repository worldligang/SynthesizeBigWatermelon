# 合成大西瓜

一个经典的合成大西瓜网页游戏，使用原生 HTML、CSS 和 JavaScript 开发。

## 游戏简介

合成大西瓜是一款有趣的物理合成游戏。玩家需要通过点击或触摸屏幕释放水果，相同的水果碰撞后会合成更大的水果，最终目标是合成最大的西瓜。

## 游戏玩法

1. **移动位置**：在画布上移动鼠标或手指，控制水果的掉落位置
2. **释放水果**：点击或松开手指，水果会掉落到下方
3. **合成规则**：两个相同的水果碰撞后会合成一个更大的水果
4. **游戏结束**：当水果堆积超过危险线（红色虚线）时，游戏结束

## 水果等级

游戏共有 10 种水果，按从小到大的顺序排列：

| 等级 | 名称 | 颜色 | 分数 |
|------|------|------|------|
| 1 | 樱桃 | 红色 | 1 |
| 2 | 草莓 | 橙红色 | 3 |
| 3 | 葡萄 | 金色 | 6 |
| 4 | 橙子 | 橙色 | 10 |
| 5 | 柿子 | 番茄红 | 15 |
| 6 | 桃子 | 紫色 | 21 |
| 7 | 菠萝 | 蓝色 | 28 |
| 8 | 椰子 | 绿色 | 36 |
| 9 | 哈密瓜 | 棕色 | 45 |
| 10 | 西瓜 | 深绿色 | 55 |

## 功能特性

- 🎮 **响应式设计**：支持桌面端和移动端，自动适配屏幕大小
- 💾 **本地存储**：自动保存最高分记录
- 🎨 **精美界面**：渐变背景和精美的水果设计
- 📱 **触摸支持**：支持触摸屏操作
- ⚡ **流畅动画**：基于物理引擎的流畅动画效果

## 如何运行

1. 克隆项目到本地：
```bash
git clone git@github.com:worldligang/SynthesizeBigWatermelon.git
```

2. 进入项目目录：
```bash
cd SynthesizeBigWatermelon
```

3. 直接用浏览器打开 `index.html` 文件即可开始游戏

或者使用本地服务器（推荐）：
```bash
# 使用 Python 3
python3 -m http.server 8000

# 使用 Node.js 的 http-server
npx http-server
```

然后在浏览器中访问 `http://localhost:8000`

## 技术栈

- **HTML5 Canvas**：用于游戏画布渲染
- **CSS3**：用于页面样式和布局
- **JavaScript (ES6+)**：实现游戏逻辑和物理引擎

## 游戏配置

游戏的主要配置参数可以在 `game.js` 文件中调整：

- `GRAVITY`：重力加速度
- `BOUNCE`：弹性系数
- `FRICTION`：摩擦系数
- `FRUIT_TYPES`：水果的配置（半径、颜色、名称、分数）

## 项目结构

```
SynthesizeBigWatermelon/
├── index.html          # 主页面
├── style.css           # 样式文件
├── game.js             # 游戏逻辑
├── game-load.jpg       # 游戏加载截图
├── game-with-fruits.jpg    # 游戏进行中截图
├── game-after-click.jpg    # 点击后截图
├── game-final-state.jpg    # 游戏结束截图
└── README.md           # 说明文档
```

## 许可证

MIT License

## 贡献

欢迎提交 Issue 和 Pull Request！

## 联系方式

- GitHub: [worldligang](https://github.com/worldligang)
- 项目地址: [SynthesizeBigWatermelon](https://github.com/worldligang/SynthesizeBigWatermelon)