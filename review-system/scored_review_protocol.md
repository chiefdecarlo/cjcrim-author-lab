# Scored Review Protocol

<!-- Prototype: Numeric scoring layer for MIT 6-agent panel -->

## Concept

Extend the existing MIT 6-agent adversarial review with:
1. Numeric scores (1–10) per dimension per agent
2. Formal meta-synthesis agent that aggregates across all 6 reviews
3. Ranked priority list for revisions
4. Decision classification (accept / minor revision / major revision / reject)

## Scoring Dimensions

Each agent scores relevant dimensions from its specialty:
- Agent 1 (Grammar): clarity, readability, APA compliance
- Agent 2 (Consistency): internal logic, claim-evidence alignment
- Agent 3 (Statistics): methodological rigor, analytical validity
- Agent 4 (Tables): data presentation, figure quality
- Agent 5 (Contribution): novelty, significance, positioning
- Agent 6 (Data): integrity, reproducibility, transparency

## Status: Placeholder — needs implementation and testing
