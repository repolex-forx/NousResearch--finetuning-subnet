# Repolex Knowledge Graph of NousResearch/finetuning-subnet

RDF knowledge graph data for [NousResearch/finetuning-subnet](https://github.com/NousResearch/finetuning-subnet), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download NousResearch/finetuning-subnet
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e2f5eb6373a417fc7c03e38adbc6cf145670ab58
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e2f5eb6373a417fc7c03e38adbc6cf145670ab58.nq.gz
│   └── repolex
│       └── e2f5eb6373a417fc7c03e38adbc6cf145670ab58
│           └── chunk-001.nq.gz
├── blob
│   ├── 02613dafe77e27bf983f3351c85fd26e4427c04c.nq.gz
│   ├── 06761e4d1834940899b37a8af25ed58ab688dcfd.nq.gz
│   ├── 116f35b817fda310ae18989aa61a7d1b83d998e1.nq.gz
│   ├── 12b8a27f8f3f4a4780a47b1d3e2d2414e7ac87a5.nq.gz
│   ├── 13bb07b253d4a45de39c50f222fabfb8ed9b73ae.nq.gz
│   ├── 1466e39b6971224d78d13020ddc242051472a5e2.nq.gz
│   ├── 1945020842b5f8372df6ed0f6aa1e4c308840609.nq.gz
│   ├── 1bb909382b2f30e05ef44f9282aa7745d7fbd6ed.nq.gz
│   ├── 2149d2dcb13c92993ef8ec879bc7146988f69843.nq.gz
│   ├── 266e11bf60371f2b7873226b16e5573b6731fe2e.nq.gz
│   ├── 2cd47cb8e419eaa7b8619323fd48d1be8b4cce20.nq.gz
│   ├── 37e4062a04bff55c65ee5db1121d47e11185c18b.nq.gz
│   ├── 38a156325140e7c1b6c8d508d1017baecb5f75b7.nq.gz
│   ├── 3a0852b705ccd8681ea905800592acbc34de0703.nq.gz
│   ├── 3bd50d5838b38952ac40904882a6d008479a72bc.nq.gz
│   ├── 400fba6abe804782dbffbe81ffd8be554adbaa10.nq.gz
│   ├── 4021dcb385b3c699a80328c8d5c4f25f08f99a47.nq.gz
│   ├── 432489acafde5b7e99d2a8978834958ecb6a841c.nq.gz
│   ├── 476277123e9d34fd30a2d5e8c9ed3fd02cd3b625.nq.gz
│   ├── 4b0543f5bedc7ca333ed61f97953879968cf0a8d.nq.gz
│   ├── 5ac17228f2682659e9efc3777094851392c10965.nq.gz
│   ├── 5f34b2898e6c78e759319bafa58854af5a93c1d5.nq.gz
│   ├── 61ce3b6d5536800a8a93598016f046f7a97eb056.nq.gz
│   ├── 66b8117adb35f75f0e400c08c5095320bcd522c6.nq.gz
│   ├── 67cebb1941d33a2dfa797f483b44624c8b337c60.nq.gz
│   ├── 6924c4e4c7010f2aca52f068184d98589a3c53d6.nq.gz
│   ├── 756237558f4bd8e63e06336932361fd8f36dbe64.nq.gz
│   ├── 81ba829938eb9a3a0718e8e8798f6a9dd4942a9c.nq.gz
│   ├── 8a8c7b274fc51bc97836835bbba6277b2c26bab0.nq.gz
│   ├── 93efeaaa5ff2620cfcf4eb8a43259d5b010447d1.nq.gz
│   ├── 9909606a8995f6702a688ae3f9bfc53fd9b4466c.nq.gz
│   ├── 9cd0a26b97583b25fa6e6fe3e293140ce90d995e.nq.gz
│   ├── a06d050f894ffbe7139ecb8d90d06a72684c1e0e.nq.gz
│   ├── a2b033a306e22fd0583eda2f77fb7c21f5196a42.nq.gz
│   ├── a78becddbe2bd4b9fdfd1531e52a695e1ef93af7.nq.gz
│   ├── a8df9ddbe974370fcba05f00f38bf0c262c92aaa.nq.gz
│   ├── b0bd6b43db0f4115a4d15fc4ddc70e99b6d111c9.nq.gz
│   ├── b7ac755fc06a69f60e6ca9ecef6030de9ae741d6.nq.gz
│   ├── b84d7991b8d8ff3b8d5b3af8aecc55a5ab76df3a.nq.gz
│   ├── b8cbd5dd66f4ad95a03493896d2aafb7196f253a.nq.gz
│   ├── c0bdddc45bcbe0dec3d9d6adc342ffc44213b50e.nq.gz
│   ├── c18e70fb6455f2b408b2c560d7ee7ca6dd32c948.nq.gz
│   ├── c32fd0e8e504670e9fcfc237a89f0ad194b81ae7.nq.gz
│   ├── c99e2ab90f61ee29d4cb1bba5d97694009285f7a.nq.gz
│   ├── d202215e232e639e3339fcfcc5ab374ea82d10ff.nq.gz
│   ├── d33337bc4cd65376061997a4af405c6117aa7258.nq.gz
│   ├── d4848bfac5da62900bc50a438cb876baab7e8b55.nq.gz
│   ├── dff1aa8152cd7882c49a6142292d0fb897ea1080.nq.gz
│   ├── e3148ce2cf3f4e374997409d7df91320370939ad.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea52c9c3bc9fd5f0815f0349bfdf7f3fa6dd3bdb.nq.gz
│   ├── f13784469f65ba9d3238301658d2eb6e8ae0e2a2.nq.gz
│   ├── f16316a0c8f35f9e81915d4c439c4fb053dd91e0.nq.gz
│   ├── f5dc828fa5582849cab9b00d3328d3eb29719c9b.nq.gz
│   ├── fadb9bbcb76ce67e15804e713b679b276d3a3d70.nq.gz
│   ├── fb81282176ba81ac02ce630f459d774577748011.nq.gz
│   └── fee6ef7322f38be2bfe70c1bcfa9be440c8a0935.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e2f5eb6373a417fc7c03e38adbc6cf145670ab58.nq.gz
├── filetree
│   └── e2f5eb6373a417fc7c03e38adbc6cf145670ab58.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 67 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[NousResearch/finetuning-subnet](https://github.com/NousResearch/finetuning-subnet)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
