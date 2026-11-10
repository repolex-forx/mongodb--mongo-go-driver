# Repolex Knowledge Graph of mongodb/mongo-go-driver

RDF knowledge graph data for [mongodb/mongo-go-driver](https://github.com/mongodb/mongo-go-driver), parsed by [repolex](https://repolex.ai).

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
rlex download mongodb/mongo-go-driver
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 31be4fe7124c584a720b036c98e2a4540d2e866e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 31be4fe7124c584a720b036c98e2a4540d2e866e
│           └── chunk-001.nq.gz
└── blob
    ├── 000f86efc35f1823aa4f8bb4aa5ffaceef49aa6c.nq.gz
    ├── 0029fa396f454267be678dccdfb82e2634b06cfc.nq.gz
    ├── 0033379dfb505a5bc10eceb421ddd953f24ac5d2.nq.gz
    ├── 005b61da106292c8025e82ddfecdb425dd156f05.nq.gz
    ├── 00f142247d61388a1fb64ea37b844d4623b74f0f.nq.gz
    ├── 00fac897ec706f4b30ef7fa8fbbfdf706c078774.nq.gz
    ├── 028c32dabf0b17a9537652797b8b0cb34d68bff0.nq.gz
    ├── 045cc5f558d68903c53f9d51f77cf389fba87aa0.nq.gz
    ├── 04f6b17875ef70c94693b95381d2ba7a08c1dfc1.nq.gz
    ├── 054c4f3e2ebbd48e725df8cc55c63240caa5653e.nq.gz
    ├── 055fe77db3be93a25f21d8ea58beaf177f3ed5f6.nq.gz
    ├── 05b3f5b6893202223a891743a4538cb7d1446d3f.nq.gz
    ├── 0666372bb7837e49b8e7a5c05f9af7ce8640f04f.nq.gz
    ├── 06ae91a3f3b724c5204a56bb287a572c5de33a57.nq.gz
    ├── 0735b87a354832355c84d6d8bf0766ebee2baaeb.nq.gz
    ├── 07f15ca7ff732e684d1384898fb71351126b33d5.nq.gz
    ├── 07f85b35d7610556f6693f0b5ecf6524d6f9b95b.nq.gz
    ├── 08e0202ce2a11eed93697c5c3b196e79174cbffc.nq.gz
    ├── 08eff7e9908b79c7d91252389a0c61e42fef59e1.nq.gz
    ├── 0999357afca94a03f78d7f4b3098da2990577c2d.nq.gz
    ├── 09fd4fd7805c9f86238517d32f11f0ced813eb22.nq.gz
    ├── 0abf06b538d1dc4df28542c54d4b7fd2089ff516.nq.gz
    ├── 0d980c406c151c052ef1256509a2a861899e2432.nq.gz
    ├── 0d99b11e35fd282eb41854260f6af1d59fac4d3f.nq.gz
    ├── 0db077d96481df3fb7b266e4aa2078f7e81d17f8.nq.gz
    ├── 0dfa4afbfc7dfb6ea3d9eb8ef277232ee4abec94.nq.gz
    ├── 0e8bae6a2d166ddb7797460ab1bfa0fea0c6088c.nq.gz
    ├── 0eb7ce421799882ad5a4a73929b5d7169bea7d53.nq.gz
    ├── 0fac086899e247fdba6ad9906f383e0b50c2e266.nq.gz
    ├── 0fb21b51cf23b67318303ef8520a6dbb8b333d76.nq.gz
    ├── 0fffac2e3dd975f2ceed94c97cb62d05962dc005.nq.gz
    ├── 10619b5cd10c34357c64805ced25635f9bbabbbe.nq.gz
    ├── 10799671ccc91a7b9c1fb8a035ee5dc8c4bf9876.nq.gz
    ├── 10c3f204eb82d1a1e8440f8b8fc66543ba8f08a7.nq.gz
    ├── 11a74312b78ccabac913ada78be40894423c3d65.nq.gz
    ├── 11c6adb95394d19b48ed850f587e70ce9c66a6f7.nq.gz
    ├── 124a70490430c160bd4c23f9959465853029014a.nq.gz
    ├── 134ee96f3a08ecfa4ffdf1cee597583005af8a24.nq.gz
    ├── 13839d7f8d93e00d975fbb35fc265d6257435875.nq.gz
    ├── 143df5e7f45bc9a0721495186fc379f8b62050e6.nq.gz
    ├── 14bc764d18c818b789ea6c93a9f2c88984a2fce9.nq.gz
    ├── 1572a92bfbdfe99c28195104740d1f4b1e560f66.nq.gz
    ├── 1581bf72f516efbc92d8abcdc1cbd7aed645fbff.nq.gz
    ├── 16e89d326371da24748b39cda85c23db57b296a6.nq.gz
    ├── 170cb383fb96fb704829aac386c9b332dc33a7de.nq.gz
    ├── 17a22a2297531358d0fae590a5eb18ad85030e2d.nq.gz
    ├── 17bdc0a733ccca0fafc5f6fd87beffb4a323b4f2.nq.gz
    ├── 1803741d020f63dc3cb13f61b3cae4cd2674496d.nq.gz
    ├── 180632ff040527481c8aa400d3a7eb91278699f8.nq.gz
    ├── 184dd69fb89ffd4c6c1b74c7895b0ab52de3cbde.nq.gz
    ├── 187c23aae857d2ea898bbdc8173e80a27a23ef77.nq.gz
    ├── 1881b1cab1ee9d0e4cddfafdecde79117a6743c6.nq.gz
    ├── 18a70f0cadfc31e1c48b152c8436d7f37c166f7a.nq.gz
    ├── 1963dd43a0381bc560580040acb465373d6ae6da.nq.gz
    ├── 19c29428dad81562c1a77d73e90cc0f1795e3c84.nq.gz
    ├── 1a3d537d102c18ad5eb6a23dcfdab81b03df5b1f.nq.gz
    ├── 1ad460d9e2118c219d131e8b14c08eee0c6c07ce.nq.gz
    ├── 1b392fdd9c624c4f2cd5c78589ee434c9c2b94c4.nq.gz
    ├── 1b6f42ae253dd7fb0e344634ce72d4e84588cd39.nq.gz
    ├── 1befd5a262a4fecd50734b8fc9adb29b580cf674.nq.gz
    ├── 1c3ab57efa6a27b869c537cd5c986b44a316a62e.nq.gz
    ├── 1c49faee688dced4e636a8a070d901b54cdf8931.nq.gz
    ├── 1d2e9be7b758a0d660f9339b045b5aa08403cb9e.nq.gz
    ├── 1d646f594249b45c5370d82875007124a7f2d430.nq.gz
    ├── 1d9b56a783f18f5786c90da98c9fb0e6bc40c1db.nq.gz
    ├── 1dee2172b4074781ec96da26be71a9bfdb936d85.nq.gz
    ├── 1e7b1901ea37695751cca5f8463ae36aad93b9a7.nq.gz
    ├── 1e88007ac7c767e6d402251a9f6433619530f4cc.nq.gz
    ├── 1f9ea486dadc4d2431954b80707cdca445b5acab.nq.gz
    ├── 2011846901c0d2f1a0972cebb8cbaaa57c3f5eb2.nq.gz
    ├── 208f230ef0eab0ae71ac4b62ecdb4285dfbd4176.nq.gz
    ├── 20a86fd5d66fed53fb99d7890aecec9816b48040.nq.gz
    ├── 21057da4c56412879b5525cbfe80eb4ba1586ebf.nq.gz
    ├── 210d65ec8e5c6b8399a28d1b54efe5479c11b60d.nq.gz
    ├── 211e15c47478a07f99aa6c04898b3acb33c4b832.nq.gz
    ├── 23c6140706b17282544b7b08073d07f11485b4de.nq.gz
    ├── 23ef4c30a6bf7f5903a32674fba77e31bbaac856.nq.gz
    ├── 247d33ac37bd2cae450f4aed84e1cec0ca042d12.nq.gz
    ├── 269fe6872b329534c79ab4b43ed9ba29a0ef08e2.nq.gz
    ├── 2779a5c60ca7a0dc8f95e34edabc544931ba26bc.nq.gz
    ├── 281bf515b7eb4c93058ec17a082bc992357802ca.nq.gz
    ├── 283ca373f3367c49c63968ada398cb38778f9200.nq.gz
    ├── 29649b6636b02d0030be93497690beac237fe6ae.nq.gz
    ├── 297cafc7013d8da5ae5f9a209899190abc97918a.nq.gz
    ├── 2a68564c1c97e811e7a068e5b97f3249a822f4c3.nq.gz
    ├── 2a9aa00aaa56702a4bccf0822057320f697ac554.nq.gz
    ├── 2c3be54c37de4a8017456e85c08f8270d78a0152.nq.gz
    ├── 2cc4ebc313d3e4b2bede7b03df8c1fc80be044f8.nq.gz
    ├── 2d12ace87a9515b215209bf2ab14ef457a89219a.nq.gz
    ├── 2e1a4c5f2eca77397db42ea90367032bd63cdcf6.nq.gz
    ├── 2e650cf15dd9a8918d420901f8267e01c4693263.nq.gz
    ├── 2f3be1e16c443b801808dded08583c7760586fa7.nq.gz
    ├── 2f454121002a1aff9fb4e009cd1a9cba6d9c5013.nq.gz
    ├── 31737d24e4f16d9b84d2bfea3b6d235c7777f710.nq.gz
    ├── 3180500a4c55da2e0a74869653ae7cb5260af0d9.nq.gz
    ├── 31a10bd5be57aea78fa8d007aebbe7bc0b17a4c6.nq.gz
    ├── 3293a4e7cbaae28855fb56bc2b5179d17d8eaeb4.nq.gz
    ├── 336b5a8a00243843531e4b66af69b7d0a9c98bf7.nq.gz
    ├── 337373909a5f8a6ae777dd10674bcb6873f52491.nq.gz
    ├── 339cdbbcbdcbf8f9cb556ad60efadd5a18726a5f.nq.gz
    ├── 33d37c2bc1168bcd50edb1869fff7bdc56313e52.nq.gz
    ├── 33e368dd48c4f2945ef88e9c233014055ecc993f.nq.gz
    ├── 3440cc761ea022b4f924595c51ed143a784be9b5.nq.gz
    ├── 348d9586afe57992aa52f6a938e82bd0c7286644.nq.gz
    ├── 3592761e8914eefd39f2eb3ee0e5e6f75f973d10.nq.gz
    ├── 364a810d85059c6b80de038f0950b29c70cd837c.nq.gz
    ├── 36d2f6ae26f86f63d0314222ba1dd3923f199035.nq.gz
    ├── 36e6c0b1fcb1c1fc7d851225cd158d5cc9b41960.nq.gz
    ├── 37243d712042faceeead25281449beb46ab0603b.nq.gz
    ├── 37dc90119ea6d264514f0ebee0b7d01fb75c98e9.nq.gz
    ├── 380214783a88e919e51e521d10f2a0a14dcc3b5e.nq.gz
    ├── 387db974405aa0a65de65561f00e42815628effa.nq.gz
    ├── 39725da4db27babaacb473e0cfdce737c2566796.nq.gz
    ├── 398d15b210a4f21fdb99f42bd199065cc473abe1.nq.gz
    ├── 3ad8b7cb2fa28c42b8fb3c8b25a7c92f2b31b7e5.nq.gz
    ├── 3b3783b4b476943f6941ff153c955754f89460e6.nq.gz
    ├── 3dab855f3a2dcb4d7c4481c89236e843364a16e7.nq.gz
    ├── 3dc5e862655689e21c886bfab7656eaa91250f7c.nq.gz
    ├── 3e0eebbec4cdd72fd0afe10a27be4ca5d7b49073.nq.gz
    ├── 3e3b3cec7b07983d5798c3c6089667016a7fb9d8.nq.gz
    ├── 3e97009ec729f46b56ca040b9992e629cab64e94.nq.gz
    ├── 3edceb619618703d9fff41a2b13977c1e7aa0f62.nq.gz
    ├── 3f2080ec293a832f152b7bd74facf7420d78fda6.nq.gz
    ├── 3fc6f4e20d424f78863b24a783f9b87c6dc65a43.nq.gz
    ├── 40074dfc2731796a441f0054e75026c65d427ea9.nq.gz
    ├── 4029de5687c7583142aed74c369e306bf4fcfecf.nq.gz
    ├── 416d9b618b6fe9cf5152ba6c6e45e75522455345.nq.gz
    ├── 4214e5a7c338268f5605d7190deed342edf84945.nq.gz
    ├── 4229ada5d243fd2207d98a014b0a3d6d5ad47566.nq.gz
    ├── 427c24d7386d3fc8a2e0382a23063a101f17a2da.nq.gz
    ├── 430f7510104e20dc14d643a589d4257e0bf9e63e.nq.gz
    ├── 432038af8340f1b79ec6e2d827a4cfd50407171b.nq.gz
    ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
    ├── 43f6d93235ca0fd434abc79377fe6d6ab7b62586.nq.gz
    ├── 441ae34615b93f1c0f44b4968fce7e5c4b925a7b.nq.gz
    ├── 44607a306bc15ae11b582f9db001a868461184e5.nq.gz
    ├── 44790091447acbfb93760d0575faf14c688759a3.nq.gz
    ├── 449fc4d3140171a20735006c7b0ddb3f25716516.nq.gz
    ├── 454c7bcd7b4b7a24786b304c50e97246e3f0b5a1.nq.gz
    ├── 45f4d7ea30b023a20b259cbc0e7a90bd4debb3f2.nq.gz
    ├── 476c10480e6f3e204153fb2c827aaf0fe095929d.nq.gz
    ├── 47955639b437d22e1489a52ed87a2ae696d23dfe.nq.gz
    ├── 49014ead0e227cbc0991491b59a7df408bb2de68.nq.gz
    ├── 490adcef3df7f3789cd98b7f520696a00301c854.nq.gz
    ├── 4a2adfcd2647d0fc1d307c1300348e3310120cbc.nq.gz
    ├── 4a3ddf4ba253e6bd82564e14690606c3b03ea596.nq.gz
    ├── 4b2099dfabeeb67a83d559518909d66e427d0df7.nq.gz
    ├── 4b8d6f2462f480af70c74a7cc372e95ff8818e2a.nq.gz
    ├── 4becf8aa037a596a158b4b2cfafe047980fc7430.nq.gz
    ├── 4c3d3e6ee2b707fa0bc92a58a069928a6b8cfde6.nq.gz
    ├── 4d53302f74093ef726000751457be073f9e5dd96.nq.gz
    ├── 4e2b00f86ea383898733c2e0c87b3132abbf42c5.nq.gz
    ├── 4e30693153ed0db3840608c810142d7dfb895c5f.nq.gz
    ├── 4e5dce624aeecaefcd956f0f5f2b58ea3a5d85dc.nq.gz
    ├── 4fcdf31f43fcf58a85bff185a5874ba2f10b0e37.nq.gz
    ├── 4fd7fcc8bb5f22838e8d4293b69f53ceae88b77f.nq.gz
    ├── 521a3cd8bffad990da3a630690781be3c513e9c4.nq.gz
    ├── 5271aead75604abc54d8ee4ec1a1fa4bbb6836a9.nq.gz
    ├── 527eeaf6af2ee0f29969378d3b64fbe8d7f10993.nq.gz
    ├── 52aecda76b66ac9b014c39afdcaf2a27bc30600d.nq.gz
    ├── 52cd7d85539f9ed2903b9304cb04bc4bdd82f348.nq.gz
    ├── 536faef09a9fac6df0d597d767d7a35ee91ede10.nq.gz
    ├── 5384db225d0f7b62854921d28948a7a86199aacc.nq.gz
    ├── 54327891418a52fd3073076f70f5aacddd34c312.nq.gz
    ├── 5452a88b99007deaa4aae79bbdd65c86759c37ab.nq.gz
    ├── 54e19c57b3e15785e8b6f7d0ef4ba47d41a52ce5.nq.gz
    ├── 5504595a6678f2a3a6332bc8b1fe7c832b45fadb.nq.gz
    ├── 550eb15a4720a50847abc9c84eeb354895d0bf66.nq.gz
    ├── 55392f484beaeeabed0727db8be568e17e747f89.nq.gz
    ├── 5624d9f9839679be7b7dfb8c207b5f459ec23fa8.nq.gz
    ├── 5684bda9425fc8dc6e1f35a3dae62f73e58a7a6f.nq.gz
    ├── 5712a36209fb6cbe16c093cb5faf4c7a68b53426.nq.gz
    ├── 571f3f39601b7b3800fbef876d165d09aece7420.nq.gz
    ├── 57c03a528f1998f04bfb9fb4aa408064609657d7.nq.gz
    ├── 57dea9cbb6d33b1e30e209e1f7235f1a7a4ca164.nq.gz
    ├── 58549eba1633fcd8ea1a4de1b785571e9658242d.nq.gz
    ├── 5940b7d47dc71a6fbadc39c4026230d9e29f11f7.nq.gz
    ├── 595d8d1e90de915b2d1de00f515890bfdc0e8735.nq.gz
    ├── 5a771076a54a85e36b124cd6e09a200429ad2ae0.nq.gz
    ├── 5b5a429701d6b22c2fda387498c10fae222c7432.nq.gz
    ├── 5c8f95287ec7ef7786f6fed828caeb5ed9bac5fc.nq.gz
    ├── 5cd43cc98427e60c0f58bdfbfb38242012b9fe93.nq.gz
    ├── 5cd9c9f69cb1b2b9998ef20ca78bf9a14fd89767.nq.gz
    ├── 5e441355fc1881923c252cf59494f2e541a614a1.nq.gz
    ├── 5f27181aaa8349a0949f25678d0aaf589591e975.nq.gz
    ├── 5f2e944d0df0ab79373b29fa970781a94b9d1842.nq.gz
    ├── 5fdfdfe0d1de02ac571cdc34ed0a8e4fcaaceb25.nq.gz
    ├── 5ff75cebef62ff9f96d5173b1054507bfca6d16e.nq.gz
    ├── 60546160ce1bbd7d522390d1a0161bd4cf8dd436.nq.gz
    ├── 606799a622b5fc1b8d4d451140057a945a4627f0.nq.gz
    ├── 60e109f394e5aa07e6042750707ad2f83d116d94.nq.gz
    ├── 61755b56f6442307c6562eec1ddc83ec8fba370e.nq.gz
    ├── 61fdbb33aea5911cfc5089b6967d4a5fb9f79f3e.nq.gz
    ├── 637718e41c94feb9f3f787498d663436f84320b3.nq.gz
    ├── 63d06a1769c89effdb407ab882edba125574a777.nq.gz
    ├── 64dd9daef307d3646469c8081de4620d59ee2f07.nq.gz
    ├── 65b134343123a4138554d5c7fa9827d77d485085.nq.gz
    └── 668276c9e42a5f845f3b06b7835a9456fd638f7d.nq.gz

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

[mongodb/mongo-go-driver](https://github.com/mongodb/mongo-go-driver)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
