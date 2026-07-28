# Restatement Map — Scaffolding MCR

**Purpose:** After any numeric fix at the MCR source row, every listed restatement must be corrected in the same commit.

**Updated:** 28 July 2026 — seed map (high-risk rows).

| MCR ID | Topic | Known restatements | Last swept |
|--------|-------|--------------------|------------|
| MCR-001 / 002 | Tube OD / wall | Ch05, appendices if any | Pending formal sweep |
| MCR-008–014 | Coupler SWL | Ch06, Appendix B | Pending |
| MCR-015 / 054 | Duty classes | Ch09, Appendix A, training BASIC | Pending |
| MCR-017 / 018 | Free-stand / tower ratios | Ch13, Appendix D | Pending |
| MCR-021 / 022 | Guardrail geometry | Ch16, WAH summary, Appendix C | Align Anabeeb 1.1 m ± 8 cm vs PPTX band |
| MCR-028 / 029 | Tag colours | Ch17, Appendix E, templates/tags | Pending |
| MCR-046 | Fall trigger 1.8 m | Ch01, WAH summary, Rigging WAH interface | Family cross-wiki |

## Cross-wiki restatements

| Topic | Scaffolding | Rigging | HPWJ |
|-------|-------------|---------|------|
| WAH 1.8 m / 22.2 kN | WAH summary + MCR-046 | WAH lifting interface | n/a |
| SWP-019 scaffold | GAP-001 | n/a | n/a |

## Sweep procedure

Same as family standard §7: fix register first, then `rg` every restatement, same commit, update this map, CHANGELOG.
