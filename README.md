# Home Trust (home-trust)

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
