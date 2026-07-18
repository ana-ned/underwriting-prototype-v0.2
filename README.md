# Underwriting — v0.2 (demo prototype)

A clickable, self-contained prototype of the Uncapped back-office **underwriting workspace**,
built for the *lending-as-a-service* partner demo. Forked and evolved from the internal
back-office deal-view prototype.

- **`index.html`** — the whole prototype (single file, no build step). Open it directly or serve it statically.
- **`DEMO-SCRIPT.md`** — a 1-page click-path for presenting it.

## What's inside
- **Portfolio (helicopter) view** — MI strip (value-by-rating donut with legend, sparkline
  trend cards for total-in-underwriting / weighted amount / deals-at-risk) + filter tabs and a
  "Deals in underwriting" table (org logos, rating, suggested decision, time-in-UW bars,
  intervention tags).
- **Deal workspace** — sticky header + point-in-time data lock/version control, an 8-step
  spine (Overview → Data checks → Background → Categorisation → RAG checks → Scorecards →
  Forecast → Decision), and a movable/resizable **Underwriter notes** window + History popup.
- **Overview** built out as two sections: a **Recommendation** card (recommended amount,
  rationale, positive factors, risks) and a **Company overview** (KPI tiles + an AI company
  summary: business background · web search · Uncapped history), plus lending relationship and
  a one-view summary of multi-series charts (click any chart to open the gallery).
- **Data checks** tab holds the full non-financial hygiene checklist (moved off Overview).
- Eight fictional demo cases spanning ratings A–E (Approve / Request info / Reject).

> Prototype only — all data is illustrative/fictional. Not connected to any live system.

## Run / deploy
Static site — `index.html` at the root. Deploy on Vercel (import the repo, no config needed)
or open the file locally.
