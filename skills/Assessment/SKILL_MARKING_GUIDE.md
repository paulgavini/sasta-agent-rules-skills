# Skill: Marking Guide

## Purpose

This skill allows the agent to create marking guides that help teachers make fair, consistent and evidence-based judgements.

## When To Use

Use this skill when the user asks for:

- a marking guide
- answer key with marking notes
- grade descriptors
- teacher-facing assessment criteria
- SACE or Australian Curriculum judgement support
- moderation notes or evidence examples

## Inputs

- assessment task and student instructions
- criteria, rubric or standards
- mark allocation or grade scale if supplied
- expected student evidence
- answer key or sample response if available
- year level, subject and assessment type
- integrity, safety or accessibility constraints

## Process

1. Read the task and identify required evidence.
2. Identify the criteria or standards used for judgement.
3. Decide whether the guide needs marks, grades, descriptors or qualitative evidence notes.
4. Draft expected evidence for each criterion or question.
5. Include acceptable alternatives where relevant.
6. Identify common errors or partial evidence if useful.
7. Avoid hidden penalties and double-counting.
8. Add verification or integrity notes where student authorship matters.
9. Include moderation or teacher judgement notes where appropriate.
10. Check that the guide can be used without seeing internal reasoning.

## Output

```markdown
# Marking Guide

## Assessment Evidence

## Criteria And Judgement Notes

| Criterion or question | Expected evidence | Marking notes |
| --- | --- | --- |

## Common Issues

## Integrity Or Verification Notes
```

## Quality Criteria

- Judgements are based on observable evidence.
- Criteria match the task.
- Acceptable alternatives are recognised.
- Marking notes are fair and practical.
- Integrity concerns are handled through verification, not guesswork.
- Teacher judgement remains central.

## Related Rules

- `rules/Assessment/RULE_MARKING_EVIDENCE.md`
- `rules/Assessment/RULE_NO_UNFAIR_PENALTY.md`
- `rules/Assessment/RULE_RUBRIC_A_TO_E.md`
- `rules/Curriculum/RULE_SACE_ALIGNMENT.md`
- `rules/Quality control/RULE_ACCURACY_CHECK.md`

## Example User Requests

- `Write a marking guide for this practical report.`
- `Create an answer key with partial-credit notes.`
- `Make teacher marking notes for this rubric.`
- `Create a SACE-style evidence guide for this task.`

## Failure Modes

- Marking material the task did not ask for.
- Treating one possible answer as the only acceptable answer when alternatives are valid.
- Penalising presentation without criteria.
- Making integrity accusations without verification.
- Creating a guide too vague to support consistent marking.

## Completion Checklist

- Does the guide match the task?
- Is expected evidence clear?
- Are partial and alternative responses handled fairly?
- Are criteria or marks aligned?
- Are integrity notes cautious and appropriate?
- Is the guide practical for teacher use?

## Sources

- Performance standards and grades - SACE Board of South Australia - https://www.sace.sa.edu.au/teaching/assessment/performance-standards - Accessed 2026-05-17
- Verification of student work - SACE Board of South Australia - https://www.sace.sa.edu.au/teaching/assessment/verification - Accessed 2026-05-17
- Australian Professional Standards for Teachers - Australian Institute for Teaching and School Leadership - https://aitsl.edu.au/docs/default-source/teach-documents/australian-professional-standards-for-teachers - Accessed 2026-05-17
