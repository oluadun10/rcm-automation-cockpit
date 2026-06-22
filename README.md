# RCM Automation Prioritization Cockpit

An interactive model for prioritizing revenue cycle automation opportunities — adjust the scoring weights and the pipeline re-ranks in real time.

**Live demo:** `https://<your-username>.github.io/rcm-automation-cockpit/`

---

## What this is

Pre-work for an Automation Product Owner conversation with Health Prime. It's a working draft of two deliverables: an automation intake & prioritization framework, and a scored pipeline of opportunities across the RCM lifecycle (patient access, coding & charge, claims, denials & appeals, payment posting, A/R, client services). The goal is to prioritize the next wave of opportunities flowing into **Prime Flow**, sequenced by value, feasibility, and reuse across clients rather than one client at a time.

> **Note on the numbers.** Every volume, handle time, and dollar figure is an illustrative placeholder built to demonstrate the model — not Health Prime data. The point is the method and the prioritization logic. Swap the assumptions for real operational figures and the whole model re-derives and re-ranks itself.

## How to use it

- **Scoring weights** — move the six sliders to shift emphasis across the criteria; the ranking and the chart update instantly.
- **ROI assumptions** — change the loaded hourly cost or the realization haircut to re-cost every opportunity.
- **Filters** — narrow the view by RCM function or delivery wave.
- **Value vs. effort** — vertical position is the live priority score, bubble size is annual value, and the current top 5 are highlighted.

## The scoring model

Each opportunity is scored 1–5 on six criteria. A weighted average (×20) produces a 0–100 priority score; weights normalize automatically.

| Criterion | Default weight |
| --- | --- |
| Business value / ROI | 25% |
| Volume & frequency | 15% |
| Feasibility / readiness | 20% |
| Process standardization | 15% |
| Strategic alignment | 15% |
| Risk & compliance (inverse) | 10% |

Delivery waves reflect sequencing and dependencies, not score alone — a high-scoring item can still sit in a later wave when it depends on earlier foundations or build capacity.

## Run it locally

No build step and no dependencies. Open `index.html` in any browser, or host it with GitHub Pages (Settings → Pages → deploy from the `main` branch, root folder).

---

*Prepared as candidate pre-work · illustrative model.*
