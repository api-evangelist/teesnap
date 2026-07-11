# Teesnap (teesnap)

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

### Teesnap Tee Sheet API

Modeled tee sheet and tee-time booking surface — reservations, availability, and rate types. Exposed to partners (e.g. GolfNow distribution) through gated integrations, not a public API.

- **Human URL:** [https://www.teesnap.com/our-platform/](https://www.teesnap.com/our-platform/)

### Teesnap Point of Sale API

Modeled point-of-sale surface for pro-shop and food-and-beverage sales, orders, tenders, and payment capture (Heartland processing, QuickBooks Online sync).

- **Human URL:** [https://www.teesnap.com/point-of-sale/](https://www.teesnap.com/point-of-sale/)

### Teesnap Members and Customers API

Modeled customer and membership surface — golfer profiles, memberships, and account data feeding the marketing system (Golf Genius player-profile sync is a known partner integration).

- **Human URL:** [https://www.teesnap.com/our-platform/](https://www.teesnap.com/our-platform/)

### Teesnap Products and Inventory API

Modeled product catalog and inventory surface backing the pro-shop POS and the Teesnap online store — products, pricing, and stock levels.

- **Human URL:** [https://www.teesnap.com/point-of-sale/](https://www.teesnap.com/point-of-sale/)

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
