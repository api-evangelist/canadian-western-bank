# Canadian Western Bank (canadian-western-bank)

Canadian Western Bank (CWB) is a Schedule I domestic chartered bank founded in 1988 and headquartered in Edmonton, Alberta. Historically the largest publicly traded Schedule I bank headquartered in Western Canada (TSX: CWB) with roughly CA$43 billion in assets, it focused on full-service business and commercial banking, personal banking, equipment financing and leasing, trust services, and wealth management. In June 2024 National Bank of Canada agreed to acquire CWB in an all-share deal valued at roughly CA$5 billion; the acquisition closed in early 2025, and CWB now operates as a subsidiary of National Bank of Canada with its branches and brand being rebranded under National Bank.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/canadian-western-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/canadian-western-bank/refs/heads/main/apis.yml)

## Open Finance & API Posture

Canada's open-finance landscape is voluntary and still fragmented. The federal Consumer-Driven Banking (CDB) framework was legislated in 2024 (Budget 2024 / Fall Economic Statement, overseen by the Financial Consumer Agency of Canada / FCAC) but is **not yet operational**, so there is no mandated open-banking contract in force today.

Against that backdrop, Canadian Western Bank publishes **no first-party public developer portal and no documented public API**:

- Developer and API hostnames (`developer.cwbank.com`, `developers.cwbank.com`, `api.cwbank.com`, `apis.cwbank.com`) do **not resolve**.
- The entire `cwbank.com` domain now **301-redirects to National Bank of Canada** (`nbc.ca`), reflecting the completed acquisition and brand wind-down.
- No downloadable OpenAPI/Swagger specification, SDK, or sandbox was found.
- Consumer-permissioned account and transaction data is reached only **indirectly through third-party data aggregators** — Plaid is confirmed via aggregator coverage directories. As a National Bank of Canada subsidiary, CWB also sits within an ecosystem where the Canadian aggregator Flinks (National Bank–owned) is prominent, though no first-party CWB integration is documented.
- No first-party FDX-conformant data-access API and no published Consumer-Driven Banking data endpoint were found (the CDB framework is not live).

This is an honest identity-only, aggregator-only record for an institution now absorbed into National Bank of Canada.

## Tags

- Financial Services
- Banking
- Canada
- Schedule I Bank
- Business Banking
- Alberta
- Open Finance
- Consumer-Driven Banking
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No first-party public APIs are documented. `apis[]` is intentionally empty rather than padded with fabricated entries.

## Common Properties

- [Website](https://www.cwbank.com/) (redirects to National Bank of Canada)
- [Parent Company — National Bank of Canada](https://www.nbc.ca/)
- [LinkedIn](https://www.linkedin.com/company/canadian-western-bank)
- [Twitter / X](https://x.com/cwbank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
