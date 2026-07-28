# Chapter 24 — Incident Case Study Library

**Status:** Production draft v0.6  
**Version:** v0.5.1-draft (28 July 2026)  
**Branch:** `draft/campaign-max-stack-v0.2`

## MCR Mapping

Lessons map to MCR-015/054, 016–020, 028–029, 047–048, 060–062, and FMEA Ch19.

---

## 1. Rules for this library

1. **No fake Anabeeb cases.** Real Anabeeb incidents = **GAP-006**.  
2. Public / composite cases are labelled **[COMPOSITE]** or **[PUBLIC]** with source if public.  
3. Each case ends with **controls that would have applied** using MCR IDs.  
4. Cases are for training discussion after human freeze — not for blaming.

---

## 2. Composite case A — Missing midrail during modify [COMPOSITE]

**What happened (pattern):** During board change-out, midrail left open; worker stepped through.  

**Controls that apply here:**

| Control | MCR |
|---------|-----|
| Temporary edge protection / hierarchy | MCR-030 |
| Only scaffolders modify | MCR-060 |
| Tag status reflects restricted work | MCR-028 |
| Sequence in design for incomplete edges | MCR-045 / Ch22 |

**Learning ID:** LL-S01 (Ch26)

---

## 3. Composite case B — Duty class confusion [COMPOSITE]

**What happened (pattern):** Materials stacked on “light duty” platform; local collapse of boards/ledgers.  

**Controls:**

| Control | MCR |
|---------|-----|
| Duty class known and marked | MCR-015 / 054 |
| User briefing on duty | Ch17 / MCR-029 |
| Dual system interface | GAP-019 / Ch21 |

**Learning ID:** LL-S02, LL-S09

---

## 4. Composite case C — Mobile tower shifted with forklift [COMPOSITE]

**What happened (pattern):** Tower moved with machine; overturn or person injury.  

**Controls:**

| Control | MCR |
|---------|-----|
| No machine shift of scaffold | MCR-062 |
| Wheels locked; height ratio | MCR-019 / 056 |
| No persons on tower while moving | MCR-019 |

**Learning ID:** LL-S06

---

## 5. Composite case D — Dropped tool from hop-up [COMPOSITE]

**What happened (pattern):** Hand tool fell from height; struck worker below.  

**Controls:**

| Control | MCR |
|---------|-----|
| Tool lanyards mandatory | MCR-047 |
| Drop zone barricade | MCR-048 |
| Toe-boards / screens as applicable | MCR-030 |

**Learning ID:** linked Ch23 SIMOPS

---

## 6. How to add a real case (when GAP-006 closes)

```
### Case ANB-YYYY-### 
**Source:** [incident number]
**Facts:** …
**MCR controls that failed or were absent:** …
**Register changes:** new Drafting rows if needed
**Training feed:** ATC-SCAF-BASIC / SUP / VOC
```

---

## Verification Log

| Date | Reviewer | Scope | Result |
|------|----------|-------|--------|
| 28 Jul 2026 | Grok | All cases composite; MCR links present | Self-check only |

## Honest Gaps

GAP-006 Anabeeb incidents; public investigation PDFs not yet harvested systematically.
