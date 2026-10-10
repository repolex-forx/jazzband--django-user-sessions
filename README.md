# Repolex Knowledge Graph of jazzband/django-user-sessions

RDF knowledge graph data for [jazzband/django-user-sessions](https://github.com/jazzband/django-user-sessions), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-user-sessions
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 527f91e83e61d240d6bba6e20d460cc515a52dbb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 527f91e83e61d240d6bba6e20d460cc515a52dbb
│           └── chunk-001.nq.gz
├── blob
│   ├── 01d2f3a3636cb91b3f3f6957df2da362ddad3169.nq.gz
│   ├── 032079fe3cc3498b6444973616b1a31938e90b90.nq.gz
│   ├── 0b8b10637660c5b46b394355a36506211292e5cf.nq.gz
│   ├── 15a8428de12d04e09f171af29e0cab30f20317ea.nq.gz
│   ├── 1e939b6817eefc7fe876b07f73451f779ad118ec.nq.gz
│   ├── 1ff458a2ce0d28ac01899851e049637bb8035dcc.nq.gz
│   ├── 20c112ac91c863aba58f8e4617d5e14f47105f29.nq.gz
│   ├── 21d758856e72247df32a527bc3d093161657a9b8.nq.gz
│   ├── 2605e3768e2bab92ef0550d452036472e9a6a210.nq.gz
│   ├── 294e27278df69858ee5df38840647d02db3615d7.nq.gz
│   ├── 2b2f5b6480b2a62508789504e7753eaf79bb8c1d.nq.gz
│   ├── 2c405044cb87500eaf2cbe6b3236aee531eaa364.nq.gz
│   ├── 2d0416a5df127fbf0c49f6f947876867f7e33b04.nq.gz
│   ├── 2ee13b91bad2f7c763adc12852c4131cbd7acb3a.nq.gz
│   ├── 32a5177727a975b509196e99b9dd204ebdca2848.nq.gz
│   ├── 3831c82d7665d7600c0905d28502e4f6beaf5c70.nq.gz
│   ├── 3d74b1628787b943467284e08ddc944e26b55227.nq.gz
│   ├── 3de622565b2d86902386785c510192eaa694aea6.nq.gz
│   ├── 3eb03151a8fc07f4d5d26e9b6d26a67e601fa6c5.nq.gz
│   ├── 406b88a8753f63f1ced24e36c5c625493a06e405.nq.gz
│   ├── 41fde416f0899c56265d56f922e1373e115d11ab.nq.gz
│   ├── 45895962865bc9a7801364b4b925811e383e7e6a.nq.gz
│   ├── 48b9725180ebd8cf4c3e0ac0c1d564dab0d7084f.nq.gz
│   ├── 4aa149f16621df673f5f4a143ceef8da3753a008.nq.gz
│   ├── 4bda6aeedf595554dbdf2b3ebea1b4d7e3ac292f.nq.gz
│   ├── 4e2bef9fd763d89967f3b4bf93842d11b913e13d.nq.gz
│   ├── 4f66f90afd7fbd3ebc947337cf82e4cb49cc0a84.nq.gz
│   ├── 50f22549906c5f82f54afee6f5651a4329a0fa57.nq.gz
│   ├── 51a12fcab9a7d45a0ec7863995e1895a95dd9e6c.nq.gz
│   ├── 52a90377dc38144e75c30d76c488ddc2cf38f471.nq.gz
│   ├── 52d37f4335e8e687778498e34869a1782450ade5.nq.gz
│   ├── 53435f5b64df56c15c96609c192f7ee78b43da38.nq.gz
│   ├── 5536b7310fa9a27275ccb255cadc6641318fcabb.nq.gz
│   ├── 5a87979d366d5dbcc9acabc8b7de691f63e96230.nq.gz
│   ├── 5b55c0fa6cd614c8722b2d8c0740df562ef35be4.nq.gz
│   ├── 6592725d98d41a275a5466aeca1ddecc3968632e.nq.gz
│   ├── 6755cd2929f8485b4184d00c8bdee009635a1ac5.nq.gz
│   ├── 68e11452c35ab08aeec1b3a5df4eea9bf0f59115.nq.gz
│   ├── 6affa152d19423d86e61b9099256de42fe690014.nq.gz
│   ├── 6fc72f780e3ee3ed7c2d895a68e62932c7a31ced.nq.gz
│   ├── 70c9562638a9cf22366efab3492ae218dce8532f.nq.gz
│   ├── 726d5806e9fba6bbdcdc11f5dea87c9ee7b8eff1.nq.gz
│   ├── 73b42e668694bdb71ec51d074f4b83bb659e62b2.nq.gz
│   ├── 7a0a1c18cbbcb6b51a312aab6e3e3fae304c4ab7.nq.gz
│   ├── 800c70eb89431be18a5041080a0d79abdc9da0ed.nq.gz
│   ├── 80ab28dfc98ed47557bef4fd54bba054021e2b6f.nq.gz
│   ├── 823c15b02bf30ee2e6380ce50b10e03dac212bd4.nq.gz
│   ├── 82eae508cd8874d1c16415aeede009ca3259f0aa.nq.gz
│   ├── 8acd6b8370a28222edd3a0afae2cb26b75a89b5c.nq.gz
│   ├── 8ced386b6872eb03cef84e96367ad9b116e50ae7.nq.gz
│   ├── 92fdc96af27adecbadd587eb443da29d5b19988f.nq.gz
│   ├── 95e749c93f11ff8cb4afba5a7a2b45f64a9836bb.nq.gz
│   ├── 9a7bd9936ed5e793da38edb006870ff3ff907caa.nq.gz
│   ├── 9c01fd90c2c6fed0e01e75d248d28ac767ba05c7.nq.gz
│   ├── 9f39b801698bf3d7bfa83ddf378395b1aa416d4f.nq.gz
│   ├── a7b524999e65d9ddb1000f5751e74634e29ef70b.nq.gz
│   ├── b08a83437d8f66a056c0d7cf0bec79d86c226f8d.nq.gz
│   ├── b3a98ed54310a7d0b550e3bc76ba9639a49a073f.nq.gz
│   ├── b70278df1a5c4114131b16ce61633d07e083aca2.nq.gz
│   ├── baae3f5f46d6a663fb9f5b87efbb8c4917b27208.nq.gz
│   ├── bcabfc85072f926365745a4e25f3cb318e5e9a6d.nq.gz
│   ├── bdcbe1aa419ddef1bbcc21abd1b8a5e533dc0872.nq.gz
│   ├── cad7aa4cbd942c89319a81bd216c9da1dfaa27be.nq.gz
│   ├── d12f02a0e06dd12f82f5a89ab6de9d7cdea9fd9f.nq.gz
│   ├── d363dc60d57de76d4746e2464c832acf3f2869be.nq.gz
│   ├── d6bc596fbfad6d3c697b770f2335802660e53136.nq.gz
│   ├── de9f300a0f923e3d7ea55f3d66cd9a490e67f674.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9238f90acb003443bfe5400ff19a07563322307.nq.gz
│   ├── ec65a81b4a4b4eff03c83881784a9895de69cddc.nq.gz
│   ├── ee12b74dd0acbe0940a092c6ea2336ff9c94189e.nq.gz
│   ├── f23579e8295ee68a959f8707bcc36a1a8627b0d5.nq.gz
│   ├── f328c0d52a6cc819cfde9477116e294a2dac130f.nq.gz
│   ├── f814466cc885393b08c4e55d221aa25c1d69ce4a.nq.gz
│   ├── fa9f0ccbb4095a9b0cfea4d5a50eacdf316640cc.nq.gz
│   ├── fb3463eb8f6cc008b5757a18487af4c431b4869c.nq.gz
│   └── fc3af324a4ec2b5fc548aa6d22de7eb54bfda44a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 527f91e83e61d240d6bba6e20d460cc515a52dbb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[jazzband/django-user-sessions](https://github.com/jazzband/django-user-sessions)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
