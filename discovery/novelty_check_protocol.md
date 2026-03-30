# Novelty Check Protocol

<!-- Prototype: Automated novelty assessment -->

## Concept

Before committing to a research project, verify:
1. Has this hypothesis been empirically tested?
2. What is the closest existing work?
3. What is the incremental contribution?

## Pipeline

1. Extract hypothesis from command packet
2. Search scite / Semantic Scholar / Google Scholar
3. LLM judges novelty against retrieved literature
4. Output: novelty score (1–10), closest prior work, recommended differentiation

## Tools
- scite MCP (already connected)
- Semantic Scholar API
- LLM judgment prompt

## Status: Placeholder — needs implementation
