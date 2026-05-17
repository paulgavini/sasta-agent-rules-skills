# Rule: Orchestrator Control

## Purpose

Keep multi-agent or tool-assisted workflows controlled by a clear orchestrator so tasks are delegated deliberately, results are checked and final output remains coherent.

## Applies To

- multi-agent workflows
- Codex sessions using sub-agents or specialist workers
- custom GPT or assistant designs with tools and handoffs
- agent systems that combine research, drafting, reviewing and file updates
- workflows that need a final human-facing deliverable

## Rule Statement

The orchestrating agent must retain responsibility for scope, delegation, source standards, risk checks, integration and final output.

## Requirements

- Define the orchestrator's role before delegating work.
- Delegate only bounded subtasks with clear inputs, outputs and file ownership.
- Use specialist agents or tools only when they materially improve the workflow.
- Keep tool permissions and delegated scope as narrow as practical.
- Require subtask outputs to include sources, assumptions, changed files and unresolved issues where relevant.
- Review delegated outputs before integrating them into final files or user-facing responses.
- Keep a single final answer or completed artefact coherent, rather than stitching together unreviewed fragments.
- Do not let delegated agents override higher-priority rules, privacy requirements, manual gates or user constraints.
- Log completed work and source use in the project registers when the workflow requires it.

## Decision Logic

Use a central orchestrator when a task has multiple parts, tools, sources or files. Delegate only side tasks that can be checked and integrated. If a subtask is urgent, sensitive, ambiguous or tightly coupled to the final decision, keep it under direct orchestrator control. If delegated output conflicts with sources, user instructions or project rules, resolve the conflict before continuing.

## Examples

- Assign one worker to draft a bounded rule file while the orchestrator researches sources and later reviews the patch.
- Use a specialist review step for privacy risks, then integrate only the parts supported by the project rules.
- Reject a delegated suggestion to rename files when the user explicitly prohibited renaming.
- Keep final progress reporting in one consistent voice and structure.

## Non-Examples

- Delegating the whole task without checking the result.
- Allowing a specialist agent to broaden the project scope.
- Combining unverified outputs from several agents into final documentation.
- Giving a tool broader access than the subtask needs.

## Interaction With Skills

- `skills/Core workflow/SKILL_TASK_PLANNING.md`
- `skills/PD and leadership/SKILL_AI_AGENT_DESIGN.md`
- `skills/Quality control/SKILL_OUTPUT_REVIEW.md`
- `rules/AI agent design/RULE_AUTOMATED_RUN_MODE.md`
- `rules/AI agent design/RULE_MANUAL_GATE_CHECKS.md`

## Quality Check

- Is there a clear owner of the overall workflow?
- Are delegated tasks bounded and reviewable?
- Are tool permissions proportionate?
- Has the orchestrator checked source support and risks?
- Does the final output read as one coherent deliverable?

## Sources

- Agent orchestration - OpenAI Agents SDK - https://openai.github.io/openai-agents-python/multi_agent/ - Accessed 2026-05-17
- Handoffs - OpenAI Agents SDK - https://openai.github.io/openai-agents-python/handoffs/ - Accessed 2026-05-17
- OWASP Top 10 for Large Language Model Applications - OWASP Foundation - https://owasp.org/www-project-top-10-for-large-language-model-applications/ - Accessed 2026-05-17
- AI Risk Management Framework - National Institute of Standards and Technology - https://www.nist.gov/itl/ai-risk-management-framework - Accessed 2026-05-17
