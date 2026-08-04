# VC-005 Affluenza Sequence Reconstruction Report v0.2

## Outcome

The complete 78-row original CSV is now available and has been reconciled against the repository evidence.

The repository supports a continuous engineered sequence through global position 23. Scene 1 positions 1 through 15 are unchanged from the baseline. Scene 2 introduces eight confirmed moves. Positions 24 through 78 retain full baseline visibility but remain unresolved as engineered positions.

## Confirmed Changes

| Song | Original | Engineered | Change |
|---|---:|---:|---|
| Medusa (Stone) | 17 | 16 | Moved forward 1 position |
| The One | 20 | 17 | Moved forward 3 positions |
| Nothing Could Come Between Us | 21 | 18 | Moved forward 3 positions |
| Not Meant to Be | 32 | 19 | Moved forward 13 positions |
| Say Goodbye | 22 | 20 | Moved forward 2 positions |
| Hate My Life | 25 | 21 | Moved forward 4 positions |
| Hurricane | 23 | 22 | Moved forward 1 position |
| The Truth Is... (I Lied About Everything) | 30 | 23 | Moved forward 7 positions |

## Conflicts Resolved

### TES-0018 identity

The original CSV places `Nothing Could Come Between Us` immediately before `Say Goodbye`. The locked design inserts `Not Meant to Be` between them.

Resolution: TES-0018 is `Nothing Could Come Between Us` to `Not Meant to Be`.

### Recovery entry

SA-0002 contains a stale placeholder for the Recovery entry. SD-0002 v1.0 explicitly identifies `Hate My Life` and is the later Design Locked source.

Resolution: global position 21 is `Hate My Life`.

### Scene 2 length

The VC-005 overview allocates Scene 2 to tracks 16 through 30, while SD-0002 locks only eight songs through global position 23.

Resolution: positions 24 through 30 remain unresolved. Scene 3 is not moved forward without an explicit engineering decision.

## Displaced Baseline Songs Requiring Placement Review

The engineered Scene 2 moves displace baseline songs at positions 16, 18, 19, 24, 26 through 29, and 31 through 32. The most immediate unresolved candidates include `Drag Me to Hell`, `Barricade`, `Wake Up Call`, `Get In Line`, `History of Violence`, `Shape of My Heart`, `In Ruins`, `Since You've Been Gone`, and `Echoes`.

These songs are not deleted by this reconstruction. Their current engineered positions are unknown.

## Validation Results

- Original source contains exactly 78 data rows.
- Canonical CSV contains exactly 78 position rows.
- Positions are unique and contiguous from 1 through 78.
- Every canonical row includes the original baseline song at that position.
- All 23 resolved engineered songs occur in the original source.
- Scene 1 positions 1 through 15 match the original source exactly.
- Eight Scene 2 position changes have explicit source traceability.
- No unresolved row contains an invented engineered song title.
- TES-0018 agrees with SD-0002 and SA-0002.
- No em dash characters are present.

## Remaining Questions

- Does locked Scene 2 end at global position 23, or must positions 24 through 30 be designed before Scene 2 can close?
- Where do the displaced baseline songs from the original Scene 2 range belong in the engineered sequence?
- What is the engineered Scene 3 opening needed to complete TA-0023?
- Does the Archive retain its original internal order, or will it be separately engineered?

Version 0.2 is the canonical reconstruction for current evidence. It supersedes v0.1 while preserving unresolved positions explicitly.

