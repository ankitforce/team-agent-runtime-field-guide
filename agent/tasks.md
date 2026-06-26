# Agent Tasks

## Draft Runtime Review

Given a proposed team agent, assess:

- surface
- context access
- tool access
- write permissions
- memory policy
- budget controls
- logs
- verification
- human approval gates
- failure recovery

Return a concise review with strengths, risks, missing decisions, and next actions.

## Create Task Packet

Turn a vague request into a task packet using `templates/agent-ready-task-packet.md`.

## Build Risk Checklist

Use `checklists/team-agent-runtime-checklist.md` to identify missing controls before an agent is allowed to run in a shared team surface.
