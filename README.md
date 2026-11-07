# Repolex Knowledge Graph of huggingface/dell-ai

RDF knowledge graph data for [huggingface/dell-ai](https://github.com/huggingface/dell-ai), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/dell-ai
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eead83fd703ffa70b5c19ebd847b8ade3bf162ca
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eead83fd703ffa70b5c19ebd847b8ade3bf162ca
│           └── chunk-001.nq.gz
├── blob
│   ├── 02d8a760e2c429bf79375a2a25fa13d4b1e03694.nq.gz
│   ├── 054a6fb84d98ceeb30198ed81ad6d4651e2b4c4a.nq.gz
│   ├── 0a4673d89aa2e6c5c56bd6646003db8be0a42567.nq.gz
│   ├── 0af16c9dca9ad40b9bc6772f53c591a698489ff8.nq.gz
│   ├── 0c80d5e040c0c8ef6a756c37cc567356793457f4.nq.gz
│   ├── 0cd7d8d99dbc1321f456d886bdc8df32711e2f8a.nq.gz
│   ├── 108c5b4195e398f5fb523a2201fcf470d5dff50f.nq.gz
│   ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
│   ├── 1652b564ac82410d65ef31370b7d45f09551e615.nq.gz
│   ├── 17dfcb52f73970ba6ceb968717ccd97c8df05876.nq.gz
│   ├── 190a9908280a1fefd9c007fbee1c43caed3346b0.nq.gz
│   ├── 1ee38725e679db2f989a12ebdda6b3b6b4c29e82.nq.gz
│   ├── 1f1f5a990cf918e997b1faf1f65cbcd0f07852a0.nq.gz
│   ├── 1f3729f556e09aa7e8e2bd19f087d20299215215.nq.gz
│   ├── 2064b0c674463fd68e22d0a775ae52f3d0c97622.nq.gz
│   ├── 2335e2c8a299f6715ea2202a84be74c6ddfbbac0.nq.gz
│   ├── 242402b676c5729810011e6109bec84d70614f5e.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26b09b7e80b390df739883c59b78761b7b9210f1.nq.gz
│   ├── 26e353de2b859e4ca9e744fe28e2e492794ffbc5.nq.gz
│   ├── 26fbdf7859959b18ea986e60bd96213be41b5fee.nq.gz
│   ├── 28049214fc1874a46adb12fb22eb8963ab56952d.nq.gz
│   ├── 2aea730e2097bc42204b68d08398ba35528cac7c.nq.gz
│   ├── 2af813a6230f65507ed59daf307a4b2b7450f6c7.nq.gz
│   ├── 2bf4bb1df0ccc7a8e8dc1a4af7512285c881f93e.nq.gz
│   ├── 2cbc2ea8739a0b0c3f0b86a290578e8eeff0d609.nq.gz
│   ├── 2efca0efceb93bd5469f46799594323ce3f5c0d5.nq.gz
│   ├── 31d9a6bd70038d28bc55b3366f97b1e1e77c31ef.nq.gz
│   ├── 34026d1d4038f7f25b9d2f2518ef34d9e65c72c8.nq.gz
│   ├── 340c6b1ffe353ddcf4871c9a3ef18b2f15ca0ff2.nq.gz
│   ├── 3758b109044582446cc2594e2f60aadb19c66a2c.nq.gz
│   ├── 3a22fb4e93e325d5327fed6accfe3f1dbbf83cae.nq.gz
│   ├── 4221c063e57e5d4d960e068b2efc512989038285.nq.gz
│   ├── 433f513dd7e237e495d3fe37c8bba8f082d3a509.nq.gz
│   ├── 461644f89aaea0476147d7c826fe6693049a1244.nq.gz
│   ├── 46311f6e098ee8bb276993d9439dcf18c1b8965e.nq.gz
│   ├── 4967a2a2cd037cc717767c07874cbf7aa3a772e8.nq.gz
│   ├── 4ad49b35dc0cce8161ac517cf069342aa426ce65.nq.gz
│   ├── 4dd7de1cf1020cf9542399898f1e7b5b2f092888.nq.gz
│   ├── 4fa98bec5ecf46b4e4738770c53ba3d0b608f93a.nq.gz
│   ├── 51c860fc09a9018edcfa6f2ee17b21e0e8fb0606.nq.gz
│   ├── 59c1d8ac416c414141e2367cde485f83b4a2b82b.nq.gz
│   ├── 5b99634d80695366e5ac8a7efb57a2c4b9d19024.nq.gz
│   ├── 5d1d901e116a0ecc8650170bc2743d60a1b29733.nq.gz
│   ├── 5e155b177b8f1c66c801f9acc34f4d10a15f4776.nq.gz
│   ├── 621dbd6ee0c8a637e9a0f166f4bcecd71194a00c.nq.gz
│   ├── 62e4cc35b26835cc17c5bddab2394b1cefc5c8b7.nq.gz
│   ├── 63dcb6413de782782e89ef4697950e404611ee97.nq.gz
│   ├── 67206882d304c9a5d622802f6a41fda35ad43a22.nq.gz
│   ├── 6cb48caea257b4aa5270fe55478d5db9d697af14.nq.gz
│   ├── 6ea3f1b58f475d94612be3ced5a5bc1526edf5ea.nq.gz
│   ├── 6ec867dafcc544ee7e99a0a6935f1ae1b6230a38.nq.gz
│   ├── 6f339ce6cd2e73a1b0a0b97ed2147290b4b05839.nq.gz
│   ├── 74355e891597e4b7395485f6f6d97045d98c8e49.nq.gz
│   ├── 7444b5c278f62e868dec41e9b999a4fdd3a97456.nq.gz
│   ├── 752c6e463f336be77dfae7045cc3eeaa357791a9.nq.gz
│   ├── 78a652b8d42237bbc79dd59d9792c970ae41ffbb.nq.gz
│   ├── 7b366796035ba872a485602fc2c6e18a73fe3718.nq.gz
│   ├── 7f3e2106bb5843b3504a6048c1d1a2ef3193633d.nq.gz
│   ├── 7f9efb5e19ca5b4173780a70863feea4d0b81a84.nq.gz
│   ├── 8095ef0b81d110942376af6a075a75d13e1cdcc2.nq.gz
│   ├── 8654677cade1ed3fe1998450e1243678d1b0c0da.nq.gz
│   ├── 8703319c882e238674fec9204c201915707d1ca5.nq.gz
│   ├── 889804cc53a21fb894cf32adb36166bf75df6af0.nq.gz
│   ├── 8a5fce73ecf347b3e3ffc60ec9b205b536d98fae.nq.gz
│   ├── 8aab09fc7d00d342d72bdecfb2c8b8b7cdb7f4f2.nq.gz
│   ├── 8d4775cd353348555e2197e7a8a7a8d9f85347c0.nq.gz
│   ├── 8ebe5edc951a2117639ef7840f3032ea699bc4f5.nq.gz
│   ├── 910ccc1ff200988906111728b89da75eebc241d6.nq.gz
│   ├── 915127ca3b245eddcbe56c6ccabea54c5e9e6fae.nq.gz
│   ├── 92dd72c9e6d004ec336b33fb6f3536ff088fca11.nq.gz
│   ├── 96da51ee5fcd67f816becf4e3bbd5def17509cb0.nq.gz
│   ├── 984c5d16ad13cedc16fb7b7b67d3dac440025f34.nq.gz
│   ├── 99637209109a1c78113d35e61703910417bb467c.nq.gz
│   ├── 9a2fe282f43d7d026472dae62132d24a9cac44f5.nq.gz
│   ├── 9b41bb8b1893f708f599615d51101143a82bd0de.nq.gz
│   ├── 9d5e944b048eaad2a20971d5d05991b7af63f758.nq.gz
│   ├── a1cfd8c0288be390400de747f55de6410454ac15.nq.gz
│   ├── ad836ff354f775bdc9f3bcb9c1810af83d748f7d.nq.gz
│   ├── ba8c59e307daf2086ef5a385c2703263dcf709f1.nq.gz
│   ├── bca5d936c2995e76b3cc6de13ab783ec1f8e2425.nq.gz
│   ├── bdd665904ab5f4ad1ee71120853e9340d5b0a431.nq.gz
│   ├── c011dc7aef8b99985b4dd6b5978313a0ac923c45.nq.gz
│   ├── c6d2d640e17f10c3b5b005ef1e9068a308233cca.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── c98222472861ddc3180b54755c723dd66f7bfee1.nq.gz
│   ├── caa1c7cb3fbd5d44c257be3385d2f8b06e8418f6.nq.gz
│   ├── ccfa449443561fc2984428a02ccc0263fafe704a.nq.gz
│   ├── cdac3168032771ca476149e83cf32d9b460c6882.nq.gz
│   ├── cec430a60e5cdafdca0fe34c55f2c49822373b17.nq.gz
│   ├── cf7de47048ad3096661d517dff9da3dc59a3facf.nq.gz
│   ├── d0c010fd6cbcbfadb41411c00a9b61a802682d43.nq.gz
│   ├── d6af6d2a24ca9036339c1d7dfa4bfa27a21fd64b.nq.gz
│   ├── db1e0633761eb6cfd21ebe18255a839cb2648c38.nq.gz
│   ├── dbed94bc8c902d6a92fd7f19185b3a480a7e6c38.nq.gz
│   ├── dc25ca6c36acd51871f578b8ab8c8b5b50b8055d.nq.gz
│   ├── df0eb930b2d62d8f2ed3a82879aa9f1233ade314.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8d5e0a5c961ffc4973ac48e9c0615a14222f325.nq.gz
│   ├── ea9f79b0c0cf171d62f278892dda5a45dbcf6d97.nq.gz
│   ├── ef0b2d84cefc053a4bb702cce6bc40dd4f772bca.nq.gz
│   ├── f712b736fbe520a528b481016adc08ec2929ca59.nq.gz
│   ├── fa9dffe0c23f789852c10f08d120d36cde577e93.nq.gz
│   ├── fb09ea28307f9caca996c6422701d4b2aec4f41c.nq.gz
│   ├── fca759b4d7c84e9f80f17a99e79754f8554a4e8e.nq.gz
│   ├── fe110a6d7a63a75c8993504587b9c8dde22c4642.nq.gz
│   └── ff7b0827348c6b4a867a5cc51d024694e47db3ef.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── eead83fd703ffa70b5c19ebd847b8ade3bf162ca.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 115 files
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

[huggingface/dell-ai](https://github.com/huggingface/dell-ai)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
