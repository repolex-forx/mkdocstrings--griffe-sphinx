# Repolex Knowledge Graph of mkdocstrings/griffe-sphinx

RDF knowledge graph data for [mkdocstrings/griffe-sphinx](https://github.com/mkdocstrings/griffe-sphinx), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/griffe-sphinx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 786711f1fe5f7c8c949fe4b3762e702e040c91de
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 786711f1fe5f7c8c949fe4b3762e702e040c91de
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 05ca71fa2c886851400510ad90c5bcedbd1e70c8.nq.gz
│   ├── 0b399b2ad8b4b26b5241a1412d7cf68597ec71c2.nq.gz
│   ├── 0ca7fabfe18b401de8974a8668482dfddfb3b9e3.nq.gz
│   ├── 14bf4dd6f7e398d4404735ec08baba4ad15cc7e2.nq.gz
│   ├── 276c7e5e06bcf6635c7eace9cbc8092145f978db.nq.gz
│   ├── 2caf1f3fb9243df7e3f2cb5838ca7d8f6bb78f11.nq.gz
│   ├── 2d46305a68da4b9569bf6813f4d2fb1131653842.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 2fcf869f97e3db32d04bba2de14fc59596538076.nq.gz
│   ├── 30571233ab2743c8bfa278db17f69b884823c94f.nq.gz
│   ├── 35ec8f1917b21691560159f7e6051600f0674f58.nq.gz
│   ├── 372709410d446494f5d0831a568306b01cc33f46.nq.gz
│   ├── 3c056e55510f61d550334203799276af29ced50c.nq.gz
│   ├── 461f7e3d73ca89f0dee46d673a8057f563b9873f.nq.gz
│   ├── 4ac4d14d93b6d4536a534b4ff46ca722abbb379e.nq.gz
│   ├── 50d9903c2979c789b795297394ac66301141576e.nq.gz
│   ├── 51587578d052005002f5e1f131bfeb180807caed.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 5b93032858c4ad10bc811eb0d1051585ae53eda4.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 640c03d38d9ae465d8b89310ce816ec1c13b6a61.nq.gz
│   ├── 6c54c4f9aaeab88e7f64cbe5be9e6be4a86dfffd.nq.gz
│   ├── 6ec48d5821210cae0f7ce914b88fa04b4b7cde8a.nq.gz
│   ├── 6f0f2faf32486394750d5d5421e2261430b73fef.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 767bbe280e6ddf497104f316fca52259955da077.nq.gz
│   ├── 7d77578a0caf3aae833d381e9700787c6e663807.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 82377e2175cb6a3e81bcd4650e4c158db89a8004.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 97724fa80f2fd81fddb1eb8b00029dc4fee78054.nq.gz
│   ├── 98cbfdd106f6af898b9ceed1ec1f707b532c5173.nq.gz
│   ├── 9ac0b2a6524d3268e7019a2439791243b364a1e5.nq.gz
│   ├── 9e1a6da4f432fa05d89c08f95012a5f4fe32043a.nq.gz
│   ├── a09379f1b6893041a9e5249ae2b8e054b532cd23.nq.gz
│   ├── a3315b69c0aad9469129f0135d66948097927cde.nq.gz
│   ├── a870a24f9f15eb47b00bd3c3feef3c82d97687cf.nq.gz
│   ├── b2e69ee8a908cbea3a6430ed5174dda6dfe9f49b.nq.gz
│   ├── b3fbe524f72abe60cfad0301e97b71b123af0ae5.nq.gz
│   ├── b56a2866c098400c2cdb660aa908a99bfd0cba34.nq.gz
│   ├── b5b9e4112f6a5d9d1bd791fc83f100a905861ca5.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── c4a180a3325cd3b07f80af8b9720a194260373a6.nq.gz
│   ├── cf5167c2e9679501b2c8826b58e24e8a71cea84e.nq.gz
│   ├── d4e1b544069c9e1a36c69e5a4841cc2305a10e1f.nq.gz
│   ├── d6eaf6e9835c8dac49d4432f6a53a11bee2616b5.nq.gz
│   ├── dc711a48b9bd2f8029f3af22e74526a2cb8661f3.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── e2e39a222429aaa9f07363f523b219c6c8b8941b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bb5b91b56c550fab69e0f2898006069366f3da.nq.gz
│   ├── e70d92783fc1ba829f1aed855eb3cdcea3155275.nq.gz
│   ├── f072271cb235e97740a9887ebc76955c62749a18.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   └── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 786711f1fe5f7c8c949fe4b3762e702e040c91de.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
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

[mkdocstrings/griffe-sphinx](https://github.com/mkdocstrings/griffe-sphinx)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
