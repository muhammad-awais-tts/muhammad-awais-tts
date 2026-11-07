# Muhammad Awais

**E-commerce automation for TikTok Shop and Shopify.**
I build the systems behind the stores I run: product feeds, pricing rules, inventory sync,
creator programs, and the compliance guardrails that keep a shop from being shut down.

Most of my work is the unglamorous half of e-commerce — the part that runs at 3am without
anyone watching it, and the part that quietly loses money when it doesn't.

---

### Tracked across the shops I've run

| | |
|---|---|
| GMV tracked | **$16.62M** |
| Orders | **419,826** |
| Blended ROAS | **6.84x** on $343,302.77 of media |
| Creator GMV, best 28-day window | **$4.74M** |
| Account suspensions | **0** |

That last row is the one I care about. Growth on TikTok Shop is not hard to buy; keeping the
shop alive while you buy it is the actual job. Every store I have taken over had at least one
policy violation already counting against it.

---

### What I do

**Catalogue and feed automation.** Supplier feed in, store out — matched on SKU, priced by
rule, images and metafields filled, out-of-stock products drafted and restored automatically.
I currently run one of these over a 6,700-product catalogue with a 2-hourly sync.

**TikTok Shop growth and risk.** Creator outreach and sample programs, affiliate and GMV Max
campaigns, and the violation side nobody advertises: listing audits, appeal handling, and the
account-health work that happens before a strike, not after.

**The things that silently break.** Duplicate SKUs across a catalogue, products that are
"Active" but published to no sales channel, variants priced below cost, sale prices above the
compare-at. None of these raise an error. All of them cost orders. I write tools that find
them.

---

### Open source

**[shopify-catalog-check](https://github.com/muhammad-awais-tts/shopify-catalog-check)** —
fifteen checks over a Shopify product CSV export, standard library only, no API token. Finds
the problems that look fine in the admin: live-but-unpublished products, duplicate SKUs,
live-but-unbuyable pages, cost above price. Run against a real 6,730-product catalogue it
found 77 invisible products and 30 duplicate SKUs, none of which anyone had noticed.

More coming — most of what I build for stores is generic enough to open up once the
client-specific parts are stripped out.

---

### Stack

Python · Shopify Admin GraphQL · TikTok Shop & Affiliate APIs · GitHub Actions · pandas ·
Playwright · Google Sheets API · Liquid

---

### Work with me

Available for catalogue automation, feed integrations, and TikTok Shop account work —
including stores that are already in trouble.

Top Rated on Upwork · 100% job success
