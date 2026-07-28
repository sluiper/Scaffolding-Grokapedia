# Anabeeb Scaffolding Encyclopedia (Grokapedia)

**Version:** v0.1.0-scaffold  
**Status:** Local scaffold only — process locked; structure seeded; content not yet production  
**Last Updated:** 28 July 2026  
**Location:** `~/projects/Scaffolding-Grokapedia` (local first; no remote required yet)

## Purpose

A practical, high-depth, single-source reference for industrial scaffolding operations, safety, components, inspection, training, and best practices, built for Anabeeb use in the Eastern Province, KSA.

Same operating system as **HPWJ-Grokapedia**: Master Control Register (MCR) as SSOT, dual-model Grok/Claude workflow, draft-branch discipline, human gate on Drafting → Visible.

## Current Status (Honest)

| Area | State |
|------|--------|
| Repo + process files (`AGENTS` / `WORKFLOW` / `PROCESS`) | Live |
| Encyclopedia chapter map | Live (`docs/00_Encyclopedia_Structure.md`) |
| Master Control Register | **Seeded Drafting** from Anabeeb basic training module — numbers not yet dual-model verified against primary standards |
| Production chapter prose | Not started |
| Training packs | Index + course stubs only |
| Remote / GitHub | Not configured (local-first by design) |

## Source Material (Human-Gated)

Primary seed deck (local copy under `references/source_materials/`):

- **Anabeeb — New Scaffolder’s Basic Training Program Module-1**  
  Source path: `Desktop/nebosh/scaf/Scaffolding basic training module.pptx` (66 slides)

Additional sources to integrate later (many internal / paid):

- BS EN 39 / BS 1139 (tubes), EN 74 (couplers), BS 2482 (boards)
- NASC / TG20 (tube & fitting good practice — UK)
- OSHA 1926 Subpart L (US) — comparative only unless client requires
- Aramco / SABIC / client scaffolding procedures — **[INTERNAL GAP]**
- Anabeeb scaffolding procedure(s) if issued — **[INTERNAL GAP]**
- CISRS / TVTC / client competency schemes

## How to Use

1. **`MASTER_CONTROL_REGISTER.md`** — single source of truth for every rule/number.
2. **`AGENTS.md` + `WORKFLOW.md` + `PROCESS.md`** — how Grok / Claude / Human work.
3. **`docs/`** — encyclopedia chapters (stubs → production drafts).
4. **`templates/`** — checklists, scaff-tag cards, inspection forms.
5. **`training/`** — ATC training packs (after MCR freeze).
6. **`references/`** — standards summaries, manufacturers, seed materials.

## Next Steps (Recommended Order)

1. Human supplies internal Anabeeb scaffold procedure + any client matrices (Aramco/SABIC).
2. Grok: public harvest of EN 39 / EN 74 / BS 2482 / NASC TG20 open notes → research packages.
3. Dual-model truth pass on every Drafting MCR row before any training exam content.
4. Promote core MCR rows Visible → open `draft/section-01` and write Chapter 1.
5. Only then build full ATC-SCAF-* packs (same gate used on HPWJ).

## Relationship to HPWJ-Grokapedia

| | HPWJ | Scaffolding |
|--|------|-------------|
| Domain | High-pressure water jetting | Temporary works / access scaffold |
| Process | Dual-model MCR-first | **Same** (copied) |
| Training codes | ATC-HPWJ-* | ATC-SCAF-* |
| Maturity | v8.6+ operational | v0.1 scaffold |

**This is a working scaffold, not a finished encyclopedia.**
