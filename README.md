<a id="infographic"></a>

<div align="center">

<a href="assets/infographic-en.png"><img src="assets/infographic-en.png" width="760" alt="Infographic of 47 motion and animation GitHub projects in five categories; open full resolution"></a>

<h1>Awesome Motion & Animation</h1>

<p>47 GitHub projects for animation, 3D, physics, audio, editing, and delivery.</p>

<p><a href="LICENSE"><img src="assets/badge-license.svg" alt="Collection license: CC BY 4.0"></a> <a href="#animation"><img src="assets/badge-projects.svg" alt="47 GitHub projects"></a> <a href="README.md"><img src="assets/badge-en.svg" alt="Read in English"></a> <a href="README_zh-CN.md"><img src="assets/badge-zh.svg" alt="阅读简体中文"></a></p>

<p><a href="#animation">Explore the collection</a> · <a href="CONTRIBUTING.md">Suggest a resource</a></p>

</div>


A curated collection for developers, motion designers, and creative coders. Find tools by production stage, follow their official repositories, and build a workflow around the piece you want to make.

This collection includes open-source projects and source-available software with custom terms. Free-use eligibility and commercial terms depend on each upstream license.


<a id="menu"></a>

## 📑 Menu

- [Overview](#overview)
- [Getting started](#getting-started)
- [Workflow](#workflow)
- [Animation & Choreography](#animation)
  - [Data Motion](#data-motion-tools)
- [3D & Scenes](#scenes)
- [Physics & Drawing](#physics)
- [Audio & Editing](#audio)
- [Render & Delivery](#delivery)
- [Infographic](#infographic)
- [Licensing](#licensing)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

<a id="overview"></a>

## 🧭 Overview
| Category | Projects |
| --- | ---: |
| [Animation & Choreography](#animation) | 23 |
| [3D & Scenes](#scenes) | 7 |
| [Physics & Drawing](#physics) | 8 |
| [Audio & Editing](#audio) | 7 |
| [Render & Delivery](#delivery) | 2 |

<a id="getting-started"></a>

## ⚡ Getting started

1. **Choose the output.** Web motion, programmatic video, 3D scenes, and hand-drawn animation call for different starting points.
2. **Pick one core tool.** Explore React video with Remotion, build a 3D scene with Three.js or Babylon.js, or draw animation with OpenToonz.
3. **Add the stages you need.** Bring in physics, voiceovers, subtitles, and mixing as your project requires.
4. **Follow upstream setup and export instructions.** Dependencies, supported platforms, and hardware needs differ between tools.

Use this collection for discovery and tool selection. Choose the pieces you need; there is no requirement to install the entire list.


Start with the task you need to do:

- **Animate and render with HTML:** [HyperFrames](#project-23).
- **Make a product video:** [cinetic](#project-24) or [Guizang Product Video Skill](#project-25).
- **Rough-cut footage:** [LosslessCut](#project-30) for source-quality selects or [video-use](#project-31) for transcript-based edits.

<a id="workflow"></a>

## 🛠️ Workflow

**Idea → Storyboard → Build → Animate → Mix → Export**

The categories below show where tools can fit into production. Specific combinations depend on formats, dependencies, and your working environment.

<a id="animation"></a>

## 🎞️ Animation & Choreography

Timelines, keyframes, vector scenes, and data-driven graphics.

<a id="project-01"></a>

### 01 · [Remotion](https://github.com/remotion-dev/remotion)

Remotion renders React compositions frame by frame. Use React props to vary text, imagery, and other inputs, then preview the result in Studio before rendering a video.

**In production** — Build a reusable product demo and render a separate cut for each feature or language.

[Upstream guide](https://www.remotion.dev/docs/) · **License** [Remotion custom license](https://github.com/remotion-dev/remotion/blob/main/LICENSE.md)

Free use is limited by the upstream eligibility rules; a Company License is required for other organizations.

<a href="https://github.com/remotion-dev/remotion"><img src="https://repository-images.githubusercontent.com/274495425/970f34be-47bd-4010-9def-bc1bf7fb0669" alt="Remotion — official project banner; open repository" width="760"></a>

<a id="project-02"></a>

### 02 · [Anime.js](https://github.com/juliangarnier/anime)

Anime.js animates DOM elements, SVG, and JavaScript objects. Its timelines let you overlap or sequence effects, with easing and stagger controls for groups of elements.

**In production** — Build a title reveal where the headline, accents, and supporting text enter on different beats.

[Upstream guide](https://animejs.com/documentation/) · **License** [MIT](https://github.com/juliangarnier/anime/blob/master/LICENSE.md)

<a href="https://github.com/juliangarnier/anime"><img src="https://repository-images.githubusercontent.com/53809090/dbff3ffc-8459-43db-8a05-b6fdca5c9ed9" alt="Anime.js — official project banner; open repository" width="760"></a>

<a id="project-03"></a>

### 03 · [mo.js](https://github.com/mojs/mojs)

mo.js is a JavaScript toolkit for motion graphics built from shapes, bursts, and tweens. Combine those primitives to layer short accents over a web scene.

**In production** — Add a particle burst to a logo reveal or a confirmation moment in a product demo.

[Upstream guide](https://mojs.github.io/api/) · **License** [MIT](https://github.com/mojs/mojs/blob/main/LICENSE.md)

<a href="https://github.com/mojs/mojs"><img src="https://repository-images.githubusercontent.com/21234201/eb8c6800-895e-11ea-883c-97b8a49e3e1d" alt="mo.js — official project banner; open repository" width="760"></a>

<a id="project-04"></a>

### 04 · [Theatre.js](https://github.com/theatre-js/theatre)

Theatre.js adds a visual timeline to a scene built in JavaScript. Its Studio records keyframes for exposed properties such as camera position, object transforms, and material values.

**In production** — Tune the timing and framing of a Three.js product fly-through by adjusting keyframes in the editor.

[Upstream guide](https://www.theatrejs.com/docs/latest/) · **License** [Apache-2.0 (core) / AGPL-3.0 (studio)](https://github.com/theatre-js/theatre#license)

The core runtime and visual studio use different licenses; check the component you use.

<a href="https://github.com/theatre-js/theatre"><img src="https://opengraph.githubassets.com/9b8fb753fbdf588f154c96e9b5687d720ca907281bc7964bb8ab8540f6d053be/theatre-js/theatre" alt="Theatre.js — official GitHub repository preview; open repository" width="760"></a>

<a id="project-05"></a>

### 05 · [Two.js](https://github.com/jonobr1/two.js)

Two.js provides a 2D scene graph with paths, shapes, text, and groups. The same drawing API works with SVG, Canvas, or WebGL, and an update loop lets you animate scene properties.

**In production** — Animate icons, line illustrations, or callouts for an explainer.

[Upstream guide](https://two.js.org/docs/two/) · **License** [MIT](https://github.com/jonobr1/two.js/blob/dev/LICENSE)

<a href="https://github.com/jonobr1/two.js"><img src="https://repository-images.githubusercontent.com/5694937/c230f18d-aa36-47cd-911a-2722414d7ec6" alt="Two.js — official project banner; open repository" width="760"></a>

<a id="project-06"></a>

### 06 · [D3](https://github.com/d3/d3)

D3 maps data values to visual properties with scales, axes, and shape generators. Data joins and transitions can animate changes as values arrive, move, or disappear.

**In production** — Animate a launch metric chart or show how rankings change across a sequence of dates.

[Upstream guide](https://d3js.org/getting-started) · **License** [ISC](https://github.com/d3/d3/blob/main/LICENSE)

<a href="https://github.com/d3/d3"><img src="https://repository-images.githubusercontent.com/943149/c8e15cb8-7046-4518-9677-cd5f56b226c0" alt="D3 — official project banner; open repository" width="760"></a>

<a id="project-23"></a>

### 23 · [HyperFrames](https://github.com/heygen-com/hyperframes)

HyperFrames turns HTML, CSS, media, and seekable animation into video. Its CLI can preview a composition and render it to MP4.

**In production** — Render a title card, caption treatment, or launch animation using browser layout and GSAP timelines.

[Upstream guide](https://hyperframes.heygen.com/quickstart) · **License** [Apache-2.0](https://github.com/heygen-com/hyperframes/blob/main/LICENSE)

<a href="https://github.com/heygen-com/hyperframes"><img src="https://opengraph.githubassets.com/6e0fcb958680bae36cd27d37c5186f86a71d55124942594928be8f96b16407cc/heygen-com/hyperframes" alt="HyperFrames — official GitHub repository preview; open repository" width="760"></a>

<a id="project-24"></a>

### 24 · [cinetic](https://github.com/Leonxlnx/cinetic)

cinetic gives coding agents a workflow for writing, designing, and rendering product launch or update films. It includes treatments for animated type and product UI and runs with Remotion or HyperFrames.

**In production** — Turn a short product brief into a release trailer with moving type and a staged interface walkthrough.

[Upstream guide](https://github.com/Leonxlnx/cinetic/blob/main/docs/setup.md) · **License** [MIT](https://github.com/Leonxlnx/cinetic/blob/main/LICENSE)

Remotion, the default renderer, has [separate licensing terms](https://github.com/remotion-dev/remotion/blob/main/LICENSE.md).

<a href="https://github.com/Leonxlnx/cinetic"><img src="https://opengraph.githubassets.com/6243e867f2658391808e583356ce37ce36c9eb7b16410f04bbc75ef6680c2942/Leonxlnx/cinetic" alt="cinetic — official GitHub repository preview; open repository" width="760"></a>

<a id="project-25"></a>

### 25 · [Guizang Product Video Skill](https://github.com/op7418/guizang-product-video-skill)

Guizang Product Video Skill guides an agent through storyboarding, adapting real product components for video, and building motion and sound around each feature. The workflow uses the product’s own design language.

**In production** — Turn a software changelog into a short video that demonstrates updated features using the actual interface.

[Upstream guide](https://github.com/op7418/guizang-product-video-skill/blob/main/SKILL.md) · **License** [AGPL-3.0](https://github.com/op7418/guizang-product-video-skill/blob/main/LICENSE)

The bundled CodePilot fallback assets retain [Business Source License 1.1 terms](https://github.com/op7418/guizang-product-video-skill/blob/main/assets/fallback/LICENSE.CodePilot).

<a href="https://github.com/op7418/guizang-product-video-skill"><img src="https://opengraph.githubassets.com/c93b43abfb6d19922aff54dd39dab02d60b3b95a63a942a259fbaeeb83d3bcc0/op7418/guizang-product-video-skill" alt="Guizang Product Video Skill — official GitHub repository preview; open repository" width="760"></a>

<a id="project-33"></a>

### 33 · [liquid-glass-react](https://github.com/rdev/liquid-glass-react)

A React component for refractive glass effects with configurable displacement, elasticity, and pointer feedback.

**In production** — Add a tactile hover and press treatment to a product UI card or button.

[Upstream guide](https://github.com/rdev/liquid-glass-react#basic-usage) · **License** [MIT](https://github.com/rdev/liquid-glass-react/blob/master/LICENSE)

The displacement effect has limited support in Safari and Firefox.

<a href="https://github.com/rdev/liquid-glass-react"><img src="https://opengraph.githubassets.com/ff4b85397a8ce27632a488776f72d22067a82559ddd014d8dd7141c7407d956a/rdev/liquid-glass-react" alt="liquid-glass-react — official GitHub repository preview; open repository" width="760"></a>

<a id="project-38"></a>

### 38 · [GSAP](https://github.com/greensock/GSAP)

Sequence tweens on a timeline and control how elements enter, transform, and leave. Plugins add scroll progress, SVG morphing, and motion paths.

**In production** — Synchronize a title reveal, icon movement, and product shot with a single timeline.

[Upstream guide](https://gsap.com/docs/v3/) · **License** [GSAP Standard License](https://gsap.com/community/standard-license/)

The standard license restricts certain uses in visual animation builders that compete with Webflow. Review the terms for your integration.

<a href="https://github.com/greensock/GSAP"><img src="https://repository-images.githubusercontent.com/5905330/b77da600-0330-11ea-965b-ec11bc9d0759" alt="GSAP — official project banner; open repository" width="760"></a>

<a id="project-39"></a>

### 39 · [Motion](https://github.com/motiondivision/motion)

Animate layout changes, shared elements, gestures, and presence in React. Its motion values and spring transitions can connect an input to several animated properties.

**In production** — Animate a card moving between a grid and its detail view while preserving the visual connection.

[Upstream guide](https://motion.dev/docs/react-layout-animations) · **License** [MIT](https://github.com/motiondivision/motion/blob/main/LICENSE.md)

<a href="https://github.com/motiondivision/motion"><img src="https://repository-images.githubusercontent.com/157846876/2a38d0a3-269e-45b1-bd76-d95cdc971579" alt="Motion — official project banner; open repository" width="760"></a>

<a id="project-40"></a>

### 40 · [Motion Canvas](https://github.com/motion-canvas/motion-canvas)

Build vector animations from TypeScript scenes. Generator functions sequence and synchronize changes, and the editor previews timing and scene properties.

**In production** — Animate a process diagram step by step, then align the scene changes with narration.

[Upstream guide](https://motioncanvas.io/docs/quickstart/) · **License** [MIT](https://github.com/motion-canvas/motion-canvas/blob/main/LICENSE)

<a href="https://github.com/motion-canvas/motion-canvas"><img src="https://repository-images.githubusercontent.com/520955562/cc460c06-142c-4559-bd70-5ed5a5a797e3" alt="Motion Canvas — official project banner; open repository" width="760"></a>

<a id="project-41"></a>

### 41 · [Manim](https://github.com/ManimCommunity/manim)

Write Python scenes that transform equations, shapes, graphs, and other objects over time. Its scene and camera classes give code explicit control over composition and framing.

**In production** — Morph one equation into the next while highlighting the term that changed.

[Upstream guide](https://docs.manim.community/en/stable/tutorials/quickstart.html) · **License** [MIT](https://github.com/ManimCommunity/manim/blob/main/LICENSE)

<a href="https://github.com/ManimCommunity/manim"><img src="https://opengraph.githubassets.com/c79f4ca51562765675c86e5879c9cb4ca96a4471b552d5c841c39047dd46eca9/ManimCommunity/manim" alt="Manim — official GitHub repository preview; open repository" width="760"></a>

<a id="project-42"></a>

### 42 · [Rive Web Runtime](https://github.com/rive-app/rive-wasm)

Run Rive files in the browser through JavaScript and WebAssembly. A state machine can drive animations in response to interaction or changes in application data.

**In production** — Give a button or mascot distinct idle, hover, and success states driven by the application.

[Upstream guide](https://rive.app/docs/runtimes/web/web-js) · **License** [MIT](https://github.com/rive-app/rive-wasm/blob/master/LICENSE)

<a href="https://github.com/rive-app/rive-wasm"><img src="https://opengraph.githubassets.com/ead13c613493740dab4f48b9b28b843c71f38bccd7389576e59ab6369992b52b/rive-app/rive-wasm" alt="Rive Web Runtime — official GitHub repository preview; open repository" width="760"></a>

<a id="project-43"></a>

### 43 · [lottie-web](https://github.com/airbnb/lottie-web)

Play Lottie JSON animations exported from After Effects in a browser. Playback controls let you seek, change speed or direction, and play a defined frame segment.

**In production** — Embed an animated icon and play only its confirmation segment after a form is submitted.

[Upstream guide](https://github.com/airbnb/lottie-web#usage) · **License** [MIT](https://github.com/airbnb/lottie-web/blob/master/LICENSE.md)

<a href="https://github.com/airbnb/lottie-web"><img src="https://opengraph.githubassets.com/4696024a5842c3b2f05c40e0ef28ae122740ff3ab7f441924dc57c3721eeb8a9/airbnb/lottie-web" alt="lottie-web — official GitHub repository preview; open repository" width="760"></a>

<a id="project-44"></a>

### 44 · [react-spring](https://github.com/pmndrs/react-spring)

Animate React values with spring physics. Parameters such as mass, tension, and friction shape how elements respond when their targets change.

**In production** — Tune how a draggable card settles back into position after release.

[Upstream guide](https://www.react-spring.dev/docs/getting-started) · **License** [MIT](https://github.com/pmndrs/react-spring/blob/next/LICENSE)

<a href="https://github.com/pmndrs/react-spring"><img src="https://repository-images.githubusercontent.com/124257233/7bdde70a-e54f-4623-8cbc-537da87daba6" alt="react-spring — official project banner; open repository" width="760"></a>

<a id="project-45"></a>

### 45 · [AutoAnimate](https://github.com/formkit/auto-animate)

Attach animation to a parent element so its children transition when added, removed, or moved in the DOM.

**In production** — Smooth the reordering of cards in a filterable grid.

[Upstream guide](https://auto-animate.formkit.com/#usage) · **License** [MIT](https://github.com/formkit/auto-animate/blob/master/LICENSE)

<a href="https://github.com/formkit/auto-animate"><img src="https://repository-images.githubusercontent.com/491235501/1409bd0d-1d33-445a-9cf1-d59e951edb07" alt="AutoAnimate — official project banner; open repository" width="760"></a>

<a id="project-46"></a>

### 46 · [Popmotion](https://github.com/Popmotion/popmotion)

Use low-level JavaScript primitives for keyframe, spring, and inertia animations. An update callback lets you apply each value to your own renderer.

**In production** — Drive a custom canvas control with an inertial release and spring return.

[Upstream guide](https://github.com/Popmotion/popmotion#animation) · **License** [MIT (popmotion package)](https://github.com/Popmotion/popmotion/blob/master/packages/popmotion/LICENSE.md)

<a href="https://github.com/Popmotion/popmotion"><img src="https://opengraph.githubassets.com/6f48b75682a4cb9ff27ca34405b4cd5bf51e24acb15540dd4849f7ce695d422b/Popmotion/popmotion" alt="Popmotion — official GitHub repository preview; open repository" width="760"></a>

<a id="data-motion-tools"></a>

### Data Motion

Tools for animating charts, data transitions, and scientific graphics.

<a id="project-34"></a>

#### 34 · [Chart.js](https://github.com/chartjs/Chart.js)

A Canvas chart library with per-property animation options for start and end values, easing, duration, and transitions between chart states.

**In production** — Reveal a trend line or animate a bar chart when a filter changes.

[Upstream guide](https://www.chartjs.org/docs/latest/configuration/animations.html) · **License** [MIT](https://github.com/chartjs/Chart.js/blob/master/LICENSE.md)

<a href="https://github.com/chartjs/Chart.js"><img src="https://opengraph.githubassets.com/11486419ab3f242f4bcc603bab6bc128874cfb51875b1a304d3c4c49005893bc/chartjs/Chart.js" alt="Chart.js — official GitHub repository preview; open repository" width="760"></a>

<a id="project-35"></a>

#### 35 · [Apache ECharts](https://github.com/apache/echarts)

A JavaScript charting library that animates data entering, updating, and leaving a chart, with controls for timing, easing, and delay.

**In production** — Animate the change between two reporting periods in a data story.

[Upstream guide](https://echarts.apache.org/handbook/en/how-to/animation/transition/) · **License** [Apache-2.0](https://github.com/apache/echarts/blob/master/LICENSE)

<a href="https://github.com/apache/echarts"><img src="https://opengraph.githubassets.com/9957fce95001093a1cd13094908630115ec5b140b0d57d07e9781f2d414a82d0/apache/echarts" alt="Apache ECharts — official GitHub repository preview; open repository" width="760"></a>

<a id="project-36"></a>

#### 36 · [Matplotlib](https://github.com/matplotlib/matplotlib)

A Python plotting library with an animation API that updates plot elements at each frame. Its writers can save the sequence as a video or animated image.

**In production** — Animate a trajectory, simulation, or time series frame by frame for a scientific explainer.

[Upstream guide](https://matplotlib.org/stable/api/animation_api.html) · **License** [Matplotlib license](https://github.com/matplotlib/matplotlib/blob/main/LICENSE/LICENSE)

Bundled fonts and other components have separate terms in the [license directory](https://github.com/matplotlib/matplotlib/tree/main/LICENSE).

<a href="https://github.com/matplotlib/matplotlib"><img src="https://opengraph.githubassets.com/e278a31bbea57303c7ef0f1dfed0fbe8f152049b7e9fc55ce11deae7bf3802be/matplotlib/matplotlib" alt="Matplotlib — official GitHub repository preview; open repository" width="760"></a>

<a id="project-37"></a>

#### 37 · [Plotly.py](https://github.com/plotly/plotly.py)

A Python charting library that plays a sequence of chart states using animation frames, with optional play and pause controls.

**In production** — Build an interactive chart that reveals how values move over successive years.

[Upstream guide](https://plotly.com/python/animations/) · **License** [MIT](https://github.com/plotly/plotly.py/blob/main/LICENSE.txt)

<a href="https://github.com/plotly/plotly.py"><img src="https://opengraph.githubassets.com/1ea600ea02640a047655142be440721cf03162e2871a09523a91ba88db72b319/plotly/plotly.py" alt="Plotly.py — official GitHub repository preview; open repository" width="760"></a>

<a id="scenes"></a>

## 🧊 3D & Scenes

Build spatial scenes, control cameras, and explore different rendering approaches.

<a id="project-07"></a>

### 07 · [Three.js](https://github.com/mrdoob/three.js)

Three.js provides JavaScript building blocks for browser-based 3D, including cameras, lighting, materials, and model loaders. Set up a scene and drive its objects or camera with code.

**In production** — Stage a product turntable or a camera move through a glTF model for a product video.

[Upstream guide](https://threejs.org/manual/) · **License** [MIT](https://github.com/mrdoob/three.js/blob/dev/LICENSE)

<a href="https://github.com/mrdoob/three.js"><img src="https://repository-images.githubusercontent.com/576201/6c52fa00-6238-11eb-8763-f36f6e226bba" alt="Three.js — official project banner; open repository" width="760"></a>

<a id="project-08"></a>

### 08 · [Babylon.js](https://github.com/BabylonJS/Babylon.js)

Babylon.js is a real-time 3D engine with a scene graph, animation, and physically based materials. Its browser Inspector lets you inspect and tune a running scene.

**In production** — Prototype a product scene with animated parts, then review lighting and materials before recording it.

[Upstream guide](https://doc.babylonjs.com/) · **License** [Apache-2.0](https://github.com/BabylonJS/Babylon.js/blob/master/license.md)

<a href="https://github.com/BabylonJS/Babylon.js"><img src="https://repository-images.githubusercontent.com/11007313/03147e80-4379-11ea-80b8-58c66da0bf29" alt="Babylon.js — official project banner; open repository" width="760"></a>

<a id="project-09"></a>

### 09 · [Drei](https://github.com/pmndrs/drei)

Drei supplies reusable React Three Fiber components for common 3D tasks. Helpers for cameras, environments, text, and glTF loading handle much of the scene setup.

**In production** — Set up a React 3D product shot with an environment light and camera controls.

[Upstream guide](https://drei.docs.pmnd.rs/) · **License** [MIT](https://github.com/pmndrs/drei/blob/master/LICENSE)

<a href="https://github.com/pmndrs/drei"><img src="https://opengraph.githubassets.com/a36c241a2aae4c847fba5f35ed57b9d5fea864c778d77c212fc0b47d513b7811/pmndrs/drei" alt="Drei — official GitHub repository preview; open repository" width="760"></a>

<a id="project-10"></a>

### 10 · [Spark](https://github.com/sparkjsdev/spark)

Spark renders 3D Gaussian splats inside Three.js and supports formats such as PLY and SPZ. A scene can combine splats with mesh objects and transform them together.

**In production** — Use a scanned location as a backdrop and add 3D titles or mesh props for a camera move.

[Upstream guide](https://sparkjs.dev/docs/) · **License** [MIT](https://github.com/sparkjsdev/spark/blob/main/LICENSE)

<a href="https://github.com/sparkjsdev/spark"><img src="https://opengraph.githubassets.com/98a8ddb16c31715bafc8899896163deaec7ec0d6768fe91882941a02c13510c2/sparkjsdev/spark" alt="Spark — official GitHub repository preview; open repository" width="760"></a>

<a id="project-11"></a>

### 11 · [cables.gl](https://github.com/cables-gl/cables_electron)

The standalone cables.gl editor lets you connect visual nodes into patches on a desktop. Patches route data between operations that control graphics and animation.

**In production** — Build a looping abstract background by connecting geometry, transforms, and timing nodes.

[Upstream guide](https://cables.gl/standalone) · **License** [MIT](https://github.com/cables-gl/cables_electron/blob/develop/LICENCE)

<a href="https://github.com/cables-gl/cables_electron"><img src="https://opengraph.githubassets.com/00e4ac7410cf4f003e01bfd01dcfc9d0286ea0fa399733426513e707a72fc906/cables-gl/cables_electron" alt="cables.gl — official GitHub repository preview; open repository" width="760"></a>

<a id="project-26"></a>

### 26 · [MCP for Blender](https://github.com/ahujasid/mcp-for-blender)

MCP for Blender connects an MCP client to a Blender add-on that can inspect and modify a scene. The agent can arrange objects and cameras and request viewport or camera views for review.

**In production** — Block out a sequence and compare alternate camera angles before adding detailed models or lighting.

[Upstream guide](https://github.com/ahujasid/mcp-for-blender#quickstart) · **License** [MIT](https://github.com/ahujasid/mcp-for-blender/blob/main/LICENSE)

<a href="https://github.com/ahujasid/mcp-for-blender"><img src="https://opengraph.githubassets.com/d0660785425b79050202708b4c7d9c4ba9cc60fc5c8ed3daee24bc87a00e6bbb/ahujasid/mcp-for-blender" alt="MCP for Blender — official GitHub repository preview; open repository" width="760"></a>

<a id="project-27"></a>

### 27 · [Motion2MixamoRig](https://github.com/MaxLiu22/Motion2MixamoRig)

Motion2MixamoRig estimates body motion from video, then retargets it to a Mixamo rig. Its export can be imported into Blender as an animated character.

**In production** — Start a 3D performance from a filmed movement reference and refine the result in Blender.

[Upstream guide](https://github.com/MaxLiu22/Motion2MixamoRig/blob/main/docs/user-guide.md) · **License** [Apache-2.0 (code)](https://github.com/MaxLiu22/Motion2MixamoRig/blob/main/LICENSE)

Downloaded models, weights, and character assets have [separate terms](https://github.com/MaxLiu22/Motion2MixamoRig#license); the default SMPL-X license limits commercial use.

<a href="https://github.com/MaxLiu22/Motion2MixamoRig"><img src="https://opengraph.githubassets.com/f92b2987f7f19941685f12d63ea735fdfa122bfaccffb50cc9aaa1f1f4b386c7/MaxLiu22/Motion2MixamoRig" alt="Motion2MixamoRig — official GitHub repository preview; open repository" width="760"></a>

<a id="physics"></a>

## 🌊 Physics & Drawing

Simulate physical motion, write materials, and animate hand-drawn characters.

<a id="project-12"></a>

### 12 · [Taichi](https://github.com/taichi-dev/taichi)

Taichi adds parallel kernels and data structures to Python for numerical and graphics workloads. Simulation code can target a CPU or a supported GPU backend.

**In production** — Prototype a particle or cloth effect and tune how it moves before using it in a shot.

[Upstream guide](https://docs.taichi-lang.org/) · **License** [Apache-2.0](https://github.com/taichi-dev/taichi/blob/master/LICENSE)

<a href="https://github.com/taichi-dev/taichi"><img src="https://opengraph.githubassets.com/dca4a7a79c000fea5d3e77a49625bce5f4cc44f32b08d8217055a6c966fc08cb/taichi-dev/taichi" alt="Taichi — official GitHub repository preview; open repository" width="760"></a>

<a id="project-13"></a>

### 13 · [SPlisHSPlasH](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH)

SPlisHSPlasH simulates fluids with smoothed particle hydrodynamics and can generate secondary spray, foam, and bubbles. It exports particle data for downstream tools.

**In production** — Simulate a liquid splash and bring the particle sequence into Blender for lighting and rendering.

[Upstream guide](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH/blob/master/doc/py_getting_started.md) · **License** [MIT](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH/blob/master/LICENSE)

<a href="https://github.com/InteractiveComputerGraphics/SPlisHSPlasH"><img src="https://repository-images.githubusercontent.com/74058995/510e03f0-6306-48bb-afaf-5921b4455371" alt="SPlisHSPlasH — official project banner; open repository" width="760"></a>

<a id="project-14"></a>

### 14 · [Custom Shader Material](https://github.com/FarazzShaikh/THREE-CustomShaderMaterial)

Custom Shader Material lets you add custom vertex and fragment logic to a standard Three.js material. The base material can still supply features such as lighting and roughness.

**In production** — Add a procedural reveal or displacement to a product surface while keeping its existing scene lighting.

[Upstream guide](https://github.com/FarazzShaikh/THREE-CustomShaderMaterial#installation) · **License** [MIT](https://github.com/FarazzShaikh/THREE-CustomShaderMaterial/blob/main/LICENSE.md)

<a href="https://github.com/FarazzShaikh/THREE-CustomShaderMaterial"><img src="https://opengraph.githubassets.com/fce19e6042626c6ab4867793dca16d6eae1026d3924b178b9fbde1d5d8670a58/FarazzShaikh/THREE-CustomShaderMaterial" alt="Custom Shader Material — official GitHub repository preview; open repository" width="760"></a>

<a id="project-15"></a>

### 15 · [OpenToonz](https://github.com/opentoonz/opentoonz)

OpenToonz is a 2D animation application for drawing and painting frames, arranging exposures in an Xsheet, and compositing levels with effects. It supports vector and raster artwork.

**In production** — Draw a character reaction frame by frame, time it in the Xsheet, and composite it with a background.

[Upstream guide](https://opentoonz.readthedocs.io/en/latest/) · **License** [BSD-3-Clause + third-party notices](https://github.com/opentoonz/opentoonz/blob/master/LICENSE.txt)

Third-party libraries and bundled brushes carry their own terms.

<a href="https://github.com/opentoonz/opentoonz"><img src="https://opengraph.githubassets.com/fcf63601c29c69468fa3aa91adebbe79b0212c60538f31a47ab9c27258f5db54/opentoonz/opentoonz" alt="OpenToonz — official GitHub repository preview; open repository" width="760"></a>

<a id="project-28"></a>

### 28 · [ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase)

ClaudeAnimationBase is a p5.js and p5.brush starter kit with reusable character views, expressions, and scene code. It includes an agent guide and a renderer for contact sheets and MP4 output.

**In production** — Storyboard a hand-painted reaction short, review the poses on a contact sheet, and render the scene.

[Upstream guide](https://github.com/JohnHeibel/ClaudeAnimationBase/blob/main/ANIMATION_GUIDE.md) · **License** [MIT](https://github.com/JohnHeibel/ClaudeAnimationBase/blob/main/LICENSE)

<a href="https://github.com/JohnHeibel/ClaudeAnimationBase"><img src="https://opengraph.githubassets.com/fa387dce7cb66fbf4d230c914ea4c3c1975b589de9b29283b56a47e6a916e061/JohnHeibel/ClaudeAnimationBase" alt="ClaudeAnimationBase — official GitHub repository preview; open repository" width="760"></a>

<a id="project-47"></a>

### 47 · [tsParticles](https://github.com/tsparticles/tsparticles)

Configure particle emitters, motion, interactions, and presets to build effects such as confetti and fireworks in the browser.

**In production** — Trigger a short confetti burst when a product demo reaches a success state.

[Upstream guide](https://particles.js.org/) · **License** [MIT](https://github.com/tsparticles/tsparticles/blob/main/LICENSE)

<a href="https://github.com/tsparticles/tsparticles"><img src="https://repository-images.githubusercontent.com/238514517/0b2e31ff-aef0-45de-99ab-938bae64a744" alt="tsParticles — official project banner; open repository" width="760"></a>

<a id="project-48"></a>

### 48 · [PixiJS](https://github.com/pixijs/pixijs)

Render a real-time 2D scene with sprites, textures, filters, and an update loop. Animated sprites can play texture frames while code controls scene transforms.

**In production** — Build an interactive 2D hero with looping sprite animation and a reactive filter.

[Upstream guide](https://pixijs.com/8.x/guides/getting-started/quick-start) · **License** [MIT](https://github.com/pixijs/pixijs/blob/dev/LICENSE)

<a href="https://github.com/pixijs/pixijs"><img src="https://repository-images.githubusercontent.com/7741856/20ddf680-86b9-11e9-90e3-aa6dd61c184a" alt="PixiJS — official project banner; open repository" width="760"></a>

<a id="project-49"></a>

### 49 · [p5.js](https://github.com/processing/p5.js)

Draw graphics in JavaScript with a recurring draw loop, time and input variables, and 2D or WebGL renderers.

**In production** — Make a kinetic typography study or an interactive procedural pattern that changes each frame.

[Upstream guide](https://p5js.org/reference/p5/draw/) · **License** [LGPL-2.1](https://github.com/processing/p5.js/blob/main/license.txt)

<a href="https://github.com/processing/p5.js"><img src="https://opengraph.githubassets.com/7b59b190b1f02477594855877e51bd3e9783c066ed55fd897a74cb641879ca51/processing/p5.js" alt="p5.js — official GitHub repository preview; open repository" width="760"></a>

<a id="audio"></a>

## 🎧 Audio & Editing

Add voiceovers, clean up audio, sync subtitles, and automate editing.

<a id="project-17"></a>

### 17 · [Audacity](https://github.com/audacity/audacity)

Audacity is a desktop editor for recording and editing audio tracks. Its tools cover waveform edits, noise reduction, fades, and level adjustment before export.

**In production** — Clean up a voiceover take and balance its level against a music bed before bringing the mix into a video editor.

[Upstream guide](https://manual.audacityteam.org/) · **License** [GPL-3.0 + file-level notices](https://github.com/audacity/audacity/blob/master/LICENSE.txt)

See the upstream license for file-level and third-party notices.

<a href="https://github.com/audacity/audacity"><img src="https://opengraph.githubassets.com/b15a43eca658d79444a94b5c8979c659e22b68f654cec298f4a68f16893ee941/audacity/audacity" alt="Audacity — official GitHub repository preview; open repository" width="760"></a>

<a id="project-18"></a>

### 18 · [Subtitle Edit](https://github.com/SubtitleEdit/subtitleedit)

Subtitle Edit lets you preview captions against video, adjust cue timing and text, and convert between subtitle formats. Its built-in checks help catch common subtitle errors.

**In production** — Review auto-generated captions for timing and line breaks, then deliver a corrected SRT.

[Upstream guide](https://subtitleedit.github.io/subtitleedit/) · **License** [MIT](https://github.com/SubtitleEdit/subtitleedit/blob/main/LICENSE)

<a href="https://github.com/SubtitleEdit/subtitleedit"><img src="https://opengraph.githubassets.com/a1e1ba001eea4a19eb1adfb4174f5f2a901b51e224d10cb3fea1bb69372fdf78/SubtitleEdit/subtitleedit" alt="Subtitle Edit — official GitHub repository preview; open repository" width="760"></a>

<a id="project-19"></a>

### 19 · [Auto-Editor](https://github.com/WyattBlue/auto-editor)

Auto-Editor analyzes a video with rules such as audio loudness or detected motion. It can trim or speed through selected intervals and export an editing timeline for further work.

**In production** — Make a first pass on a screen recording or talking-head take, then refine the cuts by hand.

[Upstream guide](https://auto-editor.com/docs) · **License** [Unlicense](https://github.com/WyattBlue/auto-editor/blob/master/LICENSE)

<a href="https://github.com/WyattBlue/auto-editor"><img src="https://repository-images.githubusercontent.com/260117248/8e873ebb-fe50-48f2-8e62-e9ad9f85b3aa" alt="Auto-Editor — official project banner; open repository" width="760"></a>

<a id="project-29"></a>

### 29 · [OpenCut](https://github.com/OpenCut-app/OpenCut)

OpenCut Classic is the browser editor linked by the OpenCut project. It provides a timeline and preview for arranging and trimming video clips.

**In production** — Assemble a short sequence from several existing clips in a browser.

[Upstream guide](https://github.com/opencut-app/opencut-classic) · **License** [MIT](https://github.com/OpenCut-app/OpenCut/blob/main/LICENSE)

The main repository is undergoing a rewrite; use [OpenCut Classic](https://github.com/opencut-app/opencut-classic) for the current browser editor.

<a href="https://github.com/OpenCut-app/OpenCut"><img src="https://opengraph.githubassets.com/5a57619992da9efc4dcf7869aabf5cb091e376aa583a711ff392bb9f7896987c/OpenCut-app/OpenCut" alt="OpenCut — official GitHub repository preview; open repository" width="760"></a>

<a id="project-30"></a>

### 30 · [LosslessCut](https://github.com/mifi/lossless-cut)

LosslessCut is an FFmpeg-based desktop app for trimming media and working with its tracks. It can copy streams without re-encoding when the format and cut points allow.

**In production** — Pull usable segments out of a long camera recording before importing them into a full timeline editor.

[Upstream guide](https://losslesscut.app/docs/getting-started) · **License** [GPL-2.0-only](https://github.com/mifi/lossless-cut/blob/master/LICENSE)

<a href="https://github.com/mifi/lossless-cut"><img src="https://opengraph.githubassets.com/0ef4c12c8fc988a82b1540dd1871c725836935904ffe8bb073de6e3cc8c56776/mifi/lossless-cut" alt="LosslessCut — official GitHub repository preview; open repository" width="760"></a>

<a id="project-31"></a>

### 31 · [video-use](https://github.com/browser-use/video-use)

video-use gives a coding agent a word-level transcript and visual checks near candidate cuts. It turns edit decisions into a rendered video with FFmpeg and can add captions or motion overlays.

**In production** — Clean up a talking-head clip by choosing between retakes, removing false starts, and checking the rendered joins.

[Upstream guide](https://github.com/browser-use/video-use/blob/main/SKILL.md) · **License** [MIT](https://github.com/browser-use/video-use/blob/main/LICENSE)

The documented transcription workflow requires an ElevenLabs API key.

<a href="https://github.com/browser-use/video-use"><img src="https://opengraph.githubassets.com/e044180e0445e87a5dac37fe37a14c9470c7f102da044a18d09fc610dc6fb3dd/browser-use/video-use" alt="video-use — official GitHub repository preview; open repository" width="760"></a>

<a id="project-32"></a>

### 32 · [Palmier Pro](https://github.com/palmier-io/palmier-pro)

Palmier Pro is a macOS timeline editor with MCP support and in-editor media generation. An MCP client can issue editing actions while the timeline stays available for manual review.

**In production** — Ask an agent to assemble or adjust a rough cut, then inspect and refine it on the timeline.

[Upstream guide](https://github.com/palmier-io/palmier-pro#mcp-server) · **License** [GPL-3.0 (source)](https://github.com/palmier-io/palmier-pro/blob/main/LICENSE)

Published source is GPLv3. Binary releases after v0.7.6 are distributed under a [proprietary license](https://github.com/palmier-io/palmier-pro/blob/main/BINARY_LICENSE.md).

<a href="https://github.com/palmier-io/palmier-pro"><img src="https://opengraph.githubassets.com/9d76ad33143b460b80e11ea49cb59273868e211977e4bb11472dd7b00e2c3092/palmier-io/palmier-pro" alt="Palmier Pro — official GitHub repository preview; open repository" width="760"></a>

<a id="delivery"></a>

## 📦 Render & Delivery

Interpolate frames and encode the final output.

<a id="project-20"></a>

### 20 · [RIFE](https://github.com/hzwer/ECCV2022-RIFE)

RIFE estimates intermediate frames between existing images. Its inference scripts accept a video or image sequence and can produce output at a higher frame rate.

**In production** — Create a slow-motion insert from a short clip and review fast movement and occlusions for interpolation artifacts.

[Upstream guide](https://github.com/hzwer/ECCV2022-RIFE#cli-usage) · **License** [MIT](https://github.com/hzwer/ECCV2022-RIFE/blob/main/LICENSE)

<a href="https://github.com/hzwer/ECCV2022-RIFE"><img src="https://opengraph.githubassets.com/6cbb4110b9a5ca968f5f26919056594374c1f523b6cab86b418665d4491f68b1/hzwer/ECCV2022-RIFE" alt="RIFE — official GitHub repository preview; open repository" width="760"></a>

<a id="project-22"></a>

### 22 · [FFmpeg](https://github.com/FFmpeg/FFmpeg)

FFmpeg is a command-line toolkit for reading, filtering, encoding, and packaging media streams. It can scale footage, select audio or subtitle tracks, and output different codecs and containers.

**In production** — Produce delivery variants from a master render, such as a resized review MP4 with the intended audio track.

[Upstream guide](https://ffmpeg.org/ffmpeg.html) · **License** [LGPL-2.1-or-later / optional GPL](https://github.com/FFmpeg/FFmpeg/blob/master/LICENSE.md)

Enabled components and external libraries affect the license of the resulting build.

<a href="https://github.com/FFmpeg/FFmpeg"><img src="https://opengraph.githubassets.com/fe798c68729ffbdf282625a25ebb7e39bc34de686d2b430fe870b6f14e06984a/FFmpeg/FFmpeg" alt="FFmpeg — official GitHub repository preview; open repository" width="760"></a>

<a id="licensing"></a>

## 📄 Licensing

The original curation text and line-art visuals in this repository are licensed under [CC BY 4.0](LICENSE). Attribute **@林悦己 cheer / cheercheung** and indicate changes. This license covers the collection's own content; it does not relicense any linked project.

Each resource includes an upstream license link. Remotion has free-use eligibility conditions; Theatre.js core and studio use different licenses; FFmpeg licensing depends on build components. Check the upstream terms for the version, components, dependencies, model weights, and assets you actually use.

Project banners use the official social images configured on their GitHub pages; where no custom image is set, a GitHub-generated repository preview is used. Each image links to its project. [View banner sources](docs/media-sources.md). These upstream images are excluded from this collection's CC BY 4.0 license.

Project sources and license information were checked on **2026-11-02** (01–22) **2026-11-08** (23–37), and **2026-11-09** (38–49). Labels are navigation aids; the full upstream terms govern.


<a id="contributing"></a>

## 🤝 Contributing

Start by [reading the contribution guide](CONTRIBUTING.md), or [suggest a project](https://github.com/cheercheung/awesome-motion-animation/issues/new?template=resource.yml). Resource suggestions, clearer descriptions, license corrections, and translation improvements are welcome.

[Read the project data](data/projects.json) · [Read the maintenance guide](docs/maintenance.md)

<a id="acknowledgements"></a>

## 🙏 Acknowledgements

Thanks to the authors, contributors, and maintainers of every upstream project. Development, support, and licensing remain with each project.

[Remotion](https://github.com/remotion-dev/remotion), [Anime.js](https://github.com/juliangarnier/anime), [mo.js](https://github.com/mojs/mojs), [Theatre.js](https://github.com/theatre-js/theatre), [Two.js](https://github.com/jonobr1/two.js), [D3](https://github.com/d3/d3), [Three.js](https://github.com/mrdoob/three.js), [Babylon.js](https://github.com/BabylonJS/Babylon.js), [Drei](https://github.com/pmndrs/drei), [Spark](https://github.com/sparkjsdev/spark), [cables.gl](https://github.com/cables-gl/cables_electron), [Taichi](https://github.com/taichi-dev/taichi), [SPlisHSPlasH](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH), [Custom Shader Material](https://github.com/FarazzShaikh/THREE-CustomShaderMaterial), [OpenToonz](https://github.com/opentoonz/opentoonz), [Audacity](https://github.com/audacity/audacity), [Subtitle Edit](https://github.com/SubtitleEdit/subtitleedit), [Auto-Editor](https://github.com/WyattBlue/auto-editor), [RIFE](https://github.com/hzwer/ECCV2022-RIFE), [FFmpeg](https://github.com/FFmpeg/FFmpeg), [HyperFrames](https://github.com/heygen-com/hyperframes), [cinetic](https://github.com/Leonxlnx/cinetic), [Guizang Product Video Skill](https://github.com/op7418/guizang-product-video-skill), [MCP for Blender](https://github.com/ahujasid/mcp-for-blender), [Motion2MixamoRig](https://github.com/MaxLiu22/Motion2MixamoRig), [ClaudeAnimationBase](https://github.com/JohnHeibel/ClaudeAnimationBase), [OpenCut](https://github.com/OpenCut-app/OpenCut), [LosslessCut](https://github.com/mifi/lossless-cut), [video-use](https://github.com/browser-use/video-use), [Palmier Pro](https://github.com/palmier-io/palmier-pro), [liquid-glass-react](https://github.com/rdev/liquid-glass-react), [Chart.js](https://github.com/chartjs/Chart.js), [Apache ECharts](https://github.com/apache/echarts), [Matplotlib](https://github.com/matplotlib/matplotlib), [Plotly.py](https://github.com/plotly/plotly.py), [GSAP](https://github.com/greensock/GSAP), [Motion](https://github.com/motiondivision/motion), [Motion Canvas](https://github.com/motion-canvas/motion-canvas), [Manim](https://github.com/ManimCommunity/manim), [Rive Web Runtime](https://github.com/rive-app/rive-wasm), [lottie-web](https://github.com/airbnb/lottie-web), [react-spring](https://github.com/pmndrs/react-spring), [AutoAnimate](https://github.com/formkit/auto-animate), [Popmotion](https://github.com/Popmotion/popmotion), [tsParticles](https://github.com/tsparticles/tsparticles), [PixiJS](https://github.com/pixijs/pixijs), [p5.js](https://github.com/processing/p5.js).

Curated by **@林悦己 cheer**.
