# Repolex Knowledge Graph of goccy/go-yaml

RDF knowledge graph data for [goccy/go-yaml](https://github.com/goccy/go-yaml), parsed by [repolex](https://repolex.ai).

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
lexq download goccy/go-yaml
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 92bc79cb5f685e999ad131473168fc45215d12d9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 92bc79cb5f685e999ad131473168fc45215d12d9.nq.gz
│   └── repolex
│       └── 92bc79cb5f685e999ad131473168fc45215d12d9
│           └── chunk-001.nq.gz
└── blob
    ├── 001f836462b5a64a1e6d71ad05ff227bbf7b1db3.nq.gz
    ├── 006f12add9aa7e93565aa72396ea6da36935249d.nq.gz
    ├── 012910dfe86725dd3c64fceeef3fa9d7f58b9439.nq.gz
    ├── 01883b9e7de44ce58abd825efe993b0735fd82b3.nq.gz
    ├── 018e242e47e97445c66fe17f3b3c97b17a1f406e.nq.gz
    ├── 0242202dc7579480d34c5536ac406b2320605025.nq.gz
    ├── 026d7b499e35cd959ad20888c309413c31ed2caa.nq.gz
    ├── 030ae9ccdfd516c983ff9ebe5abd08e609663b10.nq.gz
    ├── 03179cd616fad9b9185528f738b19c3797fb3627.nq.gz
    ├── 03936e6c181bbea6c05d586c0bd0da1e7e173ad0.nq.gz
    ├── 0444f189766f505a6472fc1231f2cb2080ae39b5.nq.gz
    ├── 04485ce65bba4b19f6eb9d0e9c0007312fc298c5.nq.gz
    ├── 0499250b931fa780f44372648d593cb899b30092.nq.gz
    ├── 049aa9e9f9e7ca05222e41b3bea6c124ed284b74.nq.gz
    ├── 04a1240688142170469237b34724e202805b43bc.nq.gz
    ├── 04c83021cebe8db688049faf4b63db8862f997ac.nq.gz
    ├── 04e631bbb0b2b64a41ce81e425a751ae659cd3eb.nq.gz
    ├── 04ebf691b566df202dd2315dacf7a014410f86bf.nq.gz
    ├── 052b1d68608df6146e101af07ba28dc6677168ae.nq.gz
    ├── 05675c89500fa249d316029eb554eea953d3fa24.nq.gz
    ├── 05e102d8ebd4dc9febdfcdd8b8ae0a626909a7ad.nq.gz
    ├── 0634b97078aee90d8018568efb3c1a8e97e0aa63.nq.gz
    ├── 0645c55563347466230a1b694f4cfccc92d3cad7.nq.gz
    ├── 064aca0af8976acb55a9a6cf4050a0868879fafe.nq.gz
    ├── 07186437a5ca2d2fa69ec0f4a99ba8184249de4f.nq.gz
    ├── 077ba0b6d3d5a9df8635c1abf7716d8c3c51f53c.nq.gz
    ├── 078fbc89b486a443fa004944533a3f7855dae153.nq.gz
    ├── 079de26a1980e6d6777d232f85abadc23eefb597.nq.gz
    ├── 07c3f72e48bf510661ee02778f74cea5e38c3412.nq.gz
    ├── 07ded623dce117f5543acd2455607f37cee75e34.nq.gz
    ├── 07e14f57627a79f79971e221f895aae4d3fda682.nq.gz
    ├── 0806e5a9242a24c2d79e603201eeda9167939083.nq.gz
    ├── 081e6cf459201b9c27cee8c2531bcdff6be3f076.nq.gz
    ├── 082400bfba0dcbef77ea99c59a10491f5b580d63.nq.gz
    ├── 0896cc6f40d6f54553c4cb9dcca219cb7fccd18f.nq.gz
    ├── 08c530d233d53d2be408c1a354c34dea159fa0cd.nq.gz
    ├── 092408a9f09eae19150818b4f0db5d1b70744828.nq.gz
    ├── 093e6e2c44171c73ad4f5933d1006d74b7a108db.nq.gz
    ├── 095a9e74d33167f74efaf61f880de068ffc5a54e.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 09c3705943c1278ede2e6ead2d106e416f130f08.nq.gz
    ├── 0ad38e8035222db4af5ee87b0d51ae5abeb4a5e9.nq.gz
    ├── 0adc1e532bd81fcdf2488b42dd9cfd4ff5842658.nq.gz
    ├── 0ade841d29088625ed2ddbaef7388e5cbf71e94e.nq.gz
    ├── 0b067d627068d73f073274ea1d65a0b5b1f132b5.nq.gz
    ├── 0b2fa410c9f9b1af0132dd702bc037c74d9145f7.nq.gz
    ├── 0b9cd808fc2f67d14e4ee5669e7c9de4ac7a63f4.nq.gz
    ├── 0bd18c38930d27af1de5c2020c7391ffb2600ecc.nq.gz
    ├── 0c5097af61ef4a7a2d8d116bde30e2f48e49686a.nq.gz
    ├── 0cca491af70f366dc1941479c623efb5dabd6f2a.nq.gz
    ├── 0d5be77a0863a17157a4c27f0452b325d8f30697.nq.gz
    ├── 0d9917ee895c61bdc19af487dd152dc8f7d109e9.nq.gz
    ├── 0dc83aab6651f6863c572597b7fb7e6e9f0c78b4.nq.gz
    ├── 0e29306f0b28b8ca872ba4a4f234488a6a3e1608.nq.gz
    ├── 0e62301483773b1fa11c79eb877b2d36533c5528.nq.gz
    ├── 0e75a65218bc3689e3119b86feb68e32e2d5ff02.nq.gz
    ├── 0ede90fb485d0e5c2aac06944d8476c9c888c0af.nq.gz
    ├── 0efc44a9ce3a3974e6d5f81bd0a779307ae430aa.nq.gz
    ├── 0f185f0ae66d08ef1781d4e0c9c702789894c9b1.nq.gz
    ├── 0fcc9db1e51b73a05bb1e4580bcb81b9f5e149b9.nq.gz
    ├── 1056edd745acb4747b393682137516a9f9cf057e.nq.gz
    ├── 10d58e24eecb1bfb2970a93d1ec55e08e7bb0517.nq.gz
    ├── 114171def9311e75a1354d5e5e7b77ddbb675281.nq.gz
    ├── 1180757d81cb6c1149dc3ac2838518d0ca86b39f.nq.gz
    ├── 120448d333af3ffd6c4a7f73ab0e109c5a67a84f.nq.gz
    ├── 12b8f27f7e06c60d056cb0531aee5230e8684c95.nq.gz
    ├── 13199d0ba1e514b4ee3b65a244960f5c223a5777.nq.gz
    ├── 133f05ee5405e08f532135b4c279642895b42a13.nq.gz
    ├── 134cd490b3aabbd542e1fcc2a41f3970f3fccbb6.nq.gz
    ├── 13694b0783aecfdf1fbcc9688eda8e6f9b8a0cdf.nq.gz
    ├── 13fb656010274a38022eb6ecc2eb80d854cbe0e3.nq.gz
    ├── 142134e07761ed25c81b8edf8163b257527d384a.nq.gz
    ├── 148a69390a028af63d8d11f057a9c7da34e3010f.nq.gz
    ├── 14d275374771a364a7552bcad7777460917a2b39.nq.gz
    ├── 14f338ee9ba1ad6b47baf7e3fe8f3d2b08217a48.nq.gz
    ├── 15481f414da70230bbaf120fa5d3699b5843b910.nq.gz
    ├── 156b6d0845f8bde4c8f29b698c422388318989ff.nq.gz
    ├── 1584b3ecd1b22220f65a2362789a2ac8ce6bc7b7.nq.gz
    ├── 15925a447a95690bcac92a2b6c7cb6413baf32a9.nq.gz
    ├── 15c6a3636141fd44d6e9e93567c1b054cd3fde7b.nq.gz
    ├── 15d41f0292aab1e693885d9968d68dd2da1a9c6b.nq.gz
    ├── 1609d4542aff30fe72ed8f67aa64b2aa9dee6263.nq.gz
    ├── 168723f7fb89fd2869d23548affd2343b5eb3c28.nq.gz
    ├── 16ae65bb82e2dcad162fb7407fe298bc5404dee0.nq.gz
    ├── 16bb6a7c48d27e8e26a44c50f331097ef1decb84.nq.gz
    ├── 16dd26eb8c00dc37e79e2bcbdf4e949d96e74525.nq.gz
    ├── 178c43c37f250d38725a49791a3946d96a69ea8f.nq.gz
    ├── 179dcbdc625d28a70ff62863f76d932d453be57d.nq.gz
    ├── 1866413f3fb633182bfb87201f2226c0f0779475.nq.gz
    ├── 18849594619b26883b6156fa4c99843831ee677d.nq.gz
    ├── 1948383a027a0bc74ae3aa5a3f6dab587b461e94.nq.gz
    ├── 196e58797c87a5b1cb6e8a72cdbde6bdc62a7f32.nq.gz
    ├── 19747c72611e143fa192a29fb4a6e1dd6b4594d7.nq.gz
    ├── 19765bd501b636fce433540d9e6735f51d66151d.nq.gz
    ├── 19d1e3ee3eb3d482e1d7eb0d8b66dd217ce19eb3.nq.gz
    ├── 19d72ae9d53c57783b40a57f45df4b80f264f132.nq.gz
    ├── 19dc4f5800a365627c0278e0399228764c07f237.nq.gz
    ├── 1a876c9d7e74be8bdcb7ba586abaf9d292513446.nq.gz
    ├── 1aad4754a3498bf00e68aefffd7e1e5e9c47602d.nq.gz
    ├── 1add8f86dd91ac58f56d431a03846e692ada42e1.nq.gz
    ├── 1ae7ecaca1eed4b48cd66e309092e7f447e30aea.nq.gz
    ├── 1b7a5507650b42bf8ed230885211ff421149adad.nq.gz
    ├── 1bafc6be89ff33b50767e62fd8dbbd5fd2a98afc.nq.gz
    ├── 1bce55c8bcb0cbba7ac6ea0b703d3df4cf8d1a82.nq.gz
    ├── 1c3df8c887a729342b701beb15fefdedc6ec0601.nq.gz
    ├── 1c50067cb83c0664bb6ae7dd85c253d841c0907a.nq.gz
    ├── 1c5090d0d27855bd1186680ce2ebe3fcec5ef0c9.nq.gz
    ├── 1d2cefe94671ad7ee16a72db97c0474e0e51f735.nq.gz
    ├── 1d2d27c1161b7739d3741a008b9cf1e2521e8ea4.nq.gz
    ├── 1d71c2ac44f07a47124988290b7289b846345260.nq.gz
    ├── 1dbadca3ec037daa75fddb68adaadf3d76fc7674.nq.gz
    ├── 1df6f007af48a75e5e778bab843fa6d441d142df.nq.gz
    ├── 1e3d7bfcd981592bffeeaef5c93dfd441b26eb91.nq.gz
    ├── 1ea594f1bc899c15f8026ccfd4e71f14e59ba419.nq.gz
    ├── 1f3c3bbb61b9fe42da6e0f2532327cff2ab42d24.nq.gz
    ├── 1f5b290603679b1d9a9d45a52c1806949b69d355.nq.gz
    ├── 1ff9bfa3c20752e79a2c3d5d4934b681d3417a9b.nq.gz
    ├── 1ffef600d959ec9e396d5a260bd3f5b927b2cef8.nq.gz
    ├── 20a2d6d918d686948ac44cfe9af9beb3dec8f0cd.nq.gz
    ├── 20e9ff3feaa8ede30f707e5f1b4356e3c02bb7ec.nq.gz
    ├── 20ec09f001117cdfdf10cb30d53675a156b13061.nq.gz
    ├── 21ace64fc953a084dff5881ef29a5bffbcba807a.nq.gz
    ├── 21d0ff948b6567641b038b89e565e327d0963dc0.nq.gz
    ├── 22911fca5f920503876848f90521f5899901b6ba.nq.gz
    ├── 22c8650b1691d1123daf27c39d3962d7d808568c.nq.gz
    ├── 22ded55aa2c14af167996451c06c190f270e78a9.nq.gz
    ├── 231f150c579c375de5eac79fcfe8e2fc8b71527c.nq.gz
    ├── 23314724cf5f08e9d6516f096c7c33369eb97e05.nq.gz
    ├── 235f24980a087c647c5ea11b4809173b72c61ce4.nq.gz
    ├── 236d725fad80de58a4255c2fdddadb52f7b02ec9.nq.gz
    ├── 23cbbb139634f491e20b1111e69b608fe8c078bb.nq.gz
    ├── 240a6486c41e68ab9723e4f7e55fd12e94f3b226.nq.gz
    ├── 243c466a7b64c1ff10bf1123448ad440b3092f4a.nq.gz
    ├── 247a8cd5da3809a9fa04b96f13782fee1ae58228.nq.gz
    ├── 248299a1cb79ac8adb23df9ea5b53197ad04af22.nq.gz
    ├── 24d931773b38e9bcb960a930bc029eae70134d17.nq.gz
    ├── 254e6fc40349322c7b48d84a035293280eca3866.nq.gz
    ├── 25692f497a2f48a56f6be972803579875198fe34.nq.gz
    ├── 25a2fe474c7e07dc5369aa30e11b16e8c24f64a5.nq.gz
    ├── 25f0447c410d18308dad594b4caf4eee828d1816.nq.gz
    ├── 2670feee17b1310d71f33c138fd9ee3e34108769.nq.gz
    ├── 26a80a667d566757d36bdd21be722fd1b29e03b8.nq.gz
    ├── 2716276264d8869a3083cd3c67319368a6fce358.nq.gz
    ├── 274fd323c1b4d3524bed8c5d176ba1880422a6a9.nq.gz
    ├── 28703eaabfdf18d4b178d4adabec68369cc0d995.nq.gz
    ├── 28eb29e802950bdfa786fdc721b5f999e3034496.nq.gz
    ├── 29133b171897cfe916bae0d591b3789e208c27a9.nq.gz
    ├── 2959aa239cdd0042a83f8c60425a1de25a320610.nq.gz
    ├── 29a609d2d1aa13ac0f0d3874f1ca530c2b58f59c.nq.gz
    ├── 2a1ec44a49f06c1b1b0ed78742fd25cfc1b2a89a.nq.gz
    ├── 2ae8800fbe112d757e9f65d62bb9c742ba2e6f1a.nq.gz
    ├── 2af57e7ed4d0c6e1ba9dbb85d035c78357cd431b.nq.gz
    ├── 2afa74f1830f8bef0c54450a29c089271d739f75.nq.gz
    ├── 2b07b28b3147f0fa6bb3972ab87287e60c1dc79e.nq.gz
    ├── 2c0664b34dfbc738c80118e6bb31c66b06809b73.nq.gz
    ├── 2c185ac4f913b7e19c28d4e858e9b8f8ab7e59ae.nq.gz
    ├── 2c7dd1d4c3ee9c499b6640b03ac014708f08d149.nq.gz
    ├── 2c970a22eaae0f630009e218d9411bb032775608.nq.gz
    ├── 2dc1d4e2b811235705c2e840c06af7a3b197465c.nq.gz
    ├── 2dfab84d92bd86cfe80b1f69c3a44eba2362bac0.nq.gz
    ├── 2e190c65af1c552c2bc79d8ff560af7bb9b601d4.nq.gz
    ├── 2e5a6476feb81931021c0325707d472b8b1ea2a5.nq.gz
    ├── 2ef9084ac2cf59ab93f6c9c3fe57479d44922f41.nq.gz
    ├── 2f62d082375ff43b449de887667c90586905b1c8.nq.gz
    ├── 2f701b1d61fc269e597ef83233a6472123b68196.nq.gz
    ├── 30799d963cb23e42521741c04b2d1bc64733484c.nq.gz
    ├── 30c07c241da7d09e5e574c529bee8c44981d5c6f.nq.gz
    ├── 30c49a332a924d73c6ffc1d225b94cf7eba23f08.nq.gz
    ├── 310f3c2a327734a625773cb3825ff32487bd799e.nq.gz
    ├── 3121a64accc8be24968aca11128112af81de7a20.nq.gz
    ├── 312847e512d00b86dfdb47006089b167a768ab79.nq.gz
    ├── 31ce8884c319b9e4c5e39f4d6f8160fced3803aa.nq.gz
    ├── 31f9966a0b9c83f64e47770e490b4c9d2cbc6d83.nq.gz
    ├── 3207f4f22734b4ea39b49e12c5e3345bb3d74aa1.nq.gz
    ├── 3220349bbc3083f7a32acae6fdbe3057a8b4986e.nq.gz
    ├── 3270084a7ec81c7a6fb0e55436cf0597525d053d.nq.gz
    ├── 32a69436288ea63df2a8b63a87e6bb8e78c218cb.nq.gz
    ├── 32b9bb53634a1ab35cb0ca9d52707b19c38b770d.nq.gz
    ├── 32d2114201a3be4693cc0b60678a53a034fccaba.nq.gz
    ├── 32fa08f0a438a05a7a5e4f07306b6613f98f8874.nq.gz
    ├── 33424c030966f7f3ebaca5b517f961b0d8445efb.nq.gz
    ├── 33a65778a71bda9e7cdd3356986f03a2c02bc671.nq.gz
    ├── 34ccc8741e0c4e7f0ea208b2646aa0549d0e8f2f.nq.gz
    ├── 34d30b1b86001464d5cbc8a6e65218f24350715b.nq.gz
    ├── 34ed34fee98a570d3b87d8ae5428a0a105d34d1b.nq.gz
    ├── 35361a5ae2d8951b0f041fc45ab0b6b5991336b6.nq.gz
    ├── 3574e0214df889b9c43e277c3370406799ac9886.nq.gz
    ├── 358ca9ba93f089b0133f05933f133a446402eb17.nq.gz
    ├── 3598690cce42fbb9b9833a92f9be4c71ae70b384.nq.gz
    ├── 35ac9236555ce7cf234fe2b881a2bdfe945c3d37.nq.gz
    ├── 35d556dd1520dc61ad13e322c7db362ccad28d2a.nq.gz
    ├── 3734c116b3552f1156d5512dacdc024611e21df5.nq.gz
    ├── 376284146674c196f95236dfb5fd5b4ddbd6f379.nq.gz
    ├── 3763137c241471121cca9b53c99b457fe9c37966.nq.gz
    ├── 37b52a6e3135846939f93aa0429b1dd196e488b8.nq.gz
    ├── 38515a7f445c3116de47e0800a7237a31c591455.nq.gz
    └── 3867010ce7fe0232cf7da6355e292dab9609cc87.nq.gz

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

[goccy/go-yaml](https://github.com/goccy/go-yaml)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
