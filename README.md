# University of Aberdeen (university-of-aberdeen)

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
