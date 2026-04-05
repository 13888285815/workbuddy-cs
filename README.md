# Three.js FPS Demo

🎮 基于 Three.js 的第一人称射击游戏演示，**完全独立运行，无需网络**。

## 演示地址

**GitHub Pages**: https://13888285815.github.io/workbuddy-cs/

## 功能特性

- **完全离线** - Three.js 已打包进 HTML，无需 CDN
- **八叉树碰撞检测** - 高效物理碰撞
- **第一人称视角** - WASD移动 + 鼠标视角
- **跳跃系统** - Space键跳跃
- **物理投掷** - 点击投掷彩色小球
- **实时阴影** - PCF软阴影
- **FPS计数器** - 实时显示帧率

## 操作说明

| 按键 | 功能 |
|------|------|
| W/A/S/D | 移动 |
| 鼠标 | 视角 |
| Space | 跳跃 |
| 鼠标左键 | 投掷小球 |

> 首次需要**点击页面**锁定鼠标才能移动视角！

## 本地运行

直接用浏览器打开 `index.html` 即可，无需任何服务器！

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

## 技术说明

- Three.js r160 + Octree + Capsule（已打包）
- 单文件 677KB，完全自包含
- 无任何外部依赖

## 技术说明

- Three.js r160 + Octree + Capsule（已打包进单文件）
- 单文件 ~677KB，完全自包含
- 无任何外部依赖或外部链接
