# Repolex Knowledge Graph of hyperopt/hyperopt

RDF knowledge graph data for [hyperopt/hyperopt](https://github.com/hyperopt/hyperopt), parsed by [repolex](https://repolex.ai).

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
rlex download hyperopt/hyperopt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9834314879c09c13e0b8e93eb678408ba46441a8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9834314879c09c13e0b8e93eb678408ba46441a8
│           └── chunk-001.nq.gz
├── blob
│   ├── 01219b1fff42bcb701603856da45239ec13910c6.nq.gz
│   ├── 0126a7415cc6d17d29b6ce9470df35e501a2c203.nq.gz
│   ├── 01306a996162fe69509716d50d5b57b65583ed0d.nq.gz
│   ├── 041ce903c0c60a166a625a2c68c85089bc02c7c2.nq.gz
│   ├── 062cbc75ad00826704b526e6de92bcdff7dfda9a.nq.gz
│   ├── 076e4be6d6e03aec49661765983ccf04e79dd4d0.nq.gz
│   ├── 084c6bd0507b7be7b96bba28469a6f1cca464036.nq.gz
│   ├── 0888a2ff0eb029a21b9f6982d5cac7afe95ced62.nq.gz
│   ├── 1039e455a569c01fd151303582d43bd1be7358f3.nq.gz
│   ├── 15186eaa4ea710aa9adcd0af7262e3598db25c74.nq.gz
│   ├── 17e7b2fff9d085ee6315d887a187874fd67ea1c9.nq.gz
│   ├── 1b3acb628cc09addc1ff118111afc22d0731a62c.nq.gz
│   ├── 23c0438c7d4b1d20e9e9feeda8152d921bd2a2dc.nq.gz
│   ├── 2579bc4a4cd1fcb016dc170dafddf1bcd76c89f7.nq.gz
│   ├── 2a6400dbc3ae4030c86b273bcdfdf70f51e7adc3.nq.gz
│   ├── 2f3b417bb63d250f51b2701ef3b0fc7605eeb186.nq.gz
│   ├── 319dd320fc7b970f0fb4fecdbe99262179dd27a8.nq.gz
│   ├── 32a2661160408fa437a2ccf218c902ee9172d5ed.nq.gz
│   ├── 34c23125554388e6c42a82224cd29f53ba93c275.nq.gz
│   ├── 34cd29044a1dc3e211ca847fe47aa5eda0e7c77b.nq.gz
│   ├── 351726d6ecafebfa1ff3da42ee47a5f767895100.nq.gz
│   ├── 36e2bebd70e1c3c4a2ad17050b5660152560dc8c.nq.gz
│   ├── 397bd4f60ec9440a5b19026508bc261d8cf4b969.nq.gz
│   ├── 3b3866a2f000cbbe80bd0ab9e095cbea865011e4.nq.gz
│   ├── 3f4450b6a6995b94a227dcbfc46b834c717f8868.nq.gz
│   ├── 4022b9f95a2089ce803c8524403d7d25aacad758.nq.gz
│   ├── 408458449ac2d72fab2adae82927f0586c39a1cb.nq.gz
│   ├── 41048a68eff22f96ef90a8cdbd012f0fb48d8728.nq.gz
│   ├── 4159fcbe676f81af822f537d7209027aa3a08580.nq.gz
│   ├── 462d206ce1d4c199e9da5587681e3196d5db8ac4.nq.gz
│   ├── 48062b2f63d8267fdc0bcf38580fd4e89eda6ca9.nq.gz
│   ├── 48ab2ba29e8a96fad000cd02c467fd767b9c3122.nq.gz
│   ├── 4a88ebfa0ce5091e82d9b69d3b10d21fdc270ca2.nq.gz
│   ├── 4acfd1d3db2991f2372975c025de2c8e8ee6a5a8.nq.gz
│   ├── 4be4771aeedc35731a94f2913eef696575bc1529.nq.gz
│   ├── 4e6c4a8af733385ec5171d27bc1958ab5469b84c.nq.gz
│   ├── 52736a52e2ac0d5c83e6919aa96d88b199c5649e.nq.gz
│   ├── 55b1ca00ea2979eb6c954423bf672640a54c8f57.nq.gz
│   ├── 56bff14da63274a6cb49cbe37b71a65448a3676c.nq.gz
│   ├── 586020b7d58e49e6484c31c258ca10ae1ec12176.nq.gz
│   ├── 5b87d7cba89af5c3e1eb8e4976622c49478b9953.nq.gz
│   ├── 5ca7c973975209c934f2b9f1056619deaef175e0.nq.gz
│   ├── 698b95e4fee90067184e7f03129b9031c997cf82.nq.gz
│   ├── 6b65d05bf7cef5034e1568281cb322b32f79a918.nq.gz
│   ├── 6bc0d4fc517fc83595242d835ee731c2f4323bd5.nq.gz
│   ├── 702232cd254abfd075a7f0cd57f2a8e68456ca6e.nq.gz
│   ├── 714929498ea3a1586bcdbcd29e19e90446d7180c.nq.gz
│   ├── 727b6cf55026b29e95bc8b7a87c858d2b3d05d8e.nq.gz
│   ├── 7415e68b3163d37839b3c42e8c2849683798a987.nq.gz
│   ├── 74b171750842e9cb61e398b560250346e71a78d8.nq.gz
│   ├── 79c0cc7a5194458ce6c5c13242c4cdcb443e408e.nq.gz
│   ├── 7bedac5b6e8419f0e9a453fb515bc2f51673a8cb.nq.gz
│   ├── 7ca5c6ea43c94ca6f23675d7f5b5f77639ba1785.nq.gz
│   ├── 7fd6b89a314397138bd155168713281511461fe3.nq.gz
│   ├── 8267537688fbc6e737a289ba4ca4d383a7619050.nq.gz
│   ├── 82c8544f2aacd534e99c1e04ef41bcf30e64ec31.nq.gz
│   ├── 8325cb291a45e92d201ca75f2ec65d14c8d13a14.nq.gz
│   ├── 83f4d4a4d60f1590fb890fad49d85c968f49a087.nq.gz
│   ├── 884a7a8828140dfd796b5743eaf30c45d82ca474.nq.gz
│   ├── 8bb1d7e7fda87172b67ad049d91bd587f66ef792.nq.gz
│   ├── 8c06c7a0dd70e953881c356fc6103e6fba4e257f.nq.gz
│   ├── 8c207afdb6e2e18e7ee5915101484d4bb8cf175d.nq.gz
│   ├── 8d5526bbffb82c69972bd1e7afeaf3f70e29c413.nq.gz
│   ├── 8f2cd4ecd483d3ce57b590bed7f1a5454b37bb74.nq.gz
│   ├── 8f78963326b2d5524005f56251aa111649abb143.nq.gz
│   ├── 912979d119c79cee28edfe5c47a61eaf2821ba41.nq.gz
│   ├── 91f0112db6dd5992433551476ad9de71f4cfed05.nq.gz
│   ├── 996b4d4f03c16076b2ae8cd7d4a4082bc76293e9.nq.gz
│   ├── 99ad29d9de910c2b6caea5c6bd931e2f39c44df4.nq.gz
│   ├── 9b9e1f3833e98b18eb329a463aada7d37ab3d840.nq.gz
│   ├── 9df84010c546edc356a2f8e1c62eb466407a4045.nq.gz
│   ├── a095ef0de91c16aa3175c2bbf24c457d2e81fa18.nq.gz
│   ├── a13106e46c87e75095e5f7f6716f556f3d04aee5.nq.gz
│   ├── a1b007986a5a847f4edbcc425cb57b284e94c31f.nq.gz
│   ├── a2fcd75a19b145838b9b2ddbb11304600b899162.nq.gz
│   ├── a45d447d0a8053f0f74b5c8c23a6a96448ce7598.nq.gz
│   ├── a56858997dbab73f723eb23182340d531a2f07ca.nq.gz
│   ├── a976c6f7d45a45a89f9a47c8064544c7a3d73cdc.nq.gz
│   ├── aad403b419cb397fedf49df8c8cd9426af538199.nq.gz
│   ├── ab8782e4a3932e485a2ff20813aa2a0f3de4d2a8.nq.gz
│   ├── ae45f150ce4234e32afc187a4cce5648841309a9.nq.gz
│   ├── aeb94d315eb50bac7c5c86af493ec77c686a3bc8.nq.gz
│   ├── b0c3300b42dbfd07f044e3e586cc86532c605bb5.nq.gz
│   ├── b11161446b9588d62c93a6125d8423382ee42349.nq.gz
│   ├── b2caa39453b796e5c1bd3399320f5347502ae5de.nq.gz
│   ├── b3220be8c3cd73702b166f261c7ae7c1d83066b8.nq.gz
│   ├── bb04fb3767ee51d3a36adbb0b87ccf28ab323a12.nq.gz
│   ├── be44fb87bc19f65d48a0143dadd8e8a4fbd41925.nq.gz
│   ├── c0fa8c155c52247e5d3aa294481bb8a19d88abf5.nq.gz
│   ├── cd5195c221e9d74457b0b3c60dbd919633eecb8b.nq.gz
│   ├── cd925465a52485596e342a7a23c81c7ae5d93b0e.nq.gz
│   ├── d36210843e89317135eb79c0a91e08711e046c78.nq.gz
│   ├── d7150b77363e8cc5c482098e72ab4528f2e9cacb.nq.gz
│   ├── d7ea25c52fc79b02fd276f66a1301531a3ff45f0.nq.gz
│   ├── db3fa0f2378021f6fb0dcd06342c5f313794f0c7.nq.gz
│   ├── db8b20ec62b7369f510a1dacfe66d3c9c4bcdbeb.nq.gz
│   ├── dd2d5ff6551726719cb6986e3531e3eb6cb8f478.nq.gz
│   ├── dd51fd0725962611fe406acd566f10887bb1b53d.nq.gz
│   ├── e38383b8f618921720d03a5b74774c05e3e02f8e.nq.gz
│   ├── e5974680a671e145dfe86f249a859069ab7d6630.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e74ca882fa0503a1c4a23af5528a349179685c3e.nq.gz
│   ├── ef2da718dce4955f530bebf3224a07d62ea492d5.nq.gz
│   ├── f12c204b0fe4a0b3546b395a358a6842feed348e.nq.gz
│   ├── f17a977b192d433c2fcac3da1dde68c8c3a076e0.nq.gz
│   ├── f20a87e8e0d60e5c1c1fa5edab9a3cca01f0c78d.nq.gz
│   ├── f28f648791b15c67bcbb52b7c4fdfa93300f4ef0.nq.gz
│   ├── f45a091013bf8ef0b55909a0d016240ee63af719.nq.gz
│   ├── f553a016e451d17fbddda66f180dc6a95e8dc524.nq.gz
│   ├── f67ed3a4097bfcad9bdfd0815cd04fd414836487.nq.gz
│   ├── f8366d576a907569f121edb679b1fbe744e7ad71.nq.gz
│   ├── fd19aabda0bbee58ca7c33fcb83c795d7dbf52e9.nq.gz
│   └── fe67eeed8db1ff91492546357bceccb61a0eedce.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9834314879c09c13e0b8e93eb678408ba46441a8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 121 files
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

[hyperopt/hyperopt](https://github.com/hyperopt/hyperopt)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
