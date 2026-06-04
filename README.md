# Hebrew University of Jerusalem (hebrew-university-of-jerusalem)

The Hebrew University of Jerusalem (HUJI) is Israel's leading research university, ranked #272 in the QS World University Rankings 2025, with campuses in Jerusalem, Rehovot, and Eilat. This repository catalogs HUJI's public developer/API footprint as an APIs.json provider profile for the api-evangelist organization. HUJI does not operate a dedicated public developer portal or documented open API program; its developer-relevant surface is limited to standards-based academic infrastructure and research-lab open-source code.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/hebrew-university-of-jerusalem/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=hebrew-university-of-jerusalem-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Israel

## APIs

- **HUJI Library Discovery (Ex Libris Primo/Alma)** — Library catalog/discovery on Ex Libris Primo/Alma (HUfind). Standard Primo/Alma APIs and OAI-PMH exist but require institution-issued keys; not publicly self-service. Docs: https://en.libraries.huji.ac.il/
- **OpenScholar @ HUJI** — Drupal-based profile/CMS platform for faculty, labs, and projects. Internal authoring tool; no documented public developer API confirmed. Docs: https://scholars.huji.ac.il/

## Plans

- plans/hebrew-university-of-jerusalem-plans-pricing.yml

## Rate Limits

- rate-limits/hebrew-university-of-jerusalem-rate-limits.yml

## FinOps

- finops/hebrew-university-of-jerusalem-finops.yml

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://en.huji.ac.il/
- GitHub: https://github.com/huji-nlp
- LinkedIn: https://www.linkedin.com/school/hebrew-university-of-jerusalem/
- Plans: plans/hebrew-university-of-jerusalem-plans-pricing.yml
- Rate Limits: rate-limits/hebrew-university-of-jerusalem-rate-limits.yml
- FinOps: finops/hebrew-university-of-jerusalem-finops.yml
- Review: review.yml

## Notes

- No dedicated public developer portal or self-service API was found for HUJI.
- Library discovery runs on Ex Libris Primo/Alma, which provides standard APIs/OAI-PMH but requires institution-issued credentials and is not publicly self-service.
- Single sign-on uses Shibboleth/SAML and is internal/gated.
- HUJI research labs publish open-source code on GitHub (e.g., huji-nlp, slp-rl); these are code repositories, not institutional REST APIs. The GitHub common property points to the most prominent lab org as the closest public code presence.
- All listed URLs were probed; no endpoints were fabricated. See review.yml for HTTP statuses.

## Maintainers

- Kin Lane — kin@apievangelist.com
