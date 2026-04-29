# Customs and Border Protection (customs-and-border-protection)

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
