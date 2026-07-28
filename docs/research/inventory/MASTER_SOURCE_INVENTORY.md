# Master Source Inventory — Scaffolding Encyclopedia

**Status:** Expanded inventory (campaign max-stack research packs + disk gap hunt)  
**Date:** 28 July 2026

## A. In-Hand Local Sources

| ID | Title | Location | Type | Notes |
|----|-------|----------|------|-------|
| SRC-ANB-PPTX-001 | New Scaffolder’s Basic Training Program Module-1 | `Desktop/nebosh/scaf/Scaffolding basic training module.pptx` + copy note in `references/source_materials/` | Training deck | 66 slides; primary seed for MCR Drafting rows |
| SRC-ANB-PPTX-002 | Same deck (TVTC pack copy) | `Desktop/TVTC_Site_Visit_Pack/02_Training_Programs/Other_Programs_Summary/` | Training deck | Duplicate of seed |
| SRC-ANB-WAH-P010 | AIMS-L3-HSE-P-010 Working at Height | `Desktop/TVTC_Site_Visit_Pack/04_Quality_and_Safety/HSE_Procedures_AIMS/` | Controlled procedure | Extracted 28 Jul 2026 → references/standards summary |
| SRC-ANB-HSE-ML | ANABEEB HSE Procedure Master List Rev01 | same AIMS folder | Register | Lists SWP-019 Scaffolding as **New** (file not present) |
| SRC-ANB-PTW-P007 | AIMS-L2-HSE-P-007 Permit to Work | TVTC pack + Documents/aimshse | Controlled procedure | Summary in references/standards; MCR-066–068 |
| SRC-ANB-PPE-P006 | AIMS-L2-HSE-P-006 PPE | TVTC pack + Documents/aimshse | Controlled procedure | Summary; MCR-069 |
| SRC-ANB-AIMS-BP | AIMS Standard Blue Print 2026 | `Documents/aims/QA/AIMS Standard Blue Print 2026.xlsx` | Document control register | **SSU sheet**: SSU-PRO-001 + FRM.001–009 listed; **binaries not on disk** |
| SRC-SATORP-STORP-001 | FINAL SAFETY ORIENTATION 2025 Rev 02 | `Documents/Training/STORP TRAINING/` (pptx + pdf) | Client orientation | Tag colours + harness; fall clearance example; TA lessons — secondary |
| SRC-LOC-SCAF-001 | Mac harvest inventory | `references/source_materials/MAC_HARVEST_2026-07-28.md` | Path map | 28 Jul 2026 multi-AI crawl |
| SRC-LOC-SCAF-002 | Module-1 numeric harvest card | `references/source_materials/ANABEEB_Scaffold_Basic_Module1_Numeric_Harvest.md` | Extract | Full 66-slide number table |
| SRC-LOC-SCAF-003 | Aramco CSM-II **as quoted** on deck | `references/source_materials/ARAMCO_CSM_II_From_Training_Deck.md` | Secondary client | Duty 1.2/2.4/>2.4 + cantilever 3 m; **primary CSM PDF not on Mac** |
| SRC-LOC-SCAF-004 | MCR exam extract (printable) | `training/MCR_EXAM_EXTRACT.md` | Training aid | High-frequency MCR rows only; watermark DRAFTING |
| SRC-LOC-SCAF-005 | Pre-use inspection checklist | `templates/checklists/Pre_Use_Inspection_Checklist.md` | Template | MCR-mapped draft v0.4 |
| SRC-LOC-SCAF-006 | Appendix F pre-use quick card | `docs/appendices/Appendix_F_Pre_Use_Inspection_Quick_Card.md` | Field card | Bilingual EN/AR pointer to template |
| SRC-LOC-SCAF-007 | Disk gap hunt report | `docs/research/inventory/GAP_HUNT_DISK_2026-07-28.md` | Path + extract log | Confirms SWP-019/SSU missing; STORP + Blueprint finds |

## B. Public / Standards Targets (Not Yet Harvested)

| ID | Document | Access | Priority |
|----|----------|--------|----------|
| SRC-EN-39 | BS EN 39 — steel tubes for tube & coupler scaffolds | Purchase / library | P0 |
| SRC-EN-74 | EN 74 — couplers, spigot pins, baseplates | Purchase / library | P0 |
| SRC-BS-2482 | BS 2482 — timber scaffold boards | Purchase / library | P0 |
| SRC-EN-12811 | BS EN 12811 — temporary works equipment / performance | Purchase / library | P0 |
| SRC-TG20 | NASC TG20 (tube & fitting good practice) | Member / purchase | P0 |
| SRC-OSHA-L | OSHA 1926 Subpart L | Public | P2 comparative |
| SRC-PASMA | Mobile tower guidance (class of practice) | Mixed | P1 mobile towers |

## C. Internal / Client (Human-Gated)

| ID | Document | Status |
|----|----------|--------|
| SRC-ANB-OPS-SCAF | Anabeeb scaffolding procedure | **[INTERNAL GAP]** Dual target: **SWP-019** (HSE New) + **SSU-PRO-001** (Blueprint listed Rev.3 — file missing) |
| SRC-ANB-SSU-FRM | SSU.FRM.001–009 (handover, checklists, register, delivery notes) | **[INTERNAL GAP]** Listed only |
| SRC-ARAMCO-SCAF | Aramco scaffolding requirements | **[INTERNAL GAP]** — partial deck quotes only (SRC-LOC-SCAF-003) |
| SRC-SABIC-SCAF | SABIC scaffolding requirements | **[INTERNAL GAP]** — WAH cites SHEMS 08.09 FP only |
| SRC-SATORP-SCAF | SATORP controlled scaffold standard | **[PARTIAL]** — STORP orientation secondary only (SRC-SATORP-STORP-001) |
| SRC-TVTC | TVTC competency / accreditation context | Partial (TVTC pack exists on Desktop) |

## D. Research Packages

| Package | Focus | State | Key files |
|---------|--------|-------|-----------|
| RP-STD | Standards landscape (EN, BS, TG20, OSHA comparative) | Live | SOURCE_INVENTORY + PUBLIC_HARVEST |
| RP-COMP | Components / couplers | Live | SOURCE_INVENTORY + PUBLIC_HARVEST |
| RP-LOAD | Duty classes / loads | Live | SOURCE_INVENTORY + PUBLIC_HARVEST |
| RP-TIE | Ties & stability | Live | SOURCE_INVENTORY + **PUBLIC_HARVEST** (new) |
| RP-INSP | Inspection & tagging | Live | SOURCE_INVENTORY + **PUBLIC_HARVEST** (new) |
| RP-TRN | Training & competency schemes | Live | **SOURCE_INVENTORY** ATC↔Module-1 map (expanded) |
| RP-CLI | Client matrices | Live | **SOURCE_INVENTORY** Aramco partial + gaps (expanded) |
| RP-INC | Incidents & collapse case studies | Skeleton | SOURCE_INVENTORY stub |

Package root: `docs/research/packages/README.md`

## E. Manufacturer reference stubs

| Path | Role | Manual in-repo? |
|------|------|-----------------|
| `references/manufacturers/Layher_Ringlock/Summary.md` | Ringlock-class proprietary | **No** (name appears on SSU.FRM.009 title in Blueprint) |
| `references/manufacturers/Cuplok/Summary.md` | Captive wedge proprietary | **No** |
| `references/manufacturers/Generic_Tube_Fitting/Summary.md` | EN 39/74 multi-supplier class | **No** (standards-driven) |
| `references/manufacturers/Safetech/Summary.md` | **Not scaffold OEM** — HPWJ PPE pointer only | N/A |

## F. Training pack suite (artefacts)

| Code | Path | Status |
|------|------|--------|
| ATC-SCAF-BASIC … VOC | `training/ATC-SCAF-*/` | 0.2-draft |
| Exam MCR extract | `training/MCR_EXAM_EXTRACT.md` | Drafting watermark |

## Rules

- No source is “adopted” into Visible MCR without citation path + verification.
- PPTX seed ≠ primary standard.
- Manufacturer stubs must not invent proprietary load tables.
- Client partial extracts remain secondary until primary PDF is held.
