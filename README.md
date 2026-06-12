[README.md](https://github.com/user-attachments/files/28868712/README.md)
# Portfolio Studio Site Skill

`portfolio-studio-site` 是一个用于设计、规划、构建和评审个人/工作室作品网站的 Codex Skill。它帮助 Codex 把一个人、工作室、一组作品、案例研究、服务能力或品牌方向，转化成清晰、好看、可维护、可上线的网站方案。

这个 Skill 适合用于：

- 个人作品集网站
- 工作室或创意团队官网
- 设计师、摄影师、开发者、艺术家个人主页
- 产品设计、品牌设计、技术项目的案例研究站
- 图片、影像、艺术项目的视觉档案站
- 独立顾问、创作者、服务型工作室的获客落地页
- 互动型、实验型、网站本身即作品的创意网站

## 它能做什么

这个 Skill 会从三个维度协助网站设计与实现。

**产品层面**

- 判断网站的核心目标：展示、获客、求职、销售、归档、传播或实验表达
- 明确目标受众和访问者路径
- 设计首页、作品列表、项目详情、关于、服务、联系等信息架构
- 建立项目内容模型，方便后续维护和扩展
- 规划信任要素和转化路径，例如客户、奖项、媒体、推荐语、预约入口

**设计层面**

- 根据个人或工作室气质确定视觉方向
- 设计第一屏信号，让访问者快速理解“这是谁、做什么、为什么值得看”
- 组织作品展示密度、图片节奏、排版、留白和动效
- 避免模板感、过度装饰和无意义炫技
- 强调移动端体验、图片比例、文本溢出和响应式细节

**技术层面**

- 推荐适合的实现方式：Astro、Next.js、Nuxt、SvelteKit、Eleventy 或纯静态页面
- 规划 Markdown、MDX、JSON、CMS 等内容结构
- 关注图片优化、响应式图片、懒加载、视频 poster、字体加载和性能
- 检查 SEO、Open Graph、语义 HTML、可访问性和部署方式
- 要求在交付前进行桌面端和移动端浏览器视觉 QA

## 使用方式

在 Codex 中可以这样调用：

```text
Use $portfolio-studio-site to design a website for my photography studio.
```

也可以用于更具体的任务：

```text
Use $portfolio-studio-site to plan a personal portfolio for a product designer.
```

```text
Use $portfolio-studio-site to review this studio website and identify clarity, design, performance, and conversion issues.
```

```text
Use $portfolio-studio-site to build a minimal portfolio site from these project images and descriptions.
```

## 典型输出

当用于设计网站时，它通常会输出：

- 站点类型判断
- 目标用户与核心目标
- 信息架构
- 首页结构
- 项目详情页结构
- 内容模型
- 视觉方向
- 技术实现建议
- SEO、性能、移动端和可访问性检查点

当用于构建网站时，它会指导 Codex：

- 选择或遵循现有前端技术栈
- 创建可维护的项目数据结构
- 实现首页、作品列表、详情页和联系入口
- 优化图片、响应式布局和移动端体验
- 启动本地服务并通过浏览器截图进行验证

当用于评审网站时，它会优先指出影响以下方面的问题：

- 首屏清晰度
- 作品可信度
- 视觉气质匹配度
- 转化路径
- 响应式体验
- 图片和性能
- 可访问性
- 内容维护成本

## 文件结构

```text
portfolio-studio-site/
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
└── references/
    └── patterns.md
```

`SKILL.md` 是 Codex 实际加载的核心操作手册。  
`references/patterns.md` 包含网站类型、信息架构、首页结构、项目详情页、内容模型和技术选型参考。  
`agents/openai.yaml` 提供 Codex UI 中展示这个 Skill 所需的名称、描述和默认提示词。

## 设计原则

这个 Skill 的核心判断是：

> 先让作品、个人或工作室变得清楚可信，再让网站变得聪明好看。

作品网站不只是视觉展示，而是一个帮助访问者做判断的界面。好的网站应该让人快速知道你是谁、做什么、有什么代表作品、为什么可信，以及下一步该如何联系或合作。
