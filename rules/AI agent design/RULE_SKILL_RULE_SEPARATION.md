# Rule: Skill Rule Separation

## Purpose

Keep always-on behaviour rules separate from task-specific skills so the agent library remains clear, reusable and easy to maintain.

## Applies To

- new or revised rule files
- new or revised skill files
- agent specifications that reference both rules and skills
- project documentation explaining how to use Markdown rules and skills
- repository audits for overlap, duplication or missing guidance

## Rule Statement

Rules must define required behaviour and boundaries that apply whenever their conditions are met, while skills must define repeatable procedures for specific task types.

## Requirements

- Use a rule when the guidance is a constraint, boundary, expectation, safety requirement or quality standard.
- Use a skill when the guidance is a workflow, procedure, method, template or task-specific process.
- Keep rule statements short enough to be applied as behaviour.
- Keep skill processes explicit enough to be followed step by step.
- Cross-reference related rules and skills rather than copying full content between them.
- Avoid putting optional workflow steps into a rule unless they are mandatory checks.
- Avoid putting broad behavioural obligations into a skill if they must apply across many task types.
- When overlap is unavoidable, make the rule the authority for the behaviour and make the skill show how to apply it in that task context.
- Update progress and source registers according to the file actually completed.

## Decision Logic

If the guidance answers "what must the agent always do or avoid?", make or update a rule. If it answers "how does the agent complete this type of task?", make or update a skill. If both are needed, write the rule first as the stable boundary, then write the skill as the procedure that operates inside that boundary.

## Examples

- `RULE_PRIVACY_AND_SAFETY.md` sets privacy and safety obligations across many tasks.
- `SKILL_SAFETY_AND_RISK_CHECK.md` gives a process for reviewing a specific output for safety risks.
- `RULE_OUTPUT_REVIEW_CHECKLIST.md` defines the required final checks.
- `SKILL_OUTPUT_REVIEW.md` can provide a practical workflow for conducting a review.

## Non-Examples

- A rule file that contains a long task template but no behavioural requirement.
- A skill file that quietly changes core privacy boundaries.
- Copying the same source hierarchy text into every research-related file.
- Treating a one-off project note as a reusable skill.

## Interaction With Skills

- `skills/PD and leadership/SKILL_RULESET_DEVELOPMENT.md`
- `skills/PD and leadership/SKILL_AI_AGENT_DESIGN.md`
- `skills/Quality control/SKILL_OUTPUT_REVIEW.md`
- `rules/AI agent design/RULE_AGENT_FILE_STRUCTURE.md`
- `rules/AI agent design/RULE_OUTPUT_REVIEW_CHECKLIST.md`

## Quality Check

- Is this file a rule because it states required behaviour?
- Would a skill be more suitable if the content is mainly procedural?
- Are duplicated sections replaced with cross-references?
- Is the authority of each related file clear?
- Can a human maintain the rule and skill library without confusion?

## Sources

- Agents - OpenAI Agents SDK - https://openai.github.io/openai-agents-python/agents/ - Accessed 2026-05-17
- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
- Australian Framework for Generative Artificial Intelligence in Schools - Australian Government Department of Education - https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools - Accessed 2026-05-17
