# cjcrim-author-lab

## Charter

This repo exists to test CJCRIM-Author architectural upgrades before production adoption.

It is an incubator — not a second production system. Patterns proven here migrate to [CJCRIM-Author](https://github.com/decarlo-research/CJCRIM-Author) when ready.

---

## What We're Testing

1. **Template-based domain specification** — Do study-type templates (panel regression, scoping review, DDM experiment) improve output quality and speed?
2. **Scored adversarial review** — Does adding numeric scoring (1–10 per dimension) to the MIT review panel improve revision quality?
3. **Automated novelty checking** — Does literature search + LLM novelty judgment improve project selection?
4. **Reflection/iteration loops** — Do structured reflection passes improve draft quality?

---

## Structure

```
templates/           Study-type templates with seed hypotheses, analysis code, paper structure
  panel-regression/
  scoping-review/
  ddm-experiment/
review-system/       Scored review and meta-synthesis prototypes
discovery/           Literature search and novelty checking
reflection/          Iteration loop prototypes
experiments/         Test runs and results
docs/                Transfer analysis, design notes, decision log
```

---

## Phase 1 Priorities

- [ ] Build DDM experiment template (first substantive artifact)
- [ ] Add numeric scoring to review system
- [ ] Prototype novelty check using scite + LLM judgment
- [ ] Implement reflection loops for writeup commands

---

## Ground Rules

- Nothing ships to CJCRIM-Author without a test run here first
- Document what works AND what fails
- Keep it lean — this is a lab, not a cathedral
- Source patterns: [AI Scientist Transfer Analysis](docs/AI_Scientist_Transfer_Analysis.md)

---

## Origin

Architectural patterns identified from Sakana AI's [AI Scientist](https://github.com/SakanaAI/AI-Scientist) (Nature, March 2026) and adapted for social science research pipelines. See `docs/AI_Scientist_Transfer_Analysis.md` for the full analysis.
