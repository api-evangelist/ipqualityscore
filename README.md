# IPQualityScore (ipqualityscore)

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

IPQualityScore (IPQS) provides real-time fraud prevention and threat intelligence APIs covering proxy/VPN/Tor and IP reputation scoring, email and phone validation, malicious URL and domain scanning, device fingerprinting, transaction risk scoring, and dark-web leaked-data checks. All endpoints are delivered as a simple REST/JSON interface with the API key passed in the request path.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ipqualityscore/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ipqualityscore/refs/heads/main/apis.yml)

## Tags

- Fraud Prevention
- IP Reputation
- Proxy Detection
- Email Validation
- Threat Intelligence

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### IP Reputation & Proxy/VPN Detection API

Scores an IP address for proxy, VPN, and Tor usage, bot status, recent abuse, and abuse velocity, returning a 0-100 fraud score plus geolocation and connection metadata. Requested as GET /ip/{api_key}/{ip}.

- **Human URL:** [https://www.ipqualityscore.com/documentation/proxy-detection-api/overview](https://www.ipqualityscore.com/documentation/proxy-detection-api/overview)
- **Base URL:** `https://www.ipqualityscore.com/api/json`

#### Tags

- IP Reputation
- Proxy Detection
- VPN
- Tor

#### Properties

- [Documentation](https://www.ipqualityscore.com/documentation/proxy-detection-api/overview)
- [API Reference](https://www.ipqualityscore.com/documentation/proxy-detection-api/response-parameters)
- [OpenAPI](openapi/ipqualityscore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipqualityscore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipqualityscore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Email Validation API

Verifies email addresses for validity, deliverability, disposable/temporary domains, spam traps, honeypots, and recent abuse, returning a fraud score and DNS/MX checks. Requested as GET /email/{api_key}/{email}.

- **Human URL:** [https://www.ipqualityscore.com/documentation/email-validation-api/overview](https://www.ipqualityscore.com/documentation/email-validation-api/overview)
- **Base URL:** `https://www.ipqualityscore.com/api/json`

#### Tags

- Email Validation
- Disposable Email
- Deliverability

#### Properties

- [Documentation](https://www.ipqualityscore.com/documentation/email-validation-api/overview)
- [API Reference](https://www.ipqualityscore.com/documentation/email-validation-api/response-parameters)
- [OpenAPI](openapi/ipqualityscore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipqualityscore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipqualityscore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Phone Number Validation API

Validates phone numbers across 150+ countries, returning carrier, line type (mobile, VOIP, landline, prepaid), active status, geolocation, and a fraud score. Requested as GET /phone/{api_key}/{phone}.

- **Human URL:** [https://www.ipqualityscore.com/documentation/phone-number-validation-api/overview](https://www.ipqualityscore.com/documentation/phone-number-validation-api/overview)
- **Base URL:** `https://www.ipqualityscore.com/api/json`

#### Tags

- Phone Validation
- Carrier Lookup
- Line Type

#### Properties

- [Documentation](https://www.ipqualityscore.com/documentation/phone-number-validation-api/overview)
- [API Reference](https://www.ipqualityscore.com/documentation/phone-number-validation-api/response-parameters)
- [OpenAPI](openapi/ipqualityscore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipqualityscore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipqualityscore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Malicious URL Scanner API

Scans URLs and domains for phishing, malware, parking, spam, and suspicious content, returning a risk score, domain reputation, and a content category. Requested as GET /url/{api_key}/{url}.

- **Human URL:** [https://www.ipqualityscore.com/documentation/malicious-url-scanner-api/overview](https://www.ipqualityscore.com/documentation/malicious-url-scanner-api/overview)
- **Base URL:** `https://www.ipqualityscore.com/api/json`

#### Tags

- URL Scanner
- Phishing
- Malware
- Domain Reputation

#### Properties

- [Documentation](https://www.ipqualityscore.com/documentation/malicious-url-scanner-api/overview)
- [API Reference](https://www.ipqualityscore.com/documentation/malicious-url-scanner-api/response-parameters)
- [OpenAPI](openapi/ipqualityscore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipqualityscore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipqualityscore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Device Fingerprint API

Analyzes 300+ data points about a user's device and session to detect bots, emulators, and high-risk behavior, returning a fraud score and device signals. Requested as POST /fingerprint/{api_key}.

- **Human URL:** [https://www.ipqualityscore.com/documentation/device-fingerprint-api/overview](https://www.ipqualityscore.com/documentation/device-fingerprint-api/overview)
- **Base URL:** `https://www.ipqualityscore.com/api/json`

#### Tags

- Device Fingerprinting
- Bot Detection
- Fraud Prevention

#### Properties

- [Documentation](https://www.ipqualityscore.com/documentation/device-fingerprint-api/overview)
- [OpenAPI](openapi/ipqualityscore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipqualityscore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipqualityscore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Transaction Scoring API

Extends the IP reputation endpoint with optional billing, shipping, payment, and order parameters to score payment and account fraud risk, returning a transaction_details object with risk factors and address/email/phone validation. Requested as GET /ip/{api_key}/{ip} with transaction parameters.

- **Human URL:** [https://www.ipqualityscore.com/documentation/proxy-detection-api/transaction-scoring](https://www.ipqualityscore.com/documentation/proxy-detection-api/transaction-scoring)
- **Base URL:** `https://www.ipqualityscore.com/api/json`

#### Tags

- Transaction Scoring
- Payment Fraud
- Chargeback Prevention

#### Properties

- [Documentation](https://www.ipqualityscore.com/documentation/proxy-detection-api/transaction-scoring)
- [OpenAPI](openapi/ipqualityscore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipqualityscore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipqualityscore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Leaked Data (Dark Web) API

Checks emails, phone numbers, usernames, passwords, and combinations against breached and dark-web databases, returning exposure status, breach sources, and first-seen timestamps. Requested as GET /leaked/{type}/{api_key}.

- **Human URL:** [https://www.ipqualityscore.com/documentation/dark-web-leak-api/overview](https://www.ipqualityscore.com/documentation/dark-web-leak-api/overview)
- **Base URL:** `https://www.ipqualityscore.com/api/json`

#### Tags

- Dark Web
- Data Breach
- Leaked Credentials

#### Properties

- [Documentation](https://www.ipqualityscore.com/documentation/dark-web-leak-api/overview)
- [OpenAPI](openapi/ipqualityscore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipqualityscore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipqualityscore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/IPQualityScore)
- [LinkedIn](https://www.linkedin.com/company/ipqualityscore)
- [Website](https://www.ipqualityscore.com)
- [Documentation](https://www.ipqualityscore.com/documentation/overview)
- [Plans](plans/ipqualityscore-plans-pricing.yml)
- [Rate Limits](rate-limits/ipqualityscore-rate-limits.yml)
- [Fin Ops](finops/ipqualityscore-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
