# Repolex Knowledge Graph of scverse/ecosystem-packages

RDF knowledge graph data for [scverse/ecosystem-packages](https://github.com/scverse/ecosystem-packages), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/ecosystem-packages
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ae89b293ab8478612603c9deea9fb0f95c5cd495
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ae89b293ab8478612603c9deea9fb0f95c5cd495
│           └── chunk-001.nq.gz
├── blob
│   ├── 02ee2acc282a7ae942c2d9a57edfcbfea38d246c.nq.gz
│   ├── 03254479eab473372609f5fa64ceb5063e313986.nq.gz
│   ├── 06db006dc347d8281c445af06d079064c37b12e7.nq.gz
│   ├── 09e8406d176c979282a1dc1a3d34b05dde89db07.nq.gz
│   ├── 0afaa4f001acfa56cfc678b0b038f90673da6fd7.nq.gz
│   ├── 0ca3d5339f4f2946244fe2da8d13328ce8693be5.nq.gz
│   ├── 0ecc23a5309f2f82cf5cdbece92007b51c424144.nq.gz
│   ├── 1147747d7b860b6b303a8c7422848dd35f164cb9.nq.gz
│   ├── 12712e541dde1209dffb9ed0be60f8d8de1534d4.nq.gz
│   ├── 1394ea027a3dc6fa61416a6561826be95a26737b.nq.gz
│   ├── 139fb08e141483ef05e8b077bec50733fe3728e7.nq.gz
│   ├── 1439e5131a92e50d7e6aee684ffc069751828126.nq.gz
│   ├── 14731f77468f9c0464f5d094f1dbd6fc90bd4176.nq.gz
│   ├── 15f9f7d3c8c7833108d557d9fb8259e2b7ca61f2.nq.gz
│   ├── 1669e3083e220e057cfcb3561d9bf4f29cbcf7cd.nq.gz
│   ├── 193791e79e052a0ea0e576bdf4616701b87b3111.nq.gz
│   ├── 1af9621ba8e87424195ae043e8c6506979b6d51f.nq.gz
│   ├── 20f9dc993a8e6cf5b8694b2dc1911a05b1a2127b.nq.gz
│   ├── 2339b7de974c04403f067a3645500a80fd6c40a5.nq.gz
│   ├── 247ccd74b9b5305310bdef1cf3c16556f01670e2.nq.gz
│   ├── 25c917e0ea9ecfef76f313e965a84b8421f2af08.nq.gz
│   ├── 26ad51a0ae224b6d834dcc6ee3f4a988501d4ba9.nq.gz
│   ├── 28447e72e8afc36e68de6209f038a57e3fc7a86b.nq.gz
│   ├── 28ad76c15c91ea078a7964fb0b55978b41cde774.nq.gz
│   ├── 29f8f686885c5f2754976add9636bc77805e7e5f.nq.gz
│   ├── 2ab2223e8adb58a5c84721788aae906a544d14db.nq.gz
│   ├── 2b48ceb15d66fe91fbb9a574248adff0bd727fb6.nq.gz
│   ├── 2df173089829cf6f5be50ca5eb8551215c6f430b.nq.gz
│   ├── 2e10af4689fa6292fcf77740537a8d1edc727034.nq.gz
│   ├── 2e163f9e6222b5984704ababe917269d481832ba.nq.gz
│   ├── 333531a2f6b49b62dcd86b92f6bbe456f1cfb77b.nq.gz
│   ├── 3425f4cb9207374a5f15e3269f63aa6e6cc72ad3.nq.gz
│   ├── 353453537abb4c3717e5be6883fa7fd7e7943805.nq.gz
│   ├── 389d0e2c824dae1496a37976a5f742a2ae2d0132.nq.gz
│   ├── 3aa4fa314957f80afa2d0c8de4f1e990cc699ab3.nq.gz
│   ├── 3b74b650334859a001594844abd2fcfc916285f3.nq.gz
│   ├── 3c510d663b05d97490570d6a49f615dc7e1855ec.nq.gz
│   ├── 3c732bb85f9a82c63afa79a94efe3c0fd5b83bd8.nq.gz
│   ├── 3eb2127fa1415a3be8e7fe275205a36b70796c10.nq.gz
│   ├── 40267d2a60af60d9a74c21f4ecddfdcc62669b2b.nq.gz
│   ├── 406ed3ef31f9b8aef1d73677b05ddea40639d448.nq.gz
│   ├── 414e65baf1a6122fdb489904f68981a6ad5da18e.nq.gz
│   ├── 4429543a1c8b39220228b32b968ab5e0d3a97ec2.nq.gz
│   ├── 44eb64df1c08c733575154b095492999c1ce89cc.nq.gz
│   ├── 47db43bad8812c66ee6020ff322a388d589d3c04.nq.gz
│   ├── 47f19a91e1af0689bfe6efa652144ec9cdabadb5.nq.gz
│   ├── 482b3e90e9f22061f4d6ab33517ee15e285728ba.nq.gz
│   ├── 4a9c166349705ad5a8830915b968c3434cb565b5.nq.gz
│   ├── 4b5106631de836848fad238c71ca6d45600190d3.nq.gz
│   ├── 4b6cbb9d13e9560c46a6a712ab64fc96ec49e10a.nq.gz
│   ├── 4b6dcd9c779f5c319145cf26e0947f4f27fb912d.nq.gz
│   ├── 4cfbe1c5dc2db41ed7807b748068f6cdd85361ac.nq.gz
│   ├── 4d1d5b3802ce6c7fb1ce201f08ada448de245e04.nq.gz
│   ├── 4e5859d797396b85d32c8d9f312572cfef0a4d1e.nq.gz
│   ├── 4eb35d3b2ca93d12628acb0f1444955c4d8fc6fb.nq.gz
│   ├── 5537d9395e025e921a230527190b8869aaf4315d.nq.gz
│   ├── 568b20f99fb01a765bb6ae517a81f3f0e230a0d2.nq.gz
│   ├── 56ddfdf60ad29561920acdd60c0b78e6adeb099c.nq.gz
│   ├── 57b0e02316cfe3cf7745507a1a0c5d5cc313f6a1.nq.gz
│   ├── 57f8526977a20b01cf7b0e7636da96ec1fb80c51.nq.gz
│   ├── 596b654edfd6bc6ac261771764c5b81052c49aad.nq.gz
│   ├── 599c871020b165739fc78f0c3f24dd7eb4a1b462.nq.gz
│   ├── 5c3b954e8a9a33147620a9dfe40dadf7e409a002.nq.gz
│   ├── 5cd0ee422db43e6e9a2d5fb670f141245c1d503d.nq.gz
│   ├── 5e446588b3344e774819731d0b23af709b6f4cf5.nq.gz
│   ├── 5ee2851bfe494ef9751f5caa4366b52f436018f4.nq.gz
│   ├── 5fed687ebbcbff79137388d968e8ee6113c02e54.nq.gz
│   ├── 5fffdeb34581f6fdb8765c821d8f22cfdc881108.nq.gz
│   ├── 610fc21b594ec4bb6eaa69d6698fbbdfaa641d78.nq.gz
│   ├── 649604b4dd445070a3b493942a001a773d01d1e7.nq.gz
│   ├── 650ed52ca09ff2564a77cec668dd7c528788e592.nq.gz
│   ├── 6a58020236ed55df80b7568b5037df01afb1abb8.nq.gz
│   ├── 6bd807ccb91c8865d2a679df432f2803380868fd.nq.gz
│   ├── 6da7950a5a3680695bf6d8d8bf9ade0781a11448.nq.gz
│   ├── 6ddfb696ff9fc767b3b25756fa48af89d879e2a1.nq.gz
│   ├── 6ed7fb3ab31b6178e72f3f2171ce393d88e484af.nq.gz
│   ├── 728efc5767bed72ad81a097bb07739c85257f187.nq.gz
│   ├── 72e07ac6d39b866a4880986c2a94ff2808bdc857.nq.gz
│   ├── 73fe8b3d0f93fa74fd43dd913cfae0334c329bce.nq.gz
│   ├── 7c67b797efa61f22b6196fc68b0785a694637916.nq.gz
│   ├── 7e3f562d1e0f23a6cabb2d3406d3f046fed165cd.nq.gz
│   ├── 802aa9e5e65cadeea3854423a0e4c1ce08c37292.nq.gz
│   ├── 8239b517db1ddda2100ea02592f55a7ca9ee9513.nq.gz
│   ├── 84e5e1e05ffab1a10c568c44ba009b4148dd2789.nq.gz
│   ├── 86154f2836b9eb957c3c4f36e1e9e558a432ef7a.nq.gz
│   ├── 8702ba9c9a418c1b7b3951f23c8b58ed33d9b036.nq.gz
│   ├── 87575b5bac9f99b7470b28eeadf243c8cb9a9e33.nq.gz
│   ├── 8786584c03561fcc1505c6b3f73071869f7322ae.nq.gz
│   ├── 892a218379a42990f18749a3556715f5c201e529.nq.gz
│   ├── 892b384774d85d9403f4a78080d466fffbdd8074.nq.gz
│   ├── 8bf932e8e01d32e4001021f672596ba351c52d66.nq.gz
│   ├── 8ca595f57f0f66f6932d9bf0ddb318982d6cb376.nq.gz
│   ├── 8cdd8e18ac8742b0abf4151ebf862e1e0697d0e8.nq.gz
│   ├── 900dad078fcb69015781584f6353387289d86e0a.nq.gz
│   ├── 908ed6ff91c7dfbe7e2e18d35bdd4c2bbdcfeda2.nq.gz
│   ├── 922e98cb5093a56fe845736b4399b5919f4f7063.nq.gz
│   ├── 94a88fe08fcdc3d8e9ed233d9f543b0f6ed9abc3.nq.gz
│   ├── 976f39520ae6902e66c036f631b59ae627078e30.nq.gz
│   ├── 999ef377492ad80fd1c30be12ff6c11d8dfb187b.nq.gz
│   ├── 9e071c474059a9e3e08402663a985de8332f9b79.nq.gz
│   ├── 9ec7564278b0a02b3a4c111c2a65148c322091e1.nq.gz
│   ├── 9ffa0b4ef79b11ce15fb72855b7e00064d4f1593.nq.gz
│   ├── a139df41a8779dd100c664852a826b3a11fd510c.nq.gz
│   ├── a5495e37cf08770380824ae6c77b3e8f7601eeb0.nq.gz
│   ├── a61c7c6705b728152cc145b7e2541437b8736d9e.nq.gz
│   ├── a73a44f6424bc9ae82cfd2f2135bb6006bbf74ea.nq.gz
│   ├── a802f4e289f69a26fc5ef52f57422a2227d45bb6.nq.gz
│   ├── a967338b9796f27d604388b0a1f8d4a16ed013e4.nq.gz
│   ├── ab6d425bc9e1a4a0a1b6d23fa1cb0ee005fa757b.nq.gz
│   ├── ab98bf4b4fc5c1dfc6e5487d795f60ebbc144e63.nq.gz
│   ├── abb93285254fbf8ae93543de3b6add729f2b62b7.nq.gz
│   ├── afaea224e21dc69d195d586f1f83becaf0131466.nq.gz
│   ├── b1e1dcfbff02087dfb6727fed15ad6b2398651d9.nq.gz
│   ├── b37fffef406c7c4f3d2d40ac43cc5b46f304e5b8.nq.gz
│   ├── b44ecc2c25e5fc44700dbbb1e4d3c554242e5275.nq.gz
│   ├── b85dac579d3bfa5c25b2307dc6bffa155355508c.nq.gz
│   ├── b89b1ea665b177d2d4dfc69bf34920df9a38b84f.nq.gz
│   ├── b8c7f3c66c71b01bcb8a1bec303c612f3761474b.nq.gz
│   ├── b9ad65f5b2383b044789dfa82d01fe721c419f62.nq.gz
│   ├── ba0419ccf1f6e4f48a94ec5669503c34ea0324f6.nq.gz
│   ├── baa30aec9ee45189107811c5b5208a77ef027172.nq.gz
│   ├── be10d7128a7bca7aef09078e5c94257864fb8985.nq.gz
│   ├── be5e177842526d6102c1bbacc6517c68f183a8f3.nq.gz
│   ├── c17b07be1d2fdf772962929bdd7327b94363de70.nq.gz
│   ├── c35b294100f2f3020fc0af629dd7b003b4856391.nq.gz
│   ├── c7795c30a847b368c16453fd6937df5ac2e9d790.nq.gz
│   ├── c969ddb070a9f573b0421a96ee104434044ede41.nq.gz
│   ├── c9b3fa7c9a6bae30ed880927a4df1485e6431412.nq.gz
│   ├── ca56efe94d8ded150536d846d71ccab1dcae9f4e.nq.gz
│   ├── caafb68c91a47f6f7f42be4abf3a63f7776cdefc.nq.gz
│   ├── cacf2914b1decb3b61f07864e9e5d64880678d91.nq.gz
│   ├── cc07b17db64bda14966fe50096484da5a4f7727d.nq.gz
│   ├── d2364eacec324bab3c394d3216ab073d547a2ab4.nq.gz
│   ├── d2a2bd2180be37a3f290baa1e9ec1c421f4db99a.nq.gz
│   ├── d329c0d53ec20adb1530106ce12c39a0bdfb7be4.nq.gz
│   ├── d8e906e92129596ea277b5d298decaf2256cd7e6.nq.gz
│   ├── d9f1af47f94a3d815fd1d163525aa859fe5e3c30.nq.gz
│   ├── daadda38b8c5953c74a11e7485acd0fcedfeb8fb.nq.gz
│   ├── dce1dfc9438d76f45d12f42ff5c996fe41c52599.nq.gz
│   ├── dd817b2d4d337f62b37bd0d36eec4e2fa39b62e5.nq.gz
│   ├── dec69ab1ff1bbdda5762ce525fa4a998dbe12cb9.nq.gz
│   ├── ded68b6222127851b1c69fe60671146889dcee3d.nq.gz
│   ├── df1054b4f5b0e7baf096fbfb45234b1b5249a3b5.nq.gz
│   ├── df761259fd62c98784cabae2b1f358b065c1b420.nq.gz
│   ├── e0fa8dfe09ed2fadb4b3d0d8737014c8f039e2ae.nq.gz
│   ├── e24754f8b17be9334518b531c60a234cb346654f.nq.gz
│   ├── e3ee231ab5a8faf83a71c0e900f431a8dd5c78bd.nq.gz
│   ├── e4349fd57920d6e1ca43a2f44f55478770c4c5cb.nq.gz
│   ├── e5834bc42fb97ce46e61fbf89feacd7a6f85f248.nq.gz
│   ├── e67e92ef3ed8300712a80232e0b6072a10ce5bf3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e871b98dd48a67f5636a19779cd6a3d3a4c5b310.nq.gz
│   ├── eba6cbee8920c17507dc01d12800e5079730be0f.nq.gz
│   ├── ec70c51964f34d9680a3ce7860de11c69378ded4.nq.gz
│   ├── efbf3e28f1d01ee70ac76c57062bf296d18cdd65.nq.gz
│   ├── f0640b11a5e714d26b6791627a88ab720e75333e.nq.gz
│   ├── f0df7f4ae72ace678e02704a56f51880453b6989.nq.gz
│   ├── f1c1d84f8c4ee289c4d4fb9110a1412a3ac6e2ac.nq.gz
│   ├── f477ea00895d8d26cb5cbd4c7dd7c5ebcbfb44c9.nq.gz
│   ├── f5ae9ea11aac6e21f3429e5f65782618e7557c32.nq.gz
│   ├── f64674efb8c141cf1ca55516c3b626f799be101d.nq.gz
│   ├── f6942e622efafd39459c0f3c5e5138c5c7f2af9c.nq.gz
│   ├── f724127567b407a4aa0ff9dafd94987ec8e19ee3.nq.gz
│   ├── f80468ccf7118af73d27f9bfc591c4345a000223.nq.gz
│   ├── f9c3f00b839dd813114e7e52e0029e723a5869c8.nq.gz
│   ├── fc2d25614a487441836e8c2c2314309b009a2945.nq.gz
│   ├── fc75605b64712367045f2b51ee7a8c2070be83bf.nq.gz
│   ├── fc89d9a911b29aa98a759a4fe7c40afdb7517bcc.nq.gz
│   ├── fd0d456c9b80c6bde5c7f9cd065dae98f2a042c0.nq.gz
│   ├── fdc0b670f8c922a566b23e6ff3eb49035e94c7de.nq.gz
│   └── fe2aea419a996425a5feddf1c0e68cd8e996ed3a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ae89b293ab8478612603c9deea9fb0f95c5cd495.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 179 files
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

[scverse/ecosystem-packages](https://github.com/scverse/ecosystem-packages)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
