---
name: "Maybe · 未定设计室"
description: "一个允许没想清楚、让意图边做边变的轻松创作现场。"
colors:
  paper: "#f8f7f2"
  white: "#fffefb"
  ink: "#39313d"
  muted: "#77716f"
  line: "#e9e5dc"
  purple: "#5b426b"
  lavender: "#eee6f5"
  orange: "#ee7854"
  yellow: "#f8df86"
  focus-ring: "#a385b8"
  secondary-ink: "#756b74"
  metadata-ink: "#776c79"
  button-text: "#ffffff"
  poster-paper: "#f3e7cd"
  poster-burgundy: "#8b3d3f"
  poster-terracotta: "#c76346"
  poster-coral: "#ef7752"
  poster-indigo: "#413b65"
  poster-cream: "#fae6b8"
  poster-sage: "#d4e3cb"
  poster-teal: "#315c61"
  poster-sun: "#f4da7c"
typography:
  brand:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "37px"
    fontWeight: 600
    lineHeight: 0.9
    letterSpacing: "-1.4px"
  display:
    fontFamily: "\"PingFang SC\", \"Microsoft YaHei\", sans-serif"
    fontSize: "29px"
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: "-1px"
  headline:
    fontFamily: "\"PingFang SC\", \"Microsoft YaHei\", sans-serif"
    fontSize: "26px"
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: "-1px"
  companion-title:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "21px"
    fontWeight: 600
    lineHeight: 1.4
  body:
    fontFamily: "\"PingFang SC\", \"Microsoft YaHei\", sans-serif"
    fontSize: "14px"
    lineHeight: 1.6
  conversation:
    fontFamily: "\"PingFang SC\", \"Microsoft YaHei\", sans-serif"
    fontSize: "13px"
    lineHeight: 1.95
  label:
    fontFamily: "\"PingFang SC\", \"Microsoft YaHei\", sans-serif"
    fontSize: "10px"
  question:
    fontFamily: "Fraunces, Georgia, serif"
    fontSize: "63px"
    fontWeight: 600
    lineHeight: 0.9
rounded:
  paper: "2px"
  tag: "4px"
  path: "5px"
  play: "6px"
  suggestion: "7px"
  icon: "8px"
  soft: "9px"
  primary: "10px"
  surface: "12px"
  composer: "13px"
  companion: "14px"
  dialog: "16px"
  round: "50%"
spacing:
  micro: "4px"
  tight: "6px"
  small: "8px"
  control: "10px"
  inset: "12px"
  related: "16px"
  section: "20px"
  panel: "24px"
  desktop-gutter: "34px"
  wide-gutter: "60px"
components:
  button-primary:
    backgroundColor: "{colors.purple}"
    textColor: "{colors.button-text}"
    rounded: "{rounded.primary}"
    padding: "11px 17px"
  button-soft:
    backgroundColor: "{colors.lavender}"
    textColor: "{colors.purple}"
    rounded: "{rounded.soft}"
    padding: "11px 17px"
  button-quiet:
    padding: "8px"
  prompt-form:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.composer}"
    padding: "12px 12px 9px"
  view-tab-selected:
    textColor: "{colors.purple}"
  suggestion-chip:
    rounded: "{rounded.suggestion}"
    padding: "6px 9px"
  poster-card:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.paper}"
    padding: "9px 9px 12px"
  companion-panel:
    backgroundColor: "{colors.white}"
    width: "348px"
  journey-entry:
    padding: "0 0 27px 30px"
---

# Design System: Maybe · 未定设计室

## Overview

**Creative North Star: "允许拐弯的工作桌"**

一张奶油色的创作桌，容纳还没命名的想法、斜放的矢量海报、问号批注和会犹豫的伙伴。轻松、愉悦、开放与夸张来自真实的形状、排版和反馈状态；操作区保持安定，作品区负责冒险。

这份记录以 dist/index.html、dist/styles.css 的最终级联和 dist/app.js 为依据，是已经实现的设计世界。Maybe · 未定设计室是临时名字；Cue / Muse 的具体产品尚未确认，因此这里不主张任何产品的精确复刻。对话来自本地规则和脚本，作品来自矢量模板，界面始终保留“暂时理解”的语气。

**Key Characteristics:**

- 奶油底与画纸白分出工作桌、作品和对话的层次。
- 李子紫控制操作与选择，珊瑚、鼠尾草和浅黄在作品里展开。
- 三个略微倾斜的方向、夸张问号与一枚小笑脸构成可辨认的视觉语言。
- 偏爱、否定、犹豫、跑偏、纠正与回到旧念头都拥有可见状态。

## Colors

配色像纸上拼贴：暖中性色搭建安定背景，偏灰的李子紫负责操作，珊瑚、鼠尾草和晒暖的浅黄负责作品的情绪。前置令牌是颜色值的规范来源；这里说明用途。

### Primary

- **深李子紫 / purple**：导出、发送、选择徽章、选中导航和关键文字。
- **浅丁香紫 / lavender**：柔和次级按钮与选中侧栏底色。
- **紫藤焦点 / focus-ring**：键盘焦点的清晰外轮廓。

### Secondary

- **珊瑚标点 / orange**：品牌问号与中文标题句号的短促强调。
- **旧刊酒红、陶土拱门、喧闹珊瑚、海报深靛**：初始复古作品的文字、几何和强对比色块。它们属于作品，不替代全局操作紫。

### Tertiary

- **伙伴蛋黄 / yellow**：小未的不规则圆角笑脸。
- **夏日鼠尾草、深叶青、夏日浅黄、晒暖的奶黄**：初始第三方向与第二方向细节的夏日感。

### Neutral

- **暖奶油画布 / paper**：工作桌及轨迹背景。
- **画纸白 / white**：顶栏、伙伴面板、海报衬纸和输入面板。
- **梅灰正文 / ink**：主要中文内容；**暖灰次级字 / muted**：辅助说明。
- **纸边灰 / line**：区域分界线；**纸面注释灰紫 / secondary-ink** 与 **对话元信息灰紫 / metadata-ink**：最终级联中加深的细小文字。
- **旧杂志纸 / poster-paper**：初始 A 方向的画面底色。**按钮纯白 / button-text**：深紫按钮内的字和图标。

**The Stable Desk Rule.** 工作区的奶油与李子紫保持稳定；风格与配色变化主要发生在作品中。

前置令牌记录初始作品的真实三色组合，不将每个生成主题都扩张成 UI 令牌。包豪斯、梦幻、安静、自然及暖色变体的作品配色以 app.js 的主题表为准。保留配色时沿用被选作品的实际色组；没有选择时以 A 方向为依据。

## Typography

**Display Font:** 自托管 Fraunces（dist/assets/fraunces.ttf），Georgia、serif 回退。仅声明常规体、600 字重，font-display 为 swap。

**Body Font:** PingFang SC、Microsoft YaHei、sans-serif；没有远程中文字体依赖。

**Character:** 圆润、有表情的衬线品牌和问号，配清楚、安静的中文阅读层。作品是独立排版空间：SVG 使用 Georgia 衬线以及 Arial、PingFang SC 无衬线，并非自动继承 UI 的 Fraunces。

### Hierarchy

- **品牌**：默认 37px；760px 以下 33px，390px 以下 30px。紧字距形成一个完整字标。
- **画布标题**：默认 29px，1550px 起 36px，1190px 以下 25px，950px 以下 23px，760px 以下回到 27px，390px 以下 24px。
- **轨迹标题**：默认 26px；760px 以下 23px。
- **伙伴标题**：默认 21px；950px 以下 19px。
- **正文**：基础 14px / 1.6；对话最终为 13px / 1.95。对话在 1550px 的早期规则虽声明 14px，但最终无条件覆盖为 13px，应以级联结果为准。
- **标签**：主要为 9–13px，密度较高。小文字使用最终加深的颜色；不要为追求轻盈继续减淡。
- **问号**：画布 63px，950px 以下 55px；对话内 47px。它是语言姿态，不替代可读说明。

**The Two Voices Rule.** Fraunces 承担品牌和问号的表情；中文系统字体承担阅读和决策。

## Layout

桌面是三栏工作桌：顶部 82px，工作区最大宽度 2000px，侧栏 68px、中间弹性画布、右侧伙伴 348px。中间列使用 minmax(0, 1fr)，避免长输入撑开布局。伙伴固定在视口顶部，按视口高度减顶栏高度设置、最小高度 650px；对话区独立滚动。

画布默认内边距为上 30px、左右 34px、下 24px。浅点阵每 16px 重复。海报保持三列，默认间隔 20px；每张作品为 3:4，衬纸和标题留在画幅外。间距来自真实样式，不宣称一个不存在的统一倍数系统。

| 条件 | 已实现变化 |
| --- | --- |
| ≥1550px | 76px 侧栏、380px 伙伴；画布左右留白 60px；作品最大宽度 940px、间隔 34px。 |
| ≤1190px | 56px 侧栏、310px 伙伴；画布左右 24px；隐藏中文副标和保存文字。 |
| ≤950px | 52px 侧栏、280px 伙伴；画布左右 20px；隐藏项目名称、海报圆形箭头和桌面圆注；轨迹条允许换行。 |
| ≤760px | 70px 顶栏；侧栏隐藏；画布与伙伴纵向排列；伙伴取消粘性与最小高度；对话区域 240–360px，仍可滚动；画布左右 24px。 |
| ≤390px | 画布左右 18px；更小字标、更紧海报间隔与衬纸。 |

移动端保留三种方向的同时比较；不是自动改成单张轮播。最终小屏修正给圆注固定宽度、标题 min-width:0、轨迹标签换行空间，并将海报标题和注释恢复为 10px。输入、消息和轨迹说明允许任意长词换行。继续新增内容时应复查真实小屏，不能仅依靠隐藏溢出。

## Elevation & Depth

纸张轻微抬起，区域主要依靠底色和细线分开。倾斜、纵向错位、薄衬纸和小阴影共同传达“随手放在桌上”的感觉。操作不依赖玻璃、强模糊或大范围渐变。

### Shadow Vocabulary

- **海报纸张**：`0 5px 16px #50413113`，低而轻，持续存在。
- **输入聚焦**：`0 2px 14px #694b7f13`，随 focus-within 出现，并加深边框。
- **状态提示**：`0 8px 30px #38243b22`，将短暂反馈从桌面抬起。
- **重置对话框**：`0 20px 80px #352c3a22`；背景罩为半透明梅灰。

**The Paper Has Weight Rule.** 阴影只表达纸张、聚焦输入和浮层的层次，不给所有容器加浮起效果。

## Shapes

海报衬纸接近方角（2px）；日常操作从 6–13px 的温和圆角展开；对话框为 16px。主按钮不是胶囊；小发送、箭头和计数点使用圆形。用户气泡右上角收紧，形成轻微方向性。伙伴脸使用交替 14px / 17px 圆角并轻斜，避免标准圆头像的严肃感。

三张海报依次倾斜 -4°、2°、-2.5°，顶端分别错位 13px、0、23px；问号批注约 -4°，圆形旁注约 7°。UI 图标是圆端点、圆连接的线描，常用 18px、1.7px 描边。作品 SVG 明确取消从按钮图标继承的描边；各路径的描边独立声明。

## Components

### Buttons

主动作是紧凑、沉稳的李子紫按钮，承载“带走灵感”和确认重置；次级软按钮用丁香底。文字按钮承载轻量操作。默认 hover 亮度为 0.97；按下向下 1px；禁用时透明度 0.5 并显示等待指针。所有按钮和链接保留 3px 紫藤焦点圈，外移 4px。

### Inputs / Fields

输入是画纸白的小便签，13px 圆角，细紫灰描边；focus-within 加深边框并出现轻阴影。文本域本身不画第二层 outline，因此不能移除容器的焦点变化。允许调整高度，最长 240 字；Enter 发送，Shift+Enter 换行，中文输入法组合输入不误发。空输入会聚焦字段并给出鼓励性的状态提示，没有假装校验成功。

### Navigation

顶部两页签使用文字、底边 2px 线和选中紫共同表达状态；页签有 tablist、tab、tabpanel 关系，左右方向键切换并聚焦。桌面侧栏用浅丁香块显示当前视图，移动端保留页签、隐藏侧栏。轨迹计数同步呈现在导航中。

### Chips

建议是淡紫底、细边框的小圆角按钮；对话状态标签更小、更实。轨迹条的已出现念头是实底，尚待决定的最后一项是虚线描边。标签不等同于确定性评分，也不使用进度百分比暗示系统已理解。

### Cards / Poster Choices

作品是可按的整张纸，每张有 A/B/C 标记、标题和旁注。hover 上移 8px 并扶正；按下缩至 0.98。选中时显示紫色文字徽章、勾选图标和 2px 外轮廓，aria-pressed 同步。默认导出当前选择，未选时导出 A，并用状态提示解释。导出的 SVG 保留可编辑矢量结构，字体由查看设备解析。

### Companion / Conversation

小未的蛋黄笑脸、Fraunces 名字和状态句共同构成伙伴。助手文字不装进大气泡；用户内容有浅灰圆角底。问号和语气标签对应“拿不准”“暂时理解”等脚本状态。对话使用 polite live region。850ms 的脚本等待有状态文案、跳动点与相关操作禁用；画板同时标记 aria-busy。

### Intention Journey

用细竖线、浅紫节点、时间、事件标题和解释串联变化。旧节点允许恢复，恢复产生新记录并保留其他尝试。系统判断“方向变了”后让用户区分改主意与纠正误解；不能自动把两者合并。轨迹上限 40 条、对话上限 70 条，当前状态保存在本浏览器。

**The Provisional Means Visible Rule.** 用待定虚线、文字标签和可恢复轨迹表达暂时理解，不能把系统猜测画成用户已确认的结论。

### Motion, Status & Accessibility

动作轻而有弹性：颜色 180ms，普通位移 200ms，纸张扶正 400ms；共用 cubic-bezier(.16,1,.3,1)。新草案以 700ms 入场，第二、三张分别延迟 90ms 和 180ms；消息 400ms 入场，等待点 1s 循环。prefers-reduced-motion:reduce 取消动画、过渡和滚动动效，保留静态状态表达。

用原生按钮、带标签的输入、图像名称、aria-pressed、aria-selected、aria-expanded、aria-busy 和 role=status 支撑可操作性。重置使用原生 modal dialog，并明确说明会清空记录；导出及本地保存异常使用文字反馈。装饰 SVG、问号和笑脸对辅助技术隐藏，作品 SVG 保留作品名称。这是已实现能力的记录，不是完整无障碍合规认证；新增操作需要继续检查触达尺寸、焦点顺序与对比度。

## Do's and Don'ts

### Do:

- Do 保持控制区稳定，让颜色、构图和轻微倾斜在作品区承担夸张。
- Do 使用文字、勾选徽章和轮廓共同表达选中；保留键盘焦点和辅助技术标签。
- Do 让问号、微笑和文案对应真实交互状态，而不是无意义的装饰。
- Do 保留低动态偏好、移动端换行和长中文输入的布局余量。
- Do 通过“你改变了想法”与“系统理解错了”的不同记录尊重用户解释。
- Do 在保留配色请求后沿用所选方向的实际三色组合，继续变换构图。

### Don't:

- Don't 将 Cue / Muse 当成已确认的视觉规格，也不要宣称精确还原。
- Don't 用真实 AI、模型理解或研究结论的口吻描述当前规则演示。
- Don't 把作品 SVG 的填充与描边继承为界面图标样式；海报根 SVG 取消继承描边，内部路径按模板声明。
- Don't 把旧轨迹隐藏成一次成功路径；恢复旧念头后仍保留后来的尝试。
- Don't 给所有海报套同一种圆角卡片；保留薄纸边、画幅与轻微错位。
- Don't 将低动态关闭等同于删掉状态反馈；仍然更新文本、选择、禁用和轨迹。
