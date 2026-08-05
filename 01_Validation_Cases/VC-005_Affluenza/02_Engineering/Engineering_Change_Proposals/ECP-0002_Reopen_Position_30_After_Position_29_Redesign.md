# ECP-0002 - Reopen Position 30 After Position 29 Redesign

## Record Control

- Status: Experimental branch proposal
- Date: 2026-08-05
- Affected design iteration: DI-0001
- Published baseline: canonical sequence v0.7
- Canonical effect: None until redesign approval

## Current State

Canonical sequence v0.7 places `All or Nothing` at Position 29 and leaves Position 30 unresolved. CDE-0030 evaluates Threshold from that published predecessor. Those records remain unchanged on main.

## Proposed Change

For this design iteration only, replace Position 29 `All or Nothing` with `Get In Line` and leave Position 30 unresolved.

## Engineering Basis

CDE-0030 evaluated Threshold after the published predecessor `All or Nothing`. Its criteria, scores, shortlist, and listening package were conditioned on that predecessor. DI-0001 changes the incoming architecture to `Wake Up Call` -> `Get In Line`, removes `Get In Line` from the eligible Position 30 pool, and returns `All or Nothing` to the unplaced pool.

The previous Position 30 result is therefore not transferable to the revised sequence. It remains authoritative for the v0.7 context and historical comparison only. CDE-0030-R1 supplies the branch-specific reassessment.

## Explicit Non-Assumptions

- Position 30 is not `Wake Up Call`.
- Position 30 is not `PCH` merely because PCH led CDE-0030.
- No Position 30 finalist is approved without comparative listening.
- No canonical sequence on main is superseded by this proposal.

## Required Evidence

The repository contains desk-analysis evidence but no candidate-level audio, edition, duration, availability, lyrical, or transition manifest. A fresh CDE desk analysis can narrow the revised pool, but a final Position 30 decision requires new comparative listening from `Get In Line` into the revised finalists.

## Disposition

Proceed with CDE-0030-R1 as a provisional branch analysis. Keep Position 30 unresolved until the human review is recorded. If the redesign is approved, create a new canonical version and the required TES and TA records. If rejected, close the iteration without changing v0.7.

## Final Disposition

Approved on 2026-08-05. Fresh comparative listening selected `PCH` by far after `Get In Line`. The redesign is promoted in canonical sequence v0.8 through CDE-0029-R1, CDE-0030-R2, TES-0029-R1, TA-0029-R1, TES-0030, and TA-0030. Canonical v0.7 and its production records remain preserved as historical evidence.

