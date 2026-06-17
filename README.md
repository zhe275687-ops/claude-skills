# Claude Code 技能库

> 共 **30+** 个技能，分为 8 大类

---

## 📚 目录

| # | 分类 | 技能数 | 说明 |
|---|------|--------|------|
| 1 | [🎓 雅思备考](#1-雅思备考) | 8 | IELTS 全科 AI 教练系统 |
| 2 | [📄 文档处理](#2-文档处理) | 6 | Word/PDF/PPT/Excel/Markdown/OCR |
| 3 | [🎨 设计与创意](#3-设计与创意) | 6 | 视觉设计、算法艺术、品牌 |
| 4 | [🛠 开发工具](#4-开发工具) | 4 | Skill 创建、MCP、Web 测试 |
| 5 | [🤖 Claude 相关](#5-claude-相关) | 2 | API 参考、使用指南 |
| 6 | [🔄 工作流](#6-工作流) | 7 | Code Review、PR、安全检查 |
| 7 | [⚙️ 配置与工具](#7-配置与工具) | 6 | 配置、快捷键、文件管理 |
| 8 | [📝 协作与研究](#8-协作与研究) | 3 | 文档协作、内部沟通、深度研究 |

---

## 1. 🎓 雅思备考

IELTS 全科 AI 教练系统，V3 架构。

| 技能 | 触发方式 | 功能 |
|------|----------|------|
| **ielts** | `/ielts` | 入口 + 进度追踪 + 复盘 + 规划 |
| **ielts-dashboard** | `/ielts-dashboard` | 可视化仪表板：趋势图、雷达图、热力图、错题分布 |
| **ielts-diagnose** | `/ielts-diagnose` | 成绩诊断 + 弱项定位 + 个性化备考计划 |
| **ielts-listening** | `/ielts-listening` | 听力错题分析 + 精听任务 + 题型错误追踪 |
| **ielts-reading** | `/ielts-reading` | 精读教练：同义替换 + T/F/NG 逻辑 + 段落结构 |
| **ielts-speaking** | `/ielts-speaking` | 口语素材工厂：话题分组 + 万能故事 + Part 3 预测 |
| **ielts-vocab** | `/ielts-vocab` | 词汇训练：间隔重复 + 同义替换 + 搭配练习 |
| **ielts-writing** | `/ielts-writing` | 写作批改：四维评分 + 句子标注 + 改写对比 |

**数据存储：** `~/.ielts/`（本地永久保存）

---

## 2. 📄 文档处理

处理各种文档格式的读写操作。

| 技能 | 触发方式 | 功能 |
|------|----------|------|
| **docx** | 提及 `.docx` / Word | 创建、读取、编辑 Word 文档 |
| **pdf** | 提及 `.pdf` | PDF 读写、合并、拆分、OCR、表单填写 |
| **pptx** | 提及 `.pptx` / 演示文稿 | PowerPoint 创建、编辑、模板 |
| **xlsx** | 提及 `.xlsx` / 表格 | Excel 读写、公式、图表、数据清洗 |
| **markdown-tools** | MD 转换/TOC/合并 | Markdown ↔ HTML、目录生成、文件合并 |
| **image-ocr** | 图片文字提取 | Tesseract OCR，中英双语，批量模式 |

---

## 3. 🎨 设计与创意

视觉设计和创意产出。

| 技能 | 触发方式 | 功能 |
|------|----------|------|
| **algorithmic-art** | 算法艺术/生成艺术 | p5.js 创作：流场、粒子系统、种子随机 |
| **canvas-design** | 海报/设计/静态作品 | PNG/PDF 视觉设计，原创设计理念 |
| **frontend-design** | 前端设计指导 | 美学方向、排版、避免模板化 |
| **theme-factory** | 主题/样式 | 10 套预设主题 + 即时生成，用于幻灯片/文档/网页 |
| **brand-guidelines** | 品牌/Anthropic 风格 | Anthropic 官方品牌色和字体 |
| **slack-gif-creator** | Slack GIF | 动画 GIF 创作，优化 Slack 约束 |

---

## 4. 🛠 开发工具

面向开发者的构建和测试工具。

| 技能 | 触发方式 | 功能 |
|------|----------|------|
| **skill-creator** | 创建/优化 skill | Skill 全生命周期：创建、编辑、评估、基准测试 |
| **mcp-builder** | 构建 MCP 服务器 | MCP 服务器开发指南（Python FastMCP / Node SDK） |
| **web-artifacts-builder** | 复杂 Web 组件 | React + Tailwind + shadcn/ui 多组件 Artifact |
| **webapp-testing** | 测试 Web 应用 | Playwright 测试：截图、日志、UI 验证 |

---

## 5. 🤖 Claude 相关

Claude 模型和工具参考。

| 技能 | 触发方式 | 功能 |
|------|----------|------|
| **claude-api** | Claude/Anthropic API | 模型 ID、定价、参数、流式、Token 计数 |
| **claude-code-guide** | Claude Code 使用问题 | CLI 功能、Hooks、MCP、IDE 集成 |

---

## 6. 🔄 工作流

代码质量和工作流自动化。

| 技能 | 触发方式 | 功能 |
|------|----------|------|
| **code-review** | `/code-review` | Diff 审查：正确性 Bug + 复用/简化/效率 |
| **simplify** | `/simplify` | 代码简化：重构、去重、优化（只看质量） |
| **security-review** | `/security-review` | 安全审查：当前分支变更 |
| **verify** | `/verify` | 验证改动：运行应用确认功能正常 |
| **review** | `/review` | PR 审查 |
| **loop** | `/loop` | 定时循环执行命令 |
| **run** | `/run` | 启动项目应用查看效果 |

---

## 7. ⚙️ 配置与工具

系统配置和实用工具。

| 技能 | 触发方式 | 功能 |
|------|----------|------|
| **update-config** | 配置/权限/环境变量 | settings.json 管理：权限、Hook、环境变量 |
| **keybindings-help** | 快捷键/键位绑定 | 自定义键盘快捷键 |
| **fewer-permission-prompts** | 减少权限弹窗 | 扫描历史 → 自动生成 allowlist |
| **file-organizer** | 整理文件夹 | 按类型/日期/名称自动分类文件 |
| **image-batch** | 批量图片处理 | 缩放、压缩、格式转换、水印、重命名 |
| **init** | `/init` | 初始化 CLAUDE.md 项目文档 |

---

## 8. 📝 协作与研究

文档协作和深度研究。

| 技能 | 触发方式 | 功能 |
|------|----------|------|
| **doc-coauthoring** | 写文档/提案/规范 | 结构化文档协作工作流 |
| **internal-comms** | 内部沟通 | 状态报告、3P 更新、Newsletter、事故报告 |
| **deep-research** | `/deep-research` | 多源深度研究：搜索 → 验证 → 综合报告 |

---

## 技能总数

| 分类 | 数量 |
|------|------|
| 雅思备考 | 8 |
| 文档处理 | 6 |
| 设计与创意 | 6 |
| 开发工具 | 4 |
| Claude 相关 | 2 |
| 工作流 | 7 |
| 配置与工具 | 6 |
| 协作与研究 | 3 |
| **合计** | **42** |

---

> **触发方式说明：**
> - `/xxx` — 斜杠命令直接调用
> - 提及关键词 — 对话中自然触发
> - 数据全部本地存储，永久保存
