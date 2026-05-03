# Web of Science APIs (web-of-science-apis)
The Web of Science APIs provide programmatic access to Clarivate's Web of Science databases, the world's leading citation index covering over 21,000 peer-reviewed journals across the sciences, social sciences, and humanities. The API suite includes the Starter API for basic bibliographic metadata and journal discovery, and the Expanded API for advanced search, citation tracking, related records, and bibliometric reporting with h-index and year-by-year citation analysis.

**URL:** [https://developer.clarivate.com/apis/wos-starter](https://developer.clarivate.com/apis/wos-starter)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Research, Academic, Bibliometrics, Citations, Science, Scholarly

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-03

## APIs

### Web of Science Starter API
The Web of Science Starter API provides basic bibliographic metadata search and retrieval for Web of Science documents and journals. It supports document search using advanced query syntax, retrieval by unique identifier, and journal lookup by ISSN or name.

**Human URL:** [https://developer.clarivate.com/apis/wos-starter](https://developer.clarivate.com/apis/wos-starter)

#### Tags:

 - Research, Documents, Journals, Bibliometrics

#### Properties

- [Web of Science Starter OpenAPI](openapi/web-of-science-starter-openapi.yml)
- [Documentation](https://developer.clarivate.com/apis/wos-starter)
- [Swagger UI](https://developer.clarivate.com/apis/wos-starter/swagger)

### Web of Science API Expanded
The Web of Science API Expanded provides rich bibliographic searching, citation tracking (citing articles and references), related records discovery, and citation reporting with h-index and bibliometric statistics. Requires a paid subscription.

**Human URL:** [https://developer.clarivate.com/apis/wos](https://developer.clarivate.com/apis/wos)

#### Tags:

 - Research, Citations, Bibliometrics, Search, Reports

#### Properties

- [Web of Science Expanded OpenAPI](openapi/web-of-science-expanded-openapi.yml)
- [Documentation](https://developer.clarivate.com/apis/wos)
- [Swagger UI](https://developer.clarivate.com/apis/wos/swagger)

## Common Properties

- [Documentation](https://developer.clarivate.com/apis/wos-starter)
- [Website](https://clarivate.com/products/scientific-and-academic-research/research-discovery-and-referencing/web-of-science/)
- [Developer Portal](https://developer.clarivate.com)
- [Support](https://developer.clarivate.com/support)
- [Terms of Service](https://clarivate.com/legal/terms-conditions/)
- [Privacy Policy](https://clarivate.com/privacy-statement/)
- [Blog](https://clarivate.com/blog/)

## Features

| Name | Description |
|------|-------------|
| Advanced Document Search | Search over 100 million records using Web of Science Advanced Query Syntax with 16 searchable field tags including topic, author, DOI, organization, and funding agency. |
| Citation Tracking | Track forward citations (articles citing a paper) and backward citations (reference list) to understand the full citation network of any paper. |
| Bibliometric Reporting | Generate citation reports with h-index, total citations, average citations per item, and year-by-year citation and publication counts. |
| Related Records Discovery | Find research papers related to a given article by identifying records that share cited references. |
| Journal Metadata | Retrieve journal information including ISSN, publisher, subject categories, and Journal Citation Reports profile URL. |
| Multi-Database Search | Search across 12 Web of Science databases including Core Collection, MEDLINE, BIOSIS, and Zoological Record. |
| Times-Cited Counts | Access real-time times-cited counts for documents across Web of Science databases for impact assessment. |

## Use Cases

| Name | Description |
|------|-------------|
| Literature Review Automation | Automate systematic literature review by programmatically searching and retrieving bibliographic metadata from Web of Science. |
| Research Impact Analysis | Analyze the impact of publications or researchers using citation counts, h-index, and bibliometric reports. |
| Citation Network Analysis | Build citation networks by tracing forward and backward citations to map the intellectual lineage of research topics. |
| Journal Selection | Identify appropriate journals for manuscript submission by searching journal metadata and impact metrics. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Web of Science Starter API OpenAPI](openapi/web-of-science-starter-openapi.yml)
- [Web of Science Expanded API OpenAPI](openapi/web-of-science-expanded-openapi.yml)

### JSON Schema

29 JSON Schema files covering documents, journals, search responses, citations, and bibliometric report schemas.

### JSON Structure

29 JSON Structure files (json-structure.org) converted from JSON Schema.

### JSON-LD

- [Web of Science JSON-LD Context](json-ld/web-of-science-context.jsonld) — 29 type declarations and 84 property mappings

### Examples

29 example JSON files generated from schemas.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Web of Science Starter API](capabilities/shared/web-of-science-starter-api.yaml) — 4 operations covering document and journal search
- [Web of Science Expanded API](capabilities/shared/web-of-science-expanded-api.yaml) — 8 operations covering advanced search, citations, and reports

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Academic Research](capabilities/academic-research.yaml) | Web of Science Starter API, Web of Science Expanded API | 10 | Researcher, Librarian, Data Analyst |

## Vocabulary

- [Web of Science Vocabulary](vocabulary/web-of-science-vocabulary.yml) — Unified taxonomy mapping 9 resources, 6 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Web of Science Spectral Rules](rules/web-of-science-spectral-rules.yml) — 22 rules across 8 categories enforcing Web of Science API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
