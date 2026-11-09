# Repolex Knowledge Graph of xujiyou/zhihu-flutter

RDF knowledge graph data for [xujiyou/zhihu-flutter](https://github.com/xujiyou/zhihu-flutter), parsed by [repolex](https://repolex.ai).

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
rlex download xujiyou/zhihu-flutter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c1aaaac4c8e65001af15f3dd44ca21ec958ca31f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c1aaaac4c8e65001af15f3dd44ca21ec958ca31f
│           └── chunk-001.nq.gz
├── blob
│   ├── 00fa4417cfbef8673c47c86eb24033fcd97056a8.nq.gz
│   ├── 040c50ff961c6241fc7dceff304dc2721ee122aa.nq.gz
│   ├── 09d4391482be68e9e4a07fab769b5de337d16eb1.nq.gz
│   ├── 0ccc450011c409f7e19f9170c347c2ea744ae68d.nq.gz
│   ├── 1121a2aa3a3d956e1a03e86dfec3a32e4e298b6a.nq.gz
│   ├── 112becd13b363f8f2298913ba7b4dc35c0267e07.nq.gz
│   ├── 1263ac84b1059dba93f788b61ec40796285dab40.nq.gz
│   ├── 13372aef5e24af05341d49695ee84e5f9b594659.nq.gz
│   ├── 17987b79bb8a35cc66c3c1fd44f5a5526c1b78be.nq.gz
│   ├── 1d526a16ed0f1cd0c2409d848bf489b93fefa3b2.nq.gz
│   ├── 1e1aafd63360f955c24d9320054acd51c717e2b9.nq.gz
│   ├── 24db409cb4e12836593c56b8714354b213d7f25b.nq.gz
│   ├── 28c6bf03016f6c994b70f38d1b7346e5831b531f.nq.gz
│   ├── 2b509aef4a43ef840f8bd83eac6baec61678c077.nq.gz
│   ├── 2ccbfd967d9697cd4b83225558af2911e9571c9b.nq.gz
│   ├── 2faf00a7e6f9ba6b2c957c1fb94bfe967609e3e0.nq.gz
│   ├── 304732f8842013497e14bd02f67a55f2614fb8f7.nq.gz
│   ├── 36e15743564b136ce46a414e444f6cec7a5ceb10.nq.gz
│   ├── 39f20d479e0d1920ad54b7f6a9104d6dd300b06a.nq.gz
│   ├── 3a8422613c1c656653f26ca0f5a65a5147e0b321.nq.gz
│   ├── 3d43d11e66f4de3da27ed045ca4fe38ad8b48094.nq.gz
│   ├── 43a5bc7c405d10125aa21e20759e335e35926b59.nq.gz
│   ├── 447688755cf467774b3502a053ffc83b7f62b4fe.nq.gz
│   ├── 464fc5aa2a4dd85c6b96d66f20a843f4012d8d7d.nq.gz
│   ├── 4bd63a9eddaf1e097fd46a24c0d16a1efd40f217.nq.gz
│   ├── 4cde12118dda48d71e01fcb589a74d069c5d7cb5.nq.gz
│   ├── 4d6372eebdb28e45604e46eeda8dd24651419bc0.nq.gz
│   ├── 55ce90c79f14eeb7ebb365b9a3b8a4ccce0e87e8.nq.gz
│   ├── 592ceee85b89bd111b779db6116b130509ab6d4b.nq.gz
│   ├── 59683ebeccaef501a408cdd8735ec7fc4c9ec01e.nq.gz
│   ├── 59ba17e7a488c46d3b708f68648568b6f5fba026.nq.gz
│   ├── 5a2f14fb18f6e8b8c4308ff0f0dc187d9d27a5aa.nq.gz
│   ├── 615ecefa44b1db2d617fa27d4848298991ca8320.nq.gz
│   ├── 65b7315af1b601459e7f93940be2cad3462e2aa7.nq.gz
│   ├── 6a84f41e14e27f4b11f16f9ee39279ac98f8d5ac.nq.gz
│   ├── 6c2de8086bcd867b302f0be61285cc8936d1b14a.nq.gz
│   ├── 75b2d164a5a98e212cca15ea7bf2ab5de5108680.nq.gz
│   ├── 7727d89aa0bce19f578944d5efc91474cec3a870.nq.gz
│   ├── 78ae5ec681c82948370716639115c2df52d40c62.nq.gz
│   ├── 7a974ad101309a42856b13174158e3bb4606f2b9.nq.gz
│   ├── 7eb78bec0cb94157269d929a77bdf7fffd84ad2c.nq.gz
│   ├── 80080b71f29ffc7eac6b1ef9d52b4c3e8c15dd81.nq.gz
│   ├── 809f919d3d1b3a1feb044b6ae3c9f12444c3808c.nq.gz
│   ├── 80ba42b32046f80b638a0e3844128e1628f5e5da.nq.gz
│   ├── 89c2725b70f1882be97f5214fafe22d27a0ec01e.nq.gz
│   ├── 8a0b282aa6885fb573c106b3551f7275c5f17e8e.nq.gz
│   ├── 8bd86f6805108dec87d0be823bdb1384bec8aa19.nq.gz
│   ├── 8ce261c9c276cb017246adce0086f9f2ff3fe460.nq.gz
│   ├── 94c25e195c970735ca31308f25b9676e38ddc67b.nq.gz
│   ├── 9d82f78915133e1c35a6ea51252590fb38efac2f.nq.gz
│   ├── 9da19eacad3b03bb08bbddbbf4ac48dd78b3d838.nq.gz
│   ├── 9ff5703b153d7162000aa42c7389429109c6a822.nq.gz
│   ├── a1cef506debb10dc1668bcafc8ca52ddca93e2c8.nq.gz
│   ├── a6d6b8609df07bf62e5100a53a01510388bd2b22.nq.gz
│   ├── aa901e1e0db23cb2795dd59d99c63834c1cfd87a.nq.gz
│   ├── af17aaf5b6d411d49a87c237af273b73c63ff3a5.nq.gz
│   ├── aff1469ae3f7614228f0aea598204daa2d13e0d2.nq.gz
│   ├── b25b3bbe250303078ab7b2930837866eb4e96958.nq.gz
│   ├── b620a000114953d64a253783518c8a194be1e23f.nq.gz
│   ├── b89af39c5a024ac42c70e9a9c611aad284a8b3ad.nq.gz
│   ├── c4df70d39da7941ef3f6dcb7f06a192d8dcb308d.nq.gz
│   ├── c8f9ed8f5cee1c98386d13b17e89f719e83555b2.nq.gz
│   ├── cf210d213f278f6142c450e43cf7d7fbfe5caf24.nq.gz
│   ├── d0e1f58536026aebc4f1f70e481f6993c9ff088d.nq.gz
│   ├── d0ef06e7edb86cdfe0d15b4b0d98334a86163658.nq.gz
│   ├── d49c1c0223f105d8899fe87304f5dd27b27bccdf.nq.gz
│   ├── d5f1c8d34e7a88e3f88bea192c3a370d44689c3c.nq.gz
│   ├── d847532568363c612930ae9e8ba82045564d0a28.nq.gz
│   ├── d972441be84f24a816fdc0654902f6c7c64719b6.nq.gz
│   ├── db77bb4b7b0906d62b1847e87f15cdcacf6a4f29.nq.gz
│   ├── dcdc2306c28505ebc0b6c3a359c4d252bf626b9f.nq.gz
│   ├── df206ff1eb07f185f437bcbc519583946679a891.nq.gz
│   ├── e5c837191e06fa89372f5752564eab87bff82401.nq.gz
│   ├── efd01322db2986f5d562492d2f5e39d1d93ba5f7.nq.gz
│   ├── f091b6b0bca859a3f474b03065bef75ba58a9e4c.nq.gz
│   ├── f2e259c7c9390ff69a6bbe1e0907e6dc366848e7.nq.gz
│   └── f3c28516fb38e64d88cfcf5fb1791175df078f2f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c1aaaac4c8e65001af15f3dd44ca21ec958ca31f.nq.gz
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

[xujiyou/zhihu-flutter](https://github.com/xujiyou/zhihu-flutter)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
