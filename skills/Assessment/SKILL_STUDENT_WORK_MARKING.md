# Skill: Student Work Marking

## Purpose

This skill allows the agent to support marking of student work using supplied criteria, evidence and teacher judgement while protecting privacy and assessment integrity.

## When To Use

Use this skill when the user asks for:

- marking a student response
- assigning a provisional grade or level
- comparing work to a rubric
- identifying evidence for criteria
- giving feedback based on submitted work
- checking whether work meets a standard

## Inputs

- student work, preferably de-identified
- assessment task or prompt
- rubric, criteria, achievement standard or performance standard
- year level or SACE stage
- subject and topic
- whether the judgement is formative, summative or provisional
- any teacher notes about conditions or accommodations

## Process

1. Check whether the student work is de-identified enough for the task.
2. Identify the criteria or standards to apply.
3. Read the work for evidence, not intention.
4. Map evidence to each criterion.
5. Identify missing, ambiguous or insufficient evidence.
6. Make a provisional judgement only where enough evidence exists.
7. Avoid hidden penalties and personal comments.
8. Provide concise evidence-based feedback and next steps.
9. Flag integrity, authenticity or context concerns for teacher review.
10. State limits when the task, rubric or full student work is missing.

## Output

```markdown
## Provisional Judgement

## Evidence Against Criteria
| Criterion | Evidence found | Judgement note |
| --- | --- | --- |

## Feedback
- Strength:
- Next step:

## Limits Or Teacher Checks
```

## Quality Criteria

- Judgement is tied to supplied criteria.
- Evidence from the work is quoted or paraphrased briefly.
- Missing evidence is treated fairly.
- Feedback is respectful and actionable.
- Privacy is protected.
- Final teacher judgement is not displaced.

## Related Rules

- `rules/Assessment/RULE_MARKING_EVIDENCE.md`
- `rules/Assessment/RULE_NO_UNFAIR_PENALTY.md`
- `rules/Assessment/RULE_FEEDBACK_FORMAT.md`
- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`
- `rules/Curriculum/RULE_SACE_ALIGNMENT.md`

## Example User Requests

- `Mark this Year 8 response against the rubric.`
- `Give feedback on this practical report.`
- `Is this Stage 1 response closer to a B or C?`
- `Identify evidence for each criterion in this student work.`

## Failure Modes

- Marking without the task or criteria when they are needed.
- Inferring understanding that is not shown.
- Penalising unsupported factors.
- Making definitive integrity claims from style alone.
- Including identifiable student details unnecessarily.

## Completion Checklist

- Is the student work de-identified where possible?
- Are criteria or limits clear?
- Is evidence mapped to criteria?
- Is the judgement provisional where appropriate?
- Are feedback and next steps useful?
- Are teacher checks stated?

## Sources

- Performance standards and grades - SACE Board of South Australia - https://www.sace.sa.edu.au/teaching/assessment/performance-standards - Accessed 2026-05-17
- Verification of student work - SACE Board of South Australia - https://www.sace.sa.edu.au/teaching/assessment/verification - Accessed 2026-05-17
- Guidance on privacy and the use of commercially available AI products - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/guidance-on-privacy-and-the-use-of-commercially-available-ai-products - Accessed 2026-05-17
