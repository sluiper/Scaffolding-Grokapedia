# Chapter 22 — Design Principles & When Engineering Is Required

**Status:** Production draft v0.6  
**Version:** v0.5.1-draft (28 July 2026)  
**Branch:** `draft/campaign-max-stack-v0.2`

## MCR Mapping

| MCR-ID | Control | Status |
|--------|---------|--------|
| MCR-045 | Engineering scaffold gate | Drafting |
| MCR-058 | Cantilever ≤ 3 m without design | Drafting |
| MCR-015 / 054 | Duty class limits | Drafting |
| MCR-017–019 | Free-stand / mobile ratios | Drafting |
| MCR-024 / 025 | Ladder beam specials | Drafting |
| MCR-040 | Hung / trapeze | Drafting |
| MCR-060 | User never modify | Drafting |

---

## 1. Standard / compliance vs engineered

**Standard (compliance) scaffold**  
Configuration falls inside published good-practice sheets (e.g. TG20 eGuide sheets when held) **or** the proprietary manufacturer’s system manual for the **exact** arrangement, duty, height, and tie pattern.

**Engineered scaffold**  
Outside those sheets: requires competent temporary-works design (drawing, loads, ties, sequence, foundations) and change control.

[SYNTHESIS] Industry temporary-works practice; Anabeeb design procedure number not held.

---

## 2. Hard triggers — engineering required (encyclopedia)

| Trigger | MCR / source | Notes |
|---------|--------------|-------|
| Cantilever platform **&gt; 3 m** | MCR-058 | Deck cites Aramco CSM-II; ≤3 m without design only if that rule adopted |
| Free-stand / mobile **ratio exceeded** without outriggers/ties | MCR-017–019 | External 3×, internal/mobile 4× family |
| Duty **special / heavy** beyond class on tag | MCR-015 / 054 + MCR-045 | |
| Bridge, span, ladder-beam special arrangements | MCR-024, ADV training | |
| Hung / suspended non-standard | MCR-040 + design | Trapeze assist ≤ 600 mm (MCR-040) is not a free pass for exotic hung scaffolds |
| Significant wind-area cladding / netting | [SYNTHESIS] | Often design + weather stop-work (MCR-051) |
| Public protection / complex SIMOPS | Client often | Ch23 |
| Foundations on doubtful ground without engineered sole/spread | MCR-033 | |

When in doubt, **escalate** — do not “stretch” a standard sheet.

---

## 3. Minimum design deliverables [SYNTHESIS]

Before erect outside standard sheets:

1. Duty class and max working lifts / loading diagram  
2. Plan and elevation; grid of standards  
3. Tie positions, type, and capacity assumptions  
4. Bracing scheme (face, ledger, plan)  
5. Foundation / sole board assumptions  
6. Sequence notes for incomplete edge protection during erect/dismantle  
7. Designer competence / temporary works approval as client requires  
8. Inspection / handover criteria linked to design

---

## 4. Site roles

| Role | Must |
|------|------|
| Designer / TW coordinator | Own the design; approve changes |
| Scaffold supervisor | Erect **as drawn**; stop on conflict |
| Scaffolder | No unauthorised “improvements” (MCR-060) |
| End user | Use only green/yellow as tagged; never modify (MCR-060) |

---

## 5. Worked conflict example [SYNTHESIS]

**Situation:** Crew wants a 4 m cantilever hop-up for exchanger work. Deck/Aramco-derived rule says cantilever **≤ 3 m** without design (MCR-058).

**Correct path:** stop; request engineered design or redesign access (independent scaffold / MEWP / platform).  
**Wrong path:** “We’ve always done 4 m with extra ledgers.”

---

## Verification Log

| Date | Reviewer | Scope | Result |
|------|----------|-------|--------|
| 28 Jul 2026 | Grok | Triggers map to MCR-045/058/017–019 | Self-check only |

## Honest Gaps

No TG20 eGuide library on disk; no Anabeeb temporary-works procedure number; primary standards GAP-007.
