# Rule: Research Screen Output

## Purpose

Keep research notes, source summaries and cited outputs concise, readable and useful for the teacher, rather than exposing excessive search process or raw source fragments.

## Applies To

- research summaries shown to the user
- source notes in final answers
- source lists in rule and skill files
- bibliography or reference-list outputs
- limitations, assumptions and unresolved questions after research

## Rule Statement

The agent must present research findings in a clean, task-focused format that separates final guidance from source notes and does not overwhelm the requested deliverable.

## Requirements

- Put the requested deliverable before research notes unless the user asks to see the research first.
- Summarise only the findings that affect the output.
- Keep source lists concise and relevant.
- Do not include raw search logs, irrelevant snippets or long quotations.
- Separate facts, interpretation, recommendations and uncertainty.
- Use tables only when they improve comparison or traceability.
- Include access dates and source titles when citing web sources.
- State unresolved limits clearly without making the output feel unfinished.
- Preserve clean formatting for copying into Word, LMS or project Markdown files.

## Decision Logic

If the user asks for sources, include a compact source section. If the user asks for a researched deliverable, include only the source details needed for credibility and future checking. If research reveals uncertainty that affects use, include a short `Limitations` or `Needs checking` note. If research notes are internal only, do not include them in final student-facing material.

## Examples

- A rule file should include a short `Sources` section, not the full search process.
- A researched lesson plan may include teacher-facing source notes after the lesson content.
- A comparison task may use a short table with source, key finding and implication.
- A final answer can list completed files and sources used without re-explaining every search step.

## Non-Examples

- Pasting raw web snippets into a rule file.
- Listing sources that were opened but not used.
- Putting a long literature review before a simple teaching resource.
- Mixing internal uncertainty notes into student instructions.
- Hiding an important limitation because the output looks cleaner without it.

## Interaction With Skills

- `skills/Core workflow/SKILL_SOURCE_RESEARCH.md`
- `skills/Core workflow/SKILL_SOURCE_EVALUATION.md`
- `skills/Core workflow/SKILL_SYNTHESIS.md`
- `rules/Core behaviour/RULE_FINAL_CLEAN_OUTPUT.md`
- `rules/Research/RULE_CITATION_AND_BIBLIOGRAPHY.md`

## Quality Check

- Is the research output concise and useful?
- Are only relevant sources listed?
- Are findings separated from recommendations and uncertainty?
- Is the requested deliverable still easy to use?
- Are source details sufficient for checking?
- Has raw process noise been removed?

## Sources

- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
- Quick guide: plain language - Australian Government Style Manual - https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language - Accessed 2026-05-17
- Author-date - Australian Government Style Manual - https://www.stylemanual.gov.au/referencing-and-attribution/author-date - Accessed 2026-05-17
