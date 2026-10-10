# Repolex Knowledge Graph of tiangolo/depende

RDF knowledge graph data for [tiangolo/depende](https://github.com/tiangolo/depende), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download tiangolo/depende
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 166b98c471d90d21e6ea8ac97b2e83a71b7730b0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 166b98c471d90d21e6ea8ac97b2e83a71b7730b0
│           └── chunk-001.nq.gz
├── blob
│   ├── 0741ea10d03d7814ef3c43f969b580c91fdadc37.nq.gz
│   ├── 0a81458dc41bb0c014ed98afee4aa6cde3b8533b.nq.gz
│   ├── 0d312a3e8172726de2b9bd138c42d762eb45c4c2.nq.gz
│   ├── 108ac17b6f21dc6c26784bfd7a104f4439787a5a.nq.gz
│   ├── 1591365077b207a09fca211cc2654400cbf9cdf6.nq.gz
│   ├── 274ed881cb932100582ece27b260de901155537f.nq.gz
│   ├── 29f2bf8524aa0de30a830940738892bc21b9aff1.nq.gz
│   ├── 2d2b775c2544a0c9b2c71377344362ce900661b0.nq.gz
│   ├── 3307469f8a9e24f5f846b14260328b54f8c2e3be.nq.gz
│   ├── 3834f2ba0bb6701fa0e31c3a0270375038f605ba.nq.gz
│   ├── 3da078161c1a862c475ef928fb64a4e91cbb25d9.nq.gz
│   ├── 48179b6cecbb3ebd95e71be13bc621abf1906149.nq.gz
│   ├── 53b1845d9ff6196bf27819a7641f9dda22399c15.nq.gz
│   ├── 5f60f7a87e8af202aa44420e4d11c45892dd6cc0.nq.gz
│   ├── 64285c613a58b422dd41e089857098fceaad7ebc.nq.gz
│   ├── 64c5ced6e2f3de68d32dfc38f095b1b697d060d6.nq.gz
│   ├── 6c8fb12fb1645ade8cfb8b7071699478e86744f1.nq.gz
│   ├── 6db77c89c9d4fa10f6f12474612264327cd3bbb0.nq.gz
│   ├── 7ea8c8791c81a17cf732b9b42192244a4ce1205e.nq.gz
│   ├── 85b1fea57ca9d9b114392f8ff3b3afff85d22985.nq.gz
│   ├── 85e14595474b10daa0c9ee1690b9a4a045c81a79.nq.gz
│   ├── 884d8eea78dd027e51459f97da1fd9d6a133763b.nq.gz
│   ├── 885247e2f92ac6b8f66675515ae1db48b6166773.nq.gz
│   ├── 8efff714396a8f514dd4ebc83dd71bfebcbc8915.nq.gz
│   ├── 94c1e3849225ff9d15cd391adc28c3be6153fe5d.nq.gz
│   ├── 96da28655ffb437a43a0726b1ba360b061fea98c.nq.gz
│   ├── 9d0338c3d4444d34a0289d0ed19f7837d56c0c9f.nq.gz
│   ├── a9d2d73c715f3adaedee5e1733f1d3deca9cc35f.nq.gz
│   ├── ab691199d2e4f6fb95883a26c9406c4a58d7e564.nq.gz
│   ├── b1cc5cdfa0f1bbe293887e46f7ca6b72a2d45a15.nq.gz
│   ├── b98b0b6c0b14e39277fa9edfd834df20bbb04c64.nq.gz
│   ├── bb131844cb6acd0603968d62381edbb9619b05f3.nq.gz
│   ├── c2a0d939285a46ffd791fbb3eade2aa30d5cfeec.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── d42429f38422d176ad40e53c362b4b88f7c1ea76.nq.gz
│   ├── daa6038a0a8a386d6315b541c501a9a2abddc650.nq.gz
│   ├── de4d8d1442e93d761007e4be0c28dcf6b157d8da.nq.gz
│   ├── dee1b900aa41400bdbe25cca85f4131e33690e5c.nq.gz
│   ├── e3a0f99d540ee9e631af236f00db64ff7aa22224.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ead31fa736478c0d1a8d5b1a1ddb68b3a16a3812.nq.gz
│   ├── ecd1abdaa71524d60f7dc1f2fd9b7e552cf66e11.nq.gz
│   ├── ecd288ba19b3d374f4353076bb36be677c180b89.nq.gz
│   ├── f04861479e43eaa3bf8802c5a55c1500738c2352.nq.gz
│   ├── f1bd9aa849593352c4431fe193e38cecc8453148.nq.gz
│   ├── f251dcc34da5085458f74b390f772cc21a5e49f5.nq.gz
│   ├── f3c849f43925fdf49a95de574cb3a4a805be0a26.nq.gz
│   ├── faf472a13d122abacae68787d96a0ab77af53ac9.nq.gz
│   ├── ff4b114b186342c2380e790aa54ac24eb506b217.nq.gz
│   └── ffc0c7cadb64f65c2a17934e31ed9439535de212.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 166b98c471d90d21e6ea8ac97b2e83a71b7730b0.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 57 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[tiangolo/depende](https://github.com/tiangolo/depende)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
