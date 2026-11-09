# Repolex Knowledge Graph of TheAlphamerc/flutter_ecommerce_app

RDF knowledge graph data for [TheAlphamerc/flutter_ecommerce_app](https://github.com/TheAlphamerc/flutter_ecommerce_app), parsed by [repolex](https://repolex.ai).

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
rlex download TheAlphamerc/flutter_ecommerce_app
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f7622934ae310706bffc67c0c95c740b858077da
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f7622934ae310706bffc67c0c95c740b858077da
│           └── chunk-001.nq.gz
├── blob
│   ├── 01d2dcb9ad9e2d1615a8d944d5ff2fe459c2a4ee.nq.gz
│   ├── 0892ae9a2cf29aaf7b2c57c184d102355fbc3ad4.nq.gz
│   ├── 09d4391482be68e9e4a07fab769b5de337d16eb1.nq.gz
│   ├── 0a741cb43d66c6790a2a913fa24c8878fb1ab7b5.nq.gz
│   ├── 0a8bc66d3c815568f4a0dbebcc5596adf37a552b.nq.gz
│   ├── 17987b79bb8a35cc66c3c1fd44f5a5526c1b78be.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 1e8c3c90a55e35357982e1840243bf3a0fdbdcac.nq.gz
│   ├── 21a3cc14c74e969ab1548274a8512ebfecc40f78.nq.gz
│   ├── 2693bf0429d7a39d8ec61fe4cdbc33da1a90cb4e.nq.gz
│   ├── 2793a4f3de69be1e490d23382fe7508a44a774f7.nq.gz
│   ├── 27d6f8958d5ae1fe8d104364b99ce14c5302cfe5.nq.gz
│   ├── 28c6bf03016f6c994b70f38d1b7346e5831b531f.nq.gz
│   ├── 2bb3a1009b9284103e14f2967dc3fa0b254a7445.nq.gz
│   ├── 2ccbfd967d9697cd4b83225558af2911e9571c9b.nq.gz
│   ├── 2f6a7adccb8a2292b214d78298c1a2f22d46eec1.nq.gz
│   ├── 304732f8842013497e14bd02f67a55f2614fb8f7.nq.gz
│   ├── 324939d86199ce8e47025f1c66f73624e0431ddd.nq.gz
│   ├── 399e9340e6f617f68676161ad4a64edcbe483115.nq.gz
│   ├── 39ae6c1df8203a958734815be6204137f2fd7faf.nq.gz
│   ├── 3d530cf7cd97aea1108214a478ec9c327c2dbdf4.nq.gz
│   ├── 40a0eb34fd3b2a2540a70d6bafd0528871f61707.nq.gz
│   ├── 449a9f930826851b495d039f0c0d57f247536615.nq.gz
│   ├── 44e62bcf06ae649ea809590f8a861059886502e8.nq.gz
│   ├── 4717fd13fa8fd2b9d09deec4bcca378f838b5ea7.nq.gz
│   ├── 4840d533d0a723db1fe71210f8db21a350bd2997.nq.gz
│   ├── 4cde12118dda48d71e01fcb589a74d069c5d7cb5.nq.gz
│   ├── 4d6372eebdb28e45604e46eeda8dd24651419bc0.nq.gz
│   ├── 4ed637dea124b5b912317f8ebe6d3cc46450ee0c.nq.gz
│   ├── 4efeea953264e408317a4d06177a77705f7028ed.nq.gz
│   ├── 55f89ac1aae97f7f0191c3b2ff7982833c37740e.nq.gz
│   ├── 578a71e1851f85aa17bed246bab8e1eb7ef11a17.nq.gz
│   ├── 5c25adcbeedf3a746f1ad306dd33e239e8c1efd8.nq.gz
│   ├── 6322164a079e8ec23058aa5e8ca3f6aea7ad3257.nq.gz
│   ├── 6397b1159172f631a802a4cd8f3fd3696d287a5e.nq.gz
│   ├── 6a84f41e14e27f4b11f16f9ee39279ac98f8d5ac.nq.gz
│   ├── 6bea6647b8acbad19c940127b2a62af181c74a70.nq.gz
│   ├── 6d414c84b207b41a9ddf7829362fefe5fe134a20.nq.gz
│   ├── 7053164c49034c71f39956dd45bae7b5e73b067c.nq.gz
│   ├── 70693e4a8c128fc4350b157416374ca599ac8c7b.nq.gz
│   ├── 7335fdf9000cec1b6c1e3f506b196734e8a427ff.nq.gz
│   ├── 75b2d164a5a98e212cca15ea7bf2ab5de5108680.nq.gz
│   ├── 7603b1627da064e84d95d227c3a6121389f5bd48.nq.gz
│   ├── 78207e73342dcb73301ebb9960d767399337c49e.nq.gz
│   ├── 7c2ea730a1ec9621fee19f3348152f5cfbb4e533.nq.gz
│   ├── 805d8750338636d0b5c86473282c77a87619b7f7.nq.gz
│   ├── 82e8ee232471030e748a36e573550526d06b18e3.nq.gz
│   ├── 8482a9cf2a9101d6989a21d1e66b40270bc8b7f1.nq.gz
│   ├── 855cc2df79678ae335a9e64b2db43a064b5c56a5.nq.gz
│   ├── 856f4a0c62082125ad28cf4b7fae41cf4f40eb2b.nq.gz
│   ├── 85c4081cb1c7f659c6f439f2194cd4f80eca4c00.nq.gz
│   ├── 89c2725b70f1882be97f5214fafe22d27a0ec01e.nq.gz
│   ├── 8ad995dc061be0f87bafc506b5249401f4778cbe.nq.gz
│   ├── 919434a6254f0e9651f402737811be6634a03e9c.nq.gz
│   ├── 94adc3a3f97aa8ae37ba567d080f94f95ee8f9b7.nq.gz
│   ├── 9b3a197f090c79c5a8efcc7508ed12461d007d08.nq.gz
│   ├── 9da19eacad3b03bb08bbddbbf4ac48dd78b3d838.nq.gz
│   ├── 9ec6b5ef8365e7b97f62ab7f615e5a1eab4536a0.nq.gz
│   ├── 9ff870573c19b35c85c41470af66fdf31552b4ba.nq.gz
│   ├── a0b706e1db107990dc6f852e5d34d983ab682581.nq.gz
│   ├── a257ba89c2b65e78dac95bd17f626bcc0d26e319.nq.gz
│   ├── a27b137b7a63ab41c498c7f002b56209f40c7a29.nq.gz
│   ├── a28140cfdb3ff9b7a11a9497b84546d615db2afa.nq.gz
│   ├── a6d6b8609df07bf62e5100a53a01510388bd2b22.nq.gz
│   ├── a838fc6ce3e836d3686d89479d54b8f70f9d9977.nq.gz
│   ├── aa35fd7297d56ceb27ccd6c7d29859955e200f5b.nq.gz
│   ├── ac969633f7ca3976168078a5461e28040aafe0b1.nq.gz
│   ├── ae1f1838ee7e87b1fa976268adc723e1020af38e.nq.gz
│   ├── b1706504a51bbd3a943aca45c738e19be1e02a06.nq.gz
│   ├── b8d3ebd4ebd7c6538f57f5051e8ae447fae49234.nq.gz
│   ├── bbcbbe7d61558adde3cbfd0c7a63a67c27ed6d30.nq.gz
│   ├── bc695a9829156908def83ccb75dcc42046cc1a74.nq.gz
│   ├── bc6a58afdda22a443c752eaae3d60c2480511a9f.nq.gz
│   ├── c4df70d39da7941ef3f6dcb7f06a192d8dcb308d.nq.gz
│   ├── c60990ceb842dd7e9bed10d8a66b9a270e1106a7.nq.gz
│   ├── c6cf06ac2b86cb74dfdf3b13eddcf77d7f6a9ee5.nq.gz
│   ├── c8f9ed8f5cee1c98386d13b17e89f719e83555b2.nq.gz
│   ├── cd7598378bbe69b97ce8289c121369865dbdf780.nq.gz
│   ├── cee45201ac6aadc3e2aede744b27585e731b5b41.nq.gz
│   ├── d0e1f58536026aebc4f1f70e481f6993c9ff088d.nq.gz
│   ├── d0ef06e7edb86cdfe0d15b4b0d98334a86163658.nq.gz
│   ├── d246750114885af41ba9b411243f7dcc6f6dca12.nq.gz
│   ├── d58d65d3d416942917bf22eddf2b88f5d69b0068.nq.gz
│   ├── d5f1c8d34e7a88e3f88bea192c3a370d44689c3c.nq.gz
│   ├── d74aa35c28261a8e78264252be7f0f6f9406ec35.nq.gz
│   ├── d88839c2540170bd05bb8308cfc65ef9a9810200.nq.gz
│   ├── db77bb4b7b0906d62b1847e87f15cdcacf6a4f29.nq.gz
│   ├── dc9ada4725e9b0ddb1deab583e5b5102493aa332.nq.gz
│   ├── dcdc2306c28505ebc0b6c3a359c4d252bf626b9f.nq.gz
│   ├── dd84ea7824f11be1eeda22377549cbc1aec7f980.nq.gz
│   ├── e586145087339b2914ef23888861939d95ef30a9.nq.gz
│   ├── e8efba114687be7d0e4e5d026a31f5efd04d20bf.nq.gz
│   ├── f091b6b0bca859a3f474b03065bef75ba58a9e4c.nq.gz
│   ├── f2872cf474eee0cc0439d4012e1a653ac08e9d0f.nq.gz
│   ├── f2e259c7c9390ff69a6bbe1e0907e6dc366848e7.nq.gz
│   ├── f3c28516fb38e64d88cfcf5fb1791175df078f2f.nq.gz
│   ├── f74085f3f6a2b995f8ad1f9ff7b2c46dc118a9e0.nq.gz
│   ├── f9b0d7c5ea15f194be85eb6ee8e6721a87ff4644.nq.gz
│   ├── fc412ccfe01bd529c4062e3552b8f00ac610eb5a.nq.gz
│   └── fe7cfedec9d1e38365e3f1c63a2d717cd70192bf.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f7622934ae310706bffc67c0c95c740b858077da.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 108 files
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

[TheAlphamerc/flutter_ecommerce_app](https://github.com/TheAlphamerc/flutter_ecommerce_app)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
