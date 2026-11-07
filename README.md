# Repolex Knowledge Graph of jupyterhub/mybinder.org-deploy

RDF knowledge graph data for [jupyterhub/mybinder.org-deploy](https://github.com/jupyterhub/mybinder.org-deploy), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterhub/mybinder.org-deploy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6b57625db7e0a33e12c8264e976b7c8e1d0cd3a7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6b57625db7e0a33e12c8264e976b7c8e1d0cd3a7
│           └── chunk-001.nq.gz
└── blob
    ├── 009261b1ab648c29089a6f9d97f2fff3eaa8bec2.nq.gz
    ├── 00e6de266fa98022a15043f8d58ffb0df9271b02.nq.gz
    ├── 02bad4bf457461cd7f40428152292136f255f235.nq.gz
    ├── 043496b218da26ea3cb1295ff42c3ff9f74542bb.nq.gz
    ├── 04da5d29a9e6800ac37be3ef48ed4a5532f86b54.nq.gz
    ├── 04f68be0ee755fa9f5a804e1055aff6ea6850425.nq.gz
    ├── 0726a6cd7dbc244825d6d32dfaaacf7099077150.nq.gz
    ├── 078f608bf90705fc9fbb2bd98ff5810a1f0026dc.nq.gz
    ├── 084ea9f1b227843c7b4c74836d9d2aa9924e5802.nq.gz
    ├── 09fcdd03da3373324a37059a1f9bb06d0d052c2e.nq.gz
    ├── 0bc5fac0977ecbcab35d68afc090b07a731757ee.nq.gz
    ├── 0d18cee2c3034efcd7b2a74a7d7da7cb782f294a.nq.gz
    ├── 0fd7c164501e96f04b5776e59d43be10d7e6378e.nq.gz
    ├── 112c2b6f974d1cd44725cb805e87d7d6e6c67fca.nq.gz
    ├── 11f029dc3bfec18c72d4a4e95a5a5317a1351cd4.nq.gz
    ├── 1293289a60f117292e4068c0d73c3e8b1c16aadc.nq.gz
    ├── 12a0a0afb37d154a479c13af2fb98b18c227eaca.nq.gz
    ├── 12e3690a585ac1cb82d35225371cce02e4e8e2dd.nq.gz
    ├── 136abb5a2a41aef17c9ffcd1c4768ac7fd26eafa.nq.gz
    ├── 15e39861c82c1462c6f818cf19c7955279d61ebc.nq.gz
    ├── 16038c7bd022f81a96e2407dcb298bb9c17242b2.nq.gz
    ├── 1687d03a41d2d41ca15a82864872c3b429c16fb0.nq.gz
    ├── 172e2d32b71d444ff7d178f3fc391ea13ea5b5a2.nq.gz
    ├── 19451963f9bc6615f4da358cd33343fd79c2d3ca.nq.gz
    ├── 196d566b3ad44f8f487c87771b5ca48fd1f715fa.nq.gz
    ├── 1a5038a5891fa5f84fae49c67f5f8e09a1df0243.nq.gz
    ├── 1a83c259789e9d519e22e01ab9b1f6be9e3de8c0.nq.gz
    ├── 1aba8a56be7c82aff6b13eff9af6e99967e4f79a.nq.gz
    ├── 1ad0da5ba1d619c071547397203909ad6dee9332.nq.gz
    ├── 1b3ecb02c69c9b2032e627acb9b572410f9a558f.nq.gz
    ├── 1bedbf31ec5901a347d9763c8b3390c0940da00d.nq.gz
    ├── 1deb4d3bee0b85974220078d2fc8da12b60ff10c.nq.gz
    ├── 1e1a0455d498d3ac9aaa7bd8664a1f9642e38b95.nq.gz
    ├── 1e3557516756d489627511d4d0c64142d7728634.nq.gz
    ├── 206e48197d5b1d8fbf7e8944a578cfdc893644ee.nq.gz
    ├── 233c0876f50b8302f2e9c26179ff164f1803acf2.nq.gz
    ├── 234abc05758dff0ea32fc95cd897b858d9d7d310.nq.gz
    ├── 2376958bf115074f8608ba02fbe903ef48c9d030.nq.gz
    ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
    ├── 25b00d6470de8efb7f4ad4ebabffe3c1776294b7.nq.gz
    ├── 2600dd135e053a7c456a1deb50ac858df0f6aa65.nq.gz
    ├── 26eab5e2e35aa10e1d5df1f1225607a5c38be3e6.nq.gz
    ├── 277dfd9f9985f8f9bf98f3cade1a184178532ee2.nq.gz
    ├── 278b050f9989512e13f597bce389c6f113a35cec.nq.gz
    ├── 27bc08e17b369ca53086cdabccdb88b9d2dc2ed7.nq.gz
    ├── 2819cd7b74b5df83f0c826eddef48a29600d9d25.nq.gz
    ├── 2867bded1fd2e3fa37b0dbcd6ac01cc4c71933dc.nq.gz
    ├── 28cf08ebb8a350b80b2d0da1b2ef1855366471bc.nq.gz
    ├── 28ddafd207cc0ae9f7c283210d09dc7e86686a50.nq.gz
    ├── 29884ae80741d705faf8cdd5fa814d9f97f1f311.nq.gz
    ├── 2a74f7df541c1e90f7d660b2dea83190c9f5ba5d.nq.gz
    ├── 2bd2d472b856a621b7c5be742f9e181864119d92.nq.gz
    ├── 2c3aa486cd2f441934e1f2192410797fcc78a914.nq.gz
    ├── 2ca0b75f34535698f778f8ddec6d9353a910e624.nq.gz
    ├── 2ce7ae91205961dec817ee55c5b34bcce96a3f23.nq.gz
    ├── 2d4dd72ca1f42316730da86ca90f39f9d1dcb268.nq.gz
    ├── 2f4f117a5a3f05607c3cb257b55c77983066371c.nq.gz
    ├── 2fc1798d3d9d383bfc911d319851f62a8492b020.nq.gz
    ├── 3058e6ba89a860a72e10f684e2f367ecba3bc061.nq.gz
    ├── 30db648a9a256fe4b184aea04321af013cfe7871.nq.gz
    ├── 314d60280d88f38a6f6d21af54ec3b85a0065461.nq.gz
    ├── 325b3d9c4ad4a9a58eeb924155e21129651f1b7a.nq.gz
    ├── 33b67ed2396062f32633c3d9de386dba92e7470c.nq.gz
    ├── 33cf7338b60b3686e1a0adf63e39602c7f17f143.nq.gz
    ├── 347b9248608124e888b30b48fbd3764d7aaa75e5.nq.gz
    ├── 349fe1cd7fe158132966c9e4e82137aa7d10f53c.nq.gz
    ├── 3577eff925ad4cc8f35915d35699a08f8fde82b1.nq.gz
    ├── 36023ee4ee6e4e6be41c8547d18cd52ec960a07f.nq.gz
    ├── 369cbd7d61ebd1284f0978dd90275cd5fca31b69.nq.gz
    ├── 36cd96e996285e0d95640ac193822f616423a98c.nq.gz
    ├── 36eac99af7f3e00135f6f60a386cd45b1beb4d77.nq.gz
    ├── 36ece61540b89dd984b65f5cd3713aa3f33ca72d.nq.gz
    ├── 377c0a0b527869cacdbff14ff384b446012d0a0e.nq.gz
    ├── 39c310c3e7179e85a205a9f15b164bf4b75e1239.nq.gz
    ├── 39eaec4a40d655f4c933fdafdb180aff1275c4e1.nq.gz
    ├── 3e0713790b1e1ab8ca01f988ecb4dbdb2915ce6b.nq.gz
    ├── 3f276704a604b2940d2f443c4bcc23f40282b87b.nq.gz
    ├── 400b64dfe0294b7c009dda86cb593911f639cd00.nq.gz
    ├── 408cc8d8633df2472834a86bacc3835b727780fc.nq.gz
    ├── 4100dec02601c49e0c0bbd66db49ca5f6ab057c9.nq.gz
    ├── 41cc4698149ee01b1e40d1858a9a1b7fd85de4e3.nq.gz
    ├── 422786c0d1c2246e03e91f26c8c54ef72c91bf78.nq.gz
    ├── 44d909a1acf240993236162480dd8421dd760bbb.nq.gz
    ├── 44e61efea23cc8865848a32bc8c4b622c5e1fef8.nq.gz
    ├── 456a657d83b8edbda823c1db2dae0c664cf6c221.nq.gz
    ├── 45c166baeed47bf458c8b44dc27e0a391a343e0a.nq.gz
    ├── 462c8b9f24533cda7e73d5dd4e51726cb3a74190.nq.gz
    ├── 46d6d3d40d502ebcf296aee624234831e8a1768e.nq.gz
    ├── 4797527bd9a5fdd06965f40b442019c46fb523c6.nq.gz
    ├── 4aacba6232ca853a0b3477c016a0047cf67546d5.nq.gz
    ├── 4c2f897096095f6b48ce2a4a74c7fea56a388cbf.nq.gz
    ├── 4e21e281de7c989028d98f29cbad22c4eec11916.nq.gz
    ├── 4e9af530595a42a2e57f08e0200ae22ce7dd670c.nq.gz
    ├── 4f813df6086bb06a38388ccf2726f34d6e01ecfa.nq.gz
    ├── 500c16740b42c58726bcc368b3a6233ba863830d.nq.gz
    ├── 5213590bd36ac9191b143048b5a331c0c4083d5a.nq.gz
    ├── 532f8ac3aec0eff80cbc8774e2798fb92eadf5c1.nq.gz
    ├── 53f627ca304d00dfd9ac9fe6b76687d461f8ca7b.nq.gz
    ├── 55087b1af5bbf065db6af51a642a69360d31240e.nq.gz
    ├── 5575ab6fa1abb0f37d4633cb0ef42a93f7f5a055.nq.gz
    ├── 558bfad7a367f272540221c80436cab376dc7095.nq.gz
    ├── 56ab24b03fb71256dc1df877e0b1e050cb809881.nq.gz
    ├── 5735c74dc226d9e611ce73df0032e3e64f8e2f8b.nq.gz
    ├── 5a30664186a92bf4b6526ae31b1cf79e158189d3.nq.gz
    ├── 5a87b38037b781aa46040dd4bb012169046db1e5.nq.gz
    ├── 5aa7c2b27bdc49970261a83ab5265a09e0ad6df0.nq.gz
    ├── 5b4fff6708600b20aa66c4bcc66d61cc2a70a6e2.nq.gz
    ├── 5bece4684ded8fe9a04acf1b740575fd1a50cf6d.nq.gz
    ├── 5cc435b3b69b33d57b06a39d2bf43ea2bd9f4bcf.nq.gz
    ├── 5cf5f6b949e03936b11dfb3f3808c1b61465a329.nq.gz
    ├── 5d754c23a73cb4275791565178834774621132a3.nq.gz
    ├── 5e27519f21dbd43fccf7eaaa7ef66a7ec000eb7c.nq.gz
    ├── 5e4bd1c82bc39e3a72ae60a5371c4932405f4140.nq.gz
    ├── 5e59999a84e89fba413d3f2cc547e1b43d350cf5.nq.gz
    ├── 5e846f4500def0b03387d89c9fb7956333704a1e.nq.gz
    ├── 61218a146cdcb3da90eeb7993c5af1355e5be604.nq.gz
    ├── 618a35ed757c5ca75dd20d6b5c77f10e235f9585.nq.gz
    ├── 61a58fe28ba7b5f40bac3b45b7344836071cd07a.nq.gz
    ├── 64638f23d0f84c509afcfa4fb47bc05f5adae082.nq.gz
    ├── 651933bd5e2a59f23d5fd8bc8444579b8552283a.nq.gz
    ├── 65c5f2a5410d21f6da1c6abf8ff16a0f4ab281d5.nq.gz
    ├── 6621eabc5b57f2b797b4cc9802a0cecc3a77b4f5.nq.gz
    ├── 666371553c4ba236262976d913c186ac93f2713b.nq.gz
    ├── 67d17e9c30b8dc8177c52ab5da7a57b7f99277ff.nq.gz
    ├── 6d1024f533189654762c1b12b61ed7a4ac64dbf9.nq.gz
    ├── 6e2d3ed65df70d5fc031ee5df1db4b5f62312f02.nq.gz
    ├── 6f796e12b6debab82aea1059634641fdcfd1742e.nq.gz
    ├── 70e239bbe83c571cbbaafc0bd51467ceaa8aaa4f.nq.gz
    ├── 71a482dce7ea1b6c6e717fd3cf6bddd4c265277b.nq.gz
    ├── 73380b623929238a90febb187bdc56e864b3d52e.nq.gz
    ├── 772be4d2ba1bb7cbbfec90739dd2a92c757e1997.nq.gz
    ├── 784b4224e154fa7bfcc5d92a5006e03d27334d51.nq.gz
    ├── 78f59ffc5178cd1f4d548ef6b38370cf821eba41.nq.gz
    ├── 793862f7bfe99ad133b6080533f90566c19b966a.nq.gz
    ├── 794687597ce9f8de7c0f70236755cf4ef4d66d49.nq.gz
    ├── 796ae52625a6975454fba0e40d328e5b4abd0bbf.nq.gz
    ├── 7b7ba5e9940d03ec22e8100831c9ca2293ee3b47.nq.gz
    ├── 7bb2da3ee806e37568cb239b4290f53468cebf8b.nq.gz
    ├── 7bbc71c09205c78d790739d246bbe4f9f1881c17.nq.gz
    ├── 7cc97ef7057de9dbc53ce733e387fe8924930804.nq.gz
    ├── 7e8cd15d9631337b5401fd926d085f91161667c4.nq.gz
    ├── 7ecf7396198e59a2d00a0e79ef69ff96646aa25c.nq.gz
    ├── 80fec0901a26addbddb63f08211dc759c8462d32.nq.gz
    ├── 8246cbb7a238723b61b908426fc615bd5adca654.nq.gz
    ├── 872598f9429321a3b59cddccad0fea5a32e22bee.nq.gz
    ├── 88025cd94715ce9697c9d595265890c36cd63280.nq.gz
    ├── 889934054d4f106ebcd5a6335fc68642b8c77284.nq.gz
    ├── 8977cf8275d7ba52fc72feab460ec5fac5673e3e.nq.gz
    ├── 8b9a08a5469ae47107f6d96851fa15d24fc78d78.nq.gz
    ├── 8c35d17248478448d8cdb63684495a182c2221c4.nq.gz
    ├── 8df9f1798d5f4f897815b26f497ade631ffc1379.nq.gz
    ├── 8e11139a3d690a155b98cc425c86c8c0030cb27d.nq.gz
    ├── 8e4f17ab8a0bb05f0286483ec9e8388fe384aa63.nq.gz
    ├── 8fd443c6ffa72708566bfeb2f185fa635aed3841.nq.gz
    ├── 90f2dd10ec7c64878069ce56fae76ae9c587ec26.nq.gz
    ├── 9170c78c158c651d7dea06cee180d785febaac73.nq.gz
    ├── 92a1c9c7797fa0ed39a43fbf521e4adcd7f51772.nq.gz
    ├── 92a1f9db2db961c3866356adc5623bdbcc52c628.nq.gz
    ├── 92afc5f11d9b7b9d613c1af801ea1a768f546685.nq.gz
    ├── 931556158e181d9b721f97cd798704d7a8bb61d9.nq.gz
    ├── 93431dc7e081debf30d56af96b6ab639d34e578a.nq.gz
    ├── 95dacb63b9b1508f6838eca41ab88fd9d43142de.nq.gz
    ├── 96cfc5ab58d725c9cc7a14abedd95cf4a5f177d8.nq.gz
    ├── 97000d16b1a7b7e02081642baca8ef2df7cf03f0.nq.gz
    ├── 992f2c3448a9ef28015a06084b729664e5749c85.nq.gz
    ├── 9989b71bb4ff5d6e14e4005b156b9897d411d6c1.nq.gz
    ├── 9a896bc062a01f458106042967defc8cf0d3ff56.nq.gz
    ├── 9df8843e70e0b4d043428d69d90b190f163801b6.nq.gz
    ├── 9e502cafdc058411912d4e33fef51fe4d23b4744.nq.gz
    ├── 9efafd46d904076b715e833fb38c2aa1ab44de49.nq.gz
    ├── 9fa3194ea7136ff9383d5232c1018f6a31a69984.nq.gz
    ├── a083cb0b71e10fa9df0b371de6a1879260206c71.nq.gz
    ├── a2195fbc021ac30ae4ac2cea21a982967ee2d282.nq.gz
    ├── a515641774780893decd078a28ea5ec167b868a3.nq.gz
    ├── a5740294ebd357c68e6a5adf445e1fb82d312b3e.nq.gz
    ├── ab3853cfacdcb7ba54dba31da6bb6b94925519c0.nq.gz
    ├── ac967bdee9520898a0aad6931acd64c6428829f7.nq.gz
    ├── ade06ed6090be6a2399c6d18b032898c7663c787.nq.gz
    ├── aeff536a91e073615deda312f1695f3cde945bea.nq.gz
    ├── af18a46ebdb8837234ac9578fa17fd68d8430a74.nq.gz
    ├── af6050357264b0a5713df0c154cef0b6f5804ca1.nq.gz
    ├── b05f4b3d1a24a7b25ff3bc6032252de52241fff6.nq.gz
    ├── b127e9f336fcff15d5eaf7e0b0ec0dbcac15d035.nq.gz
    ├── b16b5ebf70b3f1afa9bc40088c5c5a10bfc54772.nq.gz
    ├── b18ab4971348075b27ce4653a3e5b8b975df12dd.nq.gz
    ├── b29dd05f97cc38f9712adf87fdc393f514165a7a.nq.gz
    ├── b36f99d7051ec3f741458338b22ab0fd1939ef95.nq.gz
    ├── b38c9f26213c61cc7cdaaa0223c47f0ace2da2c0.nq.gz
    ├── b4c6c73481919dd6596dff6a8a16da9f93543f25.nq.gz
    ├── b597ce95a731e5a927539ea982e8c56bc8d6e570.nq.gz
    ├── b7a7c83c608f92efc6b7285f1b2f6896cafc1d55.nq.gz
    ├── b8b2e81b81ba1af13e95ed59bbf663831d2669bb.nq.gz
    ├── b9d0edfdf5643fabe2ea8d18f5c1c5ec89fb9b1a.nq.gz
    ├── bcbb169a783ee2cdbf5e20b2dacb8bbe23c3d9e5.nq.gz
    ├── bcf0e42e118d070acae91e5be70d2c7ec6b338ce.nq.gz
    ├── bd3721a4b3e0056384a5008f5c2d1e84d9f3a425.nq.gz
    ├── bd7e547cadcf89be52d5f8e364fe12faf4c63761.nq.gz
    └── c0164c236ff263adc18c1ed1fba8f8dd2afdf98e.nq.gz

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

[jupyterhub/mybinder.org-deploy](https://github.com/jupyterhub/mybinder.org-deploy)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
