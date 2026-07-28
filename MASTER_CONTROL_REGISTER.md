# MASTER CONTROL REGISTER (Living Document) — v0.2.0-draft

**This is the single source of truth for the entire Scaffolding Encyclopedia.**

Every named rule, numeric threshold, procedural requirement, and control from all sources and versions must be recorded here with clear sourcing and linkage to FMEA where applicable.

**Latest Update (28 July 2026 — campaign max-stack):**  
- Seed from PPTX-M1 retained.  
- T1 truth pass applied (see `docs/audit/campaign/T1_TRUTH_PASS_2026-07-28.md`).  
- Anabeeb **AIMS-L3-HSE-P-010 Working at Height** extracted → new MCR rows + tag/guardrail alignment.  
- **Still zero Visible rows.** Human + Claude gate required for any Drafting → Visible.

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

| Candidate risk | Related MCR |
|----------------|-------------|
| Fall from height / incomplete edge protection | MCR-021, MCR-022, MCR-030, MCR-049 |
| Collapse from overloading / wrong duty class | MCR-015 |
| Collapse from missing/inadequate ties | MCR-016–020 |
| Collapse from poor foundation / sole boards | MCR-005–007, MCR-033 |
| Struck by falling objects / drop zone | MCR-030, MCR-031, MCR-047, MCR-048 |
| Incorrect coupler type / class misuse | MCR-008–014 |
| Unauthorised use of red-tagged scaffold | MCR-028, MCR-029 |
| Free-standing tower exceeded height ratio | MCR-017, MCR-018 |

## Source tags

| Tag | Meaning |
|-----|---------|
| PPTX-M1 | Anabeeb New Scaffolder’s Basic Training Program Module-1 |
| WAH-P010 | Anabeeb AIMS-L3-HSE-P-010 Working at Height (docx extract 28 Jul 2026) |
| EN39-sec | Secondary restatement of EN 39 (not primary PDF) |
| EN74-sec | Secondary restatement of EN 74-1 |
| EN12811-sec | Secondary restatement of EN 12811-1 |
| BS2482-sec | Secondary restatement of BS 2482 |

## Master Control Register — Rules & Thresholds

| ID | Topic | Rule / Number / Threshold | Source(s) | Status | Notes / FMEA Link |
|----|-------|---------------------------|-----------|--------|-------------------|
| MCR-001 | Tube size — tube & fitting | Standards tubes: **48.3 mm OD × 4.0 mm** wall (EN 39 Type 4); max length often **6 m**; cited BS 1139 / EN 39 | PPTX-M1 s11; EN39-sec | Drafting | T1 PASS secondary. Defective out. Never cut on site unless supervisor instructs (MCR-038). |
| MCR-002 | Tube size — Cuplok / Type 3 | **48.3 mm OD × 3.2 mm** wall (EN 39 Type 3); max length often **6 m**; PPTX cites EN 10219 for Cuplok supply | PPTX-M1 s11; EN39-sec | Drafting | T1 PASS secondary for dimensions. |
| MCR-003 | Base plate | Base plate **150 mm × 150 mm × 6 mm** thick | PPTX-M1 s12 | Drafting | |
| MCR-004 | Base jack extension | Maximum extension of base jack = **2/3 of thread height** | PPTX-M1 s12 | Drafting | HOLD — manufacturer/TG20 primary needed |
| MCR-005 | Sole board minimum (single) | Minimum **38 mm thick × 225 mm wide × 450 mm long** | PPTX-M1 s13 | Drafting | |
| MCR-006 | Sole board omit | Sole boards may be omitted if ground is asphalt or concrete | PPTX-M1 s13 | Drafting | Confirm client stricter rules |
| MCR-007 | Sole board not scaffold board | Sole boards must **never** be returned to service as scaffold boards | PPTX-M1 s13 | Drafting | Absolute operational rule candidate |
| MCR-008 | Double coupler SWL | Right-angle / double coupler **EN 74-1 Class B slip resistance 9.1 kN**. Drop-forged preferred for load-bearing (Anabeeb training). | EN74-sec; PPTX-M1 s23; T1 truth pass | Drafting | **T1 resolved:** PPTX 9.4 kN discarded as deck inconsistency. Primary EN 74-1 still required for Visible. |
| MCR-009 | Swivel coupler SWL | Swivel coupler **Class B slip ~9.1 kN** (aligned to EN74-sec Class B right-angle class pending primary table) | EN74-sec; PPTX-M1 s23; T1 | Drafting | Use for brace / non-90° joints. Do not use as beam hanger. |
| MCR-010 | Putlog / single coupler SWL | Putlog coupler SWL **0.53 kN** (axial pull-out style); **non-load-bearing** board connection only | PPTX-M1 s16, s23 | Drafting | T1 HOLD — no independent secondary confirm |
| MCR-011 | Sleeve coupler SWL | **UNRESOLVED** — PPTX cites 3.0 kN or 0.59 kN/m (s18) vs 0.53 kN (s24). Stagger sleeves in scaffold. | PPTX-M1 s18, s24 | Drafting | **Do not promote** until EN 74 primary |
| MCR-012 | Girder couplers | Girder couplers always used **in pairs**; failure mode slip on tube/section | PPTX-M1 s19, s58 | Drafting | |
| MCR-013 | Joint pins | Not for positions subject to bending or tension | PPTX-M1 s21 | Drafting | |
| MCR-014 | Coupler standard | Couplers conform **EN 74**; marked brand, year, load class A or B; maintain free-running lightly lubricated nuts/bolts; not exposed to heat | PPTX-M1 s22 | Drafting | |
| MCR-015 | Duty load ratings (service UDL) | **Units = kN/m²** (not “N/m²”). Class 1 **0.75**; Class 2 **1.5**; Class 3 **2.0**; Class 4 **3.0**. EN also defines Class 5 **4.5** and Class 6 **6.0**. Never exceed design class marked on scaffold. | EN12811-sec; PPTX-M1 s38 (unit-corrected); T1 | Drafting | **T1 fixed units.** PPTX “N sqm” was training error. |
| MCR-016 | Brace angle | Longitudinal and transverse braces **35°–55°** from horizontal; connect nearest to node points | PPTX-M1 s33, s57 | Drafting | HOLD primary |
| MCR-017 | Free-standing tower height (external) | External free-standing tower height ≤ **3 ×** minimum base dimension | PPTX-M1 s39; TG20 secondary snippets | Drafting | HOLD TG20 primary |
| MCR-018 | Free-standing tower height (internal) | Internal free-standing tower height ≤ **4 ×** minimum base dimension | PPTX-M1 s39 | Drafting | |
| MCR-019 | Mobile tower height | Mobile tower height ≤ **4 ×** min base dimension when stationary; outriggers if exceeded; wheels locked when working; do not move occupied | PPTX-M1 s40; OSHA 4:1 comparative | Drafting | |
| MCR-020 | Independent scaffold bracing density | Face bracing both ends + every **5th** line of standards; ledger bracing alternate lines | PPTX-M1 s41 | Drafting | |
| MCR-021 | Guardrail heights — Anabeeb | **Anabeeb sites:** top edge **1.1 m ± 8 cm** (1.02–1.18 m) above working level; midrail / intermediate **≥ 53 cm**; top withstand **890 N**; midrail **666 N** | WAH-P010 | Drafting | **T1:** Anabeeb WAH supersedes deck for Anabeeb operations |
| MCR-021a | Guardrail heights — training/UK floor | Training deck top rail **0.950–1.150 m**; UK WAH Regs construction floor **≥ 950 mm**; intermediate gap **≤ 470 mm** (UK) | PPTX-M1 s34; UK WAH Regs secondary | Drafting | Comparative / training. Prefer MCR-021 on Anabeeb work. |
| MCR-022 | Kicker lift | Kicker lift max **150 mm** from ground | PPTX-M1 s30 | Drafting | |
| MCR-023 | Ladder slope & extension | Access ladder slope **4 vertical : 1 horizontal** (~75°); extend **≥ 1.0 m** above landing; secure; three-point contact | PPTX-M1 s27, s51; WAH-P010 | Drafting | **T1 PASS** dual source |
| MCR-024 | Ladder beam material | Steel ladder beams from BS EN 39 type 4 tubes 48.3 mm, 4 mm wall, fy ≥ **235 N/mm²** | PPTX-M1 s26 | Drafting | |
| MCR-025 | Ladder beam splice | Splice: short tubes on top & bottom chords with **min 4 swivel couplers** + **1 sleeve** per chord end (good practice slide) | PPTX-M1 s59 | Drafting | |
| MCR-026 | Scaffold boards | Timber boards **BS 2482**; nominal **38 mm × 225 mm** (also 63 mm grade); mark standard, manufacturer, max span | PPTX-M1 s20; BS2482-sec | Drafting | T1 PASS secondary dimensions |
| MCR-027 | Double sole under shared standards | Shared sole board for two standards: min **750 × 225 × 75 mm**; or individual **450 × 225 × 38 mm** with central bearing | PPTX-M1 s25 | Drafting | |
| MCR-028 | Scaff-tag colours (Anabeeb) | **Green** = Safe for Use; **Yellow** = Restricted Use; **Red** = Do Not Use. Display at access points. | WAH-P010; PPTX-M1 s64 | Drafting | **T1 aligned to WAH wording** (PPTX “scaffolders only / harness mandatory” folded under Red/Yellow practice) |
| MCR-029 | Scaffold inspection & pre-use | All scaffolds **inspected and approved prior to use**; tags at access points; end user confirms tag status **prior to each use** | WAH-P010; PPTX-M1 s62 | Drafting | T1 strengthened |
| MCR-030 | Fall protection hierarchy (scaffold) | Prefer collective protection (guardrails, nets); barricade drop zone; harness/lanyard as required by tag/task; tool lanyards | WAH-P010; PPTX-M1 s48 | Drafting | |
| MCR-031 | Gin wheel SWL & reach | Gin wheel max SWL **50 kg**; horizontal support tube extend max **750 mm**; fixed with **2 right-angle couplers** | PPTX-M1 s54 | Drafting | T1 HOLD — PPTX only |
| MCR-032 | Cantilever raker angle | Raker inclination **65°–75°** to horizontal (seed description) | PPTX-M1 s44 | Drafting | Engineering scaffold often required |
| MCR-033 | Foundations | Unsafe foundations prohibited (soft ground without sole boards, sloping unsecured bases, etc.) | PPTX-M1 s60 | Drafting | |
| MCR-034 | Coupler class for structural sections | Double couplers not allowed for structural section connections; use girder couplers in pairs with check couplers | PPTX-M1 s58 | Drafting | |
| MCR-035 | Training & competency link | All scaffolders trained/assessed against this Register and Anabeeb competency scheme; only competent persons erect/modify/dismantle | PPTX-M1; Ch20 | Drafting | |
| MCR-036 | Work permit & planning | Barricade work area; warning signs; secure hand tools; JSA/risk assessment; TBT; proper PPE; never use defective equipment; work permit | PPTX-M1 s7; WAH-P010 | Drafting | |
| MCR-037 | PPE last line of defence | PPE is last line of defence — engineering/admin controls first | PPTX-M1 s8; WAH-P010 hierarchy | Drafting | |
| MCR-038 | Never cut tube on site | Never cut tube on site unless instructed by supervisor | PPTX-M1 s11 | Drafting | |
| MCR-039 | Systems recognised | Tube & Fitting; Captive wedge Cuplok; Quick fix / Ringlock (Layher-type) | PPTX-M1 s37 | Drafting | |
| MCR-040 | Hung / trapeze | Hung scaffold from structural sections; trapeze assist tube max distance **[GAP-008 — extract exact figure]** | PPTX-M1 s43 | Drafting | |
| MCR-041 | Independent scaffold posts | Independent scaffold: 2 posts across width + multiple along length | PPTX-M1 s41 | Drafting | |
| MCR-042 | Check couplers on ties | Tie connections use check (safety) couplers; girder pairs with check couplers | PPTX-M1 s58 | Drafting | |
| MCR-043 | Anabeeb stricter rule gate | Any Anabeeb controlled procedure stricter than international baseline **wins** on Anabeeb work | WAH-P010; policy | Drafting | Partial content from WAH; full scaffold SWP still GAP-001 |
| MCR-044 | Client matrix gate | Aramco / SABIC / other client scaffold rules may override baseline when stricter. WAH cites **SABIC SHEMS 08.09** for fall protection. | WAH-P010; Human | Drafting | Scaffold-specific client docs still GAP-002/003 |
| MCR-045 | Engineering scaffold gate | Load-bearing, bridge, special, or design outside standard configurations requires engineered design & competent design review | Industry practice; PPTX engineering mentions | Drafting | |
| MCR-046 | Fall trigger height (Anabeeb) | Fall protection required where risk of falling **≥ 1.8 m (6 ft)** from unprotected edge or elevated surface (plus listed hole/excavation/roof cases in WAH) | WAH-P010 | Drafting | New from WAH extract |
| MCR-047 | Tool lanyards mandatory | Tool lanyards **mandatory** to prevent falling objects (with toe-boards/screens as applicable) | WAH-P010 | Drafting | New |
| MCR-048 | Drop zone barricade | Barricade and sign-post areas immediately underneath work at height; “Danger – Overhead Work” style warnings | WAH-P010 | Drafting | New |
| MCR-049 | 100% tie-off | Workers shall maintain **100% tie-off** when working at height using double lanyards or SRL (per WAH), after collective protection hierarchy | WAH-P010 | Drafting | New — scaffold erect/modify often needs task-specific application |
| MCR-050 | Anchorage strength | Anchorage point must support at least **22.2 kN (5000 lb)** per person | WAH-P010 | Drafting | New |
| MCR-051 | Weather stop-work (height) | Stop work at height during adverse weather: strong wind (numeric threshold **[GAP-009]**), rain/slippery, sandstorm, poor visibility, lightning, adverse thermal | WAH-P010 | Drafting | New |
| MCR-052 | Temporary platforms list | Where permanent platforms unavailable, temporary options include: scaffolding, mobile scaffolding, suspended scaffolding, hop-ups, personnel cages, portable stepladder | WAH-P010 | Drafting | New |
| MCR-053 | Planned scaffold SWP | Controlled scaffold procedure target: **AIMS-L3-HSE-SWP-019** Scaffolding Erection, Inspection & Use (status New on master list — file not yet available) | ANABEEB HSE Procedure Master List Rev01 | Drafting | Placeholder — bind encyclopedia when SWP issued |

## Conflicts Log

| # | Issue | Resolution |
|---|-------|------------|
| C1 | Double/swivel 9.4 vs 9.1 kN | **Adopt 9.1 kN Class B** (EN74-sec). 9.4 historical deck only. |
| C2 | Sleeve multi-values | **Open** — MCR-011 |
| C3 | Duty “N sqm” | **Resolved → kN/m²** |
| C4 | Guardrail PPTX vs WAH | **Anabeeb → MCR-021**; training/UK floor → MCR-021a |
| C5 | Trapeze limit | **Open** — GAP-008 |
| C6 | Wind threshold incomplete in WAH extract | **Open** — GAP-009 |

## Promotion Rules

A row may move Drafting → Visible only when:

1. Primary citation or full derivation is shown, **or** Anabeeb controlled procedure clause is cited with human acceptance of extract accuracy.
2. Conflicts above are resolved for that row.
3. Claude Verification Report is clean (or P2 only).
4. Human explicitly approves the promotion.

## Row Count

**54 control rows** (incl. MCR-021a) — **all Drafting**. **Zero Visible.**
