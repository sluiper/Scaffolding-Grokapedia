# RP-STD — Public Standards Harvest

**Campaign:** draft/campaign-max-stack-v0.2  
**Date:** 28 July 2026  
**Caveat:** Full paid texts of EN 39 / EN 74 / EN 12811 / BS 2482 / TG20 were **not** purchased. Values below are from manufacturer/trade secondary sources that consistently restate the standard tables. Status remains **secondary citation** until primary PDF is in hand.

---

## 1. EN 39 — Steel tubes for tube & coupler scaffolds

| Claim | Value | Secondary sources | Confidence |
|-------|-------|-------------------|------------|
| Outside diameter | **48.3 mm** | Uniasen EN39 page; industry consensus BS 1139/EN39 | High |
| Wall thickness Type 3 | **3.2 mm** | Uniasen; trade blogs | High |
| Wall thickness Type 4 | **4.0 mm** | Uniasen; trade blogs | High |
| Steel grade example | S235GT, ReH min **235 MPa** | Uniasen mechanical table | Medium-High |
| Common supply length | **6 m** (also 6.4 m / cut lengths) | Trade supply sheets | Medium |

**Vs PPTX-M1 s11:** Matches OD 48.3; T&F 4 mm and Cuplok 3.2 mm align with Type 4 / Type 3 split. Cuplok tube cited EN 10219 in deck — system tubes may be hollow-section supply; still OD-compatible with 48.3 fittings.  
**MCR impact:** Supports MCR-001/002 dimensions (not Anabeeb-unique).

---

## 2. EN 74-1 — Couplers

| Claim | Value | Secondary sources | Confidence |
|-------|-------|-------------------|------------|
| Right-angle Class A slip | **~6.1 kN** | Trad UK / SSS product pages | Medium-High |
| Right-angle Class B slip | **9.1 kN** | Trad UK; TP-Scaffold; multiple trade pages | Medium-High |
| Swivel Class B slip (cited) | **~9.1 kN** (axial slip test class) | Trade restatements | Medium |

**Conflict resolution (PPTX 9.4 vs 9.1):**  
Secondary trade sources **converge on 9.1 kN** for EN 74-1 Class B right-angle slip resistance. Deck value **9.4 kN** treated as **training-deck rounding/error**.  
**Working rule for encyclopedia:** Prefer **9.1 kN Class B** with tag `[CITATION secondary → verify primary EN 74-1 table]`.  
**MCR impact:** MCR-008/009 → 9.1 kN; PPTX 9.4 demoted to historical note.

**Still open (need primary EN 74-1):**  
- Exact putlog/single SWL (deck 0.53 kN)  
- Exact sleeve Class B values (deck conflicts 3.0 kN / 0.59 kN/m vs 0.53 kN)  
- Failure mode definitions (slip vs pull-out vs bending)

---

## 3. EN 12811-1 — Temporary works equipment — Performance requirements

| Load class | UDL q1 (kN/m²) | Typical use (secondary) |
|------------|----------------|-------------------------|
| 1 | **0.75** | Inspection / very light |
| 2 | **1.5** | Painting, cleaning, light tools |
| 3 | **2.0** | General facade / plastering |
| 4 | **3.0** | Heavy materials / masonry |
| 5 | **4.5** | Heavier construction |
| 6 | **6.0** | Very heavy |

Sources: Scafom-Rux blog (EN 12811-1:2003 restatement); multiple EU trade calculators.  
UK TG20 commonly markets Classes 1–4 matching 0.75 / 1.5 / 2.0 / 3.0 kN/m².

**PPTX unit fix:** Deck “N sqm” is almost certainly **kN/m²** (Class 1–4 only).  
**MCR impact:** MCR-015 units → kN/m²; add classes 5–6 as EN row notes.

---

## 4. Guardrails / edge protection (UK WAH Regs + EN)

| Claim | Value | Source class |
|-------|-------|--------------|
| UK WAH Regs 2005 Sch.2 top rail (construction) | **≥ 950 mm** | Secondary legal guidance sites |
| Intermediate gap | **≤ 470 mm** | Same |
| EN 12811 principal guardrail (trade restatement) | often **≥ 1.0 m** | Secondary |

**Anabeeb AIMS-L3-HSE-P-010** (controlled internal): top edge **1.1 m ± 8 cm** (1.02–1.18 m); midrail **≥ 53 cm**; strengths 890 N / 666 N.  
**Hierarchy:** Anabeeb WAH procedure governs Anabeeb sites for fall protection geometry; PPTX 0.950–1.150 remains training band overlapping UK min + Anabeeb band — **reconcile in MCR-021**.

---

## 5. BS 2482 — Timber scaffold boards

| Claim | Value | Confidence |
|-------|-------|------------|
| Nominal size | **38 mm × 225 mm** (also 63 mm thick grade) | High (trade) |
| Support span (38 mm, common) | often **1.2 m** centres (grade-dependent); some grades to 1.5 m | Medium — need BS 2482 text |

---

## 6. Free-standing / mobile height ratios

| Claim | Value | Source class |
|-------|-------|--------------|
| OSHA free-standing | height ≤ **4 ×** least base | OSHA interpretation letter (public) |
| TG20 tower (secondary) | exterior often **3:1**; interior **4:1** restated | Scribd TG20 user guide snippets |
| PPTX-M1 | external free-standing **3×**; internal **4×**; mobile **4×** | Seed deck |

**MCR-017–019:** Keep PPTX ratios as Drafting pending TG20 primary; note OSHA 4:1 as comparative US rule for mobile free-standing.

---

## 7. Ladder access

| Claim | Value | Alignment |
|-------|-------|-----------|
| Slope 4:1 (~75°) | PPTX + Anabeeb WAH + industry | Consistent |
| Extend ≥ 1.0 m above landing | PPTX + Anabeeb WAH | Consistent |

---

## Harvest log

| Package file | Status |
|--------------|--------|
| RP-STD/PUBLIC_HARVEST.md | This file |
| RP-COMP (next) | Coupler SWL focus |
| RP-LOAD (next) | Duty classes focus |
| Primary PDFs | **Not in repo** — purchase/library still GAP-007 |
