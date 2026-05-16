# Skill: Curriculum Alignment

## Purpose

This skill allows the agent to align teaching resources, assessment tasks, rubrics and feedback to the Australian Curriculum, SACE subject requirements, achievement standards, performance standards and relevant capabilities.

## When To Use

Use this skill when the user asks for:

- Australian Curriculum alignment
- SACE Stage 1 or Stage 2 alignment
- achievement standards, content descriptions or general capabilities
- assessment design linked to standards
- rubrics, success criteria or marking guides
- lesson sequences that need curriculum justification
- checking whether a task is year-level appropriate

## Inputs

- year level or SACE stage
- subject or learning area
- topic, concept or skill focus
- supplied curriculum codes, achievement standard excerpts or performance standards
- task type, assessment type or learning activity
- intended evidence of learning
- school or SACE constraints
- whether alignment should be visible in the final output

## Process

1. Identify whether the task uses Australian Curriculum F-10, SACE, school criteria or another framework.
2. If curriculum text is supplied, use it as the primary source.
3. If curriculum text is not supplied and accuracy matters, research the official curriculum or SACE source before drafting.
4. For Australian Curriculum tasks, distinguish:
   - year or band level descriptions
   - achievement standards
   - content descriptions
   - content elaborations
   - general capabilities
   - cross-curriculum priorities
5. Treat content descriptions as what students are expected to learn and achievement standards as the quality of learning students typically demonstrate.
6. Treat content elaborations as optional examples, not mandatory curriculum points.
7. For SACE tasks, align to the relevant subject outline, learning and assessment plan, assessment design criteria and performance standards where available.
8. Translate curriculum language into practical learning intentions, success criteria, task evidence or rubric criteria.
9. Avoid overloading the output with curriculum codes unless the user requests visible mapping.
10. Flag uncertainty when the exact curriculum version, SACE subject outline or school assessment plan has not been supplied or verified.

## Output

Use one of these formats depending on the task.

For brief alignment:

```markdown
## Curriculum Alignment
- Framework:
- Relevant content:
- Evidence students will produce:
- Alignment note:
```

For assessment or rubric design:

```markdown
## Alignment Map
| Curriculum or standard element | Where it appears in the task | Evidence of learning |
| --- | --- | --- |
```

For student-facing resources, keep the alignment teacher-facing unless the user asks students to see it.

## Quality Criteria

- Alignment is based on official curriculum, SACE or supplied school criteria.
- Content descriptions, achievement standards and elaborations are not confused.
- SACE tasks refer to performance standards or assessment design criteria where relevant.
- The resource remains practical and age-appropriate after alignment.
- Claims about curriculum alignment are not made without evidence.
- Visible curriculum mapping is concise and useful.

## Related Rules

- `rules/Core behaviour/RULE_FOLLOW_USER_CONTEXT.md`
- `rules/Core behaviour/RULE_CLARIFICATION.md`
- `rules/Curriculum/RULE_CURRICULUM_ALIGNMENT.md`
- `rules/Curriculum/RULE_SACE_ALIGNMENT.md`
- `rules/Curriculum/RULE_YEAR_LEVEL_APPROPRIATENESS.md`
- `rules/Curriculum/RULE_NO_OVERTEACHING.md`
- `rules/Assessment/RULE_ASSESSMENT_STRUCTURE.md`

## Example User Requests

- `Align this Year 8 Digital Technologies task to the Australian Curriculum.`
- `Create a SACE Stage 1 Physics practical assessment with performance standard links.`
- `Turn these content descriptions into learning intentions and success criteria.`
- `Check whether this Year 9 Chemistry task is pitched at the right level.`

## Failure Modes

- Treating content elaborations as mandatory requirements.
- Claiming SACE alignment without checking the subject outline or supplied performance standards.
- Including curriculum codes that do not match the task.
- Making the student-facing resource cluttered with teacher-facing alignment notes.
- Aligning only to topic words rather than evidence of learning.

## Completion Checklist

- Has the correct curriculum or SACE framework been identified?
- Has official or supplied source material been used?
- Are achievement standards and content descriptions used correctly?
- Is the alignment visible only where useful?
- Does the task create evidence that matches the standard or criterion?
- Have uncertainties been flagged?

## Sources

- About the curriculum content elements — Australian Curriculum, Assessment and Reporting Authority — https://www.australiancurriculum.edu.au/help/learning-areas/about-the-curriculum-content-elements — Accessed 2026-05-16
- General capabilities — Australian Curriculum, Assessment and Reporting Authority — https://www.australiancurriculum.edu.au/help/general-capabilities — Accessed 2026-05-16
- Learning and assessment plans — SACE Board of South Australia — https://www.sace.sa.edu.au/teaching/assessment/laps — Accessed 2026-05-16
- Performance standards and grades — SACE Board of South Australia — https://www.sace.sa.edu.au/teaching/assessment/performance-standards — Accessed 2026-05-16
