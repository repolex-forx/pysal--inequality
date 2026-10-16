# Repolex Knowledge Graph of pysal/inequality

RDF knowledge graph data for [pysal/inequality](https://github.com/pysal/inequality), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/inequality
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 77d802d6b85728e6fddb3f8871c2fa9ba72ae237
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 77d802d6b85728e6fddb3f8871c2fa9ba72ae237
│           └── chunk-001.nq.gz
├── blob
│   ├── 018d370e68433ac38ce8e81613fba84ffd30382e.nq.gz
│   ├── 075da959f1abdcdd2bb9a81ad59562c98ea8b573.nq.gz
│   ├── 09d2529e0c009089674834f13417cf47f5a9151f.nq.gz
│   ├── 0aa6afea297fc23335800b706e3133cb613f0cba.nq.gz
│   ├── 1155e256ca7ca21562af88734d416e9d3edddafe.nq.gz
│   ├── 12a5cf804c7851ba07c369ab573bce00f2d17a39.nq.gz
│   ├── 1477100bbfd0d3b12d3eb28f2a4fa03c7f0a5ce5.nq.gz
│   ├── 17660fd8fe6d594ff195434c71530fec630c041f.nq.gz
│   ├── 221b2206a6029dd0e0ca7e26e1a6efd2bcb89552.nq.gz
│   ├── 26e706e19975658516969ac476981bf615d9ceb5.nq.gz
│   ├── 2730abaae7ce89077e51b5711a5ef05b70969a8d.nq.gz
│   ├── 27b39e9e13297b5faa0d9aab985326dc547bad90.nq.gz
│   ├── 2857c5570f09a4de68a2ac1ccb2052f3ed8e07ac.nq.gz
│   ├── 2f02c459cc4129d9e268df9038e48948d6fe2734.nq.gz
│   ├── 381c610dbd094bac8df07c0398dfa31d4befff1e.nq.gz
│   ├── 3ad133c048f2189041151425a73485649e6c32c0.nq.gz
│   ├── 3f2c4d49eb6935a8f8dd7340da00657ec3a4eb4d.nq.gz
│   ├── 457c1d61de5570737562441a998d275428dabc11.nq.gz
│   ├── 4d63a411e824f1ae6070968c915c1d16af3ffc1f.nq.gz
│   ├── 5007ec2c969d8d2e5a5c2b2569e864243b3c0231.nq.gz
│   ├── 50390adcb6d0e5c3c466c336f03997c6605d133b.nq.gz
│   ├── 5046171f45aecfe1738c3bfb33fae4685e3b63ae.nq.gz
│   ├── 52b884f648e6f6f2fb0b5228686ae1e7430074ac.nq.gz
│   ├── 532abac3d4e63722d02a3f458183e349091ac17e.nq.gz
│   ├── 55b4534b5f7177b959c914a95c5b5f4aaea97eb4.nq.gz
│   ├── 5a1654f5b54abcbc8d40700d17f446ae073b9427.nq.gz
│   ├── 5be390b59074838fa7e4e33b9ad1882178ab330e.nq.gz
│   ├── 5e14777971c4c894f82c2d51163f94ee77b1ed6f.nq.gz
│   ├── 5e56c2f56595d7521c95193abad46f5dc0ef5b6c.nq.gz
│   ├── 6633c2a58c8f6bd311bc2cea32d1ec4fee8ad856.nq.gz
│   ├── 6a6f88f142ec2ae19056e09044f5986fb2fdf0a3.nq.gz
│   ├── 7575cd2a933c0351eaa355588e44366a86707617.nq.gz
│   ├── 79106105de1834793259778ae4169a2280010b7c.nq.gz
│   ├── 79e272d362bb982471030a199b0a2eee54c08899.nq.gz
│   ├── 82ebeaac1fda052229f6a7caafd6dd68a323929e.nq.gz
│   ├── 833d7c9200560a6d40105016bb8ccf40568153e8.nq.gz
│   ├── 8370f5df78ab4d366509f0dfcbe723e60abf3a8f.nq.gz
│   ├── 85e4a99a43372e17db680b3171dc890aa9a3201f.nq.gz
│   ├── 86dbdca9ea2a29bdf429830399b2b044684afa42.nq.gz
│   ├── 86e0c556087ff5872f75bb2d25165d6bcc056164.nq.gz
│   ├── 89b78e96cb8f5b0527765941650b6d48d0f5fe68.nq.gz
│   ├── 8df4a62b274f15956b00bb7a2265d1c0281e1cce.nq.gz
│   ├── 925b47345bc6314f08d0b0d8e5acd53685ffddd6.nq.gz
│   ├── 99fd3ab86c529ac2767a718497a698ac089c4037.nq.gz
│   ├── 9d28cca6b932dfad0880e0e7beb4c5e9dc06d52b.nq.gz
│   ├── 9feb65f936f456e3ad6371650093a723d05a3cf9.nq.gz
│   ├── a7f9396bd2061c06194b431c3c344bb25b21be2b.nq.gz
│   ├── b15836f8e0e506dc9ec69851eb19f482550a4c5c.nq.gz
│   ├── b3ce81534419224899155ea202079bef7e96c993.nq.gz
│   ├── bc4ce54c275f48dc296c83c9701d8a200c3bb600.nq.gz
│   ├── c1e73807371042f391e0ab90f25e2dcc564e625d.nq.gz
│   ├── c39f3948b075cfd90990d3e77f294d7974e8f905.nq.gz
│   ├── c3f5d93fd3126635ae1ba35a7ecab039a4b86757.nq.gz
│   ├── c73480cb18c08c4fa75a613d3a539750ac76973b.nq.gz
│   ├── c998af848392b5af853920e5ef09c8a173e3e579.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── e569d46eddc60823355ca7e009179463928c5d04.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7006184010bab9b33fb9cf5098317375136039d.nq.gz
│   ├── e7653ba47ccd111abf23205018825a8947eaf0e4.nq.gz
│   ├── f1e838ccc5b54d2a6e4fd37784af710ede61d432.nq.gz
│   ├── f23f4b4a3d9c0eef13267ec4c58c9b9c511cc1d7.nq.gz
│   ├── f59a369eae0aafec0ee19cd55e3501b44c375201.nq.gz
│   ├── fb1dc7294b0f74ac49d860f6652ece04c29ed1ca.nq.gz
│   ├── fb3f6f76a0bda609c4297c12bff72806f42a84ef.nq.gz
│   ├── fbff92385057249d727a03b6e98cfbed29f5108a.nq.gz
│   ├── fea02c315fea04a0633e66d525d6ed361049ad38.nq.gz
│   └── ff428683e3792913f822ec561512c18a627a6156.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 77d802d6b85728e6fddb3f8871c2fa9ba72ae237.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 76 files
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

[pysal/inequality](https://github.com/pysal/inequality)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
