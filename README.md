# Repolex Knowledge Graph of kvesteri/sqlalchemy-utils

RDF knowledge graph data for [kvesteri/sqlalchemy-utils](https://github.com/kvesteri/sqlalchemy-utils), parsed by [repolex](https://repolex.ai).

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
lexq download kvesteri/sqlalchemy-utils
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ed0cc46f96d3065331ff34c0713da23ee90920a0
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ed0cc46f96d3065331ff34c0713da23ee90920a0.nq.gz
│   └── repolex
│       └── ed0cc46f96d3065331ff34c0713da23ee90920a0
│           └── chunk-001.nq.gz
└── blob
    ├── 023958e8d59b9cb448bcc0d9d54c973f709424eb.nq.gz
    ├── 024a297389e247a8741463e1afcba5c1e5e50c31.nq.gz
    ├── 05d77ebadf3dfefc2b85add58d996b94687edf06.nq.gz
    ├── 0692806cf0873bbfbc19788481e92e583cd3c43d.nq.gz
    ├── 0918379fe2676afb93a212e51b759447faeac539.nq.gz
    ├── 09428719c2828845c93fdfdf2037f0852ee30a2a.nq.gz
    ├── 09c7265294bfe9fb7a100c37e623181bbae4c579.nq.gz
    ├── 09fec332f54c33ad63ff5158dfa7bd8694c2ae46.nq.gz
    ├── 0a0de758df4cddeadf266d393e37dba438b7dd0e.nq.gz
    ├── 0c54a20217dd2499a25c2def354f2ada6dbcf771.nq.gz
    ├── 0cfbd8b4f5a8ad3ae9a4072daffcc04c3981896e.nq.gz
    ├── 0cfe26fcfcb1008516dc7e394910d07ff445f97c.nq.gz
    ├── 0e45ae3957097ecd413756024854c1eab0f2c1e8.nq.gz
    ├── 1108e556e4672597121aca4e88930ad328d5a41f.nq.gz
    ├── 1305a27ca3d0e237ab13c6d8d6f2a7ace0213605.nq.gz
    ├── 158d3fb9c705ea0ce1cf145570821ee65818b97f.nq.gz
    ├── 15ca181a83a85e9b6caef34e24a67656f2f38c5f.nq.gz
    ├── 17b68d23c00407a534fba731592dd9d5c25f824d.nq.gz
    ├── 1865f687d3510cf5868809cee65528c38c90d3c1.nq.gz
    ├── 1ae677523b2e7698334659fedf87d317ea01a110.nq.gz
    ├── 1ba93b03260e1f80b503ed734a43e683afc185e4.nq.gz
    ├── 1df8cb6a7d84654033993d55b94d87dd6aed6a20.nq.gz
    ├── 22f802920e5386653f3a639a5d9c744ad1a1c0aa.nq.gz
    ├── 2390d8c809eea1d6587357cdad25ed4af134db32.nq.gz
    ├── 23bd69dae12c2f571f069f5d8aff7eab8c87bfd8.nq.gz
    ├── 26eefbcaaab074ecb78d4c6da699f43fe079664b.nq.gz
    ├── 2710a5c9746518f2f6e78df540bb64ed516b7678.nq.gz
    ├── 275c138fbe5f7eccfe7d1684fe8dc1f1ab7570d8.nq.gz
    ├── 29008bb0e2ff53389621165236a428eba829daed.nq.gz
    ├── 2a97ef5efd34607c1b7182d35bc1468efc7b648b.nq.gz
    ├── 2d4f8e935f67260a23c4a7821cb773072947969b.nq.gz
    ├── 2d84f1425ba8ae6d650abec54cc1a2137e964775.nq.gz
    ├── 2d9402c0fec2e13381636ee066fddf0d12d3cbe5.nq.gz
    ├── 32911c67de58fa42ee6f3baad4c81ea1907cc1e3.nq.gz
    ├── 32e6edf83ccf0387672d3f2e79e2ea95d6f86851.nq.gz
    ├── 33666afcd60986522a294c98764fa8668bdea093.nq.gz
    ├── 337a2a012af27f5ffc8d0b95012a48ef20115f68.nq.gz
    ├── 33a12a931525e502dc39829a4e44dc8001c75c76.nq.gz
    ├── 34ef517b1d79ea501f44340e9ced1ca87c2b79b7.nq.gz
    ├── 353dff1ba1f0195bb1e9bf16c784e2f998a0d085.nq.gz
    ├── 3600aab10c4146597da8f60109de72ac626d46d0.nq.gz
    ├── 380a26b9e1f8a714aa3a2a59e70e2fa9cd32076e.nq.gz
    ├── 3914be8daaab740a61b73ec1a26e3e5d1e4423ff.nq.gz
    ├── 3993ab9e49ccc86e4f5fd9c507229d8039dba7e0.nq.gz
    ├── 39d98da43fb7fbcc9a1efed82025e001a6faf307.nq.gz
    ├── 3aebf6d7302161c51c82437728cc153f5797e4d6.nq.gz
    ├── 3c1b008e47c42fef913f5754b41023401665c5f4.nq.gz
    ├── 4088e60b4e3a3fd2766f88eb91542fbe328a48a2.nq.gz
    ├── 430795e9fc0b012e8b5d7c7b8feeca6bb2705e52.nq.gz
    ├── 460452da4851320b77c5638573b7ded1d5cc5b48.nq.gz
    ├── 47edd80ca42310287034e4cef33003296dae2d68.nq.gz
    ├── 48acf3a3d2a6ffe4be4cbfb40e84c05600b8904b.nq.gz
    ├── 4a15bcdfc729ecfdcf444e535502089a5113c772.nq.gz
    ├── 4a9504133fb245682726dc9faa6983a5fba15b29.nq.gz
    ├── 4b1f837fcfd53f112818db9b58b2b4efe64308e1.nq.gz
    ├── 4e81c05ea24c3c5704effcbad593d113adbf1186.nq.gz
    ├── 50054931d2ac3ad6002aebef8685bddcd1f964df.nq.gz
    ├── 5044d9ffe2b122bb118df41b3008c2d3118d444e.nq.gz
    ├── 50901a2d09953b58bbce6f415803f9273e7bdfe0.nq.gz
    ├── 50cbcada95b3e8f080a6ba62188b7e603416cbe4.nq.gz
    ├── 511d2951a1565b6085b104d5d7331ab05006fbfc.nq.gz
    ├── 52693e7a9c61095198058b7d5af213fdd2a03c6a.nq.gz
    ├── 532e562c57b2d4edd28900026749ce0c9bfd231d.nq.gz
    ├── 547449bf949eae3311eb82ac6f496320a9de0079.nq.gz
    ├── 54899a653b68685dbb003f1ec094a240173eea31.nq.gz
    ├── 55b29ae50ce3b830fce8d9bc4a0220c7ddf315ed.nq.gz
    ├── 586b87feb71de805d301ac28c790d9564483c3c4.nq.gz
    ├── 5a6b531ed405eee0719b58818af0c964860aa3cb.nq.gz
    ├── 5ab31ffcc9f27e3f773247869f8c64f6475b2097.nq.gz
    ├── 5b40ac2e6f3645afee21cd741a63472bacc76f47.nq.gz
    ├── 5d262ffcaf4084fbf2323b977e0c83917e1428ca.nq.gz
    ├── 5f33823e9cd4107a8d6cc8c308ecdfee02b85f30.nq.gz
    ├── 60a86379a3274b66bcac66c797ad6a8d216ed717.nq.gz
    ├── 60c10b4dbf55e05a55172be3755f7507c8cc0ca5.nq.gz
    ├── 61adf32a31a167a98206f3a15002b92a8be878ae.nq.gz
    ├── 64b395e7552105a72d15d1f69c7936e639a795db.nq.gz
    ├── 654b77a9d480fbf91183521848bec47a0aa1af2a.nq.gz
    ├── 6555c713fd1fdceabb8dd0caa73f94eff97fdfc6.nq.gz
    ├── 67d71c562555065ef1f45b1e27b0e1182eae6835.nq.gz
    ├── 686387769d2fb0778db657e6e317ba002904fcc9.nq.gz
    ├── 69115f439c00f05a15e17bee82d397b33142e6fa.nq.gz
    ├── 69c09d569b458c6ad92425594bdb35bf7c579d10.nq.gz
    ├── 6a9f22d003b581f716cdf4830aad2458d7059b6c.nq.gz
    ├── 6c78e91e0745324bad988e30b91d0d01c03f8612.nq.gz
    ├── 6de8d138923881fb6f8e7390a9e6e0fabb8a71e5.nq.gz
    ├── 6ece6a11bb05ba961268675ed52820a373db145b.nq.gz
    ├── 7340d469f2ce1696058c795b2b0b612cfcef4642.nq.gz
    ├── 74b260d58232f553c923ec947fac5cc902dbeeec.nq.gz
    ├── 76d768c98f798b0b481dc68268590db90b0c2c9a.nq.gz
    ├── 77c3defaa291e192654bb00b8d659a0f426d57b9.nq.gz
    ├── 78599315fe58d2be5233dfe758615b938bf25b36.nq.gz
    ├── 79d15e1f5d86536dc2b853ca8cae69d505a490af.nq.gz
    ├── 7bce02d9353a565361622873bf60959140459b68.nq.gz
    ├── 7c4d8045f564204458715bd846c7b4911cb851a7.nq.gz
    ├── 7daa1d7d3629f4ad502bb155c2f649a174e36c4c.nq.gz
    ├── 7dffa18a12ddcfd30309f18ed5d33de654b112f2.nq.gz
    ├── 7e6291f3b9bea34542bd0bf4af2fe238d981952a.nq.gz
    ├── 7ed3ab22b539867f4584537beebbee78eb104f7c.nq.gz
    ├── 7f1f74b275e53427fba4141822ac322800de08dc.nq.gz
    ├── 809eefa98f3e9494b54fcd2537874f7cd64d012e.nq.gz
    ├── 81e619311a4d5e37ca10789bdfedb69294752a98.nq.gz
    ├── 842578d2706b58a7600d21715d6f82e84eae34b2.nq.gz
    ├── 85009f5badf9fd6dd75fd263350f30bc42b91a41.nq.gz
    ├── 8587590f7e36e0b36f922db27c272f54424fc79c.nq.gz
    ├── 865b03b97bfbde5febfa965483faa2bfedde5b5d.nq.gz
    ├── 8742320692f8582cecae5b4736c3e5a8e8e0d70e.nq.gz
    ├── 89fffd1734c628443d553efe41691eeecacdf7cb.nq.gz
    ├── 8dcebc067af9ec32744c417db6ba374748dc4f45.nq.gz
    ├── 9008b9cb43b3ef9b3794d74784bb946e29836511.nq.gz
    ├── 925702638e42dd7914e1b9bbc6bbb6df417f6be7.nq.gz
    ├── 92820101d16798605865aae970ad3f4e25440c7e.nq.gz
    ├── 929edfea4811074d5eaa7cf689f769994bcf0809.nq.gz
    ├── 92fd4ae3108b18fd0dec629a888bf3eeced179c2.nq.gz
    ├── 9374e0c855cd736f41c03bbb35e809882e30a9e5.nq.gz
    ├── 93b396f6069a51b968e4bfa6fbf7242bcb53b49c.nq.gz
    ├── 94b4bf7a73e72e6e206c0c9d1aa4677e0eca1c46.nq.gz
    ├── 94d434cd4f4207f1962d4db3905cf60f01dc8bf2.nq.gz
    ├── 986a9d99ca6462c97436ca96e50d7ffa6042a06b.nq.gz
    ├── 988bb238d412860c4ce00ecc96f4ac2c30a48157.nq.gz
    ├── 98b7280f90fe2ef0127335453ef3dfb664c5ea3a.nq.gz
    ├── 98f0b4149c56b76d1b2a5cfa11641504459f609e.nq.gz
    ├── 9990c24737681f262ac3c725a08b8459fa38eb4e.nq.gz
    ├── 9dc8848a82eb68e428a6e05e0f15450eee9f0c65.nq.gz
    ├── 9f00351fc7908e6813a5ae3992ea07e62d769a92.nq.gz
    ├── a1703f1d7f257749054d59529aac7d03c4c93dce.nq.gz
    ├── a2b1cce6c41502fa71d314a4ee51a5654d1aa9c9.nq.gz
    ├── a4c76a36fc1bcd6efb66bf38b4012fdafea5ca9d.nq.gz
    ├── a575f8617b77f036cd3d7cc98b90f93d9fc27668.nq.gz
    ├── a5835a2452a2a05ec999e8d241bfb2aaf17f4359.nq.gz
    ├── a70d96b0aa508dd9ae73889d0f074d175119e8dd.nq.gz
    ├── a7398cb3959bf086a6453a059e6ca65c0b6f40e0.nq.gz
    ├── aa9b3e8b3dfc0f092e9070c74a267e1ed1350d43.nq.gz
    ├── ac0156cf48e0e4fef46b40358a4fb2f14a2023b6.nq.gz
    ├── ac355aef944c57afb206b8a8a0255cee0f3f35cd.nq.gz
    ├── aec46519ddf9523153c70f1a476d11f2a42b028c.nq.gz
    ├── b11c8e01d72ce53cbfce606e80d598433f8523ff.nq.gz
    ├── b1d6f0551413bdeb3341ff9aad0a640201173e37.nq.gz
    ├── b31043c1b6ac45129ae8a29166bdd160b8e6f812.nq.gz
    ├── b4b4f0640c2b95dc78bd91b8b183f1ecce59a875.nq.gz
    ├── b5d3dd430b4cbf20563a6399d455ce0a7a0056c3.nq.gz
    ├── b74c51899ea004cbd5ebe68b595d5baf4e310e35.nq.gz
    ├── b8739361578b58437784dc0f377dab79a2cf6f8c.nq.gz
    ├── b94b9718f027202c946613940ffa0ab5043e1fef.nq.gz
    ├── b9eb8e3c7afaefb98b18f12d64551ada7f4acd59.nq.gz
    ├── b9eea4503cba5bbbc86693ddc01f2de4b9d26bcf.nq.gz
    ├── bc74b88bef23f632f90e9d0002f2c7cb0ab021f3.nq.gz
    ├── bcb26b410797a2ea2de13599fb343c8f353ec76c.nq.gz
    ├── bda84c2fb518dbe26e1c72d5beaa7d7645c438db.nq.gz
    ├── c077361e7f73f6822d674670db5901e5f55863d2.nq.gz
    ├── c096bfaa662bfa0eb0689a516823dae3d88af246.nq.gz
    ├── c1829de0f37f2552fda00b1e2a9d6aa3792421ac.nq.gz
    ├── c18ca8dac742bc8d3a88333c793afe806ac87dbd.nq.gz
    ├── c1b859de450a6366b4d1a9f74f836a55a91a4617.nq.gz
    ├── c2ed982fd2e3baad1f3af02854d32b06e53b6ac5.nq.gz
    ├── c40f00821af6f9399db291a466aa6d75bcd5df87.nq.gz
    ├── c467fc845693485f4194b9c3cbb87043f8d4867e.nq.gz
    ├── c53578f2487b78074b3a08b5081ae5b2edbeda31.nq.gz
    ├── c54720da56cf82fefafa51e80b05e8be1444ae62.nq.gz
    ├── c63468c2026c68ee8064b05562df92bcca9e2b9e.nq.gz
    ├── c79374a142aa703d44cb9535b8da7d3957e14d1f.nq.gz
    ├── c86376d67d17bc7d1d58a14e0a860a6057cbd467.nq.gz
    ├── c8c525c3aea88ad4930c0ee2c505e584d4ee7ea1.nq.gz
    ├── ca28c285b3a861c9c73aed6a4d9e2dec63169c4a.nq.gz
    ├── cb9306e32e7af8c78362eac7c3662ae02a75bec6.nq.gz
    ├── ccaafed6870c4c5536c55d4d49fa1c1df00d950d.nq.gz
    ├── cd079497270795dad8429c61cb463c64f3a425ec.nq.gz
    ├── cd59ef1106f3ec4af0fae85559d3d6e4c77e711f.nq.gz
    ├── cd6e361989193f2efbedb9c06527371a68de8ca5.nq.gz
    ├── cdd631ad638f15e5e39f4528df45f021ba745f5d.nq.gz
    ├── ce8cd80a9e765bfea4f339863ee5c74ca006643f.nq.gz
    ├── cf3e4e07e630fe5350ffd953026f074298da8122.nq.gz
    ├── d14d52843eeeac34626747505634b336b5ced41b.nq.gz
    ├── d1a548fdae12aaf5694d950e0f78a804445a1e26.nq.gz
    ├── d2df85f0abc4b3e3a04c56bac3727d355ab2c712.nq.gz
    ├── d3c9d7e84650e17bb6b05fd0868ce8422324dcb9.nq.gz
    ├── d46d0f3de9c7acce25c81fb55e51d8341d01baf5.nq.gz
    ├── d4b8f0a8ad8b0a65e33d7f80b41c213af0234174.nq.gz
    ├── d5503034ed47f7c6e570cb2427b036b7c4a41043.nq.gz
    ├── d604ce842e5f36785bebdf279b73cce044923b6e.nq.gz
    ├── d6ae6415780e7411ff671e83864ccfc84c1ed5aa.nq.gz
    ├── d8cce962af3666d76ac22b32b9270f8fbadd8f99.nq.gz
    ├── d95ec84516f2d1f499c53fc10387c7cf6052f409.nq.gz
    ├── d9dd11b0056c107cc621589518f28593a87a35f8.nq.gz
    ├── dd7a075f9c514b159e475396397fa25aa309a3c9.nq.gz
    ├── dd920c075f7649c3a7159c13960e46a1b1f8db0e.nq.gz
    ├── e02cb5260c4d9599b2b1c08b2ceec054fbdef11a.nq.gz
    ├── e2646122b792b0c2653e6d810e594905104ce33d.nq.gz
    ├── e3a29adeb3788985f7056b70dd3d6d4956c3bdaf.nq.gz
    ├── e4ed7f8a37e60438b1d385720bd873f320b480d0.nq.gz
    ├── e5b7baeaef96569f4ef24a8830ba277762483e93.nq.gz
    ├── e5cd83bd5806cb7b78e32279af3943502734e512.nq.gz
    ├── e5fdfc28ca5d25c34b2070c4cacbae3222a705fb.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e87ef91fcab4274f5b571f332071ddb17344299a.nq.gz
    ├── e8b2858cc38c76782e1171e058749217c6d1e866.nq.gz
    ├── eb0c2d93cd319c7cb0ed1980f0d89e849d21ab5f.nq.gz
    └── f330f853b736db776c58b96aa3458b13489cfcbb.nq.gz

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

[kvesteri/sqlalchemy-utils](https://github.com/kvesteri/sqlalchemy-utils)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
