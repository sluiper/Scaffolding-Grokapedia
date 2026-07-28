# Chapter 11 — Scaffold Ties

**Status:** Production draft v0.5  
**Date:** 28 July 2026  
**Branch:** `draft/campaign-max-stack-v0.2`  
**Seed:** PPTX-M1 s45–s47, s58; Appendix I  

## MCR Mapping

| MCR-ID | Role in chapter |
|--------|-----------------|
| MCR-012 | Girder couplers always in pairs |
| MCR-034 | No double couplers on structural sections; girder pairs + check |
| MCR-042 | Check (safety) couplers on tie connections |
| MCR-040 | Hung/underhung trapze context (not façade tie schedule) |
| MCR-060 | Only scaffolders modify (includes tie removal) |
| MCR-016 | Node-point connection discipline (shared with braces) |
| MCR-045 | Engineered tie schedule when outside standard config |
| MCR-029 | Inspection/approval before use (ties as part of structure) |

**Open gap:** GAP-015 — no numeric tie-load / spacing table in Module-1.

---

## 1. Purpose of ties

Ties connect the scaffold to a **permanent structure** so the scaffold cannot move away (or sway excessively). Tie duty is the **tension (and often push/pull) load** each tie must resist. Duty depends on **vertical & horizontal spacing** and frequency. [CITATION: PPTX-M1 s46]

**GAP-015:** No numeric tie-load or spacing table in Module-1 harvest. **Do not invent kN values or primary-standard clause numbers** for tie spacing. Use design/TG20 primary tables when loaded, or engineered schedule (**MCR-045**).

---

## 2. Tie types (Module-1)

| Type | Description | When used (training logic) |
|------|-------------|----------------------------|
| **Box tie** | Tubes & couplers tightly fixed around **all sides** of column or I-beam | Preferred when geometry allows full enclosure |
| **Lip tie** | L-shaped arrangement when full box not possible | Incomplete-box substitute |
| **Through tie** | Tie tubes through window/opening | Building opening available |
| **Drill / cast-in tie** | Anchors drilled into building or cast in | Competent install into structure |

Scaffold is tied with tie tubes connected to posts or ledgers with **right-angle couplers** (tube-to-tube). [CITATION: PPTX-M1 s46–s47]

**Field card:** Appendix I — Tie Types Quick Reference.

```
SVG placeholder: box-tie around column (plan) vs lip-tie L-shape
```

---

## 3. Connection quality — good vs bad

### 3.1 Structural section / girder connections

| Good [CITATION: PPTX-M1 s58] | Bad [CITATION: PPTX-M1 s58] |
|------------------------------|-----------------------------|
| Girder couplers **in pairs** | Girder coupler single / not paired |
| **Check (safety) couplers** fitted | No check coupler |
| Girder hardware for structural sections | **Double / right-angle couplers on structural sections** |

**Controls:** **MCR-012, MCR-034, MCR-042.**

### 3.2 Tube-to-tube façade ties

| Good | Bad |
|------|-----|
| Right-angle couplers as designed for tube-to-tube ties | Wrong coupler class / unmarked fittings |
| Tie tube near **node point** of standard/ledger | Tie far from node; flexible mid-span only |
| Intact permanent structure / sound anchor | Cracked masonry, loose cast-in, unknown embedment |
| Ties left in place per design during use | End-user or other trade removes ties for “access” |

Node discipline is the same family as bracing (**MCR-016** “nearest to node points”). [SYNTHESIS]

### 3.3 Hung / underhung context (not a façade schedule)

When scaffold hangs from I-beams, uprights form a **tie around the section**; trapeze assist ≤ **600 mm** from ledger (**MCR-040**). That is a **hang configuration**, not a façade box-tie spacing schedule — but **coupler pair + check** discipline still applies (**MCR-012, 042**). [CITATION: PPTX-M1 s43, s58]

---

## 4. Inspection checklist — ties

Use during erection progressive checks, handover, and periodic inspection (**MCR-029**). Mark fail → stop use / red tag path as appropriate (**MCR-028**).

| # | Check | Pass criteria | Fail action | MCR |
|---|-------|---------------|-------------|-----|
| T1 | Tie present where design / standard config requires | No missing run of untied scaffold that should be tied | Stop; scaffolders reinstate; no end-user “temporary remove” | 060, 045 |
| T2 | Tie type matches geometry | Box / lip / through / drill as appropriate | Redesign or add correct type | deck s46–47 |
| T3 | Tube-to-tube couplers | Right-angle as designed; free-running nuts; EN 74 marked | Replace fittings | 014, 008 |
| T4 | Structural section fixings | Girder **pairs** + **check** couplers | Correct hardware before load | 012, 034, 042 |
| T5 | Node proximity | Connection nearest practical node of post/ledger | Relocate / add stiffening as scaffolder plan | 016 |
| T6 | Permanent structure / anchor condition | No obvious crack, corrosion, pull-out, missing cast-in | Engineering / competent person; red tag if unsafe | 029 |
| T7 | Check couplers present | Safety couplers on tie joints as required | Fit check couplers | 042 |
| T8 | No unauthorised removal | Ties match last approved configuration | Red tag; only scaffolders restore | 060, 028 |
| T9 | Underhung only: trapeze | Assist tube ≤ **600 mm** from ledger | Correct geometry | 040 |
| T10 | Tag reflects status | Green/Yellow/Red consistent with incomplete ties | Do not green-tag incomplete | 028, 029 |

**Quantitative spacing / kN checks:** **not available** until GAP-015 closed. Inspectors must not invent “every X m” rules from memory. [SYNTHESIS]

---

## 5. Operational rules [SYNTHESIS]

1. Do not remove ties without scaffolders and a temporary stability plan (**MCR-060**).  
2. Prefer ties near **node points** (**MCR-016** family).  
3. Report damaged anchors/ties → red tag / stop use as appropriate (**MCR-028**).  
4. Engineered scaffolds: follow design tie schedule over training generic (**MCR-045**).  
5. Never use double couplers as the structural-section connection (**MCR-034**).  
6. Girder couplers always in pairs; add check couplers (**MCR-012, 042**).

---

## 6. Worked example — good vs bad I-beam tie [DERIVED]

**Given:** Independent scaffold tied to a steel column (I-section).  
**Required (deck good practice):** box or equivalent enclosure; on steel flanges use **girder couplers in pairs** with **check couplers**.

| Arrangement | Assessment | MCR |
|-------------|------------|-----|
| A: Single girder coupler one flange only | **Fail** — not in pairs | 012 |
| B: Two girder couplers opposing + check | **Pass** (geometry permitting) | 012, 042 |
| C: Double (right-angle) couplers clamped on flange | **Fail** — structural section rule | 034 |
| D: Full tube box around column + RA couplers tube-to-tube | **Pass** if tight and nodes OK | deck box-tie |

No kN capacity claimed — GAP-015.

---

## 7. Failure modes (tie family) [SYNTHESIS → Ch19]

| Mechanism | Effect | Control family |
|-----------|--------|----------------|
| Missing ties | Overturn / sway / progressive collapse | Density/design (GAP-015), MCR-045 |
| Wrong coupler on steel | Slip of joint under load | MCR-034, 012 |
| No check coupler | Progressive slip after primary slips | MCR-042 |
| Unauthorised removal | Instant loss of stability | MCR-060, 028 |
| Bad anchor embedment | Pull-out | Competent install; inspection T6 |

---

## 8. Verification Log

| Check | Result |
|-------|--------|
| No invented tie kN or spacing table | Yes — GAP-015 explicit |
| Good/bad table from deck s58 | Yes §3 |
| Inspection checklist present | Yes §4 (T1–T10) |
| Coupler rules cross-linked | MCR-012, 034, 042 |
| Worked example without fake capacities | Yes §6 |
| Claude independent verify | Skipped per user direction |

## 9. Honest gaps

- TG20 / NASC quantitative tie spacing and load tables not loaded (**GAP-015**).  
- Aramco / client-specific tie matrices not in-repo (**GAP-002/003**).  
- Drill-in anchor product SWL tables not in encyclopedia.  
- SWP-019 may add Anabeeb-specific tie inspection frequency (**GAP-001**).  
- Illustrated deck figures not embedded as photos.
