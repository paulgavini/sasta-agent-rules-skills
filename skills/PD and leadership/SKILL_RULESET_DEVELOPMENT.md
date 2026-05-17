# Skill: Ruleset Development

## Purpose

This skill allows the agent to design, review and refine rulesets that guide consistent AI-assisted teaching, curriculum, assessment and workflow outputs.

## When To Use

Use this skill when the user asks for:

- a new rule file
- a rule hierarchy
- updates to existing rules
- governance for AI-assisted workflows
- consistency checks across skills and rules
- a project-wide ruleset for school use

## Inputs

- purpose of the ruleset
- audience: teacher, leader, student-facing agent or workflow agent
- existing rules, skills or policy documents
- jurisdiction, school and platform constraints
- risk areas: privacy, assessment, safety, curriculum or accuracy
- preferred source hierarchy
- output format

## Process

1. Define the behaviour the ruleset should control.
2. Identify the users, contexts and boundaries.
3. Check existing rules for overlap before creating a new one.
4. Use official or supplied sources for policy, curriculum, safety and privacy claims.
5. Write rules as observable requirements, not vague values.
6. Include decision logic, examples, non-examples and quality checks.
7. Link related skills and rules.
8. Preserve teacher judgement and local policy checks.
9. Record sources and unresolved questions.

## Output

```markdown
# Rule: Name

## Purpose
## Applies To
## Rule Statement
## Requirements
## Decision Logic
## Examples
## Non-Examples
## Interaction With Skills
## Quality Check
## Sources
```

## Quality Criteria

- The rule is specific enough to guide behaviour.
- It avoids duplication with existing rules.
- It uses reputable sources where needed.
- It preserves local teacher and school judgement.
- It includes practical examples and non-examples.
- Source and update records are complete.

## Related Rules

- `rules/Research/RULE_SOURCE_HIERARCHY.md`
- `rules/Research/RULE_RESEARCH_REQUIRED.md`
- `rules/Quality control/RULE_COMPLETENESS_CHECK.md`
- `rules/Quality control/RULE_NO_HALLUCINATED_FILES.md`
- `skills/Core workflow/SKILL_SOURCE_RESEARCH.md`

## Sources

- Australian Framework for Generative Artificial Intelligence in Schools - Australian Government Department of Education - https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools - Accessed 2026-05-17
- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
- Australian Professional Standards for Teachers - Australian Institute for Teaching and School Leadership - https://aitsl.edu.au/docs/default-source/teach-documents/australian-professional-standards-for-teachers - Accessed 2026-05-17
