# DIKWP AC-PrimalQuestions OS

**DIKWP AC-PrimalQuestions OS** is a GitHub-ready open-source reference system for artificial-consciousness research assessment.

It is built around a premise that becomes unavoidable when designing serious artificial-consciousness systems:

> You cannot build a responsible artificial-consciousness system without explicitly answering a set of ultimate questions: What is life? What is consciousness? What is selfhood? What counts as feeling? What counts as intention? What counts as proof? What remains residual?

This project turns those questions into an auditable engineering layer.

## Core Idea

The system evaluates artificial-consciousness candidates through:

- DIKWP D/I/K/W/P/R layer completeness
- P-layer intent contract: goal, value, constraints, time, feedback
- SemanticClosure under incomplete, imprecise and inconsistent input
- Semantic homeostasis proxy
- Life-homeostasis proxy
- Self-model and metacognition indicators
- Auditability and claim barrier
- Welfare and possible-sentience boundary
- Ultimate Question Ledger
- Phenomenal Residual and Material Autopoiesis Residual

## Quick Start

```bash
pip install -e .
ac-primal evaluate examples/sample_ac_candidate.json --questions examples/sample_ultimate_question_answers.json --out outputs/demo
ac-primal redteam examples/sample_redteam_cases.json --out outputs/demo/redteam
ac-primal static-audit src --out outputs/demo/static_boundary_audit_report.json
```

## Outputs

The demo produces:

- `ac_ultimate_assessment_report.json`
- `ultimate_question_ledger.json`
- `indicator_scores.csv`
- `claim_level_report.md`
- `phenomenal_residual_statement.md`
- `experiment_roadmap.md`
- `kill_recovery_matrix.md`
- `redteam/redteam_report.json`
- `static_boundary_audit_report.json`

## Boundary

This system does **not** certify that any AI system is conscious.

It supports internal research review, claim-level discipline, evidence custody, welfare boundary preparation, and ultimate-question accountability.

## Attribution

Prepared for the Yucong Duan / DIKWP open research ecosystem.
