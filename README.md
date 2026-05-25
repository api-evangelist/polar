# Polar (polar)
Polar Electro Oy (operating as Polar Global) is a Finnish sports and fitness technology company founded in 1977 and headquartered in Kempele, Finland. Polar invented the first wireless wearable heart rate monitor — the Sport Tester PE 2000 in 1982 — and remains one of the longest-standing brands in consumer heart rate sensing, GPS sports watches, and fitness wearables. Developers access Polar data through the Polar AccessLink API for consumer Polar Flow data, the Polar TeamPro API for team and player training sessions, and the open-source Polar BLE SDK for iOS and Android applications.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/polar/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Fitness, Health, Wearables, Heart Rate, Sports, Training, Sleep, Activity Tracking, Sensors, Bluetooth

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Polar AccessLink API
OAuth2-based partner access to Polar Flow user data. Endpoints cover training sessions (including FIT, TCX, and GPX downloads), daily activity, continuous heart rate, sleep, Nightly Recharge, Cardio Load, SleepWise (alertness, circadian bedtime), and Elixir biosensing (ECG, SpO2, body and skin temperature, skin contacts). Webhooks deliver real-time notifications when new user data is available.

**Human URL:** [https://www.polar.com/accesslink-api/](https://www.polar.com/accesslink-api/)

**Base URL:** `https://www.polaraccesslink.com/`

- [Documentation](https://www.polar.com/accesslink-api/)
- [OpenAPI (upstream)](https://www.polar.com/accesslink-api/swagger.yaml)
- [OpenAPI (local)](openapi/polar-accesslink-api-openapi.yml)
- [Partner Admin Console](https://admin.polaraccesslink.com/)
- [Python Example](https://github.com/polarofficial/accesslink-example-python)
- [Limited License Agreement](https://www.polar.com/en/legal/polar-api-agreement)

### Polar TeamPro API
OAuth2 authorization-code API for the Polar Team Pro system. Provides teams, sport profiles, team training sessions, and player training sessions with date-range filtering, plus session and phase summaries (heart rate, speed, power, acceleration). Rate limited to 1 request/second with a 100-request burst allowance.

**Human URL:** [https://www.polar.com/teampro-api/](https://www.polar.com/teampro-api/)

**Base URL:** `https://teampro.api.polar.com/`

- [Documentation](https://www.polar.com/teampro-api/)
- [OpenAPI (upstream)](https://www.polar.com/teampro-api/swagger.yaml)
- [OpenAPI (local)](openapi/polar-teampro-api-openapi.yml)
- [Partner Admin Console](https://admin.polaraccesslink.com/)

### Polar BLE SDK
Open-source SDK for streaming live data from Polar sensors over Bluetooth Low Energy. Supports H10, H9, Verity Sense, OH1, Ignite 3, Polar 360/Loop, Vantage V3, Vantage M3, Grit X2 Pro, Grit X2, Pacer Pro, and Pacer. Streams heart rate, ECG, accelerometer, PPG, gyroscope, magnetometer, and PPI. iOS 14.0+ (Swift) and Android minSdk 24 (Kotlin/Java).

**Human URL:** [https://github.com/polarofficial/polar-ble-sdk](https://github.com/polarofficial/polar-ble-sdk)

- [Repository](https://github.com/polarofficial/polar-ble-sdk)
- [Polar SDK overview](https://www.polar.com/en/business/sdk)
- [Mobile App Starter](https://github.com/polarofficial/create-mobile-app-for-polar-sensors)

## Common Resources

- [Polar](https://www.polar.com/en) — Portal
- [Polar Developers](https://www.polar.com/en/developers) — Developer portal
- [Polar API for Business](https://www.polar.com/en/business/api) — Business landing page
- [Polar SDK](https://www.polar.com/en/business/sdk) — SDK landing page
- [AccessLink Partner Admin Console](https://admin.polaraccesslink.com/) — Partner sign-up and OAuth credential management
- [Polar Official GitHub](https://github.com/polarofficial) — Organization
- [Polar BLE SDK](https://github.com/polarofficial/polar-ble-sdk) — iOS + Android BLE SDK
- [AccessLink Python Example](https://github.com/polarofficial/accesslink-example-python) — Sample app
- [Mobile App Starter](https://github.com/polarofficial/create-mobile-app-for-polar-sensors) — Mobile development guide
- [Polar Flow](https://flow.polar.com/) — Consumer companion app
- [Polar Support](https://support.polar.com/en) — Support
- [Compatible Apps](https://www.polar.com/en/compatible-apps) — Third-party integrations
- [Research Collaboration](https://www.polar.com/en/science/collaborate-with-us) — Academic and scientific partnerships
- [Polar API Agreement](https://www.polar.com/en/legal/polar-api-agreement) — Terms of Service
- [LinkedIn](https://www.linkedin.com/company/polar-electro) · [X](https://twitter.com/PolarGlobal) · [YouTube](https://www.youtube.com/user/PolarGlobalOfficial) · [Facebook](https://www.facebook.com/polarglobal) · [Instagram](https://www.instagram.com/polarglobal/)

## Features

- Polar AccessLink API with OAuth2 access to Polar Flow user training, activity, sleep, and biosensing data
- Continuous heart rate (5-minute samples), Nightly Recharge, SleepWise alertness, and circadian bedtime endpoints
- Cardio Load training-impulse calculation across days and months
- Elixir biosensing endpoints — ECG, SpO2, body and skin temperature, skin contacts
- Exercise downloads in JSON, FIT, TCX, and GPX formats
- Webhook subscriptions for real-time delivery of new training, activity, and sleep data
- Transactional endpoints (data is discarded after commit) and non-transactional persistent endpoints
- Polar TeamPro API for coaches with team and player training session data
- OAuth2 authorization-code flow with `team_read` scope for TeamPro and `accesslink.read_all` for AccessLink
- Partner registration and OAuth credential management at admin.polaraccesslink.com
- Polar BLE SDK for iOS (Swift) and Android (Kotlin/Java) streaming live HR, ECG, ACC, PPG, gyro, magnetometer, PPI
- Supported sensors include H10, H9, Verity Sense, OH1, Polar 360/Loop, Vantage V3, Vantage M3, Grit X2 Pro, Pacer Pro
- Heart-rate monitoring pioneer — first wireless wearable HR monitor (Sport Tester PE 2000, 1982)
- Google Fit and Apple HealthKit integration paths for consumer data sharing
- Dynamic rate limiting on AccessLink based on registered user count (15-minute and 24-hour windows)
- TeamPro API rate limit of 1 request/second with 100-request burst
- Polar Flow ecosystem (web at flow.polar.com plus iOS, Android, and Huawei mobile apps)
