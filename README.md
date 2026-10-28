# Repolex Knowledge Graph of scikit-hep/ragged

RDF knowledge graph data for [scikit-hep/ragged](https://github.com/scikit-hep/ragged), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/ragged
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 14d45af4b9b086aae736f2ce7426502eaf6bdcfa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 14d45af4b9b086aae736f2ce7426502eaf6bdcfa
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
│   ├── 026c16b862f6a57e4e933aae6c27be40fdce4e1d.nq.gz
│   ├── 028ee68591803a27537d9d2eb8d856d89a9d5200.nq.gz
│   ├── 0571f12f08284c7883f1e9f863a2a27397986292.nq.gz
│   ├── 05aed1359c0718b1e3b53676b7bf38290c361196.nq.gz
│   ├── 05b1519648d2fedcd90346e2b2182f84e76accc3.nq.gz
│   ├── 0bebee7d2f8ee7035a76b0a48bd92c9653784053.nq.gz
│   ├── 1019056ea5d1028a5091a5254b2f8ad3cc9ce824.nq.gz
│   ├── 12eb72c15daab28b276ac209d99252545543c79c.nq.gz
│   ├── 1401274f2e0e3c52f288f54acbcf593e7638677e.nq.gz
│   ├── 145e63089c18113d0ca6bfbd096d8daf7239cb79.nq.gz
│   ├── 182903bce2c32515166d764d301f3c017cecd3ee.nq.gz
│   ├── 189cc990db4568938f7358921f60d3e1999cea9f.nq.gz
│   ├── 1974bcd637687facb83a79c42ef22fd07cbd22b1.nq.gz
│   ├── 1aa04649544213a921dda0a87a4e234e17c7488d.nq.gz
│   ├── 22aed41d3e6dddd522f30fd0e491d4cc31c5d870.nq.gz
│   ├── 248b7dcb99f89a65c2934dd941f0a56229b3111e.nq.gz
│   ├── 259ccd99f41f49349b34d58b73f6b240817d3ef3.nq.gz
│   ├── 26a4f9e30af2c44aefdf20f023d40930c0dc6c85.nq.gz
│   ├── 353af111fbc53c0818a6d6f4bc795c7e467f72ca.nq.gz
│   ├── 367b21b3ff8075dd2facbe364cac83c76447f3b9.nq.gz
│   ├── 3a74cbcb3535b5b564bdc3c5ceff80e0ead43297.nq.gz
│   ├── 3e617fb50ededf187164c62a64f8d771fd444b5f.nq.gz
│   ├── 3f2443d780b52cfbf54011c528e3bcb149e2954a.nq.gz
│   ├── 4375fb7699ec0818d62764016bcab6da548966ce.nq.gz
│   ├── 446027e64420c09e3b49d48bf290d2677d405c79.nq.gz
│   ├── 46d3d4bc2c4c38006880813b2e5a7e06123c8681.nq.gz
│   ├── 48d2080a488202e4add45c65a902ad629650df0f.nq.gz
│   ├── 4c11c0e5f1e885725cdbbc6ba0407f2aa5606c38.nq.gz
│   ├── 53b2adb5f3b85c07f5ac0ce54e019e720a098ea6.nq.gz
│   ├── 566dbb8bcd31ef77224d7cd8b4674e4f53d49775.nq.gz
│   ├── 64e386a9218fad1c3d28a1c20137ca2afe6e4d1a.nq.gz
│   ├── 65b664396a4f640b3270fdd22dc366037da52540.nq.gz
│   ├── 66c50045183b78f7a31ce424a51242549001e547.nq.gz
│   ├── 6b6a2e1c5e2442587198f27c4d9eba60c0c94911.nq.gz
│   ├── 70bf615928e1a7757401e568ac491f0269a4d2df.nq.gz
│   ├── 7e4965745f3ebe875effac45eb58b451b28801c7.nq.gz
│   ├── 80b57edc2c148e02774eec4428a507ede0005d7a.nq.gz
│   ├── 80eb019b870f96f66d531980d32b7843369982e9.nq.gz
│   ├── 839a8d01171091fcaecd8dddcbf1ed26725cb7c6.nq.gz
│   ├── 8c14c48457fb72b1df85f416319c8e1578a4d6fc.nq.gz
│   ├── 8fb235d7045be0330d94bcb3abd2ac43badaa197.nq.gz
│   ├── 91744f98344db40b12025cf4e48d9e6320225968.nq.gz
│   ├── 91b5efe67943e6f3ad9348b45902c5f14417f117.nq.gz
│   ├── 925e2b649c4f8b3bc045045bad28410caefe90a8.nq.gz
│   ├── 938a856300a655d45add91f87b0ee0d6954d48c4.nq.gz
│   ├── 97c46e1471816ac31af49bcc8116c12049ba32eb.nq.gz
│   ├── 9c568278f6428b6367a4b6b31897081817f5410c.nq.gz
│   ├── 9f6e1ae7c3028f905ae7c99582bdc153a7f260ba.nq.gz
│   ├── ac9b0ca8dad4e22e9b0608f558ad0d5fb967ed4c.nq.gz
│   ├── afc9dcebe9638303c2280a806d1913db86a9c87a.nq.gz
│   ├── b11efd840ea02183f239eea9a1634b27205956d5.nq.gz
│   ├── b3c3da60e85f1aaa0bc1bbcb65a39222dac29d15.nq.gz
│   ├── b6e4814e9f045937a94a82a4479bcd7364276e8f.nq.gz
│   ├── bbe7bf9d0fe77d820c91c1fee39947f5a26cae9b.nq.gz
│   ├── c2b13e1ade2b1e8eb6ca256b743c5e9f94a0b02d.nq.gz
│   ├── c49ea004885d0b3c308bf56ac54af04cb82ebbd5.nq.gz
│   ├── c66cf18d4ebb47931b566b46b3ffd8733e5c9f53.nq.gz
│   ├── caaf2c4d0020b615479b7659ba92b8263687926e.nq.gz
│   ├── d9c82099e1b0008185ee7207c9c07ca286dec342.nq.gz
│   ├── dc1e8deaa89840052da0ae83fb605e7b8d85983a.nq.gz
│   ├── df87156c65f3a5a75a021b39bf85803ce5411200.nq.gz
│   ├── e28b33c7a38f76fa60990e6259d85176d2cc8c91.nq.gz
│   ├── e3a6bd16b0a02ead0bab71953de79cad3a7b2c71.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a70601cd215a202f7b6a48047680ab66f799d3.nq.gz
│   ├── eab4178964e971da0f53a0b734a2971d4293c6b3.nq.gz
│   ├── eb2d938e9c2a6ebe50162fb22f84b1c624d3bf21.nq.gz
│   ├── ebce0c0e4d3dd2acc652f8731b76b2ea83251bd1.nq.gz
│   ├── f0755db1b8cbd5a2ff9e0a57f00b0c045201e5ec.nq.gz
│   ├── f130324628f2809983964959e6716988e1a553ae.nq.gz
│   ├── f71cadb1b2390530fd721a937bfe496c4119f9e3.nq.gz
│   ├── f8343c6f5b3a4aaafdf808c81a0e3a54e713c0bb.nq.gz
│   ├── f9b07c4d93e814a9c8d09e0e0b48609541cbd255.nq.gz
│   ├── fa4f7a5f060d6f5ab6d5d2815967d45322810c3c.nq.gz
│   └── fb7089b8603d5b691486993f70a4f78d70dbd4f8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 14d45af4b9b086aae736f2ce7426502eaf6bdcfa.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 84 files
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

[scikit-hep/ragged](https://github.com/scikit-hep/ragged)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
