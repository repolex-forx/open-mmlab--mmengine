# Repolex Knowledge Graph of open-mmlab/mmengine

RDF knowledge graph data for [open-mmlab/mmengine](https://github.com/open-mmlab/mmengine), parsed by [repolex](https://repolex.ai).

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
rlex download open-mmlab/mmengine
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f8a8b1b3b3051175a8babe5df9c753a981919087
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f8a8b1b3b3051175a8babe5df9c753a981919087
│           └── chunk-001.nq.gz
└── blob
    ├── 02e009fd74de6da897d4120088300152aeae7bda.nq.gz
    ├── 033512a985e66b300a52415fa5b206a56e268b60.nq.gz
    ├── 03e5decf0d01d211ef4a4ebfe04603e370f16307.nq.gz
    ├── 055bd73ca16a5a5ec8f22bab74a0da50b3aadf13.nq.gz
    ├── 05c008da4528631bf7b7ada08ec726602a025f73.nq.gz
    ├── 061278d0a079c4d367fc4f4bcb351ccc78939641.nq.gz
    ├── 0636e25e1d1d2a89496d3c22e21da635ea7679c1.nq.gz
    ├── 06defe67484dff91cf6f69109324cb1dd9d64bc3.nq.gz
    ├── 071db8709c42fb386f961c3b14e9583eb51ad2c9.nq.gz
    ├── 073856fd25a731b42f3cd19269ad95744b20598f.nq.gz
    ├── 0798f4a2c75831dd67559f3df5614fd6431dba3d.nq.gz
    ├── 0840d16c082be742f9ad816b226d72f80353d56a.nq.gz
    ├── 087a969cfabe30ce0ed3080fd6eb6b81e232502f.nq.gz
    ├── 0966212ef32a656aafe76c2956def67899937455.nq.gz
    ├── 0985c0026a9fa753c99f91e3a880aafbc4ba8469.nq.gz
    ├── 098bc9db94b9e2e2f1192622e48b66bb0e122852.nq.gz
    ├── 099c4b17789dcae2cca360abf9ce256a337e4646.nq.gz
    ├── 0a896a05a24dd196946e00a633ce5f30979af02a.nq.gz
    ├── 0c00c84688701117f231fd0c8ec295fb747b7d8f.nq.gz
    ├── 0c5630a765c0352031cbdcd1f85ebbe210129a0f.nq.gz
    ├── 0d7e2751b7d5afe06712c2213505c9989ff858f6.nq.gz
    ├── 0d96210edb6b985ef2461e0addb7d0067b7f2d12.nq.gz
    ├── 0e8d92b9d69be9461c04e1500f66b2a0321c482b.nq.gz
    ├── 0ee99abad2c654e975d11c0b315c14dca18171a7.nq.gz
    ├── 106fc881f2514dfcf5b31878e7eca34c7f1659ea.nq.gz
    ├── 10a5873499a32198bc8c8988059c6e47197e304c.nq.gz
    ├── 113aacd6c886f263123c1323544f7d0d5d2efd43.nq.gz
    ├── 121d8e4ed9a203cbb0f10d4c24a430c59af18f00.nq.gz
    ├── 1292ce61eccae625649603f9f8975ce6fb1bf108.nq.gz
    ├── 12f029fbd68bde00e963caa1c03f81538a2a19c5.nq.gz
    ├── 1340e4bd27198e3d3ef82dbf516f22d8daf236f2.nq.gz
    ├── 13914341f740b355c225e7779d0d6041434dd3b3.nq.gz
    ├── 13bc61d54225bf133b9d7a069ee94c2f43fe4835.nq.gz
    ├── 13d9f38fc32c51c1248a47284231d5bdea8c9499.nq.gz
    ├── 13db1375e71095d4295bde140bceaad9db9e1c31.nq.gz
    ├── 1401eed298805868bb38e581538068b41fb87d7d.nq.gz
    ├── 142d0f089f264e41bd816a80ac09849c0df52d29.nq.gz
    ├── 14366583d583edfa3b88c97cdfe579375e9ad2e3.nq.gz
    ├── 14c7a97ba73ee98600102ab28d649b01aab8f3bc.nq.gz
    ├── 15f3ef84bde918891154e2813433a7a239b373bb.nq.gz
    ├── 1698f1ea4b650a19dd22bd1776ca28cb60818988.nq.gz
    ├── 16f8fd981ced9ccfcc1b97dd9e5936ae8c551448.nq.gz
    ├── 17325b13bc515f55c044453d3d27b4f4110d1001.nq.gz
    ├── 17b294863a507718716b06b447161f8bf660e14e.nq.gz
    ├── 17c01e99adeb700ea28c4b794d90c68939871e1c.nq.gz
    ├── 18a619c96eeab6fd6995ff280225eb6175171f95.nq.gz
    ├── 18d4f15f74139d20adff18b20be5529c592a66b6.nq.gz
    ├── 198babc58239ee4bc54335b869b1418f511fcb10.nq.gz
    ├── 19edcf82d0c9a40c007ba6a1eca03153f7056ce0.nq.gz
    ├── 1ab44a8a3ee09e63e2df019dd07785d127f6db86.nq.gz
    ├── 1b8c14b42ab2b66a4c3eb3232549608dd70a6637.nq.gz
    ├── 1bfc23e48f92245b229cdd57c77e79bc10a1cc27.nq.gz
    ├── 1ca80373af6706b732a9a9e09ab5f9dc96e89d27.nq.gz
    ├── 1cb7cd17457855128f6987b0e1c82f5fa6836eb5.nq.gz
    ├── 1d1bd2e846253cf59071b96991109bc6259d181c.nq.gz
    ├── 1da42c17c8b763330d63020b2b5fa22b96bcd75a.nq.gz
    ├── 1dda04fdaad79aa40c498ff234ed18feaa018b1c.nq.gz
    ├── 1e058f9f7bb4f6b73240d3a5a358d6181414912d.nq.gz
    ├── 1e0698265da401e96aad717055672bc636dd322f.nq.gz
    ├── 1e728323684a0aad1571eb392871d6c5de6644fc.nq.gz
    ├── 1e98a1ef08285877ad702252810b438369428ccf.nq.gz
    ├── 1f1b5b1d6cf3f47d277f26d894ce7c7936352086.nq.gz
    ├── 1f674c72e67ba2d19a44d0635048e5e3a960928f.nq.gz
    ├── 1fec4196614d14fc13eb62fcbf6b00e0a3dfce81.nq.gz
    ├── 2065897887a6de446edc9cfbc4fa4105d8250da4.nq.gz
    ├── 20749a0babd17dbd4f958645e5259e18c59943e4.nq.gz
    ├── 21c8f38e795902fd4d72482e6f705dfc02f03e35.nq.gz
    ├── 21f0b978618c670f193660a2d2fbc09b82120484.nq.gz
    ├── 22787e470946da6ee985845617e4e6e896539956.nq.gz
    ├── 22c0e47147a71faff123d9c20946bcfc7cd29e9b.nq.gz
    ├── 22c2607ae43734f334bbfa83445b1409ef855433.nq.gz
    ├── 2364e1d10b054e99c2e1e5780cf8d0e007d659c2.nq.gz
    ├── 236bee234c618e647512429e154ff0381483ce3f.nq.gz
    ├── 2385e4ff5386dfd21a98f8550f7f17c5e2a3d0bb.nq.gz
    ├── 239220f3f777024e7fc608a649e6dec7d560fa52.nq.gz
    ├── 23ae707a56843af3d4633e8f69c77a343f659b80.nq.gz
    ├── 23f4f075bf7e21400758dc2ef3bd1cfb300290c9.nq.gz
    ├── 2458e7c6ec3525ba0425370c3529c4403f726716.nq.gz
    ├── 2550ae6986e0fcfe7627b96eb575f26ef601c935.nq.gz
    ├── 2617fda767733cdcb5295fc7180ff9e169ba56eb.nq.gz
    ├── 268cd8ee396e1cd20990bbad1e00c7508ddb9176.nq.gz
    ├── 2737e879a76e75e47b9f3d3760a8cd1913901718.nq.gz
    ├── 27ad74720a8338d6913209866f12a6620b6ac599.nq.gz
    ├── 288878bc57282fbb2f12b32290152ca8e9d3cab0.nq.gz
    ├── 288bd4fd103bc980adb9fc398da682d446c8b04e.nq.gz
    ├── 299cd67557ed7d7890d50bd9ded4228345230b44.nq.gz
    ├── 2ac2b3548eed0a0bf6cc6c893105ff28f9846a25.nq.gz
    ├── 2b125447b9cd9a8051fe7679fb2ac04205c90d15.nq.gz
    ├── 2c5d09192277383976d64428e87d42f2ade96a73.nq.gz
    ├── 2c9c7d6bc0a18507889e59784fe3d95e53fa5d8a.nq.gz
    ├── 2c9cf964970dc33e3b14ab3c343ef7a16067bd90.nq.gz
    ├── 2d020b630021b4c9fd44668744506f2310914c50.nq.gz
    ├── 2db28942b1264c0f350bae198af307c4b334e7c1.nq.gz
    ├── 2db6df01b613667e4e76f98a7102dce417f94161.nq.gz
    ├── 2dbfb28e87534112a03a754e37a76106c9e47e9b.nq.gz
    ├── 2dcb1af0728a387b8faf2e213bb8b57de1827a50.nq.gz
    ├── 2dded0da7647453fc8fbebca4eeed1d7073631bc.nq.gz
    ├── 2e0c69d48b97b0e5215261435d9e0f953b66088c.nq.gz
    ├── 2e39e945274c4cfc63f204e1c9a208bdb5a11632.nq.gz
    ├── 2ed1a1e319fa36eb11ed3f0fcd365eb43a382d01.nq.gz
    ├── 2f19ebc6c6e867372f61dceadba4d66de46e31ab.nq.gz
    ├── 2f8dafa3aa4dab10948b1e5e913bbd764dfdf4ca.nq.gz
    ├── 305ea898904e359d61e3aab8e51897a9d035b08e.nq.gz
    ├── 307d053f2fd9fddf0bb52d4e0081cdd32e5a6364.nq.gz
    ├── 308c7dd95a895f849fffd65ba69d3c77861a74aa.nq.gz
    ├── 31582a86796b41d089cb9120db6a1ec829a791f5.nq.gz
    ├── 319d0a0008370e44e9d8b4775a25c7ccc5384a2c.nq.gz
    ├── 31ad01a28f40bd87649417bc2fe4c6c31e8e003e.nq.gz
    ├── 321c39ed4680839e06e06b57a1ae01f04b67f4fe.nq.gz
    ├── 322d8852243493944c8b9adbed4095140a8ead89.nq.gz
    ├── 3251c5d6395974fa788eb27a368b03150eabd72c.nq.gz
    ├── 3286f6973610a171ba983af2de8602b3f2a0bc42.nq.gz
    ├── 335da9de50dbecc8138280c67e20ec945e66f11b.nq.gz
    ├── 33a0956fed982656aea45cbd26cdd12676d46633.nq.gz
    ├── 3423e6c505b19e2add8849362bdee8ae5e640245.nq.gz
    ├── 34d4ebe2f898a01ee8aa11a51f0383040213dc7f.nq.gz
    ├── 34f12d00848f6551c5ab823c12e2443e50e630c5.nq.gz
    ├── 357c02d4c6da0a4552708d715e02c7946a0c7844.nq.gz
    ├── 365af76a557c8f0f0d82dcf055c158ea781439c5.nq.gz
    ├── 37353c9e239af567e861be54d82f743d8d6651d7.nq.gz
    ├── 38073760c43879f40605ee99eda0c0145eab2a3c.nq.gz
    ├── 38d258acbe75e7e7ea6ab302df4aebded52dd028.nq.gz
    ├── 391a60c36b3cdf9070437c9d96e9c0bf23fac1a2.nq.gz
    ├── 3925a33ac9a8232c5c2f0b426f1206c2d8548d60.nq.gz
    ├── 3994372f664b22535d1104b9b9032d5c3e7ac092.nq.gz
    ├── 39b2de476fec519b2109e8eba32df4cdf7b7c433.nq.gz
    ├── 3b2f1e610a9db058e99d03faf607514d73bce030.nq.gz
    ├── 3b3e46e81a0b44a8c029e034d7008fa68fdf1c7f.nq.gz
    ├── 3b87d42373dae5c59c7c4ed45aa27cfcb09d95e6.nq.gz
    ├── 3bd4195a9627800829dab82d7eed8f9c65d85679.nq.gz
    ├── 3ca417b48d0f3cdef7304bf18b04199a7c0bc0d2.nq.gz
    ├── 3cd1a00ef53a8e949175bea0dd4f00e586b4f3c9.nq.gz
    ├── 3cfe0b14a8452bd6188a9e64adb122ce4887f750.nq.gz
    ├── 3db67f057ced0f56a533eaeb98a1ea52fdd183cf.nq.gz
    ├── 3dc5cef748bfddb5a58100f1d8872d884dd8365d.nq.gz
    ├── 3de679851455e29c3f7771b154d5f1456703e2a4.nq.gz
    ├── 3de90999073d2fafc2738519e99847d9c930502e.nq.gz
    ├── 3e6b7d8ba9cb90e464426a1c140cc0815aeac103.nq.gz
    ├── 3e996d62e16027a96771fa6f9ba2299b88e1d0e9.nq.gz
    ├── 3f89ff760d6bbe5a17a6c3afddc4879026d5f429.nq.gz
    ├── 4113aebf9ee49015f84d25f2f242c43ee9d92a23.nq.gz
    ├── 411ef6a98d905ed9e6993a5782fe2b0c2b76d169.nq.gz
    ├── 41218ef768b013a4881eb357962c0dafdfc5c017.nq.gz
    ├── 423b169b79f63b72e3b9fe6f2fb0982750e9619a.nq.gz
    ├── 427ebf789aad3f8fc348c293be52155f6a69c79c.nq.gz
    ├── 435e5fe5d3a1af4cf2d94ab11ae52910b290d5fc.nq.gz
    ├── 4395d84ab9975c59740bc0e5917a9b07c0df08e7.nq.gz
    ├── 43f0187d9aebb91c74ec1c33c2d9593dfd943017.nq.gz
    ├── 456aceb160d881c6a9b8d5b0eeeb07c31bc1e625.nq.gz
    ├── 4578a4ca76fb3f867b87c088407399bc5c700153.nq.gz
    ├── 4622f146a5884367a8475494a9967d004aa89b8d.nq.gz
    ├── 473a57c0eeedd666c2adad3cf3775851db033c83.nq.gz
    ├── 474d7bdc42101c2f600e4bcd0355a5e1303ee87c.nq.gz
    ├── 47a83994b610d77277a6d17254c4c606e96b1f93.nq.gz
    ├── 47e710603ba83b51a2e68b2ec0dfae631b2ced27.nq.gz
    ├── 48ccc34bc41b07442e2494b03a303b3c0054b42b.nq.gz
    ├── 4917e0b24f86e8bc8c48dcff0880bc80cc84d2cb.nq.gz
    ├── 4a16c7383789322908127c8780c3be9b54f11c20.nq.gz
    ├── 4b7c8e1a43111dcdf14109ff19263ecdc283e7ab.nq.gz
    ├── 4d20d7f0250565aa0af5e1f9742ec5a6579a2639.nq.gz
    ├── 4d621851b0793113373d24f1bfe97c3b35298224.nq.gz
    ├── 4e1c4ce8bd28f450f911d0e92f9ebceb6dae4014.nq.gz
    ├── 4f3323f2cccd358a75827cae9e7384860b6ebf6f.nq.gz
    ├── 4f74842394ec9807fb1ae2d8f05a8a57e9a2e24c.nq.gz
    ├── 503d848df2bc8bc0a7b30300aef75c74b9f7b8f0.nq.gz
    ├── 5160a5cfb09f0bd57c85b7d4129335f88aa3bb51.nq.gz
    ├── 52b8bc1fa3133b94f0dbe917f9e5725b9b865951.nq.gz
    ├── 5349cab931311c82c65e48e760e798fc5154bcd5.nq.gz
    ├── 5365b7142fa06524678f3fd2502a97f4080c1d6c.nq.gz
    ├── 54119805a63919e67b9ce9b7ee25e0e6d3f14135.nq.gz
    ├── 548ffd7ffed2a3b147a0a2806b3ff28eba19af2d.nq.gz
    ├── 5533ebc84cf939a38fc12e3cb6a8e5455c2f8c3c.nq.gz
    ├── 558015818fbd03157848052f85b744383ccc0ff3.nq.gz
    ├── 5632c2b25e03b5773ec694452535be1ecb661d19.nq.gz
    ├── 56a1a3e20c8e1e8466aaac328754600a341a006a.nq.gz
    ├── 56adb52280b0b7c895b3bd1e0d40c15af50ebf85.nq.gz
    ├── 56b9252e924e6c0f1d3d5226d7cefb8cbe193422.nq.gz
    ├── 570f7ea380dddb261a5ff16a7e0e3b5c30960f9b.nq.gz
    ├── 5775736d1f783d3925f98a4dbae9fb35bf740fc0.nq.gz
    ├── 58457c2a6e92311149917b1e362ae339aec8be27.nq.gz
    ├── 58b7e1e6febba882a911416eb6b77ca9d78122c1.nq.gz
    ├── 590563a3f84453fb37a7d7fd5a9d57e7009965e0.nq.gz
    ├── 5954896158477511e5a53cc7c8a70801feb63972.nq.gz
    ├── 599d20a989666ecdfb3dbfe445209066b360fcd2.nq.gz
    ├── 599e2bd2ac19bea8231ac08873b1149aabef5d36.nq.gz
    ├── 59db4df0c47060e92b89419681594022dda994c6.nq.gz
    ├── 59eddfb2737af5c5074a0fba695ede2a3fcb5165.nq.gz
    ├── 5a48f3447317d2ef0e8e8ae259076d4541d627b6.nq.gz
    ├── 5a678db7b9f7e57bf088c1d166536fb6dff2a838.nq.gz
    ├── 5bae459a2071b1560ddf159a2922925f6a58bdb7.nq.gz
    ├── 5bc1051d0b7069fa83fa4ad10454c0b6e6470716.nq.gz
    ├── 5d32cec36b90e9a082e5542319a5bda6e6f5cfa3.nq.gz
    ├── 5d41c03531da7e4d0be7d9ea326ff0925d65adc5.nq.gz
    ├── 5e60377f7ad7bf81a05711f9065d8175febe0f0f.nq.gz
    ├── 5f0a5233fccaf516f1c8bc2a5df475f4882a2697.nq.gz
    ├── 5f143dba5a8d417f14e95366b0915b97c28952bf.nq.gz
    ├── 5f54d6ebe7298001f365c661accdbf9637969d15.nq.gz
    └── 5f844b3f243721d41aa065c52071446fe8a1eaf4.nq.gz

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

[open-mmlab/mmengine](https://github.com/open-mmlab/mmengine)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
