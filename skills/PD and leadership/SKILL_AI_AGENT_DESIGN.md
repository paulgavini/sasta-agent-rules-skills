# Skill: AI Agent Design

## Purpose

This skill allows the agent to design education-focused AI agents with clear scope, safe boundaries, source expectations, workflow logic and teacher oversight.

## When To Use

Use this skill when the user asks for:

- an AI agent specification
- a custom GPT or Codex-style instruction set
- a school workflow agent
- AI guardrails for teachers or students
- role, rule and skill architecture
- review of an existing AI assistant design

## Inputs

- agent purpose and user group
- tasks the agent may and may not perform
- required rules, skills, sources and tools
- privacy, assessment, safety and curriculum constraints
- escalation or human-review points
- output formats and logging needs
- local school or system policy

## Process

1. Define the agent's role and non-role.
2. Identify users, audiences and high-risk use cases.
3. Separate always-on behaviour rules from optional task skills.
4. Specify required research and source hierarchy.
5. Add privacy, safety, assessment integrity and hallucination controls.
6. Define clarification and refusal triggers.
7. Design output formats that suit the workflow.
8. Include human review for judgement-heavy or high-stakes decisions.
9. Add testing scenarios and maintenance notes.

## Output

```markdown
# AI Agent Specification

## Purpose
## Users
## Allowed Tasks
## Boundaries
## Required Rules
## Required Skills
## Source Expectations
## Human Review Points
## Test Scenarios
```

## Quality Criteria

- Scope is clear and bounded.
- Risks are handled before convenience.
- The agent does not replace teacher judgement.
- Sources and verification expectations are explicit.
- Student privacy and assessment integrity are protected.
- The design can be tested with realistic scenarios.

## Related Rules

- `rules/Core behaviour/RULE_ROLE_AND_SCOPE.md`
- `rules/Core behaviour/RULE_CLARIFICATION.md`
- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`
- `rules/Quality control/RULE_NO_HALLUCINATED_FILES.md`
- `rules/Research/RULE_RESEARCH_REQUIRED.md`

## Sources

- Australian Framework for Generative Artificial Intelligence in Schools - Australian Government Department of Education - https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools - Accessed 2026-05-17
- Guidance on privacy and the use of commercially available AI products - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/guidance-on-privacy-and-the-use-of-commercially-available-ai-products - Accessed 2026-05-17
- Artificial intelligence (AI) in schools - information for parents and carers - South Australian Department for Education - https://www.education.sa.gov.au/parents-and-families/curriculum-and-learning/ai/artificial-intelligence-ai-in-schools-information-for-parents-and-carers - Accessed 2026-05-17
