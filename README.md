# Awesome Knowledge Infrastructure [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools and practices for capturing, connecting, and operationalizing what your organization (and you) know.

**Knowledge infrastructure** is the connective tissue that lets people *and software* find, trust, and act on what an organization knows. It spans capturing knowledge (notes, docs, decisions), connecting it (links, graphs, catalogs), and operationalizing it (search, retrieval, AI assistants) — from a single engineer's note vault to an enterprise's internal developer portal and AI knowledge layer.

The pieces have always existed in scattered categories — wikis, docs tools, search, PKM apps. What's new is treating them as *one layer* worth designing on purpose. This list is an opinionated map of that layer.

Curated by [Taylor Dolezal](https://github.com/onlydole), drawing on years of work across open source and cloud native infrastructure. Contributions are welcome.

## Contents

- [Foundations and Concepts](#foundations-and-concepts)
- [Personal Knowledge Management](#personal-knowledge-management)
- [Wikis and Team Knowledge Bases](#wikis-and-team-knowledge-bases)
- [Documentation as Code](#documentation-as-code)
- [Interoperability and Standards](#interoperability-and-standards)
- [Internal Developer Portals](#internal-developer-portals)
- [AI Knowledge Assistants](#ai-knowledge-assistants)
- [Retrieval-Augmented Generation](#retrieval-augmented-generation)
- [Search and Retrieval](#search-and-retrieval)
- [AI Memory and Context](#ai-memory-and-context)
- [Orchestration and Durable Execution](#orchestration-and-durable-execution)
- [Knowledge Graphs](#knowledge-graphs)
- [Data Catalogs and Metadata](#data-catalogs-and-metadata)
- [Architecture Decision Records](#architecture-decision-records)
- [Diagramming and Visualization as Code](#diagramming-and-visualization-as-code)
- [Operational Knowledge](#operational-knowledge)
- [Read It Later and Annotation](#read-it-later-and-annotation)
- [Learning and Community](#learning-and-community)

## Foundations and Concepts

- [Building a Second Brain](https://www.buildingasecondbrain.com) - Tiago Forte's methodology for turning scattered digital information into actionable knowledge.
- [Zettelkasten](https://zettelkasten.de) - The "slip-box" method of networked notes that underpins most modern thought tools.
- [DIKW Pyramid](https://en.wikipedia.org/wiki/DIKW_pyramid) - A foundational model describing how data becomes information, knowledge, and ultimately wisdom.
- [Communities of Practice](https://www.wenger-trayner.com/introduction-to-communities-of-practice/) - Wenger-Trayner's framework for groups that deepen shared expertise through ongoing practice.
- [Knowledge-Centered Service](https://www.serviceinnovation.org/kcs/) - A methodology for capturing and reusing support knowledge as a by-product of solving problems.
- [Docs as Code](https://www.writethedocs.org/guide/docs-as-code/) - Treating documentation with the same tools and workflows as software.
- [Diátaxis](https://diataxis.fr) - A systematic framework that organizes docs into tutorials, how-tos, reference, and explanation.
- [Team Topologies](https://teamtopologies.com) - Organizing teams and their interactions for fast flow, including how knowledge moves between them.
- [GitLab Handbook](https://handbook.gitlab.com) - The public, version-controlled handbook that models a handbook-first, transparent way of working.
- [Working Backwards](https://www.workingbackwards.com) - Amazon's PR/FAQ and narrative-memo practice for thinking through ideas before building them.

## Personal Knowledge Management

- [Obsidian](https://obsidian.md) - A local-first, Markdown-based knowledge base built on a graph of linked notes.
- [Logseq](https://github.com/logseq/logseq) - A privacy-first, open source outliner for networked note-taking and tasks.
- [SiYuan](https://github.com/siyuan-note/siyuan) - A self-hosted, block-based personal knowledge management system.
- [Joplin](https://github.com/laurent22/joplin) - An open source note and to-do app with end-to-end encryption and sync.
- [Anytype](https://github.com/anyproto/anytype-ts) - A local-first, end-to-end encrypted workspace built on an object graph you fully own.
- [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) - An open source Notion alternative for notes, wikis, and projects with local data ownership.
- [Trilium Notes](https://github.com/TriliumNext/Trilium) - A hierarchical note-taking application for building large personal knowledge bases.
- [Org-roam](https://github.com/org-roam/org-roam) - A plain-text knowledge management system for Emacs Org-mode built on the Zettelkasten method.
- [Notion](https://www.notion.com) - An all-in-one workspace combining notes, docs, wikis, and databases.
- [Roam Research](https://roamresearch.com) - A note-taking tool for networked thought with bidirectional links and daily notes.

## Wikis and Team Knowledge Bases

- [Wiki.js](https://github.com/requarks/wiki) - A modern, open source wiki engine with a powerful editor and flexible storage backends.
- [BookStack](https://github.com/BookStackApp/BookStack) - A simple, open source platform for organizing documentation into books, chapters, and pages.
- [DokuWiki](https://github.com/dokuwiki/dokuwiki) - A lightweight, database-free wiki that stores pages as plain text files.
- [MediaWiki](https://www.mediawiki.org) - The open source wiki engine that powers Wikipedia, built for large collaborative knowledge bases.
- [Outline](https://github.com/outline/outline) - A fast, open source team knowledge base and wiki with real-time collaboration.
- [TiddlyWiki](https://github.com/Jermolene/TiddlyWiki5) - A self-contained, non-linear personal wiki you can carry in a single HTML file.
- [AFFiNE](https://github.com/toeverything/AFFiNE) - An open source, local-first workspace that merges documents, whiteboards, and databases.
- [Confluence](https://www.atlassian.com/software/confluence) - Atlassian's widely used team workspace for documentation and knowledge sharing.

## Documentation as Code

- [Docusaurus](https://github.com/facebook/docusaurus) - A React-based static site generator purpose-built for documentation.
- [MkDocs](https://github.com/mkdocs/mkdocs) - A fast, simple static site generator geared toward project documentation.
- [Material for MkDocs](https://github.com/squidfunk/mkdocs-material) - A popular, feature-rich theme and toolkit on top of MkDocs.
- [Sphinx](https://github.com/sphinx-doc/sphinx) - A powerful documentation generator with rich cross-referencing, widely used in Python.
- [Starlight](https://github.com/withastro/starlight) - A documentation theme for Astro with great defaults and performance.
- [Read the Docs](https://github.com/readthedocs/readthedocs.org) - A platform that automatically builds, versions, and hosts documentation from your repository.
- [VitePress](https://github.com/vuejs/vitepress) - A Vite-powered static site generator optimized for fast, content-focused documentation.
- [Antora](https://gitlab.com/antora/antora) - A multi-repository documentation site generator built around AsciiDoc.
- [Redoc](https://github.com/Redocly/redoc) - An open source tool that renders OpenAPI definitions into reference API documentation.
- [GitBook](https://www.gitbook.com) - A hosted platform for writing and publishing polished product and developer documentation.

## Interoperability and Standards

- [CommonMark](https://commonmark.org) - A standardized, unambiguous specification of the Markdown syntax.
- [Pandoc](https://github.com/jgm/pandoc) - A universal document converter that translates between Markdown, HTML, LaTeX, and dozens of formats.
- [Org-mode](https://orgmode.org) - An Emacs format and system for authoring, organizing, and exporting structured plain-text documents.
- [JSON Canvas](https://jsoncanvas.org) - An open file format for infinite-canvas notes, originating in Obsidian.
- [Web Annotation Data Model](https://www.w3.org/TR/annotation-model/) - A W3C standard for representing annotations and highlights on web resources.
- [Model Context Protocol](https://modelcontextprotocol.io) - An open protocol that standardizes how applications supply context and tools to LLMs.

## Internal Developer Portals

- [Backstage](https://github.com/backstage/backstage) - An open platform for building developer portals, with a software catalog and TechDocs.
- [Port](https://port.io) - A developer portal with a flexible software catalog and self-service actions.
- [Cortex](https://www.cortex.io) - An internal developer portal focused on service catalogs and engineering standards.
- [OpsLevel](https://www.opslevel.com) - A service catalog and developer portal for tracking ownership and maturity.
- [Clutch](https://github.com/lyft/clutch) - Lyft's extensible platform for infrastructure tooling and developer self-service.
- [Roadie](https://roadie.io) - A managed, SaaS version of Backstage for teams that want a developer portal without self-hosting.
- [Kratix](https://github.com/syntasso/kratix) - An open source framework for building platforms that offer self-service infrastructure as a product.
- [Compass](https://www.atlassian.com/software/compass) - Atlassian's developer experience platform for cataloging services and tracking software health.

## AI Knowledge Assistants

- [Dosu](https://dosu.dev) - An AI teammate that answers questions, triages issues, and maintains knowledge from your codebase and docs.
- [Onyx](https://github.com/onyx-dot-app/onyx) - An open source AI assistant and enterprise search over your team's documents and apps (formerly Danswer).
- [Khoj](https://github.com/khoj-ai/khoj) - A self-hostable AI second brain that searches and chats across your notes and documents.
- [Glean](https://www.glean.com) - An enterprise search and AI assistant connected across workplace tools.
- [Quivr](https://github.com/QuivrHQ/quivr) - An open source framework for building a personal, RAG-powered knowledge assistant.
- [Guru](https://www.getguru.com) - An enterprise knowledge platform that surfaces verified answers in the tools where people work.

## Retrieval-Augmented Generation

- [LangChain](https://github.com/langchain-ai/langchain) - A framework for building applications with LLMs, including retrieval-augmented generation.
- [LlamaIndex](https://github.com/run-llama/llama_index) - A data framework for connecting custom data sources to LLMs.
- [Haystack](https://github.com/deepset-ai/haystack) - An end-to-end framework for building search and RAG pipelines.
- [txtai](https://github.com/neuml/txtai) - An all-in-one embeddings database for semantic search, RAG, and LLM orchestration.
- [RAGFlow](https://github.com/infiniflow/ragflow) - An open source RAG engine built on deep document understanding for grounded question answering.
- [Unstructured](https://github.com/Unstructured-IO/unstructured) - Open source libraries for ingesting and preprocessing documents into LLM-ready data.
- [Docling](https://github.com/docling-project/docling) - An open source toolkit that parses PDFs, Office files, and more into structured, LLM-ready formats.
- [Sentence Transformers](https://github.com/UKPLab/sentence-transformers) - A Python library for state-of-the-art text and image embeddings used in semantic search.

## Search and Retrieval

- [Meilisearch](https://github.com/meilisearch/meilisearch) - A fast, typo-tolerant, open source search engine.
- [Elasticsearch](https://github.com/elastic/elasticsearch) - A distributed search and analytics engine for full-text, structured, and vector search.
- [Apache Solr](https://github.com/apache/solr) - A mature, Lucene-based open source search platform for large-scale deployments.
- [Quickwit](https://github.com/quickwit-oss/quickwit) - A cloud-native, open source search engine optimized for logs and large append-only datasets.
- [pgvector](https://github.com/pgvector/pgvector) - Open source vector similarity search for PostgreSQL.
- [Qdrant](https://github.com/qdrant/qdrant) - A high-performance, open source vector database for similarity search.
- [Weaviate](https://github.com/weaviate/weaviate) - An open source vector database with built-in vectorization and hybrid search.
- [Chroma](https://github.com/chroma-core/chroma) - An open source embedding database designed for building AI applications quickly.
- [Milvus](https://github.com/milvus-io/milvus) - A cloud-native, open source vector database built for massive-scale similarity search.
- [LanceDB](https://github.com/lancedb/lancedb) - An embedded, open source vector database for multimodal AI built on the Lance format.

## AI Memory and Context

- [Mem0](https://github.com/mem0ai/mem0) - An open source memory layer that gives AI agents persistent, personalized recall.
- [Letta](https://github.com/letta-ai/letta) - An open source framework (formerly MemGPT) for building stateful agents with long-term memory.
- [Graphiti](https://github.com/getzep/graphiti) - An open source framework for building temporally-aware knowledge graphs for agent memory.
- [cognee](https://github.com/topoteretes/cognee) - An open source framework for building memory and knowledge graphs for AI agents from your data.

## Orchestration and Durable Execution

- [DBOS](https://www.dbos.dev) - An open source durable workflow library, backed by PostgreSQL, for building crash-resilient backends, pipelines, and AI agents.
- [Temporal](https://github.com/temporalio/temporal) - A durable execution platform for orchestrating reliable, long-running workflows and services.
- [Restate](https://github.com/restatedev/restate) - An open source durable execution engine for building resilient applications, workflows, and agents.

## Knowledge Graphs

- [Neo4j](https://github.com/neo4j/neo4j) - A widely used graph database for connected data and knowledge graphs.
- [Memgraph](https://github.com/memgraph/memgraph) - An in-memory graph database compatible with the Cypher query language.
- [Dgraph](https://github.com/dgraph-io/dgraph) - A distributed, GraphQL-native graph database.
- [Apache Jena](https://github.com/apache/jena) - A Java framework for building semantic web and linked-data applications.
- [TerminusDB](https://github.com/terminusdb/terminusdb) - An open source graph database for collaborative, versioned knowledge.
- [RDFLib](https://github.com/RDFLib/rdflib) - A Python library for working with RDF, including parsing, serializing, and SPARQL queries.
- [FalkorDB](https://github.com/FalkorDB/FalkorDB) - A low-latency, open source graph database designed for GraphRAG and AI workloads.
- [Protégé](https://github.com/protegeproject/protege) - A free, open source ontology editor for building OWL ontologies and knowledge models.
- [Wikidata](https://www.wikidata.org) - A free, collaborative knowledge graph of structured data maintained by the Wikimedia community.
- [schema.org](https://schema.org) - A shared vocabulary for marking up structured data on the web.

## Data Catalogs and Metadata

- [DataHub](https://github.com/datahub-project/datahub) - An open source metadata platform for data discovery, lineage, and governance.
- [OpenMetadata](https://github.com/open-metadata/OpenMetadata) - A unified, open source platform for metadata, data discovery, and observability.
- [Apache Atlas](https://atlas.apache.org) - An open source framework for data governance and metadata management.
- [OpenLineage](https://github.com/OpenLineage/OpenLineage) - An open standard for metadata and lineage collection across data pipelines.
- [CKAN](https://github.com/ckan/ckan) - An open source data management system for building open data portals and catalogs.

## Architecture Decision Records

- [adr-tools](https://github.com/npryce/adr-tools) - Command-line tools for working with Architecture Decision Records.
- [Architecture Decision Record](https://github.com/joelparkerhenderson/architecture-decision-record) - Templates and examples for capturing architectural decisions.
- [MADR](https://github.com/adr/madr) - Markdown Any Decision Records, a lean template for documenting decisions.
- [Log4brains](https://github.com/thomvaill/log4brains) - A tool to log and publish ADRs as a searchable knowledge base.
- [ADR Organization](https://adr.github.io) - A community hub of templates, tooling, and guidance for Architecture Decision Records.

## Diagramming and Visualization as Code

- [Mermaid](https://github.com/mermaid-js/mermaid) - A tool for generating diagrams and flowcharts from Markdown-like text.
- [PlantUML](https://github.com/plantuml/plantuml) - A tool for creating UML and many other diagrams from a simple text description.
- [D2](https://github.com/terrastruct/d2) - A modern, declarative language and engine for turning text into diagrams.
- [Graphviz](https://graphviz.org) - An open source toolkit for laying out and rendering graphs from the DOT language.
- [Diagrams](https://github.com/mingrammer/diagrams) - A Python library for drawing cloud system architecture diagrams as code.
- [Kroki](https://github.com/yuzutech/kroki) - A unified API that renders many text-based diagram formats into images.
- [Excalidraw](https://github.com/excalidraw/excalidraw) - An open source virtual whiteboard for sketching hand-drawn-style diagrams.
- [C4 model](https://c4model.com) - A lightweight approach for visualizing software architecture at multiple levels of detail.

## Operational Knowledge

- [PagerDuty Incident Response](https://response.pagerduty.com) - PagerDuty's open documentation on running effective incident response.
- [Dispatch](https://github.com/Netflix/dispatch) - Netflix's tool for orchestrating incident response and capturing what was learned.
- [Rundeck](https://github.com/rundeck/rundeck) - Runbook automation that turns operational knowledge into safe, self-service actions.
- [Google SRE Books](https://sre.google/books/) - Google's freely available books on site reliability engineering, including incident response and postmortems.
- [Grafana OnCall](https://github.com/grafana/oncall) - An open source on-call and alert management tool for incident response.
- [Cachet](https://github.com/cachethq/cachet) - An open source status page system for communicating incidents and uptime.

## Read It Later and Annotation

- [Readwise](https://readwise.io) - A service that syncs and resurfaces your highlights from books, articles, and more.
- [Hypothesis](https://github.com/hypothesis/h) - An open source tool for annotating and discussing any web page or PDF.
- [Wallabag](https://github.com/wallabag/wallabag) - A self-hostable, open source read-it-later application that saves and archives articles.
- [Karakeep](https://github.com/karakeep-app/karakeep) - An open source, self-hostable bookmarking app (formerly Hoarder) with AI tagging and full-text search.

## Learning and Community

- [Write the Docs](https://www.writethedocs.org) - A global community and conference series for documentation practitioners.
- [r/PKMS](https://www.reddit.com/r/PKMS/) - A community for discussing personal knowledge management systems.
- [onlydole on Substack](https://onlydole.substack.com) - Essays on open source, cloud native, and knowledge infrastructure by this list's curator.

## Contributing

Contributions are very welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first, and note the [Code of Conduct](CODE_OF_CONDUCT.md).
