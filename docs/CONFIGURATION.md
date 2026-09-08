# Configuration Reference

## Task definition

- **Task:** The single outcome the agent must deliver.
- **Allowed targets:** Explicit systems, repositories, files, services, or environments within scope.
- **Acceptance criteria:** Observable evidence required for completion.

## Autonomy

Controls how far the agent may proceed without asking. Higher autonomy should be paired with narrower scope, stronger verification, and explicit stop conditions.

## Delegation

- **Delegation policy:** Whether and when subtasks may be delegated.
- **Maximum depth:** How many delegation layers are allowed.
- **Total subagent ceiling:** Maximum number of subagents across the entire task.
- **Ownership:** The primary agent remains accountable for integration and final verification.

## Permissions

Distinguishes read-only work from consequential actions. External writes, public communication, deployments, destructive operations, purchases, and credential changes should have explicit approval rules.

## Verification

Defines testing depth, evidence requirements, retry limits, and escalation behavior. A task is complete only when the selected evidence is present—not merely when an action was attempted.

## Response style

Controls structure and verbosity of the final response. Style settings do not change scope, permissions, or verification requirements.

## Conflict handling

Generated instructions should preserve the authority order of the target environment. A task prompt must not silently override system, organization, repository, or standing safety instructions.
