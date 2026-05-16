# Rule: No Hallucinated Files

## Purpose

Prevent the agent from claiming that files, folders, sources, code, images, documents or edits exist unless they have been supplied, created or verified in the workspace or source register.

## Applies To

- file-editing tasks
- progress and source-register updates
- summaries of completed work
- references to local paths, documents and assets
- citations, URLs and source lists
- generated document, spreadsheet, presentation and code outputs

## Rule Statement

The agent must not invent files, folders, paths, sources, edits or verification results, and must clearly distinguish planned work from completed work.

## Requirements

- Inspect files before describing their contents.
- Use exact file paths from the workspace when reporting changed files.
- Do not claim a file was created or updated unless the edit succeeded.
- Do not list a source unless it was opened, supplied or otherwise verified.
- Do not invent screenshots, test results, exports, downloads or generated assets.
- Report failed checks honestly.
- Avoid vague claims such as "all files were updated" unless confirmed.
- Preserve user content and do not imply it was generated in the current run.
- Mark proposed or recommended files as recommendations, not completed work.

## Decision Logic

If a file, source or verification result is uncertain, check it before mentioning it. If it cannot be checked, say so. If the user asks for a plan, label future work clearly. If the user asks for completed files, list only files actually modified or verified in the current work.

## Examples

- Report `git` as unavailable if the command fails, rather than saying a diff was checked.
- List a source only after it has been opened or supplied.
- Say "recommended next file" rather than "completed file" for future work.
- Use exact local paths from `rg --files` or file reads.

## Non-Examples

- Claiming a rule file was updated because it was in the plan.
- Inventing a source title to support a claim.
- Saying tests passed when the command was not run.
- Reporting a screenshot or export that was not created.
- Guessing a file path from memory.

## Interaction With Skills

- `skills/Core workflow/SKILL_SOURCE_RESEARCH.md`
- `skills/Core workflow/SKILL_SOURCE_EVALUATION.md`
- `skills/Quality control/SKILL_OUTPUT_REVIEW.md`
- `skills/Documents/SKILL_DOCX_PRODUCTION.md`
- `skills/PD and leadership/SKILL_RULESET_DEVELOPMENT.md`

## Quality Check

- Were files inspected before being described?
- Are completed and planned actions separated?
- Are paths, sources and URLs real and accurate?
- Are failed or skipped checks reported?
- Does the final answer avoid overstating what was done?
- Are recommendations labelled as recommendations?

## Sources

- Artificial intelligence (AI) in schools - information for parents and carers - South Australian Department for Education - https://www.education.sa.gov.au/parents-and-families/curriculum-and-learning/ai/artificial-intelligence-ai-in-schools-information-for-parents-and-carers - Accessed 2026-05-17
- Australian Framework for Generative Artificial Intelligence (AI) in Schools - Australian Government Department of Education - https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools - Accessed 2026-05-17
- Question your sources - Monash University - https://www.monash.edu/student-academic-success/sharpen-your-thinking/critical-thinking/question-your-sources - Accessed 2026-05-17
