# 挥拍三项

羽毛球、网球、乒乓球 3D 球拍游戏。支持单打、双打和混双，以及表演赛、联赛、淘汰赛，适合 iPad 横屏游玩。

## 在线体验

GitHub Pages: `https://yefei404.github.io/racket-trio/`

## 功能特性

- **三个项目**：羽毛球 21 分制、网球、乒乓球
- **赛事**：表演赛、联赛积分榜、淘汰赛对阵图；进度保存在本浏览器
- **球员**：每个项目 16 名虚构球员，属性为力量、体力、速度、控制
- **双打**：你控制一人，搭档由电脑负责自己那半场；乒乓球双打轮流击球
- **键鼠 / 触屏**：WASD 移动、鼠标瞄准；触屏左半屏移动，右下「攻」「巧」挥拍
- **iPad**：Safari「添加到主屏幕」后标题为「挥拍三项」，建议横屏

## 项目结构

```
racket-trio/
├── index.html      # 页面（HTML + CSS + JS）
├── three.min.js    # Three.js（本地）
└── README.md
```

## 本地运行

```bash
open index.html
# 或使用静态服务器
npx serve .
```

## 部署

1. 在 GitHub 创建仓库 `yefei404/racket-trio`（Public）
2. push 到 `main` 分支
3. Settings → Pages → Source 选 `main` 分支、根目录 `/`

## License

MIT
