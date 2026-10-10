# Repolex Knowledge Graph of tox-dev/tox-pre-commit

RDF knowledge graph data for [tox-dev/tox-pre-commit](https://github.com/tox-dev/tox-pre-commit), parsed by [repolex](https://repolex.ai).

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
rlex download tox-dev/tox-pre-commit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f8808711e8461fb952e3722e460ff797d5c87dd9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f8808711e8461fb952e3722e460ff797d5c87dd9
│           └── chunk-001.nq.gz
├── blob
│   ├── 02fd59e51748f42d552f5cf8a91756c8efd21870.nq.gz
│   ├── 1a34adf8763d92a63584d989bcbc6ddc7b5ecbd5.nq.gz
│   ├── 1f0402868ee30d4f7c49407ac5cec7dbf533d993.nq.gz
│   ├── 38e57e26fad3bd8f9157502f9b85fa80aa3afd5a.nq.gz
│   ├── 3dde2eaa4cfe6dee0045748b18c8db8a4fb2fca6.nq.gz
│   ├── 4072d6b2ba953f3834f0d45ef78a7d382d9a1f5e.nq.gz
│   ├── 4479652ed8465e4e2b2c0b60c474953f060bad1b.nq.gz
│   ├── 4f7fdda9d83ccb922dd876ef5c9199c807a448c6.nq.gz
│   ├── 56695a89c616723333d3c40c0a5d015f80543066.nq.gz
│   ├── 56a9e82809c1f5f82dba0d3f2f27dda75e5d9f67.nq.gz
│   ├── 618bc0b51ce8324ce3d3a249906beab5f24ee70e.nq.gz
│   ├── 6222f51ac7161db329218efb92157362342616b4.nq.gz
│   ├── 6283f3d4e46382ae98e8c5b6ac28c47a197b51fe.nq.gz
│   ├── 6484ac9773a9ddb01d22737f244a5de3c216b922.nq.gz
│   ├── 6acb3b415aa0ee5568c3c30ff1e447d21c53b6a5.nq.gz
│   ├── 6c91dddad3e8b559f1e55314bab6908825000dd1.nq.gz
│   ├── 712b7d23a9e876ba411d6c1752452c49b7d9ea76.nq.gz
│   ├── 74f60b1215e5ecfc18b3e4ee6612c83e7e45240b.nq.gz
│   ├── 7998d1e7884309bf15e6754c4ad1e380ca0460a0.nq.gz
│   ├── 7dc0e11c701e59b45def8d3671cc4925a5106f99.nq.gz
│   ├── 7ecee60d9ca373d013ac7d05744a9fcd3b65379d.nq.gz
│   ├── 8c3a778adfa56db04a81ba121bab38bd369e7e40.nq.gz
│   ├── 8cbb75ca440ca87b1d1204804783133bc880f107.nq.gz
│   ├── 927493c69aee52871f4fe80038f2f4e2f54ad0ab.nq.gz
│   ├── 93dec44514d8a1a7733e31530cadb6a82400e865.nq.gz
│   ├── 956dd207c232a953c2c67d7d1f74fdaef9d692f0.nq.gz
│   ├── 9d8403cf2b5b21c7892156b5352fc3700cfa1380.nq.gz
│   ├── a373b0bd6c77b35b8a48a5ef926fa55c299ce62a.nq.gz
│   ├── bee24f0caa4206563d2cc018d345f7cfb1ff4108.nq.gz
│   ├── c0299be6c8051fe7f0ef76cc3f907cd7806bef6c.nq.gz
│   ├── c427ee226404e3bb848a3e995e997c2768f9ef62.nq.gz
│   ├── c51020b774e1fa52853474a89216baab8972b0d0.nq.gz
│   ├── c5e4a499c1d5ad89bf01ba8ff2d0fda3e374fb87.nq.gz
│   ├── cb96cf5e33be848fbdd858c3675390de9d8f5cf1.nq.gz
│   ├── cc544a6e7e607b94c1233de6ff72f8af6a354380.nq.gz
│   ├── d06d65b0e26f019c5183a60a439666337a68e98d.nq.gz
│   ├── d1dfe93add09e9ed8949e35078ddd41fb60cf6eb.nq.gz
│   ├── d36832df25913e9b986db37b6c6a2ea4f9f4fdef.nq.gz
│   ├── dd53a6445fffd49cac90dba7836fc4a5cf3eb56e.nq.gz
│   ├── dd64b72c3f75d7a669eca22b084dcfb3f3615f19.nq.gz
│   ├── e0d6e0d485f7d2dc93c9acd4b0a83b3e1576e928.nq.gz
│   ├── ec8c33334fee0c7b5da22af531a3394e02f63023.nq.gz
│   ├── ed00c27777c81848a54578300fac6d203f945376.nq.gz
│   ├── f145166193029b0ec3bcd7674a3339dbc9df0d1d.nq.gz
│   └── f7cdbbb9649fbfabe573896c602640081b159239.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f8808711e8461fb952e3722e460ff797d5c87dd9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[tox-dev/tox-pre-commit](https://github.com/tox-dev/tox-pre-commit)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
