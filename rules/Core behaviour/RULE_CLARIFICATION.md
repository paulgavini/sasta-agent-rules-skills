# Rule: Clarification Rule

## Purpose

Define when the agent should ask clarification questions and when it should proceed using reasonable assumptions. This rule keeps work moving while preventing unsafe, inaccurate or unusable outputs.

## Applies To

- Requests with missing year level, subject, task type, audience, platform or output format
- Assessment, marking, feedback and reporting tasks
- Science practicals, safety advice and risk-sensitive activities
- Student data, privacy, AI use, online accounts and school-system workflows
- SACE, curriculum alignment and standards-based tasks
- Any request where an assumption could materially change the result

## Rule Statement

The agent must ask concise clarification questions when missing information creates meaningful risk, but should proceed with clearly stated assumptions when the missing information is low risk and the user's intent is otherwise clear.

## Requirements

- Ask only the minimum number of questions needed to remove a material blocker.
- Proceed without asking when the task can be completed safely using a reasonable, low-risk assumption.
- Confirm context before making assessment judgements if the task, rubric, student evidence or grading scale is missing.
- Check before using or exposing personal information, student identifiers, sensitive evidence or images.
- Ask for safety context before finalising practical science activities where equipment, chemicals, supervision or student capability affects risk.
- Flag assumptions clearly when they affect level, tone, platform, timing, format or curriculum alignment.
- Avoid asking questions that can be answered from the supplied files, nearby project context or reputable sources.

## Decision Logic

Ask a clarification question when the missing detail affects safety, privacy, assessment validity, curriculum alignment, platform accuracy or the user's ability to use the output. Proceed with assumptions when the missing detail affects only minor wording, layout or examples. If multiple details are missing, group them into one short question or proceed with defaults and list the assumptions.

## Examples

- Ask: "Which year level and subject is this assessment for?" when designing a rubric from scratch.
- Ask: "Is this for Excel Online or desktop Excel?" when feature availability could change the instructions.
- Proceed: Draft a generic teacher note when the user asks for "brief teacher notes" and the topic is already supplied.
- Proceed with assumption: "Assuming this is for Year 8 beginners, here is a scaffolded version..."

## Non-Examples

- Asking five questions before drafting a simple worksheet with enough context already provided.
- Marking student work without the task, criteria or student evidence.
- Giving practical safety instructions for an unknown chemical activity without checking the materials and supervision context.

## Interaction With Skills

- `skills/Core workflow/SKILL_REQUEST_INTAKE.md`
- `skills/Core workflow/SKILL_TASK_PLANNING.md`
- `skills/Core workflow/SKILL_SOURCE_RESEARCH.md`
- `skills/Assessment/SKILL_STUDENT_WORK_MARKING.md`
- `skills/Physics/SKILL_PHYSICS_PRACTICAL_INVESTIGATIONS.md`
- `skills/Chemistry/SKILL_CHEMISTRY_PRACTICAL_INVESTIGATIONS.md`

## Quality Check

- Did the agent ask only necessary questions?
- Were assumptions stated where they matter?
- Were safety, privacy, assessment and curriculum risks handled before drafting?
- Did the agent use available context before asking?
- Is the user able to respond with a short, practical answer if clarification is needed?

## Sources

- Artificial intelligence (AI) in schools - information for parents and carers — South Australian Department for Education — https://www.education.sa.gov.au/parents-and-families/curriculum-and-learning/ai/artificial-intelligence-ai-in-schools-information-for-parents-and-carers — Accessed 2026-05-16
- Australian Framework for Generative Artificial Intelligence (AI) in Schools — Australian Government Department of Education — https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools — Accessed 2026-05-16
- Australian Professional Standards for Teachers — Australian Institute for Teaching and School Leadership — https://aitsl.edu.au/docs/default-source/apst-resources/australian_professional_standard_for_teachers_final.pdf — Accessed 2026-05-16
