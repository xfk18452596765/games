# 贪吃蛇小游戏

一个使用原生 HTML、CSS 和 JavaScript 编写的贪吃蛇小游戏，所有代码都在 `index.html` 中，无需安装依赖。

## 功能

- 方向键或 WASD 控制移动
- 空格键暂停或继续
- Enter 键重新开始
- 支持触屏方向按钮
- 自动记录本地最高分
- 响应式布局，支持桌面和移动端

## 运行方式

直接用浏览器打开 `index.html` 即可开始游戏。

也可以在项目目录启动一个本地静态服务：

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

然后访问：

```text
http://127.0.0.1:8000/index.html
```

## 操作说明

| 操作 | 按键 |
| --- | --- |
| 向上 | ↑ / W |
| 向下 | ↓ / S |
| 向左 | ← / A |
| 向右 | → / D |
| 暂停 / 继续 | 空格 |
| 重新开始 | Enter |

## 项目结构

```text
snake-game/
├── index.html
└── README.md
```
