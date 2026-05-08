# StarRocks (starrocks)

StarRocks is a high-performance, open-source (Apache 2.0) OLAP / lakehouse engine. Clients run SQL via the MySQL protocol, while the FE HTTP server exposes REST endpoints for management and Stream Load is an HTTP-based ingestion API. CelerData provides the managed cloud offering.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/starrocks/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=starrocks-api-evangelist&utm_content=repo)

## Type
- **x-type:** opensource

## APIs
- **StarRocks Stream Load HTTP API** - Synchronous PUT to `/api/{db}/{table}/_stream_load` for ingestion. HTTP Basic auth.
- **StarRocks FE HTTP API** - Frontend HTTP endpoints for cluster admin, metrics, query profile, load monitoring.
- **StarRocks Query Interface (MySQL Wire)** - Connect via any MySQL/MariaDB client on port 9030.

## Tags
- OLAP, Lakehouse, SQL, Open Source, Real-Time Analytics

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.starrocks.io/)
- [Documentation](https://docs.starrocks.io/)
- [Source Code (Apache 2.0)](https://github.com/StarRocks/starrocks)
- [Commercial Cloud: CelerData](https://www.celerdata.com/)
- [Plans](plans/starrocks-plans-pricing.yml)
- [RateLimits](rate-limits/starrocks-rate-limits.yml)
- [FinOps](finops/starrocks-finops.yml)

## Notes
- Apache 2.0 open source. CelerData Cloud (managed StarRocks) does not publicly list pricing.
- Stream Load is the canonical HTTP-based ingestion path. The FE HTTP server exposes operational endpoints; SQL `ADMIN` covers the same ground.
- No official OpenAPI spec for the FE HTTP surface.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
