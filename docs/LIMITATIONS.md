# Limitations and Safety Boundaries

Astra Harness Builder is a deterministic text assembler, not an execution environment.

It does not:

- call GPT-6 Astra or any other model;
- translate or rewrite task content;
- execute tools or install skills;
- grant or revoke permissions;
- enforce budgets, retries, or delegation limits;
- guarantee prompt-injection resistance;
- comprehensively detect secrets or malicious input;
- replace review, access control, sandboxing, logging, or rollback procedures.

Mixed-language text, source code, product names, and legitimate identifiers can resemble suspicious input. Heuristic warnings are advisory and may produce false positives or false negatives.

For production use, enforce permissions in the tool layer, verify the real target before mutation, preserve rollback paths, and retain auditable evidence of tests and approvals.
