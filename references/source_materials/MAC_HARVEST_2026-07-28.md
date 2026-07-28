# Mac Source Harvest — Scaffolding-Grokapedia

**Date:** 28 July 2026  
**Agent:** Grok (shared Mac crawl with HPWJ + Rigging)  
**Purpose:** Inventory + numeric harvest from local sources; document Aramco CSM-II values as quoted in Anabeeb training deck

---

## 1. What was done

1. Located all scaffold-related binaries on Mac (nebosh/scaf, TVTC pack).  
2. Re-extracted all **66 slides** of Anabeeb basic scaffold deck (text).  
3. Built **Aramco CSM-II secondary extract** from deck claims (full CSM PDF **not** on Mac).  
4. Cross-linked AIMS WAH (already summarised) + master list SWP-019 **New**.  
5. Updated this folder, CHANGELOG, campaign log, master inventory.

---

## 2. Gold-mine paths

| Path | Role |
|------|------|
| `/Users/ab71000372/Desktop/nebosh/scaf/Scaffolding basic training module.pptx` | **Primary seed deck** (66 slides, ~171 MB) |
| `/Users/ab71000372/Desktop/TVTC_Site_Visit_Pack/02_Training_Programs/Other_Programs_Summary/Scaffolding basic training module.pptx` | Duplicate |
| `Documents/aimshse/AIMS-L3-HSE-P-010-Working at Height.docx` | Controlled WAH — summary already in `references/standards/` |
| Master list XLSX (TVTC + Documents) | **AIMS-L3-HSE-SWP-019 Scaffolding Erection, Inspection & Use = New** (file missing) |
| Full Aramco CSM PDF | **NOT FOUND** |

---

## 3. Outputs in this folder

| File | Content |
|------|---------|
| `README.md` | Policy + seed path (pre-existing) |
| `MAC_HARVEST_2026-07-28.md` | This inventory |
| `ANABEEB_Scaffold_Basic_Module1_Numeric_Harvest.md` | All key numbers from 66 slides |
| `ARAMCO_CSM_II_From_Training_Deck.md` | CSM-II values **as quoted by deck** (secondary) |

---

## 4. Multi-AI handoff

- Grok: Mac harvest + numeric cards.  
- Prior session already put many PPTX numbers into MCR Drafting (v0.3–0.4).  
- Claude: truth pass on unit pairs / conflicts (e.g. guardrail 0.950–1.150 m vs Anabeeb WAH 1.1 m ± 8 cm).  
- Human: supply SWP-019 or full Aramco CSM when available.
