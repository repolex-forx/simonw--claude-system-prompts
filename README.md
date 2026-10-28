# Repolex Knowledge Graph of simonw/claude-system-prompts

RDF knowledge graph data for [simonw/claude-system-prompts](https://github.com/simonw/claude-system-prompts), parsed by [repolex](https://repolex.ai).

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
rlex download simonw/claude-system-prompts
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1f401657b37d8f8e2c4bba39320954b605b05724
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1f401657b37d8f8e2c4bba39320954b605b05724
│           └── chunk-001.nq.gz
├── blob
│   ├── 01eafeddd094fb806da4d9d94536822fae59dcd1.nq.gz
│   ├── 0492bba40f1e93403510ca434057a30fea8ccb9e.nq.gz
│   ├── 0741dceb131814fc0f13b98179ab1bf9597c7032.nq.gz
│   ├── 0853c84e102ede1a143a4e214c5b3985b16eac74.nq.gz
│   ├── 0c365e507de7d88d3b133b489e464b9cf767862a.nq.gz
│   ├── 11550f434749a5f160f1c5ee929ab0d19fa63c91.nq.gz
│   ├── 1444407b8d5541b0881852a888e145e9790e7603.nq.gz
│   ├── 2205db32e4d5e5c81a3ac49c84c1eb096f1c24bc.nq.gz
│   ├── 2f1bdf5c2caa3739fb6b0e1f6f18deacb2aef4a5.nq.gz
│   ├── 30fddcd7f67d0c41551667b33f736efa65da2807.nq.gz
│   ├── 315f2b0952520efe8facad83c47b4c5eb82606cb.nq.gz
│   ├── 3199ffed42d7923de9ffb54765d907b845c4a4ca.nq.gz
│   ├── 340a10ee7e835649b68581ca689cbf8800c00b0e.nq.gz
│   ├── 3bcbf52d8a11eb6f1c3a6721719976c0e764aa02.nq.gz
│   ├── 3c836393b7572b937338447ca47dd84ab1e4fb19.nq.gz
│   ├── 3deff29280986b3c1d2a36c8b40def5e540d0679.nq.gz
│   ├── 3f12c08f828139e92e81b3aebf091e9a703fbd9c.nq.gz
│   ├── 40f202d7ff91d666b69b00e43749e691b84bf8c6.nq.gz
│   ├── 441859ab833014f3b2f81658efacbd0ea7e96093.nq.gz
│   ├── 46208d1edd0d79cb50061bc6e358864d75876628.nq.gz
│   ├── 46ab494722544f81432397a049de4ddc25228ec0.nq.gz
│   ├── 4c1f7027278498ee0467bef14a3ec73c59337a17.nq.gz
│   ├── 4d154183f26b1762924a858a6895fe2d61d38273.nq.gz
│   ├── 4da5b43e1f3a6e77e9f5a4582bc2fdaf8a9ac7a3.nq.gz
│   ├── 522b0f6927a1a97644df1c4fad858eea4689ac4f.nq.gz
│   ├── 541f085cccd75ae7da192e414e910cf0b6b0e66b.nq.gz
│   ├── 56d988046558453b2d363cb7fedde89f2dcfa789.nq.gz
│   ├── 594ec65ecbd08ea60f782c3dd2772bdbb940b73e.nq.gz
│   ├── 5cd23c9e99130c4aceefbcbc2893b94fbadf9475.nq.gz
│   ├── 60d2ce508df6e84575543ef98786f48de4e04073.nq.gz
│   ├── 60eba2110d75894dbb9bb8e36fdd49177a415716.nq.gz
│   ├── 6224053efc32756c202426d771fb25e6dc34651e.nq.gz
│   ├── 6420629b0f9853209d768b703193ea8c77178ae8.nq.gz
│   ├── 66e9fc116878f59fc75c42f27425a02cab3adb79.nq.gz
│   ├── 7143b6a34cf70bb1bc1b73ee9f01595cf3ad9665.nq.gz
│   ├── 76c86ae70f4e917c05aa3380d4980fe9e6e4fa72.nq.gz
│   ├── 7a5c0e12620c5e140feb9a3d262430dcf307d80b.nq.gz
│   ├── 7a71e1faa510e276d8fb43985f4356b39c312959.nq.gz
│   ├── 7cca97701841b6e2827beaf577ae48e196138ecf.nq.gz
│   ├── 7d61155a1311a9d08211de1507872b50d2ffb989.nq.gz
│   ├── 7e000991c075507650a635f1f047df8e3714df48.nq.gz
│   ├── 7ef96b23d24d59483ccb05bd5542107d661ba5c0.nq.gz
│   ├── 7ffe81e1a9c766e568ca57e935aeb6ae8a58ea76.nq.gz
│   ├── 812e052786f6b5eed1f2249d74e169d16f278cc2.nq.gz
│   ├── 8183bc389d00d7f930370232c0b094af86f6f40a.nq.gz
│   ├── 8846ba37c6e75c78716a349547ddb31caee4da59.nq.gz
│   ├── 88cd4ed6ab3c516b9b4392d13fb7dbed23fec668.nq.gz
│   ├── 8b50d8142346e57817ba4db96ffa8ddd24f7df2f.nq.gz
│   ├── 8b7daa32c5a741413505c6e6882f0965c8dc926e.nq.gz
│   ├── 8d6cffde2ba51436969c337fb180a1b383dba3de.nq.gz
│   ├── 916a63846cf07f6a205b608229bad5a17d88dada.nq.gz
│   ├── 9698f82d16b7d58f1ce3316d1a8c1ee16da4ae07.nq.gz
│   ├── 96cb2759e50c1bf77c85bfaf455d3ba32c9bc22f.nq.gz
│   ├── 988cf4df928eb42adc035767ac42a9256e180550.nq.gz
│   ├── 9d1db666cead75629c40404a41cd69004f9bffb5.nq.gz
│   ├── 9f124f5b576fedc1a4535630af79f6f78f2f0a12.nq.gz
│   ├── 9f2cf067eee06f1d99a756fdb6efa414cb2379ba.nq.gz
│   ├── a246f7748bda076cfee58c1a62084668c6a8d2ec.nq.gz
│   ├── a26099ca72c0e33ea648413913b6db752663727c.nq.gz
│   ├── a285cfee7d58ecd161b4ae4e583fe0efded80044.nq.gz
│   ├── aa1467c29cf1d85607a1998567cd4ff90f77e967.nq.gz
│   ├── aa72e8147d7aa2d81c39b91a519a90c973ab52be.nq.gz
│   ├── acb788ecfa3baed9909c9c3c936949338fe481af.nq.gz
│   ├── ad5748e6deec62a1c648b6380e1016a4e68adf4b.nq.gz
│   ├── afe608d2a9174e0e5f02e66cac0c6ba906e3218f.nq.gz
│   ├── b417febec1101697fba97db82a34bd8c14b20acc.nq.gz
│   ├── bea771fcd5ccd0eff881291cab649b5cce8ad708.nq.gz
│   ├── c1179af2010c946397f19e5f5127b4214c8ad520.nq.gz
│   ├── c18dd8d83ceed1806b50b0aaa46beb7e335fff13.nq.gz
│   ├── c2b6f7b462a87bac07e6837688cbd1bf9a004c44.nq.gz
│   ├── c886123f68fc8e8b8470b74c8887f47ed446b41a.nq.gz
│   ├── ca61b59ce6de2429f15030df82a5023643d29d67.nq.gz
│   ├── ca966bf08ea2b1b841e72bb7645abfcd37b43050.nq.gz
│   ├── cafc81e482278ef17b9fef2facb4750d91723a5c.nq.gz
│   ├── cba43d72da53e1a3e7163037e5fab963f8edee48.nq.gz
│   ├── cd26c15fc7c9fdc1c47355eb549be116d4a6951b.nq.gz
│   ├── d024bf7ebaa2b445d8e6e07c187a93f20faa1949.nq.gz
│   ├── d03cb34c5b7ca2031653147ce0333faad556f530.nq.gz
│   ├── d363f83873a664571aa4a57573e5e59ba9dd9fc7.nq.gz
│   ├── d794b95c2145ea82500519a8ecea07cfc18c7824.nq.gz
│   ├── d83b2049ab622f1e95455be6c127927e9db066d0.nq.gz
│   ├── d8ad3f0d3ffd67f0cb227a2f6f135e2c20aacd3b.nq.gz
│   ├── d8d996cb69905d72ea9f6b53d81e546bf551f7cc.nq.gz
│   ├── dcc996112550e9c16e8a3c40893797169616819c.nq.gz
│   ├── df809074804759ff8bd4210b3ce48031fa3d8eeb.nq.gz
│   ├── e5e875a16d6d012f214df30e26f48389414ceb3f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6f4e9bde2c61bf794a7a9510991a293c4cbff4a.nq.gz
│   ├── e74fb866c194bae7d0e0134ac8d4f5550a72df17.nq.gz
│   ├── ea5d8bf9d724869cd89297d956f3c27df5d509c7.nq.gz
│   ├── eae6637304e73fe240d44afe0350da9ef685535d.nq.gz
│   ├── eb149928a4eadc6f1f85d9192186d615aa93c6ff.nq.gz
│   ├── ebbc132237dd9a09dccbd03f373d4f356e428cb6.nq.gz
│   ├── ecd7cd7fd373124fbd4f4620f2f9f288e2c059d2.nq.gz
│   ├── efa5e11ee7abdf75f4169eea344714011a6ee92a.nq.gz
│   ├── f10ed0809b5595ed5f81d993892dc53d49783271.nq.gz
│   ├── f2373b99a14fa7a649cdf2bdc48d8456f07f7f46.nq.gz
│   ├── f4bf796b6631a4436d35e20da9f72df2b707a9e8.nq.gz
│   ├── f500bcb47f7b626534de47a4be2ae5494c588402.nq.gz
│   ├── f95ce4f4f369359c33d6e076e38807278a8b4676.nq.gz
│   ├── fcc3d1335eb2c91e01af9ec770e97c8c6a5eafce.nq.gz
│   ├── fda2abe5da36f62fbb5cb27be4fb2d7a13d9a1cf.nq.gz
│   ├── fdb145812f087171cd83f2156359d87676cfe414.nq.gz
│   ├── fdbd207491f963cf571327645aec3be1e6dc9438.nq.gz
│   └── fe88c20936df5b06c57a1d50534981944d4f3574.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1f401657b37d8f8e2c4bba39320954b605b05724.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 111 files
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

[simonw/claude-system-prompts](https://github.com/simonw/claude-system-prompts)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
