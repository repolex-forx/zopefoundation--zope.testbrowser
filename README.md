# Repolex Knowledge Graph of zopefoundation/zope.testbrowser

RDF knowledge graph data for [zopefoundation/zope.testbrowser](https://github.com/zopefoundation/zope.testbrowser), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.testbrowser
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c4936bb343f486cff26062daf68b5308d554c042
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c4936bb343f486cff26062daf68b5308d554c042
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a942f79c8e707bc4e0c35afb569b18c1c550d4.nq.gz
│   ├── 041b025e2c7498f746599fc192d5636e1a55be6c.nq.gz
│   ├── 04209fa89e63c8dc72acb019a87e0cdbeebc4944.nq.gz
│   ├── 070ded7761404f41afbb1e5dd110ce4a87f77f75.nq.gz
│   ├── 205e5c390d09ae73f7828bbbcea5dbde616797e3.nq.gz
│   ├── 24eb2ec828b4b2a729073663bd1784999cc583bc.nq.gz
│   ├── 2b0b0a4b1f90aaadb7209bc484f4c6d642b2c2ac.nq.gz
│   ├── 2d365fe99ec9350e5d26caa3c952aa14f68ba1c2.nq.gz
│   ├── 2f244da57ee9637216a00c377c2b37b2d71e543c.nq.gz
│   ├── 2ffe386fa804d692f7d0c202cf820d438f2ab935.nq.gz
│   ├── 360f2755638d6b7bcc377d558c2e8e861b425eb1.nq.gz
│   ├── 3aba6bd47481de3f276dd297b9a7675676361e32.nq.gz
│   ├── 50da26782b0389ac4ac23ddd038082f172428e82.nq.gz
│   ├── 5cd13d210240d35041618ab9cd52980a05a0d860.nq.gz
│   ├── 60805bf62c672e109bd42c9e074dc1dd6da652b1.nq.gz
│   ├── 623fa469a6a921299e79918b06678a76f9042013.nq.gz
│   ├── 6c02df119fd535073c0cd8d93d20f38ba1e56a8b.nq.gz
│   ├── 7282f422ae7b1678e0e600dbb07b7f48f9eb48df.nq.gz
│   ├── 7e8c8510985ce49cb71f43c72580ce52632588c7.nq.gz
│   ├── 9b7211cce30288432c1ea2731663f0cfd4e60d1b.nq.gz
│   ├── 9d28a2929f5fd0967479137e93afb3d03d417cd6.nq.gz
│   ├── 9d92d5848f5ac8d3d94e4586c3cf8491661a1802.nq.gz
│   ├── a11a45f58fa7a25999b4752c50b5f612b4797fd5.nq.gz
│   ├── a6e465617815920cd8d818001562f8ccdeca775d.nq.gz
│   ├── a9266aa7061e524ef54fe50b2812c4e424a5315e.nq.gz
│   ├── b31a5ed4d8dd24cf01c15f69b1bb4ed7a77bb6b0.nq.gz
│   ├── b8581dd898cbb33e63961b4d181ff0ffbe5d03ee.nq.gz
│   ├── ba0f571aacc69aac02a1cb60141fa350931093be.nq.gz
│   ├── bc14e699be9f685684507ae5b5d5675341c8fdfd.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── cb80eea6d444bbe62077177bf3d2924f0c2cd3c6.nq.gz
│   ├── ceeb9d915d82736c290a4495ba28271c92d2f3a2.nq.gz
│   ├── cfd5f997dcef59116c0710a889242e5b119c6e5b.nq.gz
│   ├── d53bd1ff4a4bd4697d9a677141b24aa2eb59f892.nq.gz
│   ├── dd61654e6325f8ef36cf0e223e8f7f8d9a76f1f3.nq.gz
│   ├── e184fd8f41cbc229060cf69967d916bf6e2ddf2a.nq.gz
│   ├── e3579011e1a5792ed2adb52fe79f1ac001b9c3bf.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f507feda73c43de02c9268ef502bc4c3a2ebf32d.nq.gz
│   ├── f54089314768f7ada4c90adc2d96e46ebd44eaa0.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   ├── fb41befc52a282fe77044d0748213e3af3ca1bb4.nq.gz
│   └── fdfd801631044da0662ce6a1e3311babc659ff84.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c4936bb343f486cff26062daf68b5308d554c042.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[zopefoundation/zope.testbrowser](https://github.com/zopefoundation/zope.testbrowser)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
