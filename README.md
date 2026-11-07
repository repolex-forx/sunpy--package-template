# Repolex Knowledge Graph of sunpy/package-template

RDF knowledge graph data for [sunpy/package-template](https://github.com/sunpy/package-template), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/package-template
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 983c9114fb6ae1d4aab1b93356658b3669795cc6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 983c9114fb6ae1d4aab1b93356658b3669795cc6
│           └── chunk-001.nq.gz
├── blob
│   ├── 019752732ddeba375406daf5671af87439969133.nq.gz
│   ├── 019bcad551dae7d938e40ab0df49185add5fa12a.nq.gz
│   ├── 042a14edc8b181b004853f273371c3576c37ff22.nq.gz
│   ├── 06384f0c445bb6f45697e51838840d85d6d312f6.nq.gz
│   ├── 0dfba156172ab708bc47e93b1662a643965052bc.nq.gz
│   ├── 0f21137bd3c0cb0a76b503e02239c4fde0ae5560.nq.gz
│   ├── 14513a1ef69eecce0d217b0da5e37117267ad781.nq.gz
│   ├── 1a55c5efeb0d7e66bef2e7dc71cafb2771b8f518.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 2140b1c29df0d36a7c367603b000f892cd758e8f.nq.gz
│   ├── 22327605e33ec7c54d1fdbb23043a489892879f4.nq.gz
│   ├── 2471a1546e53cc4f25bf0101c97ea397e54872ef.nq.gz
│   ├── 26d1989805516acea84df2ac0cd98d2640a6e04a.nq.gz
│   ├── 2d17646be9ae18bfaa8c8a760d98ebc9603ae29b.nq.gz
│   ├── 2f2454d152782c80db133ccea831b03ad7921a45.nq.gz
│   ├── 2f2cad07ffc6d927aa493db36c2ce9c08449d467.nq.gz
│   ├── 312a52f2a83bcef0fe348b31bc8b5216c5eed8db.nq.gz
│   ├── 347440adeae3a2ce137513e7ede33b21c029c765.nq.gz
│   ├── 382f6e7693a2a0f3d078984f7e227a8757462a84.nq.gz
│   ├── 3b980e92a17db03802711e51b12cc9f53c6efb0a.nq.gz
│   ├── 3ef453b86184e4cc8a71121c5f48bbcac9ed24cf.nq.gz
│   ├── 457c9753d5593fbfb3b5a7aafacf24d3c375d5b7.nq.gz
│   ├── 4d4ed0fbae99c908d3902a39fa8b7a5785e4259b.nq.gz
│   ├── 5349f11e9c74b621d08781eafbb5f5dbebe58dd7.nq.gz
│   ├── 544a2dba78d51ed662a71e941aac2b984933725b.nq.gz
│   ├── 5d11e05453a6db05f624bee0eff811c40a43dbff.nq.gz
│   ├── 5e85d66e82cc3e77b0db096b361e87227ce268e7.nq.gz
│   ├── 61ab4d6e74084cf2d2ff43119e444aa91fafe1ac.nq.gz
│   ├── 621b0a7cd2dbdbb2d3c7af0af2a7400603cfb3a3.nq.gz
│   ├── 630550523f722c4679631061a7a632d05e5791bf.nq.gz
│   ├── 643e7254bec57e2d880307151755a0b667515912.nq.gz
│   ├── 65271ccd7d4054b3ba96d8b2682e7299b125b92b.nq.gz
│   ├── 6708c165a9f60781b6876dd5b185516626d3c4f0.nq.gz
│   ├── 67b82f693f53cef785f9750c2c65c0bc3c191c8b.nq.gz
│   ├── 683dc31504b919d6f0edc67b76e866c2672a1794.nq.gz
│   ├── 6ece151a3e9b434dee07712f0fe35eaa0e4ce95f.nq.gz
│   ├── 6fc78d89168f8a1a95c265d1b9b59840c2a37886.nq.gz
│   ├── 7499bb19ca2e36c1e39e436617fbd0430e2370fe.nq.gz
│   ├── 79183a10f68f0e9358958edd409f6a158a741e54.nq.gz
│   ├── 7d388e3ef17b14d560a2a08fa3004807ad0bcbd5.nq.gz
│   ├── 7ebd631fa3f39e327a0edf54e44055a485b40e4b.nq.gz
│   ├── 86d71b2e21ed47830669886e67ea6320aa63f78d.nq.gz
│   ├── 8f8301c723e02a851c200f71a04115e0f6437c2b.nq.gz
│   ├── 8fe09b731963a1272a62a3360bbf019ea563aef2.nq.gz
│   ├── 92ea707303e3d1f4b6fc3bb3446d173c4f8d3c10.nq.gz
│   ├── 97364337f2b6b3f24b89c4db50bd9f96539ca060.nq.gz
│   ├── 988debf51060eb223212788187f60b37891ac768.nq.gz
│   ├── 98f1c8dd455226e40fe9d13bd2753ab7e5a1f912.nq.gz
│   ├── 9f5a411bb75cfbf489fd2399c44e940d352223da.nq.gz
│   ├── a1e90cf018bcdbee79969db2f13d80792151fbe9.nq.gz
│   ├── a3678c42ba4e535aa6fe8a762603275a4319378c.nq.gz
│   ├── a3b2a379d6a7117f0a899970205c32746b19e364.nq.gz
│   ├── a921a1566d587432f79fbab7a48fb8cc7351efb7.nq.gz
│   ├── a9689a4e0e65461db8a0c720cce08b3d11c6ca93.nq.gz
│   ├── a9d552a6f70340e03a7ed34953ff7a024d310964.nq.gz
│   ├── b50c24dc36e03e5913494cedd5afc4f18c13f803.nq.gz
│   ├── b5fb97afee3d26260afa6d0eb671205123973319.nq.gz
│   ├── b66a0740e1ecc20b4121be469509704a3a06a636.nq.gz
│   ├── bf4ec7ce5e2f9b67e8594982ee40ae9f1bc6727d.nq.gz
│   ├── c015d4851fed58fc2858d44633416ecfbedf9208.nq.gz
│   ├── ce1463fd8570ca1841637f7252c97e8c98fd4666.nq.gz
│   ├── d495075d1fd233e3d29052cb9173b0e2ed97fb43.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d621c671f1672ed327da945b2f71b5ce11e2f512.nq.gz
│   ├── d67a24b0d91309e034a17e343aba1337ce1f84fd.nq.gz
│   ├── db836bcd0e261d985d91321feeefc90258bef134.nq.gz
│   ├── e38b3a8dc183cbe2b71aedbaf793b8192981ce43.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6c031b075d6b92ab6a8d0fd6d3855ea85c75b38.nq.gz
│   ├── eb1219515cd1f83e46ebb9f26d5def7f24c8d0b7.nq.gz
│   ├── eb146b1a4737f1b468cea6558ffd5ce80c4e36de.nq.gz
│   ├── ed17d00f9ed3849070403dcc8648cfd5c11d1c46.nq.gz
│   ├── ef1df75f9704a13d3a74527029d109a4b17e357a.nq.gz
│   ├── f2b1236f9ee9891027799bfa30e7fca0f84f5455.nq.gz
│   ├── f526cefab90d59941dc9b74e92356f0feb62c154.nq.gz
│   ├── fd9969562d6990bf5436c0d680aa7df9574bea00.nq.gz
│   └── ff56309acec345fd633c51b011ad10b13cccd2e5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 983c9114fb6ae1d4aab1b93356658b3669795cc6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 85 files
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

[sunpy/package-template](https://github.com/sunpy/package-template)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
