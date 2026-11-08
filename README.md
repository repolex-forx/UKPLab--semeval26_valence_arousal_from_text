# Repolex Knowledge Graph of UKPLab/semeval26_valence_arousal_from_text

RDF knowledge graph data for [UKPLab/semeval26_valence_arousal_from_text](https://github.com/UKPLab/semeval26_valence_arousal_from_text), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/semeval26_valence_arousal_from_text
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e1a4440ad2cd7c28beb3adeaed8dcd44ff3567a1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e1a4440ad2cd7c28beb3adeaed8dcd44ff3567a1
│           └── chunk-001.nq.gz
├── blob
│   ├── 0611c643eaabcf11fb814610d06ea6199939c574.nq.gz
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 0d39a67c24f01c1af1e9cb675f380c3a1d1b2422.nq.gz
│   ├── 0efcae78dc00c352e50e9c978d361b631503f8f5.nq.gz
│   ├── 10795da6998b54c3b5a777f9d5773b960cdeed12.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 14411fd93d699377c6e17280cabaf9a39d67dbdc.nq.gz
│   ├── 1bfe7d6123f317972ae934ee04b23243c0908103.nq.gz
│   ├── 20e5e06ed4b63624f8d1930f2cc24de2248f565a.nq.gz
│   ├── 222326b9205a42b587d8ef50fe3111edf10acd8f.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 22f1ff137c433a2926165ed2ac7f32bbe6e5b907.nq.gz
│   ├── 2476c6e2ba08922b0ed5996cbeabf471bd008cfe.nq.gz
│   ├── 2682206361799828eb1c167c709929b9eb3fdf76.nq.gz
│   ├── 2d212a00a6b687b417a90fa47063b21a1e6ed7be.nq.gz
│   ├── 3886579ba2d123b110bf76b94c20c264cec6e70c.nq.gz
│   ├── 3dc429a6613bf85898a47643fe31d4439fe9d973.nq.gz
│   ├── 48a566d706346e53ad447167d1ddbf33bd24e937.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 53353b33981d97a960b725c1e540dcbf7a637dec.nq.gz
│   ├── 5890d01658aeefa96be7d09e290644fc21169730.nq.gz
│   ├── 58acfd941b1da8c7916bc64a4562c14d005e7b4f.nq.gz
│   ├── 5dcef726f671e400c7a0873dc8e9d9f061889630.nq.gz
│   ├── 6257cbd171f18613055985a7ee863366b9e3e93a.nq.gz
│   ├── 68eb69b23434984ce6053d307b6b6b7f709a7e7e.nq.gz
│   ├── 698e9f972a96948e15606d89ceda254e571d2692.nq.gz
│   ├── 6bbbf54e7010f861a3e732beef7d5736dbaae475.nq.gz
│   ├── 6fade88c12dd5c38eafc920cb88a257a77867636.nq.gz
│   ├── 722f9f7f183d53071e7271928d985fc7c5d7d31a.nq.gz
│   ├── 80f9dedb22582266a9daa4b5a74a2b7ef60f99a4.nq.gz
│   ├── 829cafe545fbc5b6a622128620b975639019a6ef.nq.gz
│   ├── 86d9851d5be48eb9aae3cccc801497c639bde6b7.nq.gz
│   ├── 8863af98e93c02e6093a6fd837cca4150df03b2c.nq.gz
│   ├── 8871abfdc9c3745a372d1b55952f4d24481e3ea0.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8b14d41f730e3642c5986d15e956bb8af5134367.nq.gz
│   ├── 95be859de266bd01442b635c8cbdc5aaf2775b16.nq.gz
│   ├── 95e40b5352f0a9d988d639f6c17f6a28f08e4dc7.nq.gz
│   ├── 9aae802353c4020a6d297a03b21d0e8243d85936.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── a5496b464b51950ec8262ab89c4ceb1c95331847.nq.gz
│   ├── a5cc05c53c2b6abf9ac9b2d506fefc3cc4d1ca92.nq.gz
│   ├── a70d291241eea483a3e2ca58d7c779b17cc164b8.nq.gz
│   ├── a74a7a61a588f224cae2447156dc429dce2f86fc.nq.gz
│   ├── b1e937efdd90d5033e0485d99e2c54cb93e1baa2.nq.gz
│   ├── b600fbbccdefad705e37d8b40f710d9665b7a7b7.nq.gz
│   ├── b68b90452a95c3c11e1ebb17178952d62fc82466.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c309d30927298211b63df67e6dc557d83da39f29.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c7a351776c6d721e4c4b745d42d4091fc5346cc1.nq.gz
│   ├── c987490f57b1a8cb18ba2f6dda61707d62a7ac34.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── e36c4d875e4757b059038aa531ab33f370517bdb.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── f47c06cc18baa434989aa2d46756a0b678957242.nq.gz
│   └── fd53425479e82f8d3bc9175aa4ce2260ef4d37c1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e1a4440ad2cd7c28beb3adeaed8dcd44ff3567a1.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 65 files
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

[UKPLab/semeval26_valence_arousal_from_text](https://github.com/UKPLab/semeval26_valence_arousal_from_text)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
