# kb-library-team

**智博资料室** · v1.0.5 · `team`

> KB Library Team — a chief knowledge officer with six internalized domains that turns scattered files into a query-ready knowledge base


Part of the [Lucewalk Lumen](https://github.com/Lucewalk/lucewalk-lumen) collection.


## What it does

- **Ingest** — multi-source intake with normalization and hard guardrails (≤50 files per batch)
- **Classify** — directory design and batch classification plans, executed only after your confirmation
- **Promote** — four-pool maturity gates (idea → draft → official → archive) as the single quality standard
- **Index** — MOC / index / bidirectional links / tags, kept on separate layers
- **Grounded Q&A** — answers that cite the library entry they came from
- **Archive & metrics** — archive-without-delete versioning plus health and value metrics

## How it works

- One chief knowledge officer (库正) carries six internalized domains instead of spawning sub-agents
- A governance playbook skill (`kb-governance-playbook`) encodes the operating rules
- Single-domain, read-only requests can be answered directly; everything else walks the full SOP

## Agent roster

| Agent | Role |
|---|---|
| `kb-answer-quality-officer` | 问答质量官 - 齐证 |
| `kb-archive-metrics-officer` | 归档度量官 - 安档 |
| `kb-classify-officer` | 分类组织官 - 林归类 |
| `kb-index-navigator` | 索引导航官 - 苏航 |
| `kb-ingest-officer` | 采集入库官 - 罗采 |
| `kb-library-team-lead` | 首席知识管理官 - 库正 |
| `kb-promotion-reviewer` | 晋级评审官 - 关晋 |

## Skills

`kb-governance-playbook`

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk/kb-library-team/releases) or clone this repo;
2. Unzip keeping the `.codebuddy-plugin/` manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).


## Version

Current release: **v1.0.5**. See the package manifest for details.


## License

MIT — see [LICENSE](LICENSE).


---

<details>
<summary><strong>📖 中文说明(Chinese README)</strong></summary>

# 智博资料室

**智博资料室:一位首席知识官内化六域职能,把散落文件变成可随问随答的知识库**

- 版本:v1.0.5 · 类型:team
- 版本真源:包内 `.codebuddy-plugin/plugin.json` 的 `version` 字段
- 所属合集:[Lucewalk Experts 门户](https://github.com/Lucewalk/lucewalk-experts)(全部产品目录与品牌说明)

## 安装

1. 从本仓库 [Releases](https://github.com/Lucewalk/kb-library-team/releases) 页下载该包 zip(或直接克隆仓库);
2. 解压后**保持内部清单结构不变**(`.codebuddy-plugin/` 目录);
3. 在 WorkBuddy 中导入/注册(自定义连接器入口 → 信任并启用)。

能力详解见上方英文文档;品牌与全部产品目录见门户仓库。

## 许可

MIT——详见 [LICENSE](LICENSE)。

</details>
