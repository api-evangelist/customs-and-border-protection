# Customs and Border Protection (customs-and-border-protection)

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

U.S. Customs and Border Protection (CBP) is the federal law enforcement agency within the Department of Homeland Security responsible for facilitating lawful international trade and travel, collecting duties, enforcing trade laws, and securing U.S. borders. CBP's primary trade automation systems are the Automated Commercial Environment (ACE), the Automated Export System (AES) including AESDirect, the Advance Passenger Information System (APIS / eAPIS), and the Air Cargo Advance Screening (ACAS) program. Trade integrations are predominantly delivered via EDI messaging through ACE, with a small set of CBP web services such as the AESDirect WebLink Inquiry API exposed for programmatic use.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/customs-and-border-protection/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** Public
- **x-type:** government

## Tags

- ACE, ACAS, AES, AESDirect, APIS, Borders, Cargo, CBP, Customs, Department of Homeland Security, DHS, EDI, Exports, Federal Government, Imports, International Trade, Manifests, Single Window, Trade Compliance

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-04-28

## APIs

### APIS / eAPIS

The Advance Passenger Information System collects pre-arrival and pre-departure manifest data on passengers and crew. eAPIS is the web portal for creating, managing, and submitting APIS manifests; bulk integrations use UN/EDIFACT PAXLST and CUSRES messages.

**Human URL:** https://www.cbp.gov/travel/travel-industry-personnel/advance-passenger-information-system

### Automated Commercial Environment (ACE)

The U.S. Single Window for trade reporting. Trade users access ACE via the ACE Secure Data Portal and via ACE Electronic Data Interchange. The ACE Portal modernization completed user access management migration in February 2025.

**Human URL:** https://www.cbp.gov/trade/automated

### Automated Export System (AES)

AES is the system through which exporters file Electronic Export Information (EEI). AESDirect is CBP's free web-based filing tool integrated with AES through ACE.

**Human URL:** https://www.cbp.gov/trade/aes

### AESDirect WebLink Inquiry API

A web service that allows authorized partners to query AESDirect filings programmatically. CBP provides separate certification and production environments.

**Human URL:** https://www.cbp.gov/trade/automated/aesdirect-weblink-inquiry-api

### Air Cargo Advance Screening (ACAS)

Pre-loading advance data submission for inbound air cargo, transmitted via CBP-approved EDI messages for security risk-based screening.

**Human URL:** https://www.cbp.gov/border-security/ports-entry/cargo-security/acas

## Capabilities

- Pre-arrival passenger and crew manifest reporting (APIS)
- Import entry summaries and admissibility determinations (ACE)
- Electronic Export Information filings (AES / AESDirect)
- Pre-loading air cargo risk screening (ACAS)
- Single Window integration with Partner Government Agencies (PGAs)

## Use Cases

- Airline and vessel operator APIS manifest submission
- Customs broker entry filing through ACE EDI
- Exporter EEI filing via AESDirect or third-party EDI
- Air carrier ACAS pre-loading data submission
- Trade community status inquiry via AESDirect WebLink API

## Common Resources

- [CBP Website](https://www.cbp.gov/)
- [Trade Automation](https://www.cbp.gov/trade/automated)
- [ACE Service Desk](https://www.cbp.gov/contact/automated-broker-interface-service-desk)
- [Help Center](https://www.help.cbp.gov/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
