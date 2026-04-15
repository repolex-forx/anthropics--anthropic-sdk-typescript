# Repolex Knowledge Graph of anthropics/anthropic-sdk-typescript

RDF knowledge graph data for [anthropics/anthropic-sdk-typescript](https://github.com/anthropics/anthropic-sdk-typescript), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download anthropics/anthropic-sdk-typescript
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0b536ae0e9c16ef63bf08a0e4b7150211b085d6e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0b536ae0e9c16ef63bf08a0e4b7150211b085d6e.nq.gz
│   └── repolex
│       └── 0b536ae0e9c16ef63bf08a0e4b7150211b085d6e
│           └── chunk-001.nq.gz
└── blob
    ├── 009f03aa92dabe6e1a7bec3ebf3660fe9122ab10.nq.gz
    ├── 00d7c372f38fcedc51b53e2bb0cc6e5e07592341.nq.gz
    ├── 02628aed0d5346a734db93ff65c151dd8ac193e9.nq.gz
    ├── 02e586721cffe4451feb8867d12af1955b444a9d.nq.gz
    ├── 040414c12c25e05c62de7ec8b295418ae46aea1e.nq.gz
    ├── 056af0d77f15391e8989244647e028f1f5860d85.nq.gz
    ├── 0651c89c0c6690f43c6c85da956f4c1713d793da.nq.gz
    ├── 07397ea503395fac5a3a3d69396bc17b4d954a16.nq.gz
    ├── 0a70db3e6b900fb2b39a24b16fda1bd53934029e.nq.gz
    ├── 0b45a86b3fe143b4258bd7e094adf838ebcb4693.nq.gz
    ├── 0c7cd2fea475ddf85f6ab2e5785d750fe9b98eb2.nq.gz
    ├── 0c8b7a42829a3e250686a7197ecd9b150b97e216.nq.gz
    ├── 0cef491b666d8e5c18e9d5d59e742f8fc6a5274b.nq.gz
    ├── 0e0d4257317051ea07e5c3e03c1d70dc6189406e.nq.gz
    ├── 0e4fe1b823bb14692b8fd1a6898da685662b7ba0.nq.gz
    ├── 0ef75287e495970351c22a7a461d547b61da9712.nq.gz
    ├── 0ef7adec2115b51d92846fa9a82837d9d336ab2c.nq.gz
    ├── 1227adaa47421898f8038667ade1c0563002ac49.nq.gz
    ├── 1354eb4329a078332aaac419d6cba1e2371b3cc2.nq.gz
    ├── 13737de2620e3c799a03d6e846ec294d1ac9469f.nq.gz
    ├── 13f237413aa57823d8e3720230147780228542d5.nq.gz
    ├── 1542e942b513d490a80ef1a063f8f7221de8b0c1.nq.gz
    ├── 16fb081f7f5110108f3c4fd93671e786b16ba411.nq.gz
    ├── 19a3d407f4610bfd6e09869fdf3f4709c484e305.nq.gz
    ├── 1b8adde1d7af7f6ac962e5c31425013513db7da2.nq.gz
    ├── 1b9c74733feb4106123b37141d7e1b5d6f01e7d6.nq.gz
    ├── 1d259d3d0a1ab72d3cbb488c2179c087735c7e61.nq.gz
    ├── 1d44911dd078fd3aeff163a8f98ac84655f8ab5d.nq.gz
    ├── 1d483f73044168f4d00ff18ea0dee012b200c7d6.nq.gz
    ├── 1d543922639f3d24522fcc939f0582611681a367.nq.gz
    ├── 1dac2bf5bf16be1a3a8fa2b8524d705ccd18f1ec.nq.gz
    ├── 1e499934dd832e07d167e44d1ab5d6033e890439.nq.gz
    ├── 1e4cf17db424d0b60e51731c4f53be504663b8d7.nq.gz
    ├── 1e4e63b59aeef9a687ba0c66fed3a02f72572667.nq.gz
    ├── 226e51c85511bd171802d8ce203e8bd50218110b.nq.gz
    ├── 24839208d9fd441124bd80403355bb130004eae9.nq.gz
    ├── 2589cc3fbccd077c3a2ca3cf7c2e5185b8c5f72b.nq.gz
    ├── 26876cf4b3c52773af78892665f1b25ad8f99ebf.nq.gz
    ├── 2690d7735b82f9fdeabb791c60672ce1c910f7be.nq.gz
    ├── 26d103d06ed3d6e4cebfbd53911b06bd60327242.nq.gz
    ├── 26fcc0cab6fb731588f3fcb70f0645be17e5eca8.nq.gz
    ├── 2882ca6d18167e95dc8f204846ee798db6b131f1.nq.gz
    ├── 28ddcd7d2f6a10b39076b30052a6f6a8fa061033.nq.gz
    ├── 29ff31181f799f5e900111bd626c41c4f71d5908.nq.gz
    ├── 2a669c5ee09c8df1abb400c61a5b7c5ca9ffe60f.nq.gz
    ├── 2a7b8f9e40d2adf4596b9a85a4dcfb499b6158cd.nq.gz
    ├── 2d8480077c2302e9c2f376fc56afccb4330f94d8.nq.gz
    ├── 2e94efaf59f65f69ff3cd58030e0c6b2a4aa002f.nq.gz
    ├── 301a9e4230cfa8236fa375b687824ca971c2764b.nq.gz
    ├── 30bf168f1d608b880b484fff89a5d8c5e10aa707.nq.gz
    ├── 363e3516b1499158e04fab6c25c747f9c01f3a99.nq.gz
    ├── 36897c3937b19f9918e017f1762866d2459306c7.nq.gz
    ├── 370a8361721e750ff123fbd69a14ad0b10c3e28e.nq.gz
    ├── 37b0481680af4ed4b4307d425f0eda26ef576c4e.nq.gz
    ├── 37f7793cffc8d65cc02ce1750f600e676ced481f.nq.gz
    ├── 384ddac5bfa8e6a00e8c8b0dc68f713e19aac504.nq.gz
    ├── 3a495f07f62bcd9aa645e7bf879559571e99a7c1.nq.gz
    ├── 3ab767bc34d064ce7b120391063d85d8fc4a5868.nq.gz
    ├── 3b005d8c5620ee43169af6c7d80052ee2d966793.nq.gz
    ├── 3baea03a05ebfba4dcad2bff142ef91ae299dc03.nq.gz
    ├── 3c3b67a87c160fa240f8852f8daae8d0b0eb949e.nq.gz
    ├── 3d2c6392158586b4b0511d2125207d0d660dbc4a.nq.gz
    ├── 3ef5a25bac10eec3925c29eacbfa68a84517c726.nq.gz
    ├── 3ffb78a64103fd69de4ebafa74218b67dcb167e4.nq.gz
    ├── 410355dc0e6039eb86610e2f508939d53aeccbda.nq.gz
    ├── 4298888e7817d307314c472b0709379ee3bce5f7.nq.gz
    ├── 43fd5a73f89477832a4cd03b3e191672782ec83d.nq.gz
    ├── 4471febc1f0db763f6eca90d8cb324ac053b24c8.nq.gz
    ├── 45e8aa8088c83fe476238501f94f8f86e4a4bdb9.nq.gz
    ├── 4712965414fc0daecf131a8590d6310111925888.nq.gz
    ├── 4727335ba3e24c94c59a2a9a133efb099c714ecc.nq.gz
    ├── 485fce8617c9df053f0bed2dd56873df0371b0d0.nq.gz
    ├── 49f2cc770a17a0263ed54c0a5b58ed460111167b.nq.gz
    ├── 4a66637978d1eb0739662d7246b0651c43c283dd.nq.gz
    ├── 4a791d2a74a62ebe667ed1e5b742b74d2cdd18c8.nq.gz
    ├── 4b2d32bf583748f7c718edcb83bc76601dcd6f37.nq.gz
    ├── 4d3d062740d48eef502e5c3e814e107001d083c1.nq.gz
    ├── 4d744da47e879ed111473cc1fa2fe912e8027e07.nq.gz
    ├── 4f17481d21f1bd50e2670eabbede1ef7268630c9.nq.gz
    ├── 4facad5ad3ef7cf346d083f4064779d7d7fa2593.nq.gz
    ├── 50e93fef7770320504c6900c63607c1f575eb30e.nq.gz
    ├── 52008ddb04a2c6f3c19a7eb69dbc7a21c8174063.nq.gz
    ├── 522795aefa5fc06e39d257ccc15ae69c6cdf4074.nq.gz
    ├── 53721ac07d0891d33be232f628c94f6251a78472.nq.gz
    ├── 53d646750496bc4b8b2bc55f0449c70f2c170b90.nq.gz
    ├── 5557fd2da6eb175d3fc17ce869964736fca4cc88.nq.gz
    ├── 55b0fff96e7079087c1ae55b458b2c9552b37fb0.nq.gz
    ├── 55cf3e63bcd93ddbf820d6a4c651aa29f4451592.nq.gz
    ├── 5624dc66c4ebb4986e2b0e82f87e3c0136197467.nq.gz
    ├── 56495efd25af3dc14d92a00dc4fac8a43d36e0c3.nq.gz
    ├── 566b38687da2954c2e176fd2538ed7f7dfb32f73.nq.gz
    ├── 56765e5aa493b7052c234c7dfcc56268c847e595.nq.gz
    ├── 56fec6c4b89ec982fda7fb45d5c1770f276773b1.nq.gz
    ├── 57be86a3025cd8809a9122209c86d3f3554579cc.nq.gz
    ├── 581f525003bb63ac46dcd56b91161721a25d09cc.nq.gz
    ├── 59f62b0b917c2de58a324920fdb93d2bcf38edec.nq.gz
    ├── 5aa8b849099fc883dbb6567aca445a00ad104e98.nq.gz
    ├── 5ab13f79320a094b866073f7162538841abb3ef4.nq.gz
    ├── 5ac8094e4f2cfa5c4ccfc148c04beb6c208d8771.nq.gz
    ├── 5bbb835db9b537b681a1a5b877fd822d95313f29.nq.gz
    ├── 5c577a2d4dc79bc215b858274b1206bc03f7c35a.nq.gz
    ├── 5cd7c157ba0c0aa2b5844fafb9ab0a65f4037a94.nq.gz
    ├── 5d33e67857c03afae79754a2c8630d3d835581f0.nq.gz
    ├── 5dfb6d0a53bdc24e42baaa80ea8a1e03468a3ad1.nq.gz
    ├── 5f066270fc972a0862356300534c4be9355e0bd2.nq.gz
    ├── 60151c1526fcba24d5d1fc75b0e3adbda3318fa9.nq.gz
    ├── 61cbda5e6c76293556a00d723ff5cacddc4de72b.nq.gz
    ├── 63f3590ba158001fa538287bef63f2079dd55e41.nq.gz
    ├── 64e60f9ac36f517b8363170cc9d443b48e49cb16.nq.gz
    ├── 65e0490f258a06c29a4da9c93112650d30f24775.nq.gz
    ├── 65e52962bbb288c4a2f19fbe14b7ffb9baba6487.nq.gz
    ├── 66a81ffe4af83691906182c4d442d17a4dd174f6.nq.gz
    ├── 6717e55d94270a61c2e532a924dce37945c8d17d.nq.gz
    ├── 6c3bdcf6b2303e8725bd3a9d90d9f97f182cd4b1.nq.gz
    ├── 6ddb9000fb456d14740c969f7065ef17bdd1e87d.nq.gz
    ├── 6e3b472826ab92c84877547393b2b33a041187ea.nq.gz
    ├── 703d466e56148d9c7ed0fa663ed39f0e559e5679.nq.gz
    ├── 712ae0dd718c90bf7e7eb3c8831473a1eabdd27a.nq.gz
    ├── 7294aae5b8f4a4980d9ac08ada6fafb5ac7341c8.nq.gz
    ├── 7495159d5d1f2e91388b18df07e7d772c63c1ffc.nq.gz
    ├── 7554f8b20ae58485df49010107f79349db1c5943.nq.gz
    ├── 7606a0edaa5f1c7c517826f800296877b19105da.nq.gz
    ├── 7719dab102f05f8f4103af99d6084499ae7d9090.nq.gz
    ├── 79d1888eb2570a12bdf9695d3f0456b25deac8a7.nq.gz
    ├── 7a524506699a1b0674441f2420eba936190d78b8.nq.gz
    ├── 7a75640199e98e194ddced4bdf95a43813bee18c.nq.gz
    ├── 7c24f56e288abaef9cdc2a73613aa33ec7ebca2b.nq.gz
    ├── 7cd2df828c749c82d7baeb4b128a8ba7eaff9953.nq.gz
    ├── 7f6236fbf324341219f280cbf61cd4992ab5de14.nq.gz
    ├── 7ffebce39c2b20072eea16d68f8fef3c3cd35dfc.nq.gz
    ├── 80f55bf89b2033bb6e4c9410d6b7c75b4bda7721.nq.gz
    ├── 822eb346cf5ef4a1b312a4c2431fa11de38c27ee.nq.gz
    ├── 824099b3b6909499e7b787272d6d89552a2773fa.nq.gz
    ├── 82c7b14d577cccf53e1719ea34c11d47351c5a63.nq.gz
    ├── 849e070dbc77b4ce04ac2ec7f3971356f394c96d.nq.gz
    ├── 862d0aaabf5d5201fee689f671d13e4bfd3a331a.nq.gz
    ├── 864030534f5e1e4a10f8e549965124219d6c001f.nq.gz
    ├── 86c56dfd36d8193231108e1d4342b05f68bc676a.nq.gz
    ├── 87a98ca046b64023607b05ecc17f1a131098a387.nq.gz
    ├── 89bfefbf49a8ace77b96102c44a35cf7bdece669.nq.gz
    ├── 89ed4ee8e413d178fb7cd932f9c86a5c4de847f4.nq.gz
    ├── 8a4607449bdd308bf9d53af9be4c4468f7d495fc.nq.gz
    ├── 8a5cccc7e42c148ea87f5db60270b2cbbd8226b8.nq.gz
    ├── 8a6c306e4599ea4fa1e28a5068a011413764cecf.nq.gz
    ├── 8ac8a6a422d255825f56bd9a50cc0b506d7ba065.nq.gz
    ├── 8c775ee697019eb33f8b2805251379155e89114c.nq.gz
    ├── 8d288c851f412ef294468a32654658c25527abf3.nq.gz
    ├── 8da627abe133306f787a3d0c4d7182ab3170804b.nq.gz
    ├── 8ddf7b0ad14b80bc73317cf34beae74991f906bb.nq.gz
    ├── 8ffb3ec738850849a144c073867ca8a28a6b7655.nq.gz
    ├── 90bf015e124ad08b8f3a5fa818f0ab115d8e72f6.nq.gz
    ├── 9104880f98ee782ab251ebc731bc3eacd7b22fa3.nq.gz
    ├── 9107e1f8125b72a99799459117f11d6f35f5c907.nq.gz
    ├── 91be36db9d9c1e1b39448ce46ec68e5e382b336f.nq.gz
    ├── 9285ded5821a9ad601bec64a017b4e72566bbf19.nq.gz
    ├── 9470c462f1f6cd609cd1f4901d370ddd986a2dc4.nq.gz
    ├── 9501d02849d97fb29da02a9fd7f1c2b5888c2738.nq.gz
    ├── 95190443ace33085bcd86189804062f573846fed.nq.gz
    ├── 9583a1ed7f53acb53620652f4a9516be4ac5f3ce.nq.gz
    ├── 9610c4b13583aa7fac8083396c1a7996890ba8c5.nq.gz
    ├── 97a5794b4d3fabeafc5d3692a34ddf2d66a2c4b2.nq.gz
    ├── 98d8cd69eb275604e845e52ab32bcad0ae14abfa.nq.gz
    ├── 9932b507f6905b58b6df85710b4643592d0cec32.nq.gz
    ├── 99b24a36e0ffc976ec0554355b892afb5577f9c8.nq.gz
    ├── 99e6752621acc2df66e6460b5fe301cb66d10c00.nq.gz
    ├── 9a21a3a83cbdf8f89d7daccf737924490274c5a7.nq.gz
    ├── 9b9454dc9a29b830d4703ce53575834526d9aad5.nq.gz
    ├── 9e2c2faa8732ec6e40b493b03b53d71f907dae4c.nq.gz
    ├── 9e6da1063287d75edc54a69e4f6d03b5cd631667.nq.gz
    ├── a1ef08450f5db622eab360ca90071cb73fbd9b51.nq.gz
    ├── a1f43e53e4b82169f1862789e6aabb0759d28ae8.nq.gz
    ├── a24ec8c035bfc9758574587e3522f2fff94cc5da.nq.gz
    ├── a67569e4ec156377982fdbf119952cfc8d2a6faf.nq.gz
    ├── a6e4a3f70f7292b243def7a3fd784599e9cd75a4.nq.gz
    ├── a7750ed8919ffc42c2e74ead33a3003e0f5bb130.nq.gz
    ├── a789212de08e072bbe88c4a8c32c8e7f986e6806.nq.gz
    ├── a7ec73792c2810fdcfb2bcb96eeb06fcd9c4a910.nq.gz
    ├── a8a14cbd59dc710410f8dec3c647509e96d81a38.nq.gz
    ├── a918b9caa6f9b4b4522d3e486fd23deed56a1a9c.nq.gz
    ├── aa0dc3bb4689b31e41bab9bddcc24a9e1587a2ca.nq.gz
    ├── aa343f0b28acdfcae457a0ecf89f7d681c52b3f1.nq.gz
    ├── aabf9ddcb495b532be7cf4182a8e582fb17ed765.nq.gz
    ├── ac71a66cf790ec2b4cc699891aed7671a6233dd7.nq.gz
    ├── ad432916318c7ee47881c728883faf79a20c2d9f.nq.gz
    ├── ad86ee260cfdda59c7b10baa0f9f54d45882eef8.nq.gz
    ├── af1737942babb2f2d62d4f497e42270f18bb9019.nq.gz
    ├── af75adaf6d06059844e582448ae18eae192aa705.nq.gz
    ├── b0012fec02e6e151581a60463a8aac52062a2432.nq.gz
    ├── b0e53aaf7ef092c1bd64847211ab62b27bb18869.nq.gz
    ├── b283d5781de54a4df740f51ff11277e0787cb714.nq.gz
    ├── b2ef64710fb618f1115aaee5650edd3aaa82ec45.nq.gz
    ├── b3077295b7415f651e81ca82103f6120e8e3944c.nq.gz
    ├── b3477c0ef50827ad84686503b6595503485eda3e.nq.gz
    ├── b34ce3b1097d98019d155f89edad6f9dae52409c.nq.gz
    ├── b3bfa97cdfd4723a61c56281af4818dbeedafa22.nq.gz
    ├── b48132f03fab46af2f5af0a535c94d940decf310.nq.gz
    └── b7132bb687d0f8cfc7ab3183b1304024431fb5f8.nq.gz

8 directories, 200 files
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

## Source repository

[anthropics/anthropic-sdk-typescript](https://github.com/anthropics/anthropic-sdk-typescript)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
