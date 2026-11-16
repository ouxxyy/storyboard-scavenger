# Storyboard Scavenger｜AI 视频分镜与提示词生成 Skill

<!-- discovery:start -->
## AI 视频分镜与可灵、即梦提示词生成

**怎样把一个视频创意拆成可灵、即梦或 Veo 可用的分镜提示词？** 先建立环境与角色锚点，再按风格、影调、景别、构图、运镜等七要素组织逐镜头提示词，按所选平台适配。

AI video storyboard and prompts for Kling, Seedance, Veo and Sora.

**开始使用：** [安装 Skill](#quick-start) · [平台工作流](models/) · [分镜案例](examples/example-prompts.md)。

**使用边界：** 主要交付分镜与提示词；视频生成平台的可用性、费用和最终画面效果需另行确认。

[按任务浏览欧八同学的全部工具](https://github.com/ouxxyy/ouba-classmate#按需求找)；如果本项目有帮助，欢迎收藏当前仓库。

<!-- discovery:end -->

<!-- hero:start -->

<p>
  <a href="https://github.com/ouxxyy/ouba-classmate"><img src="assets/hero-card.svg" width="100%" alt="storyboard-scavenger — 多平台七要素 AI 视频分镜提示词"></a>
</p>

**把一句创意、参考图或音乐想法整理为标准七要素 AI 视频分镜与场景建立帧，内置可灵 Kling、即梦 Seedance、Google Veo 与 OpenAI Sora 专用工作流。**  
<sub>Turns creative briefs or reference images into 7-element AI video storyboards with dedicated workflows for Kling, Seedance, Veo, and Sora.</sub>

<p>
  <a href="https://github.com/ouxxyy/ouba-classmate"><img src="https://img.shields.io/badge/SUITE-ouba--classmate-1f6feb?style=for-the-badge" alt="ouba-classmate Suite"></a>
  <a href="#quick-example"><img src="https://img.shields.io/badge/Quick_Example-0969da?style=for-the-badge" alt="Quick Example"></a>
  <a href="#quick-start"><img src="https://img.shields.io/badge/Quick_Start-238636?style=for-the-badge" alt="Quick Start"></a>
  <a href="models/"><img src="https://img.shields.io/badge/Models_Guide-8957e5?style=for-the-badge" alt="Models Guide"></a>
  <a href="CHANGELOG.md"><img src="https://img.shields.io/badge/Changelog-30363d?style=for-the-badge" alt="Changelog"></a>
  <a href="#english-overview"><img src="https://img.shields.io/badge/English-30363d?style=for-the-badge" alt="English"></a>
  <a href="https://github.com/ouxxyy"><img src="https://img.shields.io/badge/PROFILE-ouxxyy-30363d?style=for-the-badge" alt="Author Profile"></a>
</p>

<img src="assets/divider.svg" width="100%" alt="">

<!-- hero:end -->

> 把创意、参考图或音乐想法整理成 AI 视频分镜提示词，提供可灵 Kling、即梦 Seedance、Google Veo 与 OpenAI Sora 的专门工作流。

<p align="center">
  <img src="img-hero.png" alt="Storyboard Scavenger：把创意整理成 AI 视频分镜与七要素提示词" width="720">
</p>

---

> [!TIP]
> 🎁 扫码关注公众号「欧八同学」，免费领取 AI 案例与 Skill《大厂产品AI经验编程 200 套》→ [去扫码](#author)

[使用示例](#quick-example) · [开始使用](#quick-start) · [English](#english-overview)

<a id="quick-example"></a>

## 一次使用示例

**虚构输入：**「做一段可灵产品短片：雨夜街头，一双白鞋踏过积水。先给环境建立帧，再拆成独立镜头。」

**输出结构示例：** 环境锚点先确定湿路面、冷色街灯和雨夜；一个镜头按七要素写成：风格核心＝写实产品短片，视觉基调＝9:16／24mm，色彩影调＝冷灰蓝与暖色反光，景别＝低机位近景，构图＝白鞋位于下三分之一，运镜＝24mm／低速横移／跟随鞋尖，画面内容＝鞋底踏水、涟漪向外扩散。最终分镜还会按所选平台工作流组织。

这是格式示例，不是已生成的视频。完整案例见 [分镜提示词案例集](examples/example-prompts.md)，也可直接使用 [分镜模板](templates/storyboard-template.md)。

## 这是什么？

一个**结构化的 AI 视频分镜提示词生成方法论**。不管你的创意有多模糊——一句话、一张图、一段 BGM——这个 Skill 都能帮你拆解成：

- **七要素结构化分镜**（风格核心 / 视觉基调 / 色彩影调 / 景别 / 构图 / 运镜手法 / 画面内容）
- **场景建立帧**（环境一致性锚点，帮助减少多分镜环境跳变）
- **38 种运镜技巧库**（含参数：焦距、光圈、速度、方向）
- **电影参考锚点**（每个分镜必须锚定电影风格 DNA）

<p align="center">
  <img src="img-compare.png" alt="痛点 vs 解决方案" width="720">
</p>

## 支持平台

下表描述仓库内现有写作工作流，不是平台最新能力上限或本轮实机验证结论；生成前请在目标平台核对当前限制。

| 平台 | 本仓库工作流中的单段时长 | 语言 | 特色 |
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

<a id="quick-start"></a>

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

## 常见问题

### 它会直接生成视频吗？

主要产物是分镜与提示词。视频生成需要在目标平台完成，成本和可用能力以该平台为准。

### Kling 和 Seedance 都有专门写法吗？

仓库分别提供 [Kling 工作流](references/kling-storyboard-workflow.md) 和 [Seedance 提示词模式](references/seedance-prompt-patterns.md)。其他模型的通用借鉴，不等于经过验证的平台专属支持。

### 为什么仓库名和技能名不同？

仓库品牌是 Storyboard Scavenger，现有 `SKILL.md` 标识是 `seedance-storyboard`。安装目录示例沿用仓库名，使用时可直接描述任务；具体识别和调用方式以宿主为准。

### 能保证多个镜头的环境完全一致吗？

场景建立帧用于减少环境描述漂移，不能保证生成平台每次都输出完全一致的画面。

<a id="english-overview"></a>

## English overview

Storyboard Scavenger is an AI video storyboard and prompt-writing Agent Skill for Kling and Seedance. Give it an idea, reference image or music concept; it organizes seven-element shot descriptions, an establishing frame and camera-movement references. It writes prompts rather than rendering a finished video.

Start with the [installation and usage instructions](#quick-start), or read [SKILL.md](SKILL.md) and the [worked examples](examples/example-prompts.md). The existing skill identifier is `seedance-storyboard`. Dedicated platform guides describe this repository's workflow, not a guarantee of current model limits or visual consistency.

<!-- suite-matrix:start -->

## 更多开源项目 · More from ouba-classmate Suite

> 如果这个项目帮到了你，欢迎去旗舰合集仓 [**`ouxxyy/ouba-classmate`**](https://github.com/ouxxyy/ouba-classmate) 点一颗 Star 或一行安装全部 Skills：
> `npx skills add ouxxyy/ouba-classmate` · `gh api -X PUT /user/starred/ouxxyy/ouba-classmate`

| 仓库 · Repo | 分类 · Category | 它做什么 · What it does |
| --- | --- | --- |
| [`ouba-classmate`](https://github.com/ouxxyy/ouba-classmate) | SUITE · 旗舰合集 | **11 个原创项目总仓 + 一键安装全部 Skills + 在线战力测算与防身情报库**<br><sub>All-in-one Skills suite & benchmark</sub> |
| [`jd-resume-match`](https://github.com/ouxxyy/jd-resume-match) | CAREER · 求职涨薪 | **AI 简历优化与 JD 匹配体检（确定性公式 + 行号证据）**<br><sub>Deterministic JD matching & line-cited resume audit</sub> |
| [`ai-interviewer`](https://github.com/ouxxyy/ai-interviewer) | CAREER · 求职涨薪 | **中文语音/文字原话追问 AI 模拟面试官（含在线版）**<br><sub>Chinese voice AI mock interviewer anchored to your answers</sub> |
| [`job-search`](https://github.com/ouxxyy/job-search) | CAREER · 求职涨薪 | **跨 5 平台实时去重筛岗，输出带来源短名单**<br><sub>5-platform source-backed job search & shortlist builder</sub> |
| [`sherlock-company`](https://github.com/ouxxyy/sherlock-company) | CAREER · 求职涨薪 | **入职前四态证据公司背调与 Offer 核实清单**<br><sub>Pre-offer employer research with 4-state evidence boundaries</sub> |
| [`mbai`](https://github.com/ouxxyy/mbai) | CAREER · 求职涨薪 | **工作任务 AI 不可替代指数与 4 核决策复盘**<br><sub>Task-level AI irreplaceability index & decision reflection</sub> |
| [`codex-gif-video`](https://github.com/ouxxyy/codex-gif-video) | CREATIVE · AI 创作 | **69 种风格原生 GIF 与静音 MP4 素材生成 Skill**<br><sub>Native GPT Image 2.6 animated GIF & MP4 generator (69 styles)</sub> |
| [`storyboard-scavenger`](https://github.com/ouxxyy/storyboard-scavenger) · **Current** | CREATIVE · AI 创作 | **可灵/即梦/Veo/Sora 七要素 AI 视频分镜工作流**<br><sub>7-element AI video storyboard skill for Kling & Seedance</sub> |
| [`travel-art-album-skill`](https://github.com/ouxxyy/travel-art-album-skill) | CREATIVE · AI 创作 | **旅行照片艺术画册与单文件离线翻页相册 Skill**<br><sub>Art-styled travel photo proofs & standalone offline HTML flipbook</sub> |
| [`mystery-skill`](https://github.com/ouxxyy/mystery-skill) | COGNITION · 认知框架 | **Mystery 认知框架与职场心理博弈分析 Skill**<br><sub>Cognitive framework for interview frame & decision study</sub> |
| [`Attention`](https://github.com/ouxxyy/Attention) | LOCAL APP · 本地工具 | **ActivityWatch 本地专注力、心流时段与切换分析**<br><sub>Local ActivityWatch focus & context-switching dashboard</sub> |
| [`postapp`](https://github.com/ouxxyy/postapp) | LOCAL APP · 本地工具 | **Chrome 本地摄像头姿态检测与坐姿提醒插件**<br><sub>On-device MoveNet Chrome posture reminder extension</sub> |

<!-- suite-matrix:end -->

<a id="author"></a>

## 作者

作者全平台同名：**欧八同学**。

- 个人主页 / 联系我：[albertou.redboook.cn](https://albertou.redboook.cn/)
- 微信公众号：扫码关注，免费领取 AI 案例与 Skill《大厂产品AI经验编程 200 套》
- 抖音：[搜索“欧八同学”](https://www.douyin.com/search/%E6%AC%A7%E5%85%AB%E5%90%8C%E5%AD%A6)
- 小红书：[搜索“欧八同学”](https://www.xiaohongshu.com/search_result?keyword=%E6%AC%A7%E5%85%AB%E5%90%8C%E5%AD%A6)
- X：[搜索“欧八同学”](https://x.com/search?q=%E6%AC%A7%E5%85%AB%E5%90%8C%E5%AD%A6&src=typed_query)

<p align="center">
  <img src="assets/wechat-qr.jpg" alt="欧八同学微信公众号二维码" width="260">
</p>

<p align="center"><sub>扫码关注「欧八同学」，免费领取《大厂产品AI经验编程 200 套》</sub></p>

如果这个 Skill 帮你拍出了满意的视频，欢迎点个 Star；分镜翻车的案例也欢迎提 Issue，附上你的提示词和生成结果链接即可。

## License

[MIT](LICENSE)

<!-- footer:start -->

<p align="center">
  <a href="https://github.com/ouxxyy"><img src="assets/footer.svg" width="100%" alt="欧八同学 · ouxxyy — Positioning × AI Leverage × Salary Growth"></a>
</p>

<!-- footer:end -->
