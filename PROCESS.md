# PROCESS.md — Dual-Model + Human Team Operating System

**Purpose:** Living record of how Grok + Claude + Human (Jacques) work together on safety-critical technical encyclopedias. Copied from HPWJ-Grokapedia and applied to Scaffolding.

**Last Updated:** 28 July 2026  
**Status:** Locked at process level; encyclopedia content at v0.1 scaffold

---

## Core Principles (Non-Negotiable)

1. **Truth over speed.** A wrong number can injure or kill. Every numeric claim requires full derivation or primary citation + stated assumptions.
2. **MCR is absolute SSOT.** No control exists until it has a row in MASTER_CONTROL_REGISTER.md.
3. **Human remains the final gate** on anything that changes operational rules or promotes Drafting → Visible.
4. **No self-grading** — not of encyclopedia content, and not of the workflow itself.
5. **Independent verification is the point of the system**, not a failure when it catches mistakes.
6. **Content-drift prevention** is enforced by both models and by draft-branch discipline.
7. **Training decks are not SSOT.** Anabeeb PPTX Module-1 is seed material. Primary standards / controlled procedures win conflicts.

---

## Current Role Split

| Role | Responsibility | Authority |
|------|----------------|-----------|
| **Grok** | Research, full production drafting, calculations with shown work, MCR row creation (Drafting), CHANGELOG, push/commit to **draft/* branches only**, self-check | draft/* only |
| **Claude** | Independent verification using mandatory report template, re-derivation of every number, MCR/CHANGELOG consistency, P0/P1/P2 fixes list | Review only — no drafting, no push |
| **Human (Jacques)** | Direction, internal Anabeeb/client sources, final approval of every Drafting → Visible promotion, merge to main, overall ownership | Final gate |

---

## Standard Delivery Loop

1. **Human** sets priority + supplies any internal material.
2. **Grok** produces a complete Delivery Package on a new branch `draft/section-XX` (or `draft/topic-name`).
3. **Claude** runs the **mandatory Verification Report** against the draft branch.
4. **Grok** applies only P0 and P1 fixes on the same draft branch.
5. **Human** reviews, explicitly approves any Drafting → Visible promotions, and merges to main.

---

## Mandatory Claude Verification Report Template

```markdown
## Claude Verification Report — Section [XX] / [Topic]

**Branch reviewed:** draft/...
**Date:**

### 1. Numbers re-derived
- [Claim]: recompute shown → Pass / Fail + notes

### 2. Citations checked
- [Source]: exists? matches claim? any flags?

### 3. MCR consistency
- Are every cited MCR-IDs actually present in MASTER_CONTROL_REGISTER.md on this branch? Y/N
- Status of proposed rows correct? Y/N

### 4. CHANGELOG consistency
- Is the claimed CHANGELOG entry actually present and accurate? Y/N

### 5. Format compliance
- Matches AGENTS format (MCR mapping table, worked examples, Verification Log, system differences where relevant, honest gaps)? Y/N + notes

### 6. Remaining gaps
- List any INTERNAL GAPs or unshown work still present

### 7. Required fixes
- **P0 (blocks merge):**
- **P1 (must fix before any Drafting → Visible):**
- **P2 (nice to have):**

### Overall recommendation
- Ready for human review / Needs fixes / etc.
```

---

## How to Replicate This System on Future Repos

1. Copy AGENTS.md, WORKFLOW.md, and this PROCESS.md.
2. Create the same three roles.
3. Always start with a Master Control Register.
4. Use draft branches from day one for any safety- or compliance-critical content.
5. Require the Claude Verification Report template for every major delivery.
6. Keep the human as the only authority that can promote Drafting → Visible.

---

## Immediate Next Actions for This Repo

- [x] Local scaffold in `~/projects/Scaffolding-Grokapedia`
- [x] Process files locked
- [x] Chapter map + seed MCR from Module-1 PPTX (all Drafting)
- [ ] Human supplies Anabeeb scaffold procedure + client matrices
- [ ] Public standards harvest packages
- [ ] Dual-model truth pass on MCR seed set
- [ ] First production chapter on `draft/section-01`
- [ ] Remote (GitHub) only when human requests

**Start every future encyclopedia at this process level, not from zero.**
