# Repolex Knowledge Graph of astropy/pyregion

RDF knowledge graph data for [astropy/pyregion](https://github.com/astropy/pyregion), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/pyregion
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cbfe54945dca2076b8b178edf8994b2e15864b81
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cbfe54945dca2076b8b178edf8994b2e15864b81
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d48c935d23596a423a4a5b39ff540ef0525f38.nq.gz
│   ├── 01ab61338f25e7cb19aa70b78ae28bb078625664.nq.gz
│   ├── 1081dc1439fb984dfa7ef627afe3c7dc476fdbce.nq.gz
│   ├── 1190c2b423412fc0b2876a01e9189e56b143a59c.nq.gz
│   ├── 135d85f8a1811b7718ef87f33f1bc5144fec8647.nq.gz
│   ├── 1b1e82ba50c6adcd83ecce82c5071c0fbaf3cc96.nq.gz
│   ├── 1bc5519c7668a4b7e26ccbc49dc3645cac914757.nq.gz
│   ├── 1f7328173ae948dd04de28c0d90c994043de0e51.nq.gz
│   ├── 246ed75e0fcdc57505458c4ad0d48ce48e03b296.nq.gz
│   ├── 27858932d0e27f31a73de87c5a519b5c6888929b.nq.gz
│   ├── 27ffa7010e3b4c2af0a4e3fda2a00bff98a05fef.nq.gz
│   ├── 2aaa33eb1e36861ee0bb51908ce23bcf7dcbf75b.nq.gz
│   ├── 2c9dddfb386ce31fa1d2ebe04ffa0bfed8b9c821.nq.gz
│   ├── 2ed00ee62bfdda6cfb7bc98c4be11072efdfe7c3.nq.gz
│   ├── 2ed27bf9b7875ee2d148ab64b7447e83b51fe228.nq.gz
│   ├── 30172572c7139a312818646c1381bf3009581056.nq.gz
│   ├── 3530aa13612632af900883a22443202faccafae3.nq.gz
│   ├── 372327781dd5f1f9a7aa218622c33d7636739514.nq.gz
│   ├── 3ab1a54aeea0ff03b5ac699d5221bd9f49449238.nq.gz
│   ├── 3b511b23c2bd2b5e7f0713c7f68ebed2def7d151.nq.gz
│   ├── 3c30375f09801dd9f4e32b644d08c064e7f81391.nq.gz
│   ├── 3e2e49b2f60fda7cbb877bba5383a1c4090110d0.nq.gz
│   ├── 4006e7d327bc7f571afacfe666a5208b3f6d63d9.nq.gz
│   ├── 43d97af60b601c0f08c889935f201e52eb12606b.nq.gz
│   ├── 46118715458e61a2f2836d2ff1c8d2b781886e46.nq.gz
│   ├── 4831e2e356507768a126bfca8a9582ab37d91d05.nq.gz
│   ├── 4a09825b21b49c7cb5281fe3f8e9cfdefb60ffcb.nq.gz
│   ├── 4a89760a4a595ee8187161ac4548512bdab4041b.nq.gz
│   ├── 4e167f438efff4b74d3771f0de4b81cbfd7da826.nq.gz
│   ├── 50c0fd6c55b5e553ea31735837b7dd05d3555c3f.nq.gz
│   ├── 50f25303f232b0d4613fc31fe92312ddc419d833.nq.gz
│   ├── 567f8da1e2f4c251ec5bdbcefff3aeddacf9ce28.nq.gz
│   ├── 5890018c40b3e40fe8f00a06d0d5e5b28732c891.nq.gz
│   ├── 5f6174a64e06067bf2d5509da0262422d323bedc.nq.gz
│   ├── 60fc1d00198c949cbec114a1b82958a47be39ea4.nq.gz
│   ├── 610cddfd68e514caffa5204f6e5e581429788d4d.nq.gz
│   ├── 630f468d673b1b0a95158cc49ecfafdb45663a04.nq.gz
│   ├── 63fd361883e33f1bc560d74f24068e45da604e0c.nq.gz
│   ├── 670510629a3e521eadb241c3dd5fbbb80dee6281.nq.gz
│   ├── 695461eea680c05d9215d6776509683ad48a711b.nq.gz
│   ├── 6ab563feb2d590631315d329000c5127f65753ae.nq.gz
│   ├── 6b214a5c09d3a2ed5399a65ba6100bdfd0b070ca.nq.gz
│   ├── 73ed431a520d9b6f5abd8e227280e4862870e28b.nq.gz
│   ├── 765dc4738a9512de6ca0993a5a0b43f6b7674125.nq.gz
│   ├── 76ea031772b7e08922a209ca59b64c7c00da07fd.nq.gz
│   ├── 778dddfd913f795ae3bed86b0d071b7817cb8fe7.nq.gz
│   ├── 7a62c33a31cb901597e15f5fe8f2d8342a82c2ff.nq.gz
│   ├── 7aa01b731654527b803cccd1fa783bae9ed7ea0c.nq.gz
│   ├── 7e95d757b6755e7f98909cbba15beeeb55e75e72.nq.gz
│   ├── 7fb82154a1748d507925865d3fbf7508d62483e5.nq.gz
│   ├── 803886e246c516fb8c652ee5b989f019c91b12e4.nq.gz
│   ├── 809c9d24ac53f543244876ecdfbb88b7bcd3a331.nq.gz
│   ├── 8579d2b12f0a5d3e155568fddb46c0cf1b124789.nq.gz
│   ├── 8b4606a341b2093d5f0547eb989bf0723c48fec9.nq.gz
│   ├── 8c07f4c2675057c7a76d9d5c10def437bee3261d.nq.gz
│   ├── 8c9bbbc40c4859c26fd5c1b9bcc9beec8a1cd2c3.nq.gz
│   ├── 8d22017710217427f555ed931d3007b10f5a3f6f.nq.gz
│   ├── 8d4829d1a87ede19e8f4ec2507c4f6bb1cf7cf5a.nq.gz
│   ├── 912a6226876acd846618a064a2163541a162a9a5.nq.gz
│   ├── 91ed46b3ae28e6d6121ed77aaaf377097cefa545.nq.gz
│   ├── 949d72bd5486927bd34f94e0b3ccec79dc39ee6f.nq.gz
│   ├── 9706d43e6e39ec9e6539c618656925b8ecb0d8d3.nq.gz
│   ├── 977677c2636afd8710c471a769e82b7144b4060f.nq.gz
│   ├── 9b39221db8e3e77f4a23ddccf553d334e3e39b76.nq.gz
│   ├── 9cabaf5238d62b16f3ff3c1fd828130815f33324.nq.gz
│   ├── 9d14f4c34110d6081e3db1ddcfd33da59f4f4a76.nq.gz
│   ├── a0e1222732428e9d0db8920d8daba1136c0cb742.nq.gz
│   ├── a175e22f86cf630ef072a9c76575af05dd4d4c29.nq.gz
│   ├── a483c210314354c782f35d3d2603b92e86ac65e9.nq.gz
│   ├── a6573af9c9daefdd3a0e30115fb6e4ad96327960.nq.gz
│   ├── a7db077cf5203e146bd508087b5347c5cf651819.nq.gz
│   ├── b1bbbcad1acb1d92aef0be58b37884f938b859d7.nq.gz
│   ├── b87372f315b4bb67d5650dbe5cac2e7728b88524.nq.gz
│   ├── b8b152e0195cb97c14925826b37939fea15a94eb.nq.gz
│   ├── bd67016dae529b16de15e97c48b7c860defbabe8.nq.gz
│   ├── c226fc8135f908fbfdb5e89b7eaaa40d90119954.nq.gz
│   ├── cc8667aa4ae95e27a811aa36d079b77070bb8a4e.nq.gz
│   ├── ccf9aded3979baea4e8e3afe83158fbf6ad0cbd9.nq.gz
│   ├── cd0c1ca5fe8213187baf618fb04bcc162ecd9fea.nq.gz
│   ├── cfa70e8525c73b34a1d3d9e79f8dbd18308c6ba7.nq.gz
│   ├── d18082e397e7e54f20721af768c4c2983258f1b4.nq.gz
│   ├── d57929b9e6335ef89200535e7433636f5e1f1f4d.nq.gz
│   ├── d9227d221734dbda4833e64a8379126a4b7744c7.nq.gz
│   ├── df0342b3b6b2a7451b8c3d3f861d68716ccb7c91.nq.gz
│   ├── e0b934c496f198299a03ee305c7feadbc06d8fcc.nq.gz
│   ├── e296440c97b3bc10416dfbcba5a343d883fd6052.nq.gz
│   ├── e4a43c25e0ad64bd364cedb33c07499fd30c7a7c.nq.gz
│   ├── eb82ef11c00b473f58f7b2cbc3dbc49dfd205571.nq.gz
│   ├── eef67af6db78425c73e429b31304989c91fa4826.nq.gz
│   ├── f12043e1239a2c76addeb4a9d2d9123277fc03d2.nq.gz
│   ├── f38315b22a4929c146aebfb5f2671bb16c003fd7.nq.gz
│   ├── f9a3dc70f174d48f3cc022032961bc37cc15aa84.nq.gz
│   ├── fb03f26e6be82581a39a45b00c82f59717bd983d.nq.gz
│   ├── fbf049195a790546646414f57baf7159a96389c7.nq.gz
│   ├── fd714ce6fb1035cccd988955ac2ccea3c2bb8f12.nq.gz
│   ├── fe273839bc515a5943d9768dbc2e759eaf37487e.nq.gz
│   └── fea9c7b4ace26a36d5acb3676a2d47fbe1081b64.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cbfe54945dca2076b8b178edf8994b2e15864b81.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 105 files
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

[astropy/pyregion](https://github.com/astropy/pyregion)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
