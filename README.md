# Sea Machines Robotics (sea-machines)

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

Sea Machines Robotics builds autonomous command-and-control systems (SM300-SP, SM300-NG) and computer-vision perception (AI-ris) for commercial and defense marine vessels. In September 2025 it announced the SMLink Streaming-API and SMLink Control-API, partner-gated interfaces that stream real-time vessel telemetry to external systems and let approved third parties command SM300 autonomy functions from their own mission software. These interfaces are embedded, vessel-side product features, not a self-service public developer platform; access is arranged through Sea Machines sales.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sea-machines/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sea-machines/refs/heads/main/apis.yml)

## Tags

- Marine
- Autonomy
- Robotics
- Maritime
- Computer Vision
- Telemetry

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### SMLink Streaming-API

Partner-gated interface announced September 2025 that delivers real-time SM300 vessel telemetry and data feeds (position, heading, mechanical and navigational state) to external command-and-control and mission systems. Supported on the SM300-SP and SM300-NG autonomy systems. No public endpoints, base URL, protocol, or developer documentation are published; access is arranged through Sea Machines sales, so this is documented as an embedded product feature rather than a public API.

- **Human URL:** [https://sea-machines.com/sea-machines-launches-marine-autonomy-apis-for-third-party-c2-systems/](https://sea-machines.com/sea-machines-launches-marine-autonomy-apis-for-third-party-c2-systems/)

#### Tags

- Telemetry
- Streaming
- Integration

#### Properties

- [Documentation](https://sea-machines.com/sea-machines-launches-marine-autonomy-apis-for-third-party-c2-systems/)
- [OpenAPI](openapi/sea-machines-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sea-machines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sea-machines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMLink Control-API

Partner-gated interface announced September 2025 that grants select partners the ability to command SM300 autonomy functions directly from third-party mission software. Supported on the SM300-SP and SM300-NG autonomy systems. No public endpoints, base URL, protocol, or developer documentation are published; access is restricted to approved partners via Sea Machines sales, so this is documented as an embedded product feature rather than a public API.

- **Human URL:** [https://sea-machines.com/sea-machines-launches-marine-autonomy-apis-for-third-party-c2-systems/](https://sea-machines.com/sea-machines-launches-marine-autonomy-apis-for-third-party-c2-systems/)

#### Tags

- Command and Control
- Integration
- Autonomy

#### Properties

- [Documentation](https://sea-machines.com/sea-machines-launches-marine-autonomy-apis-for-third-party-c2-systems/)
- [OpenAPI](openapi/sea-machines-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sea-machines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sea-machines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SM300 Autonomous Command and Control

Industrial-grade vessel intelligence system providing operator-in-the-loop autonomous command and control, multi-waypoint missions, search and survey, patrol and surveillance, and remote command. Available as the attritable SM300-SP and the class-approved SM300-NG. This is an embedded vessel-side product; the SMLink APIs are the integration surface, no standalone public HTTP API is documented.

- **Human URL:** [https://sea-machines.com/](https://sea-machines.com/)

#### Tags

- Autonomy
- Command and Control
- USV

#### Properties

- [Documentation](https://sea-machines.com/sm300-ng/)
- [Documentation](https://sea-machines.com/sm300-sp/)

### AI-ris Computer Vision

AI-ris (Artificial Intelligence Recognition and Identification System) ingests 4K imagery and processes it on-device with embedded AI/ML to detect, track, classify, and geolocate vessel traffic and obstacles day or night for maritime situational awareness. AI-ris contacts surface in FleetViewer; this is an embedded perception product with no documented public API of its own.

- **Human URL:** [https://sea-machines.com/product/ai-ris-computer-vision-center/](https://sea-machines.com/product/ai-ris-computer-vision-center/)

#### Tags

- Computer Vision
- Perception
- Situational Awareness

#### Properties

- [Documentation](https://sea-machines.com/product/ai-ris-computer-vision-center/)

### FleetViewer

Browser-based fleet monitoring and analysis platform for SM300-equipped vessels, offering real-time and historical telemetry at 5-second intervals, mechanical and navigational data (radar, ARPA, AIS, AI-ris contacts), mission playback, and exportable logs. FleetViewer is a no-code ready-to-use tool, not an API; the SMLink APIs cover programmatic integration.

- **Human URL:** [https://sea-machines.com/fleetviewer/](https://sea-machines.com/fleetviewer/)

#### Tags

- Fleet Monitoring
- Telemetry
- Dashboard

#### Properties

- [Documentation](https://sea-machines.com/fleetviewer/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sea-machines)
- [Website](https://sea-machines.com/)
- [Documentation](https://sea-machines.com/sea-machines-launches-marine-autonomy-apis-for-third-party-c2-systems/)
- [Plans](plans/sea-machines-plans-pricing.yml)
- [Rate Limits](rate-limits/sea-machines-rate-limits.yml)
- [Fin Ops](finops/sea-machines-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
