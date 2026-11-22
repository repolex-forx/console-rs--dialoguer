# Repolex Knowledge Graph of console-rs/dialoguer

RDF knowledge graph data for [console-rs/dialoguer](https://github.com/console-rs/dialoguer), parsed by [repolex](https://repolex.ai).

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
rlex download console-rs/dialoguer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 731c70b9a5919f39eb2b88f08a569c5980713b3f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 731c70b9a5919f39eb2b88f08a569c5980713b3f.nq.gz
│   └── repolex
│       └── 731c70b9a5919f39eb2b88f08a569c5980713b3f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0d69b273665d04538cea32b49ab6c2f914e349f8.nq.gz
│   ├── 12cdd226258cba5322749860318a82698803deb3.nq.gz
│   ├── 1c131855de39caf498b0472634e9dcf434081fb2.nq.gz
│   ├── 1e551569f9cc72346b42ccce718303080e24654f.nq.gz
│   ├── 209ff68fff4ee228a81eedbcf08a29137bccd43f.nq.gz
│   ├── 3465771eef59b88e66fd2c312b6116b9186cd4a1.nq.gz
│   ├── 35e1d30d0a805c3f8c672c8aec0e7782c524a17b.nq.gz
│   ├── 36e7726e03c489f475450ff75527f475e43fae38.nq.gz
│   ├── 39d46f07702c044699936964e74499f28e0ce517.nq.gz
│   ├── 3b1d3ca0ebd45ddd140ea7dc584706ad0ead4177.nq.gz
│   ├── 3e304939748d76329e23f35b2cabe651d93e775e.nq.gz
│   ├── 42b301d2d59f1dad397f4b9162a696236d408a2d.nq.gz
│   ├── 5cc21db28f0aa996c823c84f8f63fad9464f7a55.nq.gz
│   ├── 63f9726972bd4a936c16b514f20918a114c11528.nq.gz
│   ├── 68dfd2b29b1ef6471307e099f9a8ab8355c332f6.nq.gz
│   ├── 766df719307065a3551a1aa6a3ff40e139ef9350.nq.gz
│   ├── 79045abe1524aef6aba9d8458add121455f624fb.nq.gz
│   ├── 7c81907f38326657aa6e0c771577a470430ff842.nq.gz
│   ├── 86d7f75935f25a2ac834c8f13ee27a5725ec9532.nq.gz
│   ├── 872975db286ce50ac102dff1e78ffd750a62937a.nq.gz
│   ├── 8ff126fb8eac2518dd4a69a238ef78dc13194cef.nq.gz
│   ├── 96f62bd04a233cdb2a8ecddce476449161722394.nq.gz
│   ├── 975695097c56c46a1f7f91b03234b18e9ca2f504.nq.gz
│   ├── 97d3baecdafd0987215e72f2be15d6fee60e34ad.nq.gz
│   ├── 98c2a9c2411b6b6eb1edf7f712501a0b4d33b3ca.nq.gz
│   ├── 9f0679864bf2ef5ac43169461966018a09779437.nq.gz
│   ├── a00fb6b180736ae7d03adf6fdd6ace87be6085c0.nq.gz
│   ├── a9d37c560c6ab8d4afbf47eda643e8c42e857716.nq.gz
│   ├── ae920aa189d370aa5b88b1fbc16c7873b2937c13.nq.gz
│   ├── b114456e14b5e17fa0547a5b268b768438ce0223.nq.gz
│   ├── b8f00fd75cf060d314022569441e7e0f6f498170.nq.gz
│   ├── b9140327e0670284c44e101ebf9d063aead59bfa.nq.gz
│   ├── c6e06abd041b145fb61534cf449be67e0c389569.nq.gz
│   ├── cbf428f0cfd76d0191acf1cb19e3cff3dc45e4c6.nq.gz
│   ├── d22001cfda08dfecf91331ab133954a166bca4d5.nq.gz
│   ├── d282c20b0e98bec1aab25860aca57739ce062aec.nq.gz
│   ├── dc9a85c1ee2f335497ac578f7ff8fced6c49ba6e.nq.gz
│   ├── e1f18eef359440e25ab061aa877f51bdd788ed97.nq.gz
│   ├── e6f3addf147bfbbf2c4fe0a23830bec7ddfe0e81.nq.gz
│   ├── ed8e4edb47986fd188fd3704c34e68a44cc77836.nq.gz
│   ├── f59e8f9839158de9f6a970d09eb29cd992111d67.nq.gz
│   └── ff8240fd6749e6007eb16df707deb9dba14502df.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 731c70b9a5919f39eb2b88f08a569c5980713b3f.nq.gz
├── filetree
│   └── 731c70b9a5919f39eb2b88f08a569c5980713b3f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 52 files
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

[console-rs/dialoguer](https://github.com/console-rs/dialoguer)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
