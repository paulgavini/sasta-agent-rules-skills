# Rule: Follow User Context

## Purpose

Ensure the agent uses the user's supplied teaching context before making assumptions. This rule prevents generic resources that ignore year level, subject, curriculum, platform, assessment conditions, school constraints or formatting requirements.

## Applies To

- Lesson plans, tutorials, worksheets, teacher notes and relief lessons
- Assessment tasks, rubrics, marking guides, feedback and reports
- SACE Stage 1 and Stage 2 resources
- Digital Technologies, software, robotics, spreadsheet and data-analysis instructions
- Document, Word, LMS and export-ready outputs
- Any task where the user has supplied constraints or classroom context

## Rule Statement

The agent must treat the user's stated context as authoritative for the task and must apply it before adding general best practice, researched information or default assumptions.

## Requirements

- Use stated year level, subject, topic, curriculum, assessment type, output format, platform, lesson length, device context and student ability level.
- Preserve supplied terminology, school conventions and required formatting unless they conflict with safety, privacy, academic integrity or curriculum accuracy.
- Check whether the task is for students, teachers, parents, staff or leadership before choosing tone and detail.
- Confirm or flag missing context only when the missing information would materially affect accuracy, safety, assessment validity or usability.
- Apply SACE subject outline, learning and assessment plan or performance-standard context when supplied or clearly requested.
- Avoid replacing supplied context with a more generic version of the task.
- Do not assume access to software features, devices, accounts, lab equipment or student data that the user has not supplied.

## Decision Logic

First, identify all explicit context in the request. Second, infer low-risk context only when it is strongly implied by file names, folder names, previous project structure or the user's wording. Third, ask a clarification question if the missing context could change the task design, assessment judgement, safety advice, privacy handling or platform instructions. If the missing context is low risk, state the assumption briefly and proceed.

## Examples

- If the user says "Year 8 Scratch on iPads", keep instructions touch-friendly, browser/classroom appropriate and beginner-level.
- If the user supplies a rubric, mark against that rubric rather than inventing new criteria.
- If the user asks for SACE Chemistry, use SACE terminology and check for subject-specific assessment expectations.
- If the user requests Word-ready output, use simple headings, plain tables and editable text rather than complex formatting.

## Non-Examples

- Creating a senior secondary task when the user asked for Year 8.
- Adding desktop Excel features when the user specified Excel Online.
- Ignoring a supplied word limit, marking guide or output format.

## Interaction With Skills

- `skills/Core workflow/SKILL_REQUEST_INTAKE.md`
- `skills/Core workflow/SKILL_TASK_PLANNING.md`
- `skills/Core workflow/SKILL_CURRICULUM_ALIGNMENT.md`
- `skills/Lesson design/SKILL_STUDENT_FACING_TUTORIAL.md`
- `skills/Assessment/SKILL_RUBRIC_DESIGN.md`
- `skills/Documents/SKILL_WORD_EXPORT_FORMATTING.md`

## Quality Check

- Have all supplied constraints been identified and used?
- Is the tone matched to the intended audience?
- Are year level, curriculum, assessment and platform assumptions explicit?
- Would the output still work in the user's stated classroom or school system?
- Have high-risk gaps been clarified or clearly flagged?

## Sources

- Artificial intelligence (AI) in schools - information for parents and carers — South Australian Department for Education — https://www.education.sa.gov.au/parents-and-families/curriculum-and-learning/ai/artificial-intelligence-ai-in-schools-information-for-parents-and-carers — Accessed 2026-05-16
- General capabilities — Australian Curriculum, Assessment and Reporting Authority — https://www.australiancurriculum.edu.au/help/general-capabilities — Accessed 2026-05-16
- Australian Professional Standards for Teachers — Australian Institute for Teaching and School Leadership — https://aitsl.edu.au/docs/default-source/apst-resources/australian_professional_standard_for_teachers_final.pdf — Accessed 2026-05-16
- Learning and assessment plans - Stage 1 and Stage 2 — SACE Board of South Australia — https://www.sace.sa.edu.au/coordinating/admin/information-sheets/57 — Accessed 2026-05-16
