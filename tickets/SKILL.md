---
name: tickets
description: Draft, create, update, or review work tickets and book-by-book ticket series. Enforce MavuTech title formatting, description, problem and solution statements, testable acceptance criteria, and technical details when needed, in GitHub or another tracker.
---

# Tickets

Apply this contract to every ticket you create or substantively update. Use plain language and keep detail proportional to the work. Ticket bodies use the structure below, not the six-section reports format.

## Required title

Use `AREA - CODE - Action`, for example **FE - SE01 - Add button**.

- `AREA` identifies the work area. Use the project's existing prefixes; `FE` means frontend and `BE` means backend. Use an appropriate established prefix for content, QA, or other work rather than calling everything frontend.
- `CODE` is the project's series or ticket code, such as `SE01`. Follow the existing naming and numbering convention; do not invent what `SE` stands for. For a new series, state the proposed convention explicitly.
- `Action` starts with a concrete verb and identifies the outcome. Name the book or feature when needed to distinguish tickets. Correct spelling in new titles; the example is **Add**, not **Addd**.
- Before allocating a code, check existing open and closed tickets in the relevant series. Do not reuse an existing full ticket code or renumber established tickets. A draft may carry a proposed code until availability is checked; the tracker issue number is separate.

## Required body

Every ticket must have these four headings with substantive content:

### Description

State what work is included, who or what it benefits, and the completion boundary. Identify the specific book, feature, or affected behavior. Add exclusions only when they prevent likely misunderstanding.

### Problem

Describe the current behavior or gap and its impact. Separate observed facts from assumptions. Do not invent failures or research evidence.

### Solution

Describe the intended result and enough of the approach for the next owner to act. Keep unconfirmed design choices labeled as proposals. Creating a ticket does not authorize implementing it.

### Acceptance criteria

Use unchecked checkboxes for independently verifiable outcomes. State observable behavior, expected content, or concrete evidence of completion. Include relevant failure cases and preservation requirements. Avoid vague criteria such as "works correctly" or "tests pass" without specifying what is checked. Do not mark criteria complete before verification.

## Conditional details

Add **Technical details** whenever implementation depends on identifiers, data formats, interfaces, affected components, constraints, migrations, access rules, or non-obvious validation. Include verified paths or names where useful; label proposed changes. Omit this section when it adds no information. Do not pad it with guessed architecture or boilerplate code.

Add dependencies, parent/related ticket links, owner, estimates, or references when relevant or required by the project. Distinguish named agent responsibilities from actual tracker accounts; never invent an assignee mapping. Label estimates and their assumptions rather than presenting them as measurements.

For implementation details, check the project's `.standards/` and read the relevant standards. If absent, use an available MavuTech standards checkout or workspace copy and name that source. If neither is accessible, state the gap instead of guessing compliance.

## Ticket series

- Use one shared parent or prerequisite ticket for common infrastructure and decisions when that avoids duplicating work.
- Give each book or independently deliverable unit its own title, identity, scope, and acceptance criteria. Use verified catalogue IDs and counts when available; do not assume every catalogue entry is a complete work or omit prefaces and supplements silently.
- Keep each child understandable on its own. Link shared requirements while retaining the child's essential acceptance criteria and completion boundary.
- Preserve the requested team size and task scope. Do not add meetings, reviewers, or implementation work merely to fill a template.

## Quality gate and tracker workflow

Before creating or updating a ticket, verify the title format, meaningful Description/Problem/Solution sections, testable acceptance criteria, and any necessary Technical details. Repair missing information from available evidence. If a material requirement is unknown, identify the open decision and mark the ticket as draft or blocked rather than claiming it is ready for implementation.

Use existing authorization to create or update tickets; do not ask for the same approval again. A request to draft or review tickets alone does not authorize publishing them. Do not start implementation or deployment from a ticket-writing request.

When publishing is authorized, check for an existing matching ticket before creating one. Preserve unrelated discussion and completed evidence when editing. Create in the confirmed repository and add to the requested board when authorized and available. Read back the saved title and body; verify board membership separately. After an ambiguous failure, check whether creation succeeded before retrying. If access fails again after one appropriate correction, stop that mutation and return the completed draft and exact blocker.

Report actual ticket links and distinguish saved tickets, board additions, and pending drafts. This skill enforces agent authoring behavior; it does not install tracker-side validation or prevent other users from creating incomplete issues.

For status changes, completion, and retention, follow the available MavuTech `docs/standards/ticket-lifecycle.md`. Keep this skill focused on ticket quality rather than duplicating that lifecycle.
