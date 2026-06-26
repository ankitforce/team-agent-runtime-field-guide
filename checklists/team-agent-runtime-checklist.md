# Team Agent Runtime Checklist

## Surface

- Where does the agent live?
- Is it invoked by a person, schedule, event, or ambient channel mention?
- Can users see whether the agent is active, blocked, or done?

## Context

- Which channels, files, tickets, docs, repos, and databases can it read?
- Is context scoped by team, project, channel, or task?
- Can a user inspect the context used for a run?

## Tools

- Which tools can it call?
- Which actions are read-only?
- Which actions can change external state?
- Are destructive actions separately gated?

## Permissions

- Who can invoke the agent?
- Who can approve high-risk steps?
- Are permissions least-privilege by default?
- Are identities separated by channel, workspace, or use case?

## Memory

- What can the agent remember?
- Where is memory stored?
- How is memory corrected or deleted?
- Is retention tied to a business purpose?

## Budget

- Are token, time, tool, and dollar limits defined?
- Can a run be paused or cancelled?
- Are runaway loops detected?

## Logs

- Are prompts, retrieved context, tool calls, outputs, failures, approvals, and costs logged?
- Can Support or Ops reconstruct what happened?
- Are logs safe to retain?

## Verification

- What evidence proves the work was completed?
- Are tests, diffs, citations, or checks attached?
- Is human review required before publish, merge, send, or delete?

## Recovery

- What happens after partial failure?
- Can the agent retry safely?
- Are idempotency and rollback rules clear?
