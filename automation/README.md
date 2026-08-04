# CAS Automation

CAS Automation provides repository-native support for validating and indexing CAS engineering artifacts.

## Goals

- Validate artifact file names and required headings.
- Rebuild Markdown indexes from the repository contents.
- Flag incomplete or malformed records before they are treated as authoritative.
- Preserve human control over engineering decisions and certification.

## What it does not do

CAS Automation does not decide whether a transition, scene, Validation Case, or release should be certified. It validates structure and traceability only.

## Commands

```bash
python automation/cas_automation.py validate
python automation/cas_automation.py index
python automation/cas_automation.py all
```

## Supported artifacts

- Transition Audits: `TA-####_*.md`
- Engineering Decisions: `ED-####_*.md`
- Framework Contributions: `FC-####_*.md`
- Engineering Change Proposals: `ECP-####_*.md`
- Scene Analyses: `SA-####_*.md`
- Scene Scorecards: `SS-####_*.md`
- Scene Certifications: `SC-####_*.md`

## GitHub Actions

The workflow in `.github/workflows/cas-automation.yml` runs validation on pushes and pull requests. On manual dispatch, it can also rebuild generated indexes and commit them back to the selected branch.
