# Adapt Naturals — Business Context Sheet

> **All figures in this packet are illustrative**, created for this exercise. They are modeled to behave like a real DTC subscription supplement account but do not represent Adapt Naturals' actual performance. Treat them as if real; don't share externally.

## The account

Adapt Naturals sells clinician-grade supplements (flagship: Bio-Avail Multi) direct-to-consumer on a subscription-first model via adaptnaturals.com (Shopify). Paid acquisition runs on Meta (primary) and Google (Brand Search, Non-Brand Search, Shopping). The data packet covers **April 21 – July 19, 2026** (90 days).

A Memorial Day promotion ran **May 22–26** (site-wide offer). A site theme update shipped in **mid-June**.

## Metric definitions

- **aMER (acquisition marketing efficiency ratio):** new-customer revenue ÷ ad spend, per channel or ad.
- **nCPA:** ad spend ÷ new customers acquired.
- **% new customers (%NC):** new-customer purchases ÷ total attributed purchases.
- **Frequency (7d):** average impressions per user, trailing 7 days.

## Illustrative unit economics

| Metric | Value |
|---|---|
| First-order AOV (new customer) | $92 |
| Returning-customer AOV | $68 |
| First-purchase subscription opt-in rate | 38% |
| 12-month LTV — subscriber | $310 |
| 12-month LTV — one-time buyer | $118 |
| Blended 12-month LTV per new customer | ~$191 |
| Contribution margin (pre-ad-spend) | 60% |
| **Breakeven aMER for 12-month payback** | **0.85** (nCPA ≤ ~$108) |

## Company targets (current quarter)

| Target | Threshold |
|---|---|
| Meta % new customers | ≥ 85% |
| Creative testing share of Meta budget | 20% |
| Single-ad spend concentration | No ad > 20% of account spend (exception allowed if ad aMER > rolling 7-day channel average) |
| Meta Purchase event match quality (EMQ) | ≥ 7.0 |
| Non-Brand SEM + Shopping | > 25% of total media mix at ≥ 0.85 aMER |
| New test ads launched | Weekly cadence, sustained |

## Files in this packet

| File | Contents |
|---|---|
| `meta_daily.csv` | Meta daily performance at ad level: spend, impressions, clicks, frequency (7d), purchases, purchase value, new-customer purchases, new-customer value |
| `google_daily.csv` | Google daily performance at campaign level, incl. search impression share for Search campaigns |
| `emq_weekly.csv` | Weekly Meta pixel event match quality scores and event volumes |
| `utm_audit_sample.csv` | A sample of live ad destination URLs pulled from both platforms |
| `business_context.md` | This sheet |

Attribution note: Meta figures are platform-attributed (7-day click / 1-day view). Google figures are platform-attributed (data-driven). Expect the normal disagreements between platform and business truth — part of the job is knowing where those disagreements matter.
