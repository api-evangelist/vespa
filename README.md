# Vespa (vespa)

Vespa is an Apache 2.0 open-source serving engine for big-data, vector search, and recommendations. It exposes a Document API (write/read), a Search API (query), and several admin endpoints. Vespa Cloud is the commercial managed offering.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vespa/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vespa/refs/heads/main/apis.yml)

## Tags

- Vector Database
- Search
- Open Source
- Real-Time
- Recommendations

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Vespa Document API v1

The /document/v1 API supports GET, POST, PUT, and DELETE for documents, plus bulk visiting/iteration with continuation tokens, conditional writes (test-and-set using the document selector language), and upserts. Backpressure is signaled with 429 Too Many Requests.

- **Human URL:** [https://docs.vespa.ai/en/document-v1-api-guide.html](https://docs.vespa.ai/en/document-v1-api-guide.html)
- **Base URL:** `http://{vespa_endpoint}/document/v1`

#### Tags

- REST
- Documents
- CRUD
- Visit

#### Properties

- [Documentation](https://docs.vespa.ai/en/document-v1-api-guide.html)
- [Postman Collection](collections/vespa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vespa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vespa Search API

The Vespa Search API accepts queries via YQL or structured query JSON over HTTP GET/POST. It powers full-text, vector, and hybrid retrieval with ranking expressions defined in the application package.

- **Human URL:** [https://docs.vespa.ai/en/query-api.html](https://docs.vespa.ai/en/query-api.html)
- **Base URL:** `http://{vespa_endpoint}/search/`

#### Tags

- REST
- Search
- Query
- YQL

#### Properties

- [Documentation](https://docs.vespa.ai/en/query-api.html)
- [Postman Collection](collections/vespa.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vespa.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/vespa-ai)
- [Website](https://vespa.ai/)
- [Portal](https://docs.vespa.ai/)
- [Source Code](https://github.com/vespa-engine/vespa)
- [Commercial Offering](https://cloud.vespa.ai/)
- [Pricing](https://cloud.vespa.ai/price-calculator.html)
- [Plans](plans/vespa-plans-pricing.yml)
- [Rate Limits](rate-limits/vespa-rate-limits.yml)
- [Fin Ops](finops/vespa-finops.yml)
- [L L Ms Txt](https://docs.vespa.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
