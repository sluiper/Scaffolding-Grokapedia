# Campaign Log — Scaffolding-Grokapedia

## Campaign 2 — Mac gold-mine harvest (28 July 2026)

**Agent:** Grok (parallel with HPWJ + Rigging)  
**Human ask:** Search Mac; summarise; review Aramco CSM and place as example data.

| Item | Result |
|------|--------|
| Module-1 PPTX full re-extract | 66 slides → `ANABEEB_Scaffold_Basic_Module1_Numeric_Harvest.md` |
| **Aramco CSM-II (secondary)** | Duty table 1.2 / 2.4 / >2.4 + cantilever 3 m **as quoted on s38/s44** → `ARAMCO_CSM_II_From_Training_Deck.md` |
| Full CSM PDF | **Not on Mac** — still primary GAP |
| Conflicts re-logged | Coupler 9.4 vs 9.1 kN; N vs kN/m² unit wording on duty slide |

**Deliverables:** source_materials harvest pack + CHANGELOG + inventory update. No Visible MCR.

---

## Campaign 0 — Local scaffold (28 July 2026)

**Branch:** local `main`  
**Done:** Process lock, structure, seed MCR, training stubs, local git only.

---

## Campaign 1 — Max stack v0.2 (28 July 2026)

**Branch:** `draft/campaign-max-stack-v0.2`  
**Goal:** Steps 1–5 in one push — internal harvest, public standards, T1 truth, Ch01 production, GitHub remote.

### 1 — Internal / Anabeeb materials

| Item | Result |
|------|--------|
| PPTX Module-1 | Already seeded |
| OPS-P-019 style scaffold procedure | **Not found** |
| AIMS-L3-HSE-P-010 Working at Height | **Found + extracted** → `references/standards/Anabeeb_AIMS_L3_HSE_P010_Working_at_Height_Summary.md` |
| Scaffold SWP-019 on master list | **Listed New** — file missing (GAP-001) |
| Aramco/SABIC scaffold packs | Not on disk (GAP-002/003); SABIC SHEMS 08.09 cited via WAH |

### 2 — Public harvest

| Package | File |
|---------|------|
| RP-STD | `docs/research/packages/RP-STD/PUBLIC_HARVEST.md` |
| RP-COMP | `docs/research/packages/RP-COMP/PUBLIC_HARVEST.md` |
| RP-LOAD | `docs/research/packages/RP-LOAD/PUBLIC_HARVEST.md` |

### 3 — T1 truth pass

- Log: `docs/audit/campaign/T1_TRUTH_PASS_2026-07-28.md`  
- Closed: coupler 9.1 kN preference; duty units kN/m²; guardrail Anabeeb vs training split  
- Open: sleeve SWL, putlog primary, gin wheel, trapeze, wind threshold  
- **0 Visible promotions**

### 4 — Chapter 01

- Production draft: `docs/01_Introduction_Scope_Purpose_How_to_Use.md`  
- Awaiting Claude verification + human review

### 5 — GitHub remote

- Target: create `sluiper/Scaffolding-Grokapedia` and push draft branch + main  
- Local-first retained until push succeeds

### MCR delta

- v0.1.0-scaffold → **v0.2.0-draft**  
- Rows ≈45 → **54** (incl. MCR-021a, MCR-046–053)  
- Still all Drafting

### Next (Campaign 2 candidates)

- Claude Verification Report on Ch01 + T1  
- Ch03 / Ch05 / Ch06 / Ch17 production (WAH-rich)  
- Primary PDF intake when purchased  
- Human freeze of tag + ladder + duty unit set for AWARE pack pilot

---

## Campaign 1b — Max stack continue + gap hunt (28 July 2026)

**Branch:** `draft/campaign-max-stack-v0.2` (continued)

### Full PPTX re-extract → closed / new

| Item | Result |
|------|--------|
| Trapeze | **≤ 600 mm from ledger** (GAP-008 closed) |
| Aramco CSM-II duty | Light 1.2 / Med 2.4 / Spec >2.4 (MCR-054) |
| Ladder hatch | 675×900 mm; free spaces 600/200 (MCR-055) |
| Casters | ≥120 / ≥170 mm (MCR-056) |
| Plan braces free-stand | top, kicker, every 3rd lift (MCR-057) |
| Cantilever | ≤3 m without design; raker no splice (MCR-058/059) |
| User never pack | MCR-060–063 |
| Board typo | MCR-065 |

### Production drafts added

Ch02, Ch03, Ch05, Ch06, Ch13, Ch14, Ch17, Ch18  
Appendices A, D, E, G, H draft cards  
`references/standards/21_Regulatory_and_Client_Matrix.md`  
`docs/research/inventory/GAP_CATALOG.md` (GAP-001–022)

### MCR

v0.2 → **v0.3.0-draft** (~66 Drafting rows, still **0 Visible**)

### Remaining top gaps

GAP-001 SWP-019 · GAP-007 primary PDFs · GAP-004 tag validity · GAP-012 sleeve · GAP-009 wind · GAP-019 dual duty

---

## Campaign 1c — No-Claude full stack (28 July 2026)

**Human instruction:** keep building without Claude.

### Delivered
- All remaining chapters Ch04, 07–12, 15–16, 19–20 → production drafts  
- ATC-SCAF-AWARE full mini-pack (quiz 20 items)  
- Appendices B, C, I + checklist v0.4  
- Version **v0.4.0-draft**

### Explicit non-claims
- No Claude Verification Report  
- No Drafting → Visible  
- AWARE pack pilot risk accepted only by human if used in field before freeze

---

## Campaign 1d — Training suite + Ch21–28 (28 July 2026)

Human: ignore Claude, keep building.

### Delivered
- All six ATC-SCAF packs at 0.2-draft (BASIC complete with 40Q exam)
- docs/21–28 supporting sections
- v0.5.0-draft

### Still open
GAP-001, 004, 007, 009, 012, 019, real incidents, primary PDFs

---

## Campaign 2 — Family standard alignment (28 July 2026)

**Mode:** Local only (no push this pass)  
**Goal:** Parity with family standard v1.0 across inventory and honesty.

| Item | Result |
|------|--------|
| Family link | `FAMILY.md` + AGENTS/PROCESS |
| SECTION_HEALTH_SHEET | Live |
| MCR_RESTATEMENT_MAP | Seed live |
| Ch21–28 | Filenames confirmed; thin draft honesty in structure map |
| Claude VR | Still outstanding |
| Visible rows | Still **0** |

---

## Campaign 3 — Part 5 deepen v0.5.1 (28 July 2026)

**Mode:** Local only  
**Done:** Ch21–28 rewritten to production draft v0.6 depth (still unverified, 0 Visible).



---

## Campaign 1e — Multi-AI parallel build (28 July 2026)

### Parallel agents
1. **Disk gap hunt** — found SSU-PRO-001 listed (GAP-001b), SATORP STORP orientation numbers, form pack list SSU.FRM.001–009
2. **Thin-section deepen** — Ch07/08/11/12/27/28 expanded (EN/AR terms, inspection lists, flowcharts)
3. **Research packages** — RP-TIE/INSP/TRN/CLI; manufacturer stubs; MCR_EXAM_EXTRACT; Appendix F
4. **Orchestrator** — PTW/PPE MCR-066–069; SATORP MCR-070–074; family inventory files

### MCR
~75 Drafting rows (066–074 new cluster). **Still 0 Visible.**

### Highest-value human ask
Supply **SSU-PRO-001** Scaffolding Procedure Rev.3 (Blueprint says exists) + SSU forms.
