# 🎬 Storyboard Scavenger

> 把混乱创意清理成可拍摄的 AI 视频分镜。

<p align="center">
  <img src="img-hero.png" alt="Storyboard Scavenger" width="720">
</p>

---

## 这是什么？

一个**结构化的 AI 视频分镜提示词生成方法论**。不管你的创意有多模糊——一句话、一张图、一段 BGM——这个 Skill 都能帮你拆解成：

- **七要素结构化分镜**（风格核心 / 视觉基调 / 色彩影调 / 景别 / 构图 / 运镜手法 / 画面内容）
- **场景建立帧**（环境一致性锚点，杜绝多分镜环境跳变）
- **38 种运镜技巧库**（含参数：焦距、光圈、速度、方向）
- **电影参考锚点**（每个分镜必须锚定电影风格 DNA）

<p align="center">
  <img src="img-compare.png" alt="痛点 vs 解决方案" width="720">
</p>

## 支持平台

| 平台 | 单段时长 | 语言 | 特色 |
|------|---------|------|------|
| **Kling（可灵）** | ≤5s | 中文 | 独立分段，每段自包含 |
| **Seedance（即梦）** | ≤15s | 中文 + `@素材` 语法 | 多模态组合，视频延长 |

## 核心工作流

<p align="center">
  <img src="img-workflow.png" alt="五步工作流" width="720">
</p>

```
Step 0: 确认目标平台（Kling / Seedance）
         ↓
Step 1: 理解用户想法 + 深入挖掘细节
         ↓
Step 2: 构建分镜结构（七要素 + 电影参考锚点 + 场景建立帧）
         ↓
Step 3: 输出七要素分镜（平台映射 + 标准模板）
         ↓
Step 4: 优化建议 + 特殊镜头技巧
```

## 七要素结构（每个分镜必须完整）

<p align="center">
  <img src="img-elements.png" alt="分镜七要素" width="720">
</p>

| 要素 | 说明 | 示例 |
|------|------|------|
| **风格核心** | 电影锚点 + 流派 + 质感 + 杜绝什么 | 《银翼杀手2049》[Villeneuve/Deakins]，赛博朋克noir... |
| **视觉基调** | 画幅/胶片机型/镜头 | 9:16竖屏，24mm广角F2.4 |
| **色彩与影调** | 时代美学+主色+颗粒+布光 | 冷灰蓝+肌肤暖色点缀，自然光 |
| **景别** | 机位角度+人物比例+方位 | 地面仰拍5°，腿部占60% |
| **构图** | 主体位置+前景/背景 | 双腿居中纵向延伸 |
| **运镜手法** | 焦距+光圈+运动+速度+方向（≥3参数） | 24mm F2.4，固定机位 |
| **画面内容** | 角色姿态+道具+光影 | 白色厚底鞋→小腿→膝盖→大腿 |

## 场景建立帧机制

多分镜视频最常见的翻车点 = **环境跳变**（分镜1暖光木地板 → 分镜2冷光水泥地）。

**解决方案**：在正式分镜前先生成一张纯环境锚点图，所有后续分镜的环境要素必须与此帧对齐。

<p align="center">
  <img src="img-scene.png" alt="场景建立帧机制" width="720">
</p>

```
场景建立帧 → 定义空间布局/光源色温/色调/材质/道具/天气
     ↓
分镜01~N → 环境描述必须与建立帧对齐，仅允许因运镜角度不同产生的视角差异
```

## 目录结构

```
├── SKILL.md                              # 完整 Skill 文档（主入口）
├── quick-reference.md                    # 快速参考卡
├── references/
│   ├── lens-techniques-38.md             # 38种运镜技巧库
│   ├── seedance-prompt-patterns.md       # Seedance 2.0 提示词模式
│   ├── kling-storyboard-workflow.md      # Kling 实战工作流
│   └── cyberpunk-rain-night-example.md   # 完整七要素分镜范例（14镜+3段CRT）
├── templates/
│   └── storyboard-template.md            # 分镜模板（4种场景类型）
└── examples/
    └── example-prompts.md                # 实战案例集
```

## 使用方式

### 装进你的 AI Agent

任何支持 `SKILL.md` 技能约定的 Agent 都能使用它。以常见的用户级技能目录为例：

```bash
git clone https://github.com/ouxxyy/storyboard-scavenger.git ~/.agents/skills/storyboard-scavenger
```

装好后对 Agent 说「帮我把这个想法做成 AI 视频分镜」或直接提到可灵 / 即梦，Skill 会自动接管，按 Step 0–4 的流程走完并输出七要素分镜。

### 当作写作手册

不装 Agent 也可以直接读：

- [`SKILL.md`](SKILL.md) —— 完整方法论（主入口）
- [`quick-reference.md`](quick-reference.md) —— 快速参考卡
- [`examples/example-prompts.md`](examples/example-prompts.md) —— 实战案例集

## 可视化说明

打开 [`visual-guide.html`](visual-guide.html) 查看带动画的交互式 Skill 说明页（电影感暗色调，双击即可在浏览器中打开）。

<p align="center">
  <img src="img-platforms.png" alt="支持平台" width="720">
</p>

## 版本历史

| 版本 | 日期 | 更新 |
|------|------|------|
| v3.0 | 2026-06-12 | 新增「场景建立帧」机制 + 分镜场景锚点字段 + 环境一致性规则 |
| v2.0 | 2026-06-07 | 七要素结构化 + 38种运镜库 + Seedance 2.0 提示词模式 |
| v1.0 | 2026-04-11 | 初始版本 |

## 作者

作者全平台同名：**欧八同学**。

- 微信公众号：扫码关注
- 抖音：[搜索“欧八同学”](https://www.douyin.com/search/%E6%AC%A7%E5%85%AB%E5%90%8C%E5%AD%A6)
- 小红书：[搜索“欧八同学”](https://www.xiaohongshu.com/search_result?keyword=%E6%AC%A7%E5%85%AB%E5%90%8C%E5%AD%A6)
- X：[搜索“欧八同学”](https://x.com/search?q=%E6%AC%A7%E5%85%AB%E5%90%8C%E5%AD%A6&src=typed_query)

<p align="center">
  <img src="assets/wechat-qr.jpg" alt="欧八同学微信公众号二维码" width="260">
</p>

如果这个 Skill 帮你拍出了满意的视频，欢迎点个 Star；分镜翻车的案例也欢迎提 Issue，附上你的提示词和生成结果链接即可。

## License

[MIT](LICENSE)
