# obhrm-brain-trust

**OBHRM 智囊团** · v1.0.3 · `team`

> An OBHRM knowledge team linking a **12-chapter organization-behavior textbook** with **145 theories, 601 scales and 108 R methods**: a lead orchestrator routes each concept query to three specialist agents and assembles one complete four-library answer.

Part of the [Lucewalk Lumen](https://github.com/Lucewalk-Lumen/about-me) collection — expert teams, agents and skills for the WorkBuddy AI assistant platform.

## What it does

Ask about any OB & HRM concept — "equity theory", "job embeddedness scale", "how to run a mediation analysis in R" — and get one assembled answer drawn from **four libraries**: theory, scale, R methods and the textbook itself.

The grounding rules are reviewer-grade:

- **Every theory entry carries its literature trail** — origin publication, later developments, textbook section anchor (chapter and section numbers verified against the source, not guessed);
- **Every scale entry states dimensions, item counts and provenance** — and when scoring instructions are not covered by the original source, the agent says "原文未覆盖" and points you back to it, instead of inventing a scoring key;
- **Word-form matching with honesty** — "公平性" still matches "公平" via bidirectional fuzzy matching, and the agent explicitly tells you it was a relaxed match, not an exact hit;
- **Coverage tracking** — 130+ theory entries with maturity states; curated scales include workplace loneliness, leader identification and more, each labeled with its verification status.

## How it works

- **Phase 0 · Concept identification → bridge routing** (iron rule, executed by the lead): identify the concept, verify the textbook section number through the chapter index, then locate the construct in the source chapter text before anything else happens;
- **Phase 1 · Routing decision** — theory, scale or R-methods specialist, or a combination;
- **Phase 2 · Member dispatch** — the lead spawns the right specialists (TeamCreate + spawn), members query their libraries and return on contract;
- **Phase 3 · Final assembly** — the lead merges member returns into one complete four-library answer.

## Conversation mechanics

Three interaction behaviors built into the lead:

1. **Multi-turn context carry-over** — follow-up questions like "那 XX 呢" reuse the established topic without restating context;
2. **Proactive ambiguity clarification** — if a concept has multiple readings (分配公平 vs 程序公平), it asks which one you mean before searching;
3. **Layered depth** — first reply gives an overview plus explorable directions; you点名, it expands.

## Hard rules

- **Four citation iron rules** that cannot be violated by any member;
- **Explicit forbidden behaviors** for all agents;
- **Truncation honesty** — when results exceed the display cap, it states the total count and the shown count rather than letting you believe you saw everything.

## Agent roster

| Agent | Role |
|---|---|
| `obhrm-brain-trust-lead` | Orchestrator — concept identification, bridge routing, final assembly |
| `obhrm-theory` | Theory library queries — 145 theories with literature trails |
| `obhrm-scale` | Scale library queries — 601 scales with provenance labels |
| `obhrm-ranalysis` | R methods library — 108 methods for analysis guidance |

## Skills

`bridge` (textbook chapter index & source-text verification) · `theory` · `scale` · `ranalysis`

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk-Lumen/obhrm-brain-trust/releases) or clone this repo;
2. Unzip keeping the `.codebuddy-plugin/` manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).

## Version

Current release: **v1.0.3** — added multi-turn follow-ups, bidirectional word-form matching, truncation honesty, explicit missing-source labels, 2 new scales and 11 new theory entries. See the package manifest for details.

## License

MIT — see [LICENSE](LICENSE).


---

<details>
<summary><strong>📖 中文说明(Chinese README)</strong></summary>

# OBHRM 智囊团

**OBHRM 智囊团:12 章教材 × 145 理论 × 601 量表 × 108 R 方法的四库溯源问答**

- 版本:v1.0.3 · 类型:team
- 版本真源:包内 `.codebuddy-plugin/plugin.json` 的 `version` 字段
- 所属合集:[Lucewalk Experts 门户](https://github.com/Lucewalk-Lumen/about-me)(全部产品目录与品牌说明)

## 安装

1. 从本仓库 [Releases](https://github.com/Lucewalk-Lumen/obhrm-brain-trust/releases) 页下载该包 zip(或直接克隆仓库);
2. 解压后**保持内部清单结构不变**(`.codebuddy-plugin/` 目录);
3. 在 WorkBuddy 中导入/注册(自定义连接器入口 → 信任并启用)。

能力详解见上方英文文档;品牌与全部产品目录见门户仓库。

## 许可

MIT——详见 [LICENSE](LICENSE)。

</details>
