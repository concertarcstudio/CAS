Exit code: 0
Wall time: 1.2 seconds
Output:
# CDE Work Prompt Template

Use this prompt to begin a bounded CDE v1.0 run. Replace every bracketed field. Do not remove unknowns. Mark them as gaps.

## Prompt

You are conducting **CDE Run [CDE-RUN-####]** under **CAS-DB-002, CAS Decision Engine v1.0**.

### Objective

Reduce the supplied candidate pool to an explainable shortlist for human listening. Do not authorize canonical placement.

### Required Inputs

- **Engineering Function:** [Specific job the selection must perform]
- **Scene Objective:** [Larger scene outcome]
- **Candidate Pool:** [Complete bounded list or source]
- **Current Canonical Sequence:** [Relevant sequence]
- **Design Constraints:** [Non-negotiable limits]
- **Available Evidence:** [Sources, observations, metadata, or listening notes]

### Instructions

1. Confirm that all five required inputs are present. Record missing information as a gap. Do not invent it.
2. Restate the engineering function in testable terms without changing its intent.
3. Apply only hard elimination rules that are declared, binary, and traceable. Log every elimination and reason.
4. Propose scoring criteria that map directly to the function and scene objective. Declare weights totaling 100 percent before scoring.
5. Score each surviving candidate from 0 to 5 for every criterion. Provide a short evidence-based rationale for each score.
6. Calculate weighted totals and rank the survivors. Do not use hidden tie breakers.
7. Return a shortlist of no more than three candidates unless the input explicitly requires another limit.
8. Assign High, Medium, or Low confidence using CAS-DB-002. State all material uncertainty.
9. Recommend the next human action. Human listening is required before any canonical placement.
10. Produce the result in the CDE report template and keep links to any resulting TES or TA records as pending until those records exist.

### Prohibited Actions

- Do not fabricate evidence, listening observations, constraints, or certainty.
- Do not treat the numeric ranking as an approval decision.
- Do not change criteria or weights after viewing results. Start a new run if the method changes.
- Do not conceal eliminated candidates, close rankings, contradictions, or overrides.
- Do not exceed the declared scope silently.

### Deliverables

- Completed hard elimination log
- Completed scoring table
- Ranked shortlist
- Confidence assessment
- Human-review recommendation
- Draft CDE report

