# Underwriting v0.2 — demo script (partner / lending-as-a-service)

**Audience:** a prospective lender (partner bank) evaluating Uncapped as a lending platform.
**Goal:** show the *art of the possible* — that underwriting runs on real, ownable technology, not spreadsheets.
**Framing (say this up front):** *"This is a working prototype of the platform our team is building now — first release targeted for October. It's grounded in our live back-office."*

Open the deployed link. Full-screen the browser.

---

## Beat 1 — "This is a platform" (Helicopter view · 60 sec)
Land on the **Portfolio** screen.
- **Top strip:** deal value by rating, total in underwriting today, weighted pipeline (likelihood × amount), and deals-at-risk.
  > *"A lender logs in and immediately sees their whole book in underwriting — value at each rating, what's likely to close, and what needs attention today."*
- Point at the **"Lender: Meridian Capital"** switcher (top-left) and the **Deals in Underwriting** table.
  > *"Each lender sees only the deals assigned to them. Every row is a live application — rating, pre-offer value, the model's suggested decision, max amount, recommended product, and whether it needs intervention."*
- Note the **⚠ Review** flag on Harborline and Vertex.

## Beat 2 — A clean approval (Northwind Traders · 90 sec)
Click **Northwind Traders Co.** (rating B, Approve).
- **Sticky header** — rating, pre-offer value, suggested decision, max amount, product, **Make decision**.
  > *"Everything the decision hangs on stays pinned at the top, whatever tab you're in."*
- **Overview tab** — company summary, **data-hygiene checks all green**, lending relationship + principal chart, and *all the summary charts in one view*.
  > *"The underwriter gets the whole picture at a glance."* **Double-click a chart** → it expands. *"Fully interactive — nothing is a static screenshot."*
- **RAG tab** — expand a green row to show the backing charts. *"Checks are pre-computed but the underwriter can override any of them."*

## Beat 3 — The interactive model (Forecast tab · 90 sec) — the wow
Still on Northwind → **Forecast**.
- Left: **sticky cashflow P&L** (L12M vs N12M).
- **Revenue forecast** — click **Optimistic → Pessimistic**.
  > *"Change one assumption and the forecast recomputes live — actuals stay fixed, only the forward view moves. This is the interactivity a spreadsheet can never give you."*
- **Other debt** → **Edit schedule** on a facility → change a couple of cells (they turn amber) → note **Revert all**.
- **Open full model** → *"and when they need the detail, the entire cashflow model is right here — history locked, forecast editable."*

## Beat 4 — Where the platform earns its keep (Vertex Outdoor · 75 sec)
Back to Portfolio → open **Vertex Outdoor Supply** (rating E, Reject).
- **Overview** — hygiene checks show **red**: storefront owned by a different entity, inter-client match, NSF events.
- **RAG** — **Debt is red**: *"£310k of undisclosed debt drawn through a linked entity in the last 60 days."* Behaviour red (Amazon AT_RISK).
- **Categorisation tab** — click **"Transactions to review"** → the triage view surfaces the risky ones (a £60k wire, ATM deposits, an intra-company transfer). Re-categorise one → it clears.
  > *"The platform bubbles the risky money to the top instead of the underwriter hunting for it."*

## Beat 5 — Close the loop (Make decision · 30 sec)
On any deal, click **Make decision** → the offer confirmation modal → **Confirm decision**.
> *"Suggested offer, editable, decision recorded for sign-off. In future this can come straight from the decision engine — and a lender can consume all of it via API."*

---

## If asked "is this live?"
> *"This is a functional prototype with representative data — the build is underway with the risk and engineering teams. What you're seeing is the target experience, grounded in the back-office we run today."*

## Guardrails
- All data on screen is **illustrative / fictional** — no real customer figures.
- Don't promise dates beyond "targeting October for the first release."
- Three demo cases: **Northwind** (clean approve) · **Harborline** (borderline, needs review) · **Vertex** (reject, undisclosed debt).
