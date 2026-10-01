# 挥拍三项

球拍、田径、格斗和球队运动的 3D 游戏。适合 iPad 横屏游玩。

## 在线体验

GitHub Pages: `https://yefei404.github.io/racket-trio/`

## 功能特性

- **球拍项目**：羽毛球、网球、乒乓球；单打、双打、混双
- **田径**：400 米、1500 米、跳远、跳高；决赛、大奖赛、预赛加决赛
- **格斗**：拳击、柔道、空手道、摔跤；按体重级别分组
- **球队**：足球、沙滩足球、篮球、三人篮球、排球、沙滩排球
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
