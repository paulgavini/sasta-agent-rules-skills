# Skill: Output Review

## Purpose

This skill allows the agent to review a draft output before final delivery so it is accurate, complete, usable, appropriately sourced and matched to the user's requested audience and format.

## When To Use

Use this skill when the user asks for:

- a final quality check
- review of a lesson, assessment, rubric, message, source list or document
- checking whether an output is ready to use
- finding missing sections or inconsistencies
- verifying sources, claims, calculations or alignment
- polishing a completed draft without changing its intent

## Inputs

- the draft output or files to review
- original user request or stated purpose
- audience and format requirements
- curriculum, SACE, source or platform constraints
- required source register or progress updates
- relevant rules and skills already used
- known uncertainty, assumptions or local checks

## Process

1. Re-read the user's requested deliverable and constraints.
2. Check completeness: all requested parts, sections, examples, sources and tracking updates.
3. Check audience fit: student, teacher, parent/carer, staff, LMS, assessment or GitHub.
4. Check accuracy for claims, calculations, curriculum links, SACE requirements, units, code and terminology.
5. Check source use: no fabricated sources, correct source titles, access dates and register alignment.
6. Check classroom realism: timing, equipment, evidence, marking load, platform limits and teacher preparation.
7. Check privacy, safety, accessibility and assessment integrity where relevant.
8. Remove placeholders, duplicated headings, hidden assumptions and unnecessary process commentary.
9. Preserve meaningful existing content when reviewing file updates.
10. Report unresolved issues and recommended next work only where useful.

## Output

For a quick review:

```markdown
## Ready-To-Use Check

- Complete:
- Accurate:
- Audience fit:
- Sources:
- Risks or gaps:
- Recommended next action:
```

For a code-review-style or document-review request, lead with issues ordered by severity, then include assumptions and a brief summary.

## Quality Criteria

- The review is tied to the original request.
- Issues are specific and actionable.
- High-risk problems are prioritised.
- Source and file claims are verified before reporting.
- The final output is cleaner, not more cluttered.
- Uncertainty is visible when it cannot be resolved.

## Related Rules

- `rules/Quality control/RULE_COMPLETENESS_CHECK.md`
- `rules/Quality control/RULE_ACCURACY_CHECK.md`
- `rules/Quality control/RULE_NO_HALLUCINATED_FILES.md`
- `rules/Quality control/RULE_CLASSROOM_REALISM.md`
- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`
- `rules/Core behaviour/RULE_FINAL_CLEAN_OUTPUT.md`

## Example User Requests

- `Review this assessment before I use it.`
- `Check these skill files for missing sections.`
- `Make sure this lesson is classroom-ready.`
- `Review the source register against the completed files.`

## Failure Modes

- Reviewing generally without checking the user's requested output.
- Reporting a file, source or edit without verifying it.
- Focusing on style while missing accuracy, safety or assessment risks.
- Overwriting meaningful content during clean-up.
- Adding long commentary to an output that should be clean.
- Hiding unresolved gaps.

## Completion Checklist

- Did the output answer the whole request?
- Are all required sections present?
- Are sources and file claims verified?
- Are accuracy, privacy, safety and accessibility checked?
- Are risks and assumptions stated?
- Is the final output concise and usable?

## Sources

- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
- Question your sources - Monash University - https://www.monash.edu/student-academic-success/sharpen-your-thinking/critical-thinking/question-your-sources - Accessed 2026-05-17
- Artificial intelligence (AI) in schools - information for parents and carers - South Australian Department for Education - https://www.education.sa.gov.au/parents-and-families/curriculum-and-learning/ai/artificial-intelligence-ai-in-schools-information-for-parents-and-carers - Accessed 2026-05-17
