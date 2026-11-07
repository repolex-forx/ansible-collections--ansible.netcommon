# Repolex Knowledge Graph of ansible-collections/ansible.netcommon

RDF knowledge graph data for [ansible-collections/ansible.netcommon](https://github.com/ansible-collections/ansible.netcommon), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ansible.netcommon
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6b21bb8b9ecc56d5abe0dfaddd8ef372882ab444
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6b21bb8b9ecc56d5abe0dfaddd8ef372882ab444
│           └── chunk-001.nq.gz
└── blob
    ├── 00031ed8bcfc389587da325132b60a5c847b9695.nq.gz
    ├── 0044e747f24e6b27421a3271754d394b14990433.nq.gz
    ├── 01074c89511fe521202c5c402549d6d8ec95c870.nq.gz
    ├── 017166196370e607720cf68cd1a96b3492cb0e8e.nq.gz
    ├── 02a45d2a669fa3530345a22b357bcf42f208dd2a.nq.gz
    ├── 0387845e0dfab23a2ad54d9b92cfd9b256c1e279.nq.gz
    ├── 03e5e50497dd7bfa0e7264a87e380931183243ae.nq.gz
    ├── 04239f16d827c3c333f2ca85e6542c6e0753b4ae.nq.gz
    ├── 04635330a8a05843ee0d7f0c3e3c61116e6ec80b.nq.gz
    ├── 04e6db28a8d5d263f3e40c5d4aad179e67988f9f.nq.gz
    ├── 051b5683d111698ce18b2c2a7ce0ad2b7749ac2a.nq.gz
    ├── 06fb92b559a963262a054f36d3fa6bc43038e6c1.nq.gz
    ├── 0869e8a3b01ea9d52638e700357dc6734d30a230.nq.gz
    ├── 08b0f57ed06360dc703e2221ed0f1a5165d0f5f8.nq.gz
    ├── 0a6aad8916295c9c04061e314a1b12326ffd60b3.nq.gz
    ├── 0a7dcee5172ea015e9b72b5b6715532d523d9087.nq.gz
    ├── 0b4a78de7172ba1d2a3b19922936707440c31f79.nq.gz
    ├── 0bc1156a8a7f4a98b746b5709ea3bc10143c7597.nq.gz
    ├── 0cf5d75543a1351b8204baf5bb0532aff1cbdb65.nq.gz
    ├── 0cf9b8baa869c9e021ddb9defc19c3f2560c7c89.nq.gz
    ├── 0d4e6a01f1d7536e4062db6d000245fd993bac6e.nq.gz
    ├── 0d9e6ce18a60442d9a1a258cbdf11c3cc917e4c5.nq.gz
    ├── 0e5015c5a4aa6ad49d18d44bb61ac5b65da08991.nq.gz
    ├── 0ec25f7505c14bad77f34453b2730417ab431293.nq.gz
    ├── 0fbc18107e2883e2552ff3d34f532f0c9330010f.nq.gz
    ├── 0fdf9d4e78acd2e4d691399704f50a2d0e551f6d.nq.gz
    ├── 104667ea7f612111d7fc3c1795f784f95e8cacaa.nq.gz
    ├── 109e61377a375ebaed50c03ca57d9b244d10867a.nq.gz
    ├── 11e337f284a2232cd1c059388848f1135dd89053.nq.gz
    ├── 11ed6342e0be65e7587a62819040e236a907a6e2.nq.gz
    ├── 130b68a71f16bdd7f0ce29e0e05060509ba5dea8.nq.gz
    ├── 133850c0201aba9f775d5ebfc1fc8e7d3022c10e.nq.gz
    ├── 1401406be65bb8e75edaa076e05db0a353d27bd2.nq.gz
    ├── 15474ca8e0e1ddec7f569253cfa69ecbef8c3dd8.nq.gz
    ├── 15742fd2a2cb191e4853e9c1eb68e322812d3a28.nq.gz
    ├── 16bae27758cba96e050af3cc77fc9b2e455a633b.nq.gz
    ├── 178b5f4b8371bcd079646d3b1cf26b82f690fc2a.nq.gz
    ├── 18a9769dba5d3acf2d978f02be7300b003ccc0ef.nq.gz
    ├── 1992be40f19a3de568c930235ab70149f122668f.nq.gz
    ├── 1b197fae8d661efbe55e12ae3b420a02f558672e.nq.gz
    ├── 1c1e91e3f24d26927c4db06a04aca4dd637b5c4f.nq.gz
    ├── 1cedfc45b88a13d90d088a43627d7d70cf7ac321.nq.gz
    ├── 1d394e6959a09ad7d20dbd83a6cf4b830da2cbf9.nq.gz
    ├── 1dbcfcb37eaf57ea7ffb6409bd4b60004759544d.nq.gz
    ├── 1ec406d32d07f27c67543f8148b078cb83828754.nq.gz
    ├── 1eed91e23a8c4e0437ee467e0167ed1daa928f73.nq.gz
    ├── 1f36996f8b35736cc94acc57be1d52f2a9d3caa4.nq.gz
    ├── 1ff9770fb130ca0c237633f246ffd026f6b8ab8e.nq.gz
    ├── 209239d2627dd04709d3f5859d4a95245ecabdf8.nq.gz
    ├── 21c0a3323a5e53cb26409c2cabcfc53bfafc9d63.nq.gz
    ├── 2211f1c41d6658ffe80609bbb0d3515a96848837.nq.gz
    ├── 22291f2b8b882da8e6987530e99d9379dab9665a.nq.gz
    ├── 22776103651883a4a4b1495485b223c3d7b47339.nq.gz
    ├── 2456e6967bab16b849d1f62eb5fb8025b7d3623a.nq.gz
    ├── 24612c8889e1518ab42d95cb3bd4ec9cbeb90f82.nq.gz
    ├── 279f03e175184091845c0a7df3e4a4197cb4ef5c.nq.gz
    ├── 28c9e4485e550dbc609e5f0c05dc44c4c64af0b3.nq.gz
    ├── 2ac2bc29a5962747854a6a32d44ad6f6c12b5cc5.nq.gz
    ├── 2acecd7ff6ce937ff7fcc6a93180f5c05115ab5f.nq.gz
    ├── 2c1fed0e88d17b433ec917788df7b08a28ff192c.nq.gz
    ├── 2e498419a965425cbcb30ce0dbca86137f171c96.nq.gz
    ├── 2f27ed0134edb9c346b4b6d5c73de66ce8226060.nq.gz
    ├── 307dfaa111eb1f9914ae8a91a8bcb2a0be7ff39e.nq.gz
    ├── 3097e29e3249a137afa2d69371f53c6c6e42daec.nq.gz
    ├── 309eddcb6e6b039e0e242fed7167ecaccc38d1b1.nq.gz
    ├── 30b03a8bc3be56a328d42dc5509d72a03facc9af.nq.gz
    ├── 30fdfc0337f44e9d1491824b0773aadd3b323e26.nq.gz
    ├── 318bde8d8d875ed5b93e88c5fcd82b8489376838.nq.gz
    ├── 3378e7ba5d5afdf66e74fdd6a5f63209cb802379.nq.gz
    ├── 33d40c000318e64a1dd08ff7ba7baf0eba69311e.nq.gz
    ├── 341498a9ad71304e981297341d198b4b588820dc.nq.gz
    ├── 3481269e618dafdacc3bf38c0bf9862add12c2c5.nq.gz
    ├── 34b6bff934c1bc01240cc1523afc1ff9c9fadc57.nq.gz
    ├── 34be699231788a53d217d5e49bffe8c4665700ad.nq.gz
    ├── 3576435978e10ce6118ef4b08d6c9c29860b1769.nq.gz
    ├── 3658f79eb02bf16e5d2f3ef5c5e1422bad48760a.nq.gz
    ├── 36f90c549da9485ae98817a26d07683235b59830.nq.gz
    ├── 382e1903c9677fac7ac46d05974400e2ff25bab7.nq.gz
    ├── 3915e4e9c0282111e5ed9dd8d06e7ae1abf67467.nq.gz
    ├── 39403f5418c1aeb747f8ee365add19df5d56a522.nq.gz
    ├── 3afbd67f43b3ad02a6ef0e998a9d227465f489d1.nq.gz
    ├── 3b338c2cbc08a5cd45d127eabba2aa9d5f15180c.nq.gz
    ├── 3b7645e2c502e600cf7059e4ee79bc74a6fb58f3.nq.gz
    ├── 3ce9046e8b6a6a2aa3a13f48d117faf01fa13a33.nq.gz
    ├── 3d81d0324c1e2e6e5ccdaa4d5fa5485aa9e5f0c2.nq.gz
    ├── 3de54fb6d36f35b77ad7461d7ac7792c4c2b6918.nq.gz
    ├── 3e6bd4abb60267c9ffbe8d92f747a66942dbb6f3.nq.gz
    ├── 3f14fa9997a6a5cee893bfaeaf1498c078bb8d4a.nq.gz
    ├── 41abf23bbcde475a55f2775ae2b2b614c4445ca3.nq.gz
    ├── 4283ed8affa744d97de7451b0dbb1cc745d8ee8e.nq.gz
    ├── 429e58d7115bb7da84f5f48ec915bb73d2c7f564.nq.gz
    ├── 43419d06a89bb7333eff6aa0d0e5c7a77416db87.nq.gz
    ├── 434206138a6ee58f8661f9dcb669ae4a5d38d75b.nq.gz
    ├── 447d26af00265f1e317368c366c83a242cf5b5d0.nq.gz
    ├── 470e9405687567a683192ac5cc53103e29b502cc.nq.gz
    ├── 4763ef216d5778e603b7681c9dadee6846f9e24c.nq.gz
    ├── 47f453bbc0c864321d06ef63709be17f19fd7dcc.nq.gz
    ├── 480b5db1110d1b6990a2e30b9e4ee6b770bbd950.nq.gz
    ├── 48293ca1fef270950dd9798ff96af802f3203422.nq.gz
    ├── 48f2760d2df09ddfe3899837cce35a374e129e28.nq.gz
    ├── 498444b1b2c8609e4b39ad5008de4205016db746.nq.gz
    ├── 49c0300a15b63a63f1edb14b79353b812a47776f.nq.gz
    ├── 4a0d0c303acce04a9e63476e0dec5c2481bebf9a.nq.gz
    ├── 4a7718d2d4f07ee403e510ffbb91be4987445e65.nq.gz
    ├── 4d2e55fa7b7111ef15ea45a999df2edbd4034211.nq.gz
    ├── 507076d2c361460e9540bdc19ec69bbd56531622.nq.gz
    ├── 50a6eed82ce44b6d828b5b0d6e5a1aeb7ea00b66.nq.gz
    ├── 50c2cdcb87888f3357a3757cf9da89035894df08.nq.gz
    ├── 519476d3e23e631947ad2136a8202d76ae3c052e.nq.gz
    ├── 51eb77c667fbe77767e65d5588963c1024776f65.nq.gz
    ├── 53354dadebe2ff5e4231698469ca5161f4b0c00b.nq.gz
    ├── 535260cf101db7c2f55b23f8992cfa23f9e92b21.nq.gz
    ├── 5363be21ab5d533f950c6f70b8a58fcd9558a571.nq.gz
    ├── 5367efd5a8a46ac70040cace3ee3152a04fe88ed.nq.gz
    ├── 545f0108fecf468b9a8184563fbbfc4f21dad33d.nq.gz
    ├── 54ecf68ef428bd2dca26d39d56937d977460be69.nq.gz
    ├── 555e3547d0c83a4ceab96bed0ef3cb2c529deff2.nq.gz
    ├── 5637a9a30305b20c9edc81ff3806ce201f7c2844.nq.gz
    ├── 56a374f9828a138a18b164cf4b7a3b8f8957f9fb.nq.gz
    ├── 56bef5e88f4b7a9bcf9ed644b087b56f5e75d108.nq.gz
    ├── 5727cf333b2f4b941e81315c52f0668b57a4cdd3.nq.gz
    ├── 57c1b08c2e7e3024163f0bb0a6f87259e121cfc6.nq.gz
    ├── 58a5b5439d53d00c65c2940029d8d16950f5c3c0.nq.gz
    ├── 5ae051e41d967354ba8ae99e5e1a1373bd2e33cf.nq.gz
    ├── 5bdf625d686f6fb8aaba43a2bdc6ca92c5731db4.nq.gz
    ├── 5d1dc056141af7f502659249775200a54c925fe1.nq.gz
    ├── 5d418d54fb40ec37d6e6f7a937fcf5bf92cd4e23.nq.gz
    ├── 5d6f4f2f7812a79b0b3d6e970c815073f174da96.nq.gz
    ├── 5db4bb495c458840d25d31a7fc17b512eda16169.nq.gz
    ├── 5e2bd83230646e8d80d23435d3963413118279da.nq.gz
    ├── 5ec5822a87e2402b968a7c63632726ba88689f12.nq.gz
    ├── 5f26d604149641f36796aab7f6f841f84999e10a.nq.gz
    ├── 5f709c5aac15f11a4cb08bbb627883011ff762b7.nq.gz
    ├── 5fe8a31f39c4b5084e2c245ccee123af71d9fce1.nq.gz
    ├── 5ffcfd356ac8dbd88f77508bc05f9f62348f158c.nq.gz
    ├── 6053b30f2529293daebd6c9b21a0da07d74333c0.nq.gz
    ├── 6193a638f3280471559e120d0f2f28f861e0d14b.nq.gz
    ├── 64ac02e511ca05934fba7ae58ba6b7f191015113.nq.gz
    ├── 68487bdc2c268efa5b131eeb05e5f49882a38a35.nq.gz
    ├── 68ed6538bdb9bf8eaa4949ac9eb6c491c95a671e.nq.gz
    ├── 6999869b4cae909a8e51aea7af55161bcff6265c.nq.gz
    ├── 69edcec5de4bceb5efdd48b0b28e99f12b3a5f69.nq.gz
    ├── 6a7966b2f8ebc2c51af143b347a056882f7edbce.nq.gz
    ├── 6a7ba5641f8d3271363b289d2e9d63c79f198426.nq.gz
    ├── 6c3ba8f8b000990a10f95a17a1efaac6fdf9e07f.nq.gz
    ├── 6caad5ac0751485dbdf679fe69894d8ed5999f89.nq.gz
    ├── 6cb008729117cdeaca740344aa1020c647a7e99c.nq.gz
    ├── 6cd2cab3226e3138c41e01bb51fcae28678ce1e1.nq.gz
    ├── 6ce36be008dd0dac2e656ea6d4abb01247aaca2b.nq.gz
    ├── 6f4af826aa3e242ebd561923bc5198d12417b8ae.nq.gz
    ├── 6f8bea4e530a5fe53b1af95469122ce289d08850.nq.gz
    ├── 6fba7e781ec3beb067aebfac236308f825e024ab.nq.gz
    ├── 6fe2c43ad80ed3695917f9155b12d97ba5afda5c.nq.gz
    ├── 6fe4812eace6d2b49ec7e1d314ea9eb3a0c46b7a.nq.gz
    ├── 7044a60a46339600d2c800578277e21696b5dde0.nq.gz
    ├── 71d46312c602e1f21b04fcc3643b7e47448a19a0.nq.gz
    ├── 723daf1635c4066bb91534832170d25578721cf2.nq.gz
    ├── 72d2efd7fdc7c04d8931609682070edd090af178.nq.gz
    ├── 73e321fae9bd58f5c21ca9004342619977d50348.nq.gz
    ├── 74344abd422950f6c5971c441206fb1bb1067969.nq.gz
    ├── 760f71cfbc84068319226d432003f6e966d8b950.nq.gz
    ├── 76a0c5f3cbbb4df93cde71bada0e782c3ac8ccc9.nq.gz
    ├── 77679928b5dd6b70339f4aed1cff930eea0065cc.nq.gz
    ├── 77e42ca9940ec8e1d3fd623e588fc39183dc7b0b.nq.gz
    ├── 785c2c109fa3644815ad0cfe6d32f8e2d245af5d.nq.gz
    ├── 78689723c5f96ad8f722f1567e3fb80850becb6e.nq.gz
    ├── 78b55480dcbc3063d7615256eca58b06bff6e778.nq.gz
    ├── 78e126aa1afac4f8f4c37bef67f25ac55ef6eea5.nq.gz
    ├── 7c47292c25d54cd479be68a0b284a6014c228f75.nq.gz
    ├── 7d01cc5508520c74cfaf9d034f9ce2b6496fa22e.nq.gz
    ├── 7ec545d72b7a8afb1f79271d08d58353fb056986.nq.gz
    ├── 7efab69bbc4e26e31fbdbbe10e89bfd4b2bf2b64.nq.gz
    ├── 7f7d132dda3bb327494ef4354fa9ad6397f612fa.nq.gz
    ├── 8002583a0265c550603a090351a4644d20192f88.nq.gz
    ├── 81d8da839939dae6886bc06ea6998fd577eb281b.nq.gz
    ├── 837e9c66b46fa3ee7a131322009849ce19a7ca8d.nq.gz
    ├── 83b68812eb93c7d22fd348ee46c8c1e1a3c3bcd2.nq.gz
    ├── 8417ce2e7b24eceec69992d3b2759cabeb73d12b.nq.gz
    ├── 8442a8a1d0083334e07fd7601f115237cb6a33fc.nq.gz
    ├── 84b8caba1a38287806b35ae579ceeba55834f460.nq.gz
    ├── 8688732a2c8c8619e23daace810e73947edc75c3.nq.gz
    ├── 871cdf085a01d925974cd44b93fad1111dc6ed74.nq.gz
    ├── 878c91eef44899fc82d29744aa4a8a846252b6f3.nq.gz
    ├── 87904970760a98eecfcd529c7d06654c02d55118.nq.gz
    ├── 87c0c80b49750811ccab4a303ba6c66fb82c4916.nq.gz
    ├── 8825d08ae7085a7e81b5f387dbd82c9ea41c901a.nq.gz
    ├── 88d610e927400492ea055349edbb9d15587cd1fe.nq.gz
    ├── 89751f60641f8ebacd2fb83b0b6a25d2d70c5984.nq.gz
    ├── 8a782071c512fd4138aebc32fcbd9e8a36c80d55.nq.gz
    ├── 8b811f4bfd2a9921381ff29172081a0742666c36.nq.gz
    ├── 8c70b9a63e7a2051974d9a43e0fc347a157f030f.nq.gz
    ├── 8d405dece40e1f73768366de4287a131eb85dddb.nq.gz
    ├── 8d9a1cf1f66e869c7910d285bc3d736e92bd50f4.nq.gz
    ├── 8dfca759d5aaad9c576d6a813a8984c6fe06e507.nq.gz
    ├── 8e0c436f7b0924191dea67c0bae0f1dc0cd0773e.nq.gz
    ├── 8e1182d4e3e4d6e02ea00fc32f59ff89eb16ad1d.nq.gz
    ├── 8e198576371b3fdf1f2a9ce2843dcdb5df9f4213.nq.gz
    └── 8e23d435120bb665c91b2c824b4286747b9fdaa9.nq.gz

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

[ansible-collections/ansible.netcommon](https://github.com/ansible-collections/ansible.netcommon)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
