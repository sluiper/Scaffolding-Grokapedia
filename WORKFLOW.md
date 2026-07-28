# WORKFLOW.md — Dual-Model + Human Operating Rhythm

**Version:** 1.0 (28 July 2026)  
**See also:** PROCESS.md for the full decision log and replication guide.

## Current Role Split

- **Grok** researches, derives, drafts full production sections, creates Drafting MCR rows, updates CHANGELOG, commits **only to draft/* branches**, and performs a self-check after every commit.
- **Claude** independently verifies using the mandatory report template; produces P0/P1/P2 findings; does not draft or push.
- **Human** sets priorities, supplies internal sources, gives explicit approval for every Drafting → Visible promotion, and authorizes the merge from draft branch to main.

## Standard Delivery Loop

1. **Human** states the goal + any internal material.
2. **Grok** creates a new branch `draft/section-XX` (or `draft/topic`), produces the complete Delivery Package, self-checks, and declares ready for review.
3. **Claude** runs the **mandatory Verification Report** (template in PROCESS.md / below).
4. **Grok** applies only the P0 and P1 fixes on the same draft branch.
5. **Human** reviews, explicitly approves any Drafting → Visible promotions, and merges to main.

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
- Are every cited MCR-IDs actually present? Y/N
- Status of proposed rows correct? Y/N

### 4. CHANGELOG consistency
- Entry present and accurate? Y/N

### 5. Format compliance
- AGENTS format (MCR mapping, worked examples, Verification Log, honest gaps)? Y/N

### 6. Remaining gaps
- INTERNAL GAPs / unshown work

### 7. Required fixes
- **P0 (blocks merge):**
- **P1 (must fix before Drafting → Visible):**
- **P2 (nice to have):**

### Overall recommendation
- Ready for human review / Needs fixes / etc.
```

## Priority Queue (Scaffolding v0.2 campaign)

- [x] Local project scaffold + process lock
- [x] Encyclopedia structure map
- [x] Seed MCR from Anabeeb Module-1 (Drafting only)
- [x] Anabeeb WAH-P010 extract
- [x] Public secondary harvest RP-STD/COMP/LOAD
- [x] Grok T1 truth pass (high-risk set)
- [x] Chapter 01 production draft
- [ ] Claude Verification Report (Ch01 + T1)
- [ ] Human review + selective Visible promotions
- [ ] Ch03 / Ch05–06 / Ch17 drafts
- [ ] Training packs only after MCR freeze for exam-critical rows

## Safety Gate (Absolute)

No new MCR row is promoted from Drafting to Visible, and no draft branch is merged to main, without:

- Full derivation or primary citation + stated assumptions
- Clean Claude Verification Report (or only P2 remaining)
- Explicit human approval for any operational or Drafting → Visible change

## How to Start Work

- Human: “Grok: start draft/section-01 for Introduction” (or equivalent)
- Claude: “Claude: review draft/section-XX using the verification template”

Both models re-read AGENTS.md, WORKFLOW.md and the current MASTER_CONTROL_REGISTER.md before every major output.

This workflow is the standard copied from HPWJ into Scaffolding and future encyclopedias.
