# City National Bank (city-national-bank)

City National Bank is a US national bank and a wholly owned subsidiary of Royal Bank of Canada (RBC), headquartered in Los Angeles, California with roughly $98 billion in assets. Known historically as "the bank to the stars" for its entertainment-industry roots, it is an FDIC-insured, super-regional institution offering personal, business, and private banking, wealth management, treasury management, and capital markets services. It operates as CN Bank in Florida.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/city-national-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/city-national-bank/refs/heads/main/apis.yml)

## Open Finance / API Posture

City National Bank publishes **no first-party public developer portal and no documented public API**. Probes confirm `developer.cnb.com` and `developers.cnb.com` do not resolve, and `api.cnb.com` returns HTTP 404. Its public website (`www.cnb.com`) links no developer documentation, OpenAPI/Swagger specs, or third-party integration resources.

Consistent with the voluntary and fragmented US open-finance model (unlike the mandated UK/AU regimes), consumer-permissioned account data from City National is reached through third-party **data aggregators** — Plaid, MX, Finicity, and Akoya — rather than a direct City National API.

- **First-party developer portal:** none (`developer.cnb.com` does not resolve)
- **Downloadable OpenAPI/Swagger:** none published
- **FDX participation:** not publicly documented for City National specifically
- **CFPB Section 1033:** City National is a covered depository institution under the emerging Personal Financial Data Rights rule, but no City-National-specific 1033 posture page is published
- **Aggregator access:** the honest path for consumer data (Plaid / MX / Finicity / Akoya)
- **Parent portal:** RBC runs a separate developer portal at `developer.rbc.com` under a different (Canadian) charter that does not expose City National Bank APIs

## Tags

- Financial Services
- Banking
- United States
- Super-Regional Bank
- National Bank
- Private Banking
- Wealth Management
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No public API products are documented by City National Bank. This is an identity-only record; data access is available to permissioned third parties via aggregators, not a first-party API.

## Common Properties

- [Website](https://www.cnb.com/)
- [About](https://www.cnb.com/about-us.html)
- [Blog](https://www.cnb.com/personal-banking/insights.html)
- [Privacy Policy](https://www.cnb.com/privacy.html)
- [Terms of Service](https://www.cnb.com/legal.html)
- [Support](https://www.cnb.com/contact-us.html)
- [LinkedIn](https://www.linkedin.com/company/city-national-bank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
