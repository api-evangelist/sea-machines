# Sea Machines Robotics (sea-machines)

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
