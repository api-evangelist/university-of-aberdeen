# University of Aberdeen (university-of-aberdeen)

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

The University of Aberdeen is a public research university in Aberdeen, Scotland, United Kingdom, founded in 1495 and ranked #236 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an APIs.json provider profile for the api-evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-aberdeen/refs/heads/main/apis.yml
- Naftiko Run: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-aberdeen-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Institutional Repository, DSpace, OAI-PMH, United Kingdom, Scotland

## APIs

- **AURA DSpace REST API** — Public HATEOAS REST API for the Aberdeen University Research Archive (DSpace 8.1), covering communities, collections, items, and bitstreams.
  - Docs: https://aura.abdn.ac.uk/server/api
  - Base URL: https://aura.abdn.ac.uk/server/api
- **AURA OAI-PMH Metadata Harvesting** — OAI-PMH 2.0 endpoint (repository "Aura") for harvesting metadata describing the university's open-access research outputs.
  - Docs: https://aura.abdn.ac.uk/server/oai/request?verb=Identify
  - Base URL: https://aura.abdn.ac.uk/server/oai/request

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-aberdeen-plans-pricing.yml](plans/university-of-aberdeen-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-aberdeen-rate-limits.yml](rate-limits/university-of-aberdeen-rate-limits.yml)
- FinOps: [finops/university-of-aberdeen-finops.yml](finops/university-of-aberdeen-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.abdn.ac.uk/
- GitHub: https://github.com/uofa
- LinkedIn: https://www.linkedin.com/school/university-of-aberdeen/
- Review: [review.yml](review.yml)

## Notes

All APIs and URLs in this profile were probed live on 2026-06-03; no endpoints were fabricated. The two cataloged APIs are hosted on AURA (the open-access institutional repository), which runs DSpace 8.1 and exposes both a REST API and an OAI-PMH 2.0 endpoint. The Elsevier Pure research portal (abdn.elsevierpure.com) is live, but its OAI web service returned HTTP 500 and is not treated as a public API. No general-purpose developer portal or public course/timetable/SIS/library (Alma/Primo) APIs were found; such integrations appear internal or gated. The GitHub org at github.com/uofa is verified to the abdn.ac.uk domain but hosts mostly forks rather than published API specifications.

## Maintainers

- Kin Lane — kin@apievangelist.com
