# OpenAI Sora 分镜提示词规范

## 1. 核心参数与语法特征
- **Storyboard 时间轴卡片**：Sora 的强项在于同一镜头内跨时间段（0.0s → 3.0s → 6.0s）的物理状态连续演化与遮挡后主体保持。
- **空间锚点先行**：先定义静态三维空间与材质反射属性，再按时间轴描述流体、织物与光源交互。

## 2. 实战分镜示例（时间轴分段式）
```text
[0.0s - 2.5s]: Wide establishing shot, 24mm lens, Nordic minimalist studio bathed in overcast daylight. A miniature paper boat sits at the edge of a long glass water channel on a birch table.
[2.5s - 5.5s]: Camera tracks parallel at water level as a gentle current carries the paper boat forward; ripples refract caustics onto the wooden tabletop below.
[5.5s - 8.0s]: Rack focus from the paper boat in the foreground to a warm desk lamp switching on in the background, casting a golden reflection across the water surface.
```
