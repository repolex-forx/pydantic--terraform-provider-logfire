# Repolex Knowledge Graph of pydantic/terraform-provider-logfire

RDF knowledge graph data for [pydantic/terraform-provider-logfire](https://github.com/pydantic/terraform-provider-logfire), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/terraform-provider-logfire
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f25d5569942b9d4beebe1400b64af39a0e2353f4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f25d5569942b9d4beebe1400b64af39a0e2353f4
│           └── chunk-001.nq.gz
├── blob
│   ├── 01f0eb72e361342a435df9e7c8eec19fe44cc821.nq.gz
│   ├── 0200d62d7b50a7684cbfd1031bd7a2eda20e179b.nq.gz
│   ├── 05b9788d8db5cc2efa74d48967636770b4c52a8c.nq.gz
│   ├── 060b50d534e8c4b6563d0197053315e0b35ae200.nq.gz
│   ├── 06cce0eb3d2d12e629835627aed8a43a32c8bc32.nq.gz
│   ├── 0744ae3cb0c7fcc0b69a64e3c6a77338291da38d.nq.gz
│   ├── 0796840588e780890437b0aab5661b81e4f73c84.nq.gz
│   ├── 09a28aa3147fcb3d1d7e1a3a2c945258d14840e9.nq.gz
│   ├── 0a1eb454fde3faed9615effa7d92645902013858.nq.gz
│   ├── 0ac4eba71dd0f504f46b4c3b980fe0f0c3cde397.nq.gz
│   ├── 0ae7940459bbd1652dd48561134399a0dd6d8984.nq.gz
│   ├── 0f7aa4b77c8fb8414b9523cb1991953e5429cdf2.nq.gz
│   ├── 0fa3d62cb4fdea17eab0bc3da7e96c69d20dbe25.nq.gz
│   ├── 1038a1e2596b4190b2b58c6eb6a2c01ba410580c.nq.gz
│   ├── 106df03e554052c83edb1233b1be27686d79fe2a.nq.gz
│   ├── 10b0652d44f5edcaac329b52cbc6266abf39b468.nq.gz
│   ├── 13fc37367cb7eacfd4fa4eb0ed8b9e956ab5d3f5.nq.gz
│   ├── 15cb708c757188676e26507808ecd3ac7be02615.nq.gz
│   ├── 167f04d24bf59b8945655ed0b49592c822fde9de.nq.gz
│   ├── 16f2dfa87eb6bd36b63e41944116731b16c4d679.nq.gz
│   ├── 172bc9984bf7bead813156eb4b3c1f0ab9b979c2.nq.gz
│   ├── 17a93da096ed08bf823479df054206653520d698.nq.gz
│   ├── 1850b44630dc3a217bea487f1d8c53cbb3162ae9.nq.gz
│   ├── 1de7957a7f179b00a23a910767149ed6ec94a3d1.nq.gz
│   ├── 1e01ad608e631700aedb9b3b576dd1ccc550b966.nq.gz
│   ├── 1ee88c5686bc326f883a2cd5d55c4e5f7509930f.nq.gz
│   ├── 20568fff41efd72945995033a51b915260bdf9e1.nq.gz
│   ├── 211666fef512ea2e22b63fea767329a4a43efaff.nq.gz
│   ├── 212de227bd174d4c728551415954b7334d48e410.nq.gz
│   ├── 23f9374b25d9874bec801cecc3cb80f84efab103.nq.gz
│   ├── 25720dc8c343d01af7ec8b8e6da0a993da66f1da.nq.gz
│   ├── 2915f81597fdf7a839aab75089b0add214c7558c.nq.gz
│   ├── 2e75afaa91df1db8100529df144d5a8935e31859.nq.gz
│   ├── 2e84fcb79b8785d46cc7f8b60e601623af72c9d5.nq.gz
│   ├── 2ec0a15db117b31207581e9a88ae3d328543e0ed.nq.gz
│   ├── 34db206cb820f5a4e54c7e74ca138d2c9e667df1.nq.gz
│   ├── 35fde678c78fe687b4c126cbf78d5c181fb4a334.nq.gz
│   ├── 364a4ef8398fe363fd289c4f8c46470fb65e0946.nq.gz
│   ├── 36c2a0604dbd8e63b714c9faa7a697726b94951e.nq.gz
│   ├── 374bf7df7433eadbff6379cd3b90852f6ed0e95d.nq.gz
│   ├── 38e8ce7128087d3342108f33c43881ac1fb2299b.nq.gz
│   ├── 3a3b24e9245deb33097bde5f0903aa1d822898cb.nq.gz
│   ├── 3b6d3326a6ac56afabe745a6026dc8618900b5df.nq.gz
│   ├── 3d752ef82665b11aa0cb91cf4fae878417d8e73b.nq.gz
│   ├── 4022f00b7c83c5290a649eb68b25da8a4a4c7c5c.nq.gz
│   ├── 40503e8c2a40652fa5a443b1658d7cd541ece803.nq.gz
│   ├── 42f9f9ac6f1b710514f9d84d9baf2ed367a25e24.nq.gz
│   ├── 4a257682924df63f7f9985eaf94f66abefc2e820.nq.gz
│   ├── 4a591d5747bd80f0be6d4d4f804362891924a5c8.nq.gz
│   ├── 4c1387d6e79585d8a289f017dcb0d3a32912fa8f.nq.gz
│   ├── 4c83ee940deb1b21a963ca4e1dea40c987aedaba.nq.gz
│   ├── 5253050d8ab51d7614fc6244ae3c989d915dec60.nq.gz
│   ├── 52f7ec58fd215737171ca95adf72cfd539580d52.nq.gz
│   ├── 549c3bdff8c45aeb79beb944bacc76016c4bd7a1.nq.gz
│   ├── 551a4bc2cfe3447d94a8cbf2d651350609f77e7a.nq.gz
│   ├── 57beeb52a29da94b3475d89ffd0fea407d56227a.nq.gz
│   ├── 5a2d06997e64ecab4fb06a9fbf800710d2378df0.nq.gz
│   ├── 5d6dc7f316164dc9fe3dbd4dbbb6356fa9bc2ac7.nq.gz
│   ├── 5ef3b5bfa9d6031b0838204d6e82a946a8e6998c.nq.gz
│   ├── 5f4e43ff99f40f7f3758adcfa715b238e1e1b762.nq.gz
│   ├── 5f863a925a846eff51d856d67fb76ff0016ac9e9.nq.gz
│   ├── 6010cbda57ea692ab4695629f86ffe95f1aaa85f.nq.gz
│   ├── 6050022a6232cf84fe2354ccaa8bfa3226d96cbc.nq.gz
│   ├── 6054e2ac22ab35c73836f9847740d1b421141915.nq.gz
│   ├── 6171d34ca5b8b109bd47d448d05ff42aeadb2f5f.nq.gz
│   ├── 65577fdbeab6604537bc7c32b592961293c0c089.nq.gz
│   ├── 667520e6206dbcb88c6d9d6dc1ad2595af02445b.nq.gz
│   ├── 69cd0ec98ceb714403f622321c95792eeb9a4343.nq.gz
│   ├── 6dda22bfb7bcb6540c5490964c423a2f2f488a9c.nq.gz
│   ├── 6e8432083a82303413d5ac7b126db2cd68e19a0f.nq.gz
│   ├── 70ce68ab7059fd829b42a79b81f58328661c6ba7.nq.gz
│   ├── 71a34273972a6e6fa9c36b81ea04bd87286db52b.nq.gz
│   ├── 720660a79b91a3c0dcb94e2fc94bb08ce258c9b3.nq.gz
│   ├── 731e2492102a2a08d91cc760e465ad753e195649.nq.gz
│   ├── 76d367ef8aa530afff1007cec13611ac04f7c272.nq.gz
│   ├── 77979663a11c4a5bd2a598b890af7937b5ee778f.nq.gz
│   ├── 779d097510972614fc10ac65f50b9aa677fe394d.nq.gz
│   ├── 7800054370902f551332f41242cc3c0b60b00cf9.nq.gz
│   ├── 7a3d4557f427f677309c91193d847d43dce98a9a.nq.gz
│   ├── 7e82afea708c12a2fbbf3bc688a54c5deef6271e.nq.gz
│   ├── 7fc3c8df27d6302a6bcf51c682b2221b9bed5f38.nq.gz
│   ├── 7fe57b9597cbf6ae6fb1a50b4a0b65a962de5dd8.nq.gz
│   ├── 8013ccd99818c1589326447c1eb318d801521af0.nq.gz
│   ├── 844970a1591097c62f3429e3e0c4c96cf7f234bb.nq.gz
│   ├── 852049b54ae3a2aa3f0bc05983c0e00845f844c1.nq.gz
│   ├── 890583f241a22400f31560d965fa439bfbd5db72.nq.gz
│   ├── 8bf51cb5998f99f66d0482b082fb5cbd34dcd832.nq.gz
│   ├── 8ed76ab7687a3721ef57c5c80a075d9e7900c4cd.nq.gz
│   ├── 8f4e99e45f89bea8f21efed0177d51e4981ae80c.nq.gz
│   ├── 902d19c9817afb5e9694bd89b2b3948d6fa31fef.nq.gz
│   ├── 90dd263d9ce8dcf84135277b942362cbbc049e3e.nq.gz
│   ├── 919947a58424ed30ea17b5b55310cfa834c7cbb9.nq.gz
│   ├── 926fb7ea54649ace05acb57cb5b106794d99ee8b.nq.gz
│   ├── 9831590b54d511dca24a0463474e3a825ba9633a.nq.gz
│   ├── 9bcca496a4fddcdd39359861a62867a55cf23299.nq.gz
│   ├── 9c1a0590da936b063534cb4c3703a2c4a164016a.nq.gz
│   ├── a038cf921fefad47b1e5c20101ee21a0914ee2bf.nq.gz
│   ├── a068a871da79058390d53742b1b20e073e5b14ae.nq.gz
│   ├── a0f39f4008beace6673f9d7ebdff96f48d75743c.nq.gz
│   ├── a35397ce0d3cebe635299575159da4fce4e4f563.nq.gz
│   ├── a38ecbbbc5055001b7ee68f987ec9e5e97c4ffcc.nq.gz
│   ├── a69fa07d7b64f9d0420f353cc28575ed20f546b4.nq.gz
│   ├── a6dcb60aa31963b8856cd4d6546295b034c50946.nq.gz
│   ├── a71815074597281ee22b328055983fe9e90e703f.nq.gz
│   ├── a8feefb09dac21ba0b2d5961aef90b6fa0a24b7d.nq.gz
│   ├── af2e658083a9602f9b011fadf23f78e5f405d0cb.nq.gz
│   ├── af4ceca8caca00ddc139bb111ede3d778903bd67.nq.gz
│   ├── af7681f4d2e86c9ab35a2093a79ae264c81342be.nq.gz
│   ├── afef263418f7b68c2be7c9435e122bb1f57d008a.nq.gz
│   ├── b0c4c182c8dbea40e6234329f6e434f48986f704.nq.gz
│   ├── b1fa98709bd6a85c61c716d9af0e7f8e841ecd18.nq.gz
│   ├── b37c43b6897c33f65a0bd761dab2c0b6b933d942.nq.gz
│   ├── b47aeee15e06819cfe837be68f19c7491ba8ffa8.nq.gz
│   ├── b5521d4535d51dc35d23e52fc8889b58750a3818.nq.gz
│   ├── b69cfa757c34b0f79ce25fe37a0b1a653117b161.nq.gz
│   ├── b69dd1ceb1cc2ed8f6cd921b6caceaf705e7380d.nq.gz
│   ├── b70bec741a1d62ca182bede052677a74592c689a.nq.gz
│   ├── b9267608954da07a3883b9106058c563e6615f0b.nq.gz
│   ├── be1b2a7f17512aa307a84f0fca49a63817688061.nq.gz
│   ├── bedf382bd8ff8b222fe473ecc220d25fb98f09ab.nq.gz
│   ├── bf668351ec4fec0a4052877edf1209fadd7f18c1.nq.gz
│   ├── bfa93b0e8bf01e29d4892bc7cd4f4065b3c74df1.nq.gz
│   ├── c023b23d3e98b641b2a9355fb351d5c8c901c7be.nq.gz
│   ├── c1a4b5d281c2c0133f700bf74e1d5877b893315a.nq.gz
│   ├── c1f7fe17898a61d0a2784ec498d22f1d260e6da1.nq.gz
│   ├── c5a136b283357dde3f2a9b1c3676dcc2b2e04fba.nq.gz
│   ├── c85a8b925e32810facd8cf8d1fc770644828c76d.nq.gz
│   ├── ca9c7e7338cd7a30df36f59794738f535fd11f0f.nq.gz
│   ├── cfea84b489a2424a4fa8ff8370fa6da54436f185.nq.gz
│   ├── d3aaafb7b7668fc8ff05c87c36c96bda27b14919.nq.gz
│   ├── d411bc0616affad7fd6fe31f881022735d5051f8.nq.gz
│   ├── d55d9c815db473ac15efd790cc59d3689e413e06.nq.gz
│   ├── d5e35399dde3c2dd944e47c45f8e9ae472e3ac3e.nq.gz
│   ├── d6afcdbf41adb30626836b5f52c58a2f5d0ced67.nq.gz
│   ├── d8310109e99876fbaa3cecc376254a8b3239ed8e.nq.gz
│   ├── d8a02e3e63713f85b86d68bc22aa587a8c4fd58a.nq.gz
│   ├── d961af5ae7053e959ceb3736c756da74c3364edc.nq.gz
│   ├── d9ad1f583417bdfff550dd58fcdf0dd15171811d.nq.gz
│   ├── d9f560dd43a8f5c357b87419591e0d97ac0a15a1.nq.gz
│   ├── de38aabe96376cf401e6c0c7f81d13d8a9167a8e.nq.gz
│   ├── dea86fc5e61ef3305e41bb7c45701d1846ae5b38.nq.gz
│   ├── deb151e6033b6147bf02349d72b479c3b1e5519e.nq.gz
│   ├── e4b231406eec20088b09db2c95c2a0263f9dc389.nq.gz
│   ├── e5f0f413fe54830b59436573a80df543fbeafedc.nq.gz
│   ├── e9f754876669195f61d3dca251f0d711d0965fb6.nq.gz
│   ├── ea815915f57233ea3cc80fd60fb496f538fba3a5.nq.gz
│   ├── ec81a36debf29ccd2e4aa457cc46515b2b2a502c.nq.gz
│   ├── f14f5b92d24f4d052ba18969967479c24aeb7758.nq.gz
│   ├── f443e384dbe4402c988b9612d0535c35c130e68f.nq.gz
│   ├── f5e8006adf18b32fda36ceee9fdc6432dc28380a.nq.gz
│   ├── f7e4b5c9f9a7ab1bac84a4cabca84238c3c810c3.nq.gz
│   ├── fa5829fd84d916da9b3c748c37a43e0f5725ee2c.nq.gz
│   ├── fa95f7fbdc5ecd39f493bd6b54c57287ac598ccd.nq.gz
│   ├── fc714e33fced5e61fc1e3b9cd40d44b675bb587d.nq.gz
│   ├── fc98cb2e330441293e8c5463522995286342c670.nq.gz
│   ├── fd3ad8e1e197dc2e624f084fa0cebc77fcfcfbc8.nq.gz
│   ├── fe86aa32492b230471b22a247703c986169c06ba.nq.gz
│   └── fec2a5691e493a1941bd79b312b3925403a91aa6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f25d5569942b9d4beebe1400b64af39a0e2353f4.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 165 files
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

[pydantic/terraform-provider-logfire](https://github.com/pydantic/terraform-provider-logfire)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
