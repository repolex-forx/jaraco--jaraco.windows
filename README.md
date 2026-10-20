# Repolex Knowledge Graph of jaraco/jaraco.windows

RDF knowledge graph data for [jaraco/jaraco.windows](https://github.com/jaraco/jaraco.windows), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/jaraco.windows
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 26c631178124b716ba25740efe55beb23f717030
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 26c631178124b716ba25740efe55beb23f717030
│           └── chunk-001.nq.gz
├── blob
│   ├── 0057303ca794920b1bff8fefeb5480461447ad9c.nq.gz
│   ├── 07a9bc05ee41b5d0c56ee25566bc0e90b1b23610.nq.gz
│   ├── 0e03d3cd144a56ea1f4b2aa480c1ebbf6957b4f9.nq.gz
│   ├── 0ef024496dac00398810213389e87585c65cd2fe.nq.gz
│   ├── 10d412f406891b9683f832fcbc134c9bdf4f916e.nq.gz
│   ├── 14defac24ecd8d5e19c47e404e2f5423f00afcf5.nq.gz
│   ├── 175549d716a4a0e717e7b91538930a8533d9aa0c.nq.gz
│   ├── 1d971f8136425b38b9306b4ed030c3aa5a3b8d03.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 225dff6ae401c5a43ee53feb600b2952d7283e95.nq.gz
│   ├── 2805cbe4875b82a4122ccc27c4108bf146ced864.nq.gz
│   ├── 297563bf993004c48a7af5703a55fc3d695c3739.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 3337cba546956712a8d949ff523364c1330e140a.nq.gz
│   ├── 3575c08c42fd794c898bbaa331e0e5af3a457379.nq.gz
│   ├── 37bddf2d26115b37cfa2946712b1229b83242d09.nq.gz
│   ├── 37fe4d4cf34b1ccf1efb6b4b4cd4783e90b2fa30.nq.gz
│   ├── 38e3c69138a600ac2e0b6b3209201bf0c0eeded5.nq.gz
│   ├── 3a7a3f25334fe447a720eca5d59feb533fa57b09.nq.gz
│   ├── 3b3c4f0eeaeca5646956bbb215c8f87fc4207b30.nq.gz
│   ├── 3f1a845b84d821cda8c6a2dac2be6e099f81c215.nq.gz
│   ├── 3fb4d98b4d0362ed8d0329b3196bbfbfccd38c8b.nq.gz
│   ├── 459287755ed5c9ae5f19cbe7abd9418e3dc9ef6f.nq.gz
│   ├── 4a7521fb00859dd152014f3cdd2d7b5a257651eb.nq.gz
│   ├── 509c0436e2d95611de79923b9ecb30b056468fe7.nq.gz
│   ├── 5219b3702d4bb7c5553ccab787d503e04d9f3177.nq.gz
│   ├── 536bb8d08ef7f273f0900bc48254cb667d7a8426.nq.gz
│   ├── 53ed74035f84d7a525137481fc605d382a833b95.nq.gz
│   ├── 54c164aa8b96c80b333dd7e9431e08010c0f7ea7.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 5945df655ea1af1b8e7f98a91b1f01a7c2e14cb7.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 64ebfffbff0d94c2c0df83cc1ff9deb877650423.nq.gz
│   ├── 658155b455c6fa0fdc795d0a9fc2224a82c78203.nq.gz
│   ├── 670d50f546ff52a1064844fba8933750034edaca.nq.gz
│   ├── 6ba869393edb302f0c06af856c841936a29f2362.nq.gz
│   ├── 6dae5cada9c663d790bcdf630419740e5f042c86.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 70a190a5e068418bd563ddf8d04cbec4fd7a1326.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 7332906b4738d858df61730409fdc6e54b2c87db.nq.gz
│   ├── 736de57c7746ec95eb06834d2679865e54e3ea2c.nq.gz
│   ├── 75714c3e215a97f0763573abfb614593830664d1.nq.gz
│   ├── 7b34289473195a16a6d0f89b1a39c90463296e27.nq.gz
│   ├── 7fb6a49749819f3a8ecd15f8756be9b5f28672ae.nq.gz
│   ├── 80a751f85e48749d976ef070dc6ce197274c4209.nq.gz
│   ├── 813380e3b95c36042656fa3967dc4168dddd6919.nq.gz
│   ├── 8453d05e407d3197ebda2d322c46074c3090bfcf.nq.gz
│   ├── 886cf0f92997e87f24f6c05c966c61f0507ce09d.nq.gz
│   ├── 915950e1bdad3736b44befe1753f5bf3d465377d.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── 9c6289db7b3746410205edc69e1f238d146db281.nq.gz
│   ├── 9d7c3e39c48536d805f52c41015d120681fa1c57.nq.gz
│   ├── a78823649dfffdb46d8af5ec50fd5c2ccb4f17eb.nq.gz
│   ├── a9742d9e5526fbaf7b05ec4b26e3c79f75b1a77d.nq.gz
│   ├── aa06f33ef98af1e12f190e23ca5829638760155a.nq.gz
│   ├── aa1d1c73cb37b9d2ed5811bf4d6e45b3911378d2.nq.gz
│   ├── ab40fb0f30c0318dced4d6170a96cedb6e71da73.nq.gz
│   ├── aed3f0317e9202b1332f8c7859e5fbd0525a0d9c.nq.gz
│   ├── af7174dc160e023907996e198de31644ed70f5bc.nq.gz
│   ├── b06dc6d2978654d052a8c80b715119981528e89c.nq.gz
│   ├── b1cb7864bff34b6167b8eed9947608133f37a8ea.nq.gz
│   ├── b43de8760f59f4b9f339f3698dd799308b29c6c6.nq.gz
│   ├── b7403febda97d10aa52277c41b8758f92e931517.nq.gz
│   ├── b9fe153f961e2a935d4faca069d6c667b5c6ad5e.nq.gz
│   ├── ba69affbd763d1c241219c4e3d91f5ba583a1008.nq.gz
│   ├── bd72c58ac3b93490aeb355d03e2d4a45cefd3044.nq.gz
│   ├── bf8de6912653e626de4be717fe698704a6691a92.nq.gz
│   ├── c0392fed2f735f028c9b5f24e5febd263e8cadf1.nq.gz
│   ├── c1cc70eb97c1e92aef5528923c693df1b2303180.nq.gz
│   ├── c8b60472c4867c7f0a46a3e9ad3b1d15661a11e2.nq.gz
│   ├── c9ffb9c0fce3687ddd03d956063661422dbed62f.nq.gz
│   ├── ca57f45fa2486606e217d24a10b391eae93b9e49.nq.gz
│   ├── cdd4064ca1ad97228698cc682ff265daba1ea6be.nq.gz
│   ├── dce0ce7ef1c32fe00d9449caecb9351899bafaf3.nq.gz
│   ├── df50ca61b05110a455b5e9e71dda6e3ea92e4536.nq.gz
│   ├── df6eed416dbf63ba4a859ae57db80c0668a1e246.nq.gz
│   ├── e05a3d4a2ab888e32952006d8cd380864368db5f.nq.gz
│   ├── e592d6776b56f419b8870bdc68061fab4fea6e40.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6d069c07c671420c64fbf6a2f5e06a0cd741079.nq.gz
│   ├── ef3cad52a58ed4021c30638d72771991968a3beb.nq.gz
│   ├── f89a047629d3e3913bd7d795df81a295cb4e23dd.nq.gz
│   ├── f8aec6f62b112fc44b8691a6fc9857d1bba6700b.nq.gz
│   ├── fe9649b3128789d87e148b193417c0df1d6b61dd.nq.gz
│   └── fee6dbf11da8c1e8107a761251e295840e017660.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 26c631178124b716ba25740efe55beb23f717030.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 96 files
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

[jaraco/jaraco.windows](https://github.com/jaraco/jaraco.windows)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
