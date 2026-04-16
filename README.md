# Repolex Knowledge Graph of redis/redis-py

RDF knowledge graph data for [redis/redis-py](https://github.com/redis/redis-py), parsed by [repolex](https://repolex.ai).

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
lexq download redis/redis-py
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b72f24ad6a2226d46aed770e18094a86117d2217
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b72f24ad6a2226d46aed770e18094a86117d2217.nq.gz
│   └── repolex
│       └── b72f24ad6a2226d46aed770e18094a86117d2217
│           └── chunk-001.nq.gz
└── blob
    ├── 00da54791fbb622a93375dae63c98c34bdce2c56.nq.gz
    ├── 0106936daec6a91bee57ca0ce943fa949d86cc39.nq.gz
    ├── 01ec616a5e693fcb03aaa296c75466fce8a02103.nq.gz
    ├── 0205e0c3443cf788135f20fb17c474a5ccfb3092.nq.gz
    ├── 02091b87a496040c35b1f62829a7b933231ec5d1.nq.gz
    ├── 0288496e6f1c6f7675db2acbd7fa5206d381aced.nq.gz
    ├── 036d7b257ea6e2c5e4804074d7e67a216e000b68.nq.gz
    ├── 04fce61c76e8bc6f36eaa454fd63f66c2eccb40c.nq.gz
    ├── 056bf555159e23798834bb921e7db85475488ebb.nq.gz
    ├── 0571e223adf6e643c2b2c61717eca5a60dc1aaa4.nq.gz
    ├── 05c2c8208156f0d29d8f155e8a6f112f4fb50747.nq.gz
    ├── 0600219e1c31170293691ba346224e3c0b3ff10f.nq.gz
    ├── 06d0387418113adc16580909830c2b009a4b11bc.nq.gz
    ├── 0773184a03c561ecf63187c119e17ff973a050e3.nq.gz
    ├── 078844f7aaa8f5a648d3f129b0e69692a88f63cb.nq.gz
    ├── 07914fff12de3b89a932b559581692251d89b5bd.nq.gz
    ├── 0911466e5875497c982c9b38d7250fb5ef7472f5.nq.gz
    ├── 0951d95641f9f19f3ef53a66dc2a2b09e0430c5d.nq.gz
    ├── 0a491276ffe5b478d469106cad30f73b20810256.nq.gz
    ├── 0a885055572a9b9260b496fd632c3251889032ea.nq.gz
    ├── 0a920cc55bb2f8424092ab0046f54be0343c9035.nq.gz
    ├── 0ab5a4908306645c28aa204d06955b3720b7ae18.nq.gz
    ├── 0caab04e78e7148604f7f00a15db579ee2758247.nq.gz
    ├── 0d128bbedb14fd2e6f4c7622444563b580f16832.nq.gz
    ├── 0dd7dea866d4c06b2328cb2904c2476a1c818cc9.nq.gz
    ├── 0e0e74d64e798ecb0562e18faa77d4c50672984f.nq.gz
    ├── 0e717b31d60ee0ca890a2e5e66f62a939266835c.nq.gz
    ├── 0f2e318022994070ee9e36c65c83e0b7ac489f30.nq.gz
    ├── 0fcb256cfb3cdd0867e8fca8776f766fed45c6f5.nq.gz
    ├── 0ffeb7f66e36413c572bd4dee2e2ad3264eabb52.nq.gz
    ├── 10db91dd28e94d6eb9e7dcab60ed4102654b9287.nq.gz
    ├── 111da8eb08bef4b26d15e94560c191b7dabb74f2.nq.gz
    ├── 11440c7af394f70c4a2118e6ca3a673d9502f301.nq.gz
    ├── 1154fc040d45f8577a098e74f6c674f2601ee94d.nq.gz
    ├── 11ab8af716e2daf206b508e303a9476ed92d98af.nq.gz
    ├── 11e66a1f7c888103a3de04e4b605743f780b0ca2.nq.gz
    ├── 12ed6562777e9db85105d32a026a55a4d751ee80.nq.gz
    ├── 130cd293a13f57f3c24bfb2e68c40265eb28a0f7.nq.gz
    ├── 15dfd7122952f4903bf88a8b544ff2c2f76df6bd.nq.gz
    ├── 16ac75b2bbb308a5ef22121df853f428ca40c530.nq.gz
    ├── 1752a4a94b2595d44557b7ad1d585b79654df6b3.nq.gz
    ├── 17bce6d56cb2cb8d0813a6b79ea98e7851e8223b.nq.gz
    ├── 17dd52b5df5149de5e6888b438f99a57833bf6d6.nq.gz
    ├── 191600d7c683d9503b000faf84f0527412c50ee7.nq.gz
    ├── 19288267d3dbffea79fc4d7ba845294f92952d4e.nq.gz
    ├── 1a876c165575f4f78e4f46a9915d9cf6b138a568.nq.gz
    ├── 1af2323fe99c8e58d17ea917320fa2c14b70ad12.nq.gz
    ├── 1c4f0f804a982c96e3e0fb92fde7f0b25a2dd59a.nq.gz
    ├── 1ca212c09f7e61a0f5445e13b0fcf168511f7f98.nq.gz
    ├── 1dee1e9b8954f68ea30833ee6b5a9a840ecde3ce.nq.gz
    ├── 1e1c23c87efc0a05328ce99a30d8fc3b8b4a3d75.nq.gz
    ├── 1f239546c15daf50f9bda279be6d349a70b02974.nq.gz
    ├── 1f613aff5ff567007c4e8310520517268622eaad.nq.gz
    ├── 1f904e076b5c77c538dd775fcb66a7569f00a7f6.nq.gz
    ├── 1fdc88af9091c3b8780baa684d99c504419bbf75.nq.gz
    ├── 213280140c1e6f0dc7ae159c091aef33a52f136f.nq.gz
    ├── 217face01b8915439969bfc6bad163f9012db387.nq.gz
    ├── 2281629ca8624eb2a9bfde1203232bec6d1c5215.nq.gz
    ├── 23551be27f8bc05e2a89812b89f6533bf1c7850a.nq.gz
    ├── 2669c7f633439cf72747340629629f93840fab64.nq.gz
    ├── 26bcd0e0d5151cf564b0777245056d8d0b9240b6.nq.gz
    ├── 2735f9d2cb32f38ff5fffffe86f3923627ca5626.nq.gz
    ├── 279bda9605b6ef6b1f4604f5d65f72214fb1ba56.nq.gz
    ├── 281d7f0a0b1148beb3a1811f407054b48ab7ad2d.nq.gz
    ├── 283c3b723a1072fd21a0caf365f3af9ce43b748b.nq.gz
    ├── 28fe758619ad18110c56db8582dbb6e4e5ed0d4e.nq.gz
    ├── 295aa21e42f414d6ea0cefd3c422d90c14e38de6.nq.gz
    ├── 29c5c18767a9ee802d333638991c43de9e58f735.nq.gz
    ├── 29cd529e4defee72a1eb00105b05d8d703025b34.nq.gz
    ├── 2bd1c0cafa0562fad7178ed4c8cb7170af39fe21.nq.gz
    ├── 2bd6d4ea70e87835b6ecf936cbd4d3acf4dfcec6.nq.gz
    ├── 2ffd8c78a6c1ad1d7fcd63ee782fdd3c0f49f15c.nq.gz
    ├── 309b229f481a5fdbae0d2263c2fd2d2be04bbfc2.nq.gz
    ├── 30cb1cd5b9e8c01c437bb745f23801c2c6a70085.nq.gz
    ├── 3156313da6e49cc6b81a68d3ba97789557296d7c.nq.gz
    ├── 31f781f773b83a5d817bbf33125d1c8686f5bdde.nq.gz
    ├── 326495b775bb3aac5a8e3667ddabcc9724938ae5.nq.gz
    ├── 32c6e39f38832eedb7c6252480682a22957011b5.nq.gz
    ├── 3310c1f70df4d729232a07db6d97273d1bd55412.nq.gz
    ├── 3365dc9fce02c6e3f47d7f4302729140a645d152.nq.gz
    ├── 345dc306120cfbf6811baec1e3e62080b4a29f00.nq.gz
    ├── 3545ab44c24f506389cc88a7ea42b6d750ebc840.nq.gz
    ├── 35fd9e0e33c29bb89d0c75ce11e5b834e181fd9a.nq.gz
    ├── 3673d19310366d707e044bf1d2dd9649378a2467.nq.gz
    ├── 367700547fd0eda04af8352225e4f00d57b071cf.nq.gz
    ├── 37ffa97812e404a72e28289a71357c04a6dbbbad.nq.gz
    ├── 381dfc1c21a3fa0544d6cc6b42fd70024c8760b7.nq.gz
    ├── 3991a8b35b841eb7ea090127466d87c71d228e63.nq.gz
    ├── 399c8a0ddadad3633629e757cfd965667f88f711.nq.gz
    ├── 39d516242f5d5566f2914a79a3b7ac035d905946.nq.gz
    ├── 3c2161542f10f2e94b4777f799aa7c150f9c88cb.nq.gz
    ├── 3c28b9ee16644a7cdbc0c0d6aaff60f6f90fd928.nq.gz
    ├── 3d6d81465e3477f4020e4d892c020f12b75913c9.nq.gz
    ├── 3fbf82117203354736b2fda7bd10f1051b55b0b9.nq.gz
    ├── 3fcc7bc3ccfe2a0873f1120369af0eec863c3dcb.nq.gz
    ├── 3fe54a0d88256514db3bd39d054c2f7528c3f4cf.nq.gz
    ├── 3ff1320972f2a27c40378d7420b975fa0c6186ce.nq.gz
    ├── 404e396a18d992991fa5e834c770870a6211595b.nq.gz
    ├── 41f0c9d6c5ffe90cf8d4f194b1762ec6f92b7221.nq.gz
    ├── 4355d0ca034ab734a212ad960fd5b057e24889e6.nq.gz
    ├── 43dee3a7689c629626c752088b180b8bed60e965.nq.gz
    ├── 4461a80bfcdedb87472fefa4b52dc8d0cadbb6b8.nq.gz
    ├── 44717bf128f5c1250ae7d6fd9b7af367e829cbe0.nq.gz
    ├── 449ec0c50f0a1629cc954e48e5c42a078158fc83.nq.gz
    ├── 45ee3a2e26ca435d3bd506187f91c6c47f1dd5a5.nq.gz
    ├── 4607da071cce4f078094a0457c4e1924b760376c.nq.gz
    ├── 46a29ad35e8ec77c7999506275354446f12132e5.nq.gz
    ├── 47534ec248d6be6d02b7961bc42eaf53c3ca8f4d.nq.gz
    ├── 4767aa134a7c15dc824eb307f5f3ed2d246c659e.nq.gz
    ├── 47f383f3ef7b1188043dffc782752fbb52b7657b.nq.gz
    ├── 47fdbdf41de1d27a1216d018c36f3481fe610dc4.nq.gz
    ├── 499c8d917eec527af45740ccdb0351b0ea7ab9c4.nq.gz
    ├── 4a4e09f8f8225f9282424615c9c3c848519ece85.nq.gz
    ├── 4a57591f04b494764f7245a2ee13b05bbca1d163.nq.gz
    ├── 4c1fcc16a551b2fa377a3ef74e3fcf96140433c1.nq.gz
    ├── 4cb39f8fc884e7bfd964dacfb8ed6499120aa041.nq.gz
    ├── 4cffa716d8ef2e24ced9a9f3b54547cd18dadaa7.nq.gz
    ├── 4d35e61adec0fbd741e43a6424f413118cd087b5.nq.gz
    ├── 4d81ddbcdadc3d1520af1e5a4eeb05b5b300f654.nq.gz
    ├── 4dc633c1a65e96bd5d4b69befce21bdfcb37b60c.nq.gz
    ├── 4fb71964222e7b247ac761640c19f634daf9e7c9.nq.gz
    ├── 4fbc02c5fe6e8ff56d9b49f21e0f98f46f481e6b.nq.gz
    ├── 51360639eedf5f46a1759030505de507391945c2.nq.gz
    ├── 529c3ccdee577abd4c07431dbb1581fa128d6890.nq.gz
    ├── 55f011402e9d28f2d4af625fcdd46d23c4f7a3e7.nq.gz
    ├── 566ec6b4d3ee035fdf0a02c46fc030f059f572d6.nq.gz
    ├── 5857b14166dbcf85f6a0114706a98e4a0b992e6f.nq.gz
    ├── 590f238370658926e1ab1b6577fb642359abdf15.nq.gz
    ├── 59c74aa93d612607da7dfbe3fba3247bb6fe1c79.nq.gz
    ├── 5a511b279319334c089aab063d03fba4520aa5cb.nq.gz
    ├── 5b15c09268d4d9c28cf1038a6661767463f293b4.nq.gz
    ├── 5b17cffe3ae495227a12889fcee7088ce75540e3.nq.gz
    ├── 5b9202111e0092bb8e9e8e28a806dd356db608f1.nq.gz
    ├── 5dc1cf16319e6e9394ae03bdf5311e7ec5e168bf.nq.gz
    ├── 5e34ec8866a3ebce38551c37948ea4dbe79423c8.nq.gz
    ├── 5ef2edcd5cd82abf0100c3b55ed325b95bfc1a72.nq.gz
    ├── 5ffeb97e06c10b08654aa5d353eb550674229c2b.nq.gz
    ├── 60b231ab40f28410bc1900ef9f6d42a29f031e84.nq.gz
    ├── 60f4ddd3d327bf1bf18e4a9c7ee6a52cee000a8d.nq.gz
    ├── 61124ac79b36326fd5087a8babe771fa76f83383.nq.gz
    ├── 61ad1eba515bb01ba7d65cd23ed1e9cb28c54a4c.nq.gz
    ├── 6206fa2a5c90e6b0efb7e48480d560d6440290df.nq.gz
    ├── 62703af2426ab4e172499be518a11b9adbb72b6b.nq.gz
    ├── 6271adc46d2b38d410e4e6de025d6b7b674d14ed.nq.gz
    ├── 6272cdab252908120118241292198b2224e6dd0e.nq.gz
    ├── 62e8665d1fb9d19a6a061f7157856c587afd6b29.nq.gz
    ├── 633134a1b618ef5cc9171a61703b082207736f5b.nq.gz
    ├── 63889a4b06f914ad70fcf4d667d1de7787e2c66c.nq.gz
    ├── 65966ff9346c2fc3e77ff631841207d3f7f84038.nq.gz
    ├── 65bbd52d6033be7972e12e341e279f077fcdf0ea.nq.gz
    ├── 6689622d659453353e9fa0fe4eefab5419a544c9.nq.gz
    ├── 6695abfe4bc6ef198bc7db272ff0a8d69662245d.nq.gz
    ├── 66cd6b320daa58984956b19993b41a0b9d7f7b8c.nq.gz
    ├── 674afc492a1124000744604a40a45cfc680fa5ce.nq.gz
    ├── 677e165fc6d924e5e40e8d57194cfef051b2e4ca.nq.gz
    ├── 687ad9059352841e17632ae97cfa1dfc4aef97f9.nq.gz
    ├── 688b33b2e3805914b17e2b3eecf7dbdaa9953c0b.nq.gz
    ├── 691e13350a1d014619a378834b502f41d4997408.nq.gz
    ├── 6a5b289ff1e8a1f54b3c11a779d353cc161eef31.nq.gz
    ├── 6a90d55cc64a15f9386c548dfb5199eed0d25d4d.nq.gz
    ├── 6ad2b6acb2e8dad297fb71c56ace691166f8772f.nq.gz
    ├── 6d71ccd0e74fb051197bbeb67c11cafeaf031989.nq.gz
    ├── 6e1f68a7ba2d8478efb7a612a06e17165e341a4c.nq.gz
    ├── 6e59454ed32762e2a5b68d64d02ad85a7df60e49.nq.gz
    ├── 6fdf0ad88263c9e83c8a29cdcb7be1276d1ccd5a.nq.gz
    ├── 6fe5f7cd5ba17822bb88b932e22366f94da7724a.nq.gz
    ├── 7282ee3d24fc7cc11b00d14bfbc974ed454d39d7.nq.gz
    ├── 72cdab9e38514fbab11e30d58c0f195ce033b527.nq.gz
    ├── 7323c143923a659b12bdeb61de499745b5e6166c.nq.gz
    ├── 738d65a29c37279341a9b75171acc7a1f936b65c.nq.gz
    ├── 73ee3cf8114a22591eba34da14923e093fc7c9ba.nq.gz
    ├── 743dab18fee6b92027272fe562f42cf1b665742d.nq.gz
    ├── 74a9f28b2d040cc22918cf1c0600514628b7c016.nq.gz
    ├── 76c8207a875ece2763ce1adfe84d0222e5890d8f.nq.gz
    ├── 76fa72ad4c6d063706f7cf91463f49a670359061.nq.gz
    ├── 7795926a735efabcb7d1832b1b872bbc13e4c83f.nq.gz
    ├── 784e1f22d4cf18d78f52ac6471b803980ec25647.nq.gz
    ├── 792b8d6668645af56d7b30d21bad766d1a535a66.nq.gz
    ├── 79420b6e7fd0014c31932bffe590aea56adedded.nq.gz
    ├── 7c2beb4d6444a954184d6847bebd586339683f3d.nq.gz
    ├── 7d030395b9d37187ca1927392ecf53c511531515.nq.gz
    ├── 7d0f2cb7005bbcfc0a564c3b46fb6f491f3be72c.nq.gz
    ├── 7d4cc41b8910fec4c14bf1e52ac7a246d5654439.nq.gz
    ├── 7d9d5c4ad45926446c37a1e174133abd2a62f2cd.nq.gz
    ├── 7ec1ebb16cbfe44f7749f16df07b42db0c58e293.nq.gz
    ├── 7fcb020681d1dc8db96ebdb96355fffd4821636d.nq.gz
    ├── 817a5287655edfe4e4ad425909e4d40bab6596fd.nq.gz
    ├── 81a495c853d276ee3383a9000977b166677bc639.nq.gz
    ├── 828b3f2a430679026e0035728b0c80c7d07ee153.nq.gz
    ├── 84fd2e0e0554b9c03158870867acd0657f98dd28.nq.gz
    ├── 8509ccd678eea721e68a9c75139554e5d3aec8cf.nq.gz
    ├── 852fd4aaa6e6130ea65e4f4504fbffbb096d01d1.nq.gz
    ├── 85978497eb99ed8f5b4158e963aba57d002c5d42.nq.gz
    ├── 861e3ef003886edf82702b1a8b04c3e79505fd64.nq.gz
    ├── 865bd522a2004933ae5e59050015efb3a187d86f.nq.gz
    ├── 86d93b8f8abf3bed0648db2d22ab5e93b945653f.nq.gz
    └── 87532ae5d52b5ed6d98ee625fb5a987efbcc0c0b.nq.gz

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

[redis/redis-py](https://github.com/redis/redis-py)

---
*Parsed on 2026-04-16 by [repolex](https://repolex.ai)*
