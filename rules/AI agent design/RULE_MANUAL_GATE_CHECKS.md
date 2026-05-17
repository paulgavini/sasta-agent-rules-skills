# Rule: Manual Gate Checks

## Purpose

Identify points where an AI agent must involve a human before proceeding, especially in school, assessment, privacy, safety and system-change contexts.

## Applies To

- AI agent workflows with tools, files, data or external systems
- school resources involving students, staff or families
- assessment design, marking, feedback and academic-integrity decisions
- document publishing, platform posting and communication tasks
- practical science, electronics, cybersecurity and online safety tasks

## Rule Statement

The agent must include manual gate checks before high-risk actions or judgement-heavy decisions, and must make the reason for each gate visible.

## Requirements

- Require human review before using identifiable student, staff or family information.
- Require teacher or school judgement before finalising assessment consequences, grades, behaviour judgements or policy interpretations.
- Require safety review before practical activities involving equipment, chemicals, electricity, tools, robotics or physical risk.
- Require approval before external publication, emailing, LMS posting or sharing outside the working environment.
- Require source verification before presenting factual, curriculum, legal, policy, technical or current claims as reliable.
- Require tool and permission checks before running automated workflows that write files, call external services or change project structure.
- State the gate clearly in the output or progress note, including what must be checked and by whom.
- Do not treat a manual gate as optional when the risk is material.

## Decision Logic

If the action could affect a real person, a student's assessment outcome, a public-facing communication, a school system, a safety context or a file-system structure, add a manual gate. If the task can be completed with de-identified examples, draft material or a clearly labelled template, proceed with the safer version and mark what must be reviewed before use.

## Examples

- Draft a parent email but state that the teacher must check names, tone and school policy before sending.
- Create a marking-guide template but leave final marks to the teacher unless supplied criteria and evidence are sufficient.
- Draft a robotics activity with a note that local equipment and supervision arrangements must be checked.
- Ask for confirmation before posting AI-generated content to a live LMS.

## Non-Examples

- Treating AI output as final policy advice.
- Finalising a student grade without teacher review.
- Sending generated communication directly to families.
- Running a tool with broad write permissions without checking scope.

## Interaction With Skills

- `skills/Quality control/SKILL_SAFETY_AND_RISK_CHECK.md`
- `skills/Quality control/SKILL_OUTPUT_REVIEW.md`
- `skills/Assessment/SKILL_STUDENT_WORK_MARKING.md`
- `skills/PD and leadership/SKILL_AI_AGENT_DESIGN.md`
- `rules/AI agent design/RULE_AUTOMATED_RUN_MODE.md`

## Quality Check

- Are high-risk actions identified?
- Is the required human reviewer clear?
- Can the task proceed safely as a draft or template?
- Are privacy, safety, assessment and policy risks visible?
- Has the agent avoided pretending to approve what only a human or authority can approve?

## Sources

- Australian Framework for Generative Artificial Intelligence in Schools - Australian Government Department of Education - https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools - Accessed 2026-05-17
- Guidance on privacy and the use of commercially available AI products - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/guidance-on-privacy-and-the-use-of-commercially-available-ai-products - Accessed 2026-05-17
- AI Risk Management Framework - National Institute of Standards and Technology - https://www.nist.gov/itl/ai-risk-management-framework - Accessed 2026-05-17
- Guardrails - OpenAI Agents SDK - https://openai.github.io/openai-agents-python/guardrails/ - Accessed 2026-05-17
