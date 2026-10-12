# Repolex Knowledge Graph of django-crispy-forms/django-crispy-forms

RDF knowledge graph data for [django-crispy-forms/django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms), parsed by [repolex](https://repolex.ai).

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
rlex download django-crispy-forms/django-crispy-forms
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e7fbb538595dde3a4598b4403e60ecca0905fa74
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e7fbb538595dde3a4598b4403e60ecca0905fa74
│           └── chunk-001.nq.gz
├── blob
│   ├── 0062cfc511d49beb08f3df93d6e3c8c1885b821c.nq.gz
│   ├── 04bcbd2870267ed3e8d9a96d53546abb24c38137.nq.gz
│   ├── 07cdebb1c213e516148fac6971d1b3a976018889.nq.gz
│   ├── 0c2414ff5ecc4697ea4ea3110a96a7833bd92ffa.nq.gz
│   ├── 0e5be0f2bdabd6813407d779111e0974bd0851d5.nq.gz
│   ├── 0e7c5ab80c0d639d3bdd053f239522c9a92e8fda.nq.gz
│   ├── 0e7e1ffec09db4dd4ce8aa9d1b71e5d02ba06cbc.nq.gz
│   ├── 13c4c48a0b5d71e5e8658f1c49156bcfda2b671d.nq.gz
│   ├── 1477c0d90dbd028d8e4bbf641b900cbd63f4db92.nq.gz
│   ├── 147f56adf29e585a41d91cee94eba285e1f911dd.nq.gz
│   ├── 1e5e121f8f19901825f6d2e740a2fd684411347d.nq.gz
│   ├── 1f4f72e696191065db8373a9706219ca0d3a29d0.nq.gz
│   ├── 24274a6cdca17a270d8018d39cf2830e6294d467.nq.gz
│   ├── 24df311e2d6a1b9995d7b75db4ca68a6dd44fcd4.nq.gz
│   ├── 28171e9a7b53121c8317db170aa4801982a94ac8.nq.gz
│   ├── 285381efebb8509642b99871c06c8e22be7cc6b3.nq.gz
│   ├── 28d1f3bd0b6132eed03dbe6a8bbd43e33ffb1a5d.nq.gz
│   ├── 2b206a32303ffd1744075e9c44e720ddf5d6f5c1.nq.gz
│   ├── 2bf07ebc432ceed322f9e354522a3e8e06f85cbf.nq.gz
│   ├── 2c76a9d680899121cb09255d194da8a3d684c349.nq.gz
│   ├── 2d0458543a6bfc2871d45d0ed1795ee4856694fb.nq.gz
│   ├── 33a97a9f699ec8a3690a74f29cb143d79a30eddc.nq.gz
│   ├── 33f79396e12f36fc8f9d22c1b702aa317f10d1a6.nq.gz
│   ├── 3bea596f60cb015af336677b18e90c92e282a1c5.nq.gz
│   ├── 3e2f7a35804fb43cb34f80ec14da0b9ec812d2be.nq.gz
│   ├── 3ea888aadec4808f7484108bb84499006cdfba70.nq.gz
│   ├── 411aa519da687cc568809e2a0ff96ecb359c7b71.nq.gz
│   ├── 44473dfbda23c9cecf51acfd16dfcd6502d1e13a.nq.gz
│   ├── 4632e5f84677ab6e2c75855413bc7d6162c22dd3.nq.gz
│   ├── 498ec14ac4d5520dbd87f7f7066cca7ca79719f4.nq.gz
│   ├── 50d9e74c92a4cae09f67b77051f7f7c85f2d2e73.nq.gz
│   ├── 5188b8bb8af6b27fb48d670dafb6b2ce0c370aa4.nq.gz
│   ├── 57f7c782ca8445e4baf4126e21bc9b84e974f197.nq.gz
│   ├── 580990b2dda40b684b12cdce4d0c0b38d99274cf.nq.gz
│   ├── 5da373e54c6283210fae8cc635dfd7634cda120c.nq.gz
│   ├── 5f4cc61e3e5a89fc82493fbd941481345d66b4ae.nq.gz
│   ├── 606463723922e3b6c3d7691b0f5752068e328054.nq.gz
│   ├── 645c6628e8560f3824692e8ac57539adbfa9cd31.nq.gz
│   ├── 6ed8ea8abb5ad0bb0841ce8fe88ac77e2d5d8db3.nq.gz
│   ├── 7a0f0a11328989dfc6a42b74bce7786faf224e50.nq.gz
│   ├── 7c51b30fb18d89b7213bcdafefce371ac9334b40.nq.gz
│   ├── 7e5ea22aa5e2af0d8d0d6b8c9c0b9bfb79f3823f.nq.gz
│   ├── 81915c15b59dd9c0807ef8ba2f308e77ffdc409e.nq.gz
│   ├── 834a7da4baf6d95c505da6b003ac5ac5f8b6a6f3.nq.gz
│   ├── 83b0c906d91f74a74bf1c888f4633be6d8861e45.nq.gz
│   ├── 864746a8ae64e6696eb22059f250234524f211ae.nq.gz
│   ├── 87c479aec501147bf2a54d10d20f8461a06dda9f.nq.gz
│   ├── 895fa003ff8777d0e1ef46b71f842b599931101b.nq.gz
│   ├── 9056149c6666763b293dede7c4bdb73a1ef036ad.nq.gz
│   ├── 92b71dae814d0850ff43025a13618683760ec715.nq.gz
│   ├── 99fca1570c408b06d2401ad604484710027af281.nq.gz
│   ├── 9a56b2c603cef1ab48f4b558afafd6dddd21f779.nq.gz
│   ├── 9c5642a7d3722136530823a95f11429595979cb9.nq.gz
│   ├── a0fec73b81d962474edcf4b915a89a1adbbacad0.nq.gz
│   ├── a53e21b72326b941e84b3ad43744283c16990f92.nq.gz
│   ├── a57118d6f31b4a39d4f4f82c439f26f549fe9bf2.nq.gz
│   ├── a75ca24e31e77515dfab528fb886a5a5c9b4f7c1.nq.gz
│   ├── a804ff83e836302f7f50966e93f89d4ed92dda3f.nq.gz
│   ├── a97b18de514464e29d483d07e0ea1065ad53b517.nq.gz
│   ├── aba74dc196d7959bea10799bf95f948358c7d6b4.nq.gz
│   ├── b228a2789517d53b0e61ca067c8f2e50f84314da.nq.gz
│   ├── b3c7b6b2e532216ffd71dbe851db75aed0ca2687.nq.gz
│   ├── b73b208c899c2312b6698f5fd07ed9432f0bbe42.nq.gz
│   ├── bc80b73c84ae9c5c3043836c470cdb0e08c41d3a.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── c1c3cf8659ef2674ce06714212dbdd1720d89e3d.nq.gz
│   ├── c3b9ee50ba78e25d289345dcb7f9f7ea40a86ed8.nq.gz
│   ├── c48a249d5ef3354b097d52b8e7b802eba4b85aed.nq.gz
│   ├── c7019ab1b2a5d255cc7c4d5df4aa405151517a39.nq.gz
│   ├── c9e8b331680608e275865f42097c0f7b861b7429.nq.gz
│   ├── ca78c4740e065a28ad72f471ff88bf833484af58.nq.gz
│   ├── caf941db4d9d9e77165cbeb02ad53f1efe4852de.nq.gz
│   ├── cbec817dd320721c6e3cb460177c2c85234e8902.nq.gz
│   ├── cc6736d1f12fac1140ca9c84be1966cfaf3fe396.nq.gz
│   ├── cd305af1cd257149f2352febdf7604428666f060.nq.gz
│   ├── cdec9d083d7d77f5dcd0a482585f760b4ec215b4.nq.gz
│   ├── ce629cc8f6a53b6937e1aae77bff1054b2e401d1.nq.gz
│   ├── cfcaea0d4d4c5215884adb7e5805b9d3cecdfac8.nq.gz
│   ├── d713cc5b9b6b4a90acbd0216aac17035cb5941bc.nq.gz
│   ├── da0e41f83cf5d3ce80e03400a970b5df581c2a76.nq.gz
│   ├── db3509df5dee7b0c94eb87135007570ead0df811.nq.gz
│   ├── e175ba9039ce06de72579d28f924f30dec7e70db.nq.gz
│   ├── e3e1f2a7726cdc50e7324e94252ebc7625f5dd8a.nq.gz
│   ├── e5faa80c37b52ab6f576473d20cc997bcfa74091.nq.gz
│   ├── e699e59e79355a978da1b52735bd707529b264b0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── effb14e78f07d35bfaeccecc8bfad8c3ec9d11cd.nq.gz
│   ├── f0155698a2b661b66a3cb002633fb4cd0efe63bc.nq.gz
│   ├── f57caf174506d10bf58bab6a100ad89eb1697de5.nq.gz
│   ├── f66c4a356233328a34da83fbacd95dfe34255063.nq.gz
│   ├── fa8e1a4128f71997e24cbb9a9e3152d41394ea93.nq.gz
│   ├── fdd3efe566d8993c0054952ad108531ef1139e2a.nq.gz
│   ├── fe9bd3614c08f6807874a3928837d21a6cabca30.nq.gz
│   └── feb2df05b86bb77150e9de32cb7d1ae996db9074.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e7fbb538595dde3a4598b4403e60ecca0905fa74.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 102 files
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

[django-crispy-forms/django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
