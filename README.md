# Repolex Knowledge Graph of apple/swift-numerics

RDF knowledge graph data for [apple/swift-numerics](https://github.com/apple/swift-numerics), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download apple/swift-numerics
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0c0290ff6b24942dadb83a929ffaaa1481df04a2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0c0290ff6b24942dadb83a929ffaaa1481df04a2.nq.gz
│   └── repolex
│       └── 0c0290ff6b24942dadb83a929ffaaa1481df04a2
│           └── chunk-001.nq.gz
├── blob
│   ├── 0075d84b47da574042d652642097500c518a239e.nq.gz
│   ├── 0652d043b4c1c62cd77edee121d9b1ba8aa76eb3.nq.gz
│   ├── 07126fc73ed7c4f4ebe9ffb66fdc49d18e1961d9.nq.gz
│   ├── 077fb436f60bd9f428d5c7b18ede6addcd3726a1.nq.gz
│   ├── 0806fb4f7d8e2adb8cb724773b7d39854dd9cd78.nq.gz
│   ├── 0f379dbea797dd3bdd3187e3006e7972911ee46d.nq.gz
│   ├── 1a4138dd227d70e0d949b2f4eab2cfc732fea4e6.nq.gz
│   ├── 1b85910250ed62a69cbd1b234d02624dba966f19.nq.gz
│   ├── 1c88b5b3f68c4d31e2f56bd99c447b1d27b5984f.nq.gz
│   ├── 1dc1ee9d37f98612fc05ab84940254263705f522.nq.gz
│   ├── 2dd9b157c89164327a0f517ffc55d90ad415dca8.nq.gz
│   ├── 2f32b7111eacb0a009972d525f3ef6f18e4d1156.nq.gz
│   ├── 37275cc325e2cb32fa49d14c48e53d4c804cae61.nq.gz
│   ├── 38c8cdced4b3d3103a8a517444a316497ed4291f.nq.gz
│   ├── 46623c91313f8e23b2c1602ad46fbae4adac267e.nq.gz
│   ├── 4ed4dbd196b9725b9e0275e03f1a4f00f00dfa04.nq.gz
│   ├── 5929a7efc20b63466299bc9a61ef7420cfe63371.nq.gz
│   ├── 5a5d9fbe80e5db263ae258e0bdaef8f6c2ddd0e4.nq.gz
│   ├── 5e5a1b40a03b9bc8bd33277ac1a0dcc81b4e5616.nq.gz
│   ├── 61893362f10d030cd0044320c111365d7c761121.nq.gz
│   ├── 61b0c78195f2d00acaf658000eeca6ad406a3a29.nq.gz
│   ├── 640f8b94a6d95ab81b95ecb46eee2c0d1c10b01b.nq.gz
│   ├── 68fb20451129be52e29eaf1e2cfc3199fd1274c3.nq.gz
│   ├── 697b50b041dd6a76948582b0298f5935e8f23223.nq.gz
│   ├── 6a51c01a8ccd3acbc34d024e5bf7d75fabe41b19.nq.gz
│   ├── 7198461265a7c9e78a649993f6debf2e1a9877e8.nq.gz
│   ├── 8081e37793e9e6b9d535ff8ea7c384981bf6a116.nq.gz
│   ├── 85dfaf7bc56d2696270a5571edeabc59bfb0a2d5.nq.gz
│   ├── 897ee839d057a835d5d5adbda4c2ccccd5b32009.nq.gz
│   ├── 8ac212f325103cb325268116481aaf4686447b7e.nq.gz
│   ├── 8b7bf995bd7de35f4233dc2868788f38667c47b3.nq.gz
│   ├── 90a0a21fdc48953de55373a7400aa06081efab60.nq.gz
│   ├── 91e43618e4488d8bd947cfec9442a01f5416618b.nq.gz
│   ├── 94f73782052f03ff54f5b2e444da35e4d1dbe950.nq.gz
│   ├── 96c30790cfcc5ea9c109a68acdcd5c548699a6c2.nq.gz
│   ├── 971b8858ad9bba048ac9cb2764d35faa840b9e11.nq.gz
│   ├── 98e97e897c2636667450781ebca8200f69e4fa61.nq.gz
│   ├── 9b1b698231fab2d0bd58addf705a5d6a250cfe7c.nq.gz
│   ├── 9b34346519cd5f2b29f6abd9c0c6d0555e13fa4e.nq.gz
│   ├── a46c475d5a50e559d00cd40e827d5ea2d76f3401.nq.gz
│   ├── a4a219a9e42f7a55fc58693de16f353d5e9aa29f.nq.gz
│   ├── ab459bbf5598979c808743706d76e80db06d598f.nq.gz
│   ├── acc78da4ec164b07b41c25626dcc9e3336cbcdd3.nq.gz
│   ├── ae835441958bc437564f9f33c8f6d7fea7db44ed.nq.gz
│   ├── b4ca39b6276352ea78bcff25bf33c11479be5cd2.nq.gz
│   ├── b5179a04f3a632a7ed58f26e6a8beb31ec65b10c.nq.gz
│   ├── b6bd35a20c14491636f0aa091d89eebd5b5108ae.nq.gz
│   ├── b8f1127c85ff83ca4a9247120908c522d9316434.nq.gz
│   ├── bf0ce91728ade86fad5ca09fa9d697bf50340367.nq.gz
│   ├── c233cb7c4f30e73bf20534ee419da4b94ad02387.nq.gz
│   ├── c4c1f0819cd93c0d29c9ca3a021b6c7997639b3d.nq.gz
│   ├── c614028cfaa34bb72484a57b011edc8ed11ec908.nq.gz
│   ├── c6f4cb85f77281e44709ff0a5e9194a9641871da.nq.gz
│   ├── ca3714844f058ce73a56076bd323438a0d643a0f.nq.gz
│   ├── d08215179a3e183d5284d422563b01b58f6460fe.nq.gz
│   ├── d1c276bc9678597505e74233d53d1426bf475b90.nq.gz
│   ├── d41113e35467f0c485e23f43dd1279bcd0b0daa9.nq.gz
│   ├── d59043b75679dfbf402492095f2c23eb3027a7cf.nq.gz
│   ├── d9de275962f4095a2131af08babbfbd32a096b29.nq.gz
│   ├── dc60ec04383a139c9ecb7032a0d5ea3cdfd2b31f.nq.gz
│   ├── de44752e03e6b97766ec37018fc7389762aef7e4.nq.gz
│   ├── e184fecac2fe29476ad48570fca095186bdf93d8.nq.gz
│   ├── e5dabaac6a29a7b842e337d4e2cf3913ed24cb5a.nq.gz
│   ├── ec314adf8b0651293861df65f148c3cc0b60f74e.nq.gz
│   ├── ec42cef8df2b19a864ae9d043c96f05b6a6a06bb.nq.gz
│   ├── ecc46538441416a9f110cd33f9783ceaae8eaf24.nq.gz
│   ├── ef3e9a3bd9dfdb074bf0b757c5f8b86e6d7f3a0f.nq.gz
│   ├── f1565e34a30f7b60ef3f8217ba7eb6a1f0542f9c.nq.gz
│   ├── f77ecd21cd1b214998dbaec6f214df13d28018c8.nq.gz
│   └── fd76bd2c824b090c8cf504e9f46cde04b9280e5e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0c0290ff6b24942dadb83a929ffaaa1481df04a2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 79 files
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

## Source repository

[apple/swift-numerics](https://github.com/apple/swift-numerics)

---
*Parsed on 2026-04-20 by [repolex](https://repolex.ai)*
