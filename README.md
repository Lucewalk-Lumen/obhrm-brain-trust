# obhrm-brain-trust

**OBHRM 智囊团** · v1.0.3 · `team`

> OBHRM multi-agent knowledge team linking a 12-chapter textbook with 145 theories, 601 scales and 108 R methods: a lead orchestrator routes each concept query to three specialist agents and assembles one complete four-library answer.


Part of the [WorkBuddy Experts](https://github.com/Lucewalk/lucewalk-experts) collection — expert teams, agents and skills for the WorkBuddy AI assistant platform.


## What it does

- **bridge** — OBHRM 智囊团（obhrm-brain-trust）— 概念桥接层（四库联动中枢）。以「中英双语概念词表」把教材章节、145 理论、601 量表、108 个 R 方法串联成一张网；输入任意组织行为学概念（如「情感」「领导力」），一次返回该概念的教材锚点与定义、理论依据、可用量
- **scale** — OBHRM 智囊团（obhrm-brain-trust）— 量表知识库（测量域资产）。601 个组织行为/人力资源管理量表（中英变量名+构念+维度+条目+计分方式+取用文献，条目带 verified/draft 生命周期），支持按 construct_id / 关键词 / sca
- **theory** — OBHRM 智囊团（obhrm-brain-trust）— 理论库（理论域资产）。145 个组织行为/人力资源管理理论（中英理论名+构念+内容/作用机制/结构/应用四段正文+参考文献），支持按 construct_id / 关键词 / theory_id 检索，供理论框架构建、假
- **ranalysis** — OBHRM 智囊团（obhrm-brain-trust）— R 分析方法库（实证域资产）。108 个 R 分析脚本（01-env 环境 → 19-llm 大语言模型，覆盖描述/相关/回归/SEM/剖面/元分析/多层等方法族；其中 106 个依赖可从 CRAN 标准安装，2 个依赖

## Agent roster

| Agent | Role |
|---|---|
| `obhrm-brain-trust-lead` | obhrm-brain-trust 专家团 - 主理人 程亦楠 |
| `obhrm-ranalysis` | 数据分析专家 - 陆奕辰 |
| `obhrm-scale` | 量表检索专家 - 顾铭泽 |
| `obhrm-theory` | 理论查询专家 - 江语桐 |

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk/obhrm-brain-trust/releases) or clone this repo;
2. Unzip keeping the internal manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).

## Version

Current release: **v1.0.3** — see [CHANGELOG.md](CHANGELOG.md) if present, or the package manifest.

## License

MIT — see [LICENSE](LICENSE).
