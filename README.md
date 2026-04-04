# Three.js FPS Demo

🎮 基于 Three.js 的第一人称射击游戏演示，包含八叉树碰撞检测。

## 在线演示

**演示地址**: https://13888285815.github.io/workbuddy-cs/

## 功能特性

- **八叉树碰撞检测** - 高效的碰撞系统
- **第一人称视角** - WASD移动 + 鼠标视角
- **跳跃系统** - Space键跳跃
- **物理投掷** - 点击投掷彩色小球
- **实时阴影** - PCF软阴影
- **FPS计数器** - 实时显示帧率
- **调试模式** - 可视化碰撞体（右上角GUI）

## 操作说明

| 按键 | 功能 |
|------|------|
| W/A/S/D | 移动 |
| 鼠标 | 视角 |
| Space | 跳跃 |
| 鼠标左键 | 投掷小球 |

## 技术栈

- Three.js r160
- GLTFLoader
- Octree 碰撞检测
- lil-gui 控制面板

## 本地运行

```bash
# 使用任意静态服务器
npx serve .
# 或
python -m http.server 8080
```

然后访问 http://localhost:8080

## 源码来源

基于 [three.js](https://github.com/mrdoob/three.js) 官方示例修改

## License

MIT License
