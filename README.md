# Vespa (vespa)

Vespa is an Apache 2.0 open-source serving engine for big-data, vector search, and recommendations. It exposes a Document API (write/read), a Search API (query), and several admin endpoints. Vespa Cloud is the commercial managed offering.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/vespa/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=vespa-api-evangelist&utm_content=repo)

## Type
- **x-type:** opensource

## APIs
- **Vespa Document API v1** - `/document/v1` for GET/POST/PUT/DELETE plus visiting (bulk iteration with continuation tokens), conditional writes, and upserts. 429 backpressure.
- **Vespa Search API** - `/search/` accepting YQL or structured query JSON; powers full-text, vector, and hybrid retrieval with ranking expressions.

## Tags
- Vector Database, Search, Open Source, Real-Time, Recommendations

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://vespa.ai/)
- [Documentation](https://docs.vespa.ai/)
- [Source (Apache 2.0)](https://github.com/vespa-engine/vespa)
- [Vespa Cloud](https://cloud.vespa.ai/)
- [Cloud Pricing](https://cloud.vespa.ai/price-calculator.html)
- [Plans](plans/vespa-plans-pricing.yml)
- [RateLimits](rate-limits/vespa-rate-limits.yml)
- [FinOps](finops/vespa-finops.yml)

## Notes
- Pricing reconciled (research): Vespa Cloud has per-resource hourly rates across Startup, Basic, Commercial, and Enterprise plans, e.g. $0.05-0.18/vCPU-hour, $0.005-0.018/GB-RAM-hour, $0.0002-0.0007/GB-disk-hour, $0.03-0.125/GB-GPU-hour. Enterprise has $20K/mo minimum. 15% annual-commit discount.
- Self-hosted Vespa is fully Apache 2.0.
- Document API is unusually well-designed for streaming bulk writes.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
