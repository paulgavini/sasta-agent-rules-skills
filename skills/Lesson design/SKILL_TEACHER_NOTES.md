# Skill: Teacher Notes

## Purpose

This skill allows the agent to create practical teacher-facing notes that support preparation, delivery, differentiation, safety, assessment evidence and classroom decision-making.

## When To Use

Use this skill when the user asks for:

- teacher notes for a lesson or resource
- implementation guidance
- preparation notes
- classroom management or grouping notes
- checks for understanding
- differentiation or extension notes for teachers
- safety, equipment or platform notes
- assessment or evidence collection notes

## Inputs

- year level, subject and topic
- lesson, task or resource the notes support
- class context and prior learning if known
- timing, room, equipment, software or materials
- safety, privacy or platform constraints
- assessment or evidence requirements
- support, extension or accessibility needs
- local school process or template requirements

## Process

1. Identify what the teacher needs to know before, during and after the lesson.
2. Separate teacher-facing guidance from student-facing text.
3. Add preparation requirements such as printing, equipment, links, logins, risk checks or room setup.
4. Include a concise lesson flow or implementation notes if the user has not already supplied them.
5. Add checks for understanding tied to the learning intention or evidence of learning.
6. Add practical differentiation and extension options.
7. Include safety, privacy, assessment-integrity or local-approval notes where relevant.
8. State assumptions rather than hiding them.
9. Keep the tone professional and action-focused.
10. Remove generic theory that does not help the teacher run the lesson.

## Output

```markdown
# Teacher Notes

## Preparation

## Lesson Flow

## Checks For Understanding

## Differentiation And Extension

## Evidence To Collect

## Safety Or Platform Notes

## Assumptions And Local Checks
```

Adjust headings to match the user's requested format.

## Quality Criteria

- Notes help the teacher run the lesson, not just understand the topic.
- Preparation and equipment needs are clear.
- Checks for understanding are practical and linked to learning.
- Differentiation and extension are usable in a real class.
- Risks, assumptions and local checks are visible.
- Teacher notes do not leak into student-facing material.

## Related Rules

- `rules/Lesson design/RULE_TEACHER_FACING_TONE.md`
- `rules/Lesson design/RULE_SCAFFOLDED_INSTRUCTION.md`
- `rules/Lesson design/RULE_DIFFERENTIATION.md`
- `rules/Quality control/RULE_CLASSROOM_REALISM.md`
- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`
- `rules/Science/RULE_PRACTICAL_SAFETY.md`

## Example User Requests

- `Add teacher notes to this Year 8 practical.`
- `Write implementation notes for this Python tutorial.`
- `Create a teacher-facing version of this worksheet.`
- `Add checks for understanding and extension options.`

## Failure Modes

- Writing generic pedagogy instead of actionable notes.
- Omitting equipment, timing or safety assumptions.
- Mixing student instructions and teacher-only advice.
- Saying `differentiate as needed` without usable options.
- Adding privacy, safety or assessment advice only after the task is final.

## Completion Checklist

- Can the teacher prepare from these notes?
- Are lesson actions and checks clear?
- Are support and extension practical?
- Are risks and assumptions stated?
- Is student-facing text kept separate?
- Is the tone concise and professional?

## Sources

- Australian Professional Standards for Teachers - Australian Institute for Teaching and School Leadership - https://aitsl.edu.au/docs/default-source/teach-documents/australian-professional-standards-for-teachers - Accessed 2026-05-17
- Teach explicitly - Australian Education Research Organisation - https://www.edresearch.edu.au/guides-resources/practice-guides/teach-explicitly - Accessed 2026-05-17
- How students learn best: An overview of the evidence - Australian Education Research Organisation - https://www.edresearch.edu.au/research/research-reports/how-students-learn-best-overview-evidence - Accessed 2026-05-17
