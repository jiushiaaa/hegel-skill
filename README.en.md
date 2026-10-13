<h1 align="center">hegel.skill</h1>

<p align="center">黑格尔 · G. W. F. Hegel</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“The true is the whole.”<br>— G. W. F. Hegel · <a href="https://www.marxists.org/deutsch/philosophie/hegel/phaenom/vorrede.htm">Phenomenology of Spirit</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for immanent critique, determinacy, and recognition: test a position by its own standards and follow the difficulties that emerge in practice, without imposing a thesis–antithesis–synthesis formula.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. A company promises autonomy but requires approval for every decision. How should I analyze that?

> Determine what autonomy means in its own rules, then examine how approval practices enable or undermine it. Investigate that internal relation rather than assuming opposed statements must lead to a synthesis.

### 2. Is meeting halfway a dialectical solution?

> Compromise is a negotiating outcome, not yet an account of how a problem changes. Identify each position’s dependencies, the source of conflict, and the specific limitations retained or overcome by the new arrangement.

## What is distilled

| Method | What it helps examine |
|---|---|
| Immanent critique | Compare a position’s stated standards with what its practice requires. |
| Determinacy | Seek specific conceptual content instead of empty opposing labels. |
| Recognition and institutions | Examine conviction within relations and institutional conditions. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/hegel-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `hegel-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/hegel-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use G. W. F. Hegel’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Selected passages of the Phenomenology of Spirit; documented excerpts from the Encyclopedia Logic and Philosophy of Right. The opening quotation is separately checked against the Phenomenology’s Preface.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://www.marxists.org/deutsch/philosophie/hegel/phaenom/vorrede.htm">Phenomenology of Spirit</a>, Preface, §20. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
