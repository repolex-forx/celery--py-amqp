# Repolex Knowledge Graph of celery/py-amqp

RDF knowledge graph data for [celery/py-amqp](https://github.com/celery/py-amqp), parsed by [repolex](https://repolex.ai).

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
rlex download celery/py-amqp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 15fb95f7a89e20b95ebaffcdf89b1473887aa241
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 15fb95f7a89e20b95ebaffcdf89b1473887aa241
│           └── chunk-001.nq.gz
├── blob
│   ├── 0098dba9116a1efec7f118f1bfc5d20fe28a40b0.nq.gz
│   ├── 009936d2a7b93318975ae2f30dec2b684a94f13d.nq.gz
│   ├── 0588540f85ab39b60f61d2b6a53b4fcfab5b7dbb.nq.gz
│   ├── 0c2dc835d25568454d3feb51c8eec6ee340e5ad0.nq.gz
│   ├── 0d83acd97c9b704dc0829aeb4021308b88d99c28.nq.gz
│   ├── 0fe871096d165df1afc4ed5cc6876d5130635c6f.nq.gz
│   ├── 10b8609328cbc24fdee48c53b7f00ebf2f6d4775.nq.gz
│   ├── 11a1182ad5313fb8954a5a9191e7fecc07905e2a.nq.gz
│   ├── 1335bec05f2f3b6e30e795b3346018637b5147d1.nq.gz
│   ├── 13e122ba3cf9df1a59668283d4c543de31926d3c.nq.gz
│   ├── 1c64f64f181e4734c419d20ec8b375d39c5df149.nq.gz
│   ├── 21c31103028374aaf93a7ba2aa403daaf7c29f1a.nq.gz
│   ├── 22fb1f902a9f8dced0c3180ed0187471396cbf8b.nq.gz
│   ├── 24ee1d272a4ca0152861f6269d2d71c1140313a3.nq.gz
│   ├── 299ce9a441c56c3373a86aa392d5360e19328859.nq.gz
│   ├── 2a1169e1a8792f2a0182dca94073b74824cb9db3.nq.gz
│   ├── 2c062a9fbbfce501272eb84b06155ede9fd11e38.nq.gz
│   ├── 2c6c39ab71e005420953dbcd83e686f8c3a88802.nq.gz
│   ├── 2d38cc6c3d4b3868aa66f1d08bcefe1e0308474b.nq.gz
│   ├── 2e56f90578988e470044d32525b305545d556a81.nq.gz
│   ├── 387a0b0abc84e83aa5f3c7f9d1bd9b43e91ff1e2.nq.gz
│   ├── 3c6a17d867b4e42626028127194551185087cb0b.nq.gz
│   ├── 3e416477eb5c02cc77f30aecd7392a1dff407ed5.nq.gz
│   ├── 407ccb8e27322430e8e178da98d584198976204d.nq.gz
│   ├── 4091cfd13f5f76d4a204d66446b1fa379c40f7af.nq.gz
│   ├── 429ec40b3a05583aff150114b8ff4fbbdf6dfe42.nq.gz
│   ├── 42c3871187b10b2b6cb75f83cb7cb3b92efe98dc.nq.gz
│   ├── 434f924e5a61e56a5bd426de5ab9137956bc91af.nq.gz
│   ├── 43c5570c1e1a1ce1fbe8a8321595eb87527fa5a8.nq.gz
│   ├── 46087c2a76b65ddf8b1d157e1abf266f1d1c84de.nq.gz
│   ├── 46efe6fc7b31ff8541b02ca3ff20f6b2ace0f676.nq.gz
│   ├── 47348a6db681edff319038e0e82fff5c75a17bc6.nq.gz
│   ├── 4db0a8b7f1bb86778b7e21baa90563ab15a5cf8a.nq.gz
│   ├── 5175d78bde317c0b9eb5c2a7f8f7719b97815a2c.nq.gz
│   ├── 5b20da335b1980be7deed652749d4959d650f59b.nq.gz
│   ├── 5bf0cc048bd4432add8bb06366a11bc6643ce5af.nq.gz
│   ├── 5c55c7a70a5644cadce9478c24759b52087e0b54.nq.gz
│   ├── 6795fc6b73deb49f773bc3a3091697b8eba6c11b.nq.gz
│   ├── 6a9c843f6e23fab884eb5e40863c53951f947835.nq.gz
│   ├── 6f6c6f3d048d10bab5bb93c02f65757af31b818d.nq.gz
│   ├── 7059884dcc5e24f1630c122f397030e13a077bec.nq.gz
│   ├── 7202f18dccd9c914f8c572ec7ed87a1a143ebeb7.nq.gz
│   ├── 72bfcf4a450f96d4c138bc78ce94de9098ddc915.nq.gz
│   ├── 74c09290cfd94c95ea9049f278acbe889b3de2f0.nq.gz
│   ├── 772c8f686f5db1813b7226e07347ca8f621821c5.nq.gz
│   ├── 79feeaadf736610647a555ab4cb7784dcf48af88.nq.gz
│   ├── 7ce307af1c83363a408db22f3a9fa71da5234b42.nq.gz
│   ├── 8825377c32ce58c37ebc8689343a757bc115aefc.nq.gz
│   ├── 8ba5f670002137dc9b26438c6022aef35bb4e4f8.nq.gz
│   ├── 93e8b2587745a4c14aad99a2691686da937ffa0a.nq.gz
│   ├── 99eeccba2ee221268c90b9382463e70e856ae22a.nq.gz
│   ├── 9a5912483f61a4fe2cfc340131b2c80a1cb799e8.nq.gz
│   ├── 9bb3c43047d4ecf1fe3d9284682842d699ee5405.nq.gz
│   ├── a08053bda498a04b2a88cddd3c024e7ed96a5a70.nq.gz
│   ├── a08ed1b1c1a6deba264ae97a52b6ca4da90a8fdf.nq.gz
│   ├── a5a8e1e7615538f87f667c42013b3efac9aeb0fe.nq.gz
│   ├── a75aa4e2866fbb962847b820983d264b108d9a7c.nq.gz
│   ├── a7e3c7f8181de2c025e49084240e086c938cf5cd.nq.gz
│   ├── aa2b4339d3958fea68c26002628299663b3bde58.nq.gz
│   ├── aa5c2f70a8d16b9f84363a5be49a4e01ed66b12a.nq.gz
│   ├── ab1d5fb02169a5e05b99cc3fe368ebd2f1845587.nq.gz
│   ├── ac81a66c7be45e91c46ed5de9eabd23d073ae75a.nq.gz
│   ├── af8f2c581d2378f5e3da358c60e451b42207660a.nq.gz
│   ├── b10db800fe6e22f287f8a727706c60c1a55f68d5.nq.gz
│   ├── b41a72081c8e162a91bc02740c9aa00db23d12c4.nq.gz
│   ├── b58d5c96f8e4cb3ec941da4f4caae29c03ec8a91.nq.gz
│   ├── b7bdfd264f9286af878e93f93698056ac15422c7.nq.gz
│   ├── b8e07f09057a9e2df3f0af377b07706bb20385bf.nq.gz
│   ├── c0234bbd8794f422408add375e818fe40a3aae26.nq.gz
│   ├── c56577db276c92931e5f74e3f2003dab934d70e4.nq.gz
│   ├── c5e25961fdc77907a4b501a466e9fe77ba8ec76e.nq.gz
│   ├── c5e2bb17e15c256b5db441b68f52ef162cb24ce7.nq.gz
│   ├── cc03f59f489a120cdc42a5291299b517bccf8b9b.nq.gz
│   ├── cee0515d584f5cca97a3e8598e10ed893454385f.nq.gz
│   ├── d0b67b92c5e2bd8fefbda5817fcafd30030490d4.nq.gz
│   ├── da01952d70b05c72abe92054c0c8f29b82dcbf52.nq.gz
│   ├── dae165deb8dc993e3abcc2d2db1f7adf71a65d74.nq.gz
│   ├── dc1c28a745e432ddb27a80edc0edf0c9c8a70b0e.nq.gz
│   ├── de8d5c8b8b2584cc0b7a3d8d91740a62464862b6.nq.gz
│   ├── e0532bd35edabb559ea2c891b07af9c83cf55644.nq.gz
│   ├── e48a5f06ef08261c01c03a082df3999c839abff3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e97091b3db9c301ce92a3855cf4a813605e8d74a.nq.gz
│   ├── eb0b995507fa861f692559f63634750fca2ced41.nq.gz
│   ├── ed0c7a26b81a3373298c06758f2a033235784c31.nq.gz
│   ├── ef06d21dfa60473cd873647c22775d7b6d96e014.nq.gz
│   ├── f02a47838396f0ad9e0f38b8e4bc8663fe3a2437.nq.gz
│   ├── f0b8a05f2d1c052c76b13e2e05fa9683bbc4911c.nq.gz
│   ├── f16149fc5e59d95aed603e8cd1d1f486c723ef69.nq.gz
│   ├── f246e89f175dba64e4c6e611b277fe6b7efd4d81.nq.gz
│   ├── f4d470cdf61c0d886708210af6ad1d6a7cfd70ab.nq.gz
│   ├── f91ae9bff9172270fc2b255d0bf6aaedec92f15a.nq.gz
│   └── ffc9d55dd7082371b400ed4d20b347882ab54f70.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 15fb95f7a89e20b95ebaffcdf89b1473887aa241.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 101 files
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

[celery/py-amqp](https://github.com/celery/py-amqp)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
