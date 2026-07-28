# Chapter 08 — Scaffold Types & Proprietary Systems

**Status:** Production draft v0.5  
**Date:** 28 July 2026  
**Branch:** `draft/campaign-max-stack-v0.2`  
**Seed:** PPTX-M1 s37–s44; Ch13 detail  

## MCR Mapping

| MCR-ID | Role in chapter |
|--------|-----------------|
| MCR-039 | Systems recognised: T&F / Cuplok / Ringlock |
| MCR-017–020 | Free-stand / mobile / independent bracing density |
| MCR-040–041 | Hung trapeze; independent post geometry |
| MCR-045 | Engineering scaffold gate |
| MCR-058–059 | Cantilever length / raker integrity |
| MCR-015 / 054 | Duty class selection (EN vs Aramco deck) |
| MCR-052 | Temporary platforms include scaffold types |
| MCR-056, 064 | Mobile casters / ladder |

---

## 1. Systems recognised in Anabeeb Module-1

| System | Deck label | Connection concept | Tube note |
|--------|------------|--------------------|-----------|
| Tube & fitting | Tube & Fittings | EN 74 couplers on EN 39 tubes | **48.3 × 4.0 mm** standards — MCR-001 |
| Cuplok | Captive wedge – Cuplok | Proprietary wedge / cup nodes | Often **48.3 × 3.2 mm** — MCR-002 |
| Ringlock | Quick fix / Ring lock – Layher-type | Proprietary ring / rosette nodes | Manufacturer wall thickness |

**MCR-039.** Always follow manufacturer erection manuals for proprietary systems (**GAP-022** — manuals not in-repo). [CITATION: PPTX-M1 s37]

### 1.1 System differences that matter [SYNTHESIS]

| Topic | Tube & fitting | Cuplok / Ringlock |
|-------|----------------|-------------------|
| Node joint | Coupler selection critical (Class A/B, type) | Captive node hardware; torque/wedge per manual |
| Tube wall | Type 4 (4.0 mm) typical standards | Type 3 (3.2 mm) often for Cuplok stock |
| Mixed systems | Avoid mixing without design | Do not mix node hardware across brands without approval |
| Brace language | Swivel + tube diagonal | System diagonal / ledger brace modules |
| Compliance sheet | TG20-style / design | Manufacturer compliance sheet / design |

---

## 2. Configuration types (geometry)

| Type | Essence | Primary chapter | Key MCR |
|------|---------|-----------------|---------|
| Free-standing tower | 4 standards; height/base ratio | Ch13 | 017, 018, 057 |
| Mobile tower | Tower on locked casters | Ch13 | 019, 056, 064 |
| Independent | 2 standards across width + length; ties to structure | Ch13 + Ch11 | 041, 020 |
| Suspended / underhung | Hung from structure | Ch13 | 040 |
| Cantilever | Platform beyond inside line | Ch13 | 032, 058, 059 |
| Birdcage / special | Multi-bay internal access | Engineering often | 045 |

WAH temporary platform list also includes hop-ups, personnel cages, stepladders (**MCR-052**) — not expanded here.

---

## 3. Selection flowchart (markdown)

Use top-down. First match **geometry / stability mode**, then **system stock**, then **duty**, then **engineering gate**.

```
START — elevated work needs temporary platform
│
├─ [1] Fall risk ≥ 1.8 m or WAH listed case?
│      YES → fall-protection hierarchy applies (MCR-046, 030)
│      NO  → still plan edge/drop controls if elevated work develops
│
├─ [2] Can permanent platform / safer alternative be used?
│      YES → prefer permanent / lower-risk access (hierarchy)
│      NO  → continue scaffold selection
│
├─ [3] What geometry fits the structure?
│      │
│      ├─ Need platform beyond footprint of inside standards?
│      │    YES → CANTILEVER path
│      │           • Platform length ≤ 3 m without design (MCR-058)
│      │           • Raker 65°–75°, single tube no splice (MCR-032, 059)
│      │           • > 3 m → engineered design (MCR-045, 058)
│      │
│      ├─ Must hang from overhead steel / structure?
│      │    YES → SUSPENDED / UNDERHUNG path
│      │           • Tie around section; trapeze ≤ 600 mm from ledger (MCR-040)
│      │           • Girder pairs + check on steel (MCR-012, 034, 042)
│      │           • Outside standard hang method → design (MCR-045)
│      │
│      ├─ Free of permanent structure (no ties available / not required)?
│      │    │
│      │    ├─ Need to relocate frequently on firm level surface?
│      │    │    YES → MOBILE TOWER
│      │    │           • H ≤ 4 × min base; outriggers if exceeded (MCR-019)
│      │    │           • Brace 4 sides; plan braces bottom/top/intermediate
│      │    │           • Lock casters; empty when moving (MCR-019, 056)
│      │    │           • Prefer internal ladder (MCR-064)
│      │    │
│      │    └─ Fixed location free-stand
│      │         → FREE-STANDING TOWER
│      │              • External H ≤ 3 × base; internal ≤ 4 × (MCR-017, 018)
│      │              • Brace 4 sides; plan top, kicker, every 3rd lift (MCR-057)
│      │
│      └─ Runs along façade / building with tie opportunity?
│           → INDEPENDENT SCAFFOLD
│                • 2 posts across width (MCR-041)
│                • Face bracing ends + every 5th line; ledger alternate (MCR-020)
│                • Ties per Ch11 (do not invent spacing — GAP-015)
│
├─ [4] Birdcage / bridge / load-bearing / multi-lift special?
│      YES → ENGINEERING GATE (MCR-045) — competent design & review
│
├─ [5] System family (stock + client preference)
│      │
│      ├─ Proprietary compliance sheet covers full geometry + duty?
│      │    YES → prefer Cuplok or Ringlock per stock (MCR-039)
│      │          Follow manufacturer manual (GAP-022)
│      │    NO / flexibility needed → Tube & Fitting
│      │
│      └─ Outside compliance sheet or mixed systems?
│           → ENGINEERING GATE (MCR-045)
│
├─ [6] Duty class for task
│      │
│      ├─ Client specifies Aramco CSM-II style?
│      │    → Light 1.2 / Medium 2.4 / Special >2.4 kN/m² (MCR-054)
│      │
│      ├─ EN 12811 / TG20-style site?
│      │    → Class 1–4 (0.75 / 1.5 / 2.0 / 3.0 kN/m²) (MCR-015)
│      │      (EN also Class 5–6 if design uses them)
│      │
│      └─ Dual labelling risk?
│           → Prefer client-specified class (MCR-044); GAP-019 open
│
├─ [7] Foundations, access, edge protection, tag
│      → Sole/base (MCR-003–007, 033); ladder (MCR-023);
│        guardrails (MCR-021); inspect/tag (MCR-028, 029)
│
└─ END — erect only by competent scaffolders (MCR-035, 060)
```

### 3.1 Compact decision table [SYNTHESIS]

| If… | Then prefer… | Gate |
|-----|--------------|------|
| Short free access, move often | Mobile tower | H/B + casters MCR-019/056 |
| Free of structure, fixed | Free-standing tower | H/B MCR-017/018 |
| Façade work, structure available | Independent + ties | MCR-020, Ch11 |
| Work beyond building line | Cantilever | ≤3 m or design MCR-058 |
| No ground support under platform | Hung / underhung | MCR-040 + design as needed |
| Proprietary stock + manual covers job | Cuplok or Ringlock | MCR-039, GAP-022 |
| Flexibility / client T&F only | Tube & fitting | MCR-001, 008–014 |
| Outside standard sheet | Engineered scaffold | MCR-045 |

---

## 4. Selection logic (narrative summary) [SYNTHESIS]

1. Prefer proprietary system if site stock + manufacturer compliance sheet covers the job.  
2. Use tube & fitting where flexibility or client specification requires.  
3. If outside standard compliance sheet → **MCR-045** design.  
4. Match **duty class** to task (**MCR-015 / 054**) under client gate (**MCR-044**).  
5. Geometry (free-stand / mobile / independent / hung / cantilever) is chosen **before** arguing system brand.  
6. Bracing and ties are configuration-dependent (Ch11–12) — not optional add-ons after paint starts.

---

## 5. Worked example — pick a type [DERIVED]

**Given:** Paint inspection on external vessel skirt; ground firm asphalt; max platform height 4.0 m; base available 1.2 m × 1.2 m; no permanent structure for ties within reach; light tools only.

| Step | Assessment |
|------|------------|
| Geometry | Free of structure → free-stand or mobile |
| Relocate? | Several positions around vessel → **mobile** preferred |
| H/B check | H = 4.0 m; min base = 1.2 m; ratio = 4.0/1.2 ≈ **3.33** ≤ **4** → OK for mobile (**MCR-019**) without outriggers |
| Duty | Paint/inspect → Class 2 **1.5 kN/m²** (MCR-015) or Aramco Light **1.2** if CSM site (MCR-054) |
| System | Use available stock; Cuplok OK if compliance sheet covers light mobile tower |

If height were 5.5 m on same base: ratio = 5.5/1.2 ≈ **4.58** > 4 → outriggers / larger base / redesign (**MCR-019**).

---

## 6. Verification Log

| Check | Result |
|-------|--------|
| Selection flowchart in markdown | Yes §3 |
| All gates point to existing MCR | Yes |
| No manufacturer clause numbers invented | Yes |
| Dual duty systems disclosed | Yes step [6] |
| Cross-links Ch11–13 | Yes |
| Claude independent verify | Skipped per user direction |

## 7. Honest gaps

- No Layher/Cuplok manuals in-repo (**GAP-022**).  
- No Anabeeb preferred-system policy document.  
- Full Aramco CSM-II text still partial (**GAP-002**).  
- Birdcage / bridge design methods not detailed.  
- Compliance-sheet library not built for site stock.
