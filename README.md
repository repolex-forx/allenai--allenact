# Repolex Knowledge Graph of allenai/allenact

RDF knowledge graph data for [allenai/allenact](https://github.com/allenai/allenact), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/allenact
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d055fc9d4533f086e0340fe0a838ed42c28d932e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d055fc9d4533f086e0340fe0a838ed42c28d932e
│           └── chunk-001.nq.gz
└── blob
    ├── 00a15ca8e9308081cae724e579f043a5bfff2ca9.nq.gz
    ├── 00e713bef940ddccd44c135e0ced48f3dc9a3a33.nq.gz
    ├── 01c7be785bb36b8f781d627919f9c46e1dfca45f.nq.gz
    ├── 01cf642950add3ef74598a6780ce925456318866.nq.gz
    ├── 01f23c94b448ed6ab83366fa9e43717c14c14cce.nq.gz
    ├── 0246d18ee19692fb2dcb5a8c0f137ec0eadd40f9.nq.gz
    ├── 03a328b31665ea612974d0eb0ee5218622a61545.nq.gz
    ├── 03c161f68c9544e9e41a1aa70e919b64e0a28481.nq.gz
    ├── 0458d6e63a39bb671e1e7ed30c5e2bd871f90ceb.nq.gz
    ├── 04b201db5e6a0972e9c5e87c74e8be60b34001b9.nq.gz
    ├── 0612395344c0c72d1a5cbdf38252ba913e5f97e7.nq.gz
    ├── 0620c6faa35ab94ddb11743a5b16cc8fbeb2e97d.nq.gz
    ├── 07383ab4d9400b13ac19cfbf5adf24240a9071bd.nq.gz
    ├── 08e4cf09252071a9fcd52d281777393ac8b465c9.nq.gz
    ├── 0a2be525751984171aae1c48918e1ff1acf87f98.nq.gz
    ├── 0aa9f222defa20fbad2e149c3826495e4cb94114.nq.gz
    ├── 0b17e28f8e3ffb16b801d87b15e6d9ae3457e5c5.nq.gz
    ├── 0b61dc0f4c5f30bd198b70c6a12b602459ba35dd.nq.gz
    ├── 0d2dbc6c23995ded15b4581f9aa68d2913c36209.nq.gz
    ├── 0ef3a9b5272af8cc308af53e7f827887d934467c.nq.gz
    ├── 0f78932b49e7daacde99e2a166c0d87cd9d713fd.nq.gz
    ├── 105f1a04c8c124ab093805421b33edbb06753b1f.nq.gz
    ├── 10b8f9dd4c3292e17a21f300032d15dc2f2c7e4a.nq.gz
    ├── 116f4abaec7d4d1d3a4d2a4bd0c86249decae663.nq.gz
    ├── 11ced40dbc56983fef3108d11d238f4b9f7e2604.nq.gz
    ├── 11d4abc9ccd1caeb2cd871e15b72d95671a0bb68.nq.gz
    ├── 12a23db376649cf8a478c7ee7bf8586981e00528.nq.gz
    ├── 12ae26b5fcdfb6c03684dc6d2c7946afd3eafa49.nq.gz
    ├── 14379957bc93ff4f89e8b5339328688d0a0fd53a.nq.gz
    ├── 146982ae7ae7fa03de5d3ad4a05844b561f568aa.nq.gz
    ├── 16004393ac3e68e47c153d373a9a716dc8396e2e.nq.gz
    ├── 163918914a55355e6accf24246fd3c00fd24213c.nq.gz
    ├── 168c45b6a559bb1e290a300e2b39230e89ae86ee.nq.gz
    ├── 16cd7e71936917c47abc1e004b1a0a903cb38423.nq.gz
    ├── 1785dfcde189dd2bb916ec4fcfe807ae099e9834.nq.gz
    ├── 188ddcedcfaf6b80025c79bcf070881b4f11e322.nq.gz
    ├── 1962cdc1b2a46e0252fb509483aae332d0d3b6fb.nq.gz
    ├── 1c84796a17e03ad19b697757289ec187ac659b88.nq.gz
    ├── 1d81169be6dd3def07dd54d5d044f3aa2431460a.nq.gz
    ├── 1dbc76b2a792acf6778607786123fac2fcf8b20a.nq.gz
    ├── 1e2fd5568a9cb238e7a28e0302e0489adfe95ad7.nq.gz
    ├── 1ec4b8f39ff5740ce34c2fedd890ef2d185f6765.nq.gz
    ├── 1fe5f6d5b37faa45a635a4b050d72615967bc310.nq.gz
    ├── 2010f48c0598172ccbf8f1b6ff15c960dfb2afdd.nq.gz
    ├── 203d3cc08a80f3253f59ebad4c9433355bd8d4b3.nq.gz
    ├── 212b4c6e8012932d5c979d54ad7176496b4e8848.nq.gz
    ├── 22ea4049b6397112edcbc3c66e057f14c2357df6.nq.gz
    ├── 22ef3f2ad811b3e538eb2d79637e60156a0daf7d.nq.gz
    ├── 24ac5258420f7d0098f54029362f81acd3ca6788.nq.gz
    ├── 24c18a41c37b1d25056e2128c6a6057b57949b8d.nq.gz
    ├── 24d9bfa13013315917840380a67977f976099fd7.nq.gz
    ├── 256b87896570e2ec2085588526abbedffa420703.nq.gz
    ├── 25deabfb19d6890e0c549001de41c779ad3bf9f5.nq.gz
    ├── 29bedba09dbe323b67c799a1b02747931d6c22d1.nq.gz
    ├── 29c5c84edb5ea110138040808e9b5063be70b952.nq.gz
    ├── 2a048f4b9ab1254ddc20f5e3d66067400ceb3234.nq.gz
    ├── 2cd75b9d3a4528a9a75598bf8d69975a5854fca4.nq.gz
    ├── 2cebef6e3e8dca4d9ad224e023ffd48ded4eb784.nq.gz
    ├── 2cfb98572d10323bca5a064be3de47c5a15e66c9.nq.gz
    ├── 2d16941b3ad17eafb2c6ac9d38f3e3676f5f4f71.nq.gz
    ├── 2d415f047171af169545fecfb17080c360e72ada.nq.gz
    ├── 2da82b6b5416d67672f9a537036990c5d92d3d03.nq.gz
    ├── 2deac2d497c6721745b0315b68db2872f56400bf.nq.gz
    ├── 2fa9fd1041bae7a5f9bbc95b05ab379aa68e2d8a.nq.gz
    ├── 2ffc3e959e09bad7a4502c101414ad09dc97f17f.nq.gz
    ├── 30209a0af6d9196e638799ffde45998dc477e139.nq.gz
    ├── 30c925feb187eea7ef7893d5a15de0a52994ee27.nq.gz
    ├── 31d083236ca39d3bd0b05454df69b42f05b5b9ff.nq.gz
    ├── 31e85895e8e97d7b3e96c31c610b05271f7338bc.nq.gz
    ├── 31f87aee76df4dbd0fc13caf5cf7dd6e58b879b6.nq.gz
    ├── 345f0fb835c23b203b816becf5ee0c24f0d8db52.nq.gz
    ├── 3469c9a27fac2723c59ab8136051c76a74fb91b0.nq.gz
    ├── 35ea05822159776491fe4c2ee10426ce29685b44.nq.gz
    ├── 3b03dfaed71a473fbd7378a796a1ba96717192e2.nq.gz
    ├── 3b6bd24e89622b014c1d55b1158f234861bc0a14.nq.gz
    ├── 3ba89e64d5ea14c6d1f17c3f936df9ae046d5bd8.nq.gz
    ├── 3ce59b6df23d4a92fe0c7c62d340606a48dc48b5.nq.gz
    ├── 3d995c122ffcb43c73013e7c5b6c700dd4410378.nq.gz
    ├── 3db2e15674e4005aaa694ec4ada02ba201e56e67.nq.gz
    ├── 3dd54b4e71d6f899cb127b2e03c3906d37086a64.nq.gz
    ├── 3dd6a1024426ef8001a28061543497eca47f4253.nq.gz
    ├── 3f732ef333b453a05991d54be9760a997168d022.nq.gz
    ├── 3fcbfc63f3f8db8db4d4500ff93e6ac0648b1f9c.nq.gz
    ├── 3fef3a7e58676159b25920cfdf04085983143428.nq.gz
    ├── 40f168d82e1f0715d9270b1c8334a3f2e2605002.nq.gz
    ├── 4235968a2fd2a67cdc1ce0329d4b4da55e4691ae.nq.gz
    ├── 4324798f6461f86deeea3086a5737bc4cb61207b.nq.gz
    ├── 44794e151e55a2b8a2ec886f1c89e362045f1708.nq.gz
    ├── 44d19c9a749b5ca93bfcb4229c8100afdd625b54.nq.gz
    ├── 4586a7e0f1c25f531f720d987743ed42df906b81.nq.gz
    ├── 46593880a6d4db390692d5bda4a618c7772fa43a.nq.gz
    ├── 46935ab4cd1ca22a11b0d492a1379b036e6e17c5.nq.gz
    ├── 47595035de447fd4a863389a2cbea96a45a62ec7.nq.gz
    ├── 4875430f131382392b4e94dffe6c6e1e31b492ac.nq.gz
    ├── 4968de853acbd7879e9037ead5c2f4e6fc8ff625.nq.gz
    ├── 4db47f81eb82ee7da93b43202deaccaf0eac188d.nq.gz
    ├── 506736d705334d83d5e26543c0f25878cfa276ea.nq.gz
    ├── 508ef82f263b25e19d1447788b9356ba5b1d3d7d.nq.gz
    ├── 50a01db4c7a9df676f08bba226a40e91107f54ff.nq.gz
    ├── 5122ac08c8a8b1b62f167084efa1727812f04811.nq.gz
    ├── 534e5d1948677ad1ac6519ccf7237d81e3be50a4.nq.gz
    ├── 53be7766e05d59c4ad42da7c7ce03f375a00ec5e.nq.gz
    ├── 54067322e579456f0db791e56171489e40711a36.nq.gz
    ├── 54118458492bc23a11d5d50a33242a3155d3800d.nq.gz
    ├── 547f91b00bcf0e385cc278f99ed81432143079d5.nq.gz
    ├── 54d200cfd4d2085b1a03f8f053c30aca90bc4efe.nq.gz
    ├── 55e6d84aec97f7b3d2b411f802a371c88133cba0.nq.gz
    ├── 56c9110f2f0ec187ebf75ac27509a724a133d0b6.nq.gz
    ├── 56f4d624e54a17109241c9b73c25f9553d541ffb.nq.gz
    ├── 56fef1a46c7ec133c555139eeca652cfd2541c86.nq.gz
    ├── 573fbc67e2011826a38dd223641597289fa9c9c4.nq.gz
    ├── 5881b3c5c8ad8bc2157b6bd326c749cec9a83f06.nq.gz
    ├── 59ab220afb132b9ebf7bcd26fb42714c06be6275.nq.gz
    ├── 59c901da325ef87024e2b131d4e79512692c8ae7.nq.gz
    ├── 59f524f5ace3c19ba9a88652a14ac512b1e26a1a.nq.gz
    ├── 5ae5f0165b26d52547950f30057cb6d27fe1d8de.nq.gz
    ├── 5bd4e063a3bdf4a0c914fd5f03027186877f710a.nq.gz
    ├── 5bd8e40d4c86f2993f4b60a6c3964ec74cc236da.nq.gz
    ├── 5c8e8e2e3bc856b9a34831eee303249799ba2969.nq.gz
    ├── 5caed01ae7443cae711f4feac6409799ee482c2d.nq.gz
    ├── 5d0b97671a1fc349db76172684d3fd1ef04c9f3d.nq.gz
    ├── 5d19d091e2ab9c8fc038fa5855325d7f1a908df7.nq.gz
    ├── 5d490644b71bf9376c94856df00e937e114a2534.nq.gz
    ├── 5fd7c75d11e6177e4d66e525194cf59073d4cfe3.nq.gz
    ├── 60741378ce87ac128b6ce9b64c30a3efc25fbc17.nq.gz
    ├── 60bb36e19a0deb3c49a60ac415f58226c730f519.nq.gz
    ├── 60ee6889ea301ec7e09688750ddae9fcaec5dd9c.nq.gz
    ├── 611c68133ad6424011c7aed344943facd50e368c.nq.gz
    ├── 6556339e68c8628889c7192c8ef1a3537f72551e.nq.gz
    ├── 676e5a2b19e69f7decdb0958b06ea12ee8ba9027.nq.gz
    ├── 6811d29d8ec7dc506f2988d08b1b3c797ab64936.nq.gz
    ├── 69937094a1f552f716c76ade29180514a1183946.nq.gz
    ├── 69980d4cc7a6e6cf402f0773315c8216c8ad7fb2.nq.gz
    ├── 69da09bfffbccb6ee3d76ace4d90d19b3684f98a.nq.gz
    ├── 6a809941179c19693bd3f4955b2f17fc6a711763.nq.gz
    ├── 6aef7913cefeebdebebfd71e0f974549df259cd6.nq.gz
    ├── 6b62c5e0b10217645b5dc85f6f45ef47769e655d.nq.gz
    ├── 6bfb8a1aeb68cefcce8e0fa3d16fb61db49f9908.nq.gz
    ├── 6ce2d0fc16476c22f91b7979076af1619701c807.nq.gz
    ├── 6e63221b8362a3fe79831f38af5e7f3980373b72.nq.gz
    ├── 6f35bcebc2922f6d318a936dd44274443bfdef05.nq.gz
    ├── 6f363786df68ebd97dbf091ac40aebb006812a51.nq.gz
    ├── 6f3ce049f397c2798263457f726b061d0cdbe66b.nq.gz
    ├── 6fe9e26aab5e66092e1fe3bebb885c424dfcf567.nq.gz
    ├── 710ff39601dea0161d9aa2d544877041c82edae6.nq.gz
    ├── 714e0b3bb5310fc631dd99528d78ec63f009be92.nq.gz
    ├── 729d8210e18956c68f8a52a80f852221d2d1740a.nq.gz
    ├── 7316712f1a1eaf2c9ca62a878c0599fb70fd66ec.nq.gz
    ├── 734518ffb0ffeaf278883e8cd782348dfd214d1d.nq.gz
    ├── 75812e456dad87d79368224bb104ed828e0b5890.nq.gz
    ├── 759e2f2a4d47184976fcbbdfd3fb31dfbcee2ad2.nq.gz
    ├── 7620fa2b987875e512c5596b7f737a0fcf0a8bab.nq.gz
    ├── 7683bfed82e57481a1a21ff7db89417023ca3ae8.nq.gz
    ├── 76be9b4118c0f2bcef96f863fc7a7d24f0c6e6f3.nq.gz
    ├── 76feeb0b5d987641b9bb06e41c788162b61a62f2.nq.gz
    ├── 7977474eb5e06c1f4d988710d83c9ca04aefa62f.nq.gz
    ├── 7a789b9423f15b24cf66f43c62978cb9e4052128.nq.gz
    ├── 7b4be27be6a4175fbcd0b27514c29e4f5120a5cd.nq.gz
    ├── 7b7ab23d75e309640eb096eb8fec24307f962c64.nq.gz
    ├── 7c92110b0fd243a9aa7c321c2806f9ba3dc5ddbd.nq.gz
    ├── 7d24235171e9358e522ac852ec92e014f65fc0fb.nq.gz
    ├── 7ea8b29ac82e613e9753c2030f4aa4ec17d34422.nq.gz
    ├── 7f0cf56190d74bc761d0ebc99437a8bfbdbf61ce.nq.gz
    ├── 7f5c54561ec8fe7e7a8be656864a421cb69a6743.nq.gz
    ├── 80eb8fc9988529ac2db3a770235aeaeca39b25f4.nq.gz
    ├── 810a14214819e1a875a765e1dbc87d21c91f0272.nq.gz
    ├── 81c820cd875054cab6afa0acb4cb830100a2686c.nq.gz
    ├── 823ddc11a896de19d61e86c8a83a84a8facfcf1e.nq.gz
    ├── 828c2d4d677b4071711ed4a6284369255a29d61b.nq.gz
    ├── 82d632949afaf2faee0039f098a88fd43bd715c9.nq.gz
    ├── 832577ff4bb0e29035476289d638f959c385f8a3.nq.gz
    ├── 83a2b73c46fc1151c42ba37bbd3fa6a6bcbbd7d0.nq.gz
    ├── 83d6a3f2866b3fee15ffb02ccc223104aca0fc76.nq.gz
    ├── 847d084ab7fd30394a052f5a83b89c7e910019b5.nq.gz
    ├── 8480166b3980bb46e7f165401f237d796ee63879.nq.gz
    ├── 84f4f2c5bed315d4bf6e8f1f56a728a74e795d4e.nq.gz
    ├── 85635a93991d1fb097a957dd28adc5a2c4557e2d.nq.gz
    ├── 8564143be68466270c1c7b3cf23baa89548bc5fa.nq.gz
    ├── 857b3e633c29aae74e71c14738d9e7a11f071534.nq.gz
    ├── 874583a1863ae51735b49502570d3f8f466ac406.nq.gz
    ├── 87a52c05153b5f96607625ad85a6249d56f2e597.nq.gz
    ├── 87f1d02ad68fed4be0dc68e8dc7d75e2213c844e.nq.gz
    ├── 882fa1e17add2ea40c7bcbe9c212f69aa959d662.nq.gz
    ├── 8871a3171c4e3eb76de4a8b65257c48e4b0b4e6b.nq.gz
    ├── 8ab7fe54125857595d73941e6a4817d38ba35a99.nq.gz
    ├── 8ad54dd47fd9c8396ed707dd67c47b76a87c04fb.nq.gz
    ├── 8b0c68f774142ce0426642ca2f44a44428ff6a10.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8b45c54a9d748f0e103c9457167fc17600383521.nq.gz
    ├── 8b723a0e46f3abbd7b58cd9952a68dcd65ec1daa.nq.gz
    ├── 8c6492ca8e2ce80865b32f8c59e1f717a1d46353.nq.gz
    ├── 8cc6f23d95dbcfffc53f783f72cd59271d5f608b.nq.gz
    ├── 8cccfac0da65ce9ec12f29de3f5941b560b5a118.nq.gz
    ├── 8d6b998eae15d271a75f672fc627007663377df1.nq.gz
    ├── 8e0133c171f82f4c70cc61976ef116e408bb7328.nq.gz
    ├── 8e22d9033e2125cdeafc44ad25ee81e535d9da3a.nq.gz
    ├── 8f2927708618d506633aeaac44e2a6c7ff1330f4.nq.gz
    └── 8f9f3c2eded41497ff7f6dbf3ca58210b11c7b20.nq.gz

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

[allenai/allenact](https://github.com/allenai/allenact)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
