# Teesnap (teesnap)

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

Teesnap is an all-in-one golf course management platform and point-of-sale system for golf operators, founded in 2013 and based in Las Vegas, Nevada. Its cloud software suite covers a tee sheet and tee-time booking engine, golf and food-and-beverage point of sale, customer and membership management, an online store, websites, payments, and a marketing and reporting system.

> **Access model: partner-gated.** As of this catalog's review date (2026-07-11), Teesnap does **not** publish a public, self-service developer API or developer portal. There is no documented API reference, OpenAPI, authentication guide, or SDK on teesnap.com or support.teesnap.com. Extensibility is delivered through partner and business-development integrations rather than an open API. The APIs described below are **honestly modeled** from Teesnap's public product surface and are marked `endpointsModeled: true` — no endpoints, base URLs, or schemas are fabricated.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/teesnap/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/teesnap/refs/heads/main/apis.yml)

## Tags

- Golf
- Point of Sale
- POS
- Tee Times
- Golf Course Management
- Booking
- Partner Gated

## Timestamps

- **Created:** 2026-07-11
- **Modified:** 2026-07-11

## Partner Integrations

Teesnap connects to the golf ecosystem through partner-gated integrations rather than a public API:

- **GolfNow** (NBC Sports Next) — official online tee-time distribution partner / marketplace
- **Priswing** — AI-driven dynamic tee-time pricing
- **Golf Genius** — tournament management, player-profile sync
- **QuickBooks Online** — accounting sync
- **Gallus** — branded mobile apps
- **Heartland** — payment processing
- **eRange** / **Select Pi** — driving-range hardware

## APIs (Modeled)

These are logical API areas modeled from Teesnap's described product capabilities. They are **not** sourced from published API documentation and carry `endpointsModeled: true`.





## Pricing

Teesnap pricing is quote-based (contact sales) and tailored to the golf operation; there is no published API plan or developer tier. Third-party software directories have reported a starting figure around USD 60 per user per month, which is unverified against any official Teesnap price list. See [plans/teesnap-plans-pricing.yml](plans/teesnap-plans-pricing.yml).

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/teesnap)
- [Website](https://www.teesnap.com)
- [Documentation / Support](https://support.teesnap.com)
- [Plans](plans/teesnap-plans-pricing.yml)
- [Integrations](https://www.teesnap.com/partners-integrations/)

## WebSocket Review

Does Teesnap expose a documented public WebSocket API? **No.** Teesnap publishes no public API of any kind — REST or WebSocket — so no AsyncAPI document was authored. See [review.yml](review.yml).

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
