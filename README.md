<div align="center">

# airbate

**AI 庄周是否梦到电子蝴蝶**

造工具 · 写文字 · 把 AI 接到真实世界

Building tools, writing words, connecting AI to the real world.

[Projects](#selected-projects--精选项目) · [About](#about--关于我) · [Contact](#contact--联系)

</div>

---

## About · 关于我

全栈开发者，写代码也写字。关注 **AI Agent、嵌入式与机器人、本地优先工具链**，喜欢把模型、软件和硬件接起来，做出能实际使用的东西。

维护微信公众号上的 AI 科普内容和 Obsidian 知识库，也写自动化工作流、折腾 WebGL 水墨效果，以及开源 AR 硬件。

I'm a full-stack developer working across **AI agents, embedded systems, robotics, and local-first tools**. My projects range from browser automation and desktop displays to robot perception and interactive graphics. I also write about AI and maintain an Obsidian knowledge base.

## Working on · 最近在做

- **AI 工作流**：用自然语言规划网页任务，让执行过程可审阅、可回放。
- **桌面硬件**：把待办、日程、Git 状态和 Agent 动态放到桌边的反射屏 / 墨水屏上。
- **应用原型**：化验单科普解释、报告趋势追踪，以及面向实际场景的 AI 工具。
- **知识与创作**：AI 科普、内容工作流、Obsidian，以及交互式水墨实验。

## Selected projects · 精选项目

### [Glance](https://github.com/airbate/Glance)

桌边的 AI 副屏：本地 daemon 将待办、日程、Git 和 Agent 状态渲染成单色帧，推送到 ESP32 反射屏或 M5Paper；配有桌面宠物和 Agent hooks。

An ambient desktop display for tasks, schedules, Git, and AI agent activity.

`ESP32` · `C++` · `Python` · `Pillow` · `RLCD / e-paper`

### [FlowPilot](https://github.com/airbate/flowpilot)

自然语言网页流程自动化：Nemotron 规划步骤，Tavily 读取网页，Playwright 执行交互。支持执行前审阅与修改、实时进度、截图回放和 CSV 导出。

A web automation copilot with reviewable plans, live execution events, and replay evidence.

`Python` · `FastAPI` · `React` · `Playwright` · `Nemotron` · `Tavily`

### [LabLens · 化验单翻译官](https://github.com/airbate/lablens)

上传化验单，识别指标并提供通俗解释、异常提示、多次报告趋势和就诊问题清单。定位为科普与辅助工具，不提供诊断。

A lab report interpreter for accessible explanations and longitudinal tracking, with explicit non-diagnostic boundaries.

`Python` · `FastAPI` · `OCR` · `SQLite`

### [LIMO Person Following](https://github.com/airbate/limo-person-following)

基于 LIMO 机器人的行人跟随系统：MobileNet-SSD 检测、IoU 追踪、深度定位和 P 控制，结合限速、超距停车与通信看门狗。

Person following on a mobile robot, connecting visual perception to motion control.

`Python` · `ROS` · `OpenCV` · `MobileNet-SSD` · `Jetson Nano`

### [水墨流韵 · Ink Flow](https://github.com/airbate/shuimo-liuyun)

交互式 WebGL 水墨模拟，把流体计算和传统水墨的视觉效果放进浏览器。

An interactive WebGL simulation of Chinese ink on rice paper.

`WebGL` · `GLSL` · `Stable Fluids` · `Canvas 2D`

### [个人博客](https://github.com/airbate/ideal-octo-adventure)

用 Astro 搭建的个人博客，记录技术探索与写作。

My personal blog, built with Astro.

`Astro` · `TypeScript` · `Tailwind CSS`

<details>
<summary>More experiments · 其他探索</summary>

- [mushen / 赛博半仙](https://github.com/airbate/mushen)：基于 Numerologist_skills 的 AI 命理应用探索。
- [Numerologist_skills](https://github.com/airbate/Numerologist_skills)（fork）：用固定步骤与计算流程约束奇门、紫微和八字排盘。
- [Project North Star](https://github.com/airbate/ProjectNorthStar)（fork）：开源 AR 头显硬件探索。
- [微信做题小程序](https://github.com/airbate/wechat-program)：基于微信平台的线上做题工具。

</details>

## Toolbox · 常用工具

| 方向 | 技术 |
| --- | --- |
| AI 与自动化 | Python · Agent workflows · Claude Code / Codex · Playwright |
| Web 与应用 | TypeScript · React · Node.js · FastAPI · Astro |
| 硬件与机器人 | C / C++ · ESP32 · ROS · OpenCV |
| 图形与知识管理 | WebGL · GLSL · Obsidian |

## Contact · 联系

[Email](mailto:qw20060930qw@163.com) · [Blog](https://ideal-octo-adventure.vercel.app) · [X / @airbate](https://x.com/airbate)

欢迎交流 AI Agent、嵌入式、机器人和创作工具。

---

<div align="center">
<sub>工具要复利，笔记要会思考，AI 干该干的活。<br>Updated · 2026-10-05</sub>
</div>
