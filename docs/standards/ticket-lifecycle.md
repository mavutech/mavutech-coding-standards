# Ticket lifecycle and definition of done

Use this standard for stories, bugs, technical tasks, and verification work in any tracker. Map the steps to the project's available statuses and resolution reasons.

## Create and start

- Record the outcome, observable acceptance criteria, dependencies, and required approvals. Link technical work to its parent outcome.
- Name the completion boundary when it matters. Implementation, review, staging verification, and release can be separate tickets or milestones.
- Use the project's equivalent of In progress while work is active. Use In review or Blocked when the next action is verification, a decision, or an unmet dependency.

## Verify and complete

1. Check each required acceptance criterion against the delivered change. Record the actual result and link the change, tests, review, or other evidence as applicable.
2. Obtain the approvals required by the ticket or project. A material failed or unverified criterion, or an outstanding approval, keeps that ticket open. Record the blocker and next step.
3. Set the technical ticket to the tracker's equivalent of Done or Closed as completed when its own boundary is met. State the environment and completion boundary in the handoff. Link any separate release work that is still pending.
4. Complete a parent story once its required children and story-level acceptance criteria and approvals are complete. Resolve optional or deferred work explicitly and link its follow-up where applicable.
5. Reopen a completed ticket if the original acceptance criteria were missed. Link a new ticket for a separate regression or a new requirement when that better preserves the record.

If the work is cancelled, duplicated, or superseded, use the appropriate resolution and link the replacement when one exists. Record the reason so it remains distinguishable from completed work.

## Keep the record

Retain completed tickets, their links, and decisions as project history. Archive them from active views when useful. Delete a ticket only under an authorized retention, privacy, or security exception. Apply the relevant retention and access rules to linked artifacts and evidence.

Record the tested change or version, checks and outcomes, approvals, and any unresolved work. Use approved private evidence locations for sensitive material and keep credentials and personal records out of ticket text. When the tracker cannot be updated, state the verified completion result and the specific status change still pending.
