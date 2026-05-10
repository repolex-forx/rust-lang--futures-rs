# Repolex Knowledge Graph of rust-lang/futures-rs

RDF knowledge graph data for [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs), parsed by [repolex](https://repolex.ai).

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
lexq download rust-lang/futures-rs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 5af2fc274a07dd5099d61c5147b5fd9d10488d8e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6bb7937348f8fe777043c50b3062101f6275d88c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8be72deed0014a41117856beb8f03f7eb8bd023d
│   │   │   └── chunk-001.nq.gz
│   │   └── 9dda267087e6b453e7782dcf993fd4f6fe9a5510
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 6bb7937348f8fe777043c50b3062101f6275d88c.nq.gz
│   │   ├── 8be72deed0014a41117856beb8f03f7eb8bd023d.nq.gz
│   │   └── 9dda267087e6b453e7782dcf993fd4f6fe9a5510.nq.gz
│   └── repolex
│       ├── 6bb7937348f8fe777043c50b3062101f6275d88c
│       │   └── chunk-001.nq.gz
│       ├── 8be72deed0014a41117856beb8f03f7eb8bd023d
│       │   └── chunk-001.nq.gz
│       └── 9dda267087e6b453e7782dcf993fd4f6fe9a5510
│           └── chunk-001.nq.gz
└── blob
    ├── 005bbd98357ce5944458986c9cd774e99bb1a392.nq.gz
    ├── 00867d378a8d8ce06efd9336b05125d7bf242dd0.nq.gz
    ├── 017050bb5878617b942732875520c294ffe959ff.nq.gz
    ├── 01e1e599bd3cf2989ea69ec0009a178f0845e83b.nq.gz
    ├── 02459b39f60f5b0fab4294544f7b44a3613cf36f.nq.gz
    ├── 034d571cb2d8f59af7df2215cc1aa3c43b4f23eb.nq.gz
    ├── 046db516649f33d7ad8e83a4fb362c7ee8729219.nq.gz
    ├── 0614368ba3ce8b4cda479047f57e7ec81ef1b1dd.nq.gz
    ├── 069519556e3fd2cddfcb99c2a3e449207395f70a.nq.gz
    ├── 073f67be4a8430d0abf24893c9be6c7bf9ba8f6c.nq.gz
    ├── 079e3ed6161751d113b00e314c908ff96eca9101.nq.gz
    ├── 0864c536320546f727f1da22680df76b2e8d919c.nq.gz
    ├── 0a46e9afbeba365bfdeb488363988ae9fb450c69.nq.gz
    ├── 0ac8f8da43cea1d6beaa63824c6789e56b58df21.nq.gz
    ├── 0b0bf2492338c121b5aab8ce7bf9aa6af19b83da.nq.gz
    ├── 0c1e9d72ed6158401c98489c46d0522111838db0.nq.gz
    ├── 0ca68496eb6969363122577fae47d4977029f62c.nq.gz
    ├── 0cff01b18fd9bedb1e8f144f70393f4edeb5e377.nq.gz
    ├── 0f840289ab7f704199f512b79704aa2d30fdc547.nq.gz
    ├── 0ff0e5ce6f5bf8a6154a762a4a85bad8a57d0b47.nq.gz
    ├── 10f9c3cf8fb306cb6f9222b338f651609cdf8f7f.nq.gz
    ├── 113713167f633d5dd1a313de96d692e15fa1798b.nq.gz
    ├── 115413c2b5666f64b17768dfdce068f5590a8344.nq.gz
    ├── 12eb601b89a6be8769a152b200e6db08f777e570.nq.gz
    ├── 13918accc5bc6ade89b30d0f3445ead880956d6b.nq.gz
    ├── 15b7d1166d2b22b77498a273a1a5a2f73c0e574f.nq.gz
    ├── 1669a18aa515bc66cb9ed42071d2dcfac769e958.nq.gz
    ├── 16e22a9b3e12eeebf97b86ec3e3889c2b928f828.nq.gz
    ├── 16f9dad9ad99230b87a20d34194a646c9e28ae8d.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 17e3c69ffe1f1793fd2895f717b45c53d1fa724f.nq.gz
    ├── 188fb8fa80dd21cb62bd2f3b425d251bec36fde5.nq.gz
    ├── 1b204d376aeefc96279edae9b07fbf94e8e0da81.nq.gz
    ├── 1b267f2f0285a6e65d611a2c84b75f76d4918815.nq.gz
    ├── 1bf5cd639ca0b5a9d0394419f7b55d13f98729cc.nq.gz
    ├── 1f94397ec50d64c3ef1346a476bd1d2b5d605e76.nq.gz
    ├── 1fac8b952dedf346e11a2da690e51c7bde91a4d5.nq.gz
    ├── 1fbc98693b466ea5ff4eeb7c16600f22d116f963.nq.gz
    ├── 1fec653fa6b20cb02e58357526be12d439948141.nq.gz
    ├── 216bd1f0f2c7fb75b048f5649d31f0d1e4af8904.nq.gz
    ├── 22239be3dccba7d918704f7ce50ccc10c77b432d.nq.gz
    ├── 229a8e58c093462c9d84b9867d1535905bf157fc.nq.gz
    ├── 23a99819bd9f316a1f4cfd718f78243576324675.nq.gz
    ├── 246def275374a90bae1dbe50d6568dd98eb18b8a.nq.gz
    ├── 2472c8124e1ece83a781948602370953f47db013.nq.gz
    ├── 24fb327bd658d444aaf5898c7cb30d6f69c5a7c2.nq.gz
    ├── 2537ce188c0115a53a798ada216d44faf1e894d0.nq.gz
    ├── 253e015705561bda689e442ed11d38ac60919a02.nq.gz
    ├── 264e1097638b268f731fa32e3973007c99326412.nq.gz
    ├── 26940cc9f855874cae64a701652de78d36f3753c.nq.gz
    ├── 28e630cf40d23e85e1b1c48eea4c7c2e8afd90f9.nq.gz
    ├── 2940fd3495cc0d70247a364bef62eecfe2153e6f.nq.gz
    ├── 297749777ac4391e6666c1add6bd3e8ff69c9f73.nq.gz
    ├── 299a0383c2a359ee2ef283c1b3f20e2a9350cd7c.nq.gz
    ├── 2a47443803734455982896c2b14f3f1245de1909.nq.gz
    ├── 2b44aa5969c45b703add8383de9007944658070f.nq.gz
    ├── 2d15fa2b70e340d47aadf827fb2285046a854c04.nq.gz
    ├── 2ded2b3f6553ed842d8d9ed45be57a45163d2c59.nq.gz
    ├── 2df0163fe5cd3ac390214e851d4cbee1c2e49674.nq.gz
    ├── 2e27f62190e8fd290e85dcfce431e7594013b294.nq.gz
    ├── 2e5b6aa16edea3e6164537f698e93a82f8d2ca13.nq.gz
    ├── 2e702a99c9c9d3d9af4aede13179bc2d765216a3.nq.gz
    ├── 2ecde10039ce668ac8f61d482138d66805c06373.nq.gz
    ├── 2f310337b674003f3efd58fd2aafe34efc69ce24.nq.gz
    ├── 2fe1cc327459ae59bcb7caa624f2c40c7738c79b.nq.gz
    ├── 3011108cf39a9b88a59fd7b7478d3f4c8a407f6a.nq.gz
    ├── 327a98b77e352b22271a1d67dde3a6954d54b0ba.nq.gz
    ├── 34e4dd38c2fabb13af3f8d89857b399c611b2595.nq.gz
    ├── 351cfca76e8ef25bd1da2e3c7e91de88166555f0.nq.gz
    ├── 3541613f495d629df61fe506eba243b43afdf057.nq.gz
    ├── 36d393ea4a86293cca1eb4c8cddf60a39fe5ccb2.nq.gz
    ├── 37ff57bb24b9ca6575c9c8c595cff3cda0e81f24.nq.gz
    ├── 398a7a47364df403084091527405ce8a8250aa48.nq.gz
    ├── 3a361eb6f270425696d080cb15a46ccd79c65475.nq.gz
    ├── 3aad13a3393d74d105e6fc0dc9c3703cef785d09.nq.gz
    ├── 3c0bc8718b2add7bfa75107410b40c92c27df81f.nq.gz
    ├── 3d0db7ed8b387d1ba31453276e8bd1abc9f85706.nq.gz
    ├── 3d5582b65b3a1d29a08b0e48f9368a444442095d.nq.gz
    ├── 3f7e3afd27859148903428946d15631675418b44.nq.gz
    ├── 4028542dfcc93ef3de837de65d97e2954894223f.nq.gz
    ├── 405906c106edd66ed8a93087646dcb2ace175735.nq.gz
    ├── 405b9fd4c776e8a9f163499e71e0890e395a5d86.nq.gz
    ├── 40aead419d35ba6e64c0c207838b54efb8d425fc.nq.gz
    ├── 442d381fd77d5492a32380f956cf196b28350fd3.nq.gz
    ├── 452121200bfa886109730d65b68151243fab5aa5.nq.gz
    ├── 45680465348a3f9bdf04c949769f56e913b81685.nq.gz
    ├── 465bafaacf87809efd061095d2f3f844b4c45810.nq.gz
    ├── 47ef350316c37023b7a0e1b48c42e146cb8c6573.nq.gz
    ├── 4946ba0e42b77117e6543434e921748e4255cb77.nq.gz
    ├── 499a0f3ca317c09d3352c681fefcc236faf9b780.nq.gz
    ├── 4b03923b17c5226aef0423edbf668b22ce98cbdb.nq.gz
    ├── 4b1f4cd7d4733e71858864490b71b63d5283a121.nq.gz
    ├── 4baf9045a04cb0d61751b4a0dcfb516ab3372960.nq.gz
    ├── 4d828ed5c2a54d0772bea286f8a3298897077697.nq.gz
    ├── 4ea12f4586e6c205fc83b568529d9b66a6212a63.nq.gz
    ├── 4eb024ac95446e0e574c3994f103db808cdc04c5.nq.gz
    ├── 4eef5da08e8e9549a5b7fa2d6c0febc02ed13039.nq.gz
    ├── 51679f8988704ee88fc5e55b03c4d0f509dce763.nq.gz
    ├── 51bb44878d589d719b99ef11960d045759352e17.nq.gz
    ├── 523de019d55be6b5054cb77fea43aa86910aaf1e.nq.gz
    ├── 5344faad20a1dd71586e5495a6410bf08486d504.nq.gz
    ├── 54addf309c9265324eae6532417fb111cc51dca1.nq.gz
    ├── 54c878cd9383a172611925566ef92402f421b20d.nq.gz
    ├── 54f17dd6c82a0b332f9ef02be162ffd38ad849ce.nq.gz
    ├── 5616b73d7a4d37f5ee6ab7b69f2b1a43923b72dc.nq.gz
    ├── 563644942f73da5c8a5f2a988c2c96e0f3b9a8f0.nq.gz
    ├── 565c39534607f1791f997ec956f1a638f81c710e.nq.gz
    ├── 56ca6894452cf1b21c3b6c7211ed7f92e6dc685c.nq.gz
    ├── 5810498fe25a75513a08e5e6d00418859642b1df.nq.gz
    ├── 58c611b5ad6d6e0d03af805882c539464ea7963b.nq.gz
    ├── 59fcd78638a2803eb456fd83740d1b9bd129fbd3.nq.gz
    ├── 5a564c439c0f04f094230ad57d29a4d1b85d9eb7.nq.gz
    ├── 5be60adc3adce00f7e81dda9949dd7fb4fc323d7.nq.gz
    ├── 5bf3680d99028cdafd59b2e5231b5304c9c053aa.nq.gz
    ├── 5c44a63e1f07d4f4bcbe3f9f12d0eb10667f4141.nq.gz
    ├── 5cc639e628fe62886946daf71add33b8e9d4b53a.nq.gz
    ├── 5dcbf339c2f9b9b2580df4c82f7434f21bf30375.nq.gz
    ├── 5ec563aa53a019c500278649161c28e4ce42bf80.nq.gz
    ├── 5f510a2dd50a83312dfd4dfb5d6e7f940e735e8d.nq.gz
    ├── 6008efa6820ef0d1ec1edeae2772d39aff331c2a.nq.gz
    ├── 61214946af627d26c41190013888ff5871267a6e.nq.gz
    ├── 615efc1f703872dfd546f75f7c1a62843e8aace2.nq.gz
    ├── 627c52494901e521dd7ecbcba0de530dd5d4854d.nq.gz
    ├── 644aefeabcffdf6277d2a9048f130c76c387b77d.nq.gz
    ├── 64a632de1d405b7ad9fb372c6d8829e2b1b3cd52.nq.gz
    ├── 64e2d6f9e5f57bd4909e2bcca0123d0aa1927221.nq.gz
    ├── 65320a54370c6150f9fa925dc563a6c770b98fc9.nq.gz
    ├── 663958c7467f63cfb19cd1df5cbc4ff5784df845.nq.gz
    ├── 67f8faf16f76acc406207076f61b8fd29e41820e.nq.gz
    ├── 69094f7c59a242c6ca1b3d3331e6b63e8037bbf7.nq.gz
    ├── 6a07cb7a3f23a0e5254a163dd9df2c11ca52d5d9.nq.gz
    ├── 6a42978884c55c4ed0e09451a7a766c664b8d8c7.nq.gz
    ├── 6a58c9df9fb5c15766a3b50632ee28ebd55a1867.nq.gz
    ├── 6ccd7b8eb5958ac24a7bda959b602012de37fcaa.nq.gz
    ├── 6e299e6a211014d539de5a420a46eca3bfa163aa.nq.gz
    ├── 6e53b97811d75d14e3e412570f3669f180c0a8e2.nq.gz
    ├── 702e980b3f9f55ccb2dfee0e0bf9d79c15831403.nq.gz
    ├── 71173fa8369943058e94aae86efe6635ea9c3c51.nq.gz
    ├── 718757966648b54295175c0b424102023146ee13.nq.gz
    ├── 71d2d97c83fabb3fad2edbdbd7e715ffd340a4df.nq.gz
    ├── 71ecb866474ce570834287bbeda4b0c7f2f27ac4.nq.gz
    ├── 71ee69c7d5da9dccb8a83998fd10d12ffa89cede.nq.gz
    ├── 7291b2a51bf4e524b2ec1c8bde348e80a021ab05.nq.gz
    ├── 732ae855deebbaf87b898f66c1e6062211af06d9.nq.gz
    ├── 7333a52a67a652d162123718b9cede38419746aa.nq.gz
    ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
    ├── 763daa0e0193f420c515228b67c9961d937f96f9.nq.gz
    ├── 770912b219a098115544f84bf49871e188f0a13b.nq.gz
    ├── 7780aa306d8f9bb2555e7006ecaa5a73a08b19e0.nq.gz
    ├── 78d873635a603a1e3c50e4e396d8cd53ee1ac2fc.nq.gz
    ├── 7955bbd1665b2f2c42ad980f6c5fac5f6fdbcf60.nq.gz
    ├── 79f94d5ddc7dc54c4fa63ed27f59b4b7c87dd591.nq.gz
    ├── 7a0667f1353272f2a68b3f1caf58f1c67564c136.nq.gz
    ├── 7a2334f574c205e60e8dc20ec59769dadc9f12d6.nq.gz
    ├── 7bf3b9ca794e037d58769ea3ad6f8d90a41a0efc.nq.gz
    ├── 7c224b682ba87d489715ca686d190639a18e2f06.nq.gz
    ├── 7c7df7f582a7d2dc7ab0306b18e49a899024103d.nq.gz
    ├── 7e15c44b819223950f22f597610412e0980268a8.nq.gz
    ├── 7ea0a6c51c45b24aed9b499c3c8e1b3f06d94300.nq.gz
    ├── 7ee0af98578ce1ca55b5245f6bb12036ce6eeda3.nq.gz
    ├── 7f19d830404771d4658b595e5bcba6e453fa48e6.nq.gz
    ├── 7fa24b449d2f6396902d5306ce82095a7b3d3490.nq.gz
    ├── 7fe0b2461ded77e912565d4ebec27595604fe19d.nq.gz
    ├── 80acb6c2a6e54e266aa6154680ddb06bbca0029e.nq.gz
    ├── 80c4f6605a7f111eb75aa3aabd6cfbbc5292e6df.nq.gz
    ├── 85f04b9f70017ced627b588eb86b557f8881c0fd.nq.gz
    ├── 85f39e2d39c85a40fdbce4f2a905681a170eacbc.nq.gz
    ├── 89a419d150cba1237ed554ec0d2901db741a6433.nq.gz
    ├── 89b838928c8dbb5ae4715761e916d7f327df01bd.nq.gz
    ├── 8ac8cbc0338a6f25a1f9893c2b69471dba3d17fa.nq.gz
    ├── 8ae0a5381ac52d4f8ae65104e0226bec441c2bd5.nq.gz
    ├── 8b2f3c6c9598256c73a88200cc102932bac935d5.nq.gz
    ├── 8bd9d0e1dcc6b9530698eae833ff9293d23e3f52.nq.gz
    ├── 8d1c0fc083bcf74b5dad3fc586f48c51a6df25f7.nq.gz
    ├── 8d2456e7e87efc46f54bf2397bf071625f523df0.nq.gz
    ├── 8df98d490fc4b4b63362ee208ffaff607602e49c.nq.gz
    ├── 8ee580d453f27374555f4f8cb460fb5fa84d0b04.nq.gz
    ├── 8f5ef11b30e17a31bdbda7f5ebab372f6b8fba8d.nq.gz
    ├── 8f61ee4f3d82e9c6d5627e7676c8840434a35699.nq.gz
    ├── 8f77b83c26af783dc6a9d790e1c80735b9038805.nq.gz
    ├── 8fc0d977c4a2fbbb3428551ce0795005d1b6b8ec.nq.gz
    ├── 918b2c85b4e717628ccf362e6fd517a605f0440b.nq.gz
    ├── 91925d3618b9da666aeeffb3ac17f22956767797.nq.gz
    ├── 92932353d815b155233b2c1841d6404e64ecdbc9.nq.gz
    ├── 92c218fe46a0eec7eb4c43fcf9835ce106b975e8.nq.gz
    ├── 940a58862fcd7d31d3ead03dc3964939159c99eb.nq.gz
    ├── 941f227dd3e62a2079ce822ab5a45b5f6167f3e2.nq.gz
    ├── 946b3770594a2722a34f483d98b29314a0330a73.nq.gz
    ├── 94d401452390a46d65d3fec452f78b39fd4f8131.nq.gz
    └── 94f30d2bdf1913de5930b6ddd68823040e5c2fa0.nq.gz

13 directories, 200 files
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

[rust-lang/futures-rs](https://github.com/rust-lang/futures-rs)

---
*Parsed on 2026-05-10 by [repolex](https://repolex.ai)*
