## research-packs-and-stubs – 28 July 2026 (draft/campaign-max-stack-v0.2)

### Research packages
- **RP-TIE/PUBLIC_HARVEST.md** — tie types, coupler connection rules, stability ratios; GAP-015 no invented kN.
- **RP-INSP/PUBLIC_HARVEST.md** — WAH + PPTX tags/pre-use; GAP-004 reinspection still open.
- **RP-TRN/SOURCE_INVENTORY.md** — ATC-SCAF packs mapped to Module-1 slide bands + MCR clusters.
- **RP-CLI/SOURCE_INVENTORY.md** — Aramco CSM-II partial from PPTX + primary CSM gap list.
- RP-TIE / RP-INSP SOURCE_INVENTORY expanded from stubs.

### Manufacturer stubs (Summary.md only; no manuals in-repo)
- `references/manufacturers/Layher_Ringlock/`
- `references/manufacturers/Cuplok/`
- `references/manufacturers/Generic_Tube_Fitting/`
- `references/manufacturers/Safetech/` (not scaffold OEM — HPWJ PPE pointer)

### Training / field cards
- `training/MCR_EXAM_EXTRACT.md` — high-frequency MCR rows for ATC exams; watermark **DRAFTING — not Visible**.
- `docs/appendices/Appendix_F_Pre_Use_Inspection_Quick_Card.md` — bilingual EN/AR pointer to pre-use checklist template.

### Inventory
- `docs/research/inventory/MASTER_SOURCE_INVENTORY.md` updated (packages, manufacturers, exam extract).

### Not done
- Still **0 MCR Visible**; no primary EN/TG20/CSM PDFs; SWP-019 still missing.

---

## draft/campaign-max-stack-v0.2 — Slice thin-section deepen – 28 July 2026

### Priority thin-section expansions (v0.5 structure)
- `docs/07_Scaffold_Terminology.md` — EN/AR bilingual top-20 term table; full glossary; system-language caution; guardrail language conflict; worked disambiguation.
- `docs/11_Scaffold_Ties.md` — good/bad connection tables; inspection checklist T1–T10; worked I-beam example; failure modes; no invented tie kN (GAP-015).
- `docs/12_Bracing_Arrangements.md` — independent vs free-stand/mobile matrix; face-brace line worked example; plan-brace rules; bad-practice family.
- `docs/08_Scaffold_Types_and_Proprietary_Systems.md` — full markdown selection flowchart steps [1]–[7]; compact decision table; worked mobile H/B pick.
- `docs/27_Maintenance_Storage_and_Material_Control.md` — pre-use material reject criteria R1–R22 mapped to MCR; yard worked example.
- `docs/28_Emergency_Response.md` — roles matrix (workers through engineer/client); scenario table; post-event structural path; partial-collapse roles example.

### Constraints observed
- MCR-first; existing MCR IDs only; [CITATION]/[DERIVED]/[SYNTHESIS] tags.
- No fake primary-standard clause numbers; no Drafting→Visible; no self-grading language.
- Still **0 Visible** MCR rows; Claude verify skipped per campaign direction.

---

## v0.5.1-draft — 28 July 2026 — Part 5 deepen (local)

### Chapters 21–28
Deepened to production draft v0.6 structure (MCR mapping, verification log, honest gaps):
- 21 Regulatory matrix, 22 Engineering gate, 23 Weather/SIMOPS
- 24 Incident library (composites only), 25 Human factors, 26 Lessons learned
- 27 Material control, 28 Emergency response

### Still
- **0 Visible** MCR rows
- No Claude Verification Report
- GAP-001 SWP-019, GAP-006 incidents, GAP-009 wind still open

---

## mac-goldmine-harvest – 28 July 2026 (multi-AI, local)

### Source materials pack
- `references/source_materials/MAC_HARVEST_2026-07-28.md` — Mac inventory.
- `ANABEEB_Scaffold_Basic_Module1_Numeric_Harvest.md` — full numeric card from 66-slide seed deck.
- **`ARAMCO_CSM_II_From_Training_Deck.md`** — Aramco CSM-II duty ratings (1.2 / 2.4 / >2.4 kN/m²) + cantilever **3 m** design gate **as quoted on deck**; full CSM PDF still not on Mac.
- Logged coupler SWL conflict (9.4 vs 9.1 kN) and N vs kN/m² unit caution.
- No new Visible MCR; harvest supports existing Drafting stack.

### Process
- Campaign log + MASTER_SOURCE_INVENTORY updated.

---

## family-standard-alignment – 28 July 2026 (local)

### Process parity
- Linked `AGENTS.md` / `PROCESS.md` / `FAMILY.md` to `~/projects/GROKAPEDIA_STANDARD.md` v1.0.
- Added `docs/research/inventory/SECTION_HEALTH_SHEET.md` and `MCR_RESTATEMENT_MAP.md`.
- Honest structure note: Ch21–28 are thin/early drafts (filenames locked).
- README maturity **L2**; training gate reaffirmed (0 Visible).

### Not done
- Claude Verification Report; SWP-019; primary EN/TG20 PDFs; any Visible promotion.

---

# CHANGELOG

## draft/campaign-max-stack-v0.2 (v0.4 no-Claude continue) – 28 July 2026

### Full chapter set + AWARE pack
- **Ch04–12, 15–16, 19–20** production drafts (completes Ch01–20 operational set).
- **ATC-SCAF-AWARE 0.2-draft:** course spec, trainer guide, handout, 20-item quiz+key, attendance.
- Appendices **B, C, I** draft cards; pre-use checklist v0.4.
- Human directed: continue without Claude verification. Still **0 MCR Visible** (honest).
- Encyclopedia version **v0.4.0-draft**.

## draft/campaign-max-stack-v0.2 (continue) – 28 July 2026

### Gap hunt + production stack
- Full 66-slide PPTX re-extract; closed GAP-008 (trapeze 600 mm); harvested Aramco CSM-II duty, ladder openings, casters, cantilever 3 m, user never-rules.
- MCR **v0.3.0-draft** (~66 Drafting rows): MCR-054–065; MCR-023/028/040 updates.
- Production drafts: Ch02, Ch03, Ch05, Ch06, Ch13, Ch14, Ch17, Ch18.
- Draft field cards: Appendices A, D, E, G, H.
- Client matrix stub `references/standards/21_…`; living `GAP_CATALOG.md`.
- Still **0 Visible** promotions.

## draft/campaign-max-stack-v0.2 – 28 July 2026 (not yet merged to main)

### 1 — Internal harvest
- Extracted Anabeeb **AIMS-L3-HSE-P-010 Working at Height** → `references/standards/Anabeeb_AIMS_L3_HSE_P010_Working_at_Height_Summary.md`.
- Confirmed master-list planned **AIMS-L3-HSE-SWP-019 Scaffolding Erection, Inspection & Use** is **New / file missing** (GAP-001).
- Updated `INTERNAL_GAP_REGISTER.md` (GAP-001a closed for extract; partial tag/WAH closes).

### 2 — Public standards harvest
- `RP-STD/PUBLIC_HARVEST.md` — EN 39 dimensions, EN 74 Class B 9.1 kN secondary, EN 12811 classes, boards, ratios.
- `RP-COMP/PUBLIC_HARVEST.md` — coupler conflict analysis.
- `RP-LOAD/PUBLIC_HARVEST.md` — duty classes + unit fix.

### 3 — T1 truth pass
- `docs/audit/campaign/T1_TRUTH_PASS_2026-07-28.md`.
- MCR → **v0.2.0-draft**: 9.1 kN Class B preference; duty **kN/m²**; Anabeeb guardrail **MCR-021** vs training **MCR-021a**; new WAH rows **MCR-046–053**.
- **Zero Visible promotions.**

### 4 — Chapter 01 production draft
- Full `docs/01_Introduction_Scope_Purpose_How_to_Use.md` (hierarchy, how-to-use, worked conflict example, Verification Log, honest gaps).

### 5 — Remote
- GitHub remote setup (see commit / push notes).

## v0.1.0-scaffold – 28 July 2026 (Local scaffold only)

### Slice A — Project scaffold (local first)
- Created `~/projects/Scaffolding-Grokapedia` as a sibling of HPWJ-Grokapedia.
- Locked process files: `AGENTS.md`, `WORKFLOW.md`, `PROCESS.md`.
- Seeded encyclopedia structure, MCR Drafting rows from Module-1, training stubs, templates, research inventories.
- Local git init only.

**This changelog prioritises truth over presentation.**

## draft/campaign-max-stack-v0.2 (v0.5 no-Claude) – 28 July 2026

### Full training suite + supporting sections
- **ATC-SCAF-BASIC** full pack: trainer guide, workbook, 25-item practical, 40-item exam+key, PPE list.
- **INSP / SUP / VOC / ADV** packs expanded to 0.2-draft (exams + practicals).
- **Sections 21–28** production drafts (client matrix pointer, design gate, weather/SIMOPS, 10 composite cases, HF, LL, maintenance, emergency).
- Encyclopedia **v0.5.0-draft**. Still **0 MCR Visible**.
