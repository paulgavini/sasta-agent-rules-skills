# Skill: Feedback Comments

## Purpose

This skill allows the agent to write concise, evidence-based feedback comments that help students understand what they have shown and what to do next.

## When To Use

Use this skill when the user asks for:

- student feedback
- rubric comments
- formative feedback
- next steps
- strengths and improvements
- feedback rewritten for tone, length or year level

## Inputs

- student work or teacher notes
- task, criteria or learning intention
- year level and subject
- desired tone and length
- whether feedback is formative, summative, parent-facing or report-style
- privacy or de-identification requirements

## Process

1. Identify the learning evidence to comment on.
2. Select the most important strength or achievement.
3. Select the highest-value next step.
4. Link both to criteria, task evidence or learning intention.
5. Use language suitable for the student's year level.
6. Keep the comment concise and respectful.
7. Avoid unsupported personal judgements.
8. Avoid overloading the student with too many corrections.
9. For parent-facing feedback, use plain language and avoid marking jargon.
10. Check Australian spelling and school-appropriate tone.

## Output

For short student comments:

```markdown
You have shown [specific evidence]. Your next step is to [specific action].
```

For structured feedback:

```markdown
Strength:
Evidence:
Next step:
```

## Quality Criteria

- Feedback is based on evidence.
- The next step is specific and manageable.
- Tone is respectful and professional.
- The comment matches the audience.
- The comment does not reveal unnecessary personal information.
- The feedback is concise enough for the context.

## Related Rules

- `rules/Assessment/RULE_FEEDBACK_FORMAT.md`
- `rules/Assessment/RULE_MARKING_EVIDENCE.md`
- `rules/Assessment/RULE_NO_UNFAIR_PENALTY.md`
- `rules/Communication/RULE_STUDENT_COMMENT_LENGTH.md`
- `rules/Core behaviour/RULE_AUSTRALIAN_LANGUAGE.md`

## Example User Requests

- `Write feedback for this Year 8 practical report.`
- `Turn these notes into a student-friendly comment.`
- `Make this feedback shorter and more constructive.`
- `Write strengths and next steps for each criterion.`

## Failure Modes

- Giving vague praise without evidence.
- Listing too many next steps.
- Commenting on personality instead of work.
- Using teacher jargon in student-facing feedback.
- Making a grade judgement when only feedback was requested.

## Completion Checklist

- Is the feedback evidence-based?
- Is the next step clear?
- Is the tone respectful?
- Is the length suitable?
- Is the audience clear?
- Is privacy protected?

## Sources

- Australian Professional Standards for Teachers - Australian Institute for Teaching and School Leadership - https://aitsl.edu.au/docs/default-source/teach-documents/australian-professional-standards-for-teachers - Accessed 2026-05-17
- Quick guide: plain language - Australian Government Style Manual - https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language - Accessed 2026-05-17
- Performance standards and grades - SACE Board of South Australia - https://www.sace.sa.edu.au/teaching/assessment/performance-standards - Accessed 2026-05-17
