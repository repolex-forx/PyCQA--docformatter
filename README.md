# Repolex Knowledge Graph of PyCQA/docformatter

RDF knowledge graph data for [PyCQA/docformatter](https://github.com/PyCQA/docformatter), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/docformatter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f8303162e613ae818eeeea0027cb0f8294065ce9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f8303162e613ae818eeeea0027cb0f8294065ce9
│           └── chunk-001.nq.gz
├── blob
│   ├── 01b8e20160d54cd9c96027288aaf8d53c101f2d8.nq.gz
│   ├── 039640d41d1b8b58057c77067abb7f6b682b39e6.nq.gz
│   ├── 046a29850a6132b09dcb8ec0089aa2900e699d78.nq.gz
│   ├── 0c2fac327d1aba9ad454841a98d789d78060954a.nq.gz
│   ├── 0c5feaff64b00250bbb92409659dba97f5aee143.nq.gz
│   ├── 10435fcd09b48793e4a3d53aa33f48fc3bddbca4.nq.gz
│   ├── 13f645b0f08eff61d126652f2a1f6d5dee54876f.nq.gz
│   ├── 15197ca18768dcc6535c4331779e52646b3f477b.nq.gz
│   ├── 158a4cdd1367227c1f6dccceca68f928ff1eb6a5.nq.gz
│   ├── 17b93a6560c684ff958085c43c799e51e3a679ec.nq.gz
│   ├── 1a73b9863503682f25a5fdb2d805bca72016d24e.nq.gz
│   ├── 1c1c93abb402cba18b476e3e674971d52f297c8e.nq.gz
│   ├── 223cb3362c90f2929dff6912fd235e7627d61102.nq.gz
│   ├── 23b371c8e8003dcfc564eca12a2d3abd95d73884.nq.gz
│   ├── 251e4f86237fcc2cdddcef5043d5721d00e2d953.nq.gz
│   ├── 25718cc750d13d8c37157771182566e701eda48c.nq.gz
│   ├── 2be1184fe49b84f66e37630facdc7c3f8eef5866.nq.gz
│   ├── 31e049f8f73b57675b9f18533b8f644ab0380dc7.nq.gz
│   ├── 3634f657a2ac4f2ee967994eba10617d6be068d2.nq.gz
│   ├── 377b807190c5e12c86c09719ddb3dbbb367a046f.nq.gz
│   ├── 391e7d6e708073b59f7d030631007073c67f7443.nq.gz
│   ├── 3c2ddad2425af318fd4f4dd8faf1f4fb4a2987dc.nq.gz
│   ├── 3e032a3aad4f0f444260a5e8188f5525e140321d.nq.gz
│   ├── 407b105e9890b68b0e8d1e59a069af35b51fdf7c.nq.gz
│   ├── 41652f34f58376d9652a89c058f3c3a9127d2c16.nq.gz
│   ├── 426110020f97008c6b58919c1cdffcda8ece9935.nq.gz
│   ├── 43733e8e4c00de738cde7d5c18d6a4035bfef3b4.nq.gz
│   ├── 45a15a51c92db75b99c638b4e84bdfb6d9574349.nq.gz
│   ├── 45e789c5fb1136b5365595e6417f6e5535912575.nq.gz
│   ├── 4b8be3c3033ba78472ca9efab5301549aeb3267a.nq.gz
│   ├── 526fcdfbc74f910beb3cca4b425abf8d76526acc.nq.gz
│   ├── 55f8e6e2ea9abe9a61cf49962f4f10f1241a1dd9.nq.gz
│   ├── 5b95a8e3f0fad5fc51ba367a2705b62eabe84dc4.nq.gz
│   ├── 5bd3613b97871c79eeee567ee0700a7f4694f042.nq.gz
│   ├── 5d38b5629e8403b997b1aad4c2355ae492ac257a.nq.gz
│   ├── 5eaf987059af3ef986ae67fb74051ef4e9c4a85a.nq.gz
│   ├── 6008b2c939b1d14a56cc35bd3d7f09076628cdd1.nq.gz
│   ├── 61721a27c32ec12a1d23ab1199ca7e8fd6b086f6.nq.gz
│   ├── 6658257ac561edb62d815f682e43a46a285ffebd.nq.gz
│   ├── 69ead95e1627a54b8c367aacd3f89f7e9e3b5733.nq.gz
│   ├── 69f71a6f1b8b145d166bc1d84bf9288c7e3d0a2f.nq.gz
│   ├── 6c8caa77202e04525681b96d7074397c1315ed6b.nq.gz
│   ├── 6ef97261d813e0962e795b2fbdf2fac18f33ed90.nq.gz
│   ├── 72fffeb04bc755231d762bc0c46483dcdc3b42f4.nq.gz
│   ├── 734bbed6875884244c59f45e631bf1c0bacdfc81.nq.gz
│   ├── 7bbf72b39d76b047a5541c6058085f9108307a4c.nq.gz
│   ├── 7c1478ea322b7221c1051919cacdf04e458742ae.nq.gz
│   ├── 7d9cd0c0257b680f2279f695b51546a870b0624e.nq.gz
│   ├── 7d9dd094127049ccc052a383d81a61371bb3399c.nq.gz
│   ├── 810f66fdab1846addbec847407eeabf174f19b69.nq.gz
│   ├── 8290a6085752db24523f1b28c3de10e1af39f86c.nq.gz
│   ├── 835cbffc7182d79c716da87116ecf4a12bec1acc.nq.gz
│   ├── 8759bf0b2dd9d8ebafe676b5ac7c7c07ad757858.nq.gz
│   ├── 878a56b140e9b9926f32a42761c5d9f79497a4f9.nq.gz
│   ├── 89f8d3f163c113dacb5a45ff9f5558e456323aed.nq.gz
│   ├── 8a0876da15220230076289281c121c81d580c4c6.nq.gz
│   ├── 8abd0551275db9a830d25646ec411693b2a83142.nq.gz
│   ├── 8c709f9eb5717f2192563716c70ec036dae58856.nq.gz
│   ├── 8e58780464be6366d8d562008816570b743dba48.nq.gz
│   ├── 9205e720dbd0fcb452007fa12ab51a1629edb583.nq.gz
│   ├── 92db5a468af200d5c67c5f3c1674d273c6d7dc83.nq.gz
│   ├── 994fb221f4103865d8aa1a8da71e24166991e372.nq.gz
│   ├── 9aab5120ab2ab7d3a8f137f9e7d7e5b3f989e820.nq.gz
│   ├── 9aaf4a07fea87aa9dfdbbf1f21c411aec7cfaf4c.nq.gz
│   ├── 9dbef0a26537149c780686ad2681fba4a25efad1.nq.gz
│   ├── 9ed42fe6e1e310f54315be85aae1293434580e60.nq.gz
│   ├── a003f9d0d552127f0ef0ad89da01929c58db04da.nq.gz
│   ├── a3d0266453424084664ae4c87a636b2cd86cfc9b.nq.gz
│   ├── a3f2189d6712a1988ee662965de2911f1e1944ab.nq.gz
│   ├── a47522e14430e99fe04d70bee6f98c9e229ddd54.nq.gz
│   ├── a65cd323db9d7d4a3f84c89c3f312e0af12c96b5.nq.gz
│   ├── a6d2cd6e4511229035c62fef9566c90f211ae27c.nq.gz
│   ├── b06abfc0ae3086f41b728bd17ea82599e6033a72.nq.gz
│   ├── b07fe79f1e04392519daa9e5210b61437563047b.nq.gz
│   ├── b79e96a738b4086f2815b88cf039c1e280d30128.nq.gz
│   ├── b80f2218a6f9e63b42d468d15ffccdc23a41c156.nq.gz
│   ├── bdd3c85921921c099e006b2e6a2ccad31e7a1801.nq.gz
│   ├── be99438bdd11b740504c40eee9fa02f5a1655e44.nq.gz
│   ├── c60042a7bc55bdc2f353d04bad26ff87caed2364.nq.gz
│   ├── ca02e2b119abb9b16287b98285c3df686b52b470.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d1c89781ffebd97b2e47756a0db5e4e790290e27.nq.gz
│   ├── d2f188a36b49b9a4aae082d1c190ffde41edf8aa.nq.gz
│   ├── d519fd014964e80a23a9538e7090ff162edeb40c.nq.gz
│   ├── d5ea0326fbb79e23625dc5c9636afeba21c0affc.nq.gz
│   ├── da0e02506e484bae2b878cedee6f14e8ada5e9e4.nq.gz
│   ├── dc1312ab09ca6fb0267dee6b28a38e69c253631a.nq.gz
│   ├── dc684ea53bfc01cd7c5caca9c7a9415b8ceeaa37.nq.gz
│   ├── e4e60003b0eb6462384110e396ce723ee1110ac2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e93571079b2163a96d381d839d2200792ea31f5d.nq.gz
│   ├── e96c823d131d29cafb67d412da5c277a31b11867.nq.gz
│   ├── e9799a91421af6ca0639a8e85a55a9834fdeb0de.nq.gz
│   ├── ec113982b4effdeab1b2623e663e5d04cffc3c87.nq.gz
│   ├── eecede68c58bcef875f0b7c1499339f75466d6d3.nq.gz
│   ├── f5c6ffc36196b1224aa3a4568054811bd8c878ac.nq.gz
│   ├── f799c0fd7d2d67e0325d28f43a2f9e63f4bc7e59.nq.gz
│   ├── f9c0ee311d3f09f9dc37825ddb4a2d546669b154.nq.gz
│   └── fb481c96ea16ca0fad91a9230091386dcf185a6f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f8303162e613ae818eeeea0027cb0f8294065ce9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 107 files
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

[PyCQA/docformatter](https://github.com/PyCQA/docformatter)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
