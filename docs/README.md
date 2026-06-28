# 作品集项目入口

更新时间：2026-06-28

## 当前目标

搭建个人作品集网站，用于两个场景：

1. AI 产品经理、AI Agent 产品、RAG 应用产品方向求职。
2. 海外人工智能研究生申请。

视觉参考站为 `https://steven.com/`。设计目标是高度贴近参考站的字体气质、页面排版、菜单结构、页面切换、UI 动效和 3D/场景化视觉语言，同时把内容替换为童加锐的 AI 项目、技术经历和申请叙事。

## 当前阶段

阶段：阶段 0 - 文档与架构基线

状态：进行中

本阶段只建立中文文档基线，不进入代码实现。确认后的首阶段方案是：

- 写清目标站拆解。
- 写清个人内容到站点结构的映射。
- 写清技术架构和目录规划。
- 写清阶段路线、验收规则和 Git 节奏。
- 每个阶段完成后提交一次 Git，提交信息说明当前阶段完成内容。

## 重要决策

- 主叙事：AI PM 求职和海外 AI 研究生申请均衡。
- 双语范围：项目介绍双语，其余界面尽量保留 steven.com 的英文气质。
- 第一阶段交付：文档与架构基线，不先写页面代码。
- 工作目录：当前实际仓库为 `/Users/tongjiarui/Documents/作品集`。
- 旧记忆中的 `/Users/tongjiarui/Documents/作品集/.worktrees/portfolio-site` 当前不存在，本轮从当前仓库空白状态重启。

## 新会话接手顺序

新会话开始任何代码编写前，必须先读：

1. `docs/README.md`
2. `docs/开发阶段记录.md`
3. `docs/目标站拆解.md`
4. `docs/信息架构.md`
5. `docs/技术方案.md`

如果要开始某个模块实现，需要先确认 `docs/开发阶段记录.md` 中上一阶段已经验收通过，并按该文档的下一阶段计划推进。

## 文档索引

- `docs/目标站拆解.md`：steven.com 页面、组件、字体、动效和可复刻规则。
- `docs/信息架构.md`：个人内容源、站点页面结构、项目双语内容策略。
- `docs/技术方案.md`：推荐技术栈、目录结构、动效实现边界、测试和验收方式。
- `docs/开发阶段记录.md`：阶段状态、验收结果、下一步计划和提交规则。

## 内容来源

主要内容来源：

- `/Users/tongjiarui/Documents/其他/简历`
- `/Users/tongjiarui/Documents/基于RAG的多模态电商智能导购AI Agent`
- `/Users/tongjiarui/Documents/竞品分析Agent协作系统`
- GitHub：`https://github.com/Yute-Tjr`

已读取到的核心内容：

- 简历：AI 产品经理方向，计算机科学与技术本科，GPA 4.35/5，IELTS 7.5。
- 项目 1：基于 RAG 的多模态电商智能导购 AI Agent。
- 项目 2：VibeCoding 需求验证 Skill，来自竞品分析 Agent 协作系统方向重构。
- 项目 3：工业图像目标检测模型选型与 YOLO11-OBB 评测。
- GitHub：公开仓库包括 `Shopping_Guidance_Agent`、`Self_Website`、`CHD_data_analysis`、`card_trade_system`、`Motion_planning_quadcopter`、`AirSim`，另有 `Object_detection_YOLO11_OBB` 和 `CIFS_DEMO` 显示为私有仓库。

## 约束

- 文档使用中文编写，放在 `./docs`。
- 项目说明需要中英双语，但导航、按钮和短界面文案优先保持英文。
- 不使用通用蓝紫渐变、emoji 图标、模板化圆角卡片风格。
- 不直接复用未授权的第三方源代码、模型、图片或商业素材；实现时以视觉结构、动效逻辑和交互节奏复刻为准，项目资产使用自有、生成或可授权资源。
- 每完成一个阶段任务都要 Git 提交。
