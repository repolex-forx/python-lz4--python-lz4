# Repolex Knowledge Graph of python-lz4/python-lz4

RDF knowledge graph data for [python-lz4/python-lz4](https://github.com/python-lz4/python-lz4), parsed by [repolex](https://repolex.ai).

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
rlex download python-lz4/python-lz4
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 029f36597b8d182484f3c38c6be6a71ad07ddc96
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 029f36597b8d182484f3c38c6be6a71ad07ddc96
│           └── chunk-001.nq.gz
├── blob
│   ├── 046b9724867e6232b691bfe83206ed4b231eb4b5.nq.gz
│   ├── 05ac560be1c22c543d9e1bff39f2b557d2319895.nq.gz
│   ├── 0b3578ea0857d26dbd7b9ad283044ee7c2f927d0.nq.gz
│   ├── 0cc1835f6e614d3e7c7244426b9bd657940b0a5a.nq.gz
│   ├── 0fefd8e0b36264678bdfa0a9a474d98dcf76ba32.nq.gz
│   ├── 150a2570676e3209a54200a19e5461687b327acd.nq.gz
│   ├── 174f9ae4f21798f6c3fb34c3911ade0324b4ab6a.nq.gz
│   ├── 1ad8c58fb95990a594781f733a59beca36bf8782.nq.gz
│   ├── 1bdf6c4fcba57536ff3c97936e1217e5aebb6797.nq.gz
│   ├── 230867e654521623294841597d62a9f981515661.nq.gz
│   ├── 29e7765a0772b5553e9ea7a42a2cd18886983b37.nq.gz
│   ├── 2a82cd0822621e6b113df83699c82e93bb7a81fd.nq.gz
│   ├── 2b44a63155be37062247bd0f4ccfc6205bdf91bd.nq.gz
│   ├── 35110c44f11cdd31fa8720d90fe55d615dd3d7cc.nq.gz
│   ├── 3d139a02efc326233a52fea2d5035b00ea67e4f3.nq.gz
│   ├── 3d599fa99418320f2a6bc098e03fb7b780d8cf54.nq.gz
│   ├── 4392bb332c5e4effbeea86a46ddb28db47c7ae0d.nq.gz
│   ├── 440b0b50593a8b0fa42289599bd045b0bfdc87c8.nq.gz
│   ├── 481de8aa5b5c3642bf5ded97f7044758dc3aea22.nq.gz
│   ├── 491c6087c417754ff4662a02c1bfc9ddc13d43e1.nq.gz
│   ├── 49537e2d90a5161ad8fcc847c696b7101b1cdd4c.nq.gz
│   ├── 4c51d89dae5200dbc2260e1e35ab2e11ea0290fb.nq.gz
│   ├── 4f4185ee08213a7a3f122fc771e95b0e429af830.nq.gz
│   ├── 505bf4d005f18ddccea8a92c981c018a7a33ee04.nq.gz
│   ├── 518770111c77311c0f1172a3a5c65ea8cc0e2331.nq.gz
│   ├── 5444b8b4ce3a9b752cf6c227401b29c0198b99fe.nq.gz
│   ├── 5578f832c4bfb018330fe63acfbda8577ff6a590.nq.gz
│   ├── 583f3fbb0577d5b3437b38995123ea8422168576.nq.gz
│   ├── 58ce298ade55ff2a9ade4d3afd62dd8c84b8c94f.nq.gz
│   ├── 5ab52c0ada6b5e378227019da9bf8aba4e8d39bb.nq.gz
│   ├── 5c7f0c78822b6948d260fe85431375ddf1242182.nq.gz
│   ├── 654bfdf32f96ac633a5d4bc4dde097dbdff46882.nq.gz
│   ├── 65529dedd368e77c47936b5fa134f225db9e3f22.nq.gz
│   ├── 6662bab4de6d74240d73123b910db20eab113176.nq.gz
│   ├── 6b9890c15f8ac759f987408534ad524d2ffb35ce.nq.gz
│   ├── 6c52f84ad244d17a9c20ae09d3dbd031cf6ea1ce.nq.gz
│   ├── 6f2f2430b869a85464da87f642eee29ce43753d0.nq.gz
│   ├── 6f7fc0dba85fb7b1996425899b4f2a4477d2045b.nq.gz
│   ├── 709ba17c135f32e918e6e9fdb38d0d4de9018f43.nq.gz
│   ├── 7639ef73bd20cc05f187a6c45d472858615cf461.nq.gz
│   ├── 766950f513f36bbe4e356653858fd444511f7191.nq.gz
│   ├── 7fa1654701f954eea299275e327ab041fbc5d743.nq.gz
│   ├── 86bd9933ff8863ec0081efa0d04a0b6a89d356e2.nq.gz
│   ├── 9561fb1061f6de114633c70871232a6896dcbe8a.nq.gz
│   ├── 993cc44c0108cd0e4aa51cd07796d6972b180c19.nq.gz
│   ├── 9ec4b41daabed8c5928144c99a2d10c0a8292119.nq.gz
│   ├── a18ed56190615788239341121eec3e56560b0e82.nq.gz
│   ├── a75bc4d4e65af417392d48f93e6100d4255d3f48.nq.gz
│   ├── a75e92f074872fe0f38694c72f22a00afcad2484.nq.gz
│   ├── aefff88ebd53b4ee2182101f36b6e029d12375ac.nq.gz
│   ├── af606abee19a7f735f806d66208a6cd240a34577.nq.gz
│   ├── b183e93f3e53be49fdda9f83436fa25b515d73c2.nq.gz
│   ├── b21ad6bb599439c0ef90354ecb45cbbc84048042.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── be998566a1cac42366e2fe5328632c5aaef89fe4.nq.gz
│   ├── c0b0028e13e185d3618985cb2751ee55876db08d.nq.gz
│   ├── c5541b0adcb1655628a6312da96b18b5a47bc59d.nq.gz
│   ├── c7db76ee84754baf86ca130f37a2fd412b9e40f8.nq.gz
│   ├── cfaeaace600b79e183c23befd2ee19f812cc12fd.nq.gz
│   ├── d33b3520749b584d20410eeb6d7d65f84705955a.nq.gz
│   ├── d6bad943358d37e01471681e4c2b25d0c2275e87.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6cb0c9ef031e9b48d3f9958fd5d571fbba22979.nq.gz
│   ├── e937acfefd857f1b2be158cd3a5ba3a85a389f07.nq.gz
│   ├── ea23e99840f000612d90bb3f0d39f35e5e313c5c.nq.gz
│   ├── eb9030fa228a4650e2a8bb9df45b542329a63dfc.nq.gz
│   ├── f03431d4124d83906bf01ab93e6ed1b4d2bbcd56.nq.gz
│   ├── f39da18a5e1af209dbde7800db06c5adcfd4162b.nq.gz
│   ├── f6eeafedccf0178098c74f4ec790deee3216501c.nq.gz
│   ├── fe11825632eda7f4103e4dc599225923c53bb16a.nq.gz
│   └── ff28749e316434a13123667848e6692e35bfb059.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 029f36597b8d182484f3c38c6be6a71ad07ddc96.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 79 files
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

[python-lz4/python-lz4](https://github.com/python-lz4/python-lz4)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
