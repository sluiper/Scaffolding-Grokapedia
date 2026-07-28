# RP-CLI — Client Matrices Source Inventory

**Status:** Partial — Aramco CSM-II from training deck only  
**Date:** 28 July 2026  
**Parent:** `docs/research/inventory/MASTER_SOURCE_INVENTORY.md`  
**Policy:** Client rules may override baseline when **stricter** (MCR-044). Primary client PDFs human-gated.

---

## 1. Sources in hand

| Source ID | Document | Location | Type | Harvest status |
|-----------|----------|----------|------|----------------|
| SRC-LOC-SCAF-003 | Aramco CSM-II **as quoted** on Module-1 deck | `references/source_materials/ARAMCO_CSM_II_From_Training_Deck.md` | Secondary client extract | **Partial** |
| SRC-ANB-PPTX-001 | Module-1 slides 38, 44 (duty + cantilever 3 m) | Desktop PPTX | Training deck quoting client | Harvested into MCR-054, 058 |
| SRC-ANB-WAH-P010 | Working at Height — cites **SABIC SHEMS 08.09** for fall protection | `references/standards/…Summary.md` | Controlled Anabeeb | Partial client pointer only |
| SRC-ANB-OPS-SCAF | Anabeeb scaffolding SWP-019 | — | Controlled procedure | **Missing** (GAP-001) |
| SRC-ARAMCO-SCAF | Full Aramco CSM / SAES scaffold text | — | Client primary | **[INTERNAL GAP]** (GAP-002) |
| SRC-SABIC-SCAF | SABIC scaffold-specific beyond SHEMS 08.09 | — | Client primary | **[INTERNAL GAP]** (GAP-003) |

---

## 2. Aramco CSM-II — partial content from PPTX (only)

> Full Saudi Aramco Construction Safety Manual (CSM) **not present** on this Mac.  
> Claim tag: `[CITATION] Anabeeb Module-1 PPTX quoting Aramco CSM-II — secondary; verify against primary CSM when held`

### 2.1 Duty load ratings (slide 38) → **MCR-054**

| Duty (deck label) | Load (interpreted **kN/m²**) | Purpose (deck) |
|-------------------|------------------------------|----------------|
| Light | **1.2** | Painting, inspection, cleaning |
| Medium | **2.4** | Building works |
| Special | **> 2.4** | Masonry, concrete works |

**Unit note:** Deck text “N sqm” treated as **kN/m²** (same unit fix as EN/TG20 table on same slide). Aligns ~25/50 psf industry mapping at secondary level only.

### 2.2 Cantilever platform limit (slide 44) → **MCR-058**

- Cantilever platform **≤ 3 m** without scaffold design; beyond **requires design** (deck labels **Aramco CSM-II**).  
- Related deck geometry (not always labelled CSM in same sentence): raker **65°–75°**; raker **single tube — no splicing** → MCR-032 / MCR-059.

### 2.3 Free-standing / mobile ratios on deck

| Type | Ratio (deck) | Labelled CSM? |
|------|--------------|---------------|
| External free-standing | ≤ **3 ×** min base | Not always labelled CSM |
| Internal free-standing | ≤ **4 ×** min base | Not always labelled CSM |
| Mobile tower | ≤ **4 ×** min base | Not always labelled CSM |

**MCR-017–019** retain PPTX ratios as Drafting; confirm against primary CSM / TG20 before Visible.

---

## 3. Dual-system interface (critical gap)

| System | Classes | MCR |
|--------|---------|-----|
| EN 12811 / TG20-style | 0.75 / 1.5 / 2.0 / 3.0 (+ 4.5 / 6.0 EN) | MCR-015 |
| Aramco CSM-II (deck) | 1.2 / 2.4 / >2.4 | MCR-054 |

**GAP-019:** Interface procedure for same site when both systems appear (e.g. training table side-by-side) is **missing**.  
**Site rule (Drafting synthesis):** Use **client-specified** class on that site; never mix labels; Anabeeb may be stricter (MCR-043/044).

---

## 4. Explicit gaps — what primary CSM must still supply

When human obtains full CSM / CSM-II PDF, extract at least:

1. Scaffold inspection frequency and competent person definition  
2. Tag colours and validity (may differ from Anabeeb green/yellow/red)  
3. Tie spacing / wind / sheeting rules  
4. Full duty class definitions and simultaneous use rules  
5. Temporary works design thresholds  
6. Multi-craft interfaces (lifting, hydrojetting, SIMOPS)  

Until then: **GAP-002 remains OPEN**; this package is best local proxy only.

---

## 5. SABIC / other clients

| Client | What we have | Gap |
|--------|--------------|-----|
| SABIC | WAH cites SHEMS **08.09** fall protection | Scaffold-specific still GAP-003 |
| Other KSA | None in-repo | Human source required |

---

## 6. Encyclopedia / training touchpoints

| Artefact | Use of RP-CLI content |
|----------|----------------------|
| Ch09 Duty Classes | Dual tables MCR-015 vs 054 |
| Ch21 Regulatory & Client Matrix | Client gate MCR-044 |
| Appendix A | Side-by-side quick card |
| ATC-SCAF-BASIC / SUP / INSP exams | Duty dual awareness items |
| `ARAMCO_CSM_II_From_Training_Deck.md` | Canonical partial extract |

---

## 7. Inventory log

| Date | Agent | Note |
|------|-------|------|
| 28 Jul 2026 | Grok | Expanded stub → Aramco partial + gap list; no primary CSM claimed |
| Pending | Human | Drop full CSM PDF path into MASTER_SOURCE_INVENTORY when available |
