# Skill: Report Writing

## Purpose

This skill allows the agent to draft school report comments that are accurate, concise, respectful and based on evidence of student learning.

## When To Use

Use this skill when the user asks for:

- report comments
- achievement summaries
- effort or learning behaviour comments where supplied
- parent-facing progress comments
- rewriting report comments for tone, clarity or length
- batch comments from teacher notes

## Inputs

- student achievement evidence or teacher notes
- subject and year level
- grade, level or criteria if supplied
- strengths and next steps
- school tone, length or reporting format
- whether names, pronouns or anonymised placeholders should be used
- any required comment bank constraints

## Process

1. Identify the audience as parent/carer-facing unless told otherwise.
2. Use only supplied evidence, grades or teacher notes.
3. Start with achievement or demonstrated learning.
4. Add one specific strength.
5. Add one constructive next step.
6. Use plain, professional and respectful language.
7. Avoid unsupported claims about personality, home life, motivation or behaviour.
8. Avoid revealing sensitive information unnecessarily.
9. Match the requested length and school style.
10. Check Australian spelling and grammar before finalising.

## Output

For a single comment:

```markdown
[Student] has demonstrated [achievement/evidence]. [He/She/They] [specific strength]. To continue improving, [student] should [specific next step].
```

For batch comments:

```markdown
| Student | Comment |
| --- | --- |
```

Use placeholders such as `Student A` when privacy matters.

## Quality Criteria

- Comment is evidence-based.
- Tone is professional and parent-friendly.
- Strength and next step are specific.
- The comment avoids unsupported personal judgement.
- Length matches the requested format.
- Privacy and sensitivity are respected.

## Related Rules

- `rules/Assessment/RULE_FEEDBACK_FORMAT.md`
- `rules/Assessment/RULE_MARKING_EVIDENCE.md`
- `rules/Communication/RULE_PARENT_FACING_LANGUAGE.md`
- `rules/Core behaviour/RULE_AUSTRALIAN_LANGUAGE.md`
- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`

## Example User Requests

- `Write a 600-character report comment from these notes.`
- `Make these comments more parent-friendly.`
- `Write Year 8 Digital Technologies report comments.`
- `Turn these grades and strengths into concise comments.`

## Failure Modes

- Inventing achievement evidence.
- Making sensitive or personal claims not supplied by the teacher.
- Using vague statements such as "needs to try harder".
- Writing comments too long for the reporting system.
- Mixing private teacher notes into a parent-facing comment.

## Completion Checklist

- Is the comment based only on supplied evidence?
- Is the tone parent-facing and professional?
- Is there a clear strength and next step?
- Is the length suitable?
- Are privacy and sensitivity protected?
- Is Australian spelling used?

## Sources

- Australian Professional Standards for Teachers - Australian Institute for Teaching and School Leadership - https://aitsl.edu.au/docs/default-source/teach-documents/australian-professional-standards-for-teachers - Accessed 2026-05-17
- Quick guide: plain language - Australian Government Style Manual - https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language - Accessed 2026-05-17
- Inclusive language - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/inclusive-language - Accessed 2026-05-17
