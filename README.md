<h1 align="center">hegel.skill</h1>

<p align="center">黑格尔 · G. W. F. Hegel</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“真理是全体。”<br>— 黑格尔 · <a href="https://www.marxists.org/deutsch/philosophie/hegel/phaenom/vorrede.htm">《精神现象学》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将内在批判、规定性与承认问题整理为思想分析 Skill，让 AI 从一个立场自己的标准出发，追踪它如何在实践中暴露不足，而不是套用“正反合”。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 公司说人人自主，却要求每个决定都先批准，这怎么分析？

> 先明确“自主”在这家公司自己的规则里意味着什么，再看批准制度怎样实现或削弱它。重点是内部标准与实践之间的关系，不是看到两句相反的话就宣布必有某种综合。

### 2. 双方各退一步，就是辩证地解决问题了吗？

> 折中是谈判结果，尚未说明原有问题如何改变。需要指出双方各自依赖什么、冲突由何而来，以及新安排保留或克服了哪些具体限制。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 内在批判 | 比较一个立场宣称的标准与它实际要求的做法。 |
| 规定性 | 区分确定的概念内容与空泛的对立标签。 |
| 承认与制度 | 检查主观确信如何进入相互关系和制度条件。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/hegel-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `hegel-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/hegel-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用黑格尔的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《精神现象学》相关选段；《哲学全书》第一部逻辑学与《法哲学原理》的已定位选段。开篇引文另核《精神现象学》序言。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://www.marxists.org/deutsch/philosophie/hegel/phaenom/vorrede.htm">《精神现象学》</a>，序言，第 20 段。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
