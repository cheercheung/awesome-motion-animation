<a id="infographic"></a>

<div align="center">

<a href="assets/infographic-zh-CN.png"><img src="assets/infographic-zh-CN.png" width="760" alt="32 个动效与动画 GitHub 项目的五分类信息图，点击查看高清版"></a>

<h1>用代码，搭一间动效工作室</h1>

<p>32 个 GitHub 项目，覆盖动画、3D、物理模拟、声音、剪辑与交付</p>

<p><a href="LICENSE"><img src="assets/badge-license.svg" alt="Collection license: CC BY 4.0"></a> <a href="#animation"><img src="assets/badge-projects.svg" alt="32 GitHub projects"></a> <a href="README.md"><img src="assets/badge-en.svg" alt="Read in English"></a> <a href="README_zh-CN.md"><img src="assets/badge-zh.svg" alt="阅读简体中文"></a></p>

<p><a href="#animation">浏览工具合集</a> · <a href="CONTRIBUTING.md">提交资源建议</a></p>

</div>


这个合集面向开发者、动效设计师与创意编程爱好者，把代码动效和视频制作中的工具按五个环节分类。根据你想完成的作品，找到当前环节需要的项目，再逐步搭建自己的制作流程。

这里收录的是 GitHub 项目与工具，包含开源项目及采用自定义许可的源码可用项目。免费条件和商业使用范围以各项目许可为准。


<a id="menu"></a>

## 📑 目录

- [合集概览](#overview)
- [从哪里开始](#getting-started)
- [制作流程](#workflow)
- [动画与编排](#animation)
- [3D 与场景](#scenes)
- [物理与手绘](#physics)
- [声音与剪辑](#audio)
- [渲染与交付](#delivery)
- [信息图](#infographic)
- [许可说明](#licensing)
- [参与贡献](#contributing)
- [致谢](#acknowledgements)

<a id="overview"></a>

## 🧭 合集概览
| 分类 | 项目数 |
| --- | ---: |
| [动画与编排](#animation) | 9 |
| [3D 与场景](#scenes) | 7 |
| [物理与手绘](#physics) | 5 |
| [声音与剪辑](#audio) | 8 |
| [渲染与交付](#delivery) | 3 |

<a id="getting-started"></a>

## ⚡ 从哪里开始

1. **先确定作品形式。** 网页动效、程序化视频、三维场景与手绘动画，适合从不同工具入手。
2. **先选一个核心工具。** 用 Remotion 探索 React 视频，用 Three.js 或 Babylon.js 搭建 3D 场景，或用 OpenToonz 制作手绘动画。
3. **按需要补齐其他环节。** 根据项目需要增加物理模拟、配音、字幕与混音。
4. **按上游文档安装和导出。** 每个工具的依赖、支持平台与资源需求不同，直接阅读对应仓库的入门说明。

合集用于工具发现与选型；你可以按需组合，无须一次安装全部项目。


也可以按当前任务直接选工具：

- **用 HTML 制作和渲染动效:** [HyperFrames](#project-23)
- **制作产品宣传片:** [cinetic](#project-24) 或 [Guizang Product Video Skill](#project-25)
- **粗剪素材:** [LosslessCut](#project-30) 适合保留原画质的选段，[video-use](#project-31) 适合按转录文本剪辑

<a id="workflow"></a>

## 🛠️ 制作流程

**想法 → 分镜 → 搭建 → 动画 → 混音 → 导出**

下面的分类帮助你定位工具在制作中的作用。各项目的具体组合方式取决于格式、依赖与工作环境。

<a id="animation"></a>

## 🎞️ 动画与编排

从时间轴、关键帧到矢量场景与数据图形，让画面动起来。

<a id="project-01"></a>

### 01 · [Remotion](https://github.com/remotion-dev/remotion)

<a href="https://github.com/remotion-dev/remotion"><img src="https://repository-images.githubusercontent.com/274495425/970f34be-47bd-4010-9def-bc1bf7fb0669" alt="Remotion — 官方项目 banner，点击访问仓库" width="760"></a>

用 React 编程生成视频。

**上游许可说明:** [Remotion custom license](https://github.com/remotion-dev/remotion/blob/main/LICENSE.md).

免费使用须符合上游资格条件，其他组织需要 Company License。

<a id="project-02"></a>

### 02 · [Anime.js](https://github.com/juliangarnier/anime)

<a href="https://github.com/juliangarnier/anime"><img src="https://repository-images.githubusercontent.com/53809090/dbff3ffc-8459-43db-8a05-b6fdca5c9ed9" alt="Anime.js — 官方项目 banner，点击访问仓库" width="760"></a>

通过时间轴编排 JavaScript 动画。

**上游许可说明:** [MIT](https://github.com/juliangarnier/anime/blob/master/LICENSE.md).

<a id="project-03"></a>

### 03 · [mo.js](https://github.com/mojs/mojs)

<a href="https://github.com/mojs/mojs"><img src="https://repository-images.githubusercontent.com/21234201/eb8c6800-895e-11ea-883c-97b8a49e3e1d" alt="mo.js — 官方项目 banner，点击访问仓库" width="760"></a>

制作图形爆发与动态效果。

**上游许可说明:** [MIT](https://github.com/mojs/mojs/blob/main/LICENSE.md).

<a id="project-04"></a>

### 04 · [Theatre.js](https://github.com/theatre-js/theatre)

<a href="https://github.com/theatre-js/theatre"><img src="https://opengraph.githubassets.com/9b8fb753fbdf588f154c96e9b5687d720ca907281bc7964bb8ab8540f6d053be/theatre-js/theatre" alt="Theatre.js — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

可视化编辑动画关键帧。

**上游许可说明:** [Apache-2.0 (core) / AGPL-3.0 (studio)](https://github.com/theatre-js/theatre#license).

core 运行时与 studio 可视化编辑器使用不同许可，请按实际组件核对。

<a id="project-05"></a>

### 05 · [Two.js](https://github.com/jonobr1/two.js)

<a href="https://github.com/jonobr1/two.js"><img src="https://repository-images.githubusercontent.com/5694937/c230f18d-aa36-47cd-911a-2722414d7ec6" alt="Two.js — 官方项目 banner，点击访问仓库" width="760"></a>

创建二维矢量场景与动画。

**上游许可说明:** [MIT](https://github.com/jonobr1/two.js/blob/dev/LICENSE).

<a id="project-06"></a>

### 06 · [D3](https://github.com/d3/d3)

<a href="https://github.com/d3/d3"><img src="https://repository-images.githubusercontent.com/943149/c8e15cb8-7046-4518-9677-cd5f56b226c0" alt="D3 — 官方项目 banner，点击访问仓库" width="760"></a>

制作数据驱动的图形与可视化。

**上游许可说明:** [ISC](https://github.com/d3/d3/blob/main/LICENSE).

<a id="project-23"></a>

### 23 · [HyperFrames](https://github.com/heygen-com/hyperframes)

<a href="https://github.com/heygen-com/hyperframes"><img src="https://opengraph.githubassets.com/6e0fcb958680bae36cd27d37c5186f86a71d55124942594928be8f96b16407cc/heygen-com/hyperframes" alt="HyperFrames — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

用 HTML/CSS 制作片头、叠加层和动态图形，再通过 CLI 渲染成 MP4

**上游许可说明:** [Apache-2.0](https://github.com/heygen-com/hyperframes/blob/main/LICENSE)

<a id="project-24"></a>

### 24 · [cinetic](https://github.com/Leonxlnx/cinetic)

<a href="https://github.com/Leonxlnx/cinetic"><img src="https://opengraph.githubassets.com/6243e867f2658391808e583356ce37ce36c9eb7b16410f04bbc75ef6680c2942/Leonxlnx/cinetic" alt="cinetic — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

让编码代理用 Remotion 或 HyperFrames 制作产品发布片或更新片，覆盖文案、文字动效到渲染

**上游许可说明:** [MIT](https://github.com/Leonxlnx/cinetic/blob/main/LICENSE)

默认渲染器 Remotion 适用[独立许可条款](https://github.com/remotion-dev/remotion/blob/main/LICENSE.md)

<a id="project-25"></a>

### 25 · [Guizang Product Video Skill](https://github.com/op7418/guizang-product-video-skill)

<a href="https://github.com/op7418/guizang-product-video-skill"><img src="https://opengraph.githubassets.com/c93b43abfb6d19922aff54dd39dab02d60b3b95a63a942a259fbaeeb83d3bcc0/op7418/guizang-product-video-skill" alt="Guizang Product Video Skill — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

复用真实的软件功能与界面组件，通过分镜、代码动效和声音设计制作版本更新片

**上游许可说明:** [AGPL-3.0](https://github.com/op7418/guizang-product-video-skill/blob/main/LICENSE)

内置的 CodePilot 回退素材保留 [Business Source License 1.1 条款](https://github.com/op7418/guizang-product-video-skill/blob/main/assets/fallback/LICENSE.CodePilot)

<a id="scenes"></a>

## 🧊 3D 与场景

搭建三维空间，控制摄像机，探索不同的场景渲染方式。

<a id="project-07"></a>

### 07 · [Three.js](https://github.com/mrdoob/three.js)

<a href="https://github.com/mrdoob/three.js"><img src="https://repository-images.githubusercontent.com/576201/6c52fa00-6238-11eb-8763-f36f6e226bba" alt="Three.js — 官方项目 banner，点击访问仓库" width="760"></a>

创建三维场景与摄像机运动。

**上游许可说明:** [MIT](https://github.com/mrdoob/three.js/blob/dev/LICENSE).

<a id="project-08"></a>

### 08 · [Babylon.js](https://github.com/BabylonJS/Babylon.js)

<a href="https://github.com/BabylonJS/Babylon.js"><img src="https://repository-images.githubusercontent.com/11007313/03147e80-4379-11ea-80b8-58c66da0bf29" alt="Babylon.js — 官方项目 banner，点击访问仓库" width="760"></a>

构建与渲染实时 3D 场景。

**上游许可说明:** [Apache-2.0](https://github.com/BabylonJS/Babylon.js/blob/master/license.md).

<a id="project-09"></a>

### 09 · [Drei](https://github.com/pmndrs/drei)

<a href="https://github.com/pmndrs/drei"><img src="https://opengraph.githubassets.com/a36c241a2aae4c847fba5f35ed57b9d5fea864c778d77c212fc0b47d513b7811/pmndrs/drei" alt="Drei — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

使用现成的 React Three Fiber 辅助组件。

**上游许可说明:** [MIT](https://github.com/pmndrs/drei/blob/master/LICENSE).

<a id="project-10"></a>

### 10 · [Spark](https://github.com/sparkjsdev/spark)

<a href="https://github.com/sparkjsdev/spark"><img src="https://opengraph.githubassets.com/98a8ddb16c31715bafc8899896163deaec7ec0d6768fe91882941a02c13510c2/sparkjsdev/spark" alt="Spark — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

使用 Three.js 渲染三维高斯泼溅场景。

**上游许可说明:** [MIT](https://github.com/sparkjsdev/spark/blob/main/LICENSE).

<a id="project-11"></a>

### 11 · [cables.gl](https://github.com/cables-gl/cables_electron)

<a href="https://github.com/cables-gl/cables_electron"><img src="https://opengraph.githubassets.com/00e4ac7410cf4f003e01bfd01dcfc9d0286ea0fa399733426513e707a72fc906/cables-gl/cables_electron" alt="cables.gl — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

在独立桌面编辑器中通过可视化节点搭建场景。

**上游许可说明:** [MIT](https://github.com/cables-gl/cables_electron/blob/develop/LICENCE).

<a id="project-26"></a>

### 26 · [MCP for Blender](https://github.com/ahujasid/mcp-for-blender)

<a href="https://github.com/ahujasid/mcp-for-blender"><img src="https://opengraph.githubassets.com/d0660785425b79050202708b4c7d9c4ba9cc60fc5c8ed3daee24bc87a00e6bbb/ahujasid/mcp-for-blender" alt="MCP for Blender — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

将 MCP 客户端连接到 Blender，在预演阶段搭建镜头、调整相机并查看场景预览

**上游许可说明:** [MIT](https://github.com/ahujasid/mcp-for-blender/blob/main/LICENSE)

<a id="project-27"></a>

### 27 · [Motion2MixamoRig](https://github.com/MaxLiu22/Motion2MixamoRig)

<a href="https://github.com/MaxLiu22/Motion2MixamoRig"><img src="https://opengraph.githubassets.com/f92b2987f7f19941685f12d63ea735fdfa122bfaccffb50cc9aaa1f1f4b386c7/MaxLiu22/Motion2MixamoRig" alt="Motion2MixamoRig — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

从视频中提取人体动作并重定向到 Mixamo 骨骼角色，供 3D 场景使用

**上游许可说明:** [Apache-2.0 (code)](https://github.com/MaxLiu22/Motion2MixamoRig/blob/main/LICENSE)

下载的模型、权重和角色素材适用[独立条款](https://github.com/MaxLiu22/Motion2MixamoRig#license)，SMPL-X 的默认许可限制商业使用

<a id="physics"></a>

## 🌊 物理与手绘

模拟物理运动，编写材质，为手绘角色赋予动作。

<a id="project-12"></a>

### 12 · [Taichi](https://github.com/taichi-dev/taichi)

<a href="https://github.com/taichi-dev/taichi"><img src="https://opengraph.githubassets.com/dca4a7a79c000fea5d3e77a49625bce5f4cc44f32b08d8217055a6c966fc08cb/taichi-dev/taichi" alt="Taichi — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

编写高性能、GPU 加速的物理模拟。

**上游许可说明:** [Apache-2.0](https://github.com/taichi-dev/taichi/blob/master/LICENSE).

<a id="project-13"></a>

### 13 · [SPlisHSPlasH](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH)

<a href="https://github.com/InteractiveComputerGraphics/SPlisHSPlasH"><img src="https://repository-images.githubusercontent.com/74058995/510e03f0-6306-48bb-afaf-5921b4455371" alt="SPlisHSPlasH — 官方项目 banner，点击访问仓库" width="760"></a>

模拟 SPH 流体并生成泡沫与喷溅效果。

**上游许可说明:** [MIT](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH/blob/master/LICENSE).

<a id="project-14"></a>

### 14 · [Custom Shader Material](https://github.com/FarazzShaikh/THREE-CustomShaderMaterial)

<a href="https://github.com/FarazzShaikh/THREE-CustomShaderMaterial"><img src="https://opengraph.githubassets.com/fce19e6042626c6ab4867793dca16d6eae1026d3924b178b9fbde1d5d8670a58/FarazzShaikh/THREE-CustomShaderMaterial" alt="Custom Shader Material — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

将自定义着色器与 Three.js 标准材质及光照结合。

**上游许可说明:** [MIT](https://github.com/FarazzShaikh/THREE-CustomShaderMaterial/blob/main/LICENSE.md).

<a id="project-15"></a>

### 15 · [OpenToonz](https://github.com/opentoonz/opentoonz)

<a href="https://github.com/opentoonz/opentoonz"><img src="https://opengraph.githubassets.com/fcf63601c29c69468fa3aa91adebbe79b0212c60538f31a47ab9c27258f5db54/opentoonz/opentoonz" alt="OpenToonz — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

制作手绘二维角色动画。

**上游许可说明:** [BSD-3-Clause + third-party notices](https://github.com/opentoonz/opentoonz/blob/master/LICENSE.txt).

第三方库与随附笔刷适用各自的许可条款。

<a id="project-28"></a>

### 28 · [ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase)

<a href="https://github.com/JohnHeibel/ClaudeAnimationBase"><img src="https://opengraph.githubassets.com/fa387dce7cb66fbf4d230c914ea4c3c1975b589de9b29283b56a47e6a916e061/JohnHeibel/ClaudeAnimationBase" alt="ClaudeAnimationBase — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

用 p5.js 和 p5.brush 制作手绘风格的角色短片，复用现成的表情并逐镜头渲染为 MP4

**上游许可说明:** [MIT](https://github.com/JohnHeibel/ClaudeAnimationBase/blob/main/LICENSE)

<a id="audio"></a>

## 🎧 声音与剪辑

完成配音、音频处理、字幕同步与自动剪辑。

<a id="project-16"></a>

### 16 · [Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS)

<a href="https://github.com/QwenLM/Qwen3-TTS"><img src="https://opengraph.githubassets.com/77e2240c1ce87a5a0b898992b90e670d5857070c6b0c8f8cfb59f93faceaef82/QwenLM/Qwen3-TTS" alt="Qwen3-TTS — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

生成富有表现力的语音，用于配音。

**上游许可说明:** [Apache-2.0](https://github.com/QwenLM/Qwen3-TTS/blob/main/LICENSE).

<a id="project-17"></a>

### 17 · [Audacity](https://github.com/audacity/audacity)

<a href="https://github.com/audacity/audacity"><img src="https://opengraph.githubassets.com/b15a43eca658d79444a94b5c8979c659e22b68f654cec298f4a68f16893ee941/audacity/audacity" alt="Audacity — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

录制、清理、编辑与混合音频。

**上游许可说明:** [GPL-3.0 + file-level notices](https://github.com/audacity/audacity/blob/master/LICENSE.txt).

文件级与第三方组件许可说明以上游文件为准。

<a id="project-18"></a>

### 18 · [Subtitle Edit](https://github.com/SubtitleEdit/subtitleedit)

<a href="https://github.com/SubtitleEdit/subtitleedit"><img src="https://opengraph.githubassets.com/a1e1ba001eea4a19eb1adfb4174f5f2a901b51e224d10cb3fea1bb69372fdf78/SubtitleEdit/subtitleedit" alt="Subtitle Edit — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

编辑字幕并调整时间同步。

**上游许可说明:** [MIT](https://github.com/SubtitleEdit/subtitleedit/blob/main/LICENSE).

<a id="project-19"></a>

### 19 · [Auto-Editor](https://github.com/WyattBlue/auto-editor)

<a href="https://github.com/WyattBlue/auto-editor"><img src="https://repository-images.githubusercontent.com/260117248/8e873ebb-fe50-48f2-8e62-e9ad9f85b3aa" alt="Auto-Editor — 官方项目 banner，点击访问仓库" width="760"></a>

根据静音或响度分析自动剪辑视频与音频。

**上游许可说明:** [Unlicense](https://github.com/WyattBlue/auto-editor/blob/master/LICENSE).

<a id="project-29"></a>

### 29 · [OpenCut](https://github.com/OpenCut-app/OpenCut)

<a href="https://github.com/OpenCut-app/OpenCut"><img src="https://opengraph.githubassets.com/5a57619992da9efc4dcf7869aabf5cb091e376aa583a711ff392bb9f7896987c/OpenCut-app/OpenCut" alt="OpenCut — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

用 OpenCut Classic 在浏览器时间线上剪辑素材，并在主仓库跟进新版编辑器

**上游许可说明:** [MIT](https://github.com/OpenCut-app/OpenCut/blob/main/LICENSE)

主仓库正在重写，目前可用的浏览器编辑器见 [OpenCut Classic](https://github.com/opencut-app/opencut-classic)

<a id="project-30"></a>

### 30 · [LosslessCut](https://github.com/mifi/lossless-cut)

<a href="https://github.com/mifi/lossless-cut"><img src="https://opengraph.githubassets.com/0ef4c12c8fc988a82b1540dd1871c725836935904ffe8bb073de6e3cc8c56776/mifi/lossless-cut" alt="LosslessCut — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

从相机素材中挑选可用镜头并做粗剪，在源格式和切点允许时跳过重新编码

**上游许可说明:** [GPL-2.0-only](https://github.com/mifi/lossless-cut/blob/master/LICENSE)

<a id="project-31"></a>

### 31 · [video-use](https://github.com/browser-use/video-use)

<a href="https://github.com/browser-use/video-use"><img src="https://opengraph.githubassets.com/e044180e0445e87a5dac37fe37a14c9470c7f102da044a18d09fc610dc6fb3dd/browser-use/video-use" alt="video-use — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

让剪辑代理依据逐词转录选择片段、删除口头填充词并烧录字幕

**上游许可说明:** [MIT](https://github.com/browser-use/video-use/blob/main/LICENSE)

文档中的转录流程需要 ElevenLabs API Key

<a id="project-32"></a>

### 32 · [Palmier Pro](https://github.com/palmier-io/palmier-pro)

<a href="https://github.com/palmier-io/palmier-pro"><img src="https://opengraph.githubassets.com/9d76ad33143b460b80e11ea49cb59273868e211977e4bb11472dd7b00e2c3092/palmier-io/palmier-pro" alt="Palmier Pro — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

在 macOS 时间线上通过 MCP 让代理参与剪辑，并在编辑器内生成素材

**上游许可说明:** [GPL-3.0 (source)](https://github.com/palmier-io/palmier-pro/blob/main/LICENSE)

公开源码使用 GPLv3，v0.7.6 之后的二进制发行版使用[专有许可](https://github.com/palmier-io/palmier-pro/blob/main/BINARY_LICENSE.md)

<a id="delivery"></a>

## 📦 渲染与交付

完成视频补帧、画面采集与最终编码。

<a id="project-20"></a>

### 20 · [RIFE](https://github.com/hzwer/ECCV2022-RIFE)

<a href="https://github.com/hzwer/ECCV2022-RIFE"><img src="https://opengraph.githubassets.com/6cbb4110b9a5ca968f5f26919056594374c1f523b6cab86b418665d4491f68b1/hzwer/ECCV2022-RIFE" alt="RIFE — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

通过视频补帧获得更流畅的画面与慢动作效果。

**上游许可说明:** [MIT](https://github.com/hzwer/ECCV2022-RIFE/blob/main/LICENSE).

<a id="project-21"></a>

### 21 · [OBS Studio](https://github.com/obsproject/obs-studio)

<a href="https://github.com/obsproject/obs-studio"><img src="https://repository-images.githubusercontent.com/13233158/2e2fae80-da26-11e9-8da2-e1e0b931a235" alt="OBS Studio — 官方项目 banner，点击访问仓库" width="760"></a>

采集屏幕并录制视频。

**上游许可说明:** [GPL-2.0-or-later](https://github.com/obsproject/obs-studio/blob/master/COPYING).

<a id="project-22"></a>

### 22 · [FFmpeg](https://github.com/FFmpeg/FFmpeg)

<a href="https://github.com/FFmpeg/FFmpeg"><img src="https://opengraph.githubassets.com/fe798c68729ffbdf282625a25ebb7e39bc34de686d2b430fe870b6f14e06984a/FFmpeg/FFmpeg" alt="FFmpeg — GitHub 官方仓库预览图，点击访问仓库" width="760"></a>

完成视频编码、格式转换与最终封装。

**上游许可说明:** [LGPL-2.1-or-later / optional GPL](https://github.com/FFmpeg/FFmpeg/blob/master/LICENSE.md).

启用的组件与外部库会影响最终构建产物的许可。

<a id="licensing"></a>

## 📄 许可说明

本仓库的原创整理文案与线条视觉采用 [CC BY 4.0](LICENSE)，引用时请署名 **@林悦己 cheer / cheercheung** 并注明修改。该许可只适用于本合集自己的内容，不会重新许可所链接的第三方项目。

每项资源都附有上游许可链接。Remotion 的免费使用有资格限制；Theatre.js 的 core 与 studio 使用不同许可；FFmpeg 的许可受构建组件影响。请根据实际使用的版本、组件、依赖、模型权重及素材核对上游条款。

项目 banner 优先使用其 GitHub 页面设置的官方分享图；没有自定义分享图时使用 GitHub 生成的仓库预览卡。所有图片均可点击访问对应项目。[查看封面来源](docs/media-sources.md)。这些上游图片不属于本合集的 CC BY 4.0 授权范围。

项目来源与许可信息核对日期：**2026-11-02**（01–22）、**2026-11-08**（23–32）。许可标签用于导航，完整条款以上游文件为准


<a id="contributing"></a>

## 🤝 参与贡献

通过 [阅读贡献指南](CONTRIBUTING.md) 了解收录要求，或 [提交项目建议](https://github.com/cheercheung/awesome-motion-animation/issues/new?template=resource.yml)。欢迎补充资源、修正用途说明、更新许可信息与改进翻译。

[读取项目数据](data/projects.json) · [查看维护方法](docs/maintenance.md)

<a id="acknowledgements"></a>

## 🙏 致谢

感谢所有上游项目的作者、贡献者与维护者。工具的开发、支持与许可由各自项目负责。

[Remotion](https://github.com/remotion-dev/remotion), [Anime.js](https://github.com/juliangarnier/anime), [mo.js](https://github.com/mojs/mojs), [Theatre.js](https://github.com/theatre-js/theatre), [Two.js](https://github.com/jonobr1/two.js), [D3](https://github.com/d3/d3), [Three.js](https://github.com/mrdoob/three.js), [Babylon.js](https://github.com/BabylonJS/Babylon.js), [Drei](https://github.com/pmndrs/drei), [Spark](https://github.com/sparkjsdev/spark), [cables.gl](https://github.com/cables-gl/cables_electron), [Taichi](https://github.com/taichi-dev/taichi), [SPlisHSPlasH](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH), [Custom Shader Material](https://github.com/FarazzShaikh/THREE-CustomShaderMaterial), [OpenToonz](https://github.com/opentoonz/opentoonz), [Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS), [Audacity](https://github.com/audacity/audacity), [Subtitle Edit](https://github.com/SubtitleEdit/subtitleedit), [Auto-Editor](https://github.com/WyattBlue/auto-editor), [RIFE](https://github.com/hzwer/ECCV2022-RIFE), [OBS Studio](https://github.com/obsproject/obs-studio), [FFmpeg](https://github.com/FFmpeg/FFmpeg), [HyperFrames](https://github.com/heygen-com/hyperframes), [cinetic](https://github.com/Leonxlnx/cinetic), [Guizang Product Video Skill](https://github.com/op7418/guizang-product-video-skill), [MCP for Blender](https://github.com/ahujasid/mcp-for-blender), [Motion2MixamoRig](https://github.com/MaxLiu22/Motion2MixamoRig), [ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase), [OpenCut](https://github.com/OpenCut-app/OpenCut), [LosslessCut](https://github.com/mifi/lossless-cut), [video-use](https://github.com/browser-use/video-use), [Palmier Pro](https://github.com/palmier-io/palmier-pro)

整理：**@林悦己 cheer**
