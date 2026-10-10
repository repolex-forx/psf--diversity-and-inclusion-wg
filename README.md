# Repolex Knowledge Graph of psf/diversity-and-inclusion-wg

RDF knowledge graph data for [psf/diversity-and-inclusion-wg](https://github.com/psf/diversity-and-inclusion-wg), parsed by [repolex](https://repolex.ai).

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
rlex download psf/diversity-and-inclusion-wg
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 73b21b9dc523abbd61218e342234b9ae19eef9cb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 73b21b9dc523abbd61218e342234b9ae19eef9cb
│           └── chunk-001.nq.gz
├── blob
│   ├── 0041bc0f66e3ccdf3695f9006e06aa485663b307.nq.gz
│   ├── 02591bcd8ef99b9ef8fe3da64c57733e9d1aedd4.nq.gz
│   ├── 07fdd04f68e5b5f9734b24b0812adbdb1403ed41.nq.gz
│   ├── 0970c23c09f068d46366a34bd24954d826562bd1.nq.gz
│   ├── 097661f472b264166672707bb7ba204310c8a672.nq.gz
│   ├── 0bf0f4452d09f9a2f665424498662d3b8da39170.nq.gz
│   ├── 0d9ddf6d1d9cc2980f94e64b47d3500bfac97f97.nq.gz
│   ├── 0ef13942932b378c334b89f5f32552ee1b7c83ec.nq.gz
│   ├── 0f82a8360517d2c8b7d16e85434d40c6fb735954.nq.gz
│   ├── 116eaac31119f87d269dabbab4aaae4f8bee92e0.nq.gz
│   ├── 16721020f0a7172e5d8a8a8484192a7a8fbd67cb.nq.gz
│   ├── 173f5a10697c6ce8de5b0f1802b7b57be20d0618.nq.gz
│   ├── 1a71a1debf16b14d54077df46d77da0aaa83ef6a.nq.gz
│   ├── 1c10972eceaea5bc6ddf055d7e4caa75e01e6f8e.nq.gz
│   ├── 1d5a16f1fbfe540c114014b455a718bfb4ce1380.nq.gz
│   ├── 203239689389f874817b05f7056ba2a8ced0e664.nq.gz
│   ├── 211d852e5b88aadb38e62d04884a21c679cf742c.nq.gz
│   ├── 2262e0caf047dbc27442977c914fbf73ae06584f.nq.gz
│   ├── 22cac23d79be3e8de4eeca6dbd11a1f046a783d4.nq.gz
│   ├── 2c80e77173feae881d63973819d3e0c8d74c521e.nq.gz
│   ├── 2f5f9370b0d03ba773aa7b41503bf7bfa0266a76.nq.gz
│   ├── 2ffaad3f35a26868c6ab113e0c1d41f7f180cd32.nq.gz
│   ├── 30c4c835b3f2d32b5426cd791c7d94ab338e6b69.nq.gz
│   ├── 37313c69eb3697ecf153766f19fe3fff4932a74e.nq.gz
│   ├── 3bcb67ffcc1b85d1456ddb767f2172688d7138d8.nq.gz
│   ├── 3c5cf97ec392bc227363711baf1efa8972fd02f4.nq.gz
│   ├── 3cad845983467ff182997e29fca2466a7b7c883f.nq.gz
│   ├── 3d51b5a48d97b904f3e320315d96713aa9217b3f.nq.gz
│   ├── 405b95b3f09f069e53f77a9d9f4edc7175889488.nq.gz
│   ├── 498317f6ace6e3fc13aa545caf03378bc7f17c69.nq.gz
│   ├── 49ca82a6038c50ac3ce515ad8219469b185657e1.nq.gz
│   ├── 50f29e5185ecfba411828ce203c40992d3e89989.nq.gz
│   ├── 514d5bae56735c7efe0000b40bcd9fcdcecb5a66.nq.gz
│   ├── 567daa0b16c78ca0ed3c9e3c45e90ed71b2f5670.nq.gz
│   ├── 57d9179654e61ab540536657a043554c29b964a4.nq.gz
│   ├── 5e92ffb5eaf75745b5052f92ce1a2112fe2598f7.nq.gz
│   ├── 60f3886ddc8cb1ebcd18722b7c6a563703d17e9c.nq.gz
│   ├── 61849f938d940f627e081441fc6491ff18791445.nq.gz
│   ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
│   ├── 67d68167d9336da5561a6a0bdaf3bfcbc9b7c7d4.nq.gz
│   ├── 6b3f9bb2266ce673ab6d87574c3c1237f9a9ec55.nq.gz
│   ├── 6c899fdde35b960fd2b2c5104a932e1ab6b5cb17.nq.gz
│   ├── 6d6155e6404dd1361d06ee0bde8dc7a0f71a7d6e.nq.gz
│   ├── 6e126c2ba3e698d5a8fe316f44d51972b075a33c.nq.gz
│   ├── 76f17e03e0adac27e1defc84b92ac11f152ed8f6.nq.gz
│   ├── 81264df0db9b444b4de0fc736040736ed05eed32.nq.gz
│   ├── 84e44a6f87684472cb2f7c821f59c14e6ef07bf9.nq.gz
│   ├── 89547c5d1fa8f356505690fda600463c15deffe1.nq.gz
│   ├── 8aa3d1fdd16019f87b2db852b5942e26dc32d755.nq.gz
│   ├── 90f12fed273495f812e03f9e5eef47e2d0824084.nq.gz
│   ├── 9235a9794faca619d90f09f5619590820ac67e24.nq.gz
│   ├── 9349df0b1c3bb4ddc6332df172d62022ae7b51c8.nq.gz
│   ├── 98d722a2e214ce48d454e27cad0afbe97a4a9d4b.nq.gz
│   ├── 991e455bf2a9a5ca20498b4747389b644b14b8d5.nq.gz
│   ├── 9ebba9bb947a849230adc40d5960867afdc996d5.nq.gz
│   ├── 9edacd72ae562be3e3730a2ee758b1e5c81986fd.nq.gz
│   ├── 9ee1919dc230d3433cce79d137c37081c974034a.nq.gz
│   ├── 9f5a174ad93091438d011ab996b4bb9909895a78.nq.gz
│   ├── a0617e354505eb8931ee83506330bd24f33cb1fb.nq.gz
│   ├── a1258764b90bb9e6de10b9f9020c3be8ac0fda81.nq.gz
│   ├── a1711cc3af42cca3416b9e30721b1c0d5956ca11.nq.gz
│   ├── a349dcbda4872dd34460f64d118d8a9bd77f407a.nq.gz
│   ├── a5a611900e68db9f4f039fdb9c1a14070adf0710.nq.gz
│   ├── a8bd390e78fe6b1d2f5757e944dab56b2076d29c.nq.gz
│   ├── b0130675bc106e64547c5837b8ca48b5dd39013d.nq.gz
│   ├── b1a1f3d16d065f01a235edfb96bc158167e1b3ca.nq.gz
│   ├── b6de94d843a22fb5f454e86f19390d1f52ff184b.nq.gz
│   ├── b83f44b4817feb4927e2aa956fde8833eb89939c.nq.gz
│   ├── b8de3cf90358a5a477d6d085e36ec9b22994fe67.nq.gz
│   ├── b9190aa0cd2dd37233e540d32ceb2ee45ba0019b.nq.gz
│   ├── bab035436791fb812e5a86bb5d3a0b363df0b877.nq.gz
│   ├── bb8245e5ae6330776e6c9e16018e3688da1cf0a0.nq.gz
│   ├── bc22d889ef439545ac30f83ccc03fffdaa761dfb.nq.gz
│   ├── bc3495fa822dc292081d89a678b81377e93ac8ff.nq.gz
│   ├── c5ecf25528e5e9d24324a490823d6a0d5e5255d9.nq.gz
│   ├── c650e9d9d87e7a0ace0ac43d712a392b7c546bef.nq.gz
│   ├── c7a0dc2773f6564fcdc79cc9a16a4cf4612d95bb.nq.gz
│   ├── c9efc5844a2627a8474949724a2aefe4ab2baee4.nq.gz
│   ├── cc8c71dbe98b7fd3ae606bbdf9238f4e7044c4a6.nq.gz
│   ├── cc9fd67dae7ca8d0aac6e7319102cb9e15196cdf.nq.gz
│   ├── cd2d64a9c65385964678d0684097664e0b4ae86a.nq.gz
│   ├── cdff5b0a8e6b9387ca28fc11832be80afebc0d76.nq.gz
│   ├── cea32b7c3410b5b9ed385a6ec47d4be966d02d56.nq.gz
│   ├── d15728c25c6b765c784f1907f9b156ea83db84f2.nq.gz
│   ├── d1d6a96e42ae84feee6af3f55ecfb487ec216f72.nq.gz
│   ├── d2461c42aa3e64cc58b1d219fc5540ece3716f3f.nq.gz
│   ├── d3c59737d4d885be700c4458c69004105118e676.nq.gz
│   ├── db9939d0a207e233c8192fd43f059fc8185bcf44.nq.gz
│   ├── e3a85033f96aae22cae600b5c09a4781f79f5ec9.nq.gz
│   ├── e5f0a03f124f3688de8aa2f3092a2f358f0fd90d.nq.gz
│   ├── e5f6e29f5013999717e141bcc473210c75ffa0cf.nq.gz
│   ├── e69c5e39a30ce8d112e012cac36289e77691a9b7.nq.gz
│   ├── e7bdbefd2fb2b16ba52802312f822a1b69d587f4.nq.gz
│   ├── e9cd95e975f156d0d3ea6f546975d148fdeafbd6.nq.gz
│   ├── edb274eefdceb6dfe5f1515d1245d6ebc337824b.nq.gz
│   ├── fbafb2222245dff62858859f0a2f916908864051.nq.gz
│   └── fe1721e49eb9fb77d7f965461be96bfd5e2e30cc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 73b21b9dc523abbd61218e342234b9ae19eef9cb.nq.gz
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

[psf/diversity-and-inclusion-wg](https://github.com/psf/diversity-and-inclusion-wg)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
