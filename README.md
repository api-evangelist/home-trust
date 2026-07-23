# Home Trust (home-trust)

Home Trust Company is a federally regulated Canadian trust company founded in 1977 and headquartered in Toronto, the principal operating subsidiary of Home Capital Group. Home Capital was taken private by Smith Financial Corporation in 2023, and the group now spans Home Trust, Home Bank (a Schedule I bank), Fairstone Bank, and the Oaken Financial deposit brand, positioning itself as one of Canada's leading alternative (non-prime) lenders. Its products include residential and commercial mortgages, reverse mortgages, Equityline/Preferred/Secured Visa credit cards, and Oaken GIC and high-interest savings deposits.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/home-trust/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/home-trust/refs/heads/main/apis.yml)

## Open-Finance & API Posture

Home Trust exposes **no public developer portal and no first-party API**. Probes on 2026-07-23 confirm:

- `developer.hometrust.ca` — does not resolve (DNS NXDOMAIN)
- `api.hometrust.ca` — does not resolve (DNS NXDOMAIN)
- No downloadable OpenAPI/Swagger specification is published
- No documented Interac e-Transfer or Payments Canada Real-Time Rail (RTR) API surface
- No published Consumer-Driven Banking (CDB) or FDX participation position

Canada's federal Consumer-Driven Banking (open-banking) framework is legislated (Budget 2024 and Fall Economic Statement 2024, with the Financial Consumer Agency of Canada as overseer) but **not yet operational**. As with most Canadian alternative lenders, any consumer financial-data access today would occur through screen-scraping aggregators such as Flinks or Plaid rather than a first-party API. This is an **identity-only record**.

## Tags

- Financial Services
- Banking
- Canada
- Trust Company
- Alternative Lending
- Mortgages
- Credit Cards
- Deposits

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. Home Trust does not document a public API as of July 2026.

## Common Properties

- [Website](https://www.hometrust.ca/)
- [Blog](https://www.hometrust.ca/blog/)
- [LinkedIn](https://ca.linkedin.com/company/hometrustco)
- [Privacy Policy](https://www.hometrust.ca/privacy/)
- [Terms of Service](https://www.hometrust.ca/disclaimer/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
