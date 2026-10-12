# Repolex Knowledge Graph of datasette/datasette-comments

RDF knowledge graph data for [datasette/datasette-comments](https://github.com/datasette/datasette-comments), parsed by [repolex](https://repolex.ai).

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
rlex download datasette/datasette-comments
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f381d9618927d10a0e1c127a5a9ec67cc9f218a9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f381d9618927d10a0e1c127a5a9ec67cc9f218a9
│           └── chunk-001.nq.gz
├── blob
│   ├── 01406fe00fb926a64bf91e4261af87dd259855fd.nq.gz
│   ├── 03313571806e2385130c22c73cd3736f2b349d25.nq.gz
│   ├── 03372f4e0a5f5dbe54f54657780c756f2950c8e1.nq.gz
│   ├── 07081644a9f0f122315a40862c07fa1732df0fd5.nq.gz
│   ├── 092051eb37563918027a75a26ac1183be3bc08d5.nq.gz
│   ├── 095eaf11c3a14a06f210274a020b155664375b17.nq.gz
│   ├── 0a63494cfc432701056acbde53b3fa60d2881321.nq.gz
│   ├── 0c8f051e8ceb411bf2203a3e630e75d49331531e.nq.gz
│   ├── 0cf2e3c5ac02e65a54760f89250cc81ba32f638a.nq.gz
│   ├── 0fbeb87d22e6e7ed0dbd6c3ba25f1e3db7faa708.nq.gz
│   ├── 1ddc33b13dad8a364a9888db29852ebf9cdc97f7.nq.gz
│   ├── 1e03ccfda5a750e678b1135af74ba22cf9e796a3.nq.gz
│   ├── 21d2e60c8059661f566f538cc6e1ca5fcb0203ab.nq.gz
│   ├── 251cece38af5a41eda012611747056524bc751ee.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 295a67ee57d96a9a4be997c83147e1bc3f59098d.nq.gz
│   ├── 2c00fd5451cd66efd86316dc01b091080c639475.nq.gz
│   ├── 2c4a92a3f2aa7c1b537952c29e4be7c9c74b07f6.nq.gz
│   ├── 32c86d488b2cd06a8552a8f25e2704517df5b330.nq.gz
│   ├── 369944ea6179d0afc455ab561d15b6824d18ca23.nq.gz
│   ├── 384e6fd3654a4db63c92ccb2582749ff1461f458.nq.gz
│   ├── 39b19d34621bb88aae86cff75dc8e58deb6239a7.nq.gz
│   ├── 39b86f999ad534dcaa6e37ed5bedcf228e4f8f45.nq.gz
│   ├── 4367fbc1debc2cfe292f17569ed2da300ca3f0dd.nq.gz
│   ├── 44441dc8fd9e78b481d3daee56936ac5f5f0e857.nq.gz
│   ├── 45a6a8a3afc67823cef8cf17819510ad43dd0221.nq.gz
│   ├── 480c5bab615dbec8fe6bbe0c8c3c4d37d332e977.nq.gz
│   ├── 56342c0493dbbd7730aba981b3e43d82f9736709.nq.gz
│   ├── 564cfd1d06537b3e04ce13a88ee61a715389fcf3.nq.gz
│   ├── 5a37a22ffb98b99cd74d9d3643a5796e75679ca3.nq.gz
│   ├── 5a583d5d931c706ca8b89c1d7515f3e4b5b2d544.nq.gz
│   ├── 5b45b7edd62d25ef99dc382bb3fd980ee7eb8786.nq.gz
│   ├── 641c4b55d03cd3ba3f2184b0a448b173766dcd7e.nq.gz
│   ├── 64eb82b8b9191a1eae7ceef6aff99d33ff979bee.nq.gz
│   ├── 69acbcba23f5e08e42f364521b1c7075c5d61e97.nq.gz
│   ├── 69e4f34401d1bd421eb12323e9de85d7fed22073.nq.gz
│   ├── 6cf2ae398241381cfc4b28e94db7d4b79918eb05.nq.gz
│   ├── 6e0bebde4763df957aab80cbd5f4f1c8ea156133.nq.gz
│   ├── 70ee3010cb025fdb0043a9d104351ca97abd20e1.nq.gz
│   ├── 76d1f114788b4efcc9a299681a89ea38b0c0042a.nq.gz
│   ├── 77a862dce8c906f6839b3017b40cb36d0d0af5ab.nq.gz
│   ├── 7e6adc048c6c4b1b8d4d2f69a9ea5f33d8123726.nq.gz
│   ├── 7f6677dcfeab3d645500a120db2cddea5b9afe42.nq.gz
│   ├── 83c27850dacaef9dc2b031d36655e281bc12dfe9.nq.gz
│   ├── 846d34d6e4d395dd8375779530232a27c3b90515.nq.gz
│   ├── 847f186e9f3d71c815cc4257af8c6f66686be5ce.nq.gz
│   ├── 853e250fb67c1e1059741048fb0118d46559327d.nq.gz
│   ├── 8569cbc2a8da26e7a579671d0554b3e377813277.nq.gz
│   ├── 89b59af076b7b23d6df5ab6e25f53fd5cd379ef7.nq.gz
│   ├── 8e3e9bd92b2d31bd558684127811b7b046408bd2.nq.gz
│   ├── 8fca46ed4a7a7ec7bcff63605198e3f808ad2ec5.nq.gz
│   ├── 903946fa37dd2848547e0baf5ed1a7051fa50a34.nq.gz
│   ├── 9417baea7fad27cd04411c50157c654edddeafb1.nq.gz
│   ├── 955bf74bd6b0fd6cbe843022b9b5588f772bb95c.nq.gz
│   ├── 96aff21c7efdcbcf7c5208855e0cc52a53b74786.nq.gz
│   ├── 9ab8954a0d926d4f37bb1f0533dc00ce2fc799de.nq.gz
│   ├── a03c76bc21d498b2f1e2333d32cda71e36a96e22.nq.gz
│   ├── a301edb824fce7f3fdf40cbc95b057c5b0581c74.nq.gz
│   ├── a3772738e185da635825b7d3126e87b4fddbb066.nq.gz
│   ├── aa1ab1a16c0ef205cd2800ce9e8b1feaa9f77846.nq.gz
│   ├── aa28581d54ef1739da93996deef4cd453a3b0101.nq.gz
│   ├── aff83c80a8d9d48e21c88467a3e8f3ccb59124cb.nq.gz
│   ├── bdfd36bc9f025e468411b39dbbe196aae47ef92c.nq.gz
│   ├── bee5a20cd1eefdfe3efeb4b9446882c550e2ed4d.nq.gz
│   ├── c361c2a9479556e1834b18aa552fb2e7fe9c072f.nq.gz
│   ├── c5d020e4fd90f1b26d64c8bbd66246bb2857cc7b.nq.gz
│   ├── c7eb1b5893d217ea27f46a0929e28205b832b0b1.nq.gz
│   ├── c89bdaaf1296a025ded4993aeeea4ce59e7d5657.nq.gz
│   ├── cb47a4851ac0a4f98c6f390649bfb33a59513d69.nq.gz
│   ├── cc2b07d4b83f98d845e7c86e19fe9e4be54b3748.nq.gz
│   ├── da47f376bbcd05221fc33f9f6cd360f9ae3826b0.nq.gz
│   ├── dc461eb30b822ad618bb40962f36328c2a980848.nq.gz
│   ├── dfe3578727caccf0e39a53e16e57b27eb8832b8c.nq.gz
│   ├── e03aef5a0364e143187d9975e8cb71b44b391e61.nq.gz
│   ├── e2511f204494e872516b0c33929874d25bc55c2a.nq.gz
│   ├── e651cf87d667f546bc6e48a20f02a685d7ac2534.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e76b96f2abbdc024f1c738b026a7e006f0082a4f.nq.gz
│   ├── e9c7c375a335c421798dcc22712ac6b5fd4637f8.nq.gz
│   ├── eb6802d7c3fea36152c99b6947e921aca9cd0668.nq.gz
│   ├── ecb8836a5f572d40ed10c3fedd647fc7cc577c18.nq.gz
│   ├── edf3d0217bcc27a388f91b88a30ea52388e02c0a.nq.gz
│   ├── f07534efd32f2f1cd8837c0ce4562e30736f944a.nq.gz
│   ├── f25e4dc7cec8d1dad377f8ddbc1d4d971751fb9d.nq.gz
│   ├── fd40c7f780126d374e1f5f388305fea7fdc1331a.nq.gz
│   └── fe959450b0a7efe5768d21aaf7cc6ae568c369d4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f381d9618927d10a0e1c127a5a9ec67cc9f218a9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 94 files
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

[datasette/datasette-comments](https://github.com/datasette/datasette-comments)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
