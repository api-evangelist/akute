# Akute Health (akute)

Akute Health is an automation-first, API- and developer-friendly EHR (electronic health record) platform for digital health, telehealth, direct primary care, and GLP-1 weight-loss clinics. Its REST API at https://api.akutehealth.com/v1 exposes FHIR-aligned resources - patients, appointments, clinical notes, tasks, documents, medications and e-prescribing, lab orders and results, plus signed webhooks - so customers can enrich the record and build patient-facing or internal applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/akute/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/akute/refs/heads/main/apis.yml)

## Tags

- Healthcare
- EHR
- EMR
- FHIR
- Digital Health
- Telehealth

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Akute Patients API

Create, update, retrieve, and search patient records by internal id or external_id, including demographics, contact details, and external id mapping for synchronizing patients between systems.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Patients
- Demographics
- FHIR

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [API Reference](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Appointments API

Book, update, cancel, and search appointments, list appointment types, and query practitioner availability windows for scheduling across the practice.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Appointments
- Scheduling
- Availability

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Encounters API

Create and retrieve clinical encounter documentation as structured, multi-section notes (progress notes, phone notes, SOAP) with authors, signing user, service date, and final or preliminary status.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Encounters
- Clinical Notes
- Documentation

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Tasks API

Create, update, retrieve, and search care-team tasks with owner, patient, priority, status, tags, and due-date ranges to coordinate clinical and administrative workflow.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Tasks
- Workflow
- Care Coordination

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Documents API

Upload, retrieve, and search documents and file attachments, optionally associated with a patient, supporting PDF report storage and paginated, sortable listing.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Documents
- Files
- Attachments

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Medications API

Search the drug catalog, retrieve patient medications and Surescripts medication history (live or cached), look up dispensable drugs and pharmacies, and manage patient pharmacies for e-prescribing.

- **Human URL:** [https://developer.akutehealth.com/](https://developer.akutehealth.com/)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Medications
- e-Prescribing
- Pharmacy

#### Properties

- [Documentation](https://developer.akutehealth.com/)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Labs API

Search lab procedures and facilities, place lab orders, track order requests, and retrieve diagnostic reports and individual lab and vital-sign observations, including report PDFs.

- **Human URL:** [https://help.akutehealth.com/article/196-ordering-labs-via-api](https://help.akutehealth.com/article/196-ordering-labs-via-api)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Labs
- Orders
- Diagnostic Reports
- Observations

#### Properties

- [Documentation](https://help.akutehealth.com/article/196-ordering-labs-via-api)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akute Webhooks API

Register and manage webhook subscriptions for resource events (patients, appointments, notes, tasks, medications, diagnostic reports, orders, faxes, conversations) with HMAC-SHA256 signed delivery via the x-akute-signature header.

- **Human URL:** [https://help.akutehealth.com/article/212-supported-webhooks](https://help.akutehealth.com/article/212-supported-webhooks)
- **Base URL:** `https://api.akutehealth.com/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://help.akutehealth.com/article/212-supported-webhooks)
- [OpenAPI](openapi/akute-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/akute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/akute-health-inc)
- [LinkedIn](https://www.linkedin.com/company/akute-health)
- [Website](https://www.akutehealth.com/)
- [Documentation](https://developer.akutehealth.com/)
- [Plans](plans/akute-plans-pricing.yml)
- [Rate Limits](rate-limits/akute-rate-limits.yml)
- [Fin Ops](finops/akute-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
