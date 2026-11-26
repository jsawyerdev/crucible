# Crucible

> Status: concept repository - future work

An autonomous experimental engineering platform for controlled, falsifiable investigation.

## Objective

Investigate engineering questions by generating competing hypotheses, designing controlled experiments, and evaluating results against independent success criteria.

## Proposed scope

- Form competing explanations for observed behaviour
- Run reproducible experiments in isolated environments
- Record evidence, failed experiments, and disproven hypotheses
- Evaluate outcomes with independent experimental oracles

## Related projects

Crucible is the proposed umbrella platform for three independently useful experimental capabilities:

- [Disconfirm](https://github.com/jsawyerdev/disconfirm) - generates competing hypotheses and designs discriminating experiments
- [Proofsmith](https://github.com/jsawyerdev/proofsmith) - independently verifies changes proposed by coding agents
- [Replicarium](https://github.com/jsawyerdev/replicarium) - reconstructs and tests published computing experiments

These relationships are conceptual. They do not establish implementation dependencies or commit the projects to a shared architecture.

## Technical direction

Isolated execution, causal and Bayesian reasoning, experiment tracking, static and dynamic analysis.

The technologies above are candidates, not commitments. Selection will follow evidence from the smallest useful prototype.

## Open questions

- What observable result would make the first prototype useful?
- Which assumptions need controlled experiments before implementation?
- What independent oracle can determine whether an experiment succeeded?
- What is the smallest reproducible dataset or workload?

## Repository status

This repository reserves the project identity and records the initial concept. It contains no production implementation, published roadmap, or stable API.
