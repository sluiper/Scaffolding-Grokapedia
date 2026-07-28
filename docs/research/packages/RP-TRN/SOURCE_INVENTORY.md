# RP-TRN — Training & Competency Source Inventory

**Status:** Live inventory (map ATC packs ↔ Module-1 slides)  
**Date:** 28 July 2026  
**Parent:** `docs/research/inventory/MASTER_SOURCE_INVENTORY.md`  
**SSOT for numbers:** `MASTER_CONTROL_REGISTER.md` (all Drafting)  
**Rule:** Cite MCR-IDs in exams; do not hard-code unverified constants.

---

## 1. Primary training sources

| Source ID | Document | Location | Harvest status |
|-----------|----------|----------|----------------|
| SRC-ANB-PPTX-001 | New Scaffolder’s Basic Training Program Module-1 (66 slides) | Desktop `nebosh/scaf/…pptx` | **Harvested** — numeric card + chapter map |
| SRC-LOC-SCAF-002 | Module-1 numeric harvest | `references/source_materials/ANABEEB_Scaffold_Basic_Module1_Numeric_Harvest.md` | Live |
| SRC-ANB-WAH-P010 | AIMS-L3-HSE-P-010 Working at Height | `references/standards/…Summary.md` | Live extract |
| SRC-ANB-HSE-ML | HSE Procedure Master List Rev01 | Desktop TVTC pack | Lists SWP-019 **New** (file missing) |
| — | ATC-SCAF pack suite | `training/ATC-SCAF-*/` | **0.2-draft** six packs |
| — | MCR exam extract sheet | `training/MCR_EXAM_EXTRACT.md` | Drafting printable |

---

## 2. Module-1 slide map → encyclopedia / ATC themes

| Slides | Deck topic | Encyclopedia | ATC focus packs |
|--------|------------|--------------|-----------------|
| 01–04 | Title / TOC | Ch01 | BASIC day 1 intro |
| 05–08 | Intro, safety regs, PPE | Ch03 | BASIC, AWARE |
| 09–10 | Components overview, hand tools | Ch05 | BASIC |
| 11–13 | Tubes, base plate/jack, sole boards | Ch05, Ch10 | BASIC |
| 14–24 | Couplers (double, swivel, putlog, board retain, sleeve, girder, joint pin, EN74 marks) | Ch06 | BASIC, INSP, ADV |
| 20 | Boards BS 2482 | Ch05 | BASIC |
| 25–27 | Double standards sole, ladder beam, metal ladders | Ch10, Ch14 | BASIC, INSP |
| 28–35 | Terminology (kicker, ledger, brace angle, guardrails, sole) | Ch07 | BASIC |
| 36–37 | Scaffold systems (T&F, Cuplok, Ringlock/Layher) | Ch08 | BASIC, ADV |
| 38 | Duty loads TG20 + Aramco CSM-II | Ch09, App A | BASIC, SUP, INSP |
| 39–40 | Free-standing / mobile towers | Ch13, App D | BASIC, INSP |
| 41–42 | Independent scaffold + façade bracing patterns | Ch12–13 | BASIC, ADV |
| 43–44 | Hung/trapeze; cantilever + raker | Ch13 | ADV, BASIC intro |
| 45–47 | Scaffold ties (box, lip, through, drill) | Ch11, App I | BASIC, ADV, INSP |
| 48 | Fall protection measures | Ch16 | BASIC, AWARE |
| 49–52 | Access/egress, joints, ladders detail, excavations title | Ch14 | BASIC, INSP |
| 53–54 | Material lifting / gin wheel | Ch15, App H | BASIC, SUP |
| 55–60 | Bad practices (bracing, ties, ladder beam splice, foundations) | Ch18, Ch19 | BASIC, INSP, VOC |
| 61–64 | User instructions & scaff-tags | Ch17, App E | **All packs**, esp. AWARE |
| 65–66 | WAH instructions / harness | Ch03, Ch16 | BASIC, AWARE, VOC |

---

## 3. ATC pack → Module-1 / MCR coverage matrix

| Pack | Role | Module-1 slide bands (primary) | Core MCR clusters |
|------|------|--------------------------------|-------------------|
| **ATC-SCAF-BASIC** | New scaffolder erect/modify/dismantle under supervision | Full 05–66 (teaching spine) | 001–034, 015–023, 028–031, 038–042, 046–063 |
| **ATC-SCAF-ADV** | Complex / hung / cantilever / engineering gate awareness | 43–44, 26, 45–47, 38, 58–59 | 040, 045, 058–059, 012, 034, 042, 015/054 |
| **ATC-SCAF-INSP** | Inspect, tag, reject bad practice | 55–64, 11–27, 38–42, 48 | 028–029, 007–014, 015–021, 055–063 |
| **ATC-SCAF-SUP** | Planning, duty class, gin wheel, SIMOPS awareness | 06–08, 38, 53–54, 61–64 | 015/054, 031, 036, 044–045, 051 |
| **ATC-SCAF-AWARE** | End-user only — tags, never-rules, ladder basics | 61–64, 48, 27/51, duty awareness | 028–029, 046–049, 060–063, 023, 015 |
| **ATC-SCAF-VOC** | Reassess critical skills | High-risk subset of BASIC + tags | 028–029, 008/010 use-rules, 017–019, 060–062 |

---

## 4. Exam artefact rule

| Artefact | Path | Policy |
|----------|------|--------|
| Theory exams / quizzes | `training/ATC-SCAF-*/04_*` or `03_*` | Open MCR extract preferred |
| Printable MCR extract | `training/MCR_EXAM_EXTRACT.md` | Values **only** from MCR; watermark **DRAFTING — not Visible** |
| Practical checklists | `training/ATC-SCAF-*/03_*` | Map critical items to MCR-IDs |

**Do not examine** a single sleeve SWL number (MCR-011 unresolved). Test stagger + correct use instead.

---

## 5. Competency scheme gaps

| Gap | Description | Status |
|-----|-------------|--------|
| GAP-005 | CISRS / TVTC formal mapping | OPEN |
| GAP-001 | SWP-019 controlled training/forms | OPEN |
| — | Zero MCR Visible → packs remain pilot-only | Honest state |

---

## 6. Cross-links

- Framework: `docs/20_Competency_Framework_Training_and_Assessment.md`  
- Training index: `training/README.md`  
- Seed numeric card: `references/source_materials/ANABEEB_Scaffold_Basic_Module1_Numeric_Harvest.md`
