# Payments & Cross-Border Partner Programs — Research Notes

Companion notes to [`payments.json`](./payments.json). Covers 11 vendors: Stripe, Adyen, Airwallex, Wise Platform, Rapyd, Nium, Currencycloud, dLocal, Payoneer, Corpay, and Convera.

---

## 1. Thin-Data Vendors (sparse public disclosure)

Payments companies as a category keep commercial terms tightly held. These five stood out as having the least public detail, beyond the industry-wide norm of hiding revenue-share numbers:

- **Corpay** (heritage: FLEETCOR / Cambridge Global Payments) — the official partner page ([corpay.com/cross-border](https://www.corpay.com/cross-border)) doesn't mention "FLEETCOR" or "Cambridge Global Payments" anywhere; that lineage only surfaces in older acquisition press releases (e.g., [2017 FLEETCOR–Cambridge deal announcement](https://www.corpay.com/corporate-newsroom/7226/fleetcor-to-acquire-cambridge-global-payments-a-leading-b2b-international-payments-provider)). No published tiers, MDF, deal registration, or partner fee. Weakest embedded-finance story of the eleven — no third-party accounts, cards, or ledger capability.
- **dLocal** — no published partner tiers, no MDF/deal-registration/fee disclosure, and embedded finance is limited to payments/FX rails (no accounts, cards, or ledger-as-a-service).
- **Currencycloud** (a Visa solution) — program is branded "Fuse" but no tiers beneath that single name are disclosed; no rev-share percentage, no MDF/deal-reg/fee; ecosystem size is only available from older pre-full-Visa-integration citations (~500 clients).
- **Convera** (heritage: Western Union Business Solutions) — no tiers, no rev-share model detail, no MDF/deal-reg/fee. Coverage stats (currencies/countries) and active-partner count (550+) are the only solid disclosed figures.
- **Rapyd and Nium** — both describe revenue share only qualitatively ("earn commissions" / "earn revenue from transactions") with no published tiers, MDF, deal registration, or annual fee.

**Strongest public disclosure, for contrast:** Stripe publishes explicit dollar-value tier thresholds (Premier tier requires $1M partnership revenue OR $300M payment volume for referral-model platforms) — see [Stripe partner docs](https://docs.stripe.com/partners/platforms). Adyen publishes a clear three-tier structure (Partner / Premier / Premier Plus) with separate tech vs. service tracks — see [Adyen Partner Program](https://www.adyen.com/knowledge-hub/partner-program).

---

## 2. Best Sources Per Vendor

| Vendor | Best source |
|---|---|
| Stripe | [Stripe Partner Ecosystem docs](https://docs.stripe.com/partners/platforms) |
| Adyen | [Adyen Partner Program](https://www.adyen.com/knowledge-hub/partner-program); [Partner Program launch, July 2025](https://www.adyen.com/press-and-media/partner-program-launch) |
| Airwallex | Airwallex official partner program page |
| Wise Platform | [Wise mid-market rate explainer](https://wise.com/gb/blog/mid-market-rate-explained); [December 2025 fee review](https://wise.com/us/blog/december-fee-review-2025) |
| Rapyd | Rapyd Partner Programme page (official) |
| Nium | Nium Payments Partner Program page (official) |
| Currencycloud | Currencycloud "Fuse" partner program page (official, Visa-owned) |
| dLocal | dLocal Partner Program page (official) |
| Payoneer | [Payoneer investor newsroom](https://investor.payoneer.com/news-events/news-releases) (for M&A context); official Partner Program page for program mechanics |
| Corpay | [Corpay Cross-Border](https://www.corpay.com/cross-border) (current program); [Mastercard–Corpay strategic partnership announcement](https://investor.mastercard.com/investor-news/investor-news-details/2025/Mastercard-and-Corpay-Launch-Strategic-Partnership-in-Cross-Border-Payments/default.aspx) (heritage/strategic context) |
| Convera | Convera Partner Program page (official); recent Ripple/stablecoin partnership announcement (March 2026) |

Full per-vendor `sources` arrays with all cited URLs are in [`payments.json`](./payments.json).

---

## 3. SEO-Worthy Insights

1. **0 of 11 major payments partner programs publicly disclose exact revenue-share percentages.** Every vendor researched — from Stripe to Convera — describes revenue share as "custom," "negotiated," or purely qualitative ("earn commissions on volume"). Buyers and prospective partners cannot comparison-shop rev-share terms without direct sales conversations.

2. **Only Wise guarantees a quantified 0% FX markup.** Wise publishes the mid-market rate promise plus a running average fee (~0.53% globally as of December 2025, down from 0.59% a year earlier) ([Wise fee review](https://wise.com/us/blog/december-fee-review-2025); [mid-market rate explainer](https://wise.com/gb/blog/mid-market-rate-explained)). The other 10 vendors either stay silent on FX markup or use unquantified "transparent pricing" language — a clear differentiation angle for content built around "true FX transparency in payments partner programs."

3. **4 of 11 providers added stablecoin-powered rails in the trailing 12 months** — Rapyd (stablecoin launch, September 2025), Nium (Visa stablecoin pilot, November 2025; Circle/USDC partnership, May 2026), Convera (Ripple partnership for stablecoin settlement, March 2026), and Payoneer (Bridge-powered stablecoin capabilities plus an OCC trust bank charter application, February 2026). Stablecoins are moving from experimental to embedded-partner-strategy territory across the sector in the same short window.

4. **Corpay and dLocal are the two vendors with no meaningful embedded-finance capability** (no partner-facing accounts, card issuing, or ledger), positioning them as pure referral/FX-margin plays — in contrast to Adyen, Stripe, Wise Platform, Nium, Rapyd, and Payoneer, which all offer some combination of embedded accounts, card issuing, lending, or BaaS-style ledger infrastructure for partners to build on.

5. **Payoneer's partner program is a moving target mid-acquisition.** Nuvei's announced $2.75B all-cash acquisition of Payoneer ($7.40/share, announced June 15, 2026, expected to close mid-2027) will combine two payment networks into one processing $500B+ in volume across 190+ countries ([Payoneer investor newsroom](https://investor.payoneer.com/news-events/news-releases)). Partners evaluating Payoneer today should factor in likely program consolidation once the deal closes.

6. **Incumbents simplified partner tiers within the same 12-month window.** Stripe consolidated to a 2-tier model (April 2026, [Stripe partner docs](https://docs.stripe.com/partners)) while Adyen launched an enhanced tiered structure (July 2025, [Adyen press release](https://www.adyen.com/press-and-media/partner-program-launch)) — both moves suggest payments platforms are actively re-tuning partner incentive structures rather than leaving them static, useful context for a "state of payments partner programs in 2026" piece.

---

*Notes compiled July 3, 2026. All figures and dates sourced from vendor sites, vendor blogs, and company press/investor releases as cited above and in the full [`payments.json`](./payments.json) dataset.*
