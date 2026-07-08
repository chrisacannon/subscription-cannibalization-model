# Subscription Cannibalization Model

An interactive simulation of the strategic tension between subscription growth objectives and transactional revenue protection in a global hardware supplies portfolio.

**Live site:** [chrisacannon.github.io/subscription-cannibalization-model](https://chrisacannon.github.io/subscription-cannibalization-model)

---

## What This Models

As a subscription ink service expanded into developed markets, the subscription business team and the traditional supplies portfolio team were both targeting the same printer owners — but with fundamentally different incentives about which customers to pursue and how aggressively.

This project builds the analytical framework used to quantify that tension: a 10×10 customer decile matrix mapping usage behavior against OEM loyalty, combined with a channel-economics revenue model showing the annual HP revenue impact of converting each customer segment from transactional to subscription at 2019 plan pricing.

The central finding: at 2019 pricing, converting any customer segment to subscription represented a net revenue step-down relative to the transactional model. The customers the subscription team most wanted to convert — high-usage, high-loyalty customers — were the ones whose conversion was most costly. The free tier elimination and subsequent plan price increases were prerequisites for a viable subscription targeting strategy, not optional adjustments.

---

## Framework

**The Decile Matrix** maps the customer base across two dimensions:
- **Usage** (vertical) — monthly ink consumption from near-zero to 280+ pages/month
- **OEM Loyalty** (horizontal) — percentage of cartridges that are genuine HP vs. third-party or refilled

Each cell shows the annual HP revenue gap between transactional and subscription for that customer segment. Green = subscription wins on HP revenue; red = transactional wins (cannibalization risk).

**The Revenue Analysis** quantifies the gap across usage deciles using HP's 65% channel share of trade retail revenue as the break-even benchmark for subscription plan pricing.

---

## Key Findings

- At 2019 pricing, subscription plans were priced below HP's channel-adjusted trade revenue equivalent for usage deciles D8–D10 — the heaviest users and highest-value transactional customers
- The free 15-page plan created a $0 revenue floor that made any paid plan feel expensive and suppressed meaningful attach rate data
- D10 customers (280+ pages/month on entry-class hardware) represent a structural mismatch — the revenue gap cannot be closed with plan price increases alone; the right solution involves product routing to a higher-tier platform
- Post-resolution plan price increases closed the revenue gap at D8–D9; D10 remains unresolved

---

## Simulation Disclosure

All customer data, pricing figures, and revenue calculations are illustrative and have been abstracted from actual HP Inc. data to protect confidentiality. The analytical framework, channel economics, and strategic logic reflect actual work performed. This is not HP Inc. proprietary information and does not represent actual HP financial results.

---

## Files

- `index.html` — Full interactive simulation (self-contained, no dependencies beyond CDN)
