# Skill: Request Intake

## Purpose

This skill allows the agent to interpret a teacher's request, identify the teaching context, detect missing information and decide whether to ask a clarification question or proceed with stated assumptions.

## When To Use

Use this skill at the start of any substantial request for:

- lesson plans, tutorials, worksheets or teacher notes
- assessment tasks, rubrics, marking guides or feedback
- curriculum, Australian Curriculum or SACE alignment
- practical science, software, robotics, data or electronics resources
- Word, LMS, spreadsheet, presentation or export-ready outputs
- parent, staff or student communication

## Inputs

Collect or infer the following information where relevant:

- year level or SACE stage
- subject, learning area and topic
- intended audience: student, teacher, parent, staff or leadership
- output type and format
- curriculum, achievement standard, performance standard or assessment criteria
- lesson time, sequence length or due date
- platform or tool, such as Word, Excel Online, Power BI, Scratch, micro:bit, GameMaker, Stile, Frog OS or Daymap
- available devices, equipment, chemicals, data sets or school constraints
- student ability range, support needs and extension needs
- safety, privacy, academic-integrity or assessment restrictions
- required tone, length, formatting and export requirements

## Process

1. Identify the requested deliverable in one sentence.
2. Extract all explicit context from the user's request.
3. Check nearby project files, supplied documents or current conversation context for additional constraints.
4. Classify the task by domain: curriculum, lesson design, assessment, marking, science, digital technologies, document output, communication or agent design.
5. Identify required rules and skills likely to apply.
6. Check for missing information that affects safety, privacy, assessment validity, curriculum alignment, platform accuracy or classroom usability.
7. Ask a concise clarification question only when the missing information is a genuine blocker.
8. If proceeding with assumptions, state the assumptions briefly before drafting or record them in the output where useful.
9. Keep the intake lightweight; do not turn intake into a long planning document unless the user asks for one.

## Output

The usual output is not a standalone document. The skill should produce an internal intake summary or a short user-facing clarification such as:

- `I will treat this as a Year 8 student-facing Scratch tutorial for beginners.`
- `I need the task sheet or rubric before I can mark this fairly.`
- `Assuming this is for Excel Online, I will avoid desktop-only features.`

When a formal intake record is useful, use this compact structure:

```markdown
## Intake Summary
- Request:
- Audience:
- Year level or stage:
- Subject/topic:
- Output:
- Constraints:
- Missing information:
- Assumptions:
- Relevant rules/skills:
```

## Quality Criteria

- The intake captures all important context supplied by the user.
- Clarification questions are necessary, specific and easy to answer.
- Assumptions are low risk and clearly stated where they matter.
- The next drafting step is aligned with the requested audience, subject and format.
- Safety, privacy, assessment and curriculum risks are not ignored.

## Related Rules

- `rules/Core behaviour/RULE_ROLE_AND_SCOPE.md`
- `rules/Core behaviour/RULE_FOLLOW_USER_CONTEXT.md`
- `rules/Core behaviour/RULE_CLARIFICATION.md`
- `rules/Core behaviour/RULE_NO_UNREQUESTED_EXPANSION.md`
- `rules/Core behaviour/RULE_AUSTRALIAN_LANGUAGE.md`
- `rules/Core behaviour/RULE_FINAL_CLEAN_OUTPUT.md`

## Example User Requests

- `Create a Year 8 Scratch tutorial for making a sprite jump.`
- `Mark this student response against the attached rubric.`
- `Turn this SACE Chemistry task into a Word-ready assessment sheet.`
- `Write relief teacher instructions for a Year 9 robotics lesson using micro:bits.`

## Failure Modes

- Asking unnecessary questions when the request is already clear.
- Ignoring supplied year level, platform or assessment criteria.
- Assuming SACE requirements without checking the relevant subject context.
- Drafting a full resource before checking safety, privacy or assessment blockers.
- Treating the agent's assumptions as facts.

## Completion Checklist

- Has the deliverable been identified?
- Has the audience been identified?
- Have year level, subject, platform and format constraints been captured?
- Have safety, privacy, academic-integrity and assessment risks been checked?
- Has the agent either asked a necessary question or stated reasonable assumptions?
- Are the next rules and skills clear?

## Sources

- Artificial intelligence (AI) in schools - information for parents and carers — South Australian Department for Education — https://www.education.sa.gov.au/parents-and-families/curriculum-and-learning/ai/artificial-intelligence-ai-in-schools-information-for-parents-and-carers — Accessed 2026-05-16
- General capabilities — Australian Curriculum, Assessment and Reporting Authority — https://www.australiancurriculum.edu.au/help/general-capabilities — Accessed 2026-05-16
- Learning and assessment plans — SACE Board of South Australia — https://www.sace.sa.edu.au/teaching/assessment/laps — Accessed 2026-05-16
- Quick guide: plain language — Australian Government Style Manual — https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language — Accessed 2026-05-16
