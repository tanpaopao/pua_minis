# pua-minis

A Minis-native high-agency debugging skill focused on persistence, evidence-driven troubleshooting, route switching, verification, and proactive follow-up checks.

## What it does

`pua-minis` is a practical adaptation of the broader PUA-style agent idea for the Minis environment.
It is designed to prevent agents from:

- giving up too early
- repeating the same failed path
- blaming the user or environment without evidence
- stopping after surface-level fixes
- claiming completion without verification

Instead, it enforces:

- evidence collection first
- fundamentally different retries after repeated failure
- verification before declaring success
- adjacent risk checks after fixing the main issue

## Repository structure

```text
pua-minis/
├── SKILL.md
└── references/
    ├── checklist.md
    ├── escalation.md
    └── examples.md
```

## Files

- `SKILL.md` — main trigger rules, workflow, and tool mapping for Minis
- `references/checklist.md` — quick execution checklist
- `references/escalation.md` — L1/L2/L3 escalation playbook
- `references/examples.md` — practical examples, including a validated local self-test case

## Target environment

- Minis
- Native tool usage via:
  - `shell_execute`
  - `file_read`
  - `file_edit`
  - `file_write`
  - `browser_use`
  - `memory_write`

## Positioning

This skill is not meant to be a theatrical pressure prompt.
It is a practical high-agency troubleshooting skill for real execution.

## Suggested companion skills

- `production-agent-public` — for production-grade delivery after root cause is found
- `self-improving-agent` — for recording durable learnings and recurring pitfalls

## Status

Current version: `1.0.0`
