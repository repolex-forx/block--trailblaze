# Repolex Knowledge Graph of block/trailblaze

RDF knowledge graph data for [block/trailblaze](https://github.com/block/trailblaze), parsed by [repolex](https://repolex.ai).

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
rlex download block/trailblaze
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1c42e5e1ed3dcd1482109fb68d1f292ddbc09ad6
│   │       ├── chunk-001.nq.gz
│   │       ├── chunk-002.nq.gz
│   │       └── chunk-003.nq.gz
│   └── repolex
│       └── 1c42e5e1ed3dcd1482109fb68d1f292ddbc09ad6
│           └── chunk-001.nq.gz
└── blob
    ├── 000403a625a71dd103041c879e09aadb1d2bc5f3.nq.gz
    ├── 001db55cb84c8eebe248b57f96d09178f65d597d.nq.gz
    ├── 001e5612a7b2e30f521b5130d7122ff88ffd3a3f.nq.gz
    ├── 0078b0889db1c84ab6a36c2cc12ad00d274d0511.nq.gz
    ├── 0099e5447f86fec8cf2fbd426658ad5012436e56.nq.gz
    ├── 00a6cc1d19fbde706abde75aff03714da6b4b227.nq.gz
    ├── 00c19015cc304544286a90b9ad1b7ab42289c809.nq.gz
    ├── 00c6e2a951880e62742256e15fc75b555b400dcb.nq.gz
    ├── 00cbaa10da52c5836012eb13c7132c95fa7c85ba.nq.gz
    ├── 00d02250226adc569e4480237095dd688fc510fc.nq.gz
    ├── 00d315675385896390e5125915b9071354d2d042.nq.gz
    ├── 00e4aa17201390853fe47f793cb71557ea5db1ab.nq.gz
    ├── 010aee3ee796f77e9aac5ebc85707754ca3cdd98.nq.gz
    ├── 01624fe434b5d35f1fcb2db3cd5c883ebe838ebb.nq.gz
    ├── 016d61fea820930f5e1116b994c0c806deb3c684.nq.gz
    ├── 0184052f72e2509d150acddb336b546357a6ff11.nq.gz
    ├── 0184d934f4b266518b977f5afb1fccd385537776.nq.gz
    ├── 01948be6b194477192e6f3bc7456650686e61e8c.nq.gz
    ├── 01adbc021211fc3235f84fd761aa617af3e881d9.nq.gz
    ├── 01cf25de392cbc1d33e8123134196ce7e492eb4d.nq.gz
    ├── 01d6b52426cd52c80563fae62b06129c985c2cd1.nq.gz
    ├── 020203abef5e7ba97a5f0ab55427accbc1923037.nq.gz
    ├── 0211a56b40d73e4ea84823780040fe1f8f914c50.nq.gz
    ├── 023ca5c5068fe081df718c6ae01a25a06d40e09f.nq.gz
    ├── 02523de8edf03a30391a140946fdba35c64c11dc.nq.gz
    ├── 025adcbb94a78019043f6b284972306c8db023ca.nq.gz
    ├── 027ecf2b90cc6292bd67572ae5d2c61470456261.nq.gz
    ├── 02823c13fef77d703daf8158ccf40ebc567a801d.nq.gz
    ├── 028d77bdf6b2d4bd2d61ee3538690eb082c5b048.nq.gz
    ├── 028f73ddbd436d049f298f06225e6786f2699ac0.nq.gz
    ├── 02ade6acf73c54aec890ae54e88ce771f3cc5d34.nq.gz
    ├── 02b98831b7189ae484705c978a6df80a481cfb3d.nq.gz
    ├── 030bcd5203bed43c83f750c045c1c438c9ef057f.nq.gz
    ├── 0316096a5674d04ecf1d1c35490e9ba88f0f2722.nq.gz
    ├── 03196c2820e272f56b416feaf22024457672fba7.nq.gz
    ├── 0319bd82893aca8f1640245d5501cf7a28986d84.nq.gz
    ├── 032ddceff53920279f1131898bee8a0c28ef2d5f.nq.gz
    ├── 0355cb8cf51919229d4ddedf13c2f4b2d4dc34ff.nq.gz
    ├── 03781fa8138214be5d621575ceac1efcd7eb3fc0.nq.gz
    ├── 039f6b9a057c1663cb461a7fee7b419ab4796207.nq.gz
    ├── 03a7fa1c365e7ae55043bce8b26a79ec15fee1a1.nq.gz
    ├── 03e775df0a9a11591b623976eee599c11b003718.nq.gz
    ├── 03f1ca6222adaaa64d8a97c5b8561d4297f47971.nq.gz
    ├── 042c82112feb0aabced65981fc905a69b1907a45.nq.gz
    ├── 046eee5699ee7020c48f5384a6d7f3bdcfa86606.nq.gz
    ├── 04741fa22d0398a7e83d0d8da7d018477d6900da.nq.gz
    ├── 04872790e856f7b7f23b248ad5f3451ec4e5b92d.nq.gz
    ├── 04a1a6b0fbeff069d94c41705703abbf57d77bcf.nq.gz
    ├── 04bd01f336942572ecd865f3aa2638c04c347e9f.nq.gz
    ├── 04d0e672b824d5d0e0eca8aeb32984bfed924251.nq.gz
    ├── 04ec81dbf2fb730155df2a9de54766dad0819a99.nq.gz
    ├── 04edc8e73d66bec23eb426838b5f0e9ca6ddbc7c.nq.gz
    ├── 04f45eb3ffc7732cf930717db75867cba42c024e.nq.gz
    ├── 0507b1ec78edf8a9867176e417813b061d7cb00b.nq.gz
    ├── 0512ce83d4efd5c2901d5386e88bb32757151f29.nq.gz
    ├── 0513eb5049bcea4a4fd5169aadb3a01947ee277f.nq.gz
    ├── 051e59c1c4b8ae3959f02feb153e5fe2c2e51b44.nq.gz
    ├── 052a505d2f51dd7235f9883e746b3cb6ac0bd373.nq.gz
    ├── 055651b79fc01b70894659c7b0b71733a01f8f5c.nq.gz
    ├── 05657d681a2f67a6ed8918790ae706ca7fe96bdd.nq.gz
    ├── 058ba6fee6e57aff845f188043a785a400c5ae74.nq.gz
    ├── 05999d4fbb8593b404b06a7960abc27366d2431b.nq.gz
    ├── 05a8bb046c6f8f58572c187c318babbee0882f23.nq.gz
    ├── 05a9075d8ea250b29d4136c4d234458219066450.nq.gz
    ├── 05c261a1310f91e9cc58cbe9eb5be87b588fcf1e.nq.gz
    ├── 060152460396d533ac1ed0beb723e668531395f9.nq.gz
    ├── 06080f05ae61903beae0618bbd4de8f47ca8b7fd.nq.gz
    ├── 0613011974fd885d718d90f03815e367e3435cfe.nq.gz
    ├── 063140f2414f1dd740acebf1e496f1d992d12725.nq.gz
    ├── 063745c4b572890889f864287dc6739c11e3b095.nq.gz
    ├── 06397a65505b5309e9ce8fd97fc2e41e3b9bf558.nq.gz
    ├── 064a2341d4b52a35d94a76a6f19a88dee06a8d0a.nq.gz
    ├── 0663375b73de8bac29e413e1a400dd919894205e.nq.gz
    ├── 0665ff75d30b23c2de930043f8e446654fc3ad7a.nq.gz
    ├── 0666e742c5c29ae04ecbc6e3bca6cbdf542f6930.nq.gz
    ├── 067de89e5bcfa76fbeafd15b4ebb7ca497aa5a2d.nq.gz
    ├── 06af08e7b06a95f786a995ccb0052f9acea0a310.nq.gz
    ├── 06d5d004e32f636fbde76d6a1bc266efb8ad49b6.nq.gz
    ├── 06e883c8634825fc877eef741e411f8c97c082ad.nq.gz
    ├── 06f33ff97077749bc4fc3f079e045b9374d6896f.nq.gz
    ├── 0726687e2175baab787c44201637e0d84e4c116b.nq.gz
    ├── 07285c981f085f1e78320c4155aef06c1c1913c0.nq.gz
    ├── 0736cc9a14ccf1e86e5ed4313e6db241eea3ff10.nq.gz
    ├── 0741ae66f92ffb7555a7285a9fd6e5d6098c2dc0.nq.gz
    ├── 075f4a5550cbdec99c0f7dc3712c498d994fb001.nq.gz
    ├── 076178bc8c548ece06ef1b4c2221f1ac9e387fae.nq.gz
    ├── 07628e4eaa40c64b92c91ba9d1db606e7d273405.nq.gz
    ├── 076bb485f21d1c60f7042c9b03f43cf8ed68d9b5.nq.gz
    ├── 07911e30c8f32458535ef6b28ece3666164ca947.nq.gz
    ├── 07ae3034c61c6b5df3a4f50b4647380c1d69ed1c.nq.gz
    ├── 07af0a13d9275da9662c92b0a2d1c36bb42a65bf.nq.gz
    ├── 07bbd9af8a7ac3fdc37ff7e1f42a4541a47d53de.nq.gz
    ├── 07bca3dbdc8090b5d90020dc637e446922212f36.nq.gz
    ├── 07c34692c06e9844b318b82ac1863c0e6b9d6c47.nq.gz
    ├── 07ca4ce045f401afa74068ff5fa8dd707dc3c856.nq.gz
    ├── 080b51d5b0867d8003f8b6bc0cfff4364a82c36b.nq.gz
    ├── 082163bb46419443b4714a7447fe6db1380c475d.nq.gz
    ├── 0828b30d3b35a171bda55ec39eb22213fe2b7909.nq.gz
    ├── 082ea35302b3d2213f33f0c47e93d61195428220.nq.gz
    ├── 08901502c4ace0d0e28c473dfa73d7c7eeb4faaa.nq.gz
    ├── 08a174994d019692b18d234b2823b802c8590b03.nq.gz
    ├── 08b9a11e313f8e15d497c5fe78aa218986aa8f63.nq.gz
    ├── 08bab079b95fa84f42025a3b3eb095abc87ab5c3.nq.gz
    ├── 08e16e060325cc22bac9d1fdbbab02ba79aaf172.nq.gz
    ├── 09031403d063906c3467c0e9a9a196300291b4d6.nq.gz
    ├── 09092c73f288b9c71cb697a2dbdddaa9c5043135.nq.gz
    ├── 0912399f4cc0839f606218ba62067b9ffcd68ef6.nq.gz
    ├── 091be0d63a92202f3579276ae1ca72dbaf0b3d37.nq.gz
    ├── 091d24f1ff12b5ec89df24977377395cf4f32e21.nq.gz
    ├── 094939e4d39d3be318a1e8f3083438907bcf02c8.nq.gz
    ├── 097b70bdad11bca3d8a1fc54b546ef524d8f4d7c.nq.gz
    ├── 0989e1ff1fdf6b28b897858551bbc3bca6a09be9.nq.gz
    ├── 098b420e07badf942c773cd87120d434c6ef2f8c.nq.gz
    ├── 098baf3daac86bdfe161ff75de3ebe237c2f0dcf.nq.gz
    ├── 098c50db5809a617d1263219f1ebae545dcb2641.nq.gz
    ├── 098ebe52f8ead604283775ef93f8d7269e543bc3.nq.gz
    ├── 0996dd2f9e5de96a880458a2f4fc55691fe6e753.nq.gz
    ├── 09973f7384c1e867b9810602f434aa1d9869c4ab.nq.gz
    ├── 09a790749dd3dcaa1ff062308a833f6965c50f3f.nq.gz
    ├── 09af9610888e5e99782f84a21b21277ae489e029.nq.gz
    ├── 09afe680523cfd400ec31976663420e3b863cdb2.nq.gz
    ├── 09b99487f398b8e13226e1821e2d8da03da52acb.nq.gz
    ├── 09cc088873d28ab593d09b62115ff1a260d393d3.nq.gz
    ├── 09e1d16535909aba38ff79d3c8ed97c0163c1b49.nq.gz
    ├── 09f708aa9d600cf8a96de2a1b449d4f864294ebc.nq.gz
    ├── 0a0ce7c1ea7754e65a4e8cb03a020b07ac7fbfad.nq.gz
    ├── 0a1042c05bd8cf7c8607e562b857302756adb8b6.nq.gz
    ├── 0a22d14d1955320cce58feadb6c5f503bae068a3.nq.gz
    ├── 0a28aa421812cd4f9c2de07e6f4912242fb6bc32.nq.gz
    ├── 0a2aa44f25c74c805a3f519ef413710216436ce0.nq.gz
    ├── 0a38302097d9ec16b723b9a6d0c356b4c9fbe811.nq.gz
    ├── 0a4e19ee2f6f9fff19edc74c884b61285690caf1.nq.gz
    ├── 0a96d16d1456645bf1fab6abef2ed3b287783ddc.nq.gz
    ├── 0a976a6a63dd0ec3875c345edc52bb646779ec25.nq.gz
    ├── 0aa77e7dbba65a7f9077b1990d13ff2638fd6ffa.nq.gz
    ├── 0ad1b5c719a6d9ee20697d43babebe5cec3b982a.nq.gz
    ├── 0ad52cdcddb23142feeac4a6e68bb35b3e05f595.nq.gz
    ├── 0af583bdaaf16248f647cc1679e07254320679df.nq.gz
    ├── 0af83442b652e22a26836508cc3bfe78bc217fac.nq.gz
    ├── 0b0bf4c7a259661e89ea1c2b020f36e8c1dc3b41.nq.gz
    ├── 0b468052e7037e82476b8ef4d74f30bd1f8d5c53.nq.gz
    ├── 0b502154393af28d759df52cd50821461d39bd6f.nq.gz
    ├── 0b51bc23ce8b2a13972cc141ceec38cc8917bf8b.nq.gz
    ├── 0b62aad313e2897452b85680913e4a3f1461e81f.nq.gz
    ├── 0b65f18c4ba0b43093cb765b070510f4fcf5c487.nq.gz
    ├── 0b741b3b1510bf33baabb464f324ec7db74ee42a.nq.gz
    ├── 0b7acf086fe0db63629446bf76caebe54a437a5e.nq.gz
    ├── 0b7ca9570327af80a8492955dbccb7c3755c0e6b.nq.gz
    ├── 0b86239b42e772bf2398bccccaac91211a7ecd3f.nq.gz
    ├── 0b963a9b96ea94271b10e134134b3333bbcf4590.nq.gz
    ├── 0b9b9fbfa62268b1b34dc049aea0590699e3c6a5.nq.gz
    ├── 0b9e0159ac1f9d721f8bcc2717d4adbf6d45a0f5.nq.gz
    ├── 0ba5275fdeadcfd52b2e32092e433c025373aade.nq.gz
    ├── 0bb1ec766dd376604c874f30ca1811351169097b.nq.gz
    ├── 0bbaafb574831bf7bb11981397e1a08062b9ed6c.nq.gz
    ├── 0be7e6cf082fc7c77d2d8797f2c4a5db58a26c48.nq.gz
    ├── 0be962a57037afca60f6634dcd7b882d1f451b5d.nq.gz
    ├── 0bf5babd89c2f2e221fe538fc04c7faf62d321eb.nq.gz
    ├── 0c4ecbfc1f36fa7a50a21ad8f86f6d7c5d45606c.nq.gz
    ├── 0c559d878b81c61a81f5418106864dbb3ae5a793.nq.gz
    ├── 0c8140f21c56e4655a42c639844976c336ae205a.nq.gz
    ├── 0c8cae5b6de2b0c1d7c9a84d541d1e6cee9c83b9.nq.gz
    ├── 0c949a8553866451432fd4ffaeef19c1915b2b60.nq.gz
    ├── 0c97f17b53f94987f31031e54816b80f37b3fdea.nq.gz
    ├── 0cb05740112e4532606dd78369127f19fe4fd736.nq.gz
    ├── 0cbe981eacc8c9abc055a8487afb255327ce775d.nq.gz
    ├── 0cd55964822db7e6bc670a80b04f36ec7ade65f6.nq.gz
    ├── 0ce012acb602fe5eef9ea121a470bb47cf886dec.nq.gz
    ├── 0ceb34d8be9974dfbc650c276f37c216be1ca7b3.nq.gz
    ├── 0cf8e9c8396b48875ae99b09974f9a954f4b9d00.nq.gz
    ├── 0d4299029b116e273c4731f673aedd81d640961a.nq.gz
    ├── 0d71175a4775e4d85618be0cb9657ef22847a396.nq.gz
    ├── 0d82d01d2b23c646f3c37e9b3648a6c9f2fa1bcf.nq.gz
    ├── 0da90b079afe3fc10704da56393e260aa995652a.nq.gz
    ├── 0db684109f576db349f1eda0e1c3b414b761b9d4.nq.gz
    ├── 0db6f5db61aee1834ab8e59a2103fb2b1d68ba63.nq.gz
    ├── 0dc0bc6ccd78dc8dec1c45e06d7aeb459f01d0ed.nq.gz
    ├── 0dc16b8eb1e2e4f615bd2166bdd2e78308f7e14b.nq.gz
    ├── 0dd39468d7bf4c45ba411cc7e2b9c558a2a8c9ed.nq.gz
    ├── 0df4b278e210c9050c89a919f161ada359ae3e86.nq.gz
    ├── 0e132cbcee3f85d75110c5d26df541912bfa6491.nq.gz
    ├── 0e1ad239675a6ba0590f116bca0b5607ed20e370.nq.gz
    ├── 0e50551980675d5178ff2b20b2321a92988715a3.nq.gz
    ├── 0e79173607396a5ff71b913b526d1fbba6197fc0.nq.gz
    ├── 0e818c1e4bd8a5b2dae1661b359bdefef92523c1.nq.gz
    ├── 0e837682a0e404a2f6c5ac98d21c779d158fb8db.nq.gz
    ├── 0e850c741ad09c95b39a267d6529c1ed87f8e49b.nq.gz
    ├── 0e9a5ad9279e46cbd7e7c7dc7f6efd259ab144a5.nq.gz
    ├── 0ea9960e2f533f59146a0d7a23ce85591c0e1087.nq.gz
    ├── 0eb4503428e746008eab486f83efab219c141e47.nq.gz
    ├── 0f0d00d267e0e75566d2f4f1343787f2bd5b133f.nq.gz
    ├── 0f115239862bbe02655aa74341f350a6b05453a5.nq.gz
    ├── 0f13a70996b746f45940317c334e9a4a18999976.nq.gz
    ├── 0f1f995c5a1532f746c49eb590f428533c3ec0a9.nq.gz
    ├── 0f37b167e863e0f6ad680b1bafd737137c3be4af.nq.gz
    └── 0f4cb6cdb2b7da910aa07f1892811aa61414f531.nq.gz

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

[block/trailblaze](https://github.com/block/trailblaze)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
