# Skill: Lesson Sequence Planning

## Purpose

This skill allows the agent to design coherent lesson sequences that build learning over time, align with curriculum or assessment goals, and remain realistic for classroom implementation.

## When To Use

Use this skill when the user asks for:

- a sequence of lessons
- a unit outline or mini-unit
- a progression from introduction to practice to assessment
- a set of lessons for a topic, inquiry, practical skill or digital technology project
- a week-by-week or lesson-by-lesson plan
- lesson planning that needs learning intentions, success criteria, scaffolding or differentiation

## Inputs

- year level or SACE stage
- subject, topic and intended learning
- number and length of lessons
- curriculum, SACE, school or assessment requirements
- prior learning and assumed knowledge
- available equipment, software, rooms or platforms
- class profile, support needs or extension needs
- assessment or evidence students must produce
- preferred lesson structure or school template

## Process

1. Identify the end goal: understanding, skill, product, assessment evidence or practical competence.
2. Check the relevant curriculum, SACE, supplied task or school requirement before inventing outcomes.
3. Map the learning progression from prior knowledge to new learning, guided practice, independent practice and evidence.
4. Break the sequence into lessons with a clear purpose for each lesson.
5. Add learning intentions and success criteria only where they help students or teachers use the plan.
6. Include explicit modelling, worked examples, checks for understanding and practice opportunities where relevant.
7. Build in consolidation, retrieval, review or catch-up time if the sequence is more than one lesson.
8. Add differentiation, extension and accessibility options that preserve the core learning goal.
9. Check classroom realism: timing, equipment, movement, marking load, safety, platform access and teacher preparation.
10. Flag assumptions, local checks and any curriculum, SACE, safety or assessment-integrity limits.

## Output

```markdown
# Lesson Sequence

## Context

## Sequence Overview

| Lesson | Focus | Learning Intention | Main Activities | Evidence Of Learning | Notes |
| --- | --- | --- | --- | --- | --- |

## Lesson Details

## Differentiation And Extension

## Assessment Or Evidence

## Teacher Preparation

## Assumptions And Local Checks
```

Adjust headings to match the user's requested format.

## Quality Criteria

- The sequence has a clear learning progression.
- Each lesson has a distinct purpose.
- Activities align with the stated evidence of learning.
- Scaffolding is strongest where learning is newest or most complex.
- Timing and resources are realistic.
- Support and extension are practical, not decorative.
- Curriculum or assessment claims are source-based.

## Related Rules

- `rules/Lesson design/RULE_LEARNING_INTENTIONS_SUCCESS_CRITERIA.md`
- `rules/Lesson design/RULE_SCAFFOLDED_INSTRUCTION.md`
- `rules/Lesson design/RULE_DIFFERENTIATION.md`
- `rules/Lesson design/RULE_TEACHER_FACING_TONE.md`
- `rules/Curriculum/RULE_CURRICULUM_ALIGNMENT.md`
- `rules/Quality control/RULE_CLASSROOM_REALISM.md`

## Example User Requests

- `Plan a 4-lesson Year 8 Science sequence on fair testing.`
- `Create a two-week beginner Python sequence.`
- `Turn this assessment into a preparation lesson sequence.`
- `Plan lessons leading into a SACE practical investigation.`

## Failure Modes

- Listing activities without a learning progression.
- Overloading each lesson with too many outcomes.
- Treating curriculum links as decoration rather than design constraints.
- Omitting time, resources, safety or platform assumptions.
- Adding extension that is just extra work.
- Creating a sequence that cannot produce the required assessment evidence.

## Completion Checklist

- Is the end goal clear?
- Does the sequence build logically from prior knowledge?
- Are activities matched to evidence of learning?
- Are support and extension included where useful?
- Is the plan realistic for the stated time and resources?
- Are assumptions and local checks visible?

## Sources

- Teach explicitly - Australian Education Research Organisation - https://www.edresearch.edu.au/guides-resources/practice-guides/teach-explicitly - Accessed 2026-05-17
- How students learn best: An overview of the evidence - Australian Education Research Organisation - https://www.edresearch.edu.au/research/research-reports/how-students-learn-best-overview-evidence - Accessed 2026-05-17
- About the curriculum content elements - Australian Curriculum, Assessment and Reporting Authority - https://www.australiancurriculum.edu.au/help/learning-areas/about-the-curriculum-content-elements - Accessed 2026-05-17
