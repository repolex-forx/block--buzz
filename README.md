# Repolex Knowledge Graph of block/buzz

RDF knowledge graph data for [block/buzz](https://github.com/block/buzz), parsed by [repolex](https://repolex.ai).

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
rlex download block/buzz
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 53a12100b34577286c89102f1875ca2b6eea61e5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 53a12100b34577286c89102f1875ca2b6eea61e5
│           └── chunk-001.nq.gz
└── blob
    ├── 00d386310a12a654164e417c352ef83f7ade61c0.nq.gz
    ├── 0158a26039334fbb765bb3bd328f75027b9dc67a.nq.gz
    ├── 01705261d2e1a7f66c16772ce5ed86bec41bc6c5.nq.gz
    ├── 025a82467e5809cb268c371c239f14fd683d49da.nq.gz
    ├── 0263319fbacea78e0bd7d520ca93cce02b693db4.nq.gz
    ├── 031b0b7277d802cceedaa950564fc549311f93c8.nq.gz
    ├── 03a38e32f63bff8ec8f3e83ed919345cbc920b12.nq.gz
    ├── 0403481648d73954828be0495ca85c68faf2a101.nq.gz
    ├── 044c76896194a1f989e506f34aa2ea0acaa94303.nq.gz
    ├── 04decaa82734e3324c74e40606bda343d8221ef0.nq.gz
    ├── 05584d77126885ee57293b21a1ab689416e1d3ec.nq.gz
    ├── 05ab0eec2ce23ffce4442660b699b7a46bddb0b5.nq.gz
    ├── 066fa46373065dc5b6758d03c44693d135c0159a.nq.gz
    ├── 07837ab36f65693d5aa5c64aa965e140cba706b1.nq.gz
    ├── 07b018b9b1f98e7377861c3f72df7f728586f9c7.nq.gz
    ├── 08be4f020f962cac20b424ea5f5186d852237222.nq.gz
    ├── 096737d5359905589b22a40b1d7c2203037a6d20.nq.gz
    ├── 0a14e1a0abdae7e58af6d7424de1377f490758f8.nq.gz
    ├── 0a7f91eb85442b761f1d5e1f0689c592f6367457.nq.gz
    ├── 0a9e52bcadf7a094c19e8f8bcafb3ccc87465a3e.nq.gz
    ├── 0b5ffc3b7374631fc785e7c3bace3385cfc3ba4a.nq.gz
    ├── 0b94aad550a0889c7e3bdcb4545538e6cef71c55.nq.gz
    ├── 0bc815181b0eef59a0d302f42bb04207284f47b9.nq.gz
    ├── 0c73442fb7dc37884d449d3df0c9a52529eef12a.nq.gz
    ├── 0c9f170916595016074d3bdb39b3488c3c5dfe6b.nq.gz
    ├── 0d846d8626dd6b4ca871d8520c06f3638012e01f.nq.gz
    ├── 0d859dd9da08efedeabaaf4558b819b77e0b2f63.nq.gz
    ├── 0e17ba544eefcaddcdd7e75421a293ff8572b9e9.nq.gz
    ├── 0e8cb373c165826f1c9a16179038cb00d591819a.nq.gz
    ├── 0f3014affce84dde98ba1bed04d444eeac8c221c.nq.gz
    ├── 0fc4ef08044e193319f774a83dac370eaf1d06a5.nq.gz
    ├── 101514f58bcd1eded1fb9e419c7b0477068b2450.nq.gz
    ├── 1039c087833cb22c80efeb0196912d3ead285765.nq.gz
    ├── 1082ff20322092b87ec4671130e969b347abb594.nq.gz
    ├── 10fbb733ca975c2eb6086cb6331465395eef83b6.nq.gz
    ├── 114dcde9fdc851be0e2cdcaaeb278d005b94c61b.nq.gz
    ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
    ├── 12e778e4a925e415ac62e95525a5f4860b321c7a.nq.gz
    ├── 13210ca8e93b48846ab11ca00e56688a0a07707b.nq.gz
    ├── 13a93a8d1932e7cbd9628c3019cca3162f253660.nq.gz
    ├── 1502a51d3ec78b74de287dc49b194500c6d55060.nq.gz
    ├── 15893a1cb4eede3d163fb09708cc1875c42c4b1e.nq.gz
    ├── 15a1a6b3f23658580af59d9f3dfaa83eab7f94cb.nq.gz
    ├── 17059c900dfef60118214df05c506c43bdb42d65.nq.gz
    ├── 198e0fe91c3c99f64a547e95fe29e3d82fc2fc2a.nq.gz
    ├── 1993188f31956b5496bf6055aaf5b7abcadbdbbf.nq.gz
    ├── 19cd599c08e82e4c129e03fa0ab650de6388f000.nq.gz
    ├── 19d6ed3ecd9d6333b1ad74e2a4f3f9143a027317.nq.gz
    ├── 1a35666478afb897fa489d52043f45f9a0abe486.nq.gz
    ├── 1a62184505f276cdb83560d20ac31d7bd1471ae5.nq.gz
    ├── 1a6f7403b29b905c7dcea0c87c72cfd4ad8714f1.nq.gz
    ├── 1ada9f664fce4b71e6f0ffe679cc2335ab99d5eb.nq.gz
    ├── 1bedbb3c664c0f1fd0b2a70d2245185dffeb1333.nq.gz
    ├── 1c3b50c44b3816e7d70445619696e16c33491f77.nq.gz
    ├── 1da2e597dd8924711bb04b9b9b42fc20863d4bb2.nq.gz
    ├── 1dc0a667fc4dc163ed075d5ae6c4a9c77d9c770e.nq.gz
    ├── 1de2addce99cf2a340013a83ca82e4a0a4511a54.nq.gz
    ├── 1ed813b8256a600c5033e175b8d81dc7be4f6da2.nq.gz
    ├── 1eea8e217895feac1ef3301b7221b87aa9f57a1e.nq.gz
    ├── 1fe5bf751b8114677d5488c5d46e160f9206fe14.nq.gz
    ├── 208ac3a711731773c31294b683ec6e0790904068.nq.gz
    ├── 208ff6f67e0344cac5c24ddf56977db33f28489a.nq.gz
    ├── 21327c30d9298633d2a8d49617b8d96f4cf26bee.nq.gz
    ├── 217f6fb5cf0c438883d4fdfb5d0a896155d42502.nq.gz
    ├── 2182a828b110b65afd20229ace51b0f82789469b.nq.gz
    ├── 21a3cc14c74e969ab1548274a8512ebfecc40f78.nq.gz
    ├── 2225d1d442bd0b9cd279edfe19d0b483b0563153.nq.gz
    ├── 2313de50f97434b6b79314c49e2864c0862809bc.nq.gz
    ├── 2344cd1c93d7c37714a33c59a7af00980c908a28.nq.gz
    ├── 237ffbbfe9b0f02580e50f0c33d414f1be1424ef.nq.gz
    ├── 2435353dec3865be8e670d28161e5e479b5b8b78.nq.gz
    ├── 249988e3d28b4371601af49aa632708005afe089.nq.gz
    ├── 24e5156295a0687acc297e225e0dcdebfce400b6.nq.gz
    ├── 25733239baa5ad4a0867594eeea6e4fd0c6fd1a3.nq.gz
    ├── 26b8b8c3da1192a4913a6b8a555abbf39f21de63.nq.gz
    ├── 26f2160f5d31fc9051c852d6ac0996eba94e40b9.nq.gz
    ├── 2702fbef6796b3e57f2fd97a7b100d4900476f1e.nq.gz
    ├── 2819823b9e27e1ece67256580664d2bf878f0eaf.nq.gz
    ├── 2862aad1f370194f011b0669104f6b2d87e95d72.nq.gz
    ├── 28c22ec9d958dedb392795e7cb07e4f0c701657e.nq.gz
    ├── 291a052f14c48e244845d85cecb1eba1b4ce2f6c.nq.gz
    ├── 2927db60e5b02e3463e979ec46df5d146fe9ce71.nq.gz
    ├── 292b81b1eb7e451c5938765a29622a61af0fc98c.nq.gz
    ├── 294ba523627e6e411308f84010d86e28fe7241b2.nq.gz
    ├── 299c0144ab46d23a5e3c448b58acd32556d10ea4.nq.gz
    ├── 29bb0980e467a217d1a2c3ef76e4fa8f3c585235.nq.gz
    ├── 2a1d914ce55558e84f001cda7e6f1a4e10fa9781.nq.gz
    ├── 2b5391f9277b6cfea2b00db584f3f4dc24b4c9c6.nq.gz
    ├── 2c9c0f203658f960750a86384baae5955f7c3047.nq.gz
    ├── 2dafc4e9fbe1ab7a1bdbb71f9a632a99c7f185b5.nq.gz
    ├── 2ddf34d8402f24b61df4f8e9c560e4b00785418c.nq.gz
    ├── 2f39fc4680e112a70a223083a383f3d5d7a84d97.nq.gz
    ├── 2f89decab42c11564b87b8487aa8a3154cc3ec1e.nq.gz
    ├── 309bd3cdc72cb495b87e6797f09fa1c9a0340ac4.nq.gz
    ├── 30e5bec51feed9139bae08b10a56e94302da24fe.nq.gz
    ├── 31559b7d115e3c105b328cce9b9dcd9774025061.nq.gz
    ├── 3214f7b6070cadaac2efdda0b0600c1a54381768.nq.gz
    ├── 32753807486955636fe00d3afe923db98e0ea6ba.nq.gz
    ├── 329d9763c7e4d7119b2533e27ee5af0cebee76ab.nq.gz
    ├── 3458dad035ec588f5e1109ba89543b615f3a2a68.nq.gz
    ├── 348d55e2999a17b8aedb0a76e2b7405a2fc1b81d.nq.gz
    ├── 349aa3237aa33fd30c7fc8936eacf640547d1255.nq.gz
    ├── 35b5e4b20939a286e798a4e1c4d8b2186382b257.nq.gz
    ├── 361e747fe28b62e3ae80772cccf8e35eb4c46e69.nq.gz
    ├── 36d5d7c89cba3d49a908d80ec2a5ef8001c4c898.nq.gz
    ├── 37381a78f0000def2fc6fd9e9434c731d3cfe654.nq.gz
    ├── 376de0a990bc4a5e23040c1a3a75019f238c780f.nq.gz
    ├── 37c167a184079d1397837b05a3539672719cec3d.nq.gz
    ├── 380005ad4beed1526079006352165dcc07c528ba.nq.gz
    ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
    ├── 38664df092df99ec73fbac7eb4791cfa48d8a055.nq.gz
    ├── 38bd4521e0e94392edf166421f06966786926d3c.nq.gz
    ├── 391903bbbdaa4afcf6da1bcc5d82d6d7cf472cd5.nq.gz
    ├── 3a177e8a9fe3d333822915de403232bf7de79791.nq.gz
    ├── 3a396ada0f2b58c2ae4d4fbc925632631ede5a9f.nq.gz
    ├── 3ae6cfe55a4226daaa9ba3f68b34ecb823b54037.nq.gz
    ├── 3bcfda2b1d77c67f69cb5bf67c79c681651cbf6c.nq.gz
    ├── 3c1e81733e1ee169e31b9cfa4e278492a588e800.nq.gz
    ├── 3c65fcde955413fdcc8c6fbb8e4e81e29d51b1e7.nq.gz
    ├── 3c70e4afe19e08755c8f444f79146ecbe78d5b4d.nq.gz
    ├── 3c9890473b3ae62e7da456d475d3994f6471d8e7.nq.gz
    ├── 3d797b3bb72e1b508b6ac3503d19b21066ab1f00.nq.gz
    ├── 3db6536fa3489d70a8179c80d38afe359465a7ca.nq.gz
    ├── 3e2f2c5764bf48bf4a3f0e5f7fbdce5ce32a67be.nq.gz
    ├── 3e94aa43e1f79a469c29f987bc65fe922a55cb51.nq.gz
    ├── 3ebb86356e4844ca88e4bb6e4e26736920c4fe7f.nq.gz
    ├── 3ef21938e2a10df8ca9fd4a0dd6161d2e5b7f3d9.nq.gz
    ├── 3f12f883ba7a84f11583df6f5f52bd1739ee1fba.nq.gz
    ├── 409989fda94a45e398a8086ea0cc33cc0471f968.nq.gz
    ├── 409b7f7f57eb365298bd5d70f023b31662804dfc.nq.gz
    ├── 414c0a0bbd40d12fa2d8b68c10ba65d1c7f09be2.nq.gz
    ├── 4276301ea2390fe719f4a25258f6f8466ee0871a.nq.gz
    ├── 42e7f5b944f493f7b1c42b0483ba7c8c8dfba53d.nq.gz
    ├── 439dfbd6c56a4f94d6ec586800cf9f0918726f7a.nq.gz
    ├── 43ad666dba417989afc842eb7eec644367887759.nq.gz
    ├── 43b4288abbb775ff5159c8b8ba03f58964e5247b.nq.gz
    ├── 43d3506ec8cd5a3be7ba988d97b14efee6426857.nq.gz
    ├── 442d7b874d0f293ebe5b6f73813793b26fee4a6b.nq.gz
    ├── 445a41d08670860f95489e30fcb9fa130cadd04d.nq.gz
    ├── 449c984848bc343b0431f1885b7b3f6577f80782.nq.gz
    ├── 4517467c0cfe4a27701d315f0189dd5f19db1e7f.nq.gz
    ├── 452a8df6567cbd1f0ed05eea3f15ff9ae7ba534b.nq.gz
    ├── 453e11459e67436db081a1e028f37ec5407b80d8.nq.gz
    ├── 465a0a6b6128d403daa410bfb8e12c7376613e11.nq.gz
    ├── 46718d14a1a297cc631f2d5b74c3f15816bfe4b2.nq.gz
    ├── 46b2a5a577ed954277f9eedd58e6fe7c29bdd7b9.nq.gz
    ├── 47836cd30cd44710125e74943b96e3ed458d2535.nq.gz
    ├── 479b049488e280d4d4089e291f076ac493031057.nq.gz
    ├── 47ab2570df7f3dc16b9843905b6f2a38afedbc99.nq.gz
    ├── 47beb1c7a8300397a6ba6ea5a5b8ece9d66c7020.nq.gz
    ├── 47c00f2e3c7e1f0e24fab6cf11bc2f21449f73c8.nq.gz
    ├── 47f651db4dbded57ce5e6dea9e494071aa6be3ad.nq.gz
    ├── 49569bf432a4d58ba5e20f38b7103591a2319ef2.nq.gz
    ├── 49b8b40c7acaa6906264f1a253978483849caf37.nq.gz
    ├── 4b5e03eff8ebc2c6cdf5f66f5ff8ac97f04d855c.nq.gz
    ├── 4bba68837c7ed551edbae6c5ca78c64212cb9a42.nq.gz
    ├── 4bfce65adffac0199b7bbba0003bc08fb061dd30.nq.gz
    ├── 4c17eb0f0560e008692545b11d3b9a7657da3472.nq.gz
    ├── 4c86dbe5072af7bbc6acc4b79ab27b3d00c155c5.nq.gz
    ├── 4c87cb99d4f63cbf262ab8c5a09494ca479e356d.nq.gz
    ├── 4cf9ada66ec48918e5ffcb6ee9ed1e1df2d8d163.nq.gz
    ├── 4dce0fdc360145e5e3256afb7bc856bf7afaee9b.nq.gz
    ├── 4e4210bd71c799e68b8df4c4e3039a75512477e0.nq.gz
    ├── 4eab9dd4274cede7124fddaabbe4554cb8cd053d.nq.gz
    ├── 4eae61f49d6e5a316a0ae5d7b31495e9450b05da.nq.gz
    ├── 4eed60907a5555e4df9dec8b1f33ff110cfb9078.nq.gz
    ├── 4ef574d6504815f01d82db6b617c798a741615e3.nq.gz
    ├── 4f4573fe98e785e0d0de64ed77c39a92e8a08915.nq.gz
    ├── 4f705d0f405cd4a48913965754d1c3ef60c437c4.nq.gz
    ├── 4ffdc88fc444064b522547a99418e166c6d51400.nq.gz
    ├── 50371bc369f45490cd8d254e4477a05c8ce77e5e.nq.gz
    ├── 508a5d91e93844412439d2b44d897acd51162263.nq.gz
    ├── 5102f07d9f4bf1ab7ce38887673412f58a632933.nq.gz
    ├── 518ae33cec5d489ac75937d840b2f09b174fa650.nq.gz
    ├── 51bf7c70a25d7c6c240b9f5081b6ebcc03d8b1e9.nq.gz
    ├── 51d0fc46a184067b06ff77f8d3af7f3129c42986.nq.gz
    ├── 522212aedd5a286f81b65d1f08e52f46bc8a008a.nq.gz
    ├── 526acbca5e3cbdfa2af54de079611371b5aa104d.nq.gz
    ├── 535d4c9ecb1919eaf8edeaa76b852706ebb25e05.nq.gz
    ├── 53ef0a58014eac6b8f887ac04c646ee4a374eab1.nq.gz
    ├── 550cadd86aa977ad05a7ea445d95d848180fed0d.nq.gz
    ├── 56439f00bc1565ce7aca273a886eecdc12df5c1d.nq.gz
    ├── 56a972f89420cebfcb74cfd73598d9ff90c9a7f1.nq.gz
    ├── 5702281700c3a28ce2d6675405bb32ab422f7748.nq.gz
    ├── 5728b9187a62fcfbd25da68ad661cf2165097ae6.nq.gz
    ├── 57ebc61a9b695ca73b9ab4a79a5caaa9acff9a3d.nq.gz
    ├── 585de0b898d90e8c862bdb6f908fc48ac93e47cd.nq.gz
    ├── 588ca49653a38a64a222ca562b74e9e359494207.nq.gz
    ├── 594d7ac34ff0c30907fd8d77f5fa0c45f194ab76.nq.gz
    ├── 59f28b903d698cf5030a347cc8469c718afac4cc.nq.gz
    ├── 5a378fe656e938b7c2b2f316f619a64e57fe1d66.nq.gz
    ├── 5a9e970dc64258392ed47a7e2dab0e0792ca1728.nq.gz
    ├── 5ab473f17b62dc90714786cce487dea0c327345d.nq.gz
    ├── 5afc5344baf6f9247787e9799b698b1eb26f351c.nq.gz
    ├── 5b0e357a3958e4a246dab2f8bf6d8a6b96a2142e.nq.gz
    ├── 5bd46c8c882802654ce8985dd8bc772fbab0bed3.nq.gz
    ├── 5bee5e5bdcb6fcb37a2e63dc0857a7f18ef78ebe.nq.gz
    └── 5c3b9fbec93e57064c7eab835adc01a5b72b4f1b.nq.gz

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

[block/buzz](https://github.com/block/buzz)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
