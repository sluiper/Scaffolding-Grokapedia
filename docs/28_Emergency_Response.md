# Section 28 — Emergency Response (Scaffold Context)

**Status:** Production draft v0.6  
**Date:** 28 July 2026  
**Branch:** `draft/campaign-max-stack-v0.2`  

## MCR Mapping

| MCR-ID | Role in section |
|--------|-----------------|
| MCR-028–029 | Tag / stop-use when structure unsafe after event |
| MCR-030, 046, 049 | Fall protection hierarchy; ≥1.8 m; 100% tie-off context |
| MCR-047–048 | Drop zone; tool lanyards (struck-by / post-event isolation) |
| MCR-051 | Weather stop-work (sudden weather scenario) |
| MCR-036 | Planning / PTW / barricade culture feeds emergency readiness |
| MCR-035, 060 | Competent scaffolders only for structural recovery / modify |
| MCR-045 | Engineer / design review after partial collapse |
| MCR-050 | Anchorage strength (rescue anchor selection interface) |
| MCR-043–044 | Anabeeb / client emergency & WAH rules may be stricter |

**WAH extract:** Project Manager, Supervisor/Foreman, HSE Officers, Workers — duties for training, TBT, equipment inspection, PTW/risk assessment, compliance. [CITATION: WAH-P010 summary]

**Not extracted here:** full AIMS emergency preparedness procedure; First aid SWP-015 (master list). [INTERNAL GAP]

---

## 1. Scope

This section covers **scaffold-context** emergencies: fall from height, partial collapse, struck-by / dropped object, medical event on platform, and sudden adverse weather. Site-wide ERP (muster, fire, toxic release) remains governed by Anabeeb/client emergency procedures — not rewritten here. [SYNTHESIS]

---

## 2. Roles matrix

| Role | Immediate (0–5 min) | Stabilize / support | Structural / return-to-work | Notes |
|------|---------------------|---------------------|----------------------------|-------|
| **Workers (end users)** | Stop unsafe work; shout/alarm; move to safe ground if possible; do **not** re-enter collapsed/unstable scaffold | Assist first aid only if trained & scene safe; account for workmates | No scaffold modification | MCR-060 — not scaffolders |
| **Scaffolder(s) on crew** | Stop erection/modify; preserve if safe; prevent others climbing damaged scaffold | Advise temporary stability only under competent lead; red-tag path | Restore only under plan; only authorized to modify | MCR-035, 060, 028 |
| **Scaffold supervisor / competent person** | Take structural control of scene (with HSE); initiate evacuation of scaffold; prevent re-boarding | Temporary works judgment; call engineer if partial collapse | Approve re-inspect before use (**MCR-029**); tag status | MCR-028, 029 |
| **Supervisor / Foreman (area)** | Stop SIMOPS; account for people; activate site emergency number | Isolate drop zone / work area; manage headcount; notify PM/HSE | Gate work restart only after clearances | WAH role list [CITATION] |
| **HSE Officer** | Support emergency services interface; scene safety | Preserve evidence for investigation; ensure drop-zone barricade (**MCR-048**) | Verify stop-work / permit suspension; lessons feed | WAH role list [CITATION] |
| **First aider / medical** | ABC/BLS per training; request EMS | Package casualty for transfer; do not improvise rope lower without rescue plan | N/A | Site first-aid SWP — **GAP** (SWP-015 not extracted) |
| **Rescue team (if designated)** | Execute **pre-job** rescue plan for platform casualty | Controlled lower / basket per plan; fall-arrest anchors ≥ **22.2 kN** if used for PFAS (**MCR-050**) | Stand down; debrief | Do not improvise with gin wheel (**MCR-031** is 50 kg material only) |
| **Project Manager** | Ensure emergency services notified; client notification per site rules | Resource control; family/next-of-kin per company process | Authorize investigation & corrective actions | WAH role list [CITATION] |
| **Temporary works / scaffold engineer** | N/A unless on site | Advise no re-entry after partial collapse | Design review / engineered recovery (**MCR-045**) | Required after collapse/serious structural event [SYNTHESIS] |
| **Client representative** | As per site ERP | May impose stop-work | Accept return-to-work conditions | MCR-044 |

```
Command sketch [SYNTHESIS]:
  Emergency occurs
       │
       ├─ Life safety first (workers / first aid / EMS)
       ├─ Area supervisor: headcount + isolate
       ├─ HSE: ERP interface + evidence
       ├─ Scaffold competent person: no re-board damaged structure
       └─ PM: notifications + resources
            │
            └─ Before restart: engineer (if collapse) + inspect/tag (MCR-029/028)
```

---

## 3. Scenario table — immediate actions

| Scenario | Immediate actions [SYNTHESIS] | Key MCR |
|----------|-------------------------------|---------|
| **Fall from height** | Stop work; first aid/BLS per site; emergency services; preserve scene; notify HSE/PM; do not move casualty unless imminent danger | 030, 046, 049 |
| **Partial collapse** | Evacuate; account for people; **no re-entry** until engineer/scaffold competent person; red tag (**MCR-028**) | 028, 029, 045 |
| **Struck-by / dropped object** | Medical; isolate drop zone; stop overhead work; check tool lanyard / barricade failures | 047, 048 |
| **Medical on platform** | Use **pre-job** rescue plan; do not improvise unsafe lower without method; gin wheel is **not** a rescue device (50 kg material — MCR-031) | 031, 050 |
| **Weather sudden** | Clear platforms; secure materials; stop height work | 051 |
| **Missing / failed ties discovered mid-use** | Evacuate platform; red tag; scaffolders only; temporary stability plan before any partial strip | 060, 028; Ch11 |
| **Mobile tower overturn risk** | Clear users; lock scene; do not right structure under load without plan | 019, 056 |

---

## 4. Pre-job readiness (reduces emergency severity)

| Control | Link |
|---------|------|
| PTW / JSA / TBT; barricade; signs | MCR-036 |
| Tag check every access | MCR-028, 029 |
| Drop zone under overhead work | MCR-048 |
| Tool lanyards | MCR-047 |
| Weather stop criteria (wind numeric still GAP-009) | MCR-051 |
| Rescue plan when work on high / restricted platforms | [SYNTHESIS]; WAH emergency duties |
| Only competent scaffolders erect/modify | MCR-035, 060 |

---

## 5. Post-event structural path [SYNTHESIS]

1. **Red tag** / Do Not Use if structure damaged or status unknown (**MCR-028**).  
2. **Do not** machine-shift damaged scaffold (**MCR-062**).  
3. Scaffolders + competent person assess; engineer if partial collapse or design scaffold (**MCR-045**).  
4. Replace defective materials from quarantine rules (Ch27); do not re-use failed critical members without competent acceptance.  
5. Re-inspect and approve prior to use (**MCR-029**); re-tag only by authorized person.  
6. Feed incident into lessons learned (Ch26) and FMEA (Ch19).

---

## 6. Worked example — roles in partial collapse [DERIVED]

**Event:** Two-bay independent scaffold drops a boarded lift after unauthorized tie removal by another trade.

| Time | Who | Action |
|------|-----|--------|
| T+0 | Workers on adjacent bay | Alarm; evacuate; no re-board |
| T+1 min | Area supervisor | Headcount; stop SIMOPS; call site emergency / HSE |
| T+2 min | HSE | Isolate perimeter; preserve scene; EMS if injured |
| T+5 min | Scaffold supervisor | Confirm red tag at all access; forbid “quick fix” by users |
| T+1 h | Engineer + scaffold competent person | Assess remaining structure; recovery method |
| Restart | Authorized tagger | Green/Yellow only after inspect/approve (**MCR-029**) |

Unauthorized modifier discipline is separate from rescue — still **MCR-060** never-rule for future control.

---

## 7. Drills

Recommend annual scaffold rescue drill on sites with frequent high scaffolds. [SYNTHESIS]  
Drill should exercise: alarm, headcount, no re-entry discipline, simulated platform casualty with **pre-planned** rescue gear (not gin wheel as man-riding). [SYNTHESIS]

---

## 8. Links to Anabeeb controlled docs

| Document | Status in encyclopedia |
|----------|------------------------|
| AIMS-L3-HSE-P-010 WAH | Partial extract — roles/fall controls cited |
| AIMS emergency preparedness (master list) | **Not extracted** — [INTERNAL GAP] |
| First aid SWP-015 | Master list only — [INTERNAL GAP] |
| AIMS-L3-HSE-SWP-019 Scaffolding | **GAP-001** — not issued/available |

When SWP-019 and site ERP are available, bind this section’s roles matrix to named forms and phone trees. [SYNTHESIS]

---

## 9. Verification Log

| Check | Result |
|-------|--------|
| Roles matrix present | Yes §2 |
| Scenario actions without invented medical protocols | Yes — point to site first aid |
| Gin wheel not used as rescue device | Explicit (MCR-031) |
| Collapse restart gated by inspect/tag/engineer | Yes §5 |
| No fake primary-standard clause numbers | Yes |
| Claude independent verify | Skipped per user direction |

## 10. Honest gaps

- Full AIMS emergency preparedness procedure not extracted.  
- First aid SWP-015 not extracted.  
- Wind speed numeric stop threshold still **GAP-009**.  
- Site-specific phone trees / muster maps not in encyclopedia (correctly local).  
- Scaffold rescue method statement library not built.  
- SWP-019 may redefine scaffold emergency duties (**GAP-001**).
