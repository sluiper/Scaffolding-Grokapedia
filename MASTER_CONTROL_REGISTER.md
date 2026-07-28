# MASTER CONTROL REGISTER (Living Document) — v0.1.0-scaffold

**This is the single source of truth for the entire Scaffolding Encyclopedia.**

Every named rule, numeric threshold, procedural requirement, and control from all sources and versions must be recorded here with clear sourcing and linkage to FMEA where applicable.

**Latest Update (28 July 2026):** Initial seed from Anabeeb *New Scaffolder’s Basic Training Program Module-1* PPTX. **All rows Status = Drafting.** No dual-model verification against primary standards has been completed. PPTX is a teaching aid, not SSOT.

## How to Use

- Add new rows immediately when a gap, new client requirement, or incident learning is identified.
- Update Status column as content is drafted or controls are implemented.
- Never remove rows — only mark as superseded if truly replaced by a stronger, documented control.
- Every operational procedure, checklist, and training module must map back to relevant MCR items.
- **Do not hard-code MCR numbers into training slides or exams** — cite MCR-ID and look up this register.

## Status Legend

- **Visible** = Explicitly mandated and dual-model verified + human-promoted
- **Drafting** = Proposed from seed material or research; awaiting verification & human gate
- **Added** = New in current version
- **Priority** = High RPN item from FMEA requiring focused attention
- **Superseded** = Replaced by a stronger documented control (row kept for history)

## High-Priority Candidates (to be confirmed by FMEA — Section 19)

| Candidate risk | Related seed MCR |
|----------------|------------------|
| Fall from height / incomplete edge protection | MCR-021, MCR-022, MCR-030 |
| Collapse from overloading / wrong duty class | MCR-015 |
| Collapse from missing/inadequate ties | MCR-016–020 |
| Collapse from poor foundation / sole boards | MCR-005–007, MCR-033 |
| Struck by falling objects / drop zone | MCR-030, MCR-031 |
| Incorrect coupler type / class misuse | MCR-008–014 |
| Unauthorised use of red-tagged scaffold | MCR-028, MCR-029 |
| Free-standing tower exceeded height ratio | MCR-017, MCR-018 |

## Master Control Register — Seed Rules & Thresholds

> **Source tag key for this seed:**  
> `PPTX-M1` = Anabeeb New Scaffolder’s Basic Training Program Module-1 (66-slide deck).  
> Clause/page references inside PPTX are slide numbers where known.  
> Primary standard citations are **targets for verification**, not yet confirmed matches.

| ID | Topic | Rule / Number / Threshold | Source(s) | Status | Notes / FMEA Link |
|----|-------|---------------------------|-----------|--------|-------------------|
| MCR-001 | Tube size — tube & fitting | Standards tubes: **48.3 mm OD × 4 mm** wall; max length **6 m**; cited BS 1139 / EN 39 | PPTX-M1 s11; verify EN 39 / BS 1139 | Drafting | Do not use if defective; never cut on site unless supervisor instructs |
| MCR-002 | Tube size — Cuplok | Cuplok tubes: **48.3 mm OD × 3.2 mm** wall; max length **6 m**; cited EN 10219 | PPTX-M1 s11; verify EN 10219 | Drafting | System-specific |
| MCR-003 | Base plate | Base plate **150 mm × 150 mm × 6 mm** thick | PPTX-M1 s12 | Drafting | |
| MCR-004 | Base jack extension | Maximum extension of base jack = **2/3 of thread height** | PPTX-M1 s12 | Drafting | Verify against manufacturer / TG20 |
| MCR-005 | Sole board minimum (single) | Minimum **38 mm thick × 225 mm wide × 450 mm long** | PPTX-M1 s13 | Drafting | Spread load to ground |
| MCR-006 | Sole board omit | Sole boards may be omitted if ground is asphalt or concrete | PPTX-M1 s13 | Drafting | Confirm client stricter rules |
| MCR-007 | Sole board not scaffold board | Sole boards must **never** be returned to service as scaffold boards | PPTX-M1 s13 | Drafting | Absolute operational rule candidate |
| MCR-008 | Double coupler SWL | Right-angle / double coupler Class B SWL **9.4 kN** (slip along tube); drop-forged only acceptable (deck); also cites **9.1 kN** on fittings-type slide — **resolve conflict before Visible** | PPTX-M1 s14 vs s23 | Drafting | **P0 truth conflict inside seed deck** |
| MCR-009 | Swivel coupler SWL | Swivel coupler Class B SWL **9.4 kN** (s15) / **9.1 kN** (s23) — same conflict class as MCR-008 | PPTX-M1 s15, s23; verify EN 74 | Drafting | Brace joints, non-90° connections |
| MCR-010 | Putlog / single coupler SWL | Putlog coupler SWL **0.53 kN** (axial pull-out); non-load-bearing board connection | PPTX-M1 s16, s23 | Drafting | Never use as structural load path |
| MCR-011 | Sleeve coupler SWL | Sleeve Class B cited **3.0 kN or 0.59 kN/m** (s18) vs **0.53 kN** (s24) — **resolve before Visible** | PPTX-M1 s18, s24; verify EN 74 | Drafting | Stagger sleeve joints |
| MCR-012 | Girder couplers | Girder couplers always used **in pairs**; failure mode slip on tube/section | PPTX-M1 s19, s58 | Drafting | Check couplers required (seed) |
| MCR-013 | Joint pins | Not for positions subject to bending or tension | PPTX-M1 s21 | Drafting | |
| MCR-014 | Coupler standard | Couplers conform **EN 74**; marked brand, year, load class A or B; maintain free-running lightly lubricated nuts/bolts; not exposed to heat | PPTX-M1 s22 | Drafting | |
| MCR-015 | Duty load ratings | Very light **0.75 kN/m²** (access/walkway); Light **1.5**; General/medium **2.0**; Heavy **3.0** (masonry/concrete). *Deck text says “N sqm” — interpret as kN/m² pending verification* | PPTX-M1 s38; verify TG20 / BS EN 12811 | Drafting | **Unit wording in deck is ambiguous** |
| MCR-016 | Brace angle | Longitudinal and transverse braces **35°–55°** from horizontal; connect nearest to node points | PPTX-M1 s33, s57 | Drafting | Bad practice if outside band / far from node |
| MCR-017 | Free-standing tower height (external) | External free-standing tower height ≤ **3 ×** minimum base dimension | PPTX-M1 s39 | Drafting | 4 standards; brace all sides; plan braces |
| MCR-018 | Free-standing tower height (internal) | Internal free-standing tower height ≤ **4 ×** minimum base dimension | PPTX-M1 s39 | Drafting | |
| MCR-019 | Mobile tower height | Mobile tower height ≤ **4 ×** min base dimension; outriggers if exceeded; wheels locked when working; do not move occupied | PPTX-M1 s40 | Drafting | Verify against manufacturer / PASMA-class practice |
| MCR-020 | Independent scaffold bracing density | Face bracing both ends + every **5th** line of standards; ledger bracing alternate lines | PPTX-M1 s41 | Drafting | |
| MCR-021 | Guardrail heights | Top rail **0.950 m – 1.150 m** from platform; mid-rail at mid height between top rail and platform | PPTX-M1 s34; verify BS EN 12811 / local | Drafting | |
| MCR-022 | Kicker lift | Kicker lift max **150 mm** from ground | PPTX-M1 s30 | Drafting | |
| MCR-023 | Ladder slope | Access ladder slope **4 vertical : 1 horizontal** (~75°); extend **≥ 1.0 m** above landing; secure top, mid, bottom with ladder clamp | PPTX-M1 s27, s51 | Drafting | |
| MCR-024 | Ladder beam material | Steel ladder beams from BS EN 39 type 4 tubes 48.3 mm, 4 mm wall, fy ≥ **235 N/mm²** | PPTX-M1 s26 | Drafting | |
| MCR-025 | Ladder beam splice | Splice: short tubes on top & bottom chords with **min 4 swivel couplers** + **1 sleeve** per chord end (good practice slide); bad = sleeve-only chord join | PPTX-M1 s59 | Drafting | |
| MCR-026 | Scaffold boards | LVL boards BS 2482; nominal **38 mm × 225 mm**; mark standard name, manufacturer, max span | PPTX-M1 s20 | Drafting | Defect boards out of service; cut-back only if remaining section still compliant |
| MCR-027 | Double sole under shared standards | Shared sole board for two standards: min **750 × 225 × 75 mm**; or individual **450 × 225 × 38 mm** with central bearing | PPTX-M1 s25 | Drafting | |
| MCR-028 | Scaff-tag colours | **Red** = scaffolders only / incomplete; **Yellow** = harness & lanyard mandatory; **Green** = safe for intended use | PPTX-M1 s64 | Drafting | Confirm Anabeeb tag system exactly |
| MCR-029 | User pre-use check | End user must confirm scaffold safe by checking scaff-tag at access points **prior to each use** | PPTX-M1 s62 | Drafting | |
| MCR-030 | Fall protection hierarchy (seed) | Guardrails; barricade drop zone + signs; harness & lanyard; tool lanyards / scaffolder belts; nets / canopies as applicable | PPTX-M1 s48 | Drafting | Expand with Anabeeb fall-arrest procedure |
| MCR-031 | Gin wheel SWL & reach | Gin wheel max SWL **50 kg**; horizontal support tube extend max **750 mm**; fixed to scaffold with **2 right-angle couplers** | PPTX-M1 s54 | Drafting | High misuse risk |
| MCR-032 | Cantilever raker angle | Raker inclination **65°–75°** to horizontal for cantilever support arrangement (seed description) | PPTX-M1 s44 | Drafting | Engineering scaffold often required — verify |
| MCR-033 | Foundations | Unsafe foundations prohibited (soft ground without sole boards, sloping unsecured bases, etc. per bad-practice set) | PPTX-M1 s60 | Drafting | Expand with ground-bearing capacity guidance |
| MCR-034 | Coupler class for structural sections | Double couplers not allowed for structural section connections; use girder couplers in pairs with check couplers | PPTX-M1 s58 | Drafting | |
| MCR-035 | Training & competency link | All scaffolders trained/assessed against this Register and Anabeeb competency scheme; only competent persons erect/modify/dismantle | PPTX-M1 s5 concept; Ch15 | Drafting | Map to CISRS/TVTC/client later |
| MCR-036 | Work permit & planning | Barricade work area; warning signs; secure hand tools; JSA/risk assessment; TBT; proper PPE; never use defective equipment; work permit | PPTX-M1 s7 | Drafting | |
| MCR-037 | PPE last line of defence | PPE is last line of defence — engineering/admin controls first | PPTX-M1 s8 | Drafting | |
| MCR-038 | Never cut tube on site | Never cut tube on site unless instructed by supervisor | PPTX-M1 s11 | Drafting | |
| MCR-039 | Systems recognised | Tube & Fitting; Captive wedge Cuplok; Quick fix / Ringlock (Layher-type) | PPTX-M1 s37 | Drafting | Expand manufacturer rules later |
| MCR-040 | Hung / trapeze | Hung scaffold from structural sections; trapeze assist tube max distance limit stated in deck (confirm exact figure on s43 full text) | PPTX-M1 s43 | Drafting | **[GAP]** extract exact trapeze limit from deck/procedure |
| MCR-041 | Independent scaffold posts | Independent scaffold: 2 posts across width + multiple along length | PPTX-M1 s41 | Drafting | |
| MCR-042 | Check couplers on ties | Tie connections use check (safety) couplers; girder pairs with check couplers | PPTX-M1 s58 | Drafting | |
| MCR-043 | Anabeeb stricter rule gate | Placeholder: any Anabeeb procedure stricter than international baseline **wins** | Human + future OPS | Drafting | **[INTERNAL GAP – human source required]** |
| MCR-044 | Client matrix gate | Aramco / SABIC / other client scaffold rules may override baseline when stricter | Human | Drafting | **[INTERNAL GAP – human source required]** |
| MCR-045 | Engineering scaffold gate | Load-bearing, bridge, special, or design outside TG20/standard configurations requires engineered design & competent design review | Industry practice; PPTX engineering mentions | Drafting | Expand in Ch18 |

## Conflicts Logged (Must Resolve Before Any Visible Promotion)

1. **Double/swivel coupler SWL:** 9.4 kN (s14/s15) vs 9.1 kN (s23) — likely EN 74 Class B rounding or deck error.
2. **Sleeve SWL:** 3.0 kN or 0.59 kN/m (s18) vs 0.53 kN (s24).
3. **Duty loads unit text:** “N sqm” almost certainly means kN/m² — must confirm against BS EN 12811 / TG20 tables.
4. **Trapeze max distance (s43):** full numeric limit needs clean extraction.

## Promotion Rules

A row may move Drafting → Visible only when:

1. Primary citation or full derivation is shown, **or** Anabeeb controlled procedure clause is cited.
2. Conflicts above are resolved for that row.
3. Claude Verification Report is clean (or P2 only).
4. Human explicitly approves the promotion.

## Row Count

**45 seed rows, all Drafting.** Zero Visible.
