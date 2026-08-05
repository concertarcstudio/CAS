Exit code: 0
Wall time: 1.2 seconds
Output:
# CAS-DB-002 - CAS Decision Engine (CDE) v1.0

## Record Control

- **Artifact ID:** CAS-DB-002
- **Title:** CAS Decision Engine (CDE)
- **Version:** 1.0
- **Status:** Draft Design Basis
- **Authority:** This file defines the CDE v1.0 method. Templates support the method but do not override it.
- **Presentation target:** Three pages when placed in the approved CAS publication format

## 1. Purpose

The CAS Decision Engine reduces a candidate search space through deterministic engineering analysis so that human effort can focus on the highest-value decisions. It converts an engineering function and its constraints into a ranked, explainable shortlist. The CDE is a decision-support method, not an autonomous design authority.

## 2. Core Principles

1. **Engineer functions, not positions.** Define the job a candidate must perform before considering a specific placement.
2. **Eliminate faster than you promote.** Apply hard constraints before comparative scoring so unsuitable candidates do not consume listening effort.
3. **Stop when confidence exceeds uncertainty.** End analysis when the leading recommendation is sufficiently supported, remaining uncertainty is visible, and further search is unlikely to change the decision.
4. **AI narrows the design space. Humans approve the engineering decision.** Machine-assisted analysis may eliminate, score, rank, and recommend. A human listens, judges, approves, and validates.

## 3. Architecture and Pipeline

`Engineering Function -> Candidate Pool -> Hard Elimination -> Weighted Scoring -> Ranking -> Top Candidates -> Human Listening -> Canonical Placement -> TES -> TA`

Each stage has one bounded responsibility:

| Stage | Required result |
|---|---|
| Engineering Function | Testable statement of the job to be performed |
| Candidate Pool | Identified candidates and sources |
| Hard Elimination | Removed candidates with rule-based reasons |
| Weighted Scoring | Comparable scores with criterion-level rationale |
| Ranking | Ordered surviving candidates |
| Top Candidates | Small shortlist for human review, normally three |
| Human Listening | Approval, rejection, or request for more analysis |
| Canonical Placement | Approved sequence change recorded as a design decision |
| TES and TA | Evidence collection and bounded engineering analysis |

The CDE recommendation remains provisional until human approval and the required downstream evidence workflow are complete.

## 4. Inputs

Every run requires:

- **Engineering Function:** the specific narrative, musical, emotional, or structural job to be performed.
- **Candidate Pool:** the bounded set of candidates to evaluate, with source and eligibility noted.
- **Current Canonical Sequence:** the approved sequence surrounding the proposed placement.
- **Design Constraints:** non-negotiable limits such as artist, edition, duration, continuity, content, or availability.
- **Scene Objective:** the larger scene-level outcome the function must support.

Missing inputs are recorded as gaps. The engine must not invent them.

## 5. Hard Elimination Rules

A hard rule is binary, traceable, and defined before scoring. A candidate is eliminated when it:

- violates an explicit design constraint;
- cannot perform the stated engineering function;
- creates a known continuity or sequence conflict;
- duplicates a function already fulfilled without a documented reason;
- lacks the source material or evidence needed for responsible evaluation; or
- is outside the declared candidate pool or run scope.

Every elimination records the rule, evidence, and disposition. Preference alone is not a hard rule. Uncertain cases remain eligible and carry an uncertainty note.

## 6. Weighted Scoring

Only surviving candidates are scored. Criteria and weights are declared before final ranking, total 100 percent, and map directly to the engineering function and scene objective. The standard scale is 0 to 5:

| Score | Meaning |
|---|---|
| 0 | Fails or contradicts the criterion |
| 1 | Very weak support |
| 2 | Partial support with material problems |
| 3 | Adequate support |
| 4 | Strong support |
| 5 | Exceptional and well-supported fit |

`Weighted total = sum((criterion score / 5) x criterion weight)`

Scores organize evidence. They do not replace listening judgment. Each score requires a short rationale, and ties are resolved through human review rather than hidden adjustments.

## 7. Confidence and Human Review

Confidence describes the strength of the recommendation, not the quality of the candidate.

- **High:** inputs are complete, eliminations are stable, evidence supports the leading candidate, and the lead is unlikely to change through additional search.
- **Medium:** a recommendation is supportable, but one or more relevant uncertainties, close scores, or evidence gaps remain.
- **Low:** inputs are incomplete, evidence is weak, rankings are unstable, or the engine cannot distinguish candidates responsibly.

Human listening is required before canonical placement at every confidence level. High confidence may stop further candidate search. Medium confidence normally triggers comparative listening or a targeted evidence request. Low confidence returns the run for revised inputs, broader candidates, or additional evidence. A human may override a recommendation only with a recorded rationale.

## 8. Output Specification

Each CDE run produces one report containing:

- run ID, date, owner, status, and source references;
- engineering function, scene objective, canonical context, and constraints;
- candidate counts at intake, elimination, and scoring stages;
- elimination log with rule and reason;
- scoring criteria, weights, criterion scores, rationales, and totals;
- ranked shortlist, normally the top three;
- confidence level and unresolved uncertainty;
- recommendation and required human-review action;
- human decision, override rationale when applicable, and canonical disposition; and
- links to resulting TES, TA, or other engineering records.

The reusable report and scoring templates in this package define the minimum record shape.

## 9. Integration

The CDE operates before and alongside the existing CAS evidence architecture. It consumes design intent and current canonical context, then proposes a bounded candidate decision. Human approval authorizes placement work. TES records observations from the approved evaluation, and TA interprets that evidence. The CDE report may be cited as decision history, but it is not a substitute for TES evidence or TA conclusions.

## 10. What the CDE Will Never Do

The CDE will never:

- make an unreviewed canonical placement;
- treat a numeric score as proof of artistic correctness;
- fabricate inputs, evidence, listening observations, or certainty;
- conceal eliminated candidates, uncertainty, contradictions, or overrides;
- change criteria or weights after results are known without recording a new run;
- use design intent as evidence that an outcome occurred;
- exceed the declared candidate pool, constraints, or run scope silently; or
- replace the accountable human engineering decision.

## Version Control

Version 1.0 is intentionally lean. Future revisions may refine criteria libraries, automation, or presentation only through explicit version control. Final figures CDE-001 through CDE-005 remain deferred for an approved FDS-compliant rendering pass.

