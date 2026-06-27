# IPQualityScore (ipqualityscore)

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
