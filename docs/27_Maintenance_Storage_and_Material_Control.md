# Section 27 — Maintenance, Storage & Material Control

**Status:** Production draft v0.6  
**Date:** 28 July 2026  
**Branch:** `draft/campaign-max-stack-v0.2`  

## MCR Mapping

| MCR-ID | Role in section |
|--------|-----------------|
| MCR-001–002 | Tube dimensions; defective tube out |
| MCR-003–007, 027 | Base plate, jack, sole boards; sole ≠ deck board |
| MCR-008–014 | Coupler class, SWL family, EN 74 marking, heat ban, lubrication |
| MCR-010 | Putlog non-load-bearing only |
| MCR-011 | Sleeve values unresolved — stagger still taught |
| MCR-026, 065 | Boards BS 2482; 225 mm width typo flag |
| MCR-031 | Gin wheel SWL / arm / fixings |
| MCR-033 | Foundations / unsafe support (material on soft ground) |
| MCR-038 | Never cut tube on site without supervisor |
| MCR-028–029 | Tag / inspect culture (quarantine feeds red-tag material) |
| MCR-036 | Never use defective equipment |

---

## 1. Purpose

Material control prevents collapse and drop events caused by **re-issuing defective components**. Quarantine is cheaper than a red-tag scaffold after erection. [SYNTHESIS]

All numeric reject thresholds below are **only** those already in MCR or Module-1 / WAH harvest. Visual reject criteria without a numeric MCR are labelled **[SYNTHESIS / operational]** and must not be treated as primary-standard clauses.

---

## 2. Pre-use material reject criteria table

Inspect **before** issue from yard and **before** incorporation into scaffold. Fail → **quarantine bin / scrap path**; do not mix with service stock. [SYNTHESIS]

| # | Component | Reject if… | Source / MCR | Tag |
|---|-----------|------------|--------------|-----|
| R1 | **Tube (T&F standards)** | Wrong size for system (not **48.3 mm OD × 4.0 mm** wall where T&F Type 4 required) | MCR-001 | [CITATION] |
| R2 | **Tube (Cuplok / Type 3 stock)** | Wrong size for Cuplok path (not **48.3 × 3.2 mm** where that stock is specified) | MCR-002 | [CITATION] |
| R3 | **Tube (any)** | Visibly defective (crushed ends, severe corrosion holes, split, bent beyond use) | Deck “do not use defective”; MCR-036 family | [CITATION / SYNTHESIS] |
| R4 | **Tube** | Field-cut on site without supervisor instruction (piece created outside control) | MCR-038 | [CITATION] |
| R5 | **Coupler** | Unmarked / no brand, year, load class A or B | MCR-014 | [CITATION] |
| R6 | **Coupler** | Nuts/bolts seized, threads stripped, free-running requirement failed | MCR-014 | [CITATION] |
| R7 | **Coupler** | Known heat exposure (welded near, fire, cutting-torch heat) | MCR-014 | [CITATION] |
| R8 | **Double / swivel for load path** | Not drop-forged where training requires drop-forged for load-bearing double/swivel | PPTX-M1 s14–15; MCR-008/009 notes | [CITATION] |
| R9 | **Putlog / single** | Intended for structural load-bearing joint (wrong application, not only “damaged”) | MCR-010 | [CITATION] |
| R10 | **Girder coupler** | Issued as single unit for structural connection (must plan **pairs**) | MCR-012 | [CITATION] |
| R11 | **Joint pin** | Issued for position subject to bending or tension | MCR-013 | [CITATION] |
| R12 | **Base plate** | Not **150 × 150 × 6 mm** (or distorted / cracked so bearing lost) | MCR-003 | [CITATION] |
| R13 | **Base jack** | Thread damaged so extension control unreliable; or intended use would exceed **2/3** thread height | MCR-004 | [CITATION] |
| R14 | **Sole board** | Below min **38 × 225 × 450 mm** for single standard case (or shared dims not met) | MCR-005, 027 | [CITATION] |
| R15 | **Sole board** | Offered for re-use as **scaffold board** after sole service | MCR-007 | [CITATION] |
| R16 | **Scaffold board** | Missing marks for standard / manufacturer / **max span** when required | MCR-026 | [CITATION] |
| R17 | **Scaffold board** | Defective timber (split, rot, large notches) not cut back to remaining **compliant** length | MCR-026; deck defect cut-back | [CITATION] |
| R18 | **Scaffold board width teaching** | Stock labelled or taught as “225 m” (OCR error) — correct is **225 mm** | MCR-065 | [CITATION] |
| R19 | **Gin wheel** | SWL mark missing or known capacity path > **50 kg** without other lift plan | MCR-031 | [CITATION] |
| R20 | **Gin wheel rope/sheave** | Rope/sheave damaged on pre-use visual | Deck material lifting; GAP-014 thin procedure | [CITATION / GAP] |
| R21 | **Mobile caster** | Diameter below duty: light **≥ 120 mm**, medium **≥ 170 mm**; or lock broken | MCR-056 | [CITATION] |
| R22 | **Any component** | Client/Anabeeb quarantine tag already applied; unknown pedigree after incident | MCR-036, 028 family | [SYNTHESIS] |

**Not in table (honest):** quantitative wall-thickness NDT reject %, % corrosion loss, or Anabeeb scrap rates — **no source in repo**.

### 2.1 Sleeve coupler special note

**MCR-011** sleeve SWL is **unresolved** (deck multi-values). Reject unmarked / heat-damaged / seized sleeves under R5–R7. Do **not** invent a single kN reject number until EN 74 primary resolves MCR-011. Still **stagger sleeves** in erected scaffold (MCR-011 notes).

---

## 3. Couplers — maintenance

- Free-running lightly lubricated nuts/bolts; examine before use. [CITATION: MCR-014]  
- No heat exposure (**MCR-014**).  
- Segregate defective fittings — quarantine bin.  
- Prefer Class B on load-bearing paths after T1 preference (**MCR-008/009**).  
- Girder hardware stored as **pair kits** when practical (supports MCR-012 discipline). [SYNTHESIS]

---

## 4. Tubes & boards — maintenance

- Reject defective tubes; never cut on site without supervisor (**MCR-038**).  
- Boards: marks for max span; defect cut-back only if remaining compliant (**MCR-026**).  
- Sole boards stored **separately** from deck boards (**MCR-007** control).  
- Do not issue sole boards into board stacks.  

---

## 5. Storage

| Control | Why | Tag |
|---------|-----|-----|
| Stacks stable; chocked | Prevent roll / crush injury | [SYNTHESIS] |
| Off soft mud | Corrosion, contamination, sole-board damage | MCR-033 family [SYNTHESIS] |
| Protected from vehicle damage | Bent tubes / crushed boards | [SYNTHESIS] |
| Tags/forms controlled stationery | Prevent fake green tags | MCR-028 [SYNTHESIS] |
| Quarantine bin separate & signed | Stop re-issue of rejects | MCR-036 [SYNTHESIS] |
| Sole vs deck board segregation | Enforce MCR-007 | [CITATION] |

---

## 6. Gin wheels & rope

- SWL marked; max **50 kg**; arm ≤ **750 mm**; **2** right-angle couplers (**MCR-031**).  
- Inspect rope/sheave before issue.  
- GAP-014: dedicated gin-wheel maintenance procedure still thin.

---

## 7. Worked example — yard reject decision [DERIVED]

**Batch:** 20 right-angle couplers returned from site.

| Unit | Observation | Decision |
|------|-------------|----------|
| 1–12 | EN 74 mark Class B; free nuts; no heat paint damage | Return to service |
| 13–15 | Unmarked | **Reject** R5 |
| 16–17 | Seized bolt | **Reject** R6 → try free / else scrap |
| 18 | Blue heat tint from nearby hot work | **Reject** R7 |
| 19–20 | Drop-forged Class B OK | Service |

No SWL re-test numbers claimed — no Anabeeb test lab procedure in-repo.

---

## 8. Interface with inspection & tags

| Material state | Scaffold implication |
|----------------|----------------------|
| Rejected in yard | Never erected |
| Defect found after erection | Isolate area; scaffolders replace; re-inspect (**MCR-029**) |
| Incomplete / unsafe after material failure | Red tag (**MCR-028**) |

End users must not “repair” with scrap fittings (**MCR-060**).

---

## 9. Verification Log

| Check | Result |
|-------|--------|
| Pre-use reject table present | Yes §2 (R1–R22) |
| Every numeric reject maps to MCR or flagged gap | Yes |
| No invented NDT scrap rates | Yes |
| Sleeve kN not invented | MCR-011 open noted |
| Claude independent verify | Skipped per user direction |

## 10. Honest gaps

- No Anabeeb material scrap rates or NDT regime for tubes.  
- GAP-014 gin-wheel procedure thin.  
- Primary EN 74 tables for Class A vs B field identification still secondary.  
- SWP-019 may add controlled material forms (**GAP-001**).  
- Manufacturer reject criteria for proprietary decks/nodes not in-repo (**GAP-022**).
