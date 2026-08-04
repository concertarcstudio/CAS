# Engineering Decision Tree

## Purpose

Protect the authoritative engineering baseline by separating observations, proposed changes, decisions, and implementation.

## Workflow

1. **Identify an engineering concern.**
2. **Record the observation** in the relevant Transition Audit or analysis.
3. **Determine whether a baseline change is required.**
   - If no, retain the observation and update the Scene Analysis.
   - If yes, create an Engineering Change Proposal (ECP).
4. **Perform Blue Team review.** Document the case for the proposal.
5. **Perform Red Team review.** Challenge the proposal with credible alternatives and risks.
6. **Issue an Engineering Decision.** Approve, reject, modify, or defer the ECP.
7. **If approved, update the baseline** through a traceable revision.
8. **Update related records:** Evidence Register, Scene Analysis, Scorecard, indexes, and session log.
9. **Commit the change** with references to the ECP and Engineering Decision.

## Baseline Protection Rule

> The authoritative engineering baseline is never modified merely to test an idea. Proposed changes remain separate until approved through the Engineering Change Proposal process.
