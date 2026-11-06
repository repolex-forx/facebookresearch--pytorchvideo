# Repolex Knowledge Graph of facebookresearch/pytorchvideo

RDF knowledge graph data for [facebookresearch/pytorchvideo](https://github.com/facebookresearch/pytorchvideo), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/pytorchvideo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2ac6ed361309cb25144636ad82dd8bd6a4970e0c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2ac6ed361309cb25144636ad82dd8bd6a4970e0c
│           └── chunk-001.nq.gz
└── blob
    ├── 00e30353ba11053a8befb1397e8807eac7dea247.nq.gz
    ├── 011eaef57d58ef007eb950115068045970f1ddda.nq.gz
    ├── 027eeae3b5b36caf44af720219d2f090c3c16875.nq.gz
    ├── 038214fb657dceebb8f1fadcb0b3969427e456a0.nq.gz
    ├── 051ad318733666320aa442410782f9a56f89f572.nq.gz
    ├── 0570a2187d0ba34d3225fd8877390576f7536aaf.nq.gz
    ├── 05ba9a58f5970c3b70346a5f318ea535fff94c15.nq.gz
    ├── 05f4e03c18c2be2402e1241b4c2e907cf28c24d6.nq.gz
    ├── 06347a7ce16d855f81bdc8d34eb2f1adb909428e.nq.gz
    ├── 088a8bbb023468bd656ebc8cfc28d5a236cf258c.nq.gz
    ├── 08e5335f88b48d2f235b0ed148ef561a9037ae24.nq.gz
    ├── 096d4b0518a05f24954cc7c0763ecc3286263087.nq.gz
    ├── 0a69ef66e4bb7234d0d3ee951e7221e4d6b7a04f.nq.gz
    ├── 0a7983e9e4050b660e3a32d70d551207ead43451.nq.gz
    ├── 0ba382f089248bfe560b9f0a9f1bba7e9f5913c6.nq.gz
    ├── 0d33adfb6c640ffe16d99e5eb22d8180208ec40b.nq.gz
    ├── 0e1753b805fbe9cc8e422b8cb35d7b78621b2600.nq.gz
    ├── 0f35aa55b3f04b8c8f2e84da8bfc8ee8193ab6b8.nq.gz
    ├── 0f73488f2c148502c88d9fecfddb3c96954a3b3c.nq.gz
    ├── 0fbd539b811e5e31e8cef4a37b9a3e4bfe3ae33d.nq.gz
    ├── 1034a39d21a03902d562ce42cfcde8045b7fe605.nq.gz
    ├── 1040218d67f9572aaf517434f6ef6b6ac62564d1.nq.gz
    ├── 11aa160c26202f7f652fb620436317344ff765f1.nq.gz
    ├── 11df106a5b5ea06ade3caf4f9cfc37f4a2ca683e.nq.gz
    ├── 1337b5dbe26d01d16931b593582c6d628fa8896d.nq.gz
    ├── 13f792e7c1b61d8fab359cf8854240e8645d196c.nq.gz
    ├── 14a758d0ef94cf46731c513c384982fa5c9df78f.nq.gz
    ├── 153be1ca8d92db386b4a53f537d557a77c70d220.nq.gz
    ├── 15593d61e44286033a999c6ff2729038df406516.nq.gz
    ├── 155e13b2e77bdcd8c74f2fa27a0869a125061551.nq.gz
    ├── 16a9e4a16693b27ec46a33553250ecf1994bf9c4.nq.gz
    ├── 17ee078142b79c9c9d4669fcd53de2136d50d33f.nq.gz
    ├── 18d628201e7bde327e362b195d8dbe3fae25547e.nq.gz
    ├── 19aa4b450ece2420346c7236597ba0882c55dc2c.nq.gz
    ├── 1b9f65e2689c2827c1a61ee120641c398de08a78.nq.gz
    ├── 1bed28adf31b20c463b139b1c5f90b39d207e4d9.nq.gz
    ├── 1cace0350041d5e72196f9a28c1b4c3afbeffaef.nq.gz
    ├── 1d428802c45a9caf18f25b5b1df2b6eed311bfae.nq.gz
    ├── 2024a6bd71c5f95c0c436e65972742c063965d8d.nq.gz
    ├── 203097ea10f1c7e0b936066856704ccb094f2909.nq.gz
    ├── 218ead33b720986939ec75e1d433455df95ecff0.nq.gz
    ├── 21c3b9d028421a675dce4964e5919643ad5e32d7.nq.gz
    ├── 227227adcd9a16e04bebdac9bf3c5ffb1cd37982.nq.gz
    ├── 234ac1e5af8885f0cc20476758bb4ae7f564158b.nq.gz
    ├── 238971871ac7cd8be886c4cccfae983c4f30c350.nq.gz
    ├── 23e2943257ed76d661f1be066dc687a51a38c1b2.nq.gz
    ├── 247809704d8966822f0d324da50685b827f2dcda.nq.gz
    ├── 24d336b7d866c2ffac15f31e4c2b440b093e5f5d.nq.gz
    ├── 27ccdee6c59013f6321c59963c868678a5a030c3.nq.gz
    ├── 27d2dae2b493488b48bdb18b95af471821ece9bf.nq.gz
    ├── 288781a7a43feee352c1756a7d33831e8bae3a6d.nq.gz
    ├── 2919905a5779f2024b700ad259178c2cb9943bf9.nq.gz
    ├── 2938bed96b8dbe83fbc876f64ab4385dc7db24ee.nq.gz
    ├── 2b12bff991ceec68b84294c764fd76ac9bd51c95.nq.gz
    ├── 2b36f54e2430fba23f5979a45d4a99fe86b102a2.nq.gz
    ├── 2b7f7a741e2facc898b62fb47750344ec10afb07.nq.gz
    ├── 2be4f8301abfbbfe85af6245730d54ba3ffe9d45.nq.gz
    ├── 2cd87adf77f4e0c6ce58dc79efde5f91e92e3948.nq.gz
    ├── 2d7e5caa2a571faf233abdf3e46be924efea409e.nq.gz
    ├── 2d9a460caa9753a72236d6014047b91ae1d2f305.nq.gz
    ├── 2df3319cc0217226ec0cd66541b8df5d0b4ba995.nq.gz
    ├── 2e164fdeeb52e22ed976f9759eedd732ced19ed2.nq.gz
    ├── 2e7802e3a08ae45ad2895aee27c1630c1416a96f.nq.gz
    ├── 2f6e4a6341d28df5406cd131c8090cb7654cddcf.nq.gz
    ├── 2fb037e2d83ef4e8e54414d44f4c448b4551bf0e.nq.gz
    ├── 30de2bb86fb6f556c05d973f48b9e8a654158e66.nq.gz
    ├── 31677003b05386c8c41d614fc93fedb546d1ac8e.nq.gz
    ├── 319d1c3f17c2e3882fd5890166a50f0534c4310a.nq.gz
    ├── 32572baad88bf69ffd650069b021490f090ede72.nq.gz
    ├── 3334d47c67b4c1cbe821ddcb89699d63a91006ce.nq.gz
    ├── 352afc06d0c0838233186d04c817b8b04d4d66fe.nq.gz
    ├── 377302f7f4a1d49e51e0664914e1dc4d5ef805e0.nq.gz
    ├── 3805e2466140ea12b528254b97abad9d708d9536.nq.gz
    ├── 3905092fb07f50da2bf9259e6c2ef739bd0ba2b4.nq.gz
    ├── 3a6309e4a30e2f12dab03b94273d98ed17a2e888.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3bd1cdad7c874be910f98ddfd037af1f47a9f22a.nq.gz
    ├── 3c66a007b018d8082f4d0f3ddffed58042cc2c9c.nq.gz
    ├── 3d8055264b60effcb0037d81787b94224fb953df.nq.gz
    ├── 3e08e45b271337f44d02fe86b3bb2e7addb4da21.nq.gz
    ├── 3e5f6655bb35ebe933bbf7ea220c30bbbd2e661c.nq.gz
    ├── 3ea3f5f2ae19490a33932f85d0ab9da2df46576f.nq.gz
    ├── 3eaeb9d6eb66edc52d69a420a732e82cf6c29f58.nq.gz
    ├── 4019e18a283d34e9fb81beb126697432f2be1e8d.nq.gz
    ├── 413796222b1a0e70b5229df7a3b1f7b04003e7c0.nq.gz
    ├── 4208b9a53ea25c22ce785e0f14566cddb8cf3306.nq.gz
    ├── 422bdbdf58ab7266cd488fe6867c50b2a4df14d2.nq.gz
    ├── 422e042b29ae6d2c482e2944178ae30f60acd1f1.nq.gz
    ├── 42827de298d566c60490631a79ccda3d72c3c574.nq.gz
    ├── 431c0e35794bae877e9ce5bdd32887f7d4e0fa4d.nq.gz
    ├── 4390d86b39837b7ada1af970067ac330aefa9bda.nq.gz
    ├── 442b2ed30f4f186557e7b00468a3f7c9f098b7c8.nq.gz
    ├── 4434abc75937c24cd7e5e6bdb98dc90b4090d20d.nq.gz
    ├── 44775f7a5e45be7042c153055f6796cc2f143465.nq.gz
    ├── 45e74d12bb06a6c36e665d06f7e1c0922f3a0bfe.nq.gz
    ├── 46886c3384324a362bcb3411eeaa2187433eca49.nq.gz
    ├── 46dafcf1000e6f76077d686b219c1063772c9d7b.nq.gz
    ├── 474a80cb6ad7980a0087569c68664c02bc47a5db.nq.gz
    ├── 4755f6e3de205c65552b39143754873b29e65d60.nq.gz
    ├── 4828db67810cc3e314a8f96c41b8bac23efb7699.nq.gz
    ├── 488bae54e3aba8ca00ad7b8ff5b1e4db0d2f45a5.nq.gz
    ├── 48ae623e9cd15054d70f9ae4ba882107d1b097ed.nq.gz
    ├── 490c547de7311c3e4c7faa5ab99dec1484cbd4a4.nq.gz
    ├── 49666c44bef0c26b1371eced264b12a7e1ba4fae.nq.gz
    ├── 4991702b9071f3037ad97413313cf8cd19ae0fda.nq.gz
    ├── 4ba9177f5e61bada524a41bbd03ad005466de804.nq.gz
    ├── 4c8784600cca74f64bd46681d186e3a616c4e562.nq.gz
    ├── 4c8ed3c0bd1ec0daa503da343c40f259650242c3.nq.gz
    ├── 4cafa3a8aaa70720c912dc01306bce6bba350db0.nq.gz
    ├── 4d333b9d9d6b44f4f3dfa8a0690acf0eb46935ef.nq.gz
    ├── 4ea90a7ccbbdb5b8db68eca43eda222998a9016a.nq.gz
    ├── 4eab852421200f16a8b31829848e594d1baeef06.nq.gz
    ├── 4f3d7f61a4969aad19c684d588feba22cdd713c5.nq.gz
    ├── 5143209989eaec87959b18a835df24c51bb3bb00.nq.gz
    ├── 5385bb06ea15356d80d42bc99df9f814a0c3d617.nq.gz
    ├── 5388fb052d588ea689a838091319a99b474763de.nq.gz
    ├── 538a8f8e30199d1313436c54680fd6a18a53900b.nq.gz
    ├── 5395ea795d62b04c6645f5746b9cc667d26a07bb.nq.gz
    ├── 575f6823e4762f1c5ad7dd4ff7229a51537eb6e4.nq.gz
    ├── 58fb13510046b432a53aec5342c32fb0161b59d7.nq.gz
    ├── 5a90478a33957a01c8b1c16fb4d9bf8d0687affd.nq.gz
    ├── 5ae85dc04011e6c1463ab0fa1ebcbb9cd1b2ea44.nq.gz
    ├── 5b348da7eef66f3258b7a3d63f64bd54a9f4ef05.nq.gz
    ├── 5c7475702c2d9b63b62d9bdd7e7de8f86ac83b4e.nq.gz
    ├── 5c7f19c6c00a4ac3f2f2bc66f892e44bcbd72612.nq.gz
    ├── 5d15b7c1e273e2e9a51a41c99474084e25dc0899.nq.gz
    ├── 5d246c91f535daa60745f3833d9a5d6442ec697b.nq.gz
    ├── 6007439a284135ffe6cf535d223c7085d41c1a3d.nq.gz
    ├── 6077517b79adee65df6c0ca3d5d20d0f38ddb002.nq.gz
    ├── 6168b92b04077eb96a6e4ce87f33e91b42008df8.nq.gz
    ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
    ├── 624aee1aba9783dab06c632a93bdd16bb71d5b1f.nq.gz
    ├── 641cdbd502937ca2feed0948b971b16e920e8761.nq.gz
    ├── 669a328d64bbe10f3ede3961f313979a377fb48a.nq.gz
    ├── 6a32afa17fe94364b78d0f53b18e64555b9416d1.nq.gz
    ├── 6b5d7937e03e500bd99fb5dc47917b4787b88327.nq.gz
    ├── 6c3b6d91f3dcf1baa1fc8e5f337fc469e0a9b0ae.nq.gz
    ├── 6cdb36463ea3d8a909355c314210260d8fc590fb.nq.gz
    ├── 6fa824c067080996c66b7f20fab72d4d08c2c0bf.nq.gz
    ├── 6fbb2863dbffd7798a7b3e1adae70c307f16b528.nq.gz
    ├── 7028ca8d778067fd2def388e9c2fd10b9422b268.nq.gz
    ├── 729d15104e9d4135c456fdd8d731a6fe74496ec9.nq.gz
    ├── 76bc0d4db2580d0fd50f3275620bf1fca0b03879.nq.gz
    ├── 77494b33ea2707cbd02b41951d19d5c069777cfd.nq.gz
    ├── 776740c4b1b0e28142e31062ac1fe3245174dd7f.nq.gz
    ├── 78556e77f78408da7d8f7c751d4561bd83e85077.nq.gz
    ├── 786c65c5db827ae2f1933d4c505303bfcb8aa5b9.nq.gz
    ├── 7924a22a5e24c19197dcd41fd2436ea69d36e20c.nq.gz
    ├── 79fd2f3d7f0ff4bd3b7620f0752c95a4ead2b63d.nq.gz
    ├── 7b02aa73ad4e4fcf675a92be3fa45e38fa9475dd.nq.gz
    ├── 7b716ff843e5cae423ff2129a77cae9d000aac04.nq.gz
    ├── 7d46a932e3e82a503de6c890a06a849053420858.nq.gz
    ├── 7d5781ea587ad18c01302923271a952ea25c286d.nq.gz
    ├── 8023e10b8721a3df08bb623113dc6ba977cd51a8.nq.gz
    ├── 80dc2050a26867692993867fe73d64f1b5f27c5e.nq.gz
    ├── 814bc12cba68d8477cd2ac79669de9775f51caac.nq.gz
    ├── 8183e289b139e5d03ff9870d3e6bfbcd968a5edd.nq.gz
    ├── 81ce0aa5716b2477da24ed2bc478079c9cd866fc.nq.gz
    ├── 830841acb809eed3056c2eaa5e58583ebfe022dd.nq.gz
    ├── 8619ab01f809457d644138040af300d666efb5f9.nq.gz
    ├── 86e4813666fb558d2c8d32c56b1e721770b8e1f6.nq.gz
    ├── 870b06ed0d43212a5a1b4aee674a0c48a1116df1.nq.gz
    ├── 877c3814bd25d4d63608e8c3cd2942ed6f3def4d.nq.gz
    ├── 8796154e40edddd3bfc23f49ba6bfe5b1bb5f329.nq.gz
    ├── 87ca47f3f3f9284170e1dd9093eb975bdb14f0d8.nq.gz
    ├── 881d67208a6b3a58b762b6236cc535f296ae9021.nq.gz
    ├── 884870bb25cd33fc12e18fc5fd23af61c879bf3f.nq.gz
    ├── 89b2a740c457384ce0df1df25f554c4ec657da1d.nq.gz
    ├── 8a4a608d68a398d23a21a475d959836cafb382a2.nq.gz
    ├── 8a6ad5e6d8172aac8977abd5b338b68d83102f20.nq.gz
    ├── 8bbd4268953b53337c25ae6fe9f89871269cd833.nq.gz
    ├── 8cdc2238327c38df2d926541c09c1df367903eb8.nq.gz
    ├── 8d5194ff20ca0c087a63ac530ff46a6ed6dda7ba.nq.gz
    ├── 8e1ad4371e4e2bb48b7842ef8ec6a4ae5238c69e.nq.gz
    ├── 8e9523815a58dc214ad1c956979dc13865c2045d.nq.gz
    ├── 8f948ac646b860194184e5ea3d17d9ad284059bc.nq.gz
    ├── 91fea054da21d7fabc21dfdbac7c79c359b545da.nq.gz
    ├── 93c96367c0505605190f21a3e253b924866c1acb.nq.gz
    ├── 946be3a44a6b872940ece4af6ea53a3d6f019d25.nq.gz
    ├── 9542b05e79fa0d1313516b4834520b391572e0f1.nq.gz
    ├── 95e898e22933cf92dc195573361e860e2a5e9074.nq.gz
    ├── 962b54257eb00a0b1b03e6cac5d1bfdf1dd9a2bb.nq.gz
    ├── 9656bec4dab3320ae8ae79f0c49ba509bfdb5ca0.nq.gz
    ├── 96f9deb972e2f0ca65e9768c4c1e20b9c07f83c7.nq.gz
    ├── 986f1a0750b9c44ae52297ad68b8da878c54697b.nq.gz
    ├── 9a53d1af2c41ad552a75ab4efa1fd6be191644da.nq.gz
    ├── 9b0934d86fe5a0b7dc0f552c6d722e0b00d4b451.nq.gz
    ├── 9ca47842b611eb8a1fa6851b7e90216b70c2c5b4.nq.gz
    ├── 9d406fbdd50ee22e0704adfdd7273e83253b2958.nq.gz
    ├── 9d6edea269d3c5dfb9d45261296252225ed646ab.nq.gz
    ├── 9d87ba47289a9520943a4fed3cf73a1713ffd593.nq.gz
    ├── 9d9d7c228c92e93dca3ca889ed62c9c8350ab955.nq.gz
    ├── 9df08ca8b3fa19384fdafb6a6364d327de4cc493.nq.gz
    ├── 9e0213f99223cbd5551b867fed955a4fafed8a77.nq.gz
    ├── 9f798421628d59a646152646959d84228ded5be6.nq.gz
    ├── a0dc88342243d9c86872a5a1d9ec9ab1a5483f19.nq.gz
    ├── a204081c85c1acb7cae2de87d79c64ad444e4fa8.nq.gz
    └── a34ff7ccfe52298b2df0d03ea60a56135d7254ac.nq.gz

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

[facebookresearch/pytorchvideo](https://github.com/facebookresearch/pytorchvideo)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
