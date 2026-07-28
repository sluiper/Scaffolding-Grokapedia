# Generic Tube & Fitting — Manufacturer Summary (Stub)

**System class:** Traditional tube and coupler scaffold (EN 39 tubes + EN 74 fittings)  
**Status:** **Stub — multi-supplier class, not a single OEM**  
**Date:** 28 July 2026

---

## Manual status (honest)

| Item | In this repo? |
|------|----------------|
| Single “tube & fitting manufacturer” manual | **N/A** — many suppliers |
| Primary EN 39 / EN 74 / EN 12811 / BS 2482 PDFs | **No** (GAP-007) |
| NASC TG20 full good-practice guide | **No** (GAP-007) |
| Supplier certificates for Anabeeb stock tubes/couplers | **No** |

Working secondary harvest: `docs/research/packages/RP-STD/PUBLIC_HARVEST.md`, `RP-COMP/PUBLIC_HARVEST.md`.

---

## Seed / secondary values used in encyclopedia (all Drafting)

| Topic | Working value | MCR | Source class |
|-------|---------------|-----|--------------|
| Tube T&F | 48.3 mm OD × **4.0 mm** wall (Type 4) | MCR-001 | PPTX + EN39-sec |
| Base plate | 150 × 150 × 6 mm | MCR-003 | PPTX only |
| Double coupler Class B slip | **9.1 kN** | MCR-008 | EN74-sec (deck 9.4 discarded) |
| Swivel Class B (aligned) | **~9.1 kN** | MCR-009 | Secondary |
| Putlog | **0.53 kN** deck; non-load-bearing use | MCR-010 | PPTX HOLD |
| Sleeve | Unresolved multi-values | MCR-011 | Do not promote |
| Boards | BS 2482; 38 × 225 mm nominal | MCR-026 | PPTX + BS2482-sec |
| Duty UDL classes | 0.75 / 1.5 / 2.0 / 3.0 kN/m² (+ EN 5–6) | MCR-015 | EN12811-sec |

**Marking rule (MCR-014):** Couplers conform EN 74; marked brand, year, load class A or B.

---

## Brand-agnostic operational rules

1. Prefer **drop-forged** load-bearing double/swivel where training requires (PPTX).  
2. **Girder couplers in pairs** + check couplers (MCR-012, 042).  
3. **Stagger** sleeve joints; do not invent one sleeve SWL for exams (MCR-011).  
4. Never cut tube on site unless supervisor instructs (MCR-038).  
5. Defective materials out of service.

---

## When primary standards or supplier packs are added

- Attach EN/TG20 PDFs under `references/standards/` or controlled library path.  
- Add named supplier subfolders only if Anabeeb freezes preferred brands.  
- Promote MCR rows only per MCR promotion rules (primary citation + human gate).

Until then: **no single OEM manual in-repo**; T&F is standards-driven + training seed.
