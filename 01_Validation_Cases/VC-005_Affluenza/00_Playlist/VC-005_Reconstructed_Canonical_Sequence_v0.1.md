# VC-005 Reconstructed Canonical Affluenza Sequence v0.1

## Record Control

- Status: Partial canonical reconstruction
- Scope: 78-position Affluenza architecture
- Verified song positions: 1 through 16 and 19 through 23
- Positions inferred from explicit transition evidence: 17 and 18
- Unresolved song positions: 24 through 78
- Baseline limitation: the uploaded CSV was not available in the execution workspace. The prior conversation explicitly attests only original positions 20 through 22.

This artifact is canonical for the evidence it records. Blank positions are intentionally unresolved and must not be used as permission to invent or assume an order.

## Status Definitions

- Verified: directly fixed by a certified scene analysis or Design Locked scene record.
- Inferred from explicit transition evidence: fixed by accepted TES and TA adjacency evidence, supported by the locked scene record.
- Unresolved: no repository artifact currently fixes the song at that global position.

## Reconstructed Sequence

| Position | Song | Scene | Status | Source |
|---:|---|---|---|---|
| 1 | Lowlife | Scene 1 | Verified | SA-0001 certified sequence |
| 2 | Dinosaur | Scene 1 | Verified | SA-0001 certified sequence |
| 3 | Bad Girlfriend | Scene 1 | Verified | SA-0001 certified sequence |
| 4 | Blow | Scene 1 | Verified | SA-0001 certified sequence |
| 5 | No Surprise - Edit | Scene 1 | Verified | SA-0001 certified sequence |
| 6 | Rx (Medicate) | Scene 1 | Verified | SA-0001 certified sequence |
| 7 | Affluenza | Scene 1 | Verified | SA-0001 certified sequence |
| 8 | Point to Prove | Scene 1 | Verified | SA-0001 certified sequence |
| 9 | Bitch Came Back | Scene 1 | Verified | SA-0001 certified sequence |
| 10 | Ambulance | Scene 1 | Verified | SA-0001 certified sequence |
| 11 | Savages (feat. Alice Cooper) | Scene 1 | Verified | SA-0001 certified sequence |
| 12 | Santa Monica | Scene 1 | Verified | SA-0001 certified sequence |
| 13 | Make Up Your Mind | Scene 1 | Verified | SA-0001 certified sequence |
| 14 | By the Way - Vocal Remix | Scene 1 | Verified | SA-0001 certified sequence |
| 15 | Say Nothing | Scene 1 | Verified | SA-0001 certified sequence |
| 16 | Medusa (Stone) | Scene 2 | Verified | SD-0002 locked position 1 plus VC-005 Scene 2 start |
| 17 | The One | Scene 2 | Inferred from explicit transition evidence | SD-0002; TES-0016; TA-0016 |
| 18 | Nothing Could Come Between Us | Scene 2 | Inferred from explicit transition evidence | SD-0002; TES-0017; TA-0017 |
| 19 | Not Meant to Be | Scene 2 | Verified | SD-0002 locked position 4; SA-0002 TA-0018 inventory |
| 20 | Say Goodbye | Scene 2 | Verified | SD-0002 locked position 5; SA-0002 TA-0019 inventory |
| 21 | Hate My Life | Scene 2 | Verified | SD-0002 decision SD-0002-005 |
| 22 | Hurricane | Scene 2 | Verified | SD-0002 decision SD-0002-007 |
| 23 | The Truth Is... (I Lied About Everything) | Scene 2 | Verified | SD-0002 decision SD-0002-006 |
| 24-58 | Unresolved | Scenes 2 through 4 | Unresolved | Scene map fixes ranges only |
| 59-78 | Unresolved archive songs | Archive | Unresolved | Archive boundary and membership rule only |

## Traceability for Known Changes from the Original Order

The prior conversation records this baseline excerpt from the uploaded original CSV:

| Original position | Song | Reconstructed position | Change evidence |
|---:|---|---:|---|
| 20 | The One | 17 | SD-0002 places the song second in Scene 2; TES-0016 and TA-0016 retain Medusa (Stone) to The One. |
| 21 | Nothing Could Come Between Us | 18 | SD-0002 places the song third in Scene 2; TES-0017 and TA-0017 accept The One to Nothing Could Come Between Us. |
| 22 | Say Goodbye | 20 | SD-0002 places Not Meant to Be before Say Goodbye and locks Say Goodbye as the Integration opener. |

No original position is claimed for any other song because the complete baseline CSV was not accessible. For those songs, the reconstruction records repository-backed positions but leaves baseline change comparison unresolved.

## Source Register

- VC-005 README, scene map and archive rules, main branch at parent commit 9506b5b.
- SA-0001 Scene 1 Ignition, certified 15-song sequence, blob 75279e874ba3ae4c57bbf5f54f5264899b9fb5c1.
- SD-0002 Scene 2 Design v1.0, Design Locked eight-song sequence, blob 83664c79a32bc64ab36916a799c7397861a19f15.
- SA-0002 Scene 2, transition inventory and global scene context, blob 58792e711501d5b5c2aecd9e08d21ca7b8db93e3.
- TES-0016 and TA-0016, Medusa (Stone) to The One retained and accepted.
- TES-0017 and TA-0017, The One to Nothing Could Come Between Us retained and accepted.
- Prior conversation baseline attestation, original positions 20 The One, 21 Nothing Could Come Between Us, and 22 Say Goodbye.

## Use Rule

TES-0018 must use `Nothing Could Come Between Us` to `Not Meant to Be`. It must not use the original CSV adjacency from `Nothing Could Come Between Us` to `Say Goodbye`.

