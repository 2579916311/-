# Particle Morph

一个无需构建工具、无需第三方依赖的交互式粒子网站。灵感来自参考视频中的粒子变形效果。

## 本地运行

最简单的方式：直接双击 `index.html`。

也可以启动本地服务器：

```bash
python -m http.server 8080
```

然后打开 <http://localhost:8080>。

## 交互

- 点击 **CHANGE SHAPE**：在金字塔、球体、圆环、波浪之间变形
- 拖动舞台：旋转粒子模型
- 移动鼠标/触控：扰动附近粒子
- 点击色点：切换粒子颜色或彩虹模式

## 技术

- 单文件 HTML / CSS / JavaScript
- Canvas 2D 自研伪 3D 粒子渲染
- 桌面端与移动端响应式适配
- 支持 `prefers-reduced-motion`
