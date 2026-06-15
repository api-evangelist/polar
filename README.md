# Polar (polar)

Polar Electro Oy (operating as Polar Global) is a Finnish sports and fitness technology company founded in 1977 and headquartered in Kempele, Finland. Polar invented the first wireless wearable heart rate monitor — the Sport Tester PE 2000 in 1982 — and remains one of the longest-standing brands in consumer heart rate sensing, GPS sports watches, and fitness wearables. The Polar device portfolio includes the H10 and H9 chest straps, the Verity Sense and OH1 optical sensors, the Polar 360 and Loop fitness bands, and the Vantage, Grit X, Pacer, Ignite, and Unite watch lines, along with a dedicated equine sensor line. Developers access Polar data through the Polar AccessLink API for consumer Polar Flow data, the Polar TeamPro API for team and player training sessions, and the open-source Polar BLE SDK for iOS and Android applications that stream live sensor data over Bluetooth Low Energy.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/polar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/polar/refs/heads/main/apis.yml)

## Scope

- **Position:** Providing
- **Access:** 3rd-Party

## Tags

- Fitness
- Health
- Wearables
- Heart Rate
- Sports
- Training
- Sleep
- Activity Tracking
- Sensors
- Bluetooth

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-30

## APIs

### Polar AccessLink API

The Polar Open AccessLink API gives partners structured OAuth2-based access to Polar Flow user data — training sessions, daily activity, continuous heart rate, sleep, Nightly Recharge, Cardio Load, SleepWise alertness and circadian bedtime, Elixir biosensing (ECG, SpO2, skin and body temperature, skin contacts), exercise files in FIT/TCX/GPX format, and webhooks for real-time notifications when new user data is available. Operates against https://www.polaraccesslink.com/ with both transactional (data discarded after retrieval) and non-transactional endpoints.

- **Human URL:** [https://www.polar.com/accesslink-api/](https://www.polar.com/accesslink-api/)
- **Base URL:** `https://www.polaraccesslink.com/`

#### Tags

- Fitness
- Health
- Heart Rate
- Wearables
- Training
- Activity
- Sleep

#### Properties

- [Documentation](https://www.polar.com/accesslink-api/)
- [OpenAPI](https://www.polar.com/accesslink-api/swagger.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/polar-accesslink-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/polar-accesslink-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-accesslink-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](openapi/polar-accesslink-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Portal](https://admin.polaraccesslink.com/)
- [Code Examples](https://github.com/polarofficial/accesslink-example-python)
- [Terms of Service](https://www.polar.com/en/legal/polar-api-agreement)

### Polar TeamPro API

The Polar TeamPro API exposes team and player training data captured by the Polar Team Pro system. Endpoints return teams, sport profiles, team and player training sessions with date-range filters, detailed per-session metrics (heart rate, speed, power, acceleration), session summaries and phase summaries. OAuth2 authorization-code flow with the team_read scope. Rate limited to 1 request/second with a 100-request burst allowance.

- **Human URL:** [https://www.polar.com/teampro-api/](https://www.polar.com/teampro-api/)
- **Base URL:** `https://teampro.api.polar.com/`

#### Tags

- Fitness
- Health
- Sports
- Teams
- Training
- Coaching

#### Properties

- [Documentation](https://www.polar.com/teampro-api/)
- [OpenAPI](https://www.polar.com/teampro-api/swagger.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/polar-teampro-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/polar-teampro-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-teampro-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Portal](https://admin.polaraccesslink.com/)
- [Terms of Service](https://www.polar.com/en/legal/polar-api-agreement)

### Polar BLE SDK

The Polar BLE SDK enables iOS and Android applications to stream live data from Polar sensors over Bluetooth Low Energy. Supports H10, H9, Verity Sense, OH1, Ignite 3, Polar 360/Loop, Vantage V3, Vantage M3, Grit X2 Pro, Grit X2, Pacer Pro, and Pacer. Streams heart rate, ECG, accelerometer, PPG, gyroscope, magnetometer, and PPI data. iOS 14.0+ (Swift) and Android minSdk 24 (Kotlin/Java) with RxJava/RxSwift for asynchronous operations.

- **Human URL:** [https://github.com/polarofficial/polar-ble-sdk](https://github.com/polarofficial/polar-ble-sdk)

#### Tags

- BLE
- Bluetooth
- SDK
- Heart Rate
- ECG
- Sensors
- Wearables

#### Properties

- [Repository](https://github.com/polarofficial/polar-ble-sdk)
- [Documentation](https://www.polar.com/en/business/sdk)
- [SDK](https://github.com/polarofficial/polar-ble-sdk)
- [Code Examples](https://github.com/polarofficial/create-mobile-app-for-polar-sensors)
- [Postman Collection](collections/polar-accesslink-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-accesslink-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/polar-teampro-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-teampro-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.polar.com/en)
- [Portal](https://www.polar.com/en/developers)
- [Portal](https://www.polar.com/en/business/api)
- [Documentation](https://www.polar.com/accesslink-api/)
- [Documentation](https://www.polar.com/teampro-api/)
- [Sign Up](https://admin.polaraccesslink.com/)
- [SDK](https://www.polar.com/en/business/sdk)
- [GitHub Organization](https://github.com/polarofficial)
- [SDK](https://github.com/polarofficial/polar-ble-sdk)
- [Code Examples](https://github.com/polarofficial/accesslink-example-python)
- [Code Examples](https://github.com/polarofficial/create-mobile-app-for-polar-sensors)
- [Portal](https://flow.polar.com/)
- [Support](https://support.polar.com/en)
- [Documentation](https://www.polar.com/en/compatible-apps)
- [Partners](https://www.polar.com/en/science/collaborate-with-us)
- [Terms of Service](https://www.polar.com/en/legal/polar-api-agreement)
- [Privacy Policy](https://www.polar.com/en/legal/privacy-notice)
- [Terms of Service](https://www.polar.com/en/legal)
- [LinkedIn](https://www.linkedin.com/company/polar-electro)
- [Twitter](https://twitter.com/PolarGlobal)
- [YouTube](https://www.youtube.com/user/PolarGlobalOfficial)
- [Facebook](https://www.facebook.com/polarglobal)
- [Instagram](https://www.instagram.com/polarglobal/)
- [Blog](https://www.polar.com/blog/)
- [Documentation](https://www.polar.com/en/products)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
