# Repolex Knowledge Graph of vespa-engine/pyvespa

RDF knowledge graph data for [vespa-engine/pyvespa](https://github.com/vespa-engine/pyvespa), parsed by [repolex](https://repolex.ai).

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
rlex download vespa-engine/pyvespa
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 236e87cbe1bc831ca809d4d418ddd4c7a85d5dd5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 236e87cbe1bc831ca809d4d418ddd4c7a85d5dd5
│           └── chunk-001.nq.gz
└── blob
    ├── 014779630660ace82b1e428916ea5ba41539bac9.nq.gz
    ├── 015b3e3f7cbffb5eb0c06d58d2d55bd5947e5a4c.nq.gz
    ├── 03d4ee80683629fdfb4782ea4f0072aa97aa56ce.nq.gz
    ├── 03e395a691b05a83cf797197ce9999cc3a1808bc.nq.gz
    ├── 041ee7b076e8ec62e53a67d4c0e213f5efb6df10.nq.gz
    ├── 052fcd5bcb0bafe306bd563ea0803c5cd98bde11.nq.gz
    ├── 057484dcb8fe661b1d3f59d4c371dd5fcb55839b.nq.gz
    ├── 0601741bb1600b1d2aea8f01cc62e1412cdf5f3b.nq.gz
    ├── 075656eded4d4eccff8e1c85c396662278d4ddb8.nq.gz
    ├── 07a70af76b84a356240d67e7a0e4ab6aeb966ec8.nq.gz
    ├── 07d356c5c4754e08c912206e3ef7de0e8abdb969.nq.gz
    ├── 07e51ccc8de6db8b5d14c665aa37d859e3295e72.nq.gz
    ├── 08274ec00b2db235c1727f473abe7279756a602c.nq.gz
    ├── 0a357c7f88bb17fd435c7b34cfea21d87f54f972.nq.gz
    ├── 0ad6805baf8b9206af70cf865635094a74a89818.nq.gz
    ├── 0ae5d802e32b5ed11d53939d6f0b7acc68832598.nq.gz
    ├── 0b1af7765d740c98ae230d894caa604e1a7004d8.nq.gz
    ├── 0b5b688c90d17bcf7decd086828d9133e732aedc.nq.gz
    ├── 0c5cfac40f4ec9505cfe8ba32cb200705c895ddd.nq.gz
    ├── 0d1ad501c2a3d7150b414fd302f4e874dd8b6793.nq.gz
    ├── 0d5813cb927d8cd7ac7d83b3562ad0dce3d1e3c7.nq.gz
    ├── 0d61a1f16fb63438c697a18cc528401321d88674.nq.gz
    ├── 0f0ac079b376c2ca0af639cfc3df06ccce5520ef.nq.gz
    ├── 0f7b7b0298b1df251b264602fba4b08a379326df.nq.gz
    ├── 102b035cf8086eb6067c05f21c20d965ae5652ef.nq.gz
    ├── 12a668714976142130dd16bc5297c53a9dc21fe4.nq.gz
    ├── 136719793a00e545dde2a16ace6951b236035e22.nq.gz
    ├── 13b8407192c813f83622097d17cd736090e9ccb6.nq.gz
    ├── 14242647b20dd9f08f7809cd547ec190bb24135d.nq.gz
    ├── 145f83566496e299dd219f77f47df24140565f3e.nq.gz
    ├── 1463aefc324bff9798cdf88fd9964e5f99a4ac99.nq.gz
    ├── 14cc130bdbabc3afde33e6c0bac2e2e4bbd8ca2b.nq.gz
    ├── 172a5d86896ef1bac347d736c02397a3c008c89b.nq.gz
    ├── 1789c707d625c5923ab5c23c09eaa60dbea11db2.nq.gz
    ├── 19aee1b05bbf827f45e5c6cd1b7b41716d751872.nq.gz
    ├── 1a631d896316368cb6a58f8a1e3248fe5042984c.nq.gz
    ├── 1b61e3c94f24d2cc79108fab22f5fceb96f9dd51.nq.gz
    ├── 1b7a71046939d37281f9a5a6b6ba2164fe65cb4a.nq.gz
    ├── 1bcb899c9d9ba7e3d192c02ad6dd9ae08ea24c49.nq.gz
    ├── 1c5518607fe4833d2a52f1ccf84ff0f4209c12f8.nq.gz
    ├── 1cce48516e3385aabc234f2c1d26455918481957.nq.gz
    ├── 1d8a982ebf8039a97974e8ea534066e816398497.nq.gz
    ├── 207943cceba642b1a87ae84efe18cafd29088d4e.nq.gz
    ├── 216fb970daa78901680a486d7aa1191b62b853f1.nq.gz
    ├── 2213f0e20fcdd6424767b75d64fa5537f35d43e8.nq.gz
    ├── 22d9dbc940128dbdf257428b1373cdede2c173cb.nq.gz
    ├── 2375ec8c764ae2bc4771ed24d8133bc59e380a89.nq.gz
    ├── 23bcb21a5fa71a0b7236e5700712d3b3945a68fb.nq.gz
    ├── 25567d6337f9b5a93ea4f1a9a8fa846929a3f568.nq.gz
    ├── 256e89fbea7821a0e4dde3f58c14c9f774e11111.nq.gz
    ├── 259d14fbcfb4b3df1e10b861f6aa9bf97d93a744.nq.gz
    ├── 25cede731db35428d207a9a1073684038a9846b4.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 27b9b8b12999d57f2f05b9d9b6118d1a8455c5b7.nq.gz
    ├── 284066e5ad4392625d8f8499e12cccfce17c303d.nq.gz
    ├── 29235c68969686c807c03e3f8bab236a3d7d2ec6.nq.gz
    ├── 2984d722520aa23f0764c85fa50bc1b06b5332ce.nq.gz
    ├── 29bd8d0126bac1004e3ea4028bdddb3049e493de.nq.gz
    ├── 29dd276a4b8706bdcd66e9db67517c7929166a7d.nq.gz
    ├── 2a15b2b6a70f2fda6a6b8dbb775438b56e6acec0.nq.gz
    ├── 2a93fb71a2d1bfba67a7b59461686446b95e435f.nq.gz
    ├── 2f510877c7c5ab18286d438fbe7f595dbf31f16d.nq.gz
    ├── 2f6231e8382f79dc4a4741873deddb3dd424fab7.nq.gz
    ├── 2f94d5f126b52f57e03e8f82e31a1d1fb2324449.nq.gz
    ├── 2fa0d8dc01289786da17da73f9ef83622521ecb2.nq.gz
    ├── 30318bd2d0411366be72c883dca7b9a3c2135f73.nq.gz
    ├── 303c1eb6acef49737d5704914c4214d3f5c89164.nq.gz
    ├── 310a9e97ca1ff088e733af9e96b91a7a65fe2b83.nq.gz
    ├── 330e5e4d896c016aedb13d781273abd053a5d241.nq.gz
    ├── 3604cd7412a8a9fa02c8349eba1c7f4a45de75ea.nq.gz
    ├── 3615ebfa9f1413e64f7757676b50dc4f0ad6ad12.nq.gz
    ├── 37c0cc771fecb14a8b9bab71f96559ec5b7f5279.nq.gz
    ├── 388b9ea20be491de3582b245239f3a32e96c02e2.nq.gz
    ├── 390c09dc316d6ef5f38e63d7d562a7682b5b85e0.nq.gz
    ├── 3939a4dd43a927915647fd2847497c3a51b53bbb.nq.gz
    ├── 3a6728b08fc8c485e8fc081943d81005fb2a46b2.nq.gz
    ├── 3ad6aa640cd4212e7fffdd5d7fae09cd0679d0c9.nq.gz
    ├── 3ae86cf497128bd801525932dd042da11bb41d26.nq.gz
    ├── 3afb15a0e864fe18a83fdad909d34ef303d5fd72.nq.gz
    ├── 3b78acf67c3990bc0e4175abe9a87326cfa9af8f.nq.gz
    ├── 3c853ec04457090c0dafd56719e4eb3563f0b5bb.nq.gz
    ├── 3f0ac272deb7256319e292ee257e1afc0089e266.nq.gz
    ├── 3f41de319d4645ef5f6a3b6a95431155b09b872e.nq.gz
    ├── 3fbe6a469dae17c5daadfd13c58d8b3e7e9efdb0.nq.gz
    ├── 40dd1e2fa7210994822463ae273b3f71ca0fdc84.nq.gz
    ├── 4165d5de69d324f31ddc24f25a259266cf83aa6c.nq.gz
    ├── 4265cbee7ecb0223a4db62c25dd2b988890d744a.nq.gz
    ├── 431623bef06cc1c722c581541cf2c27d8fb2ce46.nq.gz
    ├── 43a45ec6b59f80cb892788f585bc8602150fad96.nq.gz
    ├── 43ed560ae659583b87f14a0642d3644576e85ff4.nq.gz
    ├── 43fcfcee9fbc72b59c3b0fd78707c60f04bc8c03.nq.gz
    ├── 4785a8b5892f230f64d8c72e5cec6d4d2da5b6f1.nq.gz
    ├── 47b8fa7c2a88a9682e405b343cbbaab299d14208.nq.gz
    ├── 4809e8315477697da04421da9f336a825734c486.nq.gz
    ├── 4a38b9fd28d3ef8a734e172be471f851f308963c.nq.gz
    ├── 4b4a12a7902b831086740a30b6a2db37abde62ae.nq.gz
    ├── 4b97648e346d15220257739f321ac81b9a5573a2.nq.gz
    ├── 4c66c9c67dd39bd2a178db133244796f65dccd28.nq.gz
    ├── 4d06afa47d14fd6cab5586a9e5af035911f48c02.nq.gz
    ├── 4e38cb0f75592656aceba90554091455fa7c15bf.nq.gz
    ├── 4fa426f78eaacac82826b9a1d718f7f963cb17a5.nq.gz
    ├── 4fe46136b896d44e6c7298ce32db36565d200554.nq.gz
    ├── 4ff3a3dd73d2bf0a2e8f23b6efc4c29f7e268001.nq.gz
    ├── 521b7c65fe30fe8335a4784449559d6319b15952.nq.gz
    ├── 53a8de5f828f212502183941a653b09c7c149482.nq.gz
    ├── 53d91d11486a22353312be397ee0c1237cc09dca.nq.gz
    ├── 55174787a7af389a731fdb53adaeef3740d0c00e.nq.gz
    ├── 555ec309c2b02c7a27acad110a22a134bece916f.nq.gz
    ├── 55dbe5d24d8a858bf3164119b7082732f3c6fd26.nq.gz
    ├── 56a3f919376c071f6e7b5df24a08340d55a21172.nq.gz
    ├── 56dc3e0668f3c6f4827a9887583400d576bc9cc0.nq.gz
    ├── 57d1c00a996f7a880fd128e329567a4797c7e54b.nq.gz
    ├── 5876180c93cb6a064869d1383e2721aec317acea.nq.gz
    ├── 58e2d6aa68eab499e9ac9f8fda838f7d4654962b.nq.gz
    ├── 5972d35559f39d76390b53cd96bdddf135924537.nq.gz
    ├── 5a462bdf023817c49bd61e5a1b93848b1565c1e7.nq.gz
    ├── 5b28703a1a7861855cb3ba923e8e10d933860740.nq.gz
    ├── 5c347d37695b2a0fd70e0951b9d76674c6cf9bc1.nq.gz
    ├── 5c36fd485bf06bcc8795c98480d5dcfa82c200c8.nq.gz
    ├── 5c675c2c427e0a433e15101c50eded42193a61f4.nq.gz
    ├── 5cd5d8d9d34b11d09c3151b4c1de3c4769733cd0.nq.gz
    ├── 5cda47ae5ee79d64fa79a22a92f066c3ecf675cd.nq.gz
    ├── 5cf6290b7052fefcacfb6b6adc64494b8c2b9763.nq.gz
    ├── 5f09655052ad43d52e1805d46fb5c5f92b41ef2c.nq.gz
    ├── 5f3ce4258dae8ecbdefc707bfcf68d8235e494ee.nq.gz
    ├── 5ffcef030e7660da9b9f3613d36c671fb90d380c.nq.gz
    ├── 60819201474e82eba7d695804b50002ce6f1766d.nq.gz
    ├── 6092a256b664cc6e7007a30d730a0a3eced177ae.nq.gz
    ├── 61787ad9236f51569bcff75a575326df26f38c9c.nq.gz
    ├── 625ccc990ae29f74f99c5ff5c8c69a67fdcc59d2.nq.gz
    ├── 62c62ec8db6f44f95a5aef1f386d3c33f0d729d5.nq.gz
    ├── 64dc66c3efe3a3b5eb4241dacc4461cbfa585513.nq.gz
    ├── 6505ba647076303d0c3d4c91d4309d7c7bac1b7b.nq.gz
    ├── 65998d584607533ed83dee5931b6810b64d37a01.nq.gz
    ├── 6602aea182c76d8d5ec7bd639a78a393617b2734.nq.gz
    ├── 662c5abeb570e344c02bc5f9fa8489e7cc806b3b.nq.gz
    ├── 6645f54b9b32ccfc811a10455e91d710ca4679c7.nq.gz
    ├── 6667d3287e3b48ffc2c3a8dc8cc675ab64c54aff.nq.gz
    ├── 66982d9ae0cc44b3796b71ab4c0599cf9df09955.nq.gz
    ├── 67436834249795bfd5a4b029e191704f4fa909cf.nq.gz
    ├── 67526dcf60d2693ba748d2b7ac381f4d9d4e2a35.nq.gz
    ├── 68c52196a75bef4423f9467133047e0ed9dbdacb.nq.gz
    ├── 698d0155b9548287ca0e7bf89ed8994f98e2bf1d.nq.gz
    ├── 6ac831381daef13489e50175b51b911738e37a86.nq.gz
    ├── 6b03c67cc598d11a22c11375b1f896897bb1a01b.nq.gz
    ├── 6bc07cb205bdec4e4b74773bd74e5112d623fcb1.nq.gz
    ├── 6c78d4dd20a0c4d6ecb54d33620f1102a762c0fe.nq.gz
    ├── 6d411094fda777842c6061b1df112d68d9761e9d.nq.gz
    ├── 6d85dea447e4b85a5b0570a17d3c8b87595e8522.nq.gz
    ├── 6da1fa591f60adc4fa42f26ea74ff4e337cee808.nq.gz
    ├── 6daa2d9f38cae5f4f172dc1c25e7803b577c3c5c.nq.gz
    ├── 6df96c9a9c9c25b2669f475f28eac23be9c19fbd.nq.gz
    ├── 6eb73902d124bceeff0d884120f344370d83d148.nq.gz
    ├── 6f254bc0be831a72bd179f7e877f0b3d0aef82d1.nq.gz
    ├── 6f3c141bb7bc142cd040fece36b5950734c4cc37.nq.gz
    ├── 70b1fdaedf84350afaa7839325c0637f91dc9a4f.nq.gz
    ├── 71ee6f7aeaa8bbbfc2ea36b67e823be6a6b382f6.nq.gz
    ├── 72764060e0609b61b76c6cb9f3bbb15bf4fa71e2.nq.gz
    ├── 72904c603eb8535006bf2a87db2501565a367256.nq.gz
    ├── 7382fc9ad4a492b1a89e22cf44aa0b881faa655b.nq.gz
    ├── 74328e9357c7beadddc3ee3a8a4c8be34e00b8ff.nq.gz
    ├── 7591ebe587018aadcc41d49dab548a1808f15a44.nq.gz
    ├── 7611e8b80c76dc0968f68c9f71673812a56bc9fe.nq.gz
    ├── 772f14bb227d72196ffe503e619c7699ee5d79d5.nq.gz
    ├── 777c4ba6663c5e69b7eaec1cec0b564a0908d04a.nq.gz
    ├── 77eafc742c6d6c18a1a4602ccc2e66b78de2cb9b.nq.gz
    ├── 7ba3e2dd205a6e486b73788d663035a7f856f533.nq.gz
    ├── 7be05d42c76cab46205b4d3760d6b9882f57b3b2.nq.gz
    ├── 7d2ba7f3e1d8f6d8a8c55e9e4afa93a9ffeefd91.nq.gz
    ├── 7d9962502e7889f937387d1499082895120cfe3b.nq.gz
    ├── 7dd769fe6168e1f4a436ad9cfa3488bade6af902.nq.gz
    ├── 8054360e7fb643ff9f741f8f0c29bff186ab5570.nq.gz
    ├── 8069c3e5d87764c7046ac250d18d761ddee22f05.nq.gz
    ├── 80ee60a9ad1f1d1879b7859cb2ad2054ef76b6b8.nq.gz
    ├── 8181e069af7d2dd85f6c12f5c95d259b996339d7.nq.gz
    ├── 824cd6e29df5183da38788b04280dfa000311e74.nq.gz
    ├── 82a2047f7881ef6f94c61a8af0392242407bff83.nq.gz
    ├── 84d73089d591c97dd3f111d9e8c55c469097e195.nq.gz
    ├── 85fa76ec29e5d55890fbbb7cf42673851e2debfa.nq.gz
    ├── 87f30504a8bafe52a75f9f496586fcc878876082.nq.gz
    ├── 88ceb3187d258b98c50ad73b1f1b77767589028a.nq.gz
    ├── 8953180a01252ae53f0648214a70d83b68405a2d.nq.gz
    ├── 8ae290ccb62891018956c367d62c7a89b239159d.nq.gz
    ├── 8b5a5cb91c5d6139269c0337e61aae9de4963ea2.nq.gz
    ├── 8b5f7c5175beef727e383feb51068ab4af6bfd5e.nq.gz
    ├── 8c95dda8e83882a29ac69f3205ce0ca7430f97f7.nq.gz
    ├── 8d2251e96e0301ca96d4217bb212a606d447257e.nq.gz
    ├── 8d836c4d9c904e84912e74d19d09b3e3eae79573.nq.gz
    ├── 8f1e767874ece85407f537d9ceebf1f4b40b8a90.nq.gz
    ├── 8fec86e4859fefec91a9bda839bb5e1d393285c5.nq.gz
    ├── 9079b44d833cf25124ef19ff65b1bd9c4fa8f112.nq.gz
    ├── 909db3d26e9588f7d77cabb143e910112904381d.nq.gz
    ├── 92fc1889e3e6f1552913d4b0f70f2391b442f533.nq.gz
    ├── 9317f60d6aacaed2ec1a925b172355da38b73b72.nq.gz
    ├── 93c1da3badd39f507c656fbe5237351438e42340.nq.gz
    ├── 95c1d7824530875e3c130ea40936ef5d431fb406.nq.gz
    ├── 983c9dc2ded9b655260ea27563b553dbf3c006d6.nq.gz
    └── 9ac135f9d77a8b1d5887cfd080d54f4557b0e1b6.nq.gz

7 directories, 200 files
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

[vespa-engine/pyvespa](https://github.com/vespa-engine/pyvespa)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
