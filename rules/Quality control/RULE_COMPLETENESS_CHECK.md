# Rule: Completeness Check

## Purpose

Ensure the final output includes all parts needed for the user to use, teach, mark, export or continue the work without avoidable gaps.

## Applies To

- final answers after file edits or drafting
- rule and skill files
- worksheets, lesson plans, assessment tasks and rubrics
- answer keys, marking guides and feedback
- source registers, progress logs and recommended next actions

## Rule Statement

The agent must check that the requested deliverable is complete, internally consistent and ready for its intended next use before finalising.

## Requirements

- Confirm the output answers every explicit part of the user's request.
- Include required sections, headings, examples, sources or checklists for the file type.
- Check that instructions, criteria, evidence, answer keys and sources align with each other.
- Remove placeholders unless they are intentional and labelled.
- Preserve meaningful existing content when updating files.
- Update tracking files when the task requires it.
- State unresolved issues, assumptions or verification gaps where they matter.
- Keep the final summary concise but include completed files, sources and recommended next work when requested.

## Decision Logic

If the output is a file, read enough of the completed file to check structure and obvious omissions. If the task spans multiple files, check that register updates match the files completed. If a required piece cannot be completed, state the reason and next action.

## Examples

- A skill file includes purpose, use cases, process, output format, quality criteria, related rules, failure modes and sources.
- A progress update records file status, sources used and recommended next action.
- An assessment task includes student instructions, evidence to submit and marking basis.
- A final answer reports what was completed and what should come next.

## Non-Examples

- Delivering a rubric without criteria descriptors.
- Updating a rule file but not the progress log when the user required it.
- Leaving `TODO` markers in a completed file.
- Providing a source list that does not match the source register.
- Forgetting one of the user's explicit requested outputs.

## Interaction With Skills

- `skills/Core workflow/SKILL_TASK_PLANNING.md`
- `skills/Core workflow/SKILL_SYNTHESIS.md`
- `skills/Quality control/SKILL_OUTPUT_REVIEW.md`
- `rules/Core behaviour/RULE_FINAL_CLEAN_OUTPUT.md`
- `rules/Research/RULE_RESEARCH_SCREEN_OUTPUT.md`

## Quality Check

- Does the output answer the whole request?
- Are all required sections present?
- Are internal references and source lists consistent?
- Are placeholders removed or labelled?
- Are tracking files updated where required?
- Are remaining issues clearly stated?

## Sources

- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
- Quick guide: plain language - Australian Government Style Manual - https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language - Accessed 2026-05-17
- Author-date - Australian Government Style Manual - https://www.stylemanual.gov.au/referencing-and-attribution/author-date - Accessed 2026-05-17
