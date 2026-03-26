# AICoding Project Skeleton Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Create the first documentation-only repository skeleton for AICoding, including the root project documents and seven topic-oriented docs pages.

**Architecture:** The repository is a Markdown-first knowledge index. `README.md` acts as the public entry point, `CONTRIBUTING.md` defines lightweight maintenance rules, and `docs/` contains topic pages with clear scope boundaries rather than deep resource curation.

**Tech Stack:** Markdown, filesystem structure

---

### Task 1: Create the root entry documents

**Files:**
- Create: `README.md`
- Create: `CONTRIBUTING.md`

- [ ] **Step 1: Create `README.md` with the first public project description**

```md
# AICoding

面向实验室学习与科研需求的 AI coding / vibe coding / agent 资源归集项目。

## 项目简介

AICoding 是一个公开维护、实验室优先使用的资源索引项目，聚焦 AI coding、vibe coding 与 agent 方向，系统整理论文、工具、网站、技能、评测基准与开源项目，帮助实验室成员更高效地学习、阅读、选题、实验与研究。

本项目当前主要服务于实验室师生的学习与科研需求，同时以公开仓库的方式持续积累和完善，希望逐步形成一个结构清晰、可长期维护的方向知识入口。

## 项目目标

- 帮助新成员快速入门 AI coding / vibe coding / agent
- 支持实验室成员系统追踪核心论文、工具与 benchmark
- 服务研究选题、论文阅读、实验设计与工程实现
- 沉淀实验室共享知识与可复用资源

## 面向对象

- 对 AI coding / vibe coding / agent 感兴趣的实验室新成员
- 开展相关研究的研究生、本科生和教师
- 需要查找论文、工具、benchmark 和开源项目的研究者
- 对该方向感兴趣的工程实践者

## 内容范围

- 入门资料与基础概念
- 核心论文与综述
- 工具与开发环境
- benchmark 与评测资源
- skills / workflow / 实践方法
- 网站、社区与持续跟踪入口
- 开源项目与研究代码
- 研究问题与选题方向

## 项目结构

```text
aicoding/
├── README.md
├── CONTRIBUTING.md
└── docs/
    ├── getting-started.md
    ├── papers.md
    ├── tools.md
    ├── benchmarks.md
    ├── skills.md
    ├── websites.md
    └── research-topics.md
```

## 内容导航

1. [Getting Started](docs/getting-started.md)
2. [Papers](docs/papers.md)
3. [Tools](docs/tools.md)
4. [Benchmarks](docs/benchmarks.md)
5. [Skills](docs/skills.md)
6. [Websites](docs/websites.md)
7. [Research Topics](docs/research-topics.md)

## 推荐使用方式

### 对实验室新成员

建议按以下顺序使用：

1. 先阅读 [getting-started.md](docs/getting-started.md)
2. 再浏览 [papers.md](docs/papers.md) 中的综述与基础论文
3. 然后了解 [tools.md](docs/tools.md) 和 [benchmarks.md](docs/benchmarks.md)
4. 最后结合 [research-topics.md](docs/research-topics.md) 思考潜在兴趣点

### 对正在开展研究的同学

建议重点使用：

- [papers.md](docs/papers.md)：建立论文地图
- [benchmarks.md](docs/benchmarks.md)：参考实验设计
- [tools.md](docs/tools.md)：追踪可用工具
- [research-topics.md](docs/research-topics.md)：辅助选题与收敛方向

### 对工程实践导向的同学

建议重点使用：

- [tools.md](docs/tools.md)
- [skills.md](docs/skills.md)
- [websites.md](docs/websites.md)
- [benchmarks.md](docs/benchmarks.md)

## 项目原则

- 优先服务实验室真实学习与科研需求
- 不追求资源数量最大化，优先保证质量
- 强调结构化整理，而不是简单堆链接
- 优先保留对学习、研究和实践真正有帮助的内容
- 鼓励长期维护和逐步扩展

## 收录标准

一般优先收录以下类型的内容：

- 方向代表性强的论文与综述
- 具有较高参考价值的 benchmark
- 在社区或实践中影响较大的工具和系统
- 对学习路径、研究设计或工程实践有明确帮助的资源
- 能够帮助实验室成员建立系统理解的内容

## 后续计划

- 更清晰的入门路径
- 更完整的论文分层索引
- 更系统的 benchmark 地图
- 更高质量的 skills / workflow 归集
- 更贴近实验室研究需求的选题问题库

## 如何贡献

欢迎实验室成员和外部读者共同完善本项目。提交方式和建议可参考 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 项目定位说明

本项目当前并不追求做成“全网最全资源库”，而是优先做成一个公开维护、实验室优先使用的 AI coding / vibe coding / agent 学习与科研资源索引库。

在此基础上，随着内容积累与使用反馈增加，再逐步扩展其开放性与公共价值。

## License

待补充。
```

- [ ] **Step 2: Create `CONTRIBUTING.md` with lightweight contribution rules**

```md
# Contributing

感谢你关注 AICoding 项目。

本项目当前以实验室学习与科研需求为核心，采用公开仓库方式持续维护。我们欢迎实验室成员和外部读者一起补充高质量资源、修正问题并改进组织结构。

## 欢迎贡献的内容

- 补充高质量论文、综述、benchmark、工具、网站或开源项目
- 修正失效链接、错误信息或过时内容
- 改进分类方式、页面结构和导航逻辑
- 补充更适合实验室使用的学习路径与研究主题整理

## 基本原则

- 优先质量，不追求堆砌链接数量
- 优先结构化整理，而不是简单罗列
- 尽量保留原始出处与必要背景信息
- 内容应对学习、研究或实践有明确帮助
- 新增内容应放入最合适的分类页面，避免重复

## 编辑建议

- 默认使用中文撰写，必要时保留英文术语
- 标题尽量清晰稳定，避免频繁改名
- 每次修改尽量围绕一个明确主题展开
- 如果增加新分类，请先确认现有页面是否已经可以容纳

## 提交方式

你可以通过以下方式参与：

- 提交 Issue 说明问题、建议或待补充资源
- 发起 Pull Request 提交内容修订

## 当前阶段说明

本项目仍处于第一版结构搭建阶段。现阶段更关注：

- 结构是否清晰
- 分类是否合理
- 内容是否便于长期维护

如果你发现有更适合实验室学习与科研使用的组织方式，欢迎提出建议。
```

- [ ] **Step 3: Write the files using `apply_patch`**

Create both files exactly as specified in Steps 1 and 2.

- [ ] **Step 4: Verify the root documents exist**

Run: `find . -maxdepth 1 -type f | sort`
Expected: output includes `./README.md` and `./CONTRIBUTING.md`

- [ ] **Step 5: Commit the root documents**

```bash
git add README.md CONTRIBUTING.md
git commit -m "docs: add initial project entry documents"
```

If the repository is not initialized yet, stop after `git add` is unavailable and note that commit could not run because `.git` is missing.

### Task 2: Create the topic document skeletons

**Files:**
- Create: `docs/getting-started.md`
- Create: `docs/papers.md`
- Create: `docs/tools.md`
- Create: `docs/benchmarks.md`
- Create: `docs/skills.md`
- Create: `docs/websites.md`
- Create: `docs/research-topics.md`

- [ ] **Step 1: Create `docs/getting-started.md`**

```md
# Getting Started

本页面向刚接触 AI coding / vibe coding / agent 方向的实验室成员，目标是帮助快速建立基础概念、阅读顺序和学习路径。

## 本页建议覆盖

- 什么是 AI coding
- 什么是 vibe coding
- 什么是 agent
- 这三个概念之间的关系
- 建议的入门阅读顺序
- 建议优先了解的工具与 benchmark

## 推荐组织方式

### 1. 基础概念

用简洁语言说明核心术语，避免一开始陷入过多实现细节。

### 2. 入门阅读路径

先综述，再工具，再 benchmark，再研究问题。

### 3. 实践起点

给出适合实验室新成员的最小实践入口，例如先体验哪些工具、先阅读哪些项目、先了解哪些典型任务。

## 后续可补充内容

- 面向实验室新成员的 1 周入门路径
- 推荐先读的综述与代表性论文
- 推荐先尝试的工具和公开资源页
```

- [ ] **Step 2: Create `docs/papers.md`**

```md
# Papers

本页用于整理 AI coding / vibe coding / agent 方向的重要论文，服务于论文阅读、研究追踪与选题分析。

## 本页建议覆盖

- survey / review
- foundational papers
- coding agent systems
- benchmark papers
- empirical studies
- safety / trust / evaluation

## 推荐组织方式

### 1. 综述与总览

优先整理帮助建立全局认知的综述类论文。

### 2. 基础方法与代表性系统

整理该方向的重要方法、系统框架与阶段性代表工作。

### 3. 评测与实证研究

整理 benchmark、实验研究和分析类论文，帮助理解当前研究如何被验证。

## 后续可补充内容

- 按研究主题分层的论文索引
- 每篇论文的简短摘要与价值说明
- 实验室内部推荐阅读顺序
```

- [ ] **Step 3: Create `docs/tools.md`**

```md
# Tools

本页用于整理 AI coding / vibe coding / agent 相关工具、开发环境和系统框架，服务于学习体验、实验搭建与工程实践。

## 本页建议覆盖

- AI coding tools
- IDE / editor integrations
- coding agents
- agent frameworks
- orchestration / workflow tools
- evaluation or tracing tools

## 推荐组织方式

### 1. 面向直接使用的工具

适合新成员快速上手体验的产品与环境。

### 2. 面向研究与实验的框架

适合搭建原型、运行任务和开展对比实验的系统与框架。

### 3. 面向评测和分析的辅助工具

包括日志、追踪、评测、复现实验相关工具。

## 后续可补充内容

- 工具对比表
- 使用门槛与适用场景说明
- 与 benchmark 或论文的对应关系
```

- [ ] **Step 4: Create `docs/benchmarks.md`**

```md
# Benchmarks

本页用于整理 AI coding / vibe coding / agent 方向常见 benchmark、评测任务和实验参考资源，服务于实验设计与研究比较。

## 本页建议覆盖

- SWE-bench 及相关变体
- repo-level benchmarks
- feature-level benchmarks
- code generation / repair / editing tasks
- agent evaluation settings

## 推荐组织方式

### 1. 通用 benchmark

整理社区认可度较高、引用较多的主流 benchmark。

### 2. 按任务类型划分的 benchmark

从修复、生成、编辑、仓库级任务等角度组织。

### 3. 评测注意事项

记录复现、比较、环境依赖与结果解释中的关键问题。

## 后续可补充内容

- benchmark 对比维度
- 数据规模与任务形式说明
- 适合实验室复现的优先级建议
```

- [ ] **Step 5: Create `docs/skills.md`**

```md
# Skills

本页用于整理与 AI coding / vibe coding / agent 相关的 skill、workflow、prompt 模板和实践经验。

## 本页建议覆盖

- skill 设计案例
- workflow 组织方式
- 常见 prompt pattern
- 人机协作实践经验

## 推荐组织方式

### 1. 可复用 skill

整理可迁移、可复用的 skill 结构与设计思路。

### 2. 工作流与协作方式

整理适合科研与工程任务的任务拆解、执行和复盘方式。

### 3. 实践建议

记录在真实使用中有效的 prompt、约束与习惯。

## 后续可补充内容

- 高质量开源 skills 索引
- workflow 示例
- 不同任务场景下的实践建议
```

- [ ] **Step 6: Create `docs/websites.md`**

```md
# Websites

本页用于整理与 AI coding / vibe coding / agent 相关的网站、官方页面、社区入口和持续跟踪资源。

## 本页建议覆盖

- 官方主页
- 文档站点
- 论文项目页
- 社区资源页
- 长期跟踪入口

## 推荐组织方式

### 1. 官方与文档入口

优先收录高可信度的一手资源页面。

### 2. 社区与聚合资源

收录对学习和追踪有帮助的社区整理页面。

### 3. 持续关注入口

整理值得长期订阅和定期查看的资源来源。

## 后续可补充内容

- 按用途分类的网站索引
- 高质量聚合页推荐
- 资源更新频率说明
```

- [ ] **Step 7: Create `docs/research-topics.md`**

```md
# Research Topics

本页用于整理 AI coding / vibe coding / agent 方向值得持续关注的研究问题、主题版图与潜在选题方向，重点服务实验室科研讨论。

## 本页建议覆盖

- 当前核心研究问题
- 可细分的主题方向
- 值得追踪的方法趋势
- 适合作为选题起点的问题

## 推荐组织方式

### 1. 主题地图

先建立该方向的研究版图，帮助区分工具层、系统层、评测层和方法层问题。

### 2. 关键问题

整理当前研究中尚未充分解决、值得进一步分析的问题。

### 3. 选题线索

从可做性、实验条件和研究价值角度给出选题提示。

## 后续可补充内容

- 面向实验室的研究问题清单
- 研究主题之间的关联关系
- 潜在论文方向与实验切入点
```

- [ ] **Step 8: Write the seven files using `apply_patch`**

Create all seven Markdown files exactly as specified in Steps 1 through 7.

- [ ] **Step 9: Verify the docs files exist**

Run: `find docs -maxdepth 1 -type f | sort`
Expected: output includes all seven topic files.

- [ ] **Step 10: Commit the topic documents**

```bash
git add docs/getting-started.md docs/papers.md docs/tools.md docs/benchmarks.md docs/skills.md docs/websites.md docs/research-topics.md
git commit -m "docs: add initial topic structure"
```

If the repository is not initialized yet, stop after `git add` is unavailable and note that commit could not run because `.git` is missing.

### Task 3: Verify repository consistency

**Files:**
- Modify: `README.md` if links or names are inconsistent

- [ ] **Step 1: List the repository files**

Run: `find . -maxdepth 2 -type f | sort`
Expected: output shows the root documents, the seven topic docs, and the spec/plan files under `docs/superpowers/`.

- [ ] **Step 2: Check that README links match real files**

Run: `rg 'docs/.*\\.md' README.md`
Expected: every linked path exists in the repository.

- [ ] **Step 3: Read back the final README and docs index headings**

Run: `sed -n '1,260p' README.md && for f in docs/*.md; do echo \"FILE: $f\"; sed -n '1,40p' \"$f\"; done`
Expected: headings and document purposes are consistent, with no missing sections or broken naming.

- [ ] **Step 4: Fix any mismatches if found**

If any path or heading mismatch appears, update the relevant Markdown file with `apply_patch` before proceeding.

- [ ] **Step 5: Commit consistency fixes**

```bash
git add README.md docs
git commit -m "docs: align initial repository structure"
```

If there are no fixes, skip this commit. If the repository is not initialized yet, note that commit could not run because `.git` is missing.
