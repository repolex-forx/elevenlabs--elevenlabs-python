# Repolex Knowledge Graph of elevenlabs/elevenlabs-python

RDF knowledge graph data for [elevenlabs/elevenlabs-python](https://github.com/elevenlabs/elevenlabs-python), parsed by [repolex](https://repolex.ai).

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
rlex download elevenlabs/elevenlabs-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 152f737d51767ca076c7341b290f157685dc1002
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 152f737d51767ca076c7341b290f157685dc1002
│           └── chunk-001.nq.gz
└── blob
    ├── 00d3a3342789d6396758fd08ea23becae463710e.nq.gz
    ├── 00fdabdf1c1ab55680a34dffe7647934420580fa.nq.gz
    ├── 0143e625f7a47fcbc89e726a053dc17ffe921ab6.nq.gz
    ├── 018ca0ffb4e1903e5320f38662908b312894f6fa.nq.gz
    ├── 01cfbe0b76e075f556b7ebcc777d293630cbb881.nq.gz
    ├── 022b0763512c19491abadb25d5a700e9bd91177a.nq.gz
    ├── 0236aa2f767e9f98ac54ac5a12765f0171505f45.nq.gz
    ├── 02882ffc6e293592616ad51ddc6e520f6bb09de9.nq.gz
    ├── 02d421b1b30481535ec4fcdc53e8622efff31a6f.nq.gz
    ├── 02f4ff1577c14ebf26895951ae87ac5200854f8a.nq.gz
    ├── 03520d038e833244c0f3a99d384d002595750386.nq.gz
    ├── 03b60f018006651695a3ea3ffa0178fb91cc5cd3.nq.gz
    ├── 04c9470854c3e63ea4beaf8c627b7934bfef7233.nq.gz
    ├── 0681b01f206162026a0828b2b952a7a98a83aaed.nq.gz
    ├── 06b05b2eef66024a6bc68e6db9aa90321e657a32.nq.gz
    ├── 06fa52bef02aea9992b5ebf9d3491d399a50ee6c.nq.gz
    ├── 077c7e4fe1bbbf130e59be8d6616c98c9016270c.nq.gz
    ├── 07a0609d5c4545002b871132218e4b7ff203bfc1.nq.gz
    ├── 07d7e45b85a17844bc95f36afaf0e614ae225950.nq.gz
    ├── 080c4d91ed7ea3ce03c7d017d3efffba019de8d0.nq.gz
    ├── 0813c11cfde14b8e60a2eba5af0917865c1f7707.nq.gz
    ├── 083a7ab6b596c0c66d2563eb43b971bccdb1f9d5.nq.gz
    ├── 08e08ac97c0a7cf2af2b9737011cd1d3e849b45c.nq.gz
    ├── 0a0441f2d8d934c514c2273938100cce55739e69.nq.gz
    ├── 0b9f676cbd49864952d21a90ed76d55bdc5e8ffa.nq.gz
    ├── 0bec3a77cdbaf38a47805c7726978a25f8c197c5.nq.gz
    ├── 0c6a53a832554b89edbd0e2efd07678421cdfff1.nq.gz
    ├── 0c72dfc31d529c7bf9882e6a2d99a081626e3e4e.nq.gz
    ├── 0c922717559dddf7ac91f7dae76f7871a79374b8.nq.gz
    ├── 0cf4a2a7d48e6f99a04aa4d3c519e5dcdb00decf.nq.gz
    ├── 0d4c3c187248778505e203f27cef1204500a9fbf.nq.gz
    ├── 0e04d98f8a0fa9db9453fa297300aeb1ce4677ec.nq.gz
    ├── 0ead222b8fa24050fcd122bfceeeec3c5b5dd484.nq.gz
    ├── 0f859cc54be0d9a657605eecf3a4cc033b4f041f.nq.gz
    ├── 1024c242316fdb12b5b4c007a73d003f5d3b4abd.nq.gz
    ├── 1026cd964e66be81146a8e6b72fe17de11d1592e.nq.gz
    ├── 104859edb8c808820c5c623d6148bdb0c0ff1f0a.nq.gz
    ├── 106d34e2e81724d1388038e938ed1241365d509c.nq.gz
    ├── 109cd979e2dd041114bbc525209c97e3c8adeb10.nq.gz
    ├── 10bbe465f451f25d9171e08eafb6c70646a08917.nq.gz
    ├── 116660bc57d6bf531faef799e152fda5b1918777.nq.gz
    ├── 117194645a1e239858a080b88c3c316560d27472.nq.gz
    ├── 12224ec83d24ea1812b89a3c188fefc039d6c9fe.nq.gz
    ├── 131f22ac465d7d89547579c74e505c6ea87d43fe.nq.gz
    ├── 134b0a602cb2dfc1be3348acf087d928b1190f78.nq.gz
    ├── 13e2138d34fc94ab1b2ab2333b6553626e4cffaf.nq.gz
    ├── 13f7f1fc79030c2224d14c9a07e078f1735383a2.nq.gz
    ├── 142285193ee470ad5f67ad0cc010bd2e333871cb.nq.gz
    ├── 149875238d1158333a93d3bdcb0651fda97a0113.nq.gz
    ├── 14dded8c832019bf2692ff66c13744c0a448b8c6.nq.gz
    ├── 1510d7540ae888a3d46dfbefca2661396c24877f.nq.gz
    ├── 161c448e5cbbda1c5c6801b995c437998d50176e.nq.gz
    ├── 166d906914adc9f6b4e7c22360fccdb50f9b36b6.nq.gz
    ├── 1692a4532b5c24ad32d27f8250c5671f7710932d.nq.gz
    ├── 169557bb94903398e50e13c25ae9cb0055e04edd.nq.gz
    ├── 17a5cc3923ac3099fd2634941875270ee33600f1.nq.gz
    ├── 18d4e2d02a9a6c09b484379fcc0827de0a5c01de.nq.gz
    ├── 18f6663398d0050ccb94bfde474cada7976fef78.nq.gz
    ├── 1a2f9f490131b6be132497339fd0bede58feeca2.nq.gz
    ├── 1af93ca83591dab423256ac4c3a638c041b5fc33.nq.gz
    ├── 1b9e48445bd3fb3bb176ae022b537b968b1b31d3.nq.gz
    ├── 1bb4ed2417fb85055ae12d596c2ac11acb3f513c.nq.gz
    ├── 1c801a4bc08bb1e0c42e59f978ad275f4656a150.nq.gz
    ├── 1cab5d638dd7b4d2f7081d04e865539843da2611.nq.gz
    ├── 1db5af2bdb5c199234fa021c0bfe560ef22da99e.nq.gz
    ├── 1e23e59c319a3bb15634473de50f0166862eb1f8.nq.gz
    ├── 1f40fbedee94b5cb7d70b00e4cc4c13da01f9c88.nq.gz
    ├── 1fea851271eba82311fa48aa4a38062d6303b37e.nq.gz
    ├── 21530a1b6beae39831f1eab8ad7136c178b7e3fd.nq.gz
    ├── 229104e1e09b5b08e96ae88cfd8d9687200956fa.nq.gz
    ├── 2303088ad7b01d392eb80f28f281e6a0d13f4534.nq.gz
    ├── 239700a8aa41dd05cb05091a1f25239fe25a3c47.nq.gz
    ├── 250b9c8b9bad141930762b86bc1eeee340315a9e.nq.gz
    ├── 251aa1735a62c96fab56adbae829b688241cb2c6.nq.gz
    ├── 25769f721830b335499d6befa0aa88879f093338.nq.gz
    ├── 257a8446ea56a5fa2615adc0e119012c313fca72.nq.gz
    ├── 26a3b5caeda7d3a3f0c9693c85c0bcef42f87993.nq.gz
    ├── 273325892c6689ecc1a89337436a72b93bbe9968.nq.gz
    ├── 288061fc198766c4ff3b7d484073d45f1b56965a.nq.gz
    ├── 28aaddcc245725d3e1759067ab7208eaa10448ff.nq.gz
    ├── 28ea4d97182132ba506924a02121a81eb8bcf125.nq.gz
    ├── 294360c8bf32f1be05d86ee597d91e8cb19437a9.nq.gz
    ├── 29f37aeb4fd655281ff59339fb4d1a4771555542.nq.gz
    ├── 2a954d82adc250bc94ca0e87472dcd867adc2bca.nq.gz
    ├── 2b0bf9463968dfdb9d96921fedbf3f8abf45389b.nq.gz
    ├── 2b98d50b24f89dfc21c8d22cfc4eecb72f01d215.nq.gz
    ├── 2bb71e76745a694fdae43f54c275034c76501d4c.nq.gz
    ├── 2beb4433da05472e0c24e0b8449d29f109d5520f.nq.gz
    ├── 2c5cbefe7ac89941342a3d58e1dbafb86e0645a0.nq.gz
    ├── 2cb6a8bc2d712efc90912ad42b38af01e9432ed2.nq.gz
    ├── 2db2e0846cd1c002622cfd9a5a76115f89cd6e5b.nq.gz
    ├── 2dc83b3d129517a6b2bb846af32f851e890062bf.nq.gz
    ├── 2e0fa9eb57b0eca4725f1d1419deec5f5dd123f0.nq.gz
    ├── 2f0884cb07080d9105af6d7d2e73659b07390b0f.nq.gz
    ├── 2f846a06e524a158ee5ba088d6a804b093fc65c1.nq.gz
    ├── 2f865eb4aa0b9a428a1510c7fc60f54c6c56e600.nq.gz
    ├── 2fb75589fa0a19f0d6452431de6ac46479d15ccf.nq.gz
    ├── 300f161bcd3f2c3cd38d21c02be89f110921521d.nq.gz
    ├── 307b55fd1b5a044e5b4d81cb65d1d09a60af5657.nq.gz
    ├── 30a9a210dd59ba6b2db11404d49125f3533b78b2.nq.gz
    ├── 30ade7f47a97fd99442f88790062fe85faf1201c.nq.gz
    ├── 30d3105c2bc6c77a48e241c73206e031db88ffc1.nq.gz
    ├── 32790d470990475cdb25b60a81b1247cb05b96ab.nq.gz
    ├── 3289a9cc6c65ab5a6640dec4cb99b0bdddf85112.nq.gz
    ├── 3435d8a8d72a8eb57e3598fa1437e3dceacb8654.nq.gz
    ├── 35dac06500107919124c3c685859635bce3e9c86.nq.gz
    ├── 35e4e5582e1a8abaff10a926b17dc4ccb9f365ef.nq.gz
    ├── 36d03bc792d84e30af8f9c753624778c7128a9ff.nq.gz
    ├── 383206bcc5b6721b1ee3033f0fe2902ba5446438.nq.gz
    ├── 3869962f92aad298a95113edae466e01c30e9def.nq.gz
    ├── 38ce6ad8875773c20a38cf633d4aacb6db31cc09.nq.gz
    ├── 3944f73a0fada3e037b06e2ccf9b47762513c814.nq.gz
    ├── 394743519b855fdd0fede8eba4f710b760645a47.nq.gz
    ├── 39fa5a59e2f0b8cf8f38a081fecb25c47f6e48ab.nq.gz
    ├── 39fedc47bef27418e5bcc09a795287f4bde70f44.nq.gz
    ├── 3af3a93f3157f4f5c605439629afb321b5a84540.nq.gz
    ├── 3ba1e2362be3ba1acb13eea875a048f763aa0b71.nq.gz
    ├── 3d4ff95d84f0b1eff9e718b742c8460666f39924.nq.gz
    ├── 3dd46bbfe66cb94df95b0685efe06cfc01e54d66.nq.gz
    ├── 3e119abee86c64e2753026f9c9d4183785ac166f.nq.gz
    ├── 3e71e7db63377c7e484bdf09360a04bc8ecc10ab.nq.gz
    ├── 3ef7fbb332cb0dee4006ef837a903327cd8bf640.nq.gz
    ├── 3fdbca48cdcd524f036f57338c7bebd51d8cd9d8.nq.gz
    ├── 4096417ed08817dcfcaa5dc1e55e699d00051d6f.nq.gz
    ├── 40db016089ff643b20606fa2239bf6df7c395791.nq.gz
    ├── 41789c94834abfc794f9f6417e44a98801ae3331.nq.gz
    ├── 41d39079c92c2c167059665b11f78b01de65554e.nq.gz
    ├── 438644222c20be7ca2ac7c623027c6518442e582.nq.gz
    ├── 43b6ec7fa660a88ee4f6740bdc78fa3e5f1a0365.nq.gz
    ├── 44b0d27c08952bcf507d01558ee469408c8d9abe.nq.gz
    ├── 45013c063e379796353f460bc840b1864318f16d.nq.gz
    ├── 4529f472b0278893ca1fbb920248e50e05ce990e.nq.gz
    ├── 453408fa9e62accc19ee4c8a96afca47e780b1c1.nq.gz
    ├── 45c25e9d940887c087bef277d5a6fda9855cb773.nq.gz
    ├── 464f25f5cd83d9995c0ebd1429ce0c2fd7131422.nq.gz
    ├── 477b0723de75354160810136660324751d86fa42.nq.gz
    ├── 48d241ffad8d531ef281bcf4d8044796536ca696.nq.gz
    ├── 48d86e72fd5107adf41c6a95bbfc83fd7d14bcb0.nq.gz
    ├── 499ae88740e602f12d56e3a982d044b584ca305b.nq.gz
    ├── 49c5aa850c2a6ef0ae059e2b898a906e3f2c81e5.nq.gz
    ├── 4c4f3ef559c397cabf3e26270414a814b3b6f743.nq.gz
    ├── 4c74b531c9ec13f476823586443c0029697d639e.nq.gz
    ├── 4c7cd2e59b84a704d4c19e10465ade4568a5ad99.nq.gz
    ├── 4c881b66085eb22d6f223afaae18f07865f97471.nq.gz
    ├── 4db55d7429379225ec93ec42b1549649c62449bd.nq.gz
    ├── 4e2a5cf75173ff0d05b3ab3723ad5de58a132c72.nq.gz
    ├── 4e309a945d13b4da4c8ec2fe4e71913056079fb9.nq.gz
    ├── 4ec0bb8ac997c65291ee37f8e5a1bc70dd59cf28.nq.gz
    ├── 4ec24e6dd1d772d2c2639dda2c1e0407ad46dc29.nq.gz
    ├── 4f581ab6f2cc8499710ff29ae37062988aacf68c.nq.gz
    ├── 4f5f94e55ac88ec16a491cb1361904c78037b2b4.nq.gz
    ├── 503951fa6aa295a36e39cce21b648a616eab25fc.nq.gz
    ├── 50b5c15616b4d23213f39126d2a22d2ad71025db.nq.gz
    ├── 515a6ee8fc907e09fd14cb032a54c5a8e082f4a8.nq.gz
    ├── 51c0952b346cc7038d603b42e44385cd63c6dbe2.nq.gz
    ├── 521e234499ae93f441c196747d998b3e3dd098b0.nq.gz
    ├── 5269868727f16aab390bd25e4f2a3255d5f01e29.nq.gz
    ├── 535f605801db8f28d7694f4218b8dcd821579b74.nq.gz
    ├── 5369eeda3e69e313268156662184f2f745dacf4f.nq.gz
    ├── 543a8cf922a66441cfe35a71e7f76ea9115f86ff.nq.gz
    ├── 549d08e99745d0ee7bbbba374df0a7797af69fd9.nq.gz
    ├── 5612e539e80c99e885c62a2ef4eb29cc6bf6ef7e.nq.gz
    ├── 56526052c0ef20cedaf3635732cf32136490d18f.nq.gz
    ├── 565dc821c961ff183175ab7a94854655d27d7e35.nq.gz
    ├── 5695bb72b7251f44e1feaf2c008559730cd5b1ba.nq.gz
    ├── 583035d9c6f28770545845372fab7cd9787fc47d.nq.gz
    ├── 58b9bfc801de9f927272e8953a9d581b51ceb110.nq.gz
    ├── 58cb2c5686a498ef0defb00938bf48993a18de91.nq.gz
    ├── 59df0e626c0fc0f05d5c6012ad93aa378bbfe92f.nq.gz
    ├── 59ec98e329322a51d8fef20f1be3eadb20104cd4.nq.gz
    ├── 5aff89d9c0224873258b7863686fdfde1ab35bc1.nq.gz
    ├── 5bd4e680179bec09fd0face061c7cd149c8b8c0e.nq.gz
    ├── 5c59eb5cab3ef8b47b2f783b2f030955d9e5e9ef.nq.gz
    ├── 5c84b46f3220488a337fea27537a201633edafa6.nq.gz
    ├── 5c89cbc8ee853c1ef72decd1cd6dc85757630d4d.nq.gz
    ├── 5cde0202dcf357bdc706ddaddb2b07a9fe49fffa.nq.gz
    ├── 5d4b1db70416cfca88dacd379143df651f3e4435.nq.gz
    ├── 5dae82b0c831a892ac6e0aee7aedab280fde718b.nq.gz
    ├── 5e092af6d30e2ff87a2842a9a9e07d7230d247b9.nq.gz
    ├── 5f00969ce3a5a271d4e900a466782e57efa2fe8d.nq.gz
    ├── 5f6e48aca2c145319ad2ac6b290b3d47551d854c.nq.gz
    ├── 5fabdb183cadc3d57ca9726ab6d500843dde8657.nq.gz
    ├── 5fc3639eaddd0bb8b25403df014ebe8768d03787.nq.gz
    ├── 5fedb5bec45fe7e00afdc94f31b3c00b016e8067.nq.gz
    ├── 600398634a02e6e3fa74812c2500fb47b903144b.nq.gz
    ├── 6008b8098d4c81f8e50f63419c489498d33dc1da.nq.gz
    ├── 6070e5532432f4af1b528196c43432f9f8622226.nq.gz
    ├── 61ca1c722f4d0b2d0ac1f62abd3a8c93f97973c5.nq.gz
    ├── 61e8b8e83e09ebae84ece3d48149bb1c627f41b9.nq.gz
    ├── 61ec6579434518cc7cfaeaf5bdeba9017e6f3a56.nq.gz
    ├── 626c0b7c5ac0aa4d39375100bf242fa127e7b02f.nq.gz
    ├── 62a667d74cbd4c8767932d37a41a8af8867ed2d8.nq.gz
    ├── 63238cdcd1a09532489892d93aa47cd1a6ed4845.nq.gz
    ├── 639d8cad2ae4b0a27a927019ddc36b96c672e454.nq.gz
    ├── 641d2e2a50822a5c11effe50ef1b0d85ec6be503.nq.gz
    ├── 6427a4754910ccbcc60df4528a7886f7396edc6d.nq.gz
    ├── 650fe61dfb13b592c0f3ca6eb93e8fb86bbe1a99.nq.gz
    └── 659416376edb4e2889442226b250b5cf40d7ee5a.nq.gz

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

[elevenlabs/elevenlabs-python](https://github.com/elevenlabs/elevenlabs-python)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
