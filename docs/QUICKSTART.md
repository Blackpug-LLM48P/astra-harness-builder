# Quick Start

## 1. Define the task

State one concrete objective. Name the systems, repositories, documents, or environments the agent may touch. Add acceptance criteria that another person can verify.

Avoid vague requests such as “handle everything” or “make it production-ready” without defining evidence of completion.

## 2. Choose an operating profile

Use a conservative preset when the task includes external writes, production systems, sensitive data, or unclear ownership. Increase initiative only when the scope and rollback path are explicit.

## 3. Configure delegation

Delegation is useful for bounded, independent subtasks. Set both a maximum depth and a total subagent ceiling. Keep one accountable owner for the final result.

## 4. Configure permissions

Separate read-only investigation from mutation. Require approval for public communication, deployment, deletion, purchases, credential changes, or other consequential actions.

## 5. Define verification

Specify the tests, checks, or evidence required before the task is complete. Include a retry limit and an escalation rule for blocked work.

## 6. Review and export

Resolve blocking checks, read every warning, and inspect the generated text. Export the bundle only after confirming that targets, permissions, and acceptance criteria match the real environment.

## 7. Apply outside the builder

Paste the selected output into the appropriate agent or project instruction surface. Configure actual tool permissions separately. The generated prompt cannot grant, restrict, or verify real system access by itself.
