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
│   │   ├── 152f737d51767ca076c7341b290f157685dc1002
│   │   │   └── chunk-001.nq.gz
│   │   └── 8af73bc840511d5f279603ba8f43018a116df661
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8af73bc840511d5f279603ba8f43018a116df661.nq.gz
│   └── repolex
│       ├── 152f737d51767ca076c7341b290f157685dc1002
│       │   └── chunk-001.nq.gz
│       └── 8af73bc840511d5f279603ba8f43018a116df661
│           └── chunk-001.nq.gz
└── blob
    ├── 006e8188006fc859fa18f90967cf696d515872c2.nq.gz
    ├── 009268b494ff46cc3b8c37ecffffd257f435b02a.nq.gz
    ├── 009b9151dbd2fc662dd1ce85f77a21d1bf85daa9.nq.gz
    ├── 00d3a3342789d6396758fd08ea23becae463710e.nq.gz
    ├── 00de6c1efbf352001e18b434e1bf9ef2e2409efa.nq.gz
    ├── 00ed93233dc1e6949e3bbc94228bef4192610fe7.nq.gz
    ├── 00fdabdf1c1ab55680a34dffe7647934420580fa.nq.gz
    ├── 01011b73d78911cf97da0e9242a9509d73b56513.nq.gz
    ├── 01155a1435144fb453e1fec49f7c38f2f9332e89.nq.gz
    ├── 011ac3bc2f92ee5536f95ae83a55b013b715343b.nq.gz
    ├── 012b9955db717f5b045a857e4a3c2952b571bf7d.nq.gz
    ├── 0143e625f7a47fcbc89e726a053dc17ffe921ab6.nq.gz
    ├── 0163bd650b4a6b42d77e4e8fbf6c2b9c76ec9b16.nq.gz
    ├── 018ca0ffb4e1903e5320f38662908b312894f6fa.nq.gz
    ├── 01b1165ff49a6a43a5f40dffd0c83282cfa43d8c.nq.gz
    ├── 01c718e33bc8e3497c10595a5c0e3c939909c515.nq.gz
    ├── 01ca86a1b5e67c8cdf5c41ec6f10a0c76c66a8e3.nq.gz
    ├── 01cfbe0b76e075f556b7ebcc777d293630cbb881.nq.gz
    ├── 01fb743392746d0bb5323bbf92a1962ce0c83fe1.nq.gz
    ├── 02099b5de5e7ee55d2cf58b60e4af4deac453f24.nq.gz
    ├── 022b0763512c19491abadb25d5a700e9bd91177a.nq.gz
    ├── 0236aa2f767e9f98ac54ac5a12765f0171505f45.nq.gz
    ├── 0249a17f0c634e4d30cb0fb3d0802f0ef7781d74.nq.gz
    ├── 02882ffc6e293592616ad51ddc6e520f6bb09de9.nq.gz
    ├── 028ac36a9673ebd1192486cb25dd3f141fcc94d9.nq.gz
    ├── 02be1f5190d101eaea60bd27f5cf286836c2c707.nq.gz
    ├── 02d421b1b30481535ec4fcdc53e8622efff31a6f.nq.gz
    ├── 02f4ff1577c14ebf26895951ae87ac5200854f8a.nq.gz
    ├── 034480562dd2582cf20e4a5e71be967e0c9805ae.nq.gz
    ├── 03520d038e833244c0f3a99d384d002595750386.nq.gz
    ├── 03af00150fbf769b6f00a6aaff55dd27ca5306dd.nq.gz
    ├── 03b60f018006651695a3ea3ffa0178fb91cc5cd3.nq.gz
    ├── 03debd3f50df2232b5728d6e89dc02de0019c7f0.nq.gz
    ├── 03ed6915b3c8e0dc5b260d082a887cf2fade4e6a.nq.gz
    ├── 03f010799c2f17f2301b13c6e26a54eccbc5a7e8.nq.gz
    ├── 03fe2b8b08662076b272d6a1c4ec224ce9198127.nq.gz
    ├── 0438bc05d8c068581b9a95edf3baacdf46528dd9.nq.gz
    ├── 0477a455003cc26357a8f0995a4aaebd76d05e89.nq.gz
    ├── 048cd2673a9fb11720e94ba471925341db247cad.nq.gz
    ├── 04a90ca4124bd5f7b1b85041676e1bda6573058f.nq.gz
    ├── 04a9f34b5dcef2d11a2cbfdf486793284d8e146e.nq.gz
    ├── 04c9470854c3e63ea4beaf8c627b7934bfef7233.nq.gz
    ├── 0515a65eec094d34e6cde1e7014eb11ad5885067.nq.gz
    ├── 052dc433b84b7762828794e284f211843814e767.nq.gz
    ├── 0536afc2389820d4d2ed065de90985650a484e67.nq.gz
    ├── 056db8fa04cedc45b91766d67e98dd56013fc71f.nq.gz
    ├── 05891edc75e912951ee5a5c9bbee24dcb536ba4d.nq.gz
    ├── 05db276c7bb9400d54a632aa917ed57d30f571ff.nq.gz
    ├── 0602a1f90ec5e40e36786ab4bd5d5b331d20c297.nq.gz
    ├── 0603e2afa1921189a14c531b49504554b95f2748.nq.gz
    ├── 060fe368c4cf186ac21f16d88b20a30cc66eb13e.nq.gz
    ├── 062617ad589a835861cf3e5e579e0957c3427215.nq.gz
    ├── 06419b99de3b0143fd91780428e6e37424df5f18.nq.gz
    ├── 064dcbdfa743e291a9c97ebdd9f01f428608fbfc.nq.gz
    ├── 0679d34370bda90398c60200c1065a4060d9e408.nq.gz
    ├── 0681b01f206162026a0828b2b952a7a98a83aaed.nq.gz
    ├── 06a0713f1d79906d2ef1d34d3138f376268f2328.nq.gz
    ├── 06b05b2eef66024a6bc68e6db9aa90321e657a32.nq.gz
    ├── 06b9239f65b46333360a4bf794ada09204bbcbe1.nq.gz
    ├── 06dd7eab0b8bdfcab719e18106e9489e2c2642df.nq.gz
    ├── 06eee44d80020a7a152cf730197eac3d10a472cc.nq.gz
    ├── 06fa52bef02aea9992b5ebf9d3491d399a50ee6c.nq.gz
    ├── 070da028e307d758d67390756a97ba9791d72fb0.nq.gz
    ├── 07231ad93d41730871d78d47db415f5b99d0b504.nq.gz
    ├── 07655d877364309faac52606a70c043f1a0028fe.nq.gz
    ├── 077c7e4fe1bbbf130e59be8d6616c98c9016270c.nq.gz
    ├── 07a0609d5c4545002b871132218e4b7ff203bfc1.nq.gz
    ├── 07b409236ac462c72ca41e53510b783b1bbddadf.nq.gz
    ├── 07b5e673b7b2e8a805793adccb5df1c2a1a07c3c.nq.gz
    ├── 07d7e45b85a17844bc95f36afaf0e614ae225950.nq.gz
    ├── 07eda444dcbb284714d5061b58c17e15a6d6bf76.nq.gz
    ├── 07fc6305741d8458b221abdd91969ed4b9f90410.nq.gz
    ├── 08037e1aa87b0aeb411d0c264503939823ea90b2.nq.gz
    ├── 080c4d91ed7ea3ce03c7d017d3efffba019de8d0.nq.gz
    ├── 0813c11cfde14b8e60a2eba5af0917865c1f7707.nq.gz
    ├── 082788a17b0e69f21e38f311b01811a810b3261d.nq.gz
    ├── 083a7ab6b596c0c66d2563eb43b971bccdb1f9d5.nq.gz
    ├── 0856d55367e2ac8c21272c20843e345fe972658e.nq.gz
    ├── 089791b737da213e3c6ab5cc6575c539a0659c0d.nq.gz
    ├── 08e08ac97c0a7cf2af2b9737011cd1d3e849b45c.nq.gz
    ├── 094ae91185c2ca5d923afa78f64af914038d1ec4.nq.gz
    ├── 099f5ab4a1f6a54b273bfa4f4e7bf1ea8bc14a2a.nq.gz
    ├── 09c432ac6cc82a4317404804abed93da3198ef08.nq.gz
    ├── 09fc54a7066b78a9958001ca443ad17b24f6d666.nq.gz
    ├── 09fc9e172ee73ce42644c8e0013779898996a6f4.nq.gz
    ├── 0a0441f2d8d934c514c2273938100cce55739e69.nq.gz
    ├── 0a14756ec0084f4cb8c0192a983899065994e97f.nq.gz
    ├── 0a645e41e717e57258a2a727d836139565153896.nq.gz
    ├── 0a73b49f46f949cfb39099d03f1fa516148e2393.nq.gz
    ├── 0a9bad1cdcda9489890624fcce68a4c1561b2bb3.nq.gz
    ├── 0aa2f00dc837b23b080861e5559f5555ba5b196b.nq.gz
    ├── 0ad9dfc282010a3523bde3fffb105ee90d6eec0e.nq.gz
    ├── 0ae2b9aaa93a07de785973a33bc7293a2d24431d.nq.gz
    ├── 0b03302284d7ea446852a8bf4ee2fd7fe97f08dd.nq.gz
    ├── 0b2795d1215c2f86df145a0ece05fd67bf800d3a.nq.gz
    ├── 0b458f74e18eaaa2827cd3c49891cd38c07037cd.nq.gz
    ├── 0b9f676cbd49864952d21a90ed76d55bdc5e8ffa.nq.gz
    ├── 0ba6e94e399beadee9d1c19eb867cc13f2b65e2a.nq.gz
    ├── 0be284c9624aaf65a9fbc5d8a3e78599f1e85942.nq.gz
    ├── 0bec3a77cdbaf38a47805c7726978a25f8c197c5.nq.gz
    ├── 0bfd6f46eb36f6980dcf48d3986980eb20289f5b.nq.gz
    ├── 0c3530caa514baa778527f6d161e5a669a501655.nq.gz
    ├── 0c54e14995fbf5a3801d874f5ca9f1a20a49c442.nq.gz
    ├── 0c6a53a832554b89edbd0e2efd07678421cdfff1.nq.gz
    ├── 0c72dfc31d529c7bf9882e6a2d99a081626e3e4e.nq.gz
    ├── 0c784f863f1630839dabd873590d830af8cef100.nq.gz
    ├── 0c8bf7662201412bcdf09563416e093de500b23b.nq.gz
    ├── 0c8d3c77e1d10ae2d5493eea9538e0b9ebc85bc2.nq.gz
    ├── 0c922717559dddf7ac91f7dae76f7871a79374b8.nq.gz
    ├── 0cdebbe05df27a17a74ba996799d327ea830534a.nq.gz
    ├── 0ced1587eb4953609a9958a845dcd1b432df8470.nq.gz
    ├── 0cf4a2a7d48e6f99a04aa4d3c519e5dcdb00decf.nq.gz
    ├── 0cfe3481f46fe7463ee2469e54d1714c02d4edb9.nq.gz
    ├── 0d3a7f904204478c99b269021f38325c484da40d.nq.gz
    ├── 0d44434b018e0bbb37297077485830b241b0af48.nq.gz
    ├── 0d4c3c187248778505e203f27cef1204500a9fbf.nq.gz
    ├── 0d6b14b489a2ed7bad8fc6172ead55f129e3da8c.nq.gz
    ├── 0d7b71cb9027086a811c2754215734b90606e802.nq.gz
    ├── 0dfebe4a0c84f1e9655aab0376858ab10a400246.nq.gz
    ├── 0e04d98f8a0fa9db9453fa297300aeb1ce4677ec.nq.gz
    ├── 0e294ddf99b77bab78cfd30fb6c95cf3b8579c59.nq.gz
    ├── 0e2feb87bad1bb68bb7626b99da7e15e67e5f4c5.nq.gz
    ├── 0e4c6c5a0f259cf9b39b2190e9da235c8c8e1940.nq.gz
    ├── 0ead222b8fa24050fcd122bfceeeec3c5b5dd484.nq.gz
    ├── 0edf30170f283dbf846ac4b89302a5bc2b61e718.nq.gz
    ├── 0ee2cf992fd1da1138d65f8d500cede3064a056d.nq.gz
    ├── 0f21391bf56106c27f4c107a0f9c6bec68dad3e2.nq.gz
    ├── 0f567a06b3e80a45b1e77d529b338debe5f37d2e.nq.gz
    ├── 0f57c4d6d785c284dbdbbb8f76c5800ce3e5ee71.nq.gz
    ├── 0f70bab0308908e88ba547afc639343d9884792f.nq.gz
    ├── 0f859cc54be0d9a657605eecf3a4cc033b4f041f.nq.gz
    ├── 0fbe517cca84f3e972d178840de3e7ef0a116d36.nq.gz
    ├── 1020e0b7ec674dbb3f3ab176f826a337d05a5b7d.nq.gz
    ├── 1024c242316fdb12b5b4c007a73d003f5d3b4abd.nq.gz
    ├── 1026cd964e66be81146a8e6b72fe17de11d1592e.nq.gz
    ├── 1028b3aba2b60ecb6f73c2d28deb3162bcf82a1b.nq.gz
    ├── 104859edb8c808820c5c623d6148bdb0c0ff1f0a.nq.gz
    ├── 1056bd54796c34c5ae38aca2c1894bfc7c3390c5.nq.gz
    ├── 106d34e2e81724d1388038e938ed1241365d509c.nq.gz
    ├── 108f974fd46f34d1876bd5e9fb4b65477809f127.nq.gz
    ├── 109cd979e2dd041114bbc525209c97e3c8adeb10.nq.gz
    ├── 10bbe465f451f25d9171e08eafb6c70646a08917.nq.gz
    ├── 10f69d8ca3e079905a74fba73e624552c0ba02df.nq.gz
    ├── 10f78fa2974c73ef1ef7a4acaa783622f2073271.nq.gz
    ├── 11239cc0f16d8a71a32dd471b67fca420a38b232.nq.gz
    ├── 115cbcf742a7b4575be44eb47e8243abde149510.nq.gz
    ├── 116660bc57d6bf531faef799e152fda5b1918777.nq.gz
    ├── 117194645a1e239858a080b88c3c316560d27472.nq.gz
    ├── 12224ec83d24ea1812b89a3c188fefc039d6c9fe.nq.gz
    ├── 123327cb6ed4cd5cfaf2572a449aea912f0d8de8.nq.gz
    ├── 129451f6a4e47e727cbdcd2f24676531de96d87e.nq.gz
    ├── 12a9b3181ad7f88e5d6d0e00ee2b55c0d1fb6eee.nq.gz
    ├── 131c5ad42c7ecd3470dc44cea98f741d011f5fee.nq.gz
    ├── 131f22ac465d7d89547579c74e505c6ea87d43fe.nq.gz
    ├── 1323c215fa0d5cbe603e3f84893a032b8bb000b4.nq.gz
    ├── 134b0a602cb2dfc1be3348acf087d928b1190f78.nq.gz
    ├── 1398e1f3dff879789578a08faefcaadc292ee39f.nq.gz
    ├── 13aae45312fbca72d084f429806f4d31cacb7c20.nq.gz
    ├── 13afd8825acf8a758642604fa4b319ee1368af5d.nq.gz
    ├── 13b92997006453083b73ef469f18c08e29341760.nq.gz
    ├── 13ddebeddae4ab957c461fa4425ac44b24baf35a.nq.gz
    ├── 13e2138d34fc94ab1b2ab2333b6553626e4cffaf.nq.gz
    ├── 13f7f1fc79030c2224d14c9a07e078f1735383a2.nq.gz
    ├── 140528ff9be836b65121342b2754521b24594829.nq.gz
    ├── 1407bd1a5ad9e40a46f9a07999f68b12a3126745.nq.gz
    ├── 142285193ee470ad5f67ad0cc010bd2e333871cb.nq.gz
    ├── 147f8b6c091e4e0fd2c6f007e05ad9b559b9cb4c.nq.gz
    ├── 14870f36be547ced7c96aa2d78d486bb38fe29a8.nq.gz
    ├── 149875238d1158333a93d3bdcb0651fda97a0113.nq.gz
    ├── 14dded8c832019bf2692ff66c13744c0a448b8c6.nq.gz
    ├── 14e00b034133a41ff8e54162282992d6fb9fcf44.nq.gz
    ├── 14f053bdc205e1e041a3bdc94dd9dfebc8f13aa9.nq.gz
    ├── 1510d7540ae888a3d46dfbefca2661396c24877f.nq.gz
    ├── 1512d5e330cddd3ac8529026f52bed7d469c014b.nq.gz
    ├── 159dd4b9b056dbe4e69cfd1c64517672edfe97b3.nq.gz
    ├── 15e5294102e440b4910126e1bf15dc03972acb58.nq.gz
    ├── 15e623a7e903258747b272fb433fc709b6595f28.nq.gz
    ├── 15f67f5d159f61d80d33dc2d89d8b048a8445b3b.nq.gz
    ├── 15fadd4e409be8738826540644b1b2b32dc3b01f.nq.gz
    ├── 161c448e5cbbda1c5c6801b995c437998d50176e.nq.gz
    ├── 1645f961a11c314131e7c84a72feaf7cd1db8671.nq.gz
    ├── 1663e49c8ea00e1af8e381c8850f066bb0ec25fb.nq.gz
    ├── 166d906914adc9f6b4e7c22360fccdb50f9b36b6.nq.gz
    ├── 168ac558fcde221cd485da1fccb716dd1ce695f0.nq.gz
    ├── 1692a4532b5c24ad32d27f8250c5671f7710932d.nq.gz
    ├── 169557bb94903398e50e13c25ae9cb0055e04edd.nq.gz
    ├── 16e65bc38df5c793c9fff79bffdf80cea0d70766.nq.gz
    ├── 17064c10993a8fb4b934917941074be440fffec2.nq.gz
    ├── 1710cd73ea82468b88e9be201765486f632c6ae1.nq.gz
    ├── 17251c03f915e1f42756ac56f88e8b336c3030c0.nq.gz
    ├── 173c789f9f9a8d28e5257331650246f15ee76372.nq.gz
    ├── 174d8b4aac5e3493005c5f7cea3ea6b58360b000.nq.gz
    ├── 17a5cc3923ac3099fd2634941875270ee33600f1.nq.gz
    ├── 17be7c988bd22bec74914f196179590e4c4443c8.nq.gz
    └── 1831093f776324a664768a627d82ddfa956e5541.nq.gz

10 directories, 200 files
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
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
