# Underwriting — v0.2 (demo prototype)

A clickable, self-contained prototype of the Uncapped back-office **underwriting workspace**,
built for the *lending-as-a-service* partner demo. Forked and evolved from the internal
back-office deal-view prototype.

- **`index.html`** — the whole prototype (single file, no build step). Open it directly or serve it statically.
- **`DEMO-SCRIPT.md`** — a 1-page click-path for presenting it.

## What's inside
- **Portfolio (helicopter) view** — MI strip + "Deals in underwriting" table.
- **Deal workspace** — sticky header + point-in-time data lock/version control, a step spine
  (Overview → Categorisation → Background → RAG → Scorecards → Forecast → Decision), and a
  tabbed right rail (Review / Notes / History).
- **Step 1 (Overview)** built out: Deal-at-a-glance tiles, About the company (AI summary,
  products, linked companies), Data coverage & checks, lending relationship, and a
  one-view summary of multi-series charts (click any chart to open the gallery).
- Three fictional demo cases (Approve / borderline / Reject).

> Prototype only — all data is illustrative/fictional. Not connected to any live system.

## Run / deploy
Static site — `index.html` at the root. Deploy on Vercel (import the repo, no config needed)
or open the file locally.
