<p align="center">
  <img src="assets/profile/avatar-badge.svg" alt="V-Reason 手绘小猫涂鸦徽章" width="58" />
</p>

<h1 align="center">V-Reason / 愚人舟</h1>

<p align="center">
  <img src="assets/profile/hero-role-strip.svg" alt="求职意向：Unity 游戏程序 · TA 技术美术" width="360" />
</p>

<p align="center">专注 Unity 2D 玩法系统、自定义渲染与交互手感，具备 C++ 图形算法与研发工具链实战经验。</p>

<p align="center"><a href="#游戏作品">游戏作品</a> &nbsp;·&nbsp; <a href="#基础知识">基础知识</a> &nbsp;·&nbsp; <a href="#ai-工具">AI 工具</a> &nbsp;·&nbsp; <a href="#技术栈与活跃度">技术栈与活跃度</a></p>

<br />

---

## 游戏作品

### 01 · 《逆流而下》 · `no-name-yet`

> 团队协作项目 · 职责：**玩法程序**（运动物理 / 交互状态）

<p align="center">
  <img src="assets/profile/nonameyet-main-screen.jpg" alt="《逆流而下》深海主菜单画面：深蓝海藻珊瑚背景中展示锚形手写书名、开始下潜按钮与海洋生物插画" width="100%" />
</p>

<p align="center">
  <img src="assets/profile/tags-nonameyet.svg" alt="浮力物理控制 · 钩爪铁链交互 · 状态机管理 · 2D 玩法手感" width="490" />
</p>

横版深海冒险闯关。负责水下持续浮力对抗下的角色运动物理、锚点钩爪与铁链交互逻辑，以及状态切换和环境障碍反馈，保障高频操作下的连续手感。

- **入口**：[GitHub 仓库](https://github.com/V-Reason/no-name-yet) &nbsp;|&nbsp; [B 站实机演示](https://www.bilibili.com/video/BV1BRT16mErS/)

<p align="center"><img src="assets/profile/nonameyet-diver-swim.webp" alt="《逆流而下》Q版粉发潜水员游泳姿态原画" height="76" />&nbsp;&nbsp;&nbsp;<img src="assets/profile/nonameyet-jellyfish.webp" alt="《逆流而下》水母敌人原画" height="76" />&nbsp;&nbsp;&nbsp;<img src="assets/profile/nonameyet-nautilus.webp" alt="《逆流而下》鹦鹉螺原画" height="68" />&nbsp;&nbsp;&nbsp;<img src="assets/profile/nonameyet-fish-school.webp" alt="《逆流而下》海洋小鱼群原画" height="72" /></p>

<br />

### 02 · 《荒原复苏指南》 · `deepseaoil`

> 团队协作项目 · 职责：**核心程序**（分层架构 / 元素连锁 / 2D 光照渲染）

<p align="center"><img src="assets/profile/deepseaoil-main-screen.jpg" alt="《荒原复苏指南》横版主视觉" width="48%" />&nbsp;<img src="assets/profile/deepseaoil-level-overview.png" alt="《荒原复苏指南》多关卡俯视总览" width="48%" /></p>

<p align="center">
  <img src="assets/profile/tags-deepseaoil.svg" alt="四层程序集架构 · 元素连锁反应 · 2D 扩散光场 · 热路径零分配" width="510" />
</p>

俯视角 2D 策略生存追逐战。主导四层程序集架构拆分、组合根调度、数据驱动地块元素连锁反应，并落地输入缓冲、受击脱困及对象池热路径优化。

渲染侧自研微型瓦片网格 `TileGridLightmap` 扩散光场，协同 `CelLit` 着色器驱动昼夜环境光照与受击反馈，兼顾手绘质感与运行效率。

- **入口**：[GitHub 仓库](https://github.com/V-Reason/deepseaoil) &nbsp;|&nbsp; [B 站实机演示](https://www.bilibili.com/video/BV1SFn16aEy6/)

<p align="center"><img src="assets/profile/deepseaoil-desert-story-cg.webp" alt="《荒原复苏指南》正面沙漠剧情 CG" width="48%" />&nbsp;<img src="assets/profile/deepseaoil-ending-cg.webp" alt="《荒原复苏指南》结局风暴与小花 CG" width="48%" /></p>

<p align="center">
  <img src="assets/profile/deepseaoil-bigbug-strip.webp" alt="《荒原复苏指南》五帧大虫子倒地动画设定条" width="380" />
</p>

<br />

---

## 基础知识

<p align="center">
  <img src="assets/profile/tags-systems.svg" alt="可复用系统架构 · C++ 图形算法 · 独立单元测试 · 渲染管线" width="494" />
</p>

| 项目 | 技术栈 | 核心职责与成果 |
| --- | --- | --- |
| [`Game-DevKits`](https://github.com/V-Reason/Game-DevKits) | `C# / .NET Standard` · Unity 适配 | 将实战玩法与工程系统抽离为引擎无关的可测范式，涵盖状态机、输入缓冲、规则表、流场寻路与资产生命周期 |
| [`CGGraphicsLab`](https://github.com/V-Reason/CGGraphicsLab) | `C++ / MFC` | 解耦 `RasterCore` 算法核与双缓冲画布，独立实现光栅化、扫描线填充、近裁剪、`1/z` 消隐、曲线曲面与凸多边形求交 |

<p align="center">
  <img src="assets/profile/cggraphics-hero.webp" alt="CGGraphicsLab 算法成果：二维光栅化、边标志填充、三维投影与 Z-buffer、Julia 集" width="760" />
</p>

<br />

---

## AI 工具

<p align="center">
  <img src="assets/profile/tags-tooling.svg" alt="多角色协作治理 · 人工审批门禁 · 自动化审计 · 知识流插件" width="494" />
</p>

| 项目 | 技术栈 | 核心职责与成果 |
| --- | --- | --- |
| [`agent-workflow-kit`](https://github.com/V-Reason/agent-workflow-kit) | `Python` | 本地多角色 AI 研发工作流，通过声明式 Profile、写边界隔离、人工审批门禁与 Git Diff 审计约束工程改动 |
| [`dsh-study-buddy`](https://github.com/V-Reason/dsh-study-buddy) | `TypeScript` | 面向技术梳理的插件与 Agent 预设，打通资料读取、自适应讲解、问答追踪与 Obsidian 归档闭环及契约校验 |

<br />

---

## 技术栈与活跃度

<p align="center"><a href="https://github.com/V-Reason?tab=repositories"><picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=cs,unity,dotnet,cpp,py,ts,git&theme=dark" /><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=cs,unity,dotnet,cpp,py,ts,git&theme=light" /><img src="https://skillicons.dev/icons?i=cs,unity,dotnet,cpp,py,ts,git&theme=light" height="36" alt="常用技术栈：C#, Unity, .NET, C++, Python, TypeScript, Git" /></picture></a></p>

<p align="center"><a href="https://github.com/V-Reason"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.ashutosh-dwivedi0710.workers.dev/graph?username=V-Reason&bg_color=2b2a28&color=f7f0e7&title_color=d0b185&line=85c6c8&point=da684c&area=true&area_color=85c6c8&radius=6&hide_border=true&custom_title=Recent%20Activity" /><source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.ashutosh-dwivedi0710.workers.dev/graph?username=V-Reason&bg_color=f7f0e7&color=343433&title_color=5f5a52&line=5b9a9d&point=da684c&area=true&area_color=85c6c8&radius=6&hide_border=true&custom_title=Recent%20Activity" /><img src="https://github-readme-activity-graph.ashutosh-dwivedi0710.workers.dev/graph?username=V-Reason&bg_color=f7f0e7&color=343433&title_color=5f5a52&line=5b9a9d&point=da684c&area=true&area_color=85c6c8&radius=6&hide_border=true&custom_title=Recent%20Activity" alt="V-Reason GitHub 提交活跃曲线（点击查看主页实时提交记录）" /></picture></a></p>

<p align="center"><sub><code>C# / Unity</code> · <code>C++ / MFC</code> · <code>Python</code> · <code>TypeScript</code> &nbsp;|&nbsp; <a href="https://github.com/V-Reason">查看实时提交记录 →</a></sub></p>

<br />

---

<p align="center">
  <img src="assets/profile/avatar-badge.svg" alt="V-Reason 手绘小猫签名徽章" width="44" />
</p>

<p align="center">
  <img src="assets/profile/footer-quote.svg" alt="画面让玩家心动，音乐让玩家沉浸，玩法让玩家留下，剧情让玩家记住。—— V-Reason / 愚人舟" width="480" />
</p>

<p align="center"><a href="https://github.com/V-Reason?tab=repositories">公开仓库</a> &nbsp;·&nbsp; <a href="https://www.bilibili.com/video/BV1BRT16mErS/">《逆流而下》实机</a> &nbsp;·&nbsp; <a href="https://www.bilibili.com/video/BV1SFn16aEy6/">《荒原复苏指南》实机</a> &nbsp;·&nbsp; <a href="mailto:vreason@qq.com">vreason@qq.com</a></p>
