# Repolex Knowledge Graph of HMBSbige/NatTypeTester

RDF knowledge graph data for [HMBSbige/NatTypeTester](https://github.com/HMBSbige/NatTypeTester), parsed by [repolex](https://repolex.ai).

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
rlex download HMBSbige/NatTypeTester
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a1935d46c5e47ea9447840a2f1dc8d6f30b29fe0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a1935d46c5e47ea9447840a2f1dc8d6f30b29fe0
│           └── chunk-001.nq.gz
├── blob
│   ├── 04cd339a68ee630924d05410ed87f5f3ba279cd1.nq.gz
│   ├── 052c37df24d20e48fa8a36c9595c08858d7b52d2.nq.gz
│   ├── 059ca1774d79551c5489ae6510910ab14155623c.nq.gz
│   ├── 0683057a1f32f5b8665330290a8bee312ab80738.nq.gz
│   ├── 07631fd7afbcdb1e17f66c782e63f30c258744a8.nq.gz
│   ├── 0901a8f07bf7f0e1f2759de21231f9ab386c66c6.nq.gz
│   ├── 09839c5a2bf8306ad811fcaa360975afbce0fba2.nq.gz
│   ├── 0b4ae2f539a02be8c0a77a670acb18185eaa72ab.nq.gz
│   ├── 0b7754df625e9a73b4afb1e77d06b78e43cb1e9b.nq.gz
│   ├── 0d9debb730497c137c34a2cc6af6aab815f07de2.nq.gz
│   ├── 11c44e8be8af7188c27b6dbca40ed37cb6756d95.nq.gz
│   ├── 12dba3859d6bb20ec8d8e9689d81ea5272e4dc97.nq.gz
│   ├── 13bcae3c4f337b04e65d205a277591127f8b7d52.nq.gz
│   ├── 1506f4a39f0eb55dbd48288c6f41cc082d93da6c.nq.gz
│   ├── 1515536fc8df63a09059b2d39bb547b28d81a82e.nq.gz
│   ├── 15ecba184a9855bec05d2b882be5eb5b301f6f4f.nq.gz
│   ├── 1721abb621772e16d71673c9d7550226b8df811b.nq.gz
│   ├── 1721b72e2b2c1e2f096f0ef83928d3f995faa962.nq.gz
│   ├── 179ac06000c041813cc91b4bc5f2e3969e2b858d.nq.gz
│   ├── 192c1c83609c4e32ee4dbeb6ccfcc109ea829fe5.nq.gz
│   ├── 1a062c64fddbb66f32f6a55204284b6a4506c239.nq.gz
│   ├── 1c2b3b71d35020c898c29542defaac77f3f6920f.nq.gz
│   ├── 1e64bb8f619665ba062c76ee077f6db9681ac8e4.nq.gz
│   ├── 222ce9b1986bc29c89ff61c861b6038dbe762c9f.nq.gz
│   ├── 2281cee7387e6dde83328faee89f36142a71de1b.nq.gz
│   ├── 22e5e561467dae18e6dd6e04c4f62abb00d51143.nq.gz
│   ├── 261bce2e2db465c4fcbd81efa5e144056792533c.nq.gz
│   ├── 2620d32cc43079c555a6cdec73e26e9908fbebc7.nq.gz
│   ├── 28799f60709b8e7f75ac5f0195c26f2426cddeb0.nq.gz
│   ├── 28d387acdfeb7814aedb99ec4196453139c818ee.nq.gz
│   ├── 2d96d8335f6c4d2c9f5874b2cc39a856fe176b3c.nq.gz
│   ├── 3017094948a44ec649f1df908de6c0f76289625d.nq.gz
│   ├── 319a5d8a9b0c0b95e9361afa35faef7c1ded23b2.nq.gz
│   ├── 35196f46770e385ac2cb5ed98b880d60e453820c.nq.gz
│   ├── 355eff0bfc1f773e9c32b511e78f6cdb4af1dd58.nq.gz
│   ├── 379226f86ea87a1ce0dc1aadeecfee6512eb54c4.nq.gz
│   ├── 3dbb12c20449e2115b0d1befcb33169733dbef84.nq.gz
│   ├── 3e24f7369143f4ad969a8c1be23d23d66c3bcfdc.nq.gz
│   ├── 3f41b425239e2cccade635a1490a0ed672ce1846.nq.gz
│   ├── 401d4565641bef0700c8ff78dbb06230c3cebdd7.nq.gz
│   ├── 413b88b12cdda4a39f241d74e0923eca9ef50d08.nq.gz
│   ├── 422c12afc362179643f032547ef691137a522d44.nq.gz
│   ├── 42a76711b7148ae6797b1c89b7f4474ca5ef26c7.nq.gz
│   ├── 43c1f62b8469bc6ec7ff1f3b0bbcf429a580d81d.nq.gz
│   ├── 4419cb5526416b227f3835232a5ddf436229a764.nq.gz
│   ├── 44869860aef15b6d9914872af30d92ac310742d9.nq.gz
│   ├── 45800332f7ce59d740f086af2eb4821daaa6e822.nq.gz
│   ├── 462df01b7317e130871ab3f18a268ee5bcf1d266.nq.gz
│   ├── 475ea4fa146ae57469a526fc3359007ff3821973.nq.gz
│   ├── 482f330ace851fc794a4fdd7d16de266a2f88e25.nq.gz
│   ├── 4d835297b4969a89af310b7946073bb1d75805fe.nq.gz
│   ├── 50309f0a5bc607c643d5a4b38fce6ebe25d27cad.nq.gz
│   ├── 50ddb9ea28e97d7fa99829913748747adc329c9e.nq.gz
│   ├── 547b576b9e7d480756616bd167c4763fa1f4ddbb.nq.gz
│   ├── 55f74691f6d6cc520d8643387b88c55cfa0a0763.nq.gz
│   ├── 5678df2444218b9556439126cd4b81740778c8d2.nq.gz
│   ├── 56ee066568f8a45af03ed21b1e9db805965a6238.nq.gz
│   ├── 57d8ee819e188f005724d6e91487c0be26a82a44.nq.gz
│   ├── 59d7088fc85e2ad9922122914e9d14dc2e30c0d8.nq.gz
│   ├── 5d47bcbd626ecc81568d44c1a8b7a5c4662118c4.nq.gz
│   ├── 5df2696591061c5b93fe2ce4e992a679edbf1a5f.nq.gz
│   ├── 5e14efcec05861921daec5ded51803413ad651c0.nq.gz
│   ├── 5f0c721fd4c2076f33eb65a69ae721e857e4d36a.nq.gz
│   ├── 5f111d48519f0f344005c6ffd366b6e5fe9d3288.nq.gz
│   ├── 636b7f15701450d61ad5a0f9877b1a9a03ebdc43.nq.gz
│   ├── 675b130c07e727dcca84b926df764abc2ef33409.nq.gz
│   ├── 6908dae4d0eadcf81bf3eae520f840890d896bd7.nq.gz
│   ├── 6a5de34b744be45e63f512e47c72c21850955bab.nq.gz
│   ├── 6c36faa267d41fe4380659be7a1b48d08bd8c5d4.nq.gz
│   ├── 6cfa35adc868a884440ac2e386bf73700f657191.nq.gz
│   ├── 6d8e25bf2213d8fd819c3cae49e0f391a2901fb1.nq.gz
│   ├── 6e853dadc7f03a751a5c1f26673f376bd9db1a15.nq.gz
│   ├── 7079b9d1180c98e2bdb131550a8cebd86446b157.nq.gz
│   ├── 70dde76d895f822674e1b78bac431bd1c7e36bd2.nq.gz
│   ├── 7109ad12a954d982f5b735a27b88473ac8027947.nq.gz
│   ├── 7128614aeba330deddc02081199725ec1f711eb3.nq.gz
│   ├── 713d86b6db2443babd34151211fbc297f883089b.nq.gz
│   ├── 7187b69e5dace20203f885ae01f4ec286dcbc242.nq.gz
│   ├── 7237c297685118bacac02a5c5eac4caa19807965.nq.gz
│   ├── 7455c4bd54931eff90407916d13b6570ceaae0fc.nq.gz
│   ├── 765346e5343d46ac83654843869dc06b65b2bdc4.nq.gz
│   ├── 7a5bc80294e9e573f58eb6145a931cc8553f9fbe.nq.gz
│   ├── 7d05e7834c528dc65c941a9d4572cd1a87f58f08.nq.gz
│   ├── 7dd650bda0fd4012289d2a375bbaf752c0ac0122.nq.gz
│   ├── 7de5968dcc1e4ea35f31fed488386b9ac00685c7.nq.gz
│   ├── 7f8145a351a82383e38e39a3864466dac4336466.nq.gz
│   ├── 80f07b559b0c297df2eb46e6878aa1cd3a8d18ce.nq.gz
│   ├── 81bbae8d166cbc5ea8b0c49c914a00ab8d946d3b.nq.gz
│   ├── 844049f74ce9fa6229f28ae28842fddc4b02cbce.nq.gz
│   ├── 84a3a4ddc75618179da0e9b211e999a1a784da9f.nq.gz
│   ├── 898ccd6cc9e7fccc49ae1aa12426c23613fa2c25.nq.gz
│   ├── 8a37cac6c46ffbf51aeeeb492e4b51d87f3a78da.nq.gz
│   ├── 8aab2f8593a96974b2d162682af42117dcebaa87.nq.gz
│   ├── 8b3b0e8d862081a9f4297e166bc12920a48638f0.nq.gz
│   ├── 8ba36729fd984d342ebcfbf8a0dcaac841d46000.nq.gz
│   ├── 8c13e03225ce9754050c096145d38582369f76c1.nq.gz
│   ├── 8c99b21bd17a825af914b90c26d159cdb04b0535.nq.gz
│   ├── 8cbf009e3a94f3162fc24d8f69634af593a45c24.nq.gz
│   ├── 8d251508be5d403828e29d0b4f22cd269765dd2c.nq.gz
│   ├── 8d55c596d6287bc432ff57cbc9f36e83fb67a07a.nq.gz
│   ├── 910528ad31d82a1e1e3ca33c357b3f2b6c07f4e1.nq.gz
│   ├── 91f1c089acd9f92c49d63663ce0a3de2fe18d2fe.nq.gz
│   ├── 91fecab68f58f72a426bcb95e5aa714417652e4a.nq.gz
│   ├── 954d39e7653dd8763c46d75956b0dc42e511b42a.nq.gz
│   ├── 96c1c7ccb3e628e7b1974e4d78c73e6569869c31.nq.gz
│   ├── 97f3b0188fd18559cb8eeea22c1066cd21f14226.nq.gz
│   ├── 9942bcd00fe0928cadce3b6574749b54c84602af.nq.gz
│   ├── 99e89f7ca681655f70616c1f8c7200dd2879f75d.nq.gz
│   ├── 9a3d260eb5d11d900c56c89fa89a657bc7b03568.nq.gz
│   ├── 9c40a0989153a8bb2dd26e4c2a1bd076b7c25ae2.nq.gz
│   ├── 9c439e58127de1b6411545f3da766617d2c22b4c.nq.gz
│   ├── 9d65bad576325c8d5fe87537e40a0a11cfab9852.nq.gz
│   ├── 9d8a4591fa7776f9c5fb1b2258fd3f84c0508208.nq.gz
│   ├── 9dc4b3b000c882a0808f9e0bf8716e9f04f669e3.nq.gz
│   ├── a18b538b600e018493f084caf2416a6917ba01cc.nq.gz
│   ├── a1b3c7f573d150736742fa0d41a4cac5b6b49a71.nq.gz
│   ├── a1f5242b26ccf50544f50ef86faa2c67b45a5ba5.nq.gz
│   ├── a2c5a2cd17eebf3670ebc1b697f08440587e22bc.nq.gz
│   ├── a323e21bd7e3ed505583f605c099b022832886e1.nq.gz
│   ├── a5b8e1cfcdc0f832386a71d6bd44f59f22e2f2a8.nq.gz
│   ├── a6db775a74c07c7c85fdc0b05666758935a44738.nq.gz
│   ├── a7271d7acdc53e29497aeb5fc0849a6447674971.nq.gz
│   ├── a7f56ac5452fee0491853d1c2d430259ab5d7cda.nq.gz
│   ├── a96f2dd3b2d3ecf9feb125b8b2a4768d4f374bc1.nq.gz
│   ├── aa99bd1dbc5832fb1d0a9bccba6c8ae41a573f1d.nq.gz
│   ├── b1034f1f7bbe287f9d066ff5e707247a97e7aa89.nq.gz
│   ├── b20bd58d5fe97cf465595d6cda77e96784d3d4c5.nq.gz
│   ├── b295efeccbe574e0849dd9bc0fdeeec125ed3a9f.nq.gz
│   ├── b2d523f5b0f558882c6e2b286a255761827c0379.nq.gz
│   ├── b3cc345cea6495d6131484f915f07d159c7cbaf1.nq.gz
│   ├── b4f57ba987d3a21b33c6b90de6421ecf4d2eaa03.nq.gz
│   ├── b590adbeb3366913744136a4b5adb621ae0e640b.nq.gz
│   ├── b78d7b7951c0435b19f50e13d69aa94550e9fa8c.nq.gz
│   ├── be48929cd917abdc1fffb026402f6001bc290a0e.nq.gz
│   ├── beffc98f62c4c296f4c8db87ae89ceb7c04a556e.nq.gz
│   ├── c1dfc9bcfadb8fb5ac5c51ce2a8a21823dab972e.nq.gz
│   ├── c2361490a73d7821a65da6b8f1b717c9b5c6b14b.nq.gz
│   ├── c29bfe3d3d6ac7c2d388b2c8531e07d95021494f.nq.gz
│   ├── c3b7b08b1f0442d06506e951cd2d9f722440440c.nq.gz
│   ├── c44315ca649804ec64a639220db8d831591aec68.nq.gz
│   ├── c4efe5d376ab0564b2959ab25e740e0924360bca.nq.gz
│   ├── c63b1fd989cd57d72bbd725d14141c4b5cf26479.nq.gz
│   ├── c63e3ccbe07ca63312cc22a2b2c98f4d74cef4d7.nq.gz
│   ├── c67f73ac9df81109a6becc07653006beb8babe7f.nq.gz
│   ├── ccb2710c53d2ffaa371a28a24bfac973d5333f8f.nq.gz
│   ├── ce6d3cfd235cab505a975a8c4b5d7407bd305ded.nq.gz
│   ├── cfa67d95c707f906b7cf30496a01e5c48fa982c6.nq.gz
│   ├── d45d47c984302f3993a8223fdba611c8268e4399.nq.gz
│   ├── d5069923e0784325c50833b329e9aa9ceba3f661.nq.gz
│   ├── d6b8dc4c6fe778085527657340119529075a5bb2.nq.gz
│   ├── d8703b0334ebd56ac12bd0ffed382ccc592b0f87.nq.gz
│   ├── d95a51ea05e3c5331bedc7ceb41254716d698f68.nq.gz
│   ├── d9a0accc9b19285f56f64a3f32146f805a1171f7.nq.gz
│   ├── dd0fdf65e354be9b707a12f4a7151a88068a702f.nq.gz
│   ├── df03a20d35dabe280ef6395f7fc4a4df32f82bcc.nq.gz
│   ├── df50a483e56255e1fd3ad73080b291b7be34f2cc.nq.gz
│   ├── df90bb49377a68d8d08b1ede1f7244c6cb2012e7.nq.gz
│   ├── e873f37870792247b27e74384b2f7a98441d699a.nq.gz
│   ├── e8a8a3dcfd0061968246660dcbed25fcfa7873fc.nq.gz
│   ├── e8ef6deb10441fa57cb13fb80afdb83d6de3b319.nq.gz
│   ├── e9ade6f97d46a4c9ce2260828cc37dd2f46cc370.nq.gz
│   ├── efd08a2e3fe6f076496e77a459f3dcebd47a2c85.nq.gz
│   ├── effbdc10e79212216ea4ae4d266ef6e87a6432ae.nq.gz
│   ├── f03026a17710025805b3e1b071ecca77549fdec7.nq.gz
│   ├── f67cb3c057fdb235c23461f802b9ba32e27d27f3.nq.gz
│   ├── fae6dcbae54b0cc8b960da52338b10660ccdb37c.nq.gz
│   ├── fb5038f38a2213b612ba41d7a5206757563baf89.nq.gz
│   ├── fc2f50a2c53ecdafe9d7a76cb41d65c8ced59469.nq.gz
│   ├── fe7797bc250faadb281c18a21a76003cca0c7105.nq.gz
│   └── ff6bcd44df30fbead5d650b8da0a7593ac560f84.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a1935d46c5e47ea9447840a2f1dc8d6f30b29fe0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 178 files
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

[HMBSbige/NatTypeTester](https://github.com/HMBSbige/NatTypeTester)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
