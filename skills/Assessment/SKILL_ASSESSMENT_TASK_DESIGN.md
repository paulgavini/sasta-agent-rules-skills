# Skill: Assessment Task Design

## Purpose

This skill allows the agent to design clear, valid and classroom-ready assessment tasks aligned to curriculum, SACE requirements or supplied school criteria.

## When To Use

Use this skill when the user asks for:

- a new assessment task
- a task sheet or student instructions
- a formative or summative assessment activity
- a SACE assessment draft
- a Year 8 assessment task
- an assessment linked to a rubric, marking guide or achievement standard

## Inputs

- year level or SACE stage
- subject and topic
- assessment purpose and type
- curriculum, SACE or school criteria
- task conditions, timing and format
- evidence students must produce
- available equipment, platforms or resources
- integrity, safety, accessibility or support requirements

## Process

1. Identify the assessment purpose: formative, summative, diagnostic, SACE, reporting or practice.
2. Confirm the framework: Australian Curriculum, SACE, school criteria or supplied rubric.
3. Define the evidence students need to produce.
4. Draft student-facing instructions in clear, staged language.
5. Add conditions such as time, resources, collaboration, AI use, supervision and submission format where relevant.
6. Align criteria to the intended evidence and standards.
7. Add teacher-facing notes for implementation, safety, differentiation, integrity or marking only where useful.
8. Check that the task can be completed and marked realistically.
9. Remove hidden expectations and unnecessary extension content.
10. Flag any required SACE, LAP, moderation or local school checks.

## Output

```markdown
# Assessment Task

## Context

## Task

## What To Submit

## Conditions

## Assessment Criteria

## Teacher Notes

## Alignment Notes
```

Adjust headings to match the user's requested format.

## Quality Criteria

- Task instructions are clear and student-ready.
- Evidence requirements are explicit.
- Criteria match what students are asked to produce.
- Curriculum or standards alignment is accurate.
- Conditions and integrity expectations are visible.
- The task is realistic for the time, year level and classroom context.

## Related Rules

- `rules/Assessment/RULE_ASSESSMENT_STRUCTURE.md`
- `rules/Assessment/RULE_MARKING_EVIDENCE.md`
- `rules/Assessment/RULE_NO_UNFAIR_PENALTY.md`
- `rules/Curriculum/RULE_CURRICULUM_ALIGNMENT.md`
- `rules/Curriculum/RULE_SACE_ALIGNMENT.md`
- `rules/Curriculum/RULE_YEAR_LEVEL_APPROPRIATENESS.md`
- `rules/Quality control/RULE_CLASSROOM_REALISM.md`

## Example User Requests

- `Create a Year 8 Science practical assessment on fair testing.`
- `Draft a SACE Stage 1 Chemistry assessment task.`
- `Turn this topic into a formative assessment.`
- `Write a task sheet and marking criteria for a coding project.`

## Failure Modes

- Designing a task without clear evidence to submit.
- Adding criteria that the task does not assess.
- Overloading the task with too many outcomes.
- Claiming SACE readiness without current SACE or LAP checks.
- Mixing teacher-only notes into student instructions.

## Completion Checklist

- Is the assessment purpose clear?
- Is the task aligned to the correct framework?
- Do students know what to do and submit?
- Are conditions and support boundaries stated?
- Can the task be marked fairly from the evidence?
- Are local checks or assumptions flagged?

## Sources

- Australian Professional Standards for Teachers - Australian Institute for Teaching and School Leadership - https://aitsl.edu.au/docs/default-source/teach-documents/australian-professional-standards-for-teachers - Accessed 2026-05-17
- Performance standards and grades - SACE Board of South Australia - https://www.sace.sa.edu.au/teaching/assessment/performance-standards - Accessed 2026-05-17
- About the curriculum content elements - Australian Curriculum, Assessment and Reporting Authority - https://www.australiancurriculum.edu.au/help/learning-areas/about-the-curriculum-content-elements - Accessed 2026-05-17
