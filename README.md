# Repolex Knowledge Graph of graphql-python/graphene-sqlalchemy

RDF knowledge graph data for [graphql-python/graphene-sqlalchemy](https://github.com/graphql-python/graphene-sqlalchemy), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphene-sqlalchemy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4ea6ee819600d65ad784c783a68321105a643d76
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4ea6ee819600d65ad784c783a68321105a643d76
│           └── chunk-001.nq.gz
├── blob
│   ├── 099e9177353858f36ccea1b5e418e34b9d78940f.nq.gz
│   ├── 1066020c841eed93f09bccc1f03324be6e6f61d6.nq.gz
│   ├── 14c87f74b8a56f11f2f92ec8a26afe6feee7f566.nq.gz
│   ├── 168a82f99a3b859b88d59c27c6de70af822cf6a5.nq.gz
│   ├── 17d774d225c77ac19485db7c23865dcbcfa303c0.nq.gz
│   ├── 1b22956b2a9cb68c1266b67f3e1fb4b7d5ebbd76.nq.gz
│   ├── 1c86b9be8437f2c6b9fcf316fc8e27d79a9196c0.nq.gz
│   ├── 1d8830b60dfd26226d1c708d5775f7e03c45792b.nq.gz
│   ├── 2013cfbb06154c8be9d620d3412d59e4bca0849f.nq.gz
│   ├── 220b7cfb282c09fb6a1b3490c5187ab841c9e44a.nq.gz
│   ├── 237cf1b0f92c2d5bc09a4a6b920898750baf9e78.nq.gz
│   ├── 24650e8597e62edd3309ebd600732b319f092c4c.nq.gz
│   ├── 262e760814216b29463d6cf6c23026f4b44d9667.nq.gz
│   ├── 2728cab7f528d0ed5c48e930261b9e2b93a34f81.nq.gz
│   ├── 2c749da7258db593595a72aeda0d00a22ca54470.nq.gz
│   ├── 30ed9526ccb27aee6ba7c23f831685cc09d6dc08.nq.gz
│   ├── 321e5ca09d0fec5a6ef31f33007b48e5b9491a93.nq.gz
│   ├── 33eabcb6e357351a0eeb541e05f6520542849ebd.nq.gz
│   ├── 38f0fd0a4dc38349c227c3f0d33fe63e083c5db3.nq.gz
│   ├── 3c4c135ef152e9e9191b08fc25a47c5832a82bf7.nq.gz
│   ├── 3de6904b8b895c690129329d9d189913f0bea2e3.nq.gz
│   ├── 4245eba806bcef5098f6a6f1b5310a40351a9b83.nq.gz
│   ├── 4e61f96cf4928b886cddb3ff8456ce9d5ff96533.nq.gz
│   ├── 5876acb53b78780f88f4b8f385dd85c7b1aebc4a.nq.gz
│   ├── 59ca64dbc032fc1c6a37df1c5d6e04aee29dd2c6.nq.gz
│   ├── 5eccd5fc69c8c02fc999688b94ba892f6643e219.nq.gz
│   ├── 617d4872da8e704f87098f334d3c60067f3f6bb6.nq.gz
│   ├── 64d305ea4f18e5d2582be6640a3bf27554508b3a.nq.gz
│   ├── 6502412fe3619216ce552167f9e51e5eab5ccbd6.nq.gz
│   ├── 66fe306b65a614c32f5cc6452cc85c418c14adaa.nq.gz
│   ├── 69bb79bbd81ca029d8466de39fb9c6f80e61d20c.nq.gz
│   ├── 6e09ab00b51955eeae7454c57ec1e956640c35e1.nq.gz
│   ├── 6e843316f160687ee82910ae3da8fd3aceefe043.nq.gz
│   ├── 6ec4699e1de4d455e339ed281acfc0ff2dc84daf.nq.gz
│   ├── 731d7645db86c2d5a3edfced5208bd29c49410bd.nq.gz
│   ├── 74ec7ca9df13b8b221326fb7bc022403b9a370a8.nq.gz
│   ├── 753282809e6c3c707c0049ad567e1b8ddd5e3ecf.nq.gz
│   ├── 7b733c7623e2c5a8d201c630b23491f7488335c9.nq.gz
│   ├── 7da67c312400aac81cc303e1b315771147e1e6c5.nq.gz
│   ├── 7f4c507854df908c65ad77e1e4c377a1079e2351.nq.gz
│   ├── 879520f637eb7207cf0b46dede2ded6d1e4f895b.nq.gz
│   ├── 87bbceaef61ba8a4578ecc0841542921b227e062.nq.gz
│   ├── 894ebfdb71ad30441bd1a2479ac9d299297c3c70.nq.gz
│   ├── 89f444678961da8b16cc3efa3c98aaae4133036f.nq.gz
│   ├── 8ca6a45c6a5d9ce8287a92df10721aa7e29dffb5.nq.gz
│   ├── 8f6522f7f44ce9fc57a86c3ef0c37d0b0965357e.nq.gz
│   ├── 97f8997c080fcb958b2d288be1d0b311da6e7957.nq.gz
│   ├── 9fed146d11849dabb65bb0b79de49a4ccf123c5d.nq.gz
│   ├── a3c843c2f839d1d62f429ed5eeec550d38eea7c0.nq.gz
│   ├── a3ed69ed29bad8a33ad4cf38ffc9a07e3a6dcff0.nq.gz
│   ├── a3f6c4aad4d0843e85f7d6f619e0ae268f628563.nq.gz
│   ├── a72e75de5fdce7d6dc72d7eb175c24296fc94764.nq.gz
│   ├── ab918da780eb060f0b633ff0167a69a8b1c6d4ac.nq.gz
│   ├── ac36803ddd3ec71088b83adefd8c971a78d46f66.nq.gz
│   ├── b433ec59cbdb0ac7942a9586ff9ca4ff3453fdbb.nq.gz
│   ├── b55d5dabc2d61217e27b33e4b57d5d8f261cb40b.nq.gz
│   ├── b959d2219d687fe034eb61147b84961d642aaed3.nq.gz
│   ├── bb530f2cd53a1fc94f26e110f93af41d64d88276.nq.gz
│   ├── bfe17d9a2599fa0962c29965b653a5cccd4cfbd7.nq.gz
│   ├── c4a91e634b850cd9c61570163f76034dd8817232.nq.gz
│   ├── cbe3d09db1f4e09f188f849c806947e2f6d9d2a3.nq.gz
│   ├── ced300b3c621f9041305e355e043c118223654bb.nq.gz
│   ├── d08b4844e1e5ef44d790204d177b2d9ccbcf6ce2.nq.gz
│   ├── d7fcca9dbcc50e454ff32e927cb117e1cadce857.nq.gz
│   ├── dc656f41b3572e140ae08276f753305a8bd9f7ad.nq.gz
│   ├── e0803895e52773aebcb7f7fe8917be294f3de8cc.nq.gz
│   ├── e0f5d4bd0ca28ba9ed82e2e27b4038f29b7c1771.nq.gz
│   ├── e1ee98582122bd1820959702cb0fff9a47b532d2.nq.gz
│   ├── e479585c8b542dfc1c4390c709a6e0fe52bd7fb8.nq.gz
│   ├── e54f08b11905628bbcc30047689c4ece9bf4bc29.nq.gz
│   ├── e62e07d20041d5b96a8cc1355b95a3a8eedfd1a1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8e619116436e9b18a410442453bffe49cb64cc8.nq.gz
│   ├── ec36544407238c78b7150781f5b0f14da5784118.nq.gz
│   ├── ef798852dd091db2696cec9fa67cccd54d9b5bee.nq.gz
│   ├── f25b0dc2a7ebf446b1b43c08ed375a6c50a82769.nq.gz
│   └── fa2c13aef0683dfc3d41f03605015ef79c04238d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4ea6ee819600d65ad784c783a68321105a643d76.nq.gz
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

[graphql-python/graphene-sqlalchemy](https://github.com/graphql-python/graphene-sqlalchemy)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
