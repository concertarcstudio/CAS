# CDE-0029-R1 - Position 29 Redesign Decision

## Record Control

- **CDE Run ID:** CDE-0029-R1
- **Date:** 2026-08-05
- **Status:** Human Redesign Decision Approved
- **Engineering Function:** Commitment
- **Historical record preserved:** [CDE-0029](CDE-0029_Position_29.md)
- **Design evidence:** [DI-0001](../00_Playlist/Design_Iterations/DI-0001_Position_29_Get_In_Line.md)
- **Change proposal:** [ECP-0002](../02_Engineering/Engineering_Change_Proposals/ECP-0002_Reopen_Position_30_After_Position_29_Redesign.md)

## Decision Context

Canonical v0.7 placed `All or Nothing` at Position 29. Completed-arc listening later identified a functional risk: its absolute declaration could consume the distinct Threshold function reserved for Position 30. DI-0001 tested `Get In Line` as enacted Commitment after `Wake Up Call` and required Position 30 to be reassessed from the new predecessor.

## Human Decision

- **Selected candidate:** `Get In Line`
- **Prior canonical candidate:** `All or Nothing`
- **Decision class:** Evidence-based redesign override
- **Rationale:** `Get In Line` turns Choice into action while preserving structural room for a separate crossing at Position 30.
- **Downstream effect:** The v0.7 CDE-0030 analysis is historical only because its predecessor changed. CDE-0030-R1 supplies the revised shortlist.

## Engineering Metrics Block (EMB)

| Metric | Value |
|---|---|
| Historical CDE Recommendation | All or Nothing |
| Human Redesign Decision | Get In Line |
| Recommendation Agreement | No, documented redesign override |
| Override Basis | Completed-arc comparative listening and function separation |
| Engineering Function | Commitment through action |
| Downstream Re-evaluation Required | Yes |
| Canonical Sequence Changed | Yes, in v0.8 |
| Historical v0.7 Records Preserved | Yes |

## Disposition

Approved for TES-0029-R1, TA-0029-R1, and canonical sequence v0.8. No claim is made that the historical v0.7 decision was invalid in its original context.
