# Astra Harness Builder

Astra Harness Builder is an independent, browser-based workbench for composing production-oriented instructions for GPT-6 Astra. It turns operational choices—autonomy, delegation, permissions, verification, and writing style—into a structured prompt package.

**[Open Astra Harness Builder](https://astra-harness-builder.llm48.chatgpt.site)**

This project is not an OpenAI or Microsoft product. It does not call a model, execute tools, store credentials, or enforce runtime permissions. It generates instruction text locally in the browser; the operator remains responsible for the actual agent configuration and approvals.

## Start here

1. Open the live application.
2. Choose a preset or keep the defaults.
3. Describe the task, allowed targets, and observable acceptance criteria in English.
4. Configure autonomy, delegation, permissions, verification, and response style.
5. Resolve blocking checks and review warnings.
6. Copy an output or export the five-file ZIP bundle.

Read [Quick Start](docs/QUICKSTART.md) for a guided workflow and [Configuration Reference](docs/CONFIGURATION.md) for every control group.

## Generated outputs

- Full operational instruction
- Compact task prompt
- Reusable `AGENTS.md` snippet
- Machine-readable configuration
- Usage notes

See [Output Reference](docs/OUTPUTS.md) before merging generated instructions into an existing project.

## Documentation

- [Quick Start](docs/QUICKSTART.md)
- [Configuration Reference](docs/CONFIGURATION.md)
- [Output Reference](docs/OUTPUTS.md)
- [Limitations and Safety Boundaries](docs/LIMITATIONS.md)
- [Production Task Example](examples/production-task.md)
- [Research Task Example](examples/research-task.md)
- [Coding Task Example](examples/coding-task.md)

## Design principles

- Bound autonomy instead of requesting unrestricted initiative.
- Give each task one accountable owner.
- Separate delegation depth from total subagent count.
- Require approval for consequential external actions.
- Define observable completion criteria before execution.
- Cap retries and escalate blockers instead of looping indefinitely.
- Treat prompts as instructions, not as a security boundary.

The control categories are informed by OpenAI's GPT-6 Astra prompting guidance, reviewed September 8, 2026. Additional checks and limits are independent design choices and do not imply OpenAI endorsement.

## License

MIT. See [LICENSE](LICENSE).
