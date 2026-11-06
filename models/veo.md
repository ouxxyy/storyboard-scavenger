# Google Veo（Veo 2 / Veo 3）分镜提示词规范

## 1. 核心参数与语法特征
- **电影摄影术语**：对焦段（18mm / 35mm / 85mm anamorphic）、光比（chiaroscuro / golden hour backlight）与机位运动（Steadicam tracking / crane up）响应极佳。
- **原生音画同步（Veo 3）**：支持在同一提示词末尾附加 `[Audio Design]` 段落，声明环境底噪、动作拟音（Foley）与对白音色，禁止混入模糊的音乐版权名。

## 2. 实战分镜示例（含音画同步）
```text
Cinematic product film, 16:9 widescreen, shot on 50mm anamorphic lens, shallow depth of field. Warm morning sunlight filtering through linen curtains onto an oak desk. Low-angle medium close-up of a ceramic pour-over dripper. Slow dolly-in as hot water spirals over dark roasted coffee grounds, rich amber crema blooming at the center while delicate steam rises into the sunbeams.
[Audio Design]: Crisp sound of hot water pouring steadily, subtle bubbling of coffee bloom, quiet morning room ambience with distant birdsong.
```
