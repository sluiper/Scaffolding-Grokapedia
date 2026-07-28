# RP-TIE — Ties & Stability Public Harvest

**Date:** 28 July 2026  
**Package:** RP-TIE  
**Status:** Secondary / seed harvest only — **no primary TG20 / CSM tie tables in-repo**  
**Parent inventory:** `SOURCE_INVENTORY.md`

---

## 1. Purpose of ties (seed + industry consensus)

Ties connect scaffold to a permanent structure so the scaffold cannot move away or sway excessively. Tie duty (tension / push-pull) depends on spacing, sheeting, wind, and configuration. [CITATION: PPTX-M1 s45–s47; industry practice]

**GAP-015:** Module-1 is **qualitative only** — no kN per-tie table. Do not invent numeric tie loads for MCR Visible or exams.

---

## 2. Tie types — Module-1 (primary seed for encyclopedia language)

| Type | Description (deck) | Slide |
|------|--------------------|-------|
| **Box tie** | Tubes & couplers tightly fixed around **all sides** of column or I-beam | s46 |
| **Lip tie** | L-shaped arrangement when full box not possible | s46–s47 (family of incomplete box) |
| **Through tie** | Tie tubes through window / opening | s46–s47 |
| **Drill / cast-in tie** | Anchors drilled into building or cast in | s47 |

Connection of tie tubes to posts/ledgers: **right-angle (double) couplers** for tube-to-tube. [CITATION: PPTX-M1 s46]

**MCR impact:** Supports Chapter 11 / Appendix I narrative; no new numeric MCR rows.

---

## 3. Connection quality (high-confidence operational controls)

| Rule | Source | MCR |
|------|--------|-----|
| Girder couplers always **in pairs** | PPTX-M1 s19, s58 | MCR-012 |
| Girder pairs + **check (safety) couplers** | PPTX-M1 s58 | MCR-042 |
| **Do not** use double couplers on structural steel sections | PPTX-M1 s58 | MCR-034 |
| Brace / structural tubes near **node points** | PPTX-M1 s57 | MCR-016 family |

**Decision (Drafting):** Pair + check-coupler discipline stays operational control even without primary load tables.

---

## 4. Related stability geometry (not “tie type” but same package)

| Claim | Value | Source | MCR |
|-------|-------|--------|-----|
| Brace angle long/trans | **35°–55°** from horizontal | PPTX-M1 s33, s57 | MCR-016 |
| Face bracing density (independent) | Both ends + every **5th** standard line | PPTX-M1 s41 | MCR-020 |
| Ledger bracing | Alternate lines | PPTX-M1 s41 | MCR-020 |
| External free-standing H/B | ≤ **3 ×** min base | PPTX-M1 s39 | MCR-017 |
| Internal free-standing H/B | ≤ **4 ×** min base | PPTX-M1 s39 | MCR-018 |
| Mobile tower H/B | ≤ **4 ×** min base | PPTX-M1 s40 | MCR-019 |
| Plan braces free-standing | Top, kicker, every **third** lift; all four sides | PPTX-M1 s39 | MCR-057 |
| Underhung trapeze assist | ≤ **600 mm** from ledger | PPTX-M1 s43 | MCR-040 |
| Cantilever without design | ≤ **3 m** (deck cites Aramco CSM-II) | PPTX-M1 s44 | MCR-058 |
| Raker angle / integrity | **65°–75°**; single tube **no splice** | PPTX-M1 s44 | MCR-032 / 059 |

---

## 5. Public / secondary targets not yet harvested

| Target | Why needed | Status |
|--------|------------|--------|
| NASC TG20 tie frequency / wind tables | Quantitative façade ties | **Not in-repo** (GAP-007 / GAP-015) |
| Manufacturer Layher / Cuplok tie schedules | Proprietary system rules | **No manuals** (GAP-022) |
| Aramco CSM primary tie spacing | Client override | **Not on Mac** (GAP-002) |
| EN 12811 / national annex wind | Design gate | Secondary only |

Trade blogs and CISRS quiz snippets sometimes state “~300 mm to node” for brace/tie connections — **not adopted into MCR** as a number until primary TG20/NASC text is attached (GAP catalog note).

---

## 6. Operational synthesis (not new MCR numbers)

1. Do not remove ties without scaffolders + temporary stability plan.  
2. Prefer ties near node points.  
3. Damaged anchors / missing ties → stop use / red-tag pathway as appropriate.  
4. Engineered scaffolds: design tie schedule **overrides** training generic.  

[SYNTHESIS — aligns Ch11 §5]

---

## 7. Harvest log

| Date | Agent | Note |
|------|-------|------|
| 28 Jul 2026 | Grok | Seed types + coupler rules + stability ratios from PPTX full extract; no invented tie kN |
| Pending | Human / primary PDF | TG20 + CSM tie matrices |
