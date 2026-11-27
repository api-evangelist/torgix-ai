# Torgix

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Torgix provides AI‑driven equipment intelligence that calculates the true cost per hour of heavy machinery by aggregating repairs, parts, fuel, idle time, and warranty data. The platform offers fleet‑wide dashboards, predictive maintenance alerts, and integration with existing CMMS tools, helping owners and operators reduce downtime and optimize asset utilization across construction, environmental services, marine, aviation, and motorsports industries.

**Areas:** AI · Equipment · Maintenance · FleetManagement · Construction

## Torgix on APIs.io

Everything profiled for Torgix is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/torgix-ai/](https://apis.io/providers/torgix-ai/)** — or go straight to one of the APIs or properties below.

### APIs (58)

- [Torgix Activities API](https://apis.io/apis/torgix-ai/torgix-ai-activities-api/) — Read-only.
- [Torgix Asset Compliance Requirements API](https://apis.io/apis/torgix-ai/torgix-ai-asset-compliance-requirements-api/) — Which requirements apply to which asset, and whether each is satisfied. Read-only.
- [Torgix Asset Photos API](https://apis.io/apis/torgix-ai/torgix-ai-asset-photos-api/) — Photo metadata per asset (name, type, size, caption). The image itself is not served by the API. Read-only.
- [Torgix Assets API](https://apis.io/apis/torgix-ai/torgix-ai-assets-api/) — Create, update, delete.
- [Torgix Audit Events API](https://apis.io/apis/torgix-ai/torgix-ai-audit-events-api/) — The account audit log, for pulling into a SIEM. Filter by created_at, cursor by id. Read-only.
- [Torgix Charge Logs API](https://apis.io/apis/torgix-ai/torgix-ai-charge-logs-api/) — EV charging sessions: state of charge in and out, kWh added, duration. Fed by Samsara; post one for a charger that is not connected. Create only (append log).
- [Torgix Checkouts API](https://apis.io/apis/torgix-ai/torgix-ai-checkouts-api/) — Small-tool checkouts: what left the shop, where it went, when it came back, what was charged. Read-only.
- [Torgix Compliance API](https://apis.io/apis/torgix-ai/torgix-ai-compliance-api/) — Create, update, delete.
- [Torgix Compliance Requirements API](https://apis.io/apis/torgix-ai/torgix-ai-compliance-requirements-api/) — State compliance requirements the account tracks, with authority, cadence and verification status. Read-only.
- [Torgix Cost Inputs API](https://apis.io/apis/torgix-ai/torgix-ai-cost-inputs-api/) — The per-asset inputs True Cost is computed from (purchase, salvage, finance, insurance, storage). Create, update, delete.
- [Torgix Costs API](https://apis.io/apis/torgix-ai/torgix-ai-costs-api/) — Computed True Cost rows per asset, including the CFO fields; read-only because they are derived. Read-only.
- [Torgix Customer Contacts API](https://apis.io/apis/torgix-ai/torgix-ai-customer-contacts-api/) — Create, update, delete.
- [Torgix Customers API](https://apis.io/apis/torgix-ai/torgix-ai-customers-api/) — Read-only.
- [Torgix Documents API](https://apis.io/apis/torgix-ai/torgix-ai-documents-api/) — Document metadata; the storage path is not exposed and uploads go through the app. Read-only.
- [Torgix Downtime API](https://apis.io/apis/torgix-ai/torgix-ai-downtime-api/) — Create only (append log).
- [Torgix Employees API](https://apis.io/apis/torgix-ai/torgix-ai-employees-api/) — People for labor costing: position, pay basis, burden. Includes pay fields; issue keys accordingly. Create, update, delete.
- [Torgix Events API](https://apis.io/apis/torgix-ai/torgix-ai-events-api/) — The Events API from Torgix — 1 operation(s) for events.
- [Torgix Faults API](https://apis.io/apis/torgix-ai/torgix-ai-faults-api/) — Diagnostic trouble codes per asset (OBD-II, J1939, J1587) from telematics, import, or manual entry. Post one to record a code read off the machine. Create…
- [Torgix Fleet Briefs API](https://apis.io/apis/torgix-ai/torgix-ai-fleet-briefs-api/) — AI fleet briefs generated for the account, by date. Read-only.
- [Torgix Fuel Logs API](https://apis.io/apis/torgix-ai/torgix-ai-fuel-logs-api/) — Create only (append log).
- [Torgix Geofences API](https://apis.io/apis/torgix-ai/torgix-ai-geofences-api/) — Geofences (points of interest) defined in the telematics provider: circle (center and radius in meters) or polygon (points as [lat, lon] pairs). active is…
- [Torgix Idle Time API](https://apis.io/apis/torgix-ai/torgix-ai-idle-time-api/) — Idle events derived from telematics. Read-only.
- [Torgix Inspection Defects API](https://apis.io/apis/torgix-ai/torgix-ai-inspection-defects-api/) — Defects raised on vehicle checks synced from the telematics provider, with the provider repair status (OPEN, DEFERRED, CLOSED_REPAIRED and so on). The check…
- [Torgix Inspection Templates API](https://apis.io/apis/torgix-ai/torgix-ai-inspection-templates-api/) — Inspection checklists defined by the account. Read-only.
- [Torgix Inspections API](https://apis.io/apis/torgix-ai/torgix-ai-inspections-api/) — Create only (append log).
- [Torgix Insurance API](https://apis.io/apis/torgix-ai/torgix-ai-insurance-api/) — Create, update, delete.
- [Torgix Inventory API](https://apis.io/apis/torgix-ai/torgix-ai-inventory-api/) — Read-only.
- [Torgix Inventory Usage API](https://apis.io/apis/torgix-ai/torgix-ai-inventory-usage-api/) — Read-only.
- [Torgix Issues API](https://apis.io/apis/torgix-ai/torgix-ai-issues-api/) — Create, update, delete.
- [Torgix Locations API](https://apis.io/apis/torgix-ai/torgix-ai-locations-api/) — Create, update, delete.
- [Torgix Maintenance API](https://apis.io/apis/torgix-ai/torgix-ai-maintenance-api/) — Completed service history. Append-only: a log is a record of work already done. Create only (append log).
- [Torgix Meter Daily API](https://apis.io/apis/torgix-ai/torgix-ai-meter-daily-api/) — One row per asset per day: engine hours, idle, odometer, fuel, PTO and regen hours, payload. Fed by Samsara, Motive or Rovi. Read-only.
- [Torgix Meter Readings API](https://apis.io/apis/torgix-ai/torgix-ai-meter-readings-api/) — Create only (append log).
- [Torgix Module Briefs API](https://apis.io/apis/torgix-ai/torgix-ai-module-briefs-api/) — AI briefs generated per module and record. Read-only.
- [Torgix Parts API](https://apis.io/apis/torgix-ai/torgix-ai-parts-api/) — Read-only.
- [Torgix Parts Orders API](https://apis.io/apis/torgix-ai/torgix-ai-parts-orders-api/) — Read-only.
- [Torgix Pm Schedules API](https://apis.io/apis/torgix-ai/torgix-ai-pm-schedules-api/) — Preventive maintenance schedules per asset (interval, last done, next due). Read-only.
- [Torgix Project Assets API](https://apis.io/apis/torgix-ai/torgix-ai-project-assets-api/) — Create only (append log).
- [Torgix Projects API](https://apis.io/apis/torgix-ai/torgix-ai-projects-api/) — Read-only.
- [Torgix Recalls API](https://apis.io/apis/torgix-ai/torgix-ai-recalls-api/) — NHTSA recalls, OEM bulletins and manual notices matched to an asset, with a status workflow. Create only (append log).
- [Torgix Reference API](https://apis.io/apis/torgix-ai/torgix-ai-reference-api/) — The Reference API from Torgix — 1 operation(s) for reference.
- [Torgix Rental Catalog API](https://apis.io/apis/torgix-ai/torgix-ai-rental-catalog-api/) — Rentable items and services with their rates. Read-only.
- [Torgix Rental Classes API](https://apis.io/apis/torgix-ai/torgix-ai-rental-classes-api/) — Rental classes an asset can belong to (rate setup follows the rental billing release). Read-only.
- [Torgix Rental Logistics API](https://apis.io/apis/torgix-ai/torgix-ai-rental-logistics-api/) — Deliveries and pickups scheduled against a rental contract. Read-only.
- [Torgix Rentals API](https://apis.io/apis/torgix-ai/torgix-ai-rentals-api/) — Read-only.
- [Torgix Service Trip Stops API](https://apis.io/apis/torgix-ai/torgix-ai-service-trip-stops-api/) — The stops on a road call, each tied to a work order with its share of the trip cost. Read-only.
- [Torgix Service Trips API](https://apis.io/apis/torgix-ai/torgix-ai-service-trips-api/) — Job-site repair trips by a service truck, costed by miles and mechanic time. Read-only.
- [Torgix Telematics Alerts API](https://apis.io/apis/torgix-ai/torgix-ai-telematics-alerts-api/) — Alerts the telematics provider triggered (speeding, idling, geofence arrive or leave, maintenance fault, tamper and so on), matched to the asset. Read-only.…
- [Torgix Telematics API](https://apis.io/apis/torgix-ai/torgix-ai-telematics-api/) — Latest GPS and engine snapshot per asset, fed by the connected telematics provider. Read-only.
- [Torgix Tire Readings API](https://apis.io/apis/torgix-ai/torgix-ai-tire-readings-api/) — Create only (append log).
- [Torgix Torgix API](https://apis.io/apis/torgix-ai/torgix-ai-torgix-api-api/) — The Torgix API API from Torgix — 1 operation(s) for torgix api.
- [Torgix Trips API](https://apis.io/apis/torgix-ai/torgix-ai-trips-api/) — One row per journey from the connected telematics provider: start and end time, place, address and geofence, distance in miles, top and average speed in…
- [Torgix Users API](https://apis.io/apis/torgix-ai/torgix-ai-users-api/) — Read-only.
- [Torgix Vendor Orders API](https://apis.io/apis/torgix-ai/torgix-ai-vendor-orders-api/) — Parts orders placed through Commerce Connect vendors, with totals and status. Read-only.
- [Torgix Warranties API](https://apis.io/apis/torgix-ai/torgix-ai-warranties-api/) — Read-only.
- [Torgix Warranty Assessments API](https://apis.io/apis/torgix-ai/torgix-ai-warranty-assessments-api/) — AI warranty verdict per work order: covered items, exclusions, rationale, confidence. Read-only.
- [Torgix Warranty Skus API](https://apis.io/apis/torgix-ai/torgix-ai-warranty-skus-api/) — Warranty products the account sells or tracks. Read-only.
- [Torgix Work Orders API](https://apis.io/apis/torgix-ai/torgix-ai-work-orders-api/) — Create, update, delete.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Torgix Ai Webhooks](https://apis.io/asyncapis/torgix-ai/torgix-ai-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Torgix Agentic Access](https://apis.io/agentic-access/torgix-ai/torgix-ai-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [BatchRequest](https://apis.io/schemas/torgix-ai/torgix-ai-batch-request/)
- [BatchResponse](https://apis.io/schemas/torgix-ai/torgix-ai-batch-response/)
- [EventList](https://apis.io/schemas/torgix-ai/torgix-ai-event-list/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Torgix Ai Context](https://apis.io/jsonld/torgix-ai/torgix-ai-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Torgix API Rules](https://apis.io/rules/torgix-ai/torgix-ai-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Torgix Authentication](https://apis.io/security/torgix-ai/torgix-ai-authentication/)
- [Torgix Domain Security](https://apis.io/security/torgix-ai/torgix-ai-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Torgix Scopes](https://apis.io/scopes/torgix-ai/torgix-ai-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Torgix Plans Pricing](https://apis.io/plans/torgix-ai/torgix-ai-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://torgix.ai/)
- [Documentation](https://torgix.ai/api.html)
- [Getting started](https://torgix.ai/quickstart.html)
- [API reference](https://torgix.ai/openapi.json)
- [Pricing](https://torgix.ai/pricing.html)
- [Support](https://torgix.ai/contact.html)
- [Terms of service](https://torgix.ai/legal/terms.html)
- [Privacy policy](https://torgix.ai/legal/privacy.html)

## API Evangelist rating

**Kin Score 57.5** — strong · rubric 0.27.0 · scored 2026-11-27

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 67.2 |
| Contract governance | 79.1 |
| Operational transparency | 7.9 |
| Developer ergonomics | 45.2 |
| Access clarity | 60.0 |

**Agent readiness 58.0** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | verified |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 31.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/torgix-ai/](https://apis.io/providers/torgix-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Torgix: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/torgix-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
