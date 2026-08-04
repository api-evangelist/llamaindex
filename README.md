# llamaindex (llamaindex)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

LlamaCloud is a hosted service for document processing and search, powered by LlamaIndex.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/llamaindex/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### LlamaIndex LlamaCloud API

The LlamaCloud API is the central REST API for LlamaIndex's cloud platform, providing programmatic access to managed document processing, indexing, and retrieval services. It enables developers to build production-grade LLM applications by leveraging cloud-hosted infrastructure for document ingestion, knowledge management, and agent orchestration. The API supports authentication via API keys and is available in both US and EU regions.

- **Human URL:** [https://developers.api.llamaindex.ai/](https://developers.api.llamaindex.ai/)
- **Base URL:** `https://api.cloud.llamaindex.ai`

#### Tags

- Agents
- Artificial Intelligence
- Cloud
- Documents
- LLM
- RAG

#### Properties

- [Documentation](https://developers.api.llamaindex.ai/)
- [OpenAPI](openapi/llamaindex-llamacloud-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/llamaindex-llamacloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamacloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LlamaIndex LlamaParse API

LlamaParse is a GenAI-native document parsing API that can parse complex document data for any downstream LLM use case including agents, RAG pipelines, and data processing workflows. The v2 API provides two main endpoints for parsing: one for JSON requests accepting file IDs or URLs, and another for multipart file uploads. It supports multiple parsing tiers including fast, cost-effective, agentic, and agentic-plus modes, and returns results asynchronously via job polling.

- **Human URL:** [https://developers.llamaindex.ai/python/cloud/llamaparse/api-v2-guide/](https://developers.llamaindex.ai/python/cloud/llamaparse/api-v2-guide/)
- **Base URL:** `https://api.cloud.llamaindex.ai`

#### Tags

- Artificial Intelligence
- Document Parsing
- LLM
- OCR
- PDF

#### Properties

- [Documentation](https://developers.llamaindex.ai/python/cloud/llamaparse/api-v2-guide/)
- [OpenAPI](openapi/llamaindex-llamaparse-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/llamaindex-llamaparse-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamaparse-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LlamaIndex LlamaExtract API

LlamaExtract is a prebuilt agentic data extraction API that transforms unstructured document data into structured JSON representations. The REST API allows developers to create extraction agents, upload documents, and run extraction jobs programmatically. Jobs are processed asynchronously, and developers can poll for job status and retrieve structured results. It is designed for use cases where documents need to be converted into well-defined schemas for downstream processing.

- **Human URL:** [https://developers.llamaindex.ai/python/cloud/llamaextract/getting_started/api/](https://developers.llamaindex.ai/python/cloud/llamaextract/getting_started/api/)
- **Base URL:** `https://api.cloud.llamaindex.ai`

#### Tags

- Artificial Intelligence
- Data Extraction
- Documents
- JSON
- Structured Data

#### Properties

- [Documentation](https://developers.llamaindex.ai/python/cloud/llamaextract/getting_started/api/)
- [OpenAPI](openapi/llamaindex-llamaextract-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/llamaindex-llamaextract-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamaextract-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LlamaIndex LlamaCloud Index API

The LlamaCloud Index API provides a fully automated document ingestion pipeline with built-in retrieval capabilities. It allows developers to create and manage indexes, upload documents for automatic parsing and embedding, and perform retrieval queries against indexed content. The API supports customizable pipeline configurations and integrates with various vector stores, making it suitable for building production RAG applications without managing infrastructure.

- **Human URL:** [https://developers.llamaindex.ai/python/cloud/llamacloud/guides/api_sdk/](https://developers.llamaindex.ai/python/cloud/llamacloud/guides/api_sdk/)
- **Base URL:** `https://api.cloud.llamaindex.ai`

#### Tags

- Document Ingestion
- Indexing
- RAG
- Retrieval
- Vector Store

#### Properties

- [Documentation](https://developers.llamaindex.ai/python/cloud/llamacloud/guides/api_sdk/)
- [OpenAPI](openapi/llamaindex-llamacloud-index-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/llamaindex-llamacloud-index-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamacloud-index-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LlamaIndex Python Framework

LlamaIndex is an open-source Python framework for building LLM-powered applications including agents, RAG pipelines, and custom workflows. It provides data connectors for ingesting data from various sources such as APIs, PDFs, databases, and more. The framework offers high-level abstractions like query engines, chat engines, and agent classes (FunctionAgent, ReActAgent, CodeActAgent), as well as lower-level APIs for advanced customization.

- **Human URL:** [https://developers.llamaindex.ai/python/framework/](https://developers.llamaindex.ai/python/framework/)
- **Base URL:** `https://api.example.com`

#### Tags

- Agents
- Framework
- LLM
- Open Source
- Python
- RAG
- SDK

#### Properties

- [Documentation](https://developers.llamaindex.ai/python/framework/)
- [Postman Collection](collections/llamaindex-llamacloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamacloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/llamaindex-llamacloud-index-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamacloud-index-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/llamaindex-llamaextract-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamaextract-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/llamaindex-llamaparse-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamaparse-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LlamaIndex TypeScript Framework

LlamaIndex TypeScript is the JavaScript and TypeScript implementation of the LlamaIndex framework for building LLM-powered applications. It provides server-side TypeScript support for building agents, RAG pipelines, and agentic workflows with the same core abstractions as the Python framework. The library supports integration with LlamaCloud services and offers convenient access to cloud APIs for document parsing, extraction, and indexing from Node.js environments.

- **Human URL:** [https://developers.llamaindex.ai/typescript/framework/](https://developers.llamaindex.ai/typescript/framework/)
- **Base URL:** `https://api.example.com`

#### Tags

- Agents
- Framework
- JavaScript
- LLM
- Open Source
- RAG
- SDK
- TypeScript

#### Properties

- [Documentation](https://developers.llamaindex.ai/typescript/framework/)
- [Postman Collection](collections/llamaindex-llamacloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamacloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/llamaindex-llamacloud-index-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamacloud-index-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/llamaindex-llamaextract-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamaextract-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/llamaindex-llamaparse-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/llamaindex-llamaparse-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/run-llama)
- [LinkedIn](https://www.linkedin.com/company/llamaindex)
- [JSON-LD](json-ld/llamaindex-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/llamaindex-pipeline-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/llamaindex-extraction-agent-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/llamaindex-parse-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [L L Ms Txt](https://developers.llamaindex.ai/llms.txt)
