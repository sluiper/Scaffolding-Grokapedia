# Chapter 09 — Duty Classes & Load Ratings

**Status:** Production draft v0.4  
**Date:** 28 July 2026  

## MCR Mapping

**MCR-015** (EN/TG20), **MCR-054** (Aramco CSM-II deck), **MCR-044**, **MCR-045**, GAP-019.

---

## 1. Why duty class matters

Overloading is a primary collapse pathway. The **marked / designed class** is the hard limit for people + materials on platforms. Never “upgrade” by adding boards alone without design.

## 2. EN 12811-1 classes (secondary) — MCR-015

| Class | UDL q1 (kN/m²) | Module-1 purpose label |
|-------|----------------|------------------------|
| 1 | **0.75** | Very light — access & walkway |
| 2 | **1.5** | Light — paint, inspection, cleaning |
| 3 | **2.0** | General/medium — building works |
| 4 | **3.0** | Heavy — masonry, concrete |
| 5 | **4.5** | (EN; not in Module-1 table) |
| 6 | **6.0** | (EN; not in Module-1 table) |

**Unit fix [DERIVED]:** Deck “N sqm” → **kN/m²** (T1). ≈ kg/m² ≈ 100 × kN/m² for rough teaching only (0.75 kN/m² ≈ 75 kg/m²).

## 3. Aramco CSM-II as taught — MCR-054

| Class | UDL (kN/m² interpreted) | Purpose (deck) |
|-------|-------------------------|----------------|
| Light | **1.2** | Paint, inspection, cleaning |
| Medium | **2.4** | Building works |
| Special | **> 2.4** | Masonry, concrete |

Rough imperial mapping often used in industry teaching: ~25 / 50 psf ≈ 1.2 / 2.4 kN/m² — **not a substitute for client text** (**GAP-002**).

## 4. Dual-system interface (GAP-019)

On mixed sites:

1. Identify **which system the permit/design uses**.  
2. Do not label a scaffold with both classes without conversion note.  
3. When in doubt, use the **stricter / client-specified** limit (**MCR-044**).  

## 5. Beyond UDL

EN 12811 also addresses concentrated and partial-area loads (secondary design notes). Heavy point loads (pallets, plant) can govern even if average UDL “looks fine” — engineering scaffold if needed (**MCR-045**).

## 6. Worked example [DERIVED]

Platform 2.0 m × 1.2 m = 2.4 m².  
Class 3 at 2.0 kN/m² → max UDL capacity ≈ 2.4 × 2.0 = **4.8 kN** total uniform.  
Two workers ~1 kN each + tools: order-of-magnitude OK for Class 3 if materials not stored; **not** a substitute for design bay tables.

## 7. Verification Log

| Check | Result |
|-------|--------|
| Both systems tabulated | Yes |
| Primary EN table | GAP-007 |
| Claude | Skipped |

## 8. Honest gaps

No TG20 compliance sheet library; no Aramco full CSM PDF.
