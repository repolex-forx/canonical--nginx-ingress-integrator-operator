# Repolex Knowledge Graph of canonical/nginx-ingress-integrator-operator

RDF knowledge graph data for [canonical/nginx-ingress-integrator-operator](https://github.com/canonical/nginx-ingress-integrator-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/nginx-ingress-integrator-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4d73fd27fbcaa676d616f11022d743c613c399a8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4d73fd27fbcaa676d616f11022d743c613c399a8
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a3c657552bc97297063b55acaf786f3caf9b48.nq.gz
│   ├── 00a3cc2c599f5f9cf074514f991d2e608000367f.nq.gz
│   ├── 0309297d00f077f32d74ccb1a839a280fe131319.nq.gz
│   ├── 04c56da5539dc995aef8768956bd60284131fd2a.nq.gz
│   ├── 05238c7ed2a31ca10b5b76b92340168c43ccf2d4.nq.gz
│   ├── 078b8d3baf58e7b1914704173e8d374f9acadfb7.nq.gz
│   ├── 07e0b48cbd1569fbf0e610fa77b6a4e96330574f.nq.gz
│   ├── 094faf5500bcf2648d787f57857436b15cead495.nq.gz
│   ├── 0b671955f9048d0ae1890f470984fc313b973466.nq.gz
│   ├── 0c2958d2cd1a885f2590ac56995bb792eb0d753d.nq.gz
│   ├── 0c9be3cfcda7817e4efae9e93972d99c8e372a82.nq.gz
│   ├── 0df58f46158e4e59401a64e71e18fcf067bb4af0.nq.gz
│   ├── 1652342ff670823078fa1384b7c74f985f290db8.nq.gz
│   ├── 17b5e6c699f1498a743bc9ed7c7970fb22cce6ed.nq.gz
│   ├── 1847ef356e2b8a424ecdc55eb89f43f1796d962c.nq.gz
│   ├── 19ea5789a3e7f53b8efd90a4da53448f647a2e2b.nq.gz
│   ├── 1de83dec0ebb64006f6944c54b487283d6cdf3af.nq.gz
│   ├── 22a77b55c8002b96a92ab998437297c9c03e7496.nq.gz
│   ├── 240d15dadd37c36c0fb8d993911cdc6eec3e4c74.nq.gz
│   ├── 2469657089f401aeab5c0ba4b00ced0a8da5dbde.nq.gz
│   ├── 26ac226df88c6bc3785214f437d30606702a7736.nq.gz
│   ├── 2876aee1d588c5b5c9715b5097f68dd02abd6d23.nq.gz
│   ├── 2c505165aff6c99d4df0c68f1db1b41b8adbb07e.nq.gz
│   ├── 3006f13e199b573708dde2114878ca4fa8071aeb.nq.gz
│   ├── 3014a84f49e5da629a320e61b44bb11e73fea385.nq.gz
│   ├── 307b5f2ec4afd37039c61500decced8f538bc94d.nq.gz
│   ├── 3372cdf832ee05e9662c2b38bd09673703f18820.nq.gz
│   ├── 348244c6fd11ffa2cc23d13c622026bc18847910.nq.gz
│   ├── 3561e99ffb8c6654466d5b7a3df57531385aee5d.nq.gz
│   ├── 35c32b4db998fa5e928693e5579f58ee4554cd3a.nq.gz
│   ├── 39664facada09e572d10efdcb7b510b83e5a9f6a.nq.gz
│   ├── 3c038a5b4360103c32fecef27d6ca8218751e44a.nq.gz
│   ├── 3f9d71352456b463ea63cb574a966266556ffe5c.nq.gz
│   ├── 423441f4735e58af8b21199e9d42ae80a1bc9a1f.nq.gz
│   ├── 448fbbe8bdd2d4b11a4796d54de07cc03e3b45a6.nq.gz
│   ├── 459d0c786194cf4d7b8ac2796f55914e617bbd7f.nq.gz
│   ├── 49f620782bbf82f983bf1d889d98293d0f184b0b.nq.gz
│   ├── 4aacdf448015d771ba3d89b6aa94d894c2e1d6d2.nq.gz
│   ├── 4bc9e1e955b212f5d21288ae5ece52e1bd0825a3.nq.gz
│   ├── 4cac3b988a5db799200f86b345b63e3d9ee63097.nq.gz
│   ├── 4e590af7aca5cfcb94428ce8d15441833d0b997f.nq.gz
│   ├── 4e7cc9273ce3c10a2c25173b0cf8e0ce670a3cdf.nq.gz
│   ├── 5078a5c7bce96a95c14bc786fd96fa9de12d12fe.nq.gz
│   ├── 51c9437c6e5ea89229cdf6b19677b93f7c5da373.nq.gz
│   ├── 544eb06814df501b5b28784b5b3c3eac83039388.nq.gz
│   ├── 593231fb876bcb55db576f689413bc64e3eb730b.nq.gz
│   ├── 5e3ca03f221f02f5df484890ccd12723c56b3435.nq.gz
│   ├── 5f255ae4ff360f8be1baeedfe82700dcbf422974.nq.gz
│   ├── 6022b421c19f4c6051255a4cb03f7d02b335b342.nq.gz
│   ├── 64aa6d728cbfa29a0a373eea7f288fe6a8954c94.nq.gz
│   ├── 64e45a222ce27e19230b2289d8ff060c8f03a63c.nq.gz
│   ├── 68139ec2579a8e555299d262cf2b8ace3295e513.nq.gz
│   ├── 68ec1b56e355bb653aaaa46d8e11b090ff22133f.nq.gz
│   ├── 6b6522c238871203506ceaa03c83f2d7b70b4aa8.nq.gz
│   ├── 6ccd559eabeae93e4d23215fa450130fa9b37ace.nq.gz
│   ├── 717a028d2463241748275dcfe8833e24c501e699.nq.gz
│   ├── 759336e89148a0cc36a47a82b2397ad4bf7e1bf8.nq.gz
│   ├── 7e64809489fd3ba1fe40d25ba4a3d2535ab696b5.nq.gz
│   ├── 7e7bd07e9fc7b05dc58fe6da696e18299b41ecff.nq.gz
│   ├── 7e9d50461abcf8053278e38c1eb264abc49fac0d.nq.gz
│   ├── 7ff0978da0cfc9a46b4033e5139574a754528088.nq.gz
│   ├── 7ff4cebf4f0afe30dc9bcf791b3b1ce5ec1c726c.nq.gz
│   ├── 8dea7bc43885c417f6190c8b9652f9930c7bffef.nq.gz
│   ├── 93432d715e2ce61d360073aba151819464930aa3.nq.gz
│   ├── 957f7208cde03877743a01a0b92a592194fc9e8f.nq.gz
│   ├── 9683aeb69c50512c74acd5a197c781b52f892f6e.nq.gz
│   ├── 96c8accd963dc6100e857eb74e091e4f11f895ee.nq.gz
│   ├── 994c6ccdd40ba6095130eb827c26fbd35195436b.nq.gz
│   ├── 9b0aff2f853825bea326f4f06c277db9b234e2f2.nq.gz
│   ├── 9c99629e5663f25fd169bb2cb742c9436714c79f.nq.gz
│   ├── 9e8948dd64dd77612cc7b785b868a565ea01391e.nq.gz
│   ├── a0cd06b9cd411b9011814306b59d5855700ebb87.nq.gz
│   ├── a15c8f31c4ace90ee087b6209a1d81daf2735ca1.nq.gz
│   ├── a1ec8cb70e4647d4a3d6ad2cd612d3c48d55abc8.nq.gz
│   ├── a3b6039d68708921a32527221b0ce920624a1eb2.nq.gz
│   ├── a4072c12cc73b0ca7ef520f949f86d66295e2c94.nq.gz
│   ├── a990a83bf38818a5742d21f3327fd1d25c4728dd.nq.gz
│   ├── af3c3b54fdd33e291e597ac56b3ea69988aabd31.nq.gz
│   ├── afb1aba4baf0dc082389a0e787a445cc5af166de.nq.gz
│   ├── b09404ae6f93e66ea326ea68268b6c34c7a62fa8.nq.gz
│   ├── b4899207bd5505af280539142219819e8f24560e.nq.gz
│   ├── b578ebc13cc47f4063c76d043ca64856d6f47062.nq.gz
│   ├── ba05d79e60909f7a030e9564085163d5cd1591c9.nq.gz
│   ├── bae604464ed98a2e93e07a5db9b36085d039f55f.nq.gz
│   ├── bbf9af1d88b02ad98188606e19067d2848ea1a3f.nq.gz
│   ├── c12140bb7122131b7664e6f3d326f65ccfa9ddd6.nq.gz
│   ├── c141718af4e80bca53edceb06a588d7d99140402.nq.gz
│   ├── c2d42f441425d2e90754427c7b440adb1b6ff383.nq.gz
│   ├── c51f8731433ae312f489f87b230c5aa38ef668fa.nq.gz
│   ├── c553ccfe0d7eaded53e6d7c5a02284ea775a0b0d.nq.gz
│   ├── c839242655f9c96011cb964792f8cfc4a92a3968.nq.gz
│   ├── cd00e4646099a38c6e2400f48853beec1722aa85.nq.gz
│   ├── cd4df0ce1231f0318e8e58cefe940645387d319d.nq.gz
│   ├── cd5ac039d67e0bdadb17976e4ac39f0ffe6bb6e4.nq.gz
│   ├── d45832cb839c8072aa5eace71b9dcdfed93a58da.nq.gz
│   ├── d7c9a9d77e0a318941718b641439f1d74f8ff3a5.nq.gz
│   ├── d97556480995caf2ea112fc9fbf248c7f63d4107.nq.gz
│   ├── da1e2049eb420c5e26c46849af0ee747a58fabcb.nq.gz
│   ├── db2308ed024fcb23e2847aa5041227af9d469269.nq.gz
│   ├── ddbddbb3e182ced55374267e0b5d1a8ba0bf8527.nq.gz
│   ├── de6e0dbfaf18615b8930d706251660b56f9fd902.nq.gz
│   ├── decd305263e7628b25c5746181a41ac73a645d76.nq.gz
│   ├── ded5cd278ca6c6b1252e4881d04c5ac5698f3dd6.nq.gz
│   ├── df541556b4c8b8d1d2040a3acdf1aa8872e9c1a7.nq.gz
│   ├── dfa0b26b9e10e3ca7f619806f6a35c2ed514400f.nq.gz
│   ├── dffce0636d6c3faa9e37afacd80534f0dbea0973.nq.gz
│   ├── e0f220ac94dc2595dfc7294907f8748fff6a11f0.nq.gz
│   ├── e44ecd9e18bea79b9e6718901827a96a3a949fca.nq.gz
│   ├── e5c83b3241875371994d90a02ebc8f623e0bc0b4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec26cd6741bbb64e3e4f5fcbb4b5e71903a197f4.nq.gz
│   ├── f0bc42a89bec0943d8383fc05958e4b341da0eb4.nq.gz
│   ├── f4e30c56a97efe41bb7baa39ac822b3e4b4d694c.nq.gz
│   ├── fc18b9fdffb3a14f91bb7956c25d13c4890e82d7.nq.gz
│   ├── fe6468e8d0a1957aba024423c38b9eac57f996f6.nq.gz
│   └── ff5c89b16402c932ffe0833f0962b3b494133f85.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4d73fd27fbcaa676d616f11022d743c613c399a8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 124 files
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

[canonical/nginx-ingress-integrator-operator](https://github.com/canonical/nginx-ingress-integrator-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
