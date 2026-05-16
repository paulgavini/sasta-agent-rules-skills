# Skill: Rubric Design

## Purpose

This skill allows the agent to create task-specific rubrics that describe evidence of learning clearly and fairly.

## When To Use

Use this skill when the user asks for:

- an A-E rubric
- a single-point rubric
- success criteria
- marking criteria
- standards-based descriptors
- a rubric aligned to Australian Curriculum, SACE or school criteria

## Inputs

- task description
- year level or SACE stage
- subject and topic
- curriculum, achievement standards, performance standards or school criteria
- assessment evidence students will produce
- preferred rubric type
- grading or feedback purpose
- audience: teacher, student or both

## Process

1. Identify the rubric purpose: grading, feedback, self-assessment, peer review or moderation.
2. Select the rubric type:
   - A-E rubric for graded standards-based judgement
   - single-point rubric for formative feedback and next steps
   - checklist only for simple completion or process checks
3. Define a small number of criteria tied to task evidence.
4. Align criteria to the relevant standard or supplied criteria.
5. Write descriptors in observable, evidence-based language.
6. Avoid vague progression words unless they are supported by concrete evidence.
7. Check that descriptors do not double-count the same weakness.
8. Keep student-facing wording clear and age-appropriate.
9. Avoid inventing grade boundaries or SACE requirements.
10. Add a note about provisional alignment if the standards source was not supplied or verified.

## Output

For an A-E rubric:

```markdown
| Criterion | A | B | C | D | E |
| --- | --- | --- | --- | --- | --- |
```

For a single-point rubric:

```markdown
| Strengths shown | Expected evidence | Next step |
| --- | --- | --- |
```

## Quality Criteria

- Criteria match the task evidence.
- Descriptors show meaningful differences in quality.
- Language is evidence-based and respectful.
- The rubric can be used consistently by a teacher.
- The rubric is not overloaded.
- Grade boundaries or SACE claims are not invented.

## Related Rules

- `rules/Assessment/RULE_RUBRIC_A_TO_E.md`
- `rules/Assessment/RULE_SINGLE_POINT_RUBRIC.md`
- `rules/Assessment/RULE_MARKING_EVIDENCE.md`
- `rules/Assessment/RULE_NO_UNFAIR_PENALTY.md`
- `rules/Curriculum/RULE_CURRICULUM_ALIGNMENT.md`
- `rules/Curriculum/RULE_SACE_ALIGNMENT.md`

## Example User Requests

- `Make an A-E rubric for this Year 8 Science assessment.`
- `Create a single-point rubric for draft feedback.`
- `Turn these SACE performance standards into task-specific criteria.`
- `Make a student-friendly rubric for a Python project.`

## Failure Modes

- Using generic descriptors that could fit any task.
- Assessing effort or neatness without criteria.
- Inventing percentage cut-offs.
- Creating too many criteria for a short task.
- Copying standards language without connecting it to task evidence.

## Completion Checklist

- Is the rubric type appropriate?
- Are criteria aligned and assessable?
- Are descriptors specific and evidence-based?
- Is the rubric fair and practical?
- Are student-facing terms clear?
- Are uncertainties about standards flagged?

## Sources

- Performance standards and grades - SACE Board of South Australia - https://www.sace.sa.edu.au/teaching/assessment/performance-standards - Accessed 2026-05-17
- Standards elaborations - Queensland Curriculum and Assessment Authority - https://www.qcaa.qld.edu.au/p-10/aciq/version-8/frequently-used-resources/standards-elaborations - Accessed 2026-05-17
- About the curriculum content elements - Australian Curriculum, Assessment and Reporting Authority - https://www.australiancurriculum.edu.au/help/learning-areas/about-the-curriculum-content-elements - Accessed 2026-05-17
