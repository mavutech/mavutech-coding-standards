# Reports Skill

The reports skill provides a consistent structure for reports, plans, assessments, proposals, and implementation roadmaps.

## What It Produces

Every report or plan includes:

- Summary
- Key points
- A useful table
- Risks with mitigations
- Recommendations
- Next steps

The skill uses plain language, separates facts from assumptions, and requires approval before implementation begins.

## How to Use It

When this repository is mounted as `.standards`, reference the skill in your request:

```text
Use #file:.standards/reports/SKILL.md and create a report on [topic].
```

For a plan:

```text
Use #file:.standards/reports/SKILL.md and create an implementation plan for [change].
```

The implementation-plan workflow also checks the relevant files under `.standards/` before recommending code or technical changes.

## Files in This Folder

```text
reports/
  README.md    # Usage and expected output
  SKILL.md     # Reusable report and plan instructions
```

