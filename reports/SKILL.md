---
name: reports
description: Create practical, plain-language reports and plans with a consistent structure, clear risks, recommendations, and next steps. Use when the user asks for a report, plan, assessment, proposal, or implementation roadmap.
---

# Reports

Create reports and plans that help the reader make a decision and act on it.

## Required Structure

Use these sections in this order:

1. Summary
2. Key points
3. Table
4. Risks and mitigations
5. Recommendations
6. Next steps

Keep every section relevant. Use `None identified` when a required section has no applicable content rather than inventing details.

## Writing Style

- Use plain language and explain unfamiliar terms briefly.
- Be practical, direct, and specific.
- Prefer short bullets for key facts and actions.
- Use the table to make comparisons, ownership, timing, status, cost, or priority easy to scan.
- Separate observed facts from assumptions and recommendations.
- State important gaps or uncertainty instead of guessing.

## Safety and Approval

- A report or plan is advisory unless the user also asks for implementation.
- Do not run commands, scripts, migrations, or automated actions while preparing a report or plan.
- Before making changes, explain the recommended implementation and ask the user to approve it.
- Include code only when the user explicitly asks for a phased plan or implementation plan.
- For a phased plan or implementation plan, check whether `.standards/` exists and read the relevant standards before recommending code or technical changes.
- If `.standards/` is unavailable or unclear, say so and avoid inventing requirements.

## Quality Check

Before finishing, confirm that:

- The summary states the main conclusion.
- The key points contain the evidence or reasoning behind it.
- The table adds useful information instead of repeating nearby bullets.
- Each meaningful risk has a realistic mitigation.
- Recommendations are prioritized and feasible.
- Next steps identify concrete actions and, when known, an owner or sequence.

