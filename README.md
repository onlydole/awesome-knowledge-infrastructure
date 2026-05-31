# Awesome Knowledge Infrastructure [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools and practices for capturing, connecting, and operationalizing what your organization (and you) know.

**Knowledge infrastructure** is the connective tissue that lets people *and software* find, trust, and act on what an organization knows. It spans capturing knowledge (notes, docs, decisions), connecting it (links, graphs, catalogs), and operationalizing it (search, retrieval, AI assistants) — from a single engineer's note vault to an enterprise's internal developer portal and AI knowledge layer.

The pieces have always existed in scattered categories — wikis, docs tools, search, PKM apps. What's new is treating them as *one layer* worth designing on purpose. This list is an opinionated map of that layer.

Curated by [Taylor Dolezal](https://github.com/onlydole), drawing on years of work across open source and cloud native infrastructure. Contributions are welcome.

## Contents

- [Foundations and Concepts](#foundations-and-concepts)
- [Personal Knowledge Management](#personal-knowledge-management)
- [Documentation as Code](#documentation-as-code)
- [Internal Developer Portals](#internal-developer-portals)
- [AI Knowledge Assistants](#ai-knowledge-assistants)
- [Search and Retrieval](#search-and-retrieval)
- [Knowledge Graphs](#knowledge-graphs)
- [Architecture Decision Records](#architecture-decision-records)
- [Operational Knowledge](#operational-knowledge)
- [Learning and Community](#learning-and-community)

## Foundations and Concepts

- [Building a Second Brain](https://www.buildingasecondbrain.com) - Tiago Forte's methodology for turning scattered digital information into actionable knowledge.
- [Zettelkasten](https://zettelkasten.de) - The "slip-box" method of networked notes that underpins most modern thought tools.
- [Docs as Code](https://www.writethedocs.org/guide/docs-as-code/) - Treating documentation with the same tools and workflows as software.
- [Team Topologies](https://teamtopologies.com) - Organizing teams and their interactions for fast flow, including how knowledge moves between them.

## Personal Knowledge Management

- [Obsidian](https://obsidian.md) - A local-first, Markdown-based knowledge base built on a graph of linked notes.
- [Logseq](https://github.com/logseq/logseq) - A privacy-first, open source outliner for networked note-taking and tasks.
- [Foam](https://github.com/foambubble/foam) - A personal knowledge management system built on VS Code and plain Markdown.
- [Dendron](https://github.com/dendronhq/dendron) - A hierarchical, schema-aware note tool that scales to large knowledge bases.
- [SiYuan](https://github.com/siyuan-note/siyuan) - A self-hosted, block-based personal knowledge management system.
- [Joplin](https://github.com/laurent22/joplin) - An open source note and to-do app with end-to-end encryption and sync.

## Documentation as Code

- [Docusaurus](https://github.com/facebook/docusaurus) - A React-based static site generator purpose-built for documentation.
- [MkDocs](https://github.com/mkdocs/mkdocs) - A fast, simple static site generator geared toward project documentation.
- [Material for MkDocs](https://github.com/squidfunk/mkdocs-material) - A popular, feature-rich theme and toolkit on top of MkDocs.
- [Sphinx](https://github.com/sphinx-doc/sphinx) - A powerful documentation generator with rich cross-referencing, widely used in Python.
- [Starlight](https://github.com/withastro/starlight) - A documentation theme for Astro with great defaults and performance.
- [Diátaxis](https://diataxis.fr) - A systematic framework that organizes docs into tutorials, how-tos, reference, and explanation.

## Internal Developer Portals

- [Backstage](https://github.com/backstage/backstage) - An open platform for building developer portals, with a software catalog and TechDocs.
- [Port](https://port.io) - A developer portal with a flexible software catalog and self-service actions.
- [Cortex](https://www.cortex.io) - An internal developer portal focused on service catalogs and engineering standards.
- [OpsLevel](https://www.opslevel.com) - A service catalog and developer portal for tracking ownership and maturity.
- [Clutch](https://github.com/lyft/clutch) - Lyft's extensible platform for infrastructure tooling and developer self-service.

## AI Knowledge Assistants

- [Dosu](https://dosu.dev) - An AI teammate that answers questions, triages issues, and maintains knowledge from your codebase and docs.
- [Onyx](https://github.com/onyx-dot-app/onyx) - An open source AI assistant and enterprise search over your team's documents and apps (formerly Danswer).
- [Khoj](https://github.com/khoj-ai/khoj) - A self-hostable AI second brain that searches and chats across your notes and documents.
- [Glean](https://www.glean.com) - An enterprise search and AI assistant connected across workplace tools.
- [Quivr](https://github.com/QuivrHQ/quivr) - An open source framework for building a personal, RAG-powered knowledge assistant.

## Search and Retrieval

- [LangChain](https://github.com/langchain-ai/langchain) - A framework for building applications with LLMs, including retrieval-augmented generation.
- [LlamaIndex](https://github.com/run-llama/llama_index) - A data framework for connecting custom data sources to LLMs.
- [Haystack](https://github.com/deepset-ai/haystack) - An end-to-end framework for building search and RAG pipelines.
- [pgvector](https://github.com/pgvector/pgvector) - Open source vector similarity search for PostgreSQL.
- [Qdrant](https://github.com/qdrant/qdrant) - A high-performance, open source vector database for similarity search.
- [Weaviate](https://github.com/weaviate/weaviate) - An open source vector database with built-in vectorization and hybrid search.
- [Meilisearch](https://github.com/meilisearch/meilisearch) - A fast, typo-tolerant, open source search engine.

## Knowledge Graphs

- [Neo4j](https://github.com/neo4j/neo4j) - A widely used graph database for connected data and knowledge graphs.
- [Memgraph](https://github.com/memgraph/memgraph) - An in-memory graph database compatible with the Cypher query language.
- [Dgraph](https://github.com/dgraph-io/dgraph) - A distributed, GraphQL-native graph database.
- [Apache Jena](https://github.com/apache/jena) - A Java framework for building semantic web and linked-data applications.
- [TerminusDB](https://github.com/terminusdb/terminusdb) - An open source graph database for collaborative, versioned knowledge.

## Architecture Decision Records

- [adr-tools](https://github.com/npryce/adr-tools) - Command-line tools for working with Architecture Decision Records.
- [Architecture Decision Record](https://github.com/joelparkerhenderson/architecture-decision-record) - Templates and examples for capturing architectural decisions.
- [MADR](https://github.com/adr/madr) - Markdown Any Decision Records, a lean template for documenting decisions.
- [Log4brains](https://github.com/thomvaill/log4brains) - A tool to log and publish ADRs as a searchable knowledge base.

## Operational Knowledge

- [PagerDuty Incident Response](https://response.pagerduty.com) - PagerDuty's open documentation on running effective incident response.
- [Dispatch](https://github.com/Netflix/dispatch) - Netflix's tool for orchestrating incident response and capturing what was learned.
- [Rundeck](https://github.com/rundeck/rundeck) - Runbook automation that turns operational knowledge into safe, self-service actions.

## Learning and Community

- [Write the Docs](https://www.writethedocs.org) - A global community and conference series for documentation practitioners.
- [r/PKMS](https://www.reddit.com/r/PKMS/) - A community for discussing personal knowledge management systems.
- [onlydole on Substack](https://onlydole.substack.com) - Essays on open source, cloud native, and knowledge infrastructure by this list's curator.

## Contributing

Contributions are very welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first, and note the [Code of Conduct](CODE_OF_CONDUCT.md).
