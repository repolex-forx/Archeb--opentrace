# Repolex Knowledge Graph of Archeb/opentrace

RDF knowledge graph data for [Archeb/opentrace](https://github.com/Archeb/opentrace), parsed by [repolex](https://repolex.ai).

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
rlex download Archeb/opentrace
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1f4dc8397780e084e1be9e33eb1adb742d800aa6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1f4dc8397780e084e1be9e33eb1adb742d800aa6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0aa4b4aa7d54bde7a8ad23c2a2c62549cc21f1a2.nq.gz
│   ├── 139f6c3f261943e42aa3872862ab54076d1e0d16.nq.gz
│   ├── 142610e31c2755eb72b97a085fc09c1dc8d803ac.nq.gz
│   ├── 15361c5aa3b34a3a9ab4646bef19b0e2e049b56a.nq.gz
│   ├── 17ded54df00ee2a6328463ec2baa4afa1137cbdf.nq.gz
│   ├── 185809d60c432f16a34532c328fe8ceb918b19aa.nq.gz
│   ├── 196727215b4c1c1b9ee288df18c179a40491d4ed.nq.gz
│   ├── 1a7d11ac635df6a4cae2a7edccddb9855201e8aa.nq.gz
│   ├── 1c43fb79a1d88b8e145cee49fcc02d587017970f.nq.gz
│   ├── 1ec07b6f60ceb8d8b68e4aa1265b98a5dc9486f6.nq.gz
│   ├── 1ff0c423042b46cb1d617b81efb715defbe8054d.nq.gz
│   ├── 218ccaf423ef0a67696226f9ef3a09149e4441d0.nq.gz
│   ├── 26550b039d578a2fcedc72da2b719783424ee59d.nq.gz
│   ├── 275133768c947ad6b0d14311ad79b04adb1cf62e.nq.gz
│   ├── 28be1a4cde92b262d609d5b07d82fc5fff4817be.nq.gz
│   ├── 298ab853f593acb45c08955b6f134cab5cadf901.nq.gz
│   ├── 2ecbd7ec872c741a529d499d34b5cde7914506e2.nq.gz
│   ├── 302bdefd244b82cda85b8d74eeaa3422ded32e67.nq.gz
│   ├── 306232887dd745fc944bc0586d1fd64b5765e2e2.nq.gz
│   ├── 33ea50c3fbea8564e94554292d2483caafc1cbf0.nq.gz
│   ├── 39b879bd6f0c9ef25522eab223b33dd9c919014e.nq.gz
│   ├── 3bb330a2a26618c14fa784dc1f79464bff1aa518.nq.gz
│   ├── 3cb7f950e1b5c03638b2b700626d0ec37bc5a043.nq.gz
│   ├── 3ce929654fa206b6a758414976fd735f72f74406.nq.gz
│   ├── 3dfd6362a2c1144dbe9a6cb87f2c78e444264c86.nq.gz
│   ├── 4a837de4679c23ffc6ca16111522761d4ba8b95c.nq.gz
│   ├── 4ebcf57c08b209d2df1a0bfaae32835702a2f5a8.nq.gz
│   ├── 4f2b9aafd72c5f7a2d93f88bc19eed5c59987ce4.nq.gz
│   ├── 50ca874308a916f834e02a749bcce365673426f3.nq.gz
│   ├── 52254e6e26a5326b85cbc047ccd82a3c03f87e1b.nq.gz
│   ├── 5e915b06ca863b599c30aeb55a07de8516397f12.nq.gz
│   ├── 5f785565944dfed3f534d068bb47b7c78a6f0fed.nq.gz
│   ├── 67016d238b66644f4ad8bddf458bc5e04336cab1.nq.gz
│   ├── 68996c262668f0061afcb0b75d1e73ff46c94fc6.nq.gz
│   ├── 6a4250bcc1bebcc7fde927c1976db98c3e486c08.nq.gz
│   ├── 6ceca1db77714822b175c3b28264f7ae95450e31.nq.gz
│   ├── 700d89c3e28c4cfaf4a165c540c3e889828218c3.nq.gz
│   ├── 7d774639b9a8f359e51829ba569dc0ceca830a7a.nq.gz
│   ├── 81b6ef9de06bec2f5c1571419589e9262659a5d8.nq.gz
│   ├── 82e7d4aec4c8d17776ba156e36a904ebaf8bff68.nq.gz
│   ├── 85299b1cf800b4fa1995ac529dd0898864e0df19.nq.gz
│   ├── 8682c3305f69bacb86cc4cc10ad8667e5ec9ba8f.nq.gz
│   ├── 8909b1888e4bd50dfdfde6c5ab355518fbac2e97.nq.gz
│   ├── 89f8b535f76cff1a752b75e0e050e93a0df4316c.nq.gz
│   ├── 96f30690210e960e2e9653947cfb91ad0a32aec5.nq.gz
│   ├── 99d466405e5ae1a140d2229af2bc9000b23bdc52.nq.gz
│   ├── 9acbcfa5cdd13c08ff1c11e164fb9b97a28a35c0.nq.gz
│   ├── 9f0a819035fb53962d8f2b1eebcae6b434cbf1b5.nq.gz
│   ├── a0e1bef6a79e3856d3e319ac926fe358d25eeb66.nq.gz
│   ├── a80347899b359fdd2957e120a5ce79f509e97012.nq.gz
│   ├── b27f794b06742f63abdc9bfc9251c47c1d56bf46.nq.gz
│   ├── b638ea83eba93a8426e456fbc0b945c80b916a8b.nq.gz
│   ├── be409baa3c80d158f37c812940dc4458da2138f1.nq.gz
│   ├── c240b5508b088699056b9bd8ce627b2e6d988898.nq.gz
│   ├── c2a522f809d71931cc3ded2dcb73d1e6437241ee.nq.gz
│   ├── c7146a04d87fe9836d511975979214c94a58fe08.nq.gz
│   ├── c83d52020eddd59014b47e10f984244647959795.nq.gz
│   ├── cd221febea0b6e11e9f54f5a47e92c64182159d5.nq.gz
│   ├── ce966403328bbc1a6e435cee9257960a198eb590.nq.gz
│   ├── d2bc4275346ed1d3c9560956645104e4e7a8df74.nq.gz
│   ├── d3c0eebf0b92efe92eceae362b65f94561c02c50.nq.gz
│   ├── d6e2f09d2116ff47698b6de7d7e00650d2504118.nq.gz
│   ├── e53c1497d048ef47b7710fde77c9547d1c4b3057.nq.gz
│   ├── e9aacf5b2b0921221b8a9e81973280cf724ca294.nq.gz
│   ├── eb0bcf8cfcf0d0ebca43e9c8acef353925f51c47.nq.gz
│   ├── eb37bf3f04d7cba817135722b3137bfb4d16e20a.nq.gz
│   ├── ebbb793dd66914a5678f4176af6b0261c282ef38.nq.gz
│   ├── edd29212f800b38ed38f2879176b084a5fc1a490.nq.gz
│   ├── f0ad287acbbdf72fcbcc41b04e4140001e7aedfc.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   └── ffe61c5cc128b8a1b09f4cc15052d7736f1241c7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1f4dc8397780e084e1be9e33eb1adb742d800aa6.nq.gz
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

[Archeb/opentrace](https://github.com/Archeb/opentrace)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
