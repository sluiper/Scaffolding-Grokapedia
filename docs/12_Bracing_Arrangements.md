# Chapter 12 — Bracing Arrangements

**Status:** Production draft v0.5  
**Date:** 28 July 2026  
**Branch:** `draft/campaign-max-stack-v0.2`  
**Seed:** PPTX-M1 s33, s39–s42, s56–s57  

## MCR Mapping

| MCR-ID | Role in chapter |
|--------|-----------------|
| MCR-016 | Brace angle **35°–55°**; nearest to node points |
| MCR-020 | Independent face bracing ends + every **5th** line; ledger bracing alternate lines |
| MCR-017 | Free-standing external height ≤ **3 ×** min base |
| MCR-018 | Free-standing internal height ≤ **4 ×** min base |
| MCR-019 | Mobile height ≤ **4 ×** min base; lock casters; empty when moving |
| MCR-057 | Free-standing plan braces: **top, kicker, every third lift**; all four sides |
| MCR-009 | Swivel couplers for non-90° brace joints |
| MCR-056 | Mobile caster sizes (context for mobile brace package) |
| MCR-064 | Mobile external ladder preference (access, not brace) |

**Bad practice slides:** PPTX-M1 s56–s57.

---

## 1. Why brace

Bracing provides **lateral stiffness** so the scaffold does not rack or collapse sideways under wind, dynamic use, or imperfect geometry. Missing or badly placed braces are a collapse family control (see Ch19). [SYNTHESIS]

Bracing is **not** a substitute for ties on independent façade scaffolds that require tying (Ch11). Free-standing towers use brace packages + height/base limits instead of façade ties. [SYNTHESIS]

---

## 2. Angle & node rules (all configurations)

| Rule | Value | MCR |
|------|-------|-----|
| Brace angle from horizontal | **35°–55°** | 016 |
| Connection location | **Nearest to node points** | 016 / deck s57 |
| Coupler type (non-90°) | **Swivel** | 009 |

| Good [CITATION: PPTX-M1 s57] | Bad [CITATION: PPTX-M1 s57] |
|------------------------------|-----------------------------|
| Braces nearest **node points** | Far from nodes (mid-member only) |
| Angle inside **35°–55°** | Angle outside band (too flat / too steep) |

**Secondary note (not MCR):** CISRS/TG20 training quizzes often use **≤ 300 mm** from node. **Not adopted into MCR** until primary/TG20 citation attached. Do not teach 300 mm as Anabeeb Visible rule. [SYNTHESIS]

Prefer correct **Class B** fittings on load paths (**MCR-008/009/014**).

---

## 3. Independent vs free-standing / mobile — comparison matrix

| Attribute | Independent scaffold | Free-standing tower | Mobile tower |
|-----------|----------------------|---------------------|--------------|
| Geometry essence | **2** standards across width + run along length (**MCR-041**) | **4** standards only | **4** standards on casters |
| Lateral restraint to structure | **Ties** to permanent structure (Ch11) | **None** — free of structure | **None** — free of structure |
| Face bracing density | Both ends + every **5th** line of standards (**MCR-020**) | Brace **all four sides** (**MCR-057**) | Brace **all four sides** |
| Ledger bracing | **Alternate** lines of standards (**MCR-020**) | Included in four-side package | Included in four-side package |
| Plan braces | Façade patterns (single / double / continuous — deck s42); not the free-stand plan schedule | **Top, kicker, every third lift** (**MCR-057**) | Plan brace **bottom, top, intermediate lifts** (deck s40) [CITATION: PPTX-M1 s40] |
| Height / base limit | Not the free-stand H/B rule; height limited by design, ties, foundations | External ≤ **3×** min base (**MCR-017**); internal ≤ **4×** (**MCR-018**) | ≤ **4×** min base stationary; outriggers if exceeded (**MCR-019**) |
| Movement | Fixed location (no machine shift — **MCR-062**) | Fixed | Casters locked when working; **no persons/materials** while moving (**MCR-019, 056**) |
| Primary chapter detail | Ch13 §3 + Ch11 | Ch13 §1 | Ch13 §2 |

```
Markdown selection sketch (brace package):

Is scaffold free of permanent structure?
├── YES → Free-standing or mobile?
│         ├── Mobile (casters) → 4-side brace + plan bottom/top/intermediate
│         │                      + H ≤ 4× base + lock casters (MCR-019/057 family)
│         └── Free-stand → 4-side brace + plan top/kicker/every 3rd lift
│                          + H ≤ 3× ext / 4× int (MCR-017/018/057)
└── NO (independent / façade) → Face bracing ends + every 5th line
                                + ledger bracing alternate lines (MCR-020)
                                + ties per Ch11 (do not replace ties with braces alone)
```

---

## 4. Independent scaffold density (detail)

| Brace type | Rule | MCR |
|------------|------|-----|
| Face bracing | Both ends + every **5th** line of standards | 020 |
| Ledger bracing | Alternate lines of standards | 020 |

Façade patterns named on deck s42: **single / double / continuous** façade bracing — figures not embedded. [CITATION: PPTX-M1 s41–s42]

**Worked example — face brace lines [DERIVED]**

**Given:** Independent run with standards numbered 1…11 along façade.  
**Rule:** Face bracing at both ends + every 5th line (**MCR-020**).

| Line | Face brace required? |
|------|----------------------|
| 1 (end) | Yes |
| 2–4 | No (unless design denser) |
| 5 | Yes |
| 6–9 | No |
| 10 | Yes (every 5th from pattern 1,5,10…) |
| 11 (end) | Yes (end) |

If design or client requires denser bracing, design wins (**MCR-045, 044**). This table is training arithmetic only, not a substitute for TG20 primary figures.

---

## 5. Free-standing & mobile (detail)

### 5.1 Free-standing

- Brace **all four sides**.  
- Plan braces: **top, kicker, and every third lift** (**MCR-057**).  
- Height/base: external **3×**, internal **4×** (**MCR-017, 018**).  

[CITATION: PPTX-M1 s39]

### 5.2 Mobile

- Brace four sides.  
- Plan brace bottom, top, intermediate lifts (deck s40).  
- Height ≤ **4×** min base; outriggers if exceeded (**MCR-019**).  
- Lock casters; do not move occupied or with materials (**MCR-019, 056**).  

[CITATION: PPTX-M1 s40]

### 5.3 Worked example — free-standing external limit [DERIVED]

**Given:** Min base dimension = 1.5 m (narrowest plan width).  
**Max external free-standing height** = 3 × 1.5 = **4.5 m** (**MCR-017**).  
If required platform height = 6 m → not free-standing external without increasing base, tying to structure (→ independent + ties), or redesign.

**Plan brace lifts [DERIVED]:**  
For lifts numbered 0 (kicker) … n (top): plan braces at kicker, every 3rd lift, and top (**MCR-057**). Example 6 lifts: plan at 0, 3, 6 (and confirm top = highest working lift).

---

## 6. Couplers for braces

| Joint | Coupler | MCR |
|-------|---------|-----|
| Brace at non-90° to ledger/standard | **Swivel** | 009 |
| True 90° only (rare for diagonal) | Right-angle / double | 008 |
| Do not use putlog as structural brace joint | Putlog is non-load-bearing board connection | 010 |

Prefer Class B marked fittings; free-running lightly lubricated nuts (**MCR-014**).

---

## 7. Bad practices (bracing family)

| Practice | Why bad | Control |
|----------|---------|---------|
| Brace far from nodes | Bending of slender member; weak frame action | MCR-016 |
| Angle outside 35–55° | Inefficient force path / deck bad practice | MCR-016 |
| Missing end face braces on independent | Weak façade plane | MCR-020 |
| Free-stand without plan braces | Rack in plan | MCR-057 |
| Mobile moved while occupied | Overturn / fall | MCR-019 |
| Brace used as excuse to omit required ties | Independent still needs ties | Ch11; GAP-015 |

---

## 8. Verification Log

| Check | Result |
|-------|--------|
| Angle/density from MCR only | Yes |
| Independent vs free-stand matrix | Yes §3 |
| 300 mm node distance not promoted to MCR | Confirmed |
| Worked examples show arithmetic | Yes §4–5 |
| No invented primary clause numbers | Yes |
| Claude independent verify | Skipped per user direction |

## 9. Honest gaps

- Full TG20 brace figures not embedded.  
- Wind-load brace design method outside encyclopedia scope.  
- Continuous vs double façade figure details not transcribed from images.  
- Proprietary system diagonal rules → manufacturer manuals (**GAP-022**).  
- ≤300 mm node rule secondary only — not MCR.
