# 🎥 38种AI视频运镜技巧手册

> 来源：微信公众号「船长AI视界」38种专业运镜技巧
> 整理日期：2026-06-05
> 用途：为 `seedance-storyboard` skill 提供运镜参考库

---

## 一、运镜速查总表

| # | 名称 | 英文关键词 | 类别 | 核心效果 | 适用场景 |
|---|------|-----------|------|---------|---------|
| 1 | 慢速推进 | Slow Dolly-in / Push-in | 轨道 | 建立亲近感/焦点 | 情绪开场、顿悟瞬间 |
| 2 | 慢速后拉 | Slow Dolly-out / Pull-out | 轨道 | 突显孤独感/环境 | 结尾、真相揭露 |
| 3 | 快速推进 | Fast Dolly-in / Rush | 轨道 | 紧张感/情绪高潮 | 危机爆发、情绪顶点 |
| 4 | 眩晕效应 | Dolly Zoom / Zolly | 变焦 | 心理不安/空间扭曲 | 震惊、密闭空间恐惧 |
| 5 | 微距变焦 | Macro Zoom | 变焦 | 穿透感/探索感 | 眼睛特写、科幻、心理戏 |
| 6 | 超远距变焦 | Cosmic Hyper-Zoom | 变焦 | 空间压缩/尺度震撼 | 开场镜头、宏大转场 |
| 7 | 过肩镜头 | Over-the-Shoulder | 特殊 | 视角代入/亲近感 | 对话、对峙、审问 |
| 8 | 鱼眼镜头 | Fisheye / Peephole | 特殊 | 畸变不安/窥视感 | 监视、悬疑、密闭空间 |
| 9 | 遮挡后显露 | Lateral Wipe Reveal | 特殊 | 悬念揭露/层层递进 | 人物登场、发现新事物 |
| 10 | 穿拍镜头 | Fly-through | 特殊 | 空间穿越/无缝转场 | 室内外连接、环境建立 |
| 11 | 模糊变清晰 | Focus Pull / Rack-to-Sharp | 焦点 | 视线引导/氛围聚焦 | 情绪建立、抽象→具体 |
| 12 | 焦点切换 | Rack Focus | 焦点 | 注意力转移/空间对比 | 对话、双人物互动 |
| 13 | 向上仰拍 | Tilt-up | 摇镜 | 建立权威感/存在感 | 人物登场、气势展现 |
| 14 | 向下俯拍 | Tilt-down | 摇镜 | 渐进展示/细节聚焦 | 时尚穿搭、物品展示 |
| 15 | 平视左移 | Truck Left | 轨道 | 视差纵深/探索感 | 环境建立、紧张升级 |
| 16 | 平视右移 | Truck Right | 轨道 | 空间纵深感/节奏感 | 视觉节奏、环境展示 |
| 17 | 半环绕运镜 | Half-Orbit (180°) | 环绕 | 视角切换/纵深感 | 人物展示、沉浸感营造 |
| 18 | 快速全环绕 | Fast Orbit (360°) | 环绕 | 紧张感/掌控力 | 战斗场景、高能量时刻 |
| 19 | 弧形缓推 | Slow Arc | 环绕 | 情感深度/亲近感 | 沉思、情感戏 |
| 20 | 垂直下移 | Pedestal Down | 升降 | 削弱主导/内省释然 | 情绪下沉、反思时刻 |
| 21 | 垂直上移 | Pedestal Up | 升降 | 提升存在/象征觉醒 | 成长、顿悟、升华 |
| 22 | 摇臂上抬 | Crane Up | 摇臂 | 揭露宏大/情感升华 | 大结局、高潮揭露 |
| 23 | 摇臂下降 | Crane Down | 摇臂 | 聚焦个人/情绪代入 | 情感收尾、人物落地 |
| 24 | 光学变焦(内) | Optical Zoom-in | 变焦 | 心理聚焦/疏离感 | 内心戏、凝视 |
| 25 | 光学变焦(外) | Optical Zoom-out | 变焦 | 环境揭露/剧情背景 | 环境展示、真相揭示 |
| 26 | 急速变焦 | Snap Zoom | 变焦 | 冲击力/震惊 | 顿悟、震惊时刻 |
| 27 | 无人机高空俯掠 | Drone Flyover | 无人机 | 尺度感/动态感 | 风景建立、宏大场面 |
| 28 | 无人机史诗揭露 | Epic Drone Reveal | 无人机 | 积累期待/戏剧发现 | 史诗开场、真相揭露 |
| 29 | 无人机大范围环绕 | Wide Drone Orbit | 无人机 | 主体掌控/尺度传递 | 地标展示、环境介绍 |
| 30 | 上帝视角 | Top-Down / God View | 无人机 | 抽象几何/宿命感 | 象征意义、神话时刻 |
| 31 | 穿越机俯冲 | FPV Dive | 无人机 | 速度感/紧迫感 | 追逐戏、揭秘 |
| 32 | 手持纪录片风格 | Handheld | 手持 | 纪实真实感 | 采访、真实感场景 |
| 33 | 快速甩镜 | Whip Pan | 摇镜 | 动感/惊喜感 | 场景转场、动作衔接 |
| 34 | 倾斜角度 | Dutch Angle / Roll | 倾斜 | 心理失衡/混乱感 | 密闭空间、情绪爆发 |
| 35 | 引导式跟拍 | Backward Tracking | 跟拍 | 临场感/自信气场 | 人物前进、自信登场 |
| 36 | 跟随式跟拍 | Forward Tracking (Behind) | 跟拍 | 未知感/神秘感 | 追逐、探索、离开 |
| 37 | 平行侧跟 | Side Tracking / Truck | 轨道 | 肢体语言/环境流动 | 行走、奔跑、动感 |
| 38 | 第一人称视角 | FPV Walking / POV | 特殊 | 极强代入感/沉浸感 | 探索、登场、旅程体验 |

---

## 二、运镜详解（完整提示词模板）

---

### 类别A：轨道运动 (Dolly / Track)

#### №1 慢速推进（缓慢轨道前推）

**英文关键词**：Slow dolly-in / Push-in

**提示词模板**：
```
A slow dolly-in toward a [角色/主体] [所处环境], [环境光线描述], 
the room gradually expanding in depth as the camera moves closer, 
emphasizing their quiet emotional shift.
```

**案例说明**：在不分散注意力的前提下，逐步建立画面的亲近感和焦点。通过将观众的视线"拉"向主体，这种运镜能有效强化紧张感，或是突出某个顿悟瞬间，同时保持画面的真实感。

**推荐参数**：50mm中焦 → 85mm、F2.0-F2.8、轨道平滑推进、每秒5-10cm

---

#### №2 慢速后拉（缓慢轨道后移）

**英文关键词**：Slow dolly-out / Pull-out

**提示词模板**：
```
A lone [角色] stands motionless on [场景] as the camera performs a slow dolly out, 
gradually revealing the vast, desolate landscape under [环境描述].
```

**案例说明**：会慢慢展现更多的环境细节，让画面焦点从人物本身转移到所处的空间。这种运镜能突出孤独感、空间尺度感或事件的后果，尤其适合用在情感饱满的结尾、顿悟时刻或转场镜头——也就是那些环境氛围盖过主体的场景。

**推荐参数**：24-35mm广角、F8-F11、轨道后拉、速度均匀

---

#### №3 快速推进（急速前推）

**英文关键词**：Fast dolly-in / Rush

**提示词模板**：
```
FAST DOLLY IN / RUSH on a [角色] as [环境音/氛围], [场景描述], 
[光影/色彩氛围].
```

**案例说明**：镜头以较快的速度向前猛推，强势拉近与主体的距离，能极大地增强画面的紧张感和情绪张力。它的作用是将观众直接"拽"入主体的内心世界，最适合用在顿悟、危机爆发或情绪高潮的时刻，尤其在空间狭小、需要聚焦人物反应的场景中效果显著。

**推荐参数**：35-50mm、F2.8、轨道加速推进、0.5-1秒完成

---

#### №10 穿拍镜头（穿越式运镜）

**英文关键词**：Fly-through

**提示词模板**：
```
Cinematic fly-through as the camera passes through [障碍物] into [新场景], 
revealing [主体] [动作/状态], [光影/色调].
```

**案例说明**：镜头穿越窗户、门缝、树叶等前景障碍物进入新空间，实现无缝的空间穿越感。可以打破空间的物理限制，让观众的视点平滑地从外部空间过渡到内部空间。最适合作开场镜头建立环境、室内向室外过渡、梦境与现实切换等场景。

**推荐参数**：16-24mm超广角、F8-F11、匀速穿越

---

#### №35 引导式跟拍（向后轨道跟拍）

**英文关键词**：Backward Tracking / Leading

**提示词模板**：
```
A determined [角色] strides forward through a long [场景] as the camera glides backward, 
holding constant distance and framing.
```

**案例说明**：平视向后移动，与主体相向而行，营造临场感/自信气场，保焦点同时增强推进节奏。

**推荐参数**：35-50mm、F2.8、后滑步、保持1:1距离

---

#### №36 跟随式跟拍（向前轨道跟拍）

**英文关键词**：Forward Tracking (Behind)

**提示词模板**：
```
A lone [角色] walks away down a moody [路径] as the camera follows closely from behind.
```

**案例说明**：从主体后方向前跟随，化身追逐者视角，突出未知感/神秘感，保持方向与情绪距离。

**推荐参数**：50-85mm、F2.8、跟随后方1-2米

---

#### №37 平行侧跟（侧面轨道跟拍）

**英文关键词**：Side Tracking / Truck

**提示词模板**：
```
Side-tracking camera trucks parallel to a [角色] walking briskly left to right on a [场景].
```

**案例说明**：从主体侧面平行移动，保速度/距离不变，展肢体语言/环境流动感，维持动态能量。

**推荐参数**：50mm、F2.8-F4、平行移动、速度跟随主体

---

#### №38 第一人称视角行走

**英文关键词**：FPV Walking / POV

**提示词模板**：
```
First-person POV camera advances with gentle walking sway through a [场景], 
the subject implied by hair, hood edge, or shadow in frame.
```

**案例说明**：平视模拟人行走视角，极强代入感/真实感，营造沉浸式体验，适合探索、登场、体验式旅程镜头。

**推荐参数**：24-35mm广角、F4-F5.6、步频自然晃动

---

### 类别B：变焦与焦点 (Zoom / Focus)

#### №4 眩晕效应（轨道推拉变焦 / 希区柯克变焦）

**英文关键词**：Dolly Zoom / Zolly / Vertigo Effect

**提示词模板**：
```
Dolly zoom (zolly): the camera moves backward while zooming in, violently warping 
and compressing the background. The subject stays the same size in frame despite 
extreme perspective distortion. A person frozen in fear, standing perfectly still, 
cinematic and tense.
```

**案例说明**：结合了镜头后移和反向变焦，通过扭曲空间感，营造出强烈的心理不安感。它能传达人物内心的恐慌或突如其来的顿悟，同时让主体始终占据画面的核心位置。最适合用在密闭且有纵深的空间里的震惊或恐惧时刻，比如走廊、楼梯间这类场景。

**推荐参数**：35mm广角、F2.8-F4、Zoom-in 同时 Dolly-out、速度需精准匹配

---

#### №5 微距变焦（眼睛/细节特写）

**英文关键词**：Macro Zoom / Eye Close-up

**提示词模板**：
```
A [眼睛颜色] human eye staring unblinking directly into the camera, 
[虹膜纹理/睫毛细节描述], [环境光在眼中的反射].
```

**案例说明**：采用极致的微距推进，营造出一种穿透感和探索感，能把熟悉的人脸转化成抽象的、近乎宏大的宇宙般的视觉景观。非常适合用在戏剧化、科幻、医疗或心理题材的镜头中，通过视觉效果暗示人物的内心世界、蜕变过程或隐藏的真相。

**推荐参数**：100mm微距、F1.8-F2.0、极浅景深、慢速推进

---

#### №6 超远距变焦（太空到街景）

**英文关键词**：Cosmic Hyper-Zoom

**提示词模板**：
```
COSMIC HYPER-ZOOM (ORBIT TO STREET): A single, unbroken zoom races from [远景] 
in deep space, through [中层] and [近层], and lands smoothly on [目标主体].
```

**案例说明**：极致的轴向变焦，能把极远的距离压缩成一个流畅无缝的镜头运动，让观众的视线从微距尺度直接切换到人物尺度，全程无需剪辑。它能快速交代场景位置、空间尺度和画面节奏。最适合用在开场镜头、预告片或转场画面。

**推荐参数**：16mm → 200mm超长焦变焦、F8-F11、全程保持焦点

---

#### №11 模糊变清晰（焦点推移）

**英文关键词**：Focus Pull / Rack to Sharp

**提示词模板**：
```
Cinematic focus pull reveals from full bokeh to sharp focus on a [角色] 
[状态描述], [背景光斑/环境], shallow depth of field, moody cinematic lighting.
```

**案例说明**：不依赖相机移动，而是通过调整焦点，让观众的视线从模糊的抽象画面逐渐聚焦到清晰的主体上。从梦幻/抽象过渡到真实/具体，能营造"从思绪中浮现"的诗意感。

**推荐参数**：85mm、F1.4-F2.0、焦段由远及近推移、速度缓慢

---

#### №12 焦点切换（前景→背景）

**英文关键词**：Rack Focus / Focus Shift

**提示词模板**：
```
A cinematic rack focus shot: a [前景物体] in sharp focus in the foreground while 
[背景内容] blurs behind, then the focus shifts to the background as the foreground softens.
```

**案例说明**：在保持相机位置不动的前提下，通过精准的焦点转换，在同一个画面里完成注意力的转移。可以在单镜头中引导观众注意不同叙事要素，建立前后关系对比。

**推荐参数**：85mm、F1.4-F2.0、焦点切换速度0.5-1秒

---

#### №24 平滑光学变焦（向内变焦）

**英文关键词**：Smooth Optical Zoom-in

**提示词模板**：
```
Smooth optical zoom-in on a calm face as it slowly fills the frame inside 
a softly lit interior with blurred background highlights.
```

**案例说明**：固定机位，镜头内变焦拉近，从心理层面聚焦，增强亲近感，让主体与环境疏离。适合内心戏、凝视镜头。

**推荐参数**：固定机位、50-85mm、匀速拉近

---

#### №25 平滑光学变焦（向外变焦）

**英文关键词**：Smooth Optical Zoom-out

**提示词模板**：
```
Smooth optical zoom-out from a centered seated person as a wide room 
is gradually revealed around them.
```

**案例说明**：固定机位，镜头外变焦拉远，展现环境细节，焦点从人物转至环境，增添剧情背景。

**推荐参数**：固定机位、24-35mm、匀速拉远

---

#### №26 急速变焦（冲击式变焦）

**英文关键词**：Snap Zoom / Crash Zoom

**提示词模板**：
```
Snap zoom straight into a [角色]'s eyes mid-realization against a chaotic, frozen background.
```

**案例说明**：镜头突然极致变焦，无过渡制造冲击，复刻震惊/顿悟，强行锁定观众注意力。最适合用在揭示真相、爆炸性消息、惊悚跳吓。

**推荐参数**：固定机位、极速变焦、0.1-0.3秒完成

---

### 类别C：摇臂与升降 (Crane / Pedestal)

#### №20 垂直下移（机位下降）

**英文关键词**：Pedestal Down

**提示词模板**：
```
Pedestal down on a standing figure exhaling slowly inside a [场景] with [环境描述].
```

**案例说明**：垂直下移，削弱主体主导地位，突出释然/内省，让情绪更接地气。

**推荐参数**：50mm、F2.8、垂直匀速下降

---

#### №21 垂直上移（机位上升）

**英文关键词**：Pedestal Up

**提示词模板**：
```
Pedestal up on a person rising emotionally amid a [环境] as the environment opens up.
```

**案例说明**：垂直上移，提升主体存在感，象征成长/顿悟/觉醒，直观强化情绪升华。

**推荐参数**：35mm、F2.8、垂直匀速上升

---

#### №22 摇臂上抬（高角度揭露）

**英文关键词**：Crane Up

**提示词模板**：
```
Crane up from a [角色/场景] standing together as a vast [环境] unfolds beneath them.
```

**案例说明**：上移+后退，拓宽视野，将亲近感转化为尺度感，揭露背景与情绪宏大感。

**推荐参数**：24mm广角、F8-F11、上升+后移复合运动

---

#### №23 摇臂下降（落地聚焦）

**英文关键词**：Crane Down

**提示词模板**：
```
Crane down onto a lone [角色] waiting in a wide [场景] that narrows into focus.
```

**案例说明**：缓缓下移，将磅礴感转化为亲近感，拉回人物个人空间，增强情绪代入。

**推荐参数**：35-50mm、F8-F2.8渐变、下降+前推复合运动

---

### 类别D：摇镜与倾斜 (Pan / Tilt / Roll)

#### №13 向上仰拍（垂直上摇）

**英文关键词**：Tilt-up

**提示词模板**：
```
A cinematic slow tilt-up shot from [起点,如靴子] to the face of a [角色描述] 
standing on [场景] with [环境] behind them.
```

**案例说明**：从地面摇至人物面部，逐步建立人物存在感，适合塑造权威/神秘人物，适配人物登场、氛围感场景。

**推荐参数**：50mm、F2.8-F4、匀速上摇、2-3秒完成

---

#### №14 向下俯拍（垂直下摇）

**英文关键词**：Tilt-down

**提示词模板**：
```
A [角色描述] holds eye contact in a [场景] as the camera slowly tilts down from face to [终点].
```

**案例说明**：从面部摇至脚部，循序渐进展细节，适合人物出场、时尚穿搭聚焦镜头。

**推荐参数**：50mm、F2.8-F4、匀速下摇

---

#### №33 快速甩镜（横摇甩切）

**英文关键词**：Whip Pan

**提示词模板**：
```
Whip pan [left/right] reveals a new subject across two connected spaces fused by streaking motion blur.
```

**案例说明**：极速横向甩动，先模糊后定格新主体，注入动感/惊喜感，适合场景转场、动作瞬间衔接。

**推荐参数**：24-35mm、高速甩动、利用动态模糊

---

#### №34 倾斜角度（荷兰式倾斜）

**英文关键词**：Dutch Angle / Roll

**提示词模板**：
```
Rolled camera frames an emotionally imbalanced character inside a tight, claustrophobic interior.
```

**案例说明**：故意倾斜拍摄，画面失衡复刻内心混乱，慎用，适合密闭空间情绪爆发时刻，放大心理张力。

**推荐参数**：35mm、F2.8、倾斜角度15-30°

---

### 类别E：环绕与弧形 (Orbit / Arc)

#### №17 半环绕运镜（180度半圆）

**英文关键词**：Half-Orbit (180°)

**提示词模板**：
```
A cinematic half-orbit shot: the camera moves 180° around a lone [角色] 
with [动作描述], transitioning from front to back, set in [场景].
```

**案例说明**：平视绕主体180度运动，保距离不变、视角切换，展纵深感/存在感，营造沉浸式动感。

**推荐参数**：50mm、F2.8-F4、轨道弧线匀速

---

#### №18 快速全环绕运镜（360度旋转）

**英文关键词**：Fast Orbit (360°)

**提示词模板**：
```
Fast 360° orbit around a fighter standing firm in a [场景] as lights blur into streaks.
```

**案例说明**：极速绕主体360度旋转，放大紧张感/主体掌控力，让主体在混乱背景中保持核心。

**推荐参数**：35mm、F2.8-F4、快速轨道旋转

---

#### №19 弧形缓推（缓慢弧形环绕）

**英文关键词**：Slow Arc

**提示词模板**：
```
Slow arc shot of a contemplative [角色] gazing off-camera in a [场景] with [光线描述].
```

**案例说明**：缓慢弧形绕主体侧面拍摄，克制展轮廓，增情感深度/亲近感，无需剪辑。

**推荐参数**：85mm、F2.0、慢速弧线

---

### 类别F：无人机与高空 (Drone / Aerial)

#### №27 无人机高空俯掠

**英文关键词**：Drone Flyover

**提示词模板**：
```
High-altitude drone flyover of a small group walking through expansive [自然景观] 
bathed in soft morning light.
```

**案例说明**：高空向前飞行俯瞰，突出尺度感/动态感，对比渺小人物与广阔环境，强化视觉冲击。

**推荐参数**：超广角、高空快速前飞

---

#### №28 无人机史诗级揭露

**英文关键词**：Epic Drone Reveal

**提示词模板**：
```
Epic drone reveal rising from behind a [前景遮挡] to expose a lone figure standing 
at a [位置] above a massive [环境] at [时间].
```

**案例说明**：上升+旋转，控制画面揭露节奏，积累期待感，带来戏剧性发现瞬间。

**推荐参数**：超广角、上升+旋转复合运动

---

#### №29 无人机大范围环绕

**英文关键词**：Wide Drone Orbit

**提示词模板**：
```
Wide drone orbit circling a central structure within a vast natural landscape, 
emphasizing immense scale.
```

**案例说明**：空中绕主体环绕，主体居中、环境旋转，同时突出主体掌控力/孤独感，传递尺度感与重要性。

**推荐参数**：超广角、高空环绕、半径50-100m

---

#### №30 上帝视角（垂直俯拍）

**英文关键词**：Top-Down / God View

**提示词模板**：
```
Top-down rotating drone shot of a lone figure in a [服装描述] centered in a [场景], 
[环境细节], and shifting light.
```

**案例说明**：垂直向下拍摄，将场景抽象为几何图形，强化孤独感/宿命感，适合象征意义强、关键神话时刻。

**推荐参数**：超广角、垂直向下、可带慢速旋转

---

#### №31 穿越机俯冲镜头

**英文关键词**：FPV Dive

**提示词模板**：
```
Aggressive FPV drone dive racing down tall [建筑] toward a [角色] reaching the base.
```

**案例说明**：极速向下俯冲，营造强烈速度感/紧迫感，适合追逐戏、揭秘，适配垂直空间感强的环境。

**推荐参数**：超广角、极速俯冲、近地急刹

---

### 类别G：特殊视角 (Special POV)

#### №7 过肩镜头

**英文关键词**：Over-the-Shoulder (OTS)

**提示词模板**：
```
Over-the-shoulder shot from a blurred [前景角色]'s shoulder, framing a [主体角色] 
under [光线描述] in a [场景], cinematic contrast, shallow depth of field.
```

**案例说明**：镜头越过前景人物的肩膀拍摄主体，能自然地建立画面的亲近感和视角代入感，让观众仿佛置身于场景之中。非常适合对话或对峙场景，既能保持空间的清晰度，又能突出人物的反应。

**推荐参数**：85mm、F1.4-F2.0、前景虚化+主体清晰

---

#### №8 鱼眼镜头（窥视视角）

**英文关键词**：Fisheye / Peephole Lens

**提示词模板**：
```
A fisheye lens view of a nervous [角色] standing alone in a dim [场景], 
walls curving unnaturally toward the edges, [光源描述], security-camera mood, 
cinematic tension, realistic lighting, shallow grime on the lens.
```

**案例说明**：夸张的广角镜头让画面边缘向外凸起，把观众塑造成隐藏的观察者的视角。画面的畸变感会营造出紧张、不安的氛围，同时带有一丝窥视感。最适合用在监视题材或心理悬疑的场景。

**推荐参数**：8-16mm鱼眼镜头、F2.8、镜头畸变明显

---

#### №9 遮挡后显露（横移揭露）

**英文关键词**：Lateral Wipe Reveal / Obscured Reveal

**提示词模板**：
```
Cinematic lateral wipe reveal from behind a [前景遮挡物], sliding sideways to reveal 
a person leaning against a wall, half-hidden and waiting, inside a [场景] with [环境描述].
```

**案例说明**：镜头从被遮挡的画面开始，通过横向移动逐渐露出拍摄主体，用有动机的运镜引导观众的视线，层层递进地营造悬念。通过自然的前景元素（墙壁、柱子）逐步揭露主体。

**推荐参数**：50-85mm、F2.8、横向匀速平移

---

#### №15 平视左移（轨道左移）

**英文关键词**：Truck Left

**提示词模板**：
```
Camera trucks left with strong parallax as a [角色] looks out from a [位置] 
over a layered [场景] at sunset, bathed in warm cinematic light.
```

**案例说明**：平视平行主体左滑，视差效果增纵深感/动感，不眩晕，适合探索、紧张氛围升级、人物观察。

---

#### №16 平视右移（轨道右移）

**英文关键词**：Truck Right

**提示词模板**：
```
Camera trucks right with strong parallax. A [角色] looks out from a [位置] 
over a layered [场景], cinematic depth and motion.
```

**案例说明**：平视平行主体右滑，背景纵深层次相对运动，增空间感/动感，适合需视觉节奏、突出环境尺度的场景。

---

#### №32 手持纪录片风格

**英文关键词**：Handheld

**提示词模板**：
```
Handheld camera follows a [角色] speaking candidly in a real-world [室内场景] 
with uncontrolled, practical lighting.
```

**案例说明**：平视拍摄带轻微抖动，营造纪实真实感，适合采访、真实感极强的镜头，适配生活化室内场景。

**推荐参数**：35mm、F2.8-F4、自然微晃、呼吸感

---

## 三、运镜选择决策树

```
你想通过镜头传达什么情绪？
│
├─ 建立/登场 ───→ 仰拍(#13) / 过肩(#7) / 摇臂上抬(#22) / 超远距变焦(#6)
│
├─ 紧张/压迫 ——→ 快速推进(#3) / 快速环绕(#18) / 急速变焦(#26) / 倾斜(#34)
│
├─ 孤独/落寞 ——→ 慢速后拉(#2) / 摇臂下降(#23) / 上帝视角(#30) / 跟随跟拍(#36)
│
├─ 悬念/揭示 ——→ 遮挡显露(#9) / 超远距变焦(#6) / 焦点推移(#11) / 鱼眼(#8)
│
├─ 震惊/顿悟 ——→ 眩晕效应(#4) / 急速变焦(#26) / 快速推进(#3)
│
├─ 探索/发现 ——→ 平视移(#15/#16) / 穿拍(#10) / 第一人称(#38) / 导引跟拍(#35)
│
├─ 内心/情感 ——→ 慢速推进(#1) / 微距变焦(#5) / 光学变焦内(#24) / 弧形缓推(#19)
│
├─ 宏大/史诗 ——→ 摇臂上抬(#22) / 无人机俯掠(#27) / 史诗揭露(#28) / 大环绕(#29)
│
├─ 纪实/真实 ——→ 手持(#32) / 第一人称(#38) / 焦点切换(#12)
│
├─ 行动/动感 ——→ 快速全环绕(#18) / 穿越机俯冲(#31) / 快速甩镜(#33) / 侧跟(#37)
│
└─ 结尾/落版 ——→ 慢速后拉(#2) / 摇臂下降(#23) / 光学变焦外(#25) / 垂直下移(#20)
```

---

## 四、运用规则（Kling/Seedance适配）

### Kling 适配注意

- Kling 每段 ≤5s，**一个运镜一个分镜**
- 复杂复合运镜（如后拉+变焦）可能在 Kling 中不稳定，优先用单一运镜
- 运镜描述需嵌入视频动作段（🎥段），不要放在生图帧段
- 每个分镜提示词首句包含：角色锚点 + 运镜关键词

### Seedance 适配注意

- Seedance 支持10-15s连续时间轴，可在一段内做多运镜衔接
- 运镜描述按时间轴分配：`0-5秒：[运镜描述]，5-10秒：[运镜切换]`
- 复杂运镜（如Dolly Zoom）在 Seedance 中效果可能优于 Kling
- 过肩镜头、鱼眼镜头的畸变效果 Seedance 支持度较好
