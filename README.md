# Repolex Knowledge Graph of ansible-collections/frr.frr

RDF knowledge graph data for [ansible-collections/frr.frr](https://github.com/ansible-collections/frr.frr), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/frr.frr
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5c9f81e119963d4d0296d23aefe6010bd819f64e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5c9f81e119963d4d0296d23aefe6010bd819f64e
│           └── chunk-001.nq.gz
├── blob
│   ├── 00f94dedf37994bef04b51cf86f9f15138ea57b5.nq.gz
│   ├── 0b4d2b8d38d706b81358c88e08ab576fe3c7933c.nq.gz
│   ├── 0b6292e0bf340b1a6c1c1fec246c306f330cca60.nq.gz
│   ├── 0fc53edcdc104efa7c05685b3648ba21472a1aa9.nq.gz
│   ├── 143bd6474344843a3de55ab4dc47e501f98eb9eb.nq.gz
│   ├── 157979e97712832c1fb1cc6170bcdb5374753683.nq.gz
│   ├── 1f9858c45831f17e4d3ddebab73b2a101688310f.nq.gz
│   ├── 30ff73b36270d2d79f38607f9e32414915ceb97f.nq.gz
│   ├── 3adaf90cf207b547be00163de2d9479bad14bf00.nq.gz
│   ├── 43e9304ce0aac759965267998a38602a0ebd238f.nq.gz
│   ├── 4a32e05a39997d4ca32eba3ffcc9c7fb36b85c0c.nq.gz
│   ├── 4bef8a35d7cc318839f64ce02de75e16093dcb73.nq.gz
│   ├── 4e139f56236f6064fbf665ea91d4a2f88d5a694a.nq.gz
│   ├── 6006ba9653d05ff7f84d090b3bfe82bfa3b238d2.nq.gz
│   ├── 62f08881f5835c410306d1d49bc0c590ed4ce7a9.nq.gz
│   ├── 631d2d5a0cafbbf8a5ecbeff4bb3d38d761748a5.nq.gz
│   ├── 66ec2838d6a480e4b7f9497b1a5202835f61e984.nq.gz
│   ├── 7883947b59e3bcb5558a3b0d35e738fb321f506f.nq.gz
│   ├── 7a6c90cdd02af88d28bcacf5ef8420c8a5795ef4.nq.gz
│   ├── 807fd27b86eb516e15009aa5f2a8b265cb5c48f3.nq.gz
│   ├── 816cb44098cc8881b333f2ca0a8f8a1d8f57df8f.nq.gz
│   ├── 8e94bd7a59afe7c3a9b696747f0b1712d0e909b9.nq.gz
│   ├── 93f7f9a9467f1488b75a31ac160474a4007cbc7e.nq.gz
│   ├── 9f980a682661fd21aeb97703c0f2dc3cf262251c.nq.gz
│   ├── a401eae2a931ccaaea2573493313b50582ae78ed.nq.gz
│   ├── a9772bea1f6568ee5ddb0c318a980c20204d88ce.nq.gz
│   ├── a9da20e86e166bd417df7c0b5c3edaa956314cdd.nq.gz
│   ├── b3159d7690296680c3555aeca82a6e22784da984.nq.gz
│   ├── b425edcc2da5002c0ac2cf1264e93775ff17a81b.nq.gz
│   ├── b483eb5db497acb4be90303d6cea24865ee6e855.nq.gz
│   ├── b995de0cae12b1961330e89aacd31bce296a2ba9.nq.gz
│   ├── ba9c980fb86bef62c1cd5c86cd09c6cde80b0cd1.nq.gz
│   ├── ba9db041ea6a065531308bcd0978082e44ad4e94.nq.gz
│   ├── c22bf988194e8fd3cf20c545eb8044bb91e4e214.nq.gz
│   ├── cd0bf4ceb32869f821a01c30c813da3eeb9bee09.nq.gz
│   ├── cdd40997a5659b9fc343baf4ce068191e2feabea.nq.gz
│   ├── d64a9a4c5cb5ddddada0395e33cca8c294a05f08.nq.gz
│   ├── dab258614eb85c973bd4e55c34905da805a80add.nq.gz
│   ├── daec039dfc96b1cb8c6f4e646888a4533a5c21c7.nq.gz
│   ├── db7e126448e884d45ffbdb986f2348d00faa8f2d.nq.gz
│   ├── df4266ec98ab8a5df6571164d19f4cf1423fd21b.nq.gz
│   ├── e0b4fe578750ff5c4366f28e17203ad7ddb57875.nq.gz
│   ├── e25e8381bd6f93f32247f1b0d29c500defd872e7.nq.gz
│   ├── e3ee6a41f6c1df860a090b306f8bc68fe5101c62.nq.gz
│   ├── e4a8c178d14d02e4a78a9c971d3e5b483d80c576.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea1472ec1f38b2d1410951194a02f8fb9f1c820a.nq.gz
│   ├── eeecbe7ae60c4183ce88f7bfec0814733bab81b2.nq.gz
│   ├── ef1b0cb9c3de9962871da97f3befc56749f84ed4.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f5987902a2d0da33afbcbffd97306880619464cd.nq.gz
│   ├── f6160e26a5cca630155b9c5dc55ba951d65e4c7b.nq.gz
│   └── fa4225f3eddd267a91bdd4c2d2ccee679c90ca97.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5c9f81e119963d4d0296d23aefe6010bd819f64e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[ansible-collections/frr.frr](https://github.com/ansible-collections/frr.frr)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
