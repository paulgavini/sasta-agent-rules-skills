# Skill: Classroom Implementation Check

## Purpose

This skill allows the agent to check whether a lesson, activity, assessment or resource can realistically be used in a classroom with the stated time, students, equipment, platform and teacher workload.

## When To Use

Use this skill when the user asks for:

- a classroom realism check
- implementation notes
- a practical review of a lesson or sequence
- checking timing, equipment, grouping or setup
- adapting a resource for a real class
- reviewing whether an assessment, practical or tutorial is usable
- identifying likely classroom friction before use

## Inputs

- draft lesson, task, sequence or resource
- year level and subject
- lesson length and number of lessons
- class size, prior learning or class profile if supplied
- equipment, room, software and internet access
- grouping, supervision and safety constraints
- assessment evidence or submission requirements
- teacher preparation and marking expectations

## Process

1. Identify the intended classroom context and any missing assumptions.
2. Check timing against the number and complexity of activities.
3. Check materials, equipment, software, logins, links and room requirements.
4. Check whether student instructions are clear enough for the intended level of independence.
5. Check teacher workload: preparation, explanation, monitoring, collection, marking and follow-up.
6. Check evidence of learning: what students produce and how the teacher can see it.
7. Check support and extension for mixed readiness without fragmenting the lesson.
8. Check likely friction: absences, device issues, transitions, group work, clean-up, printing or file submission.
9. Recommend practical adjustments that preserve the learning goal.
10. Flag local checks needed for safety, platforms, assessment conditions or school procedures.

## Output

```markdown
# Classroom Implementation Check

## Overall Readiness

## Timing

## Materials And Setup

## Student Instructions

## Evidence Of Learning

## Support And Extension

## Likely Friction Points

## Recommended Adjustments

## Local Checks
```

Use a shorter checklist if the user asks for a quick review.

## Quality Criteria

- The check is grounded in the supplied classroom context.
- Recommendations are practical and specific.
- The learning goal is preserved.
- Timing and workload are realistic.
- Evidence of learning is visible.
- Local checks are flagged instead of guessed.

## Related Rules

- `rules/Quality control/RULE_CLASSROOM_REALISM.md`
- `rules/Quality control/RULE_COMPLETENESS_CHECK.md`
- `rules/Lesson design/RULE_TEACHER_FACING_TONE.md`
- `rules/Lesson design/RULE_SCAFFOLDED_INSTRUCTION.md`
- `rules/Lesson design/RULE_DIFFERENTIATION.md`
- `rules/Assessment/RULE_ASSESSMENT_STRUCTURE.md`

## Example User Requests

- `Check if this lesson will work in 50 minutes.`
- `Review this practical for classroom realism.`
- `Make this relief lesson easier to run.`
- `Check whether this assessment task is collectable and markable.`

## Failure Modes

- Treating a plan as realistic because it is educationally sound.
- Ignoring equipment, logins or supervision.
- Overloading the lesson with too many activities.
- Suggesting changes that require more preparation than the original.
- Omitting what students will submit or show.
- Guessing local procedures instead of flagging them.

## Completion Checklist

- Is the lesson doable in the available time?
- Are materials and setup clear?
- Can students follow the instructions?
- Can the teacher monitor and collect evidence?
- Are support, extension and friction points addressed?
- Are local checks stated?

## Sources

- How students learn best: An overview of the evidence - Australian Education Research Organisation - https://www.edresearch.edu.au/research/research-reports/how-students-learn-best-overview-evidence - Accessed 2026-05-17
- Teach explicitly - Australian Education Research Organisation - https://www.edresearch.edu.au/guides-resources/practice-guides/teach-explicitly - Accessed 2026-05-17
- Australian Professional Standards for Teachers - Australian Institute for Teaching and School Leadership - https://aitsl.edu.au/docs/default-source/teach-documents/australian-professional-standards-for-teachers - Accessed 2026-05-17
