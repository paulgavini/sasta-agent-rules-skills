# Rule: Automated Run Mode

## Purpose

Define when an AI agent may continue work automatically and when it must pause for human review, approval or missing context.

## Applies To

- Codex-style build sessions
- batch completion of rule and skill files
- source research and register updates
- multi-step document or repository maintenance
- any workflow where the user asks the agent to keep progressing

## Rule Statement

The agent may proceed automatically through low-risk, reversible and clearly scoped work, but must pause or seek approval before actions that could cause privacy, safety, assessment, source, file-system or policy harm.

## Requirements

- Continue automatically when the user has clearly authorised ongoing work and the next task follows the established plan.
- Work one file or one coherent unit at a time when updating tracked rule and skill files.
- Research reputable sources where required before drafting.
- Update the completed file, progress file and source register after each completed unit.
- Preserve existing content and avoid unrelated refactors.
- Do not fabricate sources, file contents, policy positions or completion status.
- Pause before destructive actions, file moves, renames, deletion, external publication, high-risk automation or anything outside the requested scope.
- Pause when a missing local policy, student-data issue, assessment-integrity issue or safety issue cannot be handled by a conservative assumption.
- Keep a visible audit trail of sources, assumptions and unresolved issues.

## Decision Logic

Proceed automatically if the next step is clearly within scope, uses available sources and does not need a human policy decision. Pause if the task would change project structure, expose personal information, rely on uncertain authority, or create irreversible or externally visible effects. If a user explicitly asks to ignore a batch limit, remove that artificial batch limit but keep safety, privacy, source and file-preservation gates.

## Examples

- Continue drafting empty placeholder rules after the user says to proceed through all unfinished files.
- Research and cite official sources before completing a rule about agent guardrails.
- Stop and ask before deleting obsolete files, even if they appear unused.
- Mark uncertainty in `AGENT_BUILD_PROGRESS.md` where a local policy is needed.

## Non-Examples

- Publishing or sharing files externally without explicit approval.
- Moving files into a new folder structure to make the repository look neater.
- Using invented sources to avoid interrupting the run.
- Continuing through a privacy-risk task involving identifiable student data without review.

## Interaction With Skills

- `skills/Core workflow/SKILL_TASK_PLANNING.md`
- `skills/Core workflow/SKILL_SOURCE_RESEARCH.md`
- `skills/PD and leadership/SKILL_AI_AGENT_DESIGN.md`
- `rules/AI agent design/RULE_MANUAL_GATE_CHECKS.md`
- `rules/AI agent design/RULE_ORCHESTRATOR_CONTROL.md`

## Quality Check

- Did the user authorise continued work?
- Is the next action within the established scope?
- Are source, progress and completion records current?
- Would a human reasonably expect a pause before this action?
- Are privacy, safety and assessment-integrity risks handled?

## Sources

- OpenAI Agents SDK - https://openai.github.io/openai-agents-python/ - Accessed 2026-05-17
- Guardrails - OpenAI Agents SDK - https://openai.github.io/openai-agents-python/guardrails/ - Accessed 2026-05-17
- AI Risk Management Framework - National Institute of Standards and Technology - https://www.nist.gov/itl/ai-risk-management-framework - Accessed 2026-05-17
- Australian Framework for Generative Artificial Intelligence in Schools - Australian Government Department of Education - https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools - Accessed 2026-05-17
