Exit code: 0
Wall time: 1 seconds
Output:
# CDE Figure Registry

**Status:** Specifications only. No final figures are rendered in v1.0.

All listed figures are placeholders for a future FDS-compliant rendering pass. Production must follow the approved CAS/FDS typography, spacing, color hierarchy, iconography, accessibility, captioning, and export requirements. The renderer must preserve the meaning and stage order defined here.

## CDE-001 - Decision Pipeline

- **Purpose:** Show the complete CDE workflow in one vertical or left-to-right sequence.
- **Required content:** Engineering Function, Candidate Pool, Hard Elimination, Weighted Scoring, Ranking, Top Candidates, Human Listening, Canonical Placement, TES, TA.
- **Key distinction:** Visually separate machine-assisted narrowing from human approval and downstream evidence work.
- **Render status:** Future FDS-compliant rendering required.

## CDE-002 - Candidate Funnel

- **Purpose:** Show progressive reduction from the full pool to an engineering decision.
- **Required content:** Candidates received, candidates eliminated, candidates scored, shortlist, human decision.
- **Data behavior:** Counts are run-specific variables. The visual must not imply fixed quantities.
- **Key distinction:** Eliminated and scored candidates must remain auditable, not disappear from the record.
- **Render status:** Future FDS-compliant rendering required.

## CDE-003 - Human vs AI Responsibilities

- **Purpose:** Establish the authority boundary.
- **AI side:** Apply declared rules, calculate scores, rank, expose uncertainty, recommend.
- **Human side:** Listen, challenge, approve or reject, document overrides, validate.
- **Key distinction:** Only the human side may authorize canonical placement.
- **Render status:** Future FDS-compliant rendering required.

## CDE-004 - Confidence Threshold

- **Purpose:** Explain when analysis continues, stops, or returns for more evidence.
- **Required content:** Low, Medium, and High confidence; uncertainty; score separation; input completeness; required human action.
- **Decision behavior:** Low returns for revised inputs or evidence. Medium triggers targeted comparative review. High may stop further search but still requires human listening.
- **Key distinction:** Confidence applies to the recommendation, not candidate quality.
- **Render status:** Future FDS-compliant rendering required.

## CDE-005 - Engineering Function Lifecycle

- **Purpose:** Show how a function moves from definition to verified engineering record.
- **Required content:** Define Function, Set Constraints, Evaluate Candidates, Recommend, Human Approve, Canonical Placement, Observe in TES, Analyze in TA.
- **Key distinction:** The function is defined before candidates are promoted, and verification occurs after approval.
- **Render status:** Future FDS-compliant rendering required.

