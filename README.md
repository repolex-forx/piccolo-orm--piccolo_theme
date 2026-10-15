# Repolex Knowledge Graph of piccolo-orm/piccolo_theme

RDF knowledge graph data for [piccolo-orm/piccolo_theme](https://github.com/piccolo-orm/piccolo_theme), parsed by [repolex](https://repolex.ai).

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
rlex download piccolo-orm/piccolo_theme
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d6fad398aa609e39464143a0baa1f6deff918d68
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d6fad398aa609e39464143a0baa1f6deff918d68
│           └── chunk-001.nq.gz
├── blob
│   ├── 04cb2f13de355c3938c28c7c2c14d2219aec9ebe.nq.gz
│   ├── 083df158d0a29d61efc3fcbaeb0f8f1071ed06ec.nq.gz
│   ├── 0d617370bfdc6940873d41c93310d3fc903fd124.nq.gz
│   ├── 0df77588fe1337648968ee3c7aef62ad82ce7a68.nq.gz
│   ├── 13bb7e40aec5fa502196f54f56fd8566f070b3ee.nq.gz
│   ├── 209203ab78ab8367ffdec1cb5f67e89d100b2993.nq.gz
│   ├── 2667849121173044242f2a1715d748d31b33ad60.nq.gz
│   ├── 2b3aaa653ca2a4f087ce644a9dddb64aa3cb777a.nq.gz
│   ├── 30416eb55c6c735be21523ebed161871a9488fb0.nq.gz
│   ├── 332d772fb258a9873aef20cc810f683020a4111e.nq.gz
│   ├── 35bad64d4647472d0c73c59aa9c13dadccb331a8.nq.gz
│   ├── 374b58cbf4636f1e28bacf987ac2fe89ed27ccba.nq.gz
│   ├── 39cd5a6f03cf8fb56bcc25b6a20c5afb8db01cd0.nq.gz
│   ├── 3a758afd6f1a88fdc3a1c4c323afb45ef23036ad.nq.gz
│   ├── 3adb797e7135fa9793a5b0fcbe45edec68825513.nq.gz
│   ├── 3cb99c85f3848f7ae9dc89215fbbcf1bbc066956.nq.gz
│   ├── 4618efaba42dd20662eda1247a25f3ae05c7e5f7.nq.gz
│   ├── 4c03432b904874728ceb227a545125844b542026.nq.gz
│   ├── 5219105a1e2314dc26ede8095699270e41ef2261.nq.gz
│   ├── 57ab9df20f3ad01ff42b6fb772a91518032f9709.nq.gz
│   ├── 580b5aefd1ab2db292d92c9caf1d0c563e62a263.nq.gz
│   ├── 595f902d68935d83d57867dd7db0cb06c6caddfa.nq.gz
│   ├── 5ed9cda7f89bd7fe287d85d870c288fd65627334.nq.gz
│   ├── 6966869c7054c18810eb323772b93ba5a42cefc5.nq.gz
│   ├── 6ccbe66adea5d3758e643e3ff2f32fdbb03f570d.nq.gz
│   ├── 70e5e33746f9915bf43872889e5f3e696fccab33.nq.gz
│   ├── 719979294248cc489ad409e0bcf82b66c9a4ee79.nq.gz
│   ├── 73a6bab0a70be563482f6fde2641d645caad30b3.nq.gz
│   ├── 79ca680bff530d6cec16d4a11ab4241944c11870.nq.gz
│   ├── 7aa6eafc4a444ffb110e9966edde6fb6d119465a.nq.gz
│   ├── 7bbc8bb57eb419fc8557801b44826e24c5061904.nq.gz
│   ├── 8054c4eb1a066a598dd3209fda00cdbb981ac435.nq.gz
│   ├── 86879a54e75ec91f9fb40eeacc74d55966f9f8e3.nq.gz
│   ├── 883f10c196d115e1b90e4a53c744c59f04fe6c16.nq.gz
│   ├── 8a565ddb5254352114d12e96da076b2ab673f05c.nq.gz
│   ├── 8e9e4a85b3abf2c5131647f23722854ec2fa0c85.nq.gz
│   ├── 8f5146aa038f22b996db4b503716ffec08fa1292.nq.gz
│   ├── 9658d3ca85f03791687d8cbf007e61a80a5adb09.nq.gz
│   ├── 97db4cca9a21927cf3c520745f70ede1e5ab200d.nq.gz
│   ├── 9e69f6d1a0ba027ab480c536dd4d7887d5735a58.nq.gz
│   ├── a7161ba1e8b978359de17d8ff8624825ff837689.nq.gz
│   ├── a9f588cc1b1ca1bc6bd5a37828532abacb676dfc.nq.gz
│   ├── b2acae4626b196cf6aa9aff9634abd9b53cd446e.nq.gz
│   ├── b749a053ae83538ca342ee1aa9b558ddde883b1f.nq.gz
│   ├── bf36d744c4798c4c4e4a399915dbe64bd828199d.nq.gz
│   ├── c4bc4825b231f9810676fa1d68d2e987ad49d45f.nq.gz
│   ├── c6c1fb43463988b393690cfc9dad8a059db5d3bb.nq.gz
│   ├── c754a6872fa6d5f0ac1818bb5d0fd77eb391e130.nq.gz
│   ├── c7ec6ac6e4fe8453514c27de44e750f7a157172b.nq.gz
│   ├── cbc9eec1fad312e2b36c9bb40e9a6625007cf787.nq.gz
│   ├── cc4ec7dca0723f770b2b3e0764a6383f2407cef0.nq.gz
│   ├── cca8607c2abc53d7326f7a93f5328bbafc49aad8.nq.gz
│   ├── d59081604cc3e99c595f30732d3b883b32ca19e4.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── db9b8c2bceb96c77b96bd146320e7ec6b5be4841.nq.gz
│   ├── de1817e8aecf8bde036782d26697a0cf0c248846.nq.gz
│   ├── de57c7b9176272f13816fdc47ef13cbed029b754.nq.gz
│   ├── e8c58530160a72acf891535cd5d792e83565fed7.nq.gz
│   ├── eb7eb9d483082852c24878280d2939bf194a1322.nq.gz
│   ├── ed8b5520cabda5a8856fd0cf64afa7d72be193f3.nq.gz
│   ├── eddb9476b8ae43238ccd2ba5378872fcd89ae967.nq.gz
│   ├── ee230164dec3700669ff5ffb775aed068d3793ea.nq.gz
│   ├── f0ee1fd9b08db8ec7b0a0d17631a5de18f88718a.nq.gz
│   └── f94a28737b19e2dc11d5e0c0b9101540de156fb4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d6fad398aa609e39464143a0baa1f6deff918d68.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[piccolo-orm/piccolo_theme](https://github.com/piccolo-orm/piccolo_theme)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
