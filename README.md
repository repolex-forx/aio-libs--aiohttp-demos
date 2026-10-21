# Repolex Knowledge Graph of aio-libs/aiohttp-demos

RDF knowledge graph data for [aio-libs/aiohttp-demos](https://github.com/aio-libs/aiohttp-demos), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiohttp-demos
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7e2600701a2dcce81863ceac85d7756e02436e1c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7e2600701a2dcce81863ceac85d7756e02436e1c
│           └── chunk-001.nq.gz
└── blob
    ├── 011a91757df561b5955df205f63cdb000012c4e9.nq.gz
    ├── 03add183cac4ec774fa156c374e474fbd1c5d30f.nq.gz
    ├── 03e3b294341040b2409ef47276592801b0fb7207.nq.gz
    ├── 0423152f269be9be8f8453470467a88b1da27679.nq.gz
    ├── 046058a43af26e92b7d016212a8e2269ca7d26a6.nq.gz
    ├── 0577dc6ed3275c01af2e7a70cb2bd23d36b2a839.nq.gz
    ├── 0653cbbe6649ccab868dce038b012169051814c9.nq.gz
    ├── 07679f028d574118d9865d1d03482234695c4bf9.nq.gz
    ├── 079729584708b5ea93b24b6b4f190fa983b4182e.nq.gz
    ├── 07c784afec5882f07af660f48b8ddc9a03db5c60.nq.gz
    ├── 084114cd426878ab72a8039e4df6f2b485da431f.nq.gz
    ├── 08f69dcd5581d4dd4c509e80aae97bcefecf052a.nq.gz
    ├── 09e50f1ef4288cfa62cdc327ff37599fcdd5f7b2.nq.gz
    ├── 0a3c358c5a8f81d9207d5e1772617fae847eb279.nq.gz
    ├── 0a8f141e66c34f88e861c654cc540ac241b68b9c.nq.gz
    ├── 0b2f7b0655f41276d418ca8302dbaec8b7e7e829.nq.gz
    ├── 0c0b77d470d6723bf9ee0369e42ae0ba236800ec.nq.gz
    ├── 0d62949085b0cf5583935d729228127adc0928f6.nq.gz
    ├── 0db3c1ff7ef2df37a2c2884a66ce79f90d4983f7.nq.gz
    ├── 0f6bcf2be489aef33c2c5a794f3bd1dc8eb7c8b8.nq.gz
    ├── 1201e538934b2dddd9c1e9696155bfae2caa86c8.nq.gz
    ├── 123ffd4f277b90ca478f77190531ea28ca546ab5.nq.gz
    ├── 1306e09f4f04ba5cf5ee707c22a34dd82de4f09e.nq.gz
    ├── 13416f3b6af9049f2284817eb0d60930cdcec605.nq.gz
    ├── 13d1c2896c8ad03f4c3883a0805a8934a7d7b516.nq.gz
    ├── 13dc5fef84390151f98984b8ca63fcbb44dfe436.nq.gz
    ├── 15394fad214a762e10fe87b54b7cc045873f667e.nq.gz
    ├── 16e53f4fcd4a762b1cf42b6af23d42dcea3872ba.nq.gz
    ├── 176a458f94e0ea5272ce67c36bf30b6be9caf623.nq.gz
    ├── 177c320ad6813b5664c019c2f3372d29d714894c.nq.gz
    ├── 17cadcd03cc09ed762241f9d4dce289a8e274648.nq.gz
    ├── 181bf646b5648b371b982c6269f08d379554973f.nq.gz
    ├── 1a3dd91b15a21a261ad9e9eda84670b16b9fe103.nq.gz
    ├── 1a56c65f6b7c5591236d8b509f8be64bd8cad6bd.nq.gz
    ├── 1af3facc560d0851d89ef149ced5ffec8bb35508.nq.gz
    ├── 1b19000beaeb54fea30df4c2bd0626388f74ce91.nq.gz
    ├── 1b239f621b5a1634d15761af0c3c1fbffc5361d6.nq.gz
    ├── 1b491f3a116021e85a9558e2bdc2cb7be94fdd9c.nq.gz
    ├── 1c40d1236221da8b986f62565630149a6cca21b0.nq.gz
    ├── 1cee8969131cb1ab1d87dbf4008b58bdbee7a5d7.nq.gz
    ├── 1deb4ab5d81d9752cfb3d7024156296f8d83dfa0.nq.gz
    ├── 1e3013fd268736cd5bd21dfc346f2c1f5c43fa4d.nq.gz
    ├── 1ee05b540c73ae0a83baa2b197e69c639e2ccf0c.nq.gz
    ├── 20aecd50fafecdeed9c84448d46f9b809e2a2c0b.nq.gz
    ├── 23a8214e28ee84f06b9296ed0a64df3b068f2655.nq.gz
    ├── 2428d0a10d4a75dfbc3e6606b292028010966dba.nq.gz
    ├── 248f0f06dad274efa115e0b368fbc3b69caaa254.nq.gz
    ├── 24eb9e2c8d4573bf90f4d871c2efa97bbfbcc09b.nq.gz
    ├── 260983b80f9f5374a27f5a3e3fd3dc09246dc45c.nq.gz
    ├── 26e2217a92bbe86d1c2261dd885f934f2c5af2b6.nq.gz
    ├── 271b8e0d972051ed7f22c1757360dbe0202615de.nq.gz
    ├── 277375bed3bcdea6c3278f0f1d5679f0979d3f00.nq.gz
    ├── 2892b97003b152de96f5644e3dea11f28c0f646e.nq.gz
    ├── 290b698fdcb8db01e65f17027dad48cff4885d8a.nq.gz
    ├── 293f488026689e661eebc2d56f86ff7146a88ae0.nq.gz
    ├── 2a05f3a424eddb5ca2136ec7b7219a110d50bf12.nq.gz
    ├── 2b22a71363f1e7372e59d7c308f2ff63f7336383.nq.gz
    ├── 2b78ea2df73956a64338597eb94830d2612e3418.nq.gz
    ├── 2b87a55c5c088796ea09a749b0153c3a3e44b569.nq.gz
    ├── 2cdfb25adb034f87d24eb27196e7d1220e0923a2.nq.gz
    ├── 2de05db5297a15d49b2c006a2f08ac69d98001e7.nq.gz
    ├── 2f4bb5e8866dbe9297c7fe12c49c61ca0de99441.nq.gz
    ├── 2fe9e9471c95ebfae06345f04769047b6e5170fa.nq.gz
    ├── 3079691fa5aa6e196de2c520e1eba66e9983d7b1.nq.gz
    ├── 31a12a52d1655138d3c8a1a9f9b342d9daaa6197.nq.gz
    ├── 31a25ee252b572dffc4f9a13b9e395d6b38197a5.nq.gz
    ├── 34215a30932e6016e42cd7758b8d0ce3453ca4cd.nq.gz
    ├── 34de568bafea257e4d74d68310384816ed8a4245.nq.gz
    ├── 3521fa44ef21370c2d1c72db62913eea7f84ae41.nq.gz
    ├── 3522f1ec23bc9549a4572a87e645f509da7a7a5e.nq.gz
    ├── 3555498a1c6fa7f79cf400a5c0e7480b78cc4b59.nq.gz
    ├── 3b1c28b49637af1e25982fbaaaa80346af8bbedf.nq.gz
    ├── 3c012ff55f6d0780f2802b86f5684b4e165324f7.nq.gz
    ├── 3e447b4c2b9ce9245cacd902279f090661b0f2a0.nq.gz
    ├── 3f7a1b8ab29620174ec32be1b1a2d4ae1b802c36.nq.gz
    ├── 4050aa1f58f99cde34f3c9b18cb84104366a7e9e.nq.gz
    ├── 40afab6819c46bb7e7cec730fa0d7f2c52cacdba.nq.gz
    ├── 40ca65e4c1998cb99d0738bf06c7626b28a934f6.nq.gz
    ├── 411616aa8b998c4ffb30539d44c4c1ede4d5b13d.nq.gz
    ├── 42440c264e7465f8a19492c7f520c5e045cc3f77.nq.gz
    ├── 430db0fbc3b2d6906d6ae140cd6c03f4498d759f.nq.gz
    ├── 4371796281be1aa63637c6e2377c3e20ddf765b6.nq.gz
    ├── 46525133768a5712ce2d96647830ba50567a0ced.nq.gz
    ├── 46ecb38d6538e4bf45bc9ab1b7f44a2f3f4935b2.nq.gz
    ├── 46ed2df61263bc4b5f52dc77babe6a70aabf0d11.nq.gz
    ├── 47795b7dcfe247775afc054f6f0ff49b2ed12963.nq.gz
    ├── 492ccdaa5176c7e31c46839cc06c0bfb4b3d777b.nq.gz
    ├── 4a1608cf20432158967bb4de2ab43c2f20b689b1.nq.gz
    ├── 4b65c92c097e30ec316a2de81c520be035c1c55d.nq.gz
    ├── 4bef74059118907e8217e89a6a9764633182ccd3.nq.gz
    ├── 4c3315908e3ddc26825e889668d5f63fe053c80a.nq.gz
    ├── 4eef6f6eb0a43d01bcea41ef9be8d71cb0373391.nq.gz
    ├── 52a847fb714f2fdc148ebb282c40f7cfce77fa64.nq.gz
    ├── 53bc17423a46459e51e6eef093195dedb8adc1cd.nq.gz
    ├── 5695e5f85097a7b1c160058d80bc8df0aef858bd.nq.gz
    ├── 56b6e563e1364e1c0ded8b87f83578010fd6028c.nq.gz
    ├── 58231e9ca186d4be2adc99ce01d4c3067a36ca7a.nq.gz
    ├── 587f55a17af0001c64a8494a44ed72085672d53d.nq.gz
    ├── 5970a78ddc95a809338a12b892f0703386028cab.nq.gz
    ├── 5aaed0ebf3395102b020fad5842a1ca38d285db4.nq.gz
    ├── 5aea0514e106e5f7612146ef9d17f63fa106421e.nq.gz
    ├── 5cab325467d9a02fd204543f5830e72a44ade415.nq.gz
    ├── 5cbf4186223ffff9246e142e057e683249b5566b.nq.gz
    ├── 5d98ed6f5405e30531f967fa9dfc8492537ee348.nq.gz
    ├── 5ef2a98ee09be1bf64fccefabf880fd6ad861b3b.nq.gz
    ├── 5ef34bf65240895d9662d207d5d99c64acff4629.nq.gz
    ├── 5f26c66a9a8803c797e2bfa600696da96bb0140e.nq.gz
    ├── 5f45c1083a195e6688cca15561a6a4353acffedc.nq.gz
    ├── 642e9aa56b841c878de816dedac0f3c9bc0c4298.nq.gz
    ├── 645415a14ada8c82e0243d1c9c3909fd5ea82b0f.nq.gz
    ├── 65e1aa53b0f3219caf42c370cce7b8f20b41b2cd.nq.gz
    ├── 666937af4283563b86c9bc288cca20b667d4cf5c.nq.gz
    ├── 67b51bf71112ee8c4d72b41f3520c9762239c4c3.nq.gz
    ├── 6b27399ebfe1437323ee00c85917a6a48f4df7c9.nq.gz
    ├── 6c1ba8c25749bdf6a85c253a01cb18449bf82a62.nq.gz
    ├── 6c8aaca5ab04288817269f04e73b9eaaaa3e8e53.nq.gz
    ├── 6ce72348fca377a9aab9d62c2ff5fe43ed308c66.nq.gz
    ├── 6eecbfdeb57174be7088c9bc721a80d2cd695562.nq.gz
    ├── 700d310220f0b900f1699eae4b7149961cd8d1e0.nq.gz
    ├── 717870b7a343d809c58dc0e9946c2cdedd3fc36e.nq.gz
    ├── 725162c83bf68cd057db6c6c6ce6517b9f85b062.nq.gz
    ├── 7628fe44a6d56e90b6f626ac2b78eecf85834680.nq.gz
    ├── 76c985dfc75b537752f01f6f7beed750e7439166.nq.gz
    ├── 76e2804d3d59797a26cd86f47e23c19810db6aad.nq.gz
    ├── 773cf5093e996982b60d7695234765ac67b51af1.nq.gz
    ├── 77b433b92b724507de7720eed9792aa52b6dcebb.nq.gz
    ├── 785cceef01cbe1fd1e428413c6842dd029a7bef7.nq.gz
    ├── 78eb40184c49225345f3836c9a38f8ee53b9cecd.nq.gz
    ├── 7945a05de641f40709eed37de65b62b841ffc59c.nq.gz
    ├── 799df69ba29aa94ff134ac64e819809c96951349.nq.gz
    ├── 79cff0e65205daeb9c60437c6b4e1a359717c96a.nq.gz
    ├── 7bc7282404d4e642764cbe7fbc6aaaceba6f2c21.nq.gz
    ├── 7c7f854d021bd2f07c42c291484ea492e726b7a6.nq.gz
    ├── 7ca4f5296ab12c05ed60377aaabfd21abe377cb1.nq.gz
    ├── 7d29df4f09de99fa118478eeb2f31d7d9b632759.nq.gz
    ├── 7d2cdb342ae0e45ad625d5247a4ef4d6e8de5dc1.nq.gz
    ├── 7eb3c4a199bd8cb80ecde5dfe71b831f2d44f97f.nq.gz
    ├── 801c1e2003f1c56c519bd169b0e58be73643e698.nq.gz
    ├── 82beb17e1783cf73e0c0b7925c3386baccd43a72.nq.gz
    ├── 833fc06d1abe976f4b54ad512b9b6f57e22a7bf3.nq.gz
    ├── 8381c1fe7999226704a76024af8eff5268e834f4.nq.gz
    ├── 847fde7d2664459a9f5fd333a605ca9a77374c45.nq.gz
    ├── 8569da70efb3f40a903670fb56d4e4bc4ddab14b.nq.gz
    ├── 85e933c9e7a70534392567858a0b0fa5801ec03f.nq.gz
    ├── 863b902d4e56e6b2d9ae3168117d6bc283f2deeb.nq.gz
    ├── 8705a6a5e4efaf26b8fb0652b128d524aee016c1.nq.gz
    ├── 8787b2da4325789effcc2e0fa27f685df82c626f.nq.gz
    ├── 896b86a755f37a91a0902cf0e7ad67e6d6f7cdd7.nq.gz
    ├── 8c1a8393d04cdb1f69283696792eb62d722768cd.nq.gz
    ├── 8c31c24b6f991f6972a23824b7ccb317b208ae1a.nq.gz
    ├── 8cb20d84b43f74699465d39acf1d7ff81086f63d.nq.gz
    ├── 8d5028c2f3bdbfd6274284881a2c36f9f50098ad.nq.gz
    ├── 8d9942741ca9a549858b8891548eeb430e7a7aec.nq.gz
    ├── 8e05f6ce40a1827aba4a03391e136548a0589e5d.nq.gz
    ├── 9064d880374f3a82f40919222cf0ad60cb3d0e95.nq.gz
    ├── 90fc83bee173594f2fdcd44b501afb405d89ccf3.nq.gz
    ├── 91d27acff69408cf7fb57a4541d627bb5b10496c.nq.gz
    ├── 94436f33ca1a492320ee8685086a2e496f61f2a8.nq.gz
    ├── 976ba0294638950e865be3934cbeee3b6305ffd6.nq.gz
    ├── 9859732bb236fd286e0cfd9ebe09dc1f9906c154.nq.gz
    ├── 996ab27429126cab3c33970f04a5a829d1d4a9e2.nq.gz
    ├── 9a64fff30ea82827aaabc27989dd349f75b41065.nq.gz
    ├── 9bc319be799d1edd3d602dc00db5f80a6824c4e9.nq.gz
    ├── 9e38ed5ac6ab9e180ae572e3aa36a1e0b241574d.nq.gz
    ├── 9e76a8629953b8b4d17cd127f7c9c2e738d2a176.nq.gz
    ├── 9f4c874507a57757330b237d83eca1519050ea72.nq.gz
    ├── 9f5a24d089df9719c8e5cba919490808e4aef977.nq.gz
    ├── 9f5be4314651d4d520a48a76746890bdc916e7fe.nq.gz
    ├── a1737cd8a4aa56732fcbcd7869e1b870054c4d42.nq.gz
    ├── a21320c396eca0b6cc4dd4d7777a3fb17ba2e9fd.nq.gz
    ├── a2db011c7e8739d942dbde2f549c9960a060d791.nq.gz
    ├── a324c350d30a24834bf162c33256e8b2f41e95f5.nq.gz
    ├── a3b6b576a620b5857a0363d55f18978e24c5ace9.nq.gz
    ├── a3dba6946d207715fa3150efa8e19d12165b73a0.nq.gz
    ├── a445961b6bc7d7a1d8357190b200e6d015e6dfeb.nq.gz
    ├── a5e2dc35a8e17c0df38e74a696dc8e5e662ef072.nq.gz
    ├── a7d622583b66a5fb89ee426abd6beed5b717528c.nq.gz
    ├── aa1b7c6890ce12f157c74a9114afc87e6cdae9ef.nq.gz
    ├── aad35ac42522cfa9d248c4f372f182dcb4acbb05.nq.gz
    ├── ab3a7b85f5f04ae931246542f8ef2542eedb8df1.nq.gz
    ├── ab63e8f5e0a91267c5c43d191ca1e1e4288a78a2.nq.gz
    ├── ad4f18138ae4cc499ec5e7d68f83abf987235852.nq.gz
    ├── ad637e01e4614c2f98682897477fa57ab64ebdd3.nq.gz
    ├── ae497d874dcdf2001e89b62530da74dc75466612.nq.gz
    ├── b00242302f631fce5209c09fa2a886d9a1927253.nq.gz
    ├── b08d81513fcc98ff49c8de140f771aa61a992186.nq.gz
    ├── b15af53355d1492af1d2a5ea7c82fef59e77a746.nq.gz
    ├── b5972961e0e8824d6992a0753d781207699ca38b.nq.gz
    ├── b65ad8d10aaef52a7cffb1876a2651a9f2eaabca.nq.gz
    ├── b6db8d225e8ce5a80b249eb190e88ff2de489479.nq.gz
    ├── b7082ef310e9159bc75fcdc0c35de4df22d76878.nq.gz
    ├── b8023d8bc0ca413584a729e5106f86ba8fe65400.nq.gz
    ├── b820ec2f90c2428613eb2377ad752f13281a9775.nq.gz
    ├── b8746626961ba18e38a8e2575259b3a875cdf7e7.nq.gz
    ├── b8f609bee065bac560cb02120148bd880e3f722c.nq.gz
    ├── b91c08e67c190199b836483a0d1b3cbccaec6c8f.nq.gz
    ├── b9d7a7a1f7f631c8fe9a2dea40f721b3fe540554.nq.gz
    └── bcdd3c2ef939c9ae2e1eccc3acd6d2a4e4935017.nq.gz

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

[aio-libs/aiohttp-demos](https://github.com/aio-libs/aiohttp-demos)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
