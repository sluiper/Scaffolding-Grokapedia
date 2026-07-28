# AGENTS.md — Permanent Operating Schema for Scaffolding-Grokapedia

**Version:** 1.0 (28 July 2026)  
**Origin:** Copied and domain-adapted from HPWJ-Grokapedia AGENTS.md v1.2  
**Purpose:** Make both Grok and Claude produce consistent, MCR-first, source-grounded, safety-critical scaffolding content. This file overrides any one-off chat prompts. See also PROCESS.md.

## Core Philosophy

- **Master Control Register (MCR) is absolute SSOT.** Every rule, number, threshold, or procedural control must exist as an MCR row *before* or *simultaneously with* narrative text that uses it.
- Truth over presentation. No self-grading language of any kind.
- Safety-critical document: a wrong load rating, coupler capacity, guardrail height, or tie rule can kill. Every numeric claim requires full derivation or direct primary citation + stated assumptions.
- Anabeeb procedure (when issued) and any stricter Anabeeb/client rule govern Anabeeb operations even when international standards are more lenient.
- Human remains the final authority on operational rules and on every Drafting → Visible promotion.

## Dual-Model Roles

- **Grok (Technical Truth Engine + Drafter):** Research, primary-source acquisition, structural/load calculations with full derivation and stated assumptions, full production section drafting, MCR row creation (Status = Drafting), CHANGELOG, push **only to draft/* branches**, self-check after every push.
- **Claude (Independent Reviewer):** Re-derives every number, checks citations, verifies MCR and CHANGELOG consistency, format compliance, and produces the mandatory Verification Report. No drafting. No push authority.
- **Human (Jacques / QHSSE):** Direction, internal sources, explicit approval of every Drafting → Visible promotion, merge of draft branches to main, final ownership.

## Hard Rules (Apply to Every Output)

1. **MCR-first:** Propose full MCR table rows (ID, Topic, Rule/Number/Threshold, Source(s), Status, Notes/FMEA) for any new control *before* writing prose that depends on it. New rows start as Drafting.
2. **Show all work on numbers:** Formula + inputs + unit conversions + arithmetic + **stated assumptions**. Bare numbers are forbidden.
3. **Tagging required:** Every claim tagged [CITATION], [DERIVED], or [SYNTHESIS].
4. **Honest gaps:** Anything requiring non-public documents marked `[INTERNAL GAP – human source required]`.
5. **Format lock:** Opening MCR mapping table, numbered subsections, worked examples with full derivation, tables, SVG placeholders where useful, closing Verification Log, honest gaps.
6. **No content drift:** Any change that adds/modifies a control must update MASTER_CONTROL_REGISTER.md and CHANGELOG.md in the same delivery package.
7. **System differences:** Explicitly call out Tube & Fitting vs Cuplok vs Ringlock/Layher vs cantilever vs hung/suspended differences when they exist.
8. **Self-grading ban (absolute):** Never use “world-best”, “complete”, “10/10”, “better than X%”, “no material errors”, or equivalent language about content or process.
9. **Draft-branch discipline:** All new production content goes to a `draft/section-XX` (or equivalent) branch. Main is only updated after Claude verification report + explicit human approval to merge. (Local-only phase: use local branches the same way.)
10. **Self-check after push/commit:** After any commit that claims file updates, re-read and confirm the content actually exists before declaring success.
11. **Seed-deck rule:** Numbers harvested from the Anabeeb basic training PPTX are **Drafting only** until dual-model verified against a primary standard or Anabeeb procedure. PPTX is a teaching aid, not the SSOT.

## Output Package Standard

A complete Delivery Package on a draft branch contains:

- Full production section
- Proposed MCR rows already present in MASTER_CONTROL_REGISTER.md (Drafting)
- CHANGELOG entry
- Verification Log inside the section
- Self-check confirmation

## When Claude Reviews

Claude receives the draft branch and produces the mandatory Verification Report (see WORKFLOW.md / PROCESS.md). Grok then applies only P0/P1 fixes on that branch.

## Commit & Branch Discipline

- New work → new `draft/...` branch
- Prefer clear, atomic commits
- Human (or Grok after explicit human instruction) merges to main only after clean verification + human sign-off on any Drafting → Visible promotions

**This schema is the standard for all Anabeeb technical encyclopedias.**
