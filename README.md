# Repolex Knowledge Graph of sphinx-contrib/spelling

RDF knowledge graph data for [sphinx-contrib/spelling](https://github.com/sphinx-contrib/spelling), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/spelling
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1eb81816aa74a04b28c51db5ee9085efd767283c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1eb81816aa74a04b28c51db5ee9085efd767283c
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
│   ├── 09b2c075e9609b2cf485028190c5ab39b8f74a78.nq.gz
│   ├── 2c2d612ce50a0d5acaecacc358c0578ec1b1fc86.nq.gz
│   ├── 2e0db5daa435c293b625d9067935abd985cb2988.nq.gz
│   ├── 3a23e53f47dc5337b1adaecc2a178bb62a4c078a.nq.gz
│   ├── 3bdbeb8fd45b82268cca366aa6b867cd301ffb9b.nq.gz
│   ├── 44d694556d3ec97373b3c254ce6521cfc9f269de.nq.gz
│   ├── 4a83dc478f7ab9f13a73ee8b40e3c1a14b1acdba.nq.gz
│   ├── 4e48facb062ff6df23546636106e4d7244c1946f.nq.gz
│   ├── 571c52372c9e6c72a8cc943b567cd0b235766c5b.nq.gz
│   ├── 58bbc09945821f30ab24398659b389874a95519c.nq.gz
│   ├── 5d0e1624822647ee34b1831a8f4cb7884022aae8.nq.gz
│   ├── 5fa6228ae601ab7cef81834b21e18aed3d5776f0.nq.gz
│   ├── 60827263a375acb2a5c9a1e4c2569b71104f74f9.nq.gz
│   ├── 633f7ce990b8af8beb1f71883caf054cc5298875.nq.gz
│   ├── 79202b72d40833ddadcd4e6d4ec2ef8805ea6f87.nq.gz
│   ├── 7a1392c5998a3a6231fb94f7617307fc930a0947.nq.gz
│   ├── 7d1a796964a3ef578e447cd11d5ee3b1ad8a72b3.nq.gz
│   ├── 7f252f0c9ce3ea951064e1f2dbc1c22ffbd1fb30.nq.gz
│   ├── 7fbc9463031ebf080f5fb0daab3adbc69e1b42bf.nq.gz
│   ├── 7fc93535aabbc018740197c37ed787366c27aac2.nq.gz
│   ├── 81722bccfb9041aa5ad1237e3b89de5984851d15.nq.gz
│   ├── 83f9fcffd0078f983662cea622e98843de7f2b22.nq.gz
│   ├── 840284f3c2bd6f0824569a657d1ab3e3e84fd3f7.nq.gz
│   ├── 846ba239dddc989098324e314d9ec12f204cb4a3.nq.gz
│   ├── 85b5222d4efbd69c230b754dac69187a31ee922e.nq.gz
│   ├── 8900432289003e0c9e2972378516d77376a130c5.nq.gz
│   ├── 8a92a147cc371f9caf7922bf7ef080eef2cc3cfe.nq.gz
│   ├── 9d6cea799cef74a5ac695204f9e146a7cc2ded19.nq.gz
│   ├── a2ff14b27fa33e759ba5c32314d5b219276596b1.nq.gz
│   ├── a8a03b03065c62b72cd867c03946d76e9bd2228e.nq.gz
│   ├── a8c3978a71787419b247e9dfd2f8e2b97224e471.nq.gz
│   ├── ae4174a77f4f45e22a36536c6cbc25f0506a8f45.nq.gz
│   ├── af3ee5763862e3daa29c9085c29d1c64cc60edd5.nq.gz
│   ├── b4443222fd9bafc8560efa2a675af25c0cf7926b.nq.gz
│   ├── cc6e220b6ba519668a59ab4bf03e9c48c051179b.nq.gz
│   ├── d015d8980468ae4a070cfb57b5aeca75a54d97b4.nq.gz
│   ├── d0ab29bf77add24022bc7b2f2434446117afde94.nq.gz
│   ├── e4352c4a512c68832a8506f08d351263a98b2788.nq.gz
│   ├── e660bf9df22243417bc4830e251acd385c9530bd.nq.gz
│   ├── e7ce2ec569a74c0deb04570e72b609e126a53ea5.nq.gz
│   ├── eb76783e90e38f6198ccfb259e889e112494f59e.nq.gz
│   ├── eeb48af4e65cd8a8b97eebb1b8a3abd9fcaf2ff7.nq.gz
│   ├── f25c796597f8aa74fada909d8576ff4e144ffd42.nq.gz
│   ├── f60c01e3d74c7f073e0a7fd6b75b8d529b7c0203.nq.gz
│   ├── f64478f51d166284e54c8f7cbfc7875a09daa51d.nq.gz
│   └── f7fd10ccefed52e63a358620a723d9e3f02d026b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1eb81816aa74a04b28c51db5ee9085efd767283c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[sphinx-contrib/spelling](https://github.com/sphinx-contrib/spelling)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
