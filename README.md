# Repolex Knowledge Graph of eslint/js

RDF knowledge graph data for [eslint/js](https://github.com/eslint/js), parsed by [repolex](https://repolex.ai).

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
rlex download eslint/js
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f32d8a61bb5a50b09754afdf079343e5d747a444
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f32d8a61bb5a50b09754afdf079343e5d747a444
│           └── chunk-001.nq.gz
└── blob
    ├── 004372dd329ccfe6e267cdbeb7710867c0069f15.nq.gz
    ├── 00c0e530c37bdddfd260996dfca0d4faf26bf121.nq.gz
    ├── 00f4ca1e898617743a4446881d1aa67df154d5b6.nq.gz
    ├── 01201b8ab51664aa9362d88bb14e991f60c98adf.nq.gz
    ├── 01f550687c39ac84b34cf6042382c8c96bd1c839.nq.gz
    ├── 0231f32af4f1d96e9de2a79e6d9da77cc00213b7.nq.gz
    ├── 02458f045eb3ab155e4d56921cd0f51c8eb1f662.nq.gz
    ├── 0256dd4400095f2df55fd33e9fcf0fc5e2f780ed.nq.gz
    ├── 026c9ef1051f98fae758884a923afda34f64a05f.nq.gz
    ├── 0285d9bf221a8ad1b368bc3bf68f6b3722a58c59.nq.gz
    ├── 0354e8a4ea8badbb7b9ed1d4388c332174da2e4a.nq.gz
    ├── 03fa9cb6c503fbfbd7286b4b90c5f86ec76ed49d.nq.gz
    ├── 067f18ff605bc9ecfe424a9de56616851d7eca86.nq.gz
    ├── 06f5c2a384ead1730341084a1cfd8f9570097d1d.nq.gz
    ├── 074d5d40813ee6d64fa4b3ab7e8c3f87d6650dfe.nq.gz
    ├── 07c20b595e782914e49f40d5c46cd6b656dbbce8.nq.gz
    ├── 07d2f472724a406bf8486199de982cd5e2cb57e4.nq.gz
    ├── 07db7a79d553cae4e46154f281a46042a4587619.nq.gz
    ├── 080f8f88089a32ca25a53b1867b9c0437ba86cf6.nq.gz
    ├── 08255c4841a1f09cf431cdf363bb77efb6cb49d8.nq.gz
    ├── 090dccf02df695d154e5a168627ba1b073e6674c.nq.gz
    ├── 091e0f8b59802c9f3f5a621d60bb00e8f99ffbca.nq.gz
    ├── 0924c4b6e77320b999ec977a619e980016701446.nq.gz
    ├── 09be44ec85e295c290fd08d2af17148d2a99865f.nq.gz
    ├── 09f110a631ff874e4a8a6114dd43bf386bd4542d.nq.gz
    ├── 0a679a95f2c8223b82607febb1465e6ca9c1a7af.nq.gz
    ├── 0a69310519e114cdab0797f8a8f43236025fe437.nq.gz
    ├── 0aa03bd886ff64d6c7183df6ed2ca389662fce0a.nq.gz
    ├── 0b5579bf61fe2ebd6821a0e48cc14bfd54e508cc.nq.gz
    ├── 0ba8a86a5a83028f53726002f5824bd8a509fec7.nq.gz
    ├── 0be6e5d967b28d4060a874546d91cafc0667fce0.nq.gz
    ├── 0c168a31648e53a567b067fa3f1cebb4cdb872c2.nq.gz
    ├── 0c8bde149a88e971313aabd666c286107e95e4a9.nq.gz
    ├── 0c998b1284cf81866502aa85af91f4211fad8e33.nq.gz
    ├── 0ca3f619febbccef408b65ed9a78d7a5c0da4351.nq.gz
    ├── 0cdb57ad13978415b8b3fb511d34e472253ea5a6.nq.gz
    ├── 0ce82a509cb3570011e2fe2a19bc778c6a0ba051.nq.gz
    ├── 0d095fd35d215742e5dc59f5b5f14326647b2241.nq.gz
    ├── 0d2f12cb4e4965725f85f63806df1f40e95b1ea0.nq.gz
    ├── 0dd8baaf05f93c9c808ec6a2a6c634c79a609945.nq.gz
    ├── 0e5616060a7daf4c26f22e4f424492e410e7137e.nq.gz
    ├── 0e867f2859c83d9eb3e29d517d9186d562cd30b5.nq.gz
    ├── 0e97c6e2a882151a845958c712a2e41c6865a9bc.nq.gz
    ├── 0ef2df937ff73279dcbfd524b0463fcd5aaa7dc7.nq.gz
    ├── 0f33b9032923d570e323ee581a890be8e15c6e6a.nq.gz
    ├── 11d5cedfff0bf94fa51b59a8ecaab22541f4306d.nq.gz
    ├── 12037d2dc53293eb0170a28fab2e9c000a4d2d4a.nq.gz
    ├── 128cf10419b4c7600195cb19176bbc2fab66ca5b.nq.gz
    ├── 13c71041e6e45a851c026777de897f8d8ad75acc.nq.gz
    ├── 14524dd0d5e452d7500a1263d328a9d9c3ffdfec.nq.gz
    ├── 1460cdde2bd49ef9fc9a5d87ef6fae350f84d95e.nq.gz
    ├── 14e5e1dcb0b8b84f3c05aa76c8925d03d1b01232.nq.gz
    ├── 14f73a33dbabbf2b032e46318fb6ed69e42cda4a.nq.gz
    ├── 1537b02df4b32d57780fa71c8e3413971ebef012.nq.gz
    ├── 15614ac7602e97ed74bfa76c65f78095672f8a85.nq.gz
    ├── 15617f88e041ab3660d0273c9b1e84472384158d.nq.gz
    ├── 15c903627a496e81b182aa6d98a732dd79f39af7.nq.gz
    ├── 15dda167c6bd2cedcbe3a58168dca0506547a1ee.nq.gz
    ├── 162b9fafc673c5aa8cea37d5a8da6fd512b580af.nq.gz
    ├── 165980e6eac5ee9df7fa6cc78ff1cd8f48889f06.nq.gz
    ├── 167802cd6ec629561d3db18fe3fd9fdd1907926f.nq.gz
    ├── 16f0ffbd6355b56280bb3673b76f7ac9bd32a7c2.nq.gz
    ├── 1740302f82917b89b32504300655487b79fe110f.nq.gz
    ├── 17688abc0a315dfaf76b04b2bca79420843a907f.nq.gz
    ├── 1773f4c3c0584e226540501b15516ea761454676.nq.gz
    ├── 1798fcfb0f4efebc66439c3cc7fe61ac00bd7033.nq.gz
    ├── 17a25538d9bd634bc079642d35d7a6422a0d850d.nq.gz
    ├── 17d2547f1d22c9e54b70297b0d780fa2d4f02ab3.nq.gz
    ├── 19114295ee8c27034304ade639588b4a9d9f94d2.nq.gz
    ├── 19cebf9377a826b5a1ba05398cd758779941e40b.nq.gz
    ├── 1a8ecca05ecdb38ee0c99fd702920c1a9ddb0ade.nq.gz
    ├── 1d2632ed06d5f972b29a39b7f1d1cca0fc974d3c.nq.gz
    ├── 1d49c9b1f4995ae257b4ff3a2d710ecaa6625829.nq.gz
    ├── 1dabecb89842b7d9196969ed9f718ced84648b98.nq.gz
    ├── 1de9735e33370da5ffe76b0a2d04462a95d7d659.nq.gz
    ├── 1e8bf2b6140880e39ab7c1daf59a6eb655937569.nq.gz
    ├── 1f828c1486d80db13c2967dbd1b0740e17f0a5af.nq.gz
    ├── 1f883df171dbbbdce55cc5a7e2c0d4787c8dfe62.nq.gz
    ├── 201b85ad9005e1e8925bf85979df2c6e8dc334ef.nq.gz
    ├── 20aefbc996745f7359468ad26e62359afc1e4ec4.nq.gz
    ├── 20f2c79d2b3c4ea95f74cbd1eaa2c91cd1af9c64.nq.gz
    ├── 210e24692c4e7bf98a556eab027a0223eda71d86.nq.gz
    ├── 21626febc268bf4f5ba60818e5a44b9ef81f90d9.nq.gz
    ├── 2208e7f574990496b5fe9bd57ed85c83708b5ae2.nq.gz
    ├── 22275472046516d1152f8b555012e2bcaccaf118.nq.gz
    ├── 223ed242f5ec460d7acca1ae649061f51f9eb340.nq.gz
    ├── 2342f57846a3a022a235b778cbed6697e670d588.nq.gz
    ├── 236e5a136ca3150d824273ab072f6fb26b44878d.nq.gz
    ├── 2379b5760ee6f8dd98adf4a42fc4f12915361e40.nq.gz
    ├── 2389307a37be6756a62f1e969c8744a83b30a0de.nq.gz
    ├── 23effeade324103734668097b3162cba47f28d31.nq.gz
    ├── 244694c521559a31f23faf551888bf2b34772725.nq.gz
    ├── 248cc450ad83eb354b0d64c2ee14321cbfeb007e.nq.gz
    ├── 24a345559a46570995f4445d2191489880d9528e.nq.gz
    ├── 24da58ebf114e7ebf321d6ae56e7b51d6a2330f4.nq.gz
    ├── 2537287de022ab20b489d14fd426088f32987712.nq.gz
    ├── 25921f51bcc7284f97314b73868885e80aacd980.nq.gz
    ├── 25993b363d55f3610f6c2f45eb1ee92077a7f4eb.nq.gz
    ├── 26163b376b36400674198267040da72270b7cdfc.nq.gz
    ├── 26ac16e44cfa306f1f382fd7c9867c43ca45b4c8.nq.gz
    ├── 29b8588de8f1f0a29ee2be52dc62f0523b1d0526.nq.gz
    ├── 29c777ff55487df60c75af1162e62bee8b57b049.nq.gz
    ├── 2a0e3d52fd026d933c37aa131327be9b6d5b8131.nq.gz
    ├── 2a4b700478b90d195dd3e5d9eab83871c1ed5775.nq.gz
    ├── 2a522f363dcdde9a6f769fe1e4595e98ccee0abc.nq.gz
    ├── 2d5d64dc958aaf7e549d0d39496442e0a3217de6.nq.gz
    ├── 2dc64a25fc48fedae663e268e5c5c23e9c833212.nq.gz
    ├── 2e902ffa05e2ea7119e094d6195a7b5bfce7439d.nq.gz
    ├── 2f328bc2a36f72dd29c13c69ef27751fa5fb0862.nq.gz
    ├── 2f88eb2e875e8c4a5c2c33bba3f3f0a4412ebad2.nq.gz
    ├── 2fb83c2349ccc5ab5788af5ff446a1e5456d307d.nq.gz
    ├── 2fd03884a10d0356c0ef374b58325d231a45061c.nq.gz
    ├── 309cc757326039ce93a6fe68bca9bafcc5c41274.nq.gz
    ├── 311ce64d9f0bceff856a2d199337e574288dbcf6.nq.gz
    ├── 323db9ab0916308ca757b6b5ca70c7ce00cf06d7.nq.gz
    ├── 32db0af8b885320929c0c1f2a3ebe017f7ddc1ea.nq.gz
    ├── 330e31eee17219fd46e6096cd2550fd0a71558be.nq.gz
    ├── 339ad37e9cbd0e46c284ea6caec1c2cded716d90.nq.gz
    ├── 33ce0e95c298da43d90bafcf1450fb546485f601.nq.gz
    ├── 340bc7245f8b5faff7f4c68458661b20b1a7d8c2.nq.gz
    ├── 34faff3953eada6f6f5809b9916c7b4f09f73428.nq.gz
    ├── 3523d7471207ad2d4cf95d6d9606ecddd80019b5.nq.gz
    ├── 357a68294e0a2960137e6913d62ca080ae8983f3.nq.gz
    ├── 35a4f8e4b809a4bd2208b6db77a9b736b0509d50.nq.gz
    ├── 35cf2d6331ca929ae62246a6fdc5b558c93a33be.nq.gz
    ├── 360727b872ef9421f00edb6401e2aa12ce855636.nq.gz
    ├── 36d1eb699dc4646491561abbc3c32e05134b576a.nq.gz
    ├── 36fd95cc58b2320393e1680fee7cbfc87be26f4f.nq.gz
    ├── 375b977273312ce69bb3cd7bc51336be8338f298.nq.gz
    ├── 37a088a0f158c1adcba630eaa98f7f03c2326688.nq.gz
    ├── 3811042e8cff723cb5091be4104a1fb5d0b7d909.nq.gz
    ├── 3815ac8d7b4f7ac437fa2b878a4af48e307c9e95.nq.gz
    ├── 3864c1b2799637c92a239c008c4f8d7b3f2d7115.nq.gz
    ├── 386baca17315fa781213b366c40be40d113f1142.nq.gz
    ├── 386f79339d669b1e69d61e5a4624da8835980c1b.nq.gz
    ├── 38ead2b675f6122171a7bf2ead5b893a6ca5e3a4.nq.gz
    ├── 39d2b99461a0c806c8ac3d2fc09470774769c20a.nq.gz
    ├── 3a034be5382c1fd311f3f501ed2bd1e9234a47a6.nq.gz
    ├── 3a62a76e8560e3443acc2c74541c733e3d3b2fd8.nq.gz
    ├── 3a94b512597ae0565e8f5edcc153db677ad314d7.nq.gz
    ├── 3be982f572751cd6ccb4a1f1ff80cfa48d911bd5.nq.gz
    ├── 3d22cfd53f4f845a1e92584d3015bd89a4eb9ff4.nq.gz
    ├── 3d4aef87c2f9af6ecffcfd7db4cc2a6356f2381d.nq.gz
    ├── 3e0f665bcb3ff23873413b3eb6c520e6eec9c0bb.nq.gz
    ├── 3ebb74e37ac2e0e7e490a4dba34522ad2abe2243.nq.gz
    ├── 3fac74bfaa665d80dccb31116401682a3cfae03f.nq.gz
    ├── 40585f15c755e94a34dcd5402f13354bfdcf8292.nq.gz
    ├── 40a21b47d820c20941578064bd3a33f212273312.nq.gz
    ├── 40bb7fe8ade678c925e34cba86abcaeaf56d7901.nq.gz
    ├── 41756a59208f4d93da82a3041c106fde6e19cc15.nq.gz
    ├── 42ee86eb04a9e1d1d9323888f695c50bfc04a2c2.nq.gz
    ├── 430f10ebb6d4e16fe3f14b391c5d11ed784ead4d.nq.gz
    ├── 4351b5cc37711caad8c0e9e1fcd941bc40bee347.nq.gz
    ├── 4416235878e35d165e0a6b1934a59f187c636f79.nq.gz
    ├── 4416a4832bd3b43b88787402015a15c642076b55.nq.gz
    ├── 44babfa4687e64dd96c02c17d8773352c0527acb.nq.gz
    ├── 451039260ba0f6516e85aa3e1a8f7c2ea3bb586f.nq.gz
    ├── 467107daea6f63f85d83dc37f74afc5bc3820835.nq.gz
    ├── 467552325fd202f35c08f8f3b1499912fc39f445.nq.gz
    ├── 46aff2f8f1598b6c22efa11624b2c47ff4fa6415.nq.gz
    ├── 46e2e4d1cf38dd39bd35f0043c82d0d14d1d3562.nq.gz
    ├── 47f5919fba71aa0cc904f60f69baab949b208d25.nq.gz
    ├── 488863f8a144f49107aa06bb70ec28a33a30f1c5.nq.gz
    ├── 494e48a660a77fe8de2db8bbc7f0e1b7667b860c.nq.gz
    ├── 49a04ad0bcf9f093cd68c197b8a5d740534209f3.nq.gz
    ├── 49a5fb3e10dad9de490850c063057c082e4a8d3a.nq.gz
    ├── 49f55da3b4c8f57e55c849041f3d6601bcd2377b.nq.gz
    ├── 4a6196b9abf7ed398dc7b42cd06e2c94ab5f7f01.nq.gz
    ├── 4b3f9db2b6a412d95d21918992cd0e6e031dc2cb.nq.gz
    ├── 4b6d5d3f6d2597c1fa9af30b855316b879809a96.nq.gz
    ├── 4b8882f7305cad5ae7ac61fc73f516138477e1b1.nq.gz
    ├── 4ca19d3f9832dcf5d1139d5ca5b3d853b7b0fa39.nq.gz
    ├── 4d48d9f444768595e72de8e549fb4651cad6be39.nq.gz
    ├── 4dc0eeb08a3465bc665c99bad5f30c6f90aaf48a.nq.gz
    ├── 4dc892be77fb2f4ba531ba6af43f6202d0eaae26.nq.gz
    ├── 4f37d67fe60f9df8abc782aad9106c3caa7ac5a8.nq.gz
    ├── 4fbafb3e617ee44a337c840ff79920b3bd06fb05.nq.gz
    ├── 503dc7e6080d47ce9c232b7262c30ac2d9075df0.nq.gz
    ├── 509f52cae4ba6ed6b72a68a676459fbb0a0b1de6.nq.gz
    ├── 50ffad7279c04042146aac09984a460b884d0fff.nq.gz
    ├── 511f4c884dafcf17c8ddffaf79ee50daf388c449.nq.gz
    ├── 5138ffb142370c1a10415bb0641fdca434b87d53.nq.gz
    ├── 51c7ddd9ba9dc24d6d5192b9df18bce4497b5865.nq.gz
    ├── 52b850d0366f5ceca07abb13b000d1410e30fc24.nq.gz
    ├── 5320beb0a81e0a417b7c6cad206965267185210f.nq.gz
    ├── 53937bb4b426bb6a6cadb8f6793b9ab0b9a7c567.nq.gz
    ├── 539e3780e45227d48243c41673fe2c35ee5ca291.nq.gz
    ├── 53b1654cb828d48e386ca242f0fbc48cb6c15c19.nq.gz
    ├── 53bbb5dfadbcd12a03a14ae91567045e0ab29e3e.nq.gz
    ├── 55a983f23ad26f4e2ae3d2c685ed7211abf9f32a.nq.gz
    ├── 5616e4b17adab6a25d6bf4019983d4ee44fc17ea.nq.gz
    ├── 5618d7fdf2c9702993a74785fea7b97884325f6f.nq.gz
    ├── 5625925eba53a62073211f5e160faa3d9dbe7fc6.nq.gz
    ├── 5682041b2a17967e2f723d5a3cd391e15f13ccd7.nq.gz
    ├── 568f331b89a3efccf69d20c78d314b8f1d4d83c3.nq.gz
    ├── 5699c183ea8efde73b9f1f524327027dc53086c3.nq.gz
    ├── 569f8040ed8fdf69488c572570a9b9e6f9f40d11.nq.gz
    └── 57e20018c2d30f0941c99a10f1e7b5f60a2bec43.nq.gz

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

[eslint/js](https://github.com/eslint/js)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
