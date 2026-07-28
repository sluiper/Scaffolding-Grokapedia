# Chapter 23 — Weather, Environmental & SIMOPS Interfaces

**Status:** Production draft v0.6  
**Version:** v0.5.1-draft (28 July 2026)  
**Branch:** `draft/campaign-max-stack-v0.2`

## MCR Mapping

| MCR-ID | Control | Status |
|--------|---------|--------|
| MCR-051 | Weather stop-work at height | Drafting — wind number **GAP-009** |
| MCR-048 | Drop zone barricade | Drafting |
| MCR-047 | Tool lanyards | Drafting |
| MCR-036 | Work permit & planning | Drafting |
| MCR-033 | Foundations | Drafting |

---

## 1. Weather stop-work (Anabeeb WAH)

Stop work at height for [CITATION] WAH-P010 / MCR-051:

| Condition | Action |
|-----------|--------|
| Strong wind | Stop — **numeric threshold incomplete in extract (GAP-009)** |
| Rain / slippery platforms | Stop or restrict per risk assessment |
| Sandstorm | Stop |
| Poor visibility | Stop |
| Lightning | Stop |
| Adverse thermal conditions | Stop / heat-stress interface |

**Until GAP-009 closes:** use client numeric wind limits if posted; otherwise supervisor stop-work authority with recorded reason. Do **not** invent a wind speed here.

---

## 2. Environmental effects on scaffold structure [SYNTHESIS]

| Effect | Risk | Control direction |
|--------|------|-------------------|
| Wind on boarded/clad faces | Overturn / overload ties | Ties per design; reduce sail area; stop-work |
| Rain / washout | Sole board settlement | Foundations MCR-033; re-inspect after storms |
| Heat | Tube expansion minor; heat stress major | SWP heat stress interface (GAP-020) |
| Corrosion / coastal | Coupler/tube deterioration | Material control Ch27 |
| Night / low light | Access errors | Lighting + permit conditions |

---

## 3. SIMOPS (simultaneous operations)

Scaffold interfaces often conflict with:

- Hot work / grinding under or beside platforms  
- Lifting / rigging over walkways (drop zone MCR-048)  
- Process live equipment / leaks  
- Other trades removing boards or ties  

### Minimum SIMOPS controls [SYNTHESIS]

1. Shared JSA / PTW with scaffold as a named interface (GAP-021 PTW linkage).  
2. Drop zone barricades and tool lanyards (MCR-047/048).  
3. No unauthorised modify of scaffold by other trades (MCR-060).  
4. Lift plans do not use scaffold as load path unless designed for it.  
5. Gin wheel limits remain (MCR-031) — not a crane substitute.

---

## 4. After severe weather — re-inspection trigger

Before re-use [SYNTHESIS + MCR-029 family]:

- Tag status reconfirmed by competent person  
- Sole boards / bases checked for settlement  
- Ties and braces checked  
- Boards and guardrails complete  

---

## Verification Log

| Date | Reviewer | Scope | Result |
|------|----------|-------|--------|
| 28 Jul 2026 | Grok | No invented wind number; MCR-051 gap explicit | Self-check only |

## Honest Gaps

GAP-009 wind speed; GAP-020 heat stress SWP link; GAP-021 PTW form linkage; client numeric weather matrices.
