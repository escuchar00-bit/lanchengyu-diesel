# LANCHENGYU Diesel B2B Website

An independent website for Nantong Lanchengyu International Trading Co., Ltd. This repository must remain completely separate from Liangrui Home, liangruihome.com, and Liangrui's ads/analytics configurations.

## Current release — reference database V2 (2026-10-30)
- 80 technical reference records (55 complete injectors, 11 nozzles, 9 valves, 5 repair kits).
- 67 entries from manufacturer-issued catalogues or bulletins, plus 13 with a distributor-hosted Delphi cross-reference guide.
- `products.js`: client-side searchable technical reference index.
- `products.csv` / `products.json`: research and source records.
- English/French B2B buyer guidance, FAQ, search by manufacturer reference / OE number / engine / application.
- Company WhatsApp: **+86 15301481237**.

**Important:** These are technical reference entries, NOT confirmed inventory, price, MOQ, interchangeability, product authenticity, manufacturer authorization, or delivery promises. Isuzu OE numbers containing `#` are incomplete number families. Obtain the exact suffix and verify engine/VIN and calibration before quoting.

### Publishing controls
The preview currently uses `noindex,nofollow` and disallows crawlers via `robots.txt`. Remove these preview protections only after the independent domain, actual stock/supplier documentation, and live RFQ flow are fully checked.

### Deployment
Publish `index.html`, `products.js`, and `assets/` together. Site is plain HTML + JS and does not store RFQs on a server. WhatsApp creates a message which the customer must manually send.
