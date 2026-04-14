# Repolex Knowledge Graph of lxml/lxml

RDF knowledge graph data for [lxml/lxml](https://github.com/lxml/lxml), parsed by [repolex](https://repolex.ai).

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
lexq download lxml/lxml
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 973d059449a66799f468b46f4b12c95e32cff5e9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 973d059449a66799f468b46f4b12c95e32cff5e9.nq.gz
│   └── repolex
│       └── 973d059449a66799f468b46f4b12c95e32cff5e9
│           └── chunk-001.nq.gz
└── blob
    ├── 0249a45e2c4b757f236ab5891510934f9add6b3e.nq.gz
    ├── 0300f9d562db30c9d76d4dc98bc60c3c96c0f647.nq.gz
    ├── 0321f8061952e62ce88fd79dcddc30480930237d.nq.gz
    ├── 041e1ec8ebe59a5b86e38785a18a25f76f50602e.nq.gz
    ├── 04fea06420ca60892f73becee3614f6d023a4b7f.nq.gz
    ├── 066733666d1a0b9463d04db84b870ccd84d4a5a3.nq.gz
    ├── 0674111132ee3c2da8f2a3ec1db7d9dbb462ad30.nq.gz
    ├── 0786d7dbd57c3f45644232e2da360e7fcac7d4d7.nq.gz
    ├── 07e0cd7e0ed52b14ec88b2876308fae66dfd651e.nq.gz
    ├── 07f40ff8ff0a6b38922e153e4e84cae962651f44.nq.gz
    ├── 0a25d2da4f96309c91f80546e525851e71d1b98a.nq.gz
    ├── 0bdf03913ffdfd09be5a524c9303bd54a132d450.nq.gz
    ├── 0be2bac4f0bf2d992bd2793a443f915c2e714895.nq.gz
    ├── 0be38f98cb13986c9bf5575f86d4119649c45958.nq.gz
    ├── 0c2cf3d6ae86f6c6ee65742ed2dbb8c50f99f89f.nq.gz
    ├── 0c5f978aba80414a3a456b5802110b4ccea5a1b5.nq.gz
    ├── 0cb6eb3a58c5910770733e8837c5d296049fe4cb.nq.gz
    ├── 0e7e03ccc5b88952e660648f5cefe7525a7b0b71.nq.gz
    ├── 100c92741d0ed7a4aa015a7f67bdbc46673fe637.nq.gz
    ├── 10bd97beda3baa917481eb0f3128d6b9e585b60d.nq.gz
    ├── 1233952e3927a9c1963f3637bd7a9f346d04051e.nq.gz
    ├── 149a414df04e316ad4b08c67a7706bb1bb725e8f.nq.gz
    ├── 14d8509e97d49115f397b5f3b801c7f94ed73837.nq.gz
    ├── 14fb92633d717de8193c4ceeca04690e16227e82.nq.gz
    ├── 1531f6d98fdde3319e453826e12e375a80fafcc2.nq.gz
    ├── 15582a113a2186cf8544caf311b19adcc8d938f3.nq.gz
    ├── 1576eb8d24eef7b132acd9b469451d3c27dbac3b.nq.gz
    ├── 1592ed3e7a2eb9eec63c478aa296ecfb1165aa23.nq.gz
    ├── 1689f3bf423dc504e9ab28ee84d800705c6cc20c.nq.gz
    ├── 181248afd6ab89811c896f2992aa8bf4c69affe9.nq.gz
    ├── 184c124f01eca52eadd9c119cfdc9cdc5c1ce380.nq.gz
    ├── 18ab87a8a2b37f6916883b3817005701e6e31d8e.nq.gz
    ├── 1b2386f623acababa4e41ed12bf39537707b8144.nq.gz
    ├── 1bedfc8168b8abedde79e19012f9424197332d2e.nq.gz
    ├── 1cc05cf8c3feff473c0818a46d42ea6e8dacfba6.nq.gz
    ├── 1e3bc70304d0cc10976036ddcd0e314756b90f36.nq.gz
    ├── 1e95def94eb64d9982b44603e6b59ba29020cd94.nq.gz
    ├── 1eefa1f3d437a075ff72ced4dcbab65269d49780.nq.gz
    ├── 1f02b7f32d3d167f3c7503f8bcda8a983f846da0.nq.gz
    ├── 201765f7e238283105bab72d3cbbfe86bd65fdde.nq.gz
    ├── 20e1c2e9d6dfb47dc10d561d9df7297dd03c0147.nq.gz
    ├── 21884336f534cd2013165934111146684c9909cf.nq.gz
    ├── 21894b9ef5859a455fd2f9f4443e805818b94517.nq.gz
    ├── 21a5d2a069cab9fa327d9a3cd4e4d56c21bb10db.nq.gz
    ├── 22069eb7cbb576b6236f53912f8529863a07cd08.nq.gz
    ├── 23188eedbc2451d4536a44fabad7b4635b4af44c.nq.gz
    ├── 2359eff5d03c9eecaa5c07238382adb2b3f672b1.nq.gz
    ├── 23b1e1c5fb07a400f1b214450c0019b200aa569d.nq.gz
    ├── 243d0e61f2e94fddd29b0b46e54c7263124627ea.nq.gz
    ├── 244a46f786d51464f44371ba971e2d96ece3a6ce.nq.gz
    ├── 2473cfb84858a1e6a841f665766cf113878cafdb.nq.gz
    ├── 24d83ba8ab001236e036aa6caf88c64a51277e37.nq.gz
    ├── 25ae1809b8faf42138750c62b562dc2c511c13a0.nq.gz
    ├── 25d4ba191fe950e8a76ac71d1e2ba7fffad9f21d.nq.gz
    ├── 274afff6c60a028ba854289fde5350dbc3e49a5f.nq.gz
    ├── 29005f470bf3d4c2f7266eba5baa4ffb1dc53c9f.nq.gz
    ├── 29db736a064bdea808cfd24d0c73ccb1ef95680d.nq.gz
    ├── 2a630df73a872dc8c05f02576a555b2f10c6dac2.nq.gz
    ├── 2ad49db11b20e4e710f4f55cf5590ef3928f1058.nq.gz
    ├── 2afa15ccb363824e1b32be6c92d8366f32132326.nq.gz
    ├── 2bc999f0f64f9e137812b9ac5617293b9ad89bf8.nq.gz
    ├── 2c55af578cb3d7efb8641f1b76a5e894411042fc.nq.gz
    ├── 2c83794974902a4fd83a4fb45b11b6e783430d5e.nq.gz
    ├── 2cee9f441d896b088bd873aa1ceef12abbb31dda.nq.gz
    ├── 2e7544b7ba11c6caa4fcdfdbd36bf13376d83df1.nq.gz
    ├── 2eccc29231abeda4b77790dfde9dcca4036b8291.nq.gz
    ├── 2f7be1568977aff1ccc6533f0626226e0f57bec9.nq.gz
    ├── 30164c48a03dff31865387aa507e0e6c32cf0999.nq.gz
    ├── 31dcc406cdc3d006afe811e7e1f778b56407510f.nq.gz
    ├── 31e2071867257cb3300a5f14cb0b302e1fa727e7.nq.gz
    ├── 32c35f35af6440da150e737254253a5d6a68968b.nq.gz
    ├── 3382bc022d9365c58cf361637501e4a430e004b6.nq.gz
    ├── 34c273f13f519a87b587484a06410bd86447eac0.nq.gz
    ├── 352f63134734780e5a9c869ccb59b4cb4e4ade40.nq.gz
    ├── 358adc87fcc187578175c5192d3883314ce8fd6f.nq.gz
    ├── 35f875891f7e59a785518b8b70bd19ef3f0f6099.nq.gz
    ├── 371fc6a695af4c0f05d1d9d430fbc6b77c4942cf.nq.gz
    ├── 37c29957dd12e7a685a6450c408baa68e2c3de02.nq.gz
    ├── 38508a47f6b904aff0b135056ee3a8059c979ae1.nq.gz
    ├── 3873719c18bd3fb05c9ab7b59fcfdb5c25dc848f.nq.gz
    ├── 3873e1db9b897726dd496baea356ca883af8afa7.nq.gz
    ├── 38ced243544553127e3fa2aa57ec6476cced3043.nq.gz
    ├── 3a8ecdc5aa4428929149e36238e205aafdca0576.nq.gz
    ├── 3accd0558311aa6bbad6ee711ad98dc7d7ba2c80.nq.gz
    ├── 3b0e3fb2a2490850e6de0ccc0f3d472c7a9c06d3.nq.gz
    ├── 3b7cd021a8e13ab52721aed7d1558026c75931b7.nq.gz
    ├── 3dd455a31843e7183532b0fcb59c74d86654f1c3.nq.gz
    ├── 3e0d323bad27c286bf219fc21fcbef464eadb6c7.nq.gz
    ├── 3ec45f91d9f61e2a767515daa73dd03c5bff4a3f.nq.gz
    ├── 3fa84b1e9860141c20dc4c40ea97e686dae3d905.nq.gz
    ├── 42b7524998f8633ae4ba8014314b0c9ad5d30628.nq.gz
    ├── 4385a3cc333386bbc834eec7a25138229fb4d020.nq.gz
    ├── 43a52589cdce5ba47ab83820e4f79f2ab110f074.nq.gz
    ├── 43a52e647be68a5aea00f7363df1df1de4f2a48c.nq.gz
    ├── 44916c2732b7d9d1a27636f68e13bd5980be44b9.nq.gz
    ├── 44e5573b73077e015d404935479bdc9344c5ea4d.nq.gz
    ├── 4560f07a96fe968a2477c52750e58576cef7d1b7.nq.gz
    ├── 45a05c494813d607818602b4d1b4fffedcf55f84.nq.gz
    ├── 45f9d5d6c92718bcff251b7a5d927eed56aea38f.nq.gz
    ├── 46f7b898104fc90a00851d06c6705f6178c61c4b.nq.gz
    ├── 484078e2290f960905448f48ba5d537c1ee3a0d8.nq.gz
    ├── 488e1f0bede5a08cbccbfa548e948f5eafd9da02.nq.gz
    ├── 499ff7d5ffa2e4875e90b98479093d8299113833.nq.gz
    ├── 4c184018ffae8d37053df35fb9f54e1db780a2cf.nq.gz
    ├── 4c1fadc6e425b05b1c4cecb04630d62902937b5b.nq.gz
    ├── 4c46d42c0b31082383700e5d25b358ebe9cadd11.nq.gz
    ├── 4c5050d8c4fb8fcfa625d4fbda4f2ca3d60bf1f2.nq.gz
    ├── 4d717ba324585229784b01d565764edd7b34f8e9.nq.gz
    ├── 4d90c87a9240fb78e820d5e30b36b72ad458944d.nq.gz
    ├── 4e77ac7616a2789c4696638f58c1c6a69f62c802.nq.gz
    ├── 4f35ad9662df3b39688af52167fa9e012e160c74.nq.gz
    ├── 501161bad5187fcb2750b004d751936bb4c6c247.nq.gz
    ├── 5018395234799dd65d53a339daaddf445a09dbea.nq.gz
    ├── 51869c0c8e6054fd3fd4487e9f2fd5e9135c7af0.nq.gz
    ├── 51c9b563ee939aabbefdd38699a6f94dab7c58e8.nq.gz
    ├── 5266bdf2bdc71a0bbdbe0c8702dbc43f5684ee28.nq.gz
    ├── 537bfc79fee59e2b0459a509b59297310f6290d6.nq.gz
    ├── 54cd75ac9bfecdec7ea81e91b0840c6edd401515.nq.gz
    ├── 57aa02d5195ecd8e0f91533445229c2d85cc8e6d.nq.gz
    ├── 584058b4de249e0fb240ca1619e6e4e77c66ad88.nq.gz
    ├── 584c2f2af6d5a2e22a62007bff6fae9f982e9d80.nq.gz
    ├── 5945080c923a80f573ecf02a74b2706637efb09e.nq.gz
    ├── 5a838e562acc89741e016990962b04ebd46c73b0.nq.gz
    ├── 5ac96711e7b8124400fe6a8acb59f0e4192d2949.nq.gz
    ├── 5c01e21a477f1e9e89c2a8e1a61b4896f222673f.nq.gz
    ├── 5c5d544a0df845172e48a8be291a0a28904fba9f.nq.gz
    ├── 5c71d8d2870375877016d9860be121c3bb73d5e2.nq.gz
    ├── 5c9ac45096efb2250e268dd2eed9ade07c2ca998.nq.gz
    ├── 5d3806537993d9bd18620492fa3f00a4f63d0863.nq.gz
    ├── 5d80c4b6111959a0ca5602b26ba47d4bc7a0820a.nq.gz
    ├── 5e56e7f53d250b53217d2b720db8edc02e5f3583.nq.gz
    ├── 5f448a16fe6dc7a03a4279fb19f9ba3af38eb634.nq.gz
    ├── 5fe9b89c702adcb5a7de7f29194af13e3ec250d9.nq.gz
    ├── 60e5d32dc88d2f35d1cdb02af6d8f6afdf2d392f.nq.gz
    ├── 6102b021d8025e52baa8621dbfa3a4490f11b293.nq.gz
    ├── 610cb3748b3659be262ab1a3eaa88d93764f3f17.nq.gz
    ├── 610eefea66e6f727be102d2b71d3d80f3ea330e4.nq.gz
    ├── 6237293b166bdf2e05c7910d80ef6b14a4a7f39c.nq.gz
    ├── 626fc48f410fa01dd1fabdd27a68ede46cf26842.nq.gz
    ├── 62d7e004a44034e49f2b86808bba27e99a8118f6.nq.gz
    ├── 62db519ed905170bfb9ef3bd52c53c35ffff6968.nq.gz
    ├── 6417fb9d0e52c789a8c9174594420427a22ca495.nq.gz
    ├── 6438df32e49a3ea3540a0311a3807783cec56fce.nq.gz
    ├── 64b3d7bd50f85ae4db94341455d692f1c6d49b88.nq.gz
    ├── 64b59ec90b016a08b5aca9a7a1cf5692b91bc6cf.nq.gz
    ├── 64efa60f5fafd6ffd361f7c6f1d3c3e33a153067.nq.gz
    ├── 650e34b2b4c562517479b56a8f6f45b7111efafd.nq.gz
    ├── 65f843733480bc36b74ed24575bc65df4ad03075.nq.gz
    ├── 662e108aa8a1e47f63e89d8411a62b138449d2fe.nq.gz
    ├── 67053cf13d26e75bf39df41730ec9c6d4e63dc83.nq.gz
    ├── 674b076dd6d9a606be00447267071efb47708c4b.nq.gz
    ├── 68267175afa602f6bb0970566bd5f71f2d318af7.nq.gz
    ├── 690ed95271cff00d470d2a43a32c2bdad402524b.nq.gz
    ├── 69a940b872fd6be01d6b2a7bb4fda0f554074dce.nq.gz
    ├── 6bb862d763d7377d8d3fe934e290cf1a1fac6888.nq.gz
    ├── 6d579200c9dc8c61301cbe8cb6315445ed95e540.nq.gz
    ├── 6ee9cc310b462f27a94dc6b21cb52b2b08903e6c.nq.gz
    ├── 6fbe53673bd622edfbe4ca0b3496eb365e616408.nq.gz
    ├── 700a16d42a7746495fe4fcaae1a98dc8d458fc90.nq.gz
    ├── 70df649cecc20ec2585b4db09b8595a812283161.nq.gz
    ├── 71052836f57d6a6298c8a2e42362357931f4e708.nq.gz
    ├── 733afa6182051a6a0576278438106e777b5c4c42.nq.gz
    ├── 74eeea147c3791a54dd21369e094433e5a5664fe.nq.gz
    ├── 7520cf3fb9eb281d5ffbc79e41975976fd6d4df9.nq.gz
    ├── 75b945d2553848b8b6f41fe5e24599c0687b8472.nq.gz
    ├── 760a1e00b8e1611e3915085482af1d9efc3a6ae1.nq.gz
    ├── 77ccfdb70edeb8679a4797e7dabdaaa9033788f5.nq.gz
    ├── 784dbfc183a66017b832b7462dfba16af0d735aa.nq.gz
    ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
    ├── 7a1dc32946bce31e153da6d0ac0c9635b2a27bb4.nq.gz
    ├── 7a702b222b1c0868aa18e5b9791c09eee11d12ee.nq.gz
    ├── 7a8402575b1797df7db0fcbe28c65bd4a20207e3.nq.gz
    ├── 7ba79ef7f7d128083f9de1d4c90d935a783e9615.nq.gz
    ├── 7c013f56ae738d897fd514f9d8d3019ddf3dd589.nq.gz
    ├── 7c797fdcd19fbbdc4ac0cfa0dbfd14ffd4556d4f.nq.gz
    ├── 7d1b0e6756495111ca84778679542ad391c57be1.nq.gz
    ├── 7d71b435b5ea89732af41addf75a27ef79650eb6.nq.gz
    ├── 7e1ed6f0727e4c27f786c649b056cb22e03489d3.nq.gz
    ├── 7e3db5754adc5cde5b1924301e35f30ad86ad3ff.nq.gz
    ├── 7e4aa899be6bf1dede9e387023073eb0c5f537c1.nq.gz
    ├── 7ef001b17b765de2a94172412681e6029e931c54.nq.gz
    ├── 8099771de906a37ed007c779f152fe96f182060d.nq.gz
    ├── 810f41dddaf1966ccd7946de11e12c75af4985a8.nq.gz
    ├── 8157d582b6aa486d537b732ded824847c11be543.nq.gz
    ├── 8318aeea959bd9b6a9e37cbc7d4ffad746b4f812.nq.gz
    ├── 83edaae91e7423c67f350a5d80f80cc83c683916.nq.gz
    ├── 8520af5f6e721b6daa9c4ab6e25b22bc721065ce.nq.gz
    ├── 85a8f41ec2db227e86be8ef29810c070b7eb1956.nq.gz
    ├── 85dfe70d5048356394c301294d653f9c0126ac9c.nq.gz
    ├── 86444e0417e8b04f280ab6c151dc07f07b807411.nq.gz
    ├── 867980f82bfa595e3cf880e427530201abdf33e7.nq.gz
    ├── 8767d8fb32790e1ffc3d90c492b131759523335f.nq.gz
    ├── 88bc6343bc1f6724a265bd92b0ed962d2c8146e0.nq.gz
    ├── 8a92c5c61c2c2cb498ac264e3bbe5ece464f9c11.nq.gz
    ├── 8ad9523ab24aab4888124a5febedb048af8ea806.nq.gz
    ├── 8af7055cb5304aa5da50f751f96fc4162aa0f6c3.nq.gz
    └── 8b1f3c4c516b23ec938da286e0ddb7b8f5795ee2.nq.gz

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

[lxml/lxml](https://github.com/lxml/lxml)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
