# Chapter 21 — Regulatory & Client Matrix

**Status:** Production draft v0.6 (deepen pass)  
**Version:** v0.5.1-draft (28 July 2026)  
**Canonical companion:** `references/standards/21_Regulatory_and_Client_Matrix.md`  
**Branch:** `draft/campaign-max-stack-v0.2`

## MCR Mapping

| MCR-ID | Control | Status |
|--------|---------|--------|
| MCR-043 | Anabeeb stricter rule gate | Drafting |
| MCR-044 | Client matrix gate | Drafting |
| MCR-015 / 054 | Duty classes TG20/EN vs Aramco CSM-II | Drafting |
| MCR-021 / 021a | Guardrail Anabeeb vs training floor | Drafting |
| MCR-046–050 | WAH fall protection suite | Drafting |
| MCR-053 | Planned SWP-019 | Drafting placeholder |

---

## 1. Authority layers (Anabeeb work)

| Priority | Layer | Examples | In-repo status |
|----------|-------|----------|----------------|
| 1 | Host law / client HSEMS | Aramco, SABIC SHEMS | Partial — GAP-002/003 |
| 2 | Anabeeb controlled procedures | WAH-P010; **SWP-019 (missing)** | WAH yes; SWP-019 **GAP-001** |
| 3 | International product/design standards | EN 39, EN 74, EN 12811, BS 2482, TG20 | Secondary harvest only |
| 4 | Training decks | Module-1 PPTX | Seed only — not SSOT |

[SYNTHESIS] Same pattern as family standard / HPWJ client matrix thinking.

When layers conflict: **stricter applicable rule wins** on that site (MCR-043 / MCR-044).

---

## 2. Duty class comparison (do not silently merge)

| System | Access / very light | Light | Medium / general | Heavy / special |
|--------|---------------------|-------|------------------|-----------------|
| EN 12811 / TG20 (MCR-015) | **0.75** | **1.5** | **2.0** | **3.0** (+ EN 4.5 / 6.0) |
| Aramco CSM-II via Module-1 (MCR-054) | — | **1.2** | **2.4** | **&gt;2.4** special |

**Units:** kN/m² (PPTX “N sqm” corrected in T1).  

**GAP-019:** no written interface procedure when both systems are cited on one site — human/client required.

[CITATION] MCR rows; deck for Aramco numbers only.

---

## 3. Fall protection sample (Anabeeb vs training)

| Topic | Anabeeb WAH (prefer on Anabeeb sites) | Module-1 training | MCR |
|-------|----------------------------------------|-------------------|-----|
| Trigger height | ≥ **1.8 m** | Major-risk narrative | MCR-046 |
| Top rail | **1.1 m ± 8 cm** (1.02–1.18 m) | 0.950–1.150 m | MCR-021 / 021a |
| Midrail | ≥ **53 cm**; strength 666 N top/mid 890/666 N | — | MCR-021 |
| Tags | Green / Yellow / Red + access-point display | Same family + operational detail | MCR-028 |
| Tool lanyards | **Mandatory** | Listed | MCR-047 |
| Anchorage | ≥ **22.2 kN** per person | — | MCR-050 |

[CITATION] WAH-P010 extract; PPTX for training band.

---

## 4. Document status matrix

| Document | Held? | Gap |
|----------|-------|-----|
| Anabeeb AIMS-L3-HSE-P-010 WAH | **Yes** (summary) | Wind number incomplete GAP-009 |
| Anabeeb AIMS-L3-HSE-SWP-019 Scaffold | **No** — master list “New” | **GAP-001** |
| Aramco CSM-II full text | No — duty via PPTX only | GAP-002 |
| SABIC SHEMS 08.09 | Cited in WAH only | GAP-003 |
| EN 39 / 74 / 12811 / BS 2482 / TG20 primary PDFs | No | GAP-007 |
| Manufacturer system manuals (Layher/Cuplok) | No | GAP-022 |

---

## 5. How to use this chapter

1. Start every site with **which duty table** applies (MCR-015 vs MCR-054).  
2. Apply Anabeeb guardrail/tag/WAH numbers on Anabeeb operations.  
3. Do not promote secondary EN numbers to Visible without primary PDF or human freeze.  
4. Full tables remain in `references/standards/21_Regulatory_and_Client_Matrix.md` — keep one place for detailed comparison edits.

---

## Verification Log

| Date | Reviewer | Scope | Result |
|------|----------|-------|--------|
| 28 Jul 2026 | Grok | Duty figures match MCR-015/054; WAH heights match MCR-021 | Self-check only |

## Honest Gaps

GAP-001, 002, 003, 007, 009, 019 still open. **0 Visible.**
