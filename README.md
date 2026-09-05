# Hussen Ghabayen

**Flutter Developer** · Gaza, Palestine (GMT+3) · Open to full-time remote

Nine apps live on the App Store and Google Play across five markets. Sole author of six production codebases totaling ~250,000 lines of Dart. I build Arabic-first, offline-capable mobile products on feature-first Clean Architecture — and I ship them end to end, from repository layer to signed store release.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hussendev/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://hussendev.netlify.app/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ghabayenhussej@gmail.com)

---

## Published Apps

| App | What it is | Market | Links |
|---|---|---|---|
| **Mushaf Qatar** | Official Qur'an app of the Qatar Ministry of Awqaf — 50K+ downloads, 4.5★ (947 reviews) | Qatar | [App Store](https://apps.apple.com/us/app/id500544210) · [Play](https://play.google.com/store/apps/details?id=com.islamweb.ns.quran) |
| **Eduba** | Spaced-repetition learning platform with an Anki-compatible SRS engine | MENA | [App Store](https://apps.apple.com/us/app/eduba/id6762039465) · [Play](https://play.google.com/store/apps/details?id=wepioners.eduba.com) |
| **MisterCar** | Car services and licensing platform with Telr payments | Saudi Arabia | [App Store](https://apps.apple.com/us/app/id6758611421) · [Play](https://play.google.com/store/apps/details?id=com.mistercarsa.abd_aziz_app) |
| **Dar Al-Asas** | Gold-investment and wallet platform (Flutter + TypeScript backend) | Iraq | [App Store](https://apps.apple.com/us/app/id6789016723) · [Play](https://play.google.com/store/apps/details?id=wepioners.tjaraa.com) |
| **Kayan Cafe** | Multi-tenant cafe-management SaaS | Egypt | [Play](https://play.google.com/store/apps/details?id=com.kayan.app) |
| **MMB** | Salon booking and e-commerce | Palestine | [App Store](https://apps.apple.com/us/app/mmb/id6462795471) · [Play](https://play.google.com/store/apps/details?id=ps.mmb.app) |
| **E-Shabni** | Ride-hailing — passenger app | Iraq | [App Store](https://apps.apple.com/us/app/id6755629100) · [Play](https://play.google.com/store/apps/details?id=com.saifsaad.taksicar_user) |
| **E-Shabni Captain** | Ride-hailing — driver app | Iraq | [App Store](https://apps.apple.com/us/app/id6755610414) · [Play](https://play.google.com/store/apps/details?id=com.saifsaad.taksicar_driver) |
| **LinkedWithin** | AI life-management platform with WebRTC voice and SSE streaming chat | Australia | Pre-launch |

> Most of this work lives in private client repositories, so it isn't visible here. The links above are the shipped result.

---

## Engineering I'm proud of

**Anki-compatible SRS engine** *(Eduba)* — New/learning/review/relearning queues, ease-factor scheduling, graduating and easy intervals, lapse and leech handling, all server-configurable. Backed by unit tests.

**Offline Arabic Qur'an search** *(Mushaf Qatar)* — Diacritic-insensitive search across 114 surahs and 6,000+ ayahs using a Dart isolate word index, meeting CI-enforced latency budgets of p50 < 25 ms and p95 < 75 ms.

**WebRTC voice coach + SSE streaming** *(LinkedWithin)* — Parallel local-offer and session creation, 1.5s ICE gathering timeout, Android audio focus handling, inbound-audio speech detection. Streaming chat over a line-based SSE parser with sealed event types and mid-stream disconnect recovery.

**Correctness-first HTTP layer** *(Kayan Cafe)* — RFC 7807 Problem Details error mapping, `Idempotency-Key` on writes, `If-Match` optimistic concurrency with replay detection surfaced in the UI.

**Payment verification that doesn't trust the client** *(MisterCar)* — Telr XML Mobile API through a WebView, intercepting deep links and return URLs, verifying against the gateway completion endpoint before backend confirmation, with double-finalize guards.

**Transactional money handling** *(Dar Al-Asas)* — Investment subscription, wallet withdrawal and daily profit claiming as atomic Firestore transactions over a dual-currency ledger, with a server-clock-aligned cooldown. Backend is mine too: 6 HTTPS callables and 2 Firestore triggers in TypeScript.

**A 500k-line migration** *(MMB)* — Replaced a FluxStore/WooCommerce template with a hand-written Clean Architecture codebase: ~493k lines removed, ~22k authored. Also cut ~50s iOS launch stalls by capping the image cache and applying decode-size limits.

---

## Stack

**Core** — Flutter · Dart 3 · Android · iOS

**Architecture** — Clean Architecture · feature-first modules · Repository pattern · Use Cases · SOLID

**State & DI** — flutter_bloc (Cubit/BLoC) · Riverpod · Provider · GetIt · dartz `Either` · Equatable

**Routing** — go_router · StatefulShellRoute · route guards

**Networking** — REST · Dio · SSE · WebRTC · Socket.IO · LiveKit · RFC 7807 · Idempotency-Key · If-Match

**Backend** — Firebase (Auth, Firestore, Cloud Functions, Storage, FCM, Crashlytics) · Node.js 20 + TypeScript · NestJS · Laravel Sanctum and ASP.NET Core APIs

**Storage** — Drift/SQLite · Hive · flutter_secure_storage · offline-first sync queues · paginated cache

**Payments** — RevenueCat · Telr · Stripe · wallet ledgers · installments

**Testing & CI** — flutter_test · mocktail · integration_test · golden tests · GitHub Actions · flavors

**i18n** — gen-l10n · ARB · Arabic / English / Urdu / Hindi · full RTL

---

## Experience

**Flutter Developer — [Wepioners](https://wepioners.com/)** · May 2025 – Present
Lead mobile developer on the product portfolio: BALONIA (social live-streaming, 16,000+ users, LiveKit + Socket.IO), Eduba, Dar Al-Asas and E-Shabni. Standardized delivery on Clean Architecture with Cubit, GetIt and go_router.

**Freelance Flutter Developer** · Oct 2025 – Present
Clients in Australia, Qatar, Saudi Arabia, Egypt and Palestine. Five production apps, owned end to end.

**Data Entry Volunteer — International Medical Corps** · Jul 2023 – Sep 2024
Managed medical and aid-distribution data during the humanitarian crisis in Gaza.

**Open-Source Contributor — Bond Framework (Flutter)** · Jun 2023 – Aug 2023
Improved state management, authentication and theming components.

**Mobile Application Developer — Developer Plus** · Jan 2023 – Jul 2023
Shipped 4+ commercial Flutter apps (10,000+ combined downloads). Mentored 3 junior developers and set up the team's code review process.

**Education** — BSc Information Technology, Islamic University of Gaza, 2020–2024 · GPA 89.39/100

---

## Stats

![Stats](https://github-readme-stats.vercel.app/api?username=hussendev&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true)
![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=hussendev&layout=compact&langs_count=8&theme=tokyonight)

---

**Arabic** native · **English** professional working proficiency

Open to full-time remote roles. Reach me at [ghabayenhussej@gmail.com](mailto:ghabayenhussej@gmail.com).
