# Chapter 01 — Introduction, Scope, Purpose & How to Use

**Status:** Production draft v0.2 (branch `draft/campaign-max-stack-v0.2`)  
**Encyclopedia version:** Scaffolding-Grokapedia v0.2.0-draft  
**Date:** 28 July 2026  

## MCR Mapping

| MCR-ID | Control used in this chapter |
|--------|------------------------------|
| MCR-043 | Anabeeb stricter rule gate |
| MCR-044 | Client matrix gate |
| MCR-045 | Engineering scaffold gate |
| MCR-046 | Fall trigger height ≥ 1.8 m |
| MCR-052 | Temporary platforms include scaffolding |
| MCR-053 | Planned SWP-019 placeholder |
| MCR-028 / 029 | Tag system referenced as user-facing SSOT entry |
| MCR-015 | Duty class must be known before use |

All rows above are **Drafting** until human + Claude promotion.

---

## 1. Purpose

This encyclopedia is a practical, high-depth, single-source reference for **industrial scaffolding** used by Arabian Pipeline & Services Co. Ltd. (**Anabeeb**) in the Eastern Province, Kingdom of Saudi Arabia — and for client sites (e.g. SABIC/Aramco) where Anabeeb erects, inspects, or uses scaffolds.

It exists so that:

1. Every safety-critical number lives in one place — the **Master Control Register (MCR)**.  
2. Training packs (`training/ATC-SCAF-*`) cite MCR IDs instead of free-floating constants.  
3. Dual-model production (Grok drafts → Claude verifies → Human gates) can scale without content drift.  

[SYNTHESIS] Same operating system as HPWJ-Grokapedia, domain-adapted for temporary works.

---

## 2. Scope

### 2.1 In scope

- Tube & fitting, Cuplok, and Ringlock-class systems used for access and working platforms.  
- Free-standing, mobile, independent, hung, and simple cantilever arrangements as described in Anabeeb training material.  
- Inspection, scaff-tag discipline, user pre-use checks, and fall protection interfaces.  
- Competency and training framework for ATC packs.  
- Mapping to Anabeeb HSE controls (Working at Height procedure; future Scaffold SWP).  

### 2.2 Out of scope (unless later extended)

- Permanent structural steel design (building codes).  
- Full structural analysis software methods (TG20/EN design beyond encyclopedia guidance).  
- Non-Anabeeb commercial product manuals as authority (they are **references**, not SSOT).  
- Rope access specialty work (pointer only; see WAH rope-access duties).  

### 2.3 Geographic / client posture

- **Anabeeb controlled procedures** and **client HSEMS** may be stricter than EN/BS/TG20.  
- Rule: **MCR-043 / MCR-044** — stricter Anabeeb or client requirement wins on that site.  
- International standards remain the technical backbone for materials and load classes.

---

## 3. Definitions (working)

| Term | Working definition |
|------|--------------------|
| Scaffold | Temporary safe platform or temporary structure for elevated work. [PPTX-M1 s5] [CITATION] |
| Scaffolder | Competent certified person who erects / modifies / dismantles scaffold. [PPTX-M1 s5] |
| Duty class | Service load class of the working platform (kN/m² UDL) per design / EN 12811 classes. See **MCR-015**. |
| Scaff-tag | Status indicator at access points (Green / Yellow / Red). See **MCR-028**. |
| MCR | Master Control Register — absolute SSOT for numbers and rules in this wiki. |
| Drafting / Visible | MCR status: proposed vs human-promoted after verification. |

Additional terminology: Chapter 07.

---

## 4. Why this document set is safety-critical

Scaffold failures kill and injure through:

1. **Falls from height** (missing edge protection, incomplete platforms, bad access).  
2. **Collapse** (overload, missing ties/bracing, bad foundations, wrong fittings).  
3. **Struck-by** (falling materials, tools, gin-wheel loads).  

Anabeeb Working at Height procedure applies fall protection when free-fall risk is **≥ 1.8 m** (**MCR-046**) and treats scaffolding as a temporary platform class (**MCR-052**). [CITATION: WAH-P010]

A wrong **coupler class**, **duty load unit**, or **tag meaning** taught in training can propagate into site practice. Therefore:

- Numbers are **MCR-first**.  
- Training decks are **not SSOT**.  
- Self-grading language is banned (AGENTS.md Rule 8).

---

## 5. Document hierarchy (authority order)

When sources conflict, apply this order on Anabeeb work unless a client mandate is stricter:

1. **Applicable law / host-country regulatory requirements**  
2. **Client HSEMS / permit conditions** (e.g. SABIC SHEMS cited in WAH) — **MCR-044**  
3. **Anabeeb controlled procedures** (WAH-P010 today; SWP-019 when issued — **MCR-053**) — **MCR-043**  
4. **This encyclopedia MCR (Visible rows)**  
5. **Primary international standards** (EN 39, EN 74, EN 12811, BS 2482, TG20, etc.)  
6. **Anabeeb training decks** (PPTX Module-1) — teaching aid only  
7. **Manufacturer manuals** for proprietary systems  
8. **Secondary web restatements** — research only, never sole basis for Visible without human risk acceptance  

[SYNTHESIS]

---

## 6. How to use the encyclopedia

### 6.1 For field supervisors / inspectors

1. Confirm scaffold **tag** at every access (**MCR-028 / MCR-029**).  
2. Confirm **duty class** and intended use match the work (**MCR-015**).  
3. Use templates under `templates/` once human-approved.  
4. Look up any numeric limit in **MCR**, not in memory of a slide.

### 6.2 For trainers (ATC)

1. Build lesson plans from chapter outlines + Module-1 topics.  
2. Exam items must **cite MCR-IDs**.  
3. Do not print free-floating SWL/load constants on slides once MCR is frozen.  
4. Packs under `training/` stay stubbed until high-risk MCR rows are Visible or human pilot-freezes them.

### 6.3 For encyclopedia authors (Grok / Claude / Human)

1. Read `AGENTS.md`, `WORKFLOW.md`, `PROCESS.md`.  
2. New control → new or updated **MCR row (Drafting)** in the same delivery package.  
3. Draft on `draft/*` branches.  
4. Claude Verification Report before human merge/promotion.  
5. Tag claims `[CITATION]`, `[DERIVED]`, or `[SYNTHESIS]`.  
6. Mark internal needs `[INTERNAL GAP – human source required]`.

### 6.4 Claim tagging (mandatory)

| Tag | Meaning |
|-----|---------|
| [CITATION] | Directly from a named source (procedure, standard, deck slide) |
| [DERIVED] | Calculated or unit-corrected with shown work |
| [SYNTHESIS] | Combined judgment from multiple sources; lowest authority |

Example unit fix: PPTX “0.75 N sqm” interpreted as **0.75 kN/m²** because N/m² is physically absurd for scaffold service loads and matches EN 12811 Class 1. [DERIVED — see MCR-015 / T1 truth pass]

---

## 7. Repository map

| Path | Contents |
|------|----------|
| `MASTER_CONTROL_REGISTER.md` | SSOT numbers & rules |
| `docs/01`–`20` | Encyclopedia chapters |
| `docs/appendices/` | Field cards (after freeze) |
| `docs/research/` | Source inventories & harvest packages |
| `docs/audit/` | Truth campaigns & verification |
| `references/` | Standards summaries, WAH extract, source paths |
| `templates/` | Checklists & tag cards |
| `training/` | ATC-SCAF-* packs |
| `AGENTS.md` / `WORKFLOW.md` / `PROCESS.md` | Dual-model OS |

---

## 8. Current maturity (honest)

| Area | State |
|------|--------|
| Process OS | Locked |
| MCR | 54 Drafting rows; **0 Visible** |
| Chapter 01 | This production draft |
| Chapters 02–20 | Stubs |
| Anabeeb WAH | Extracted to reference summary |
| Anabeeb Scaffold SWP-019 | **Not on disk** (planned New) |
| Primary EN/BS PDFs | Not purchased — secondary harvest only |
| Training exams | Not started (correct gate) |

---

## 9. Worked example — resolving a conflict

**Problem:** Module-1 slide states Class B double coupler SWL **9.4 kN**; another slide states **9.1 kN**.

**Method:**

1. Log both in MCR conflict list.  
2. Harvest secondary EN 74-1 trade restatements → **9.1 kN Class B slip**.  
3. Adopt **9.1 kN** in **MCR-008** (Drafting).  
4. Demote 9.4 to historical deck note.  
5. **Do not** mark Visible until primary EN 74-1 table or human accepts secondary risk + Claude re-derives.

[DERIVED process — T1 truth pass 28 July 2026]

---

## 10. Verification Log

| Check | Result |
|-------|--------|
| MCR IDs cited exist in MASTER_CONTROL_REGISTER.md | Yes (v0.2.0-draft) |
| No free-floating exam constants introduced | Yes |
| Hierarchy states Anabeeb/client win when stricter | Yes §5 |
| Honest gaps stated | Yes §8 |
| Numbers dual-model (Claude) verified | **Not yet** — Grok draft only |
| Human Drafting → Visible | **None** |

---

## 11. Honest gaps

1. Dedicated Anabeeb scaffold SWP (`AIMS-L3-HSE-SWP-019`) not available — **GAP-001 / MCR-053**.  
2. Primary standards PDFs not in library — **GAP-007**.  
3. Aramco scaffold-specific matrix not loaded — **GAP-002**.  
4. Wind numeric threshold incomplete in WAH extract — **GAP-009**.  
5. This chapter awaits **Claude Verification Report** and human review before merge-as-authoritative.

---

## 12. Next chapters

- **Ch02** Fundamentals & major risks  
- **Ch03** Safety, permits, PPE (WAH + Module-1)  
- **Ch05–06** Components & couplers (consume T1 coupler decisions)  
- **Ch17** Tags & inspection (MCR-028/029)  
- **Ch20** Competency → unlock training pack builds  

---

*End of Chapter 01 production draft.*
