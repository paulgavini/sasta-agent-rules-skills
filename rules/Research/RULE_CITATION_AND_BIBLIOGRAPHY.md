# Rule: Citation And Bibliography

## Purpose

Ensure sources are cited clearly, honestly and consistently when the agent uses researched material in rules, skills, teaching resources, assessment materials or advice.

## Applies To

- rule and skill source lists
- research summaries and evidence-informed recommendations
- curriculum, SACE, policy and software guidance
- bibliographies, reference lists and source-register entries
- quoted, paraphrased or summarised source material

## Rule Statement

The agent must cite sources that materially support factual, policy, curriculum, assessment or evidence claims, and must never invent or misrepresent a citation.

## Requirements

- Cite sources when the user asks for citations or sources.
- Cite sources when claims depend on researched curriculum, SACE, policy, safety, software or evidence material.
- Record sources in `SOURCE_REGISTER.md` when they support completed rule or skill files.
- Include enough source detail for the user to identify and revisit the source.
- Use the project's established source-list format inside rule and skill files.
- Use Australian Government Style Manual author-date principles when a formal bibliography is requested.
- Distinguish direct quotations, paraphrases and summaries.
- Keep quotations short and only use them when exact wording matters.
- Do not cite a source that was not opened, supplied or otherwise verified.
- Do not use a citation to imply stronger evidence than the source provides.

## Project Source Format

For rule and skill files:

```markdown
- Source title - Organisation or publisher - URL - Accessed YYYY-MM-DD
```

For `SOURCE_REGISTER.md`, use the existing table columns:

```markdown
| Source title | Organisation or publisher | URL | Date accessed | Used by | Relevance |
```

## Decision Logic

If the source supports a completed project file, add it to both the file's `Sources` section and `SOURCE_REGISTER.md`. If the source was consulted but did not materially inform the file, leave it out. If a claim is based on user-supplied material, identify it as supplied material rather than pretending it is an external source.

## Examples

- Cite SACE performance standards when a rule explains SACE grade evidence.
- Cite official software documentation when a skill gives platform-specific instructions.
- Cite AERO when making an evidence-informed teaching recommendation.
- Add an access date for web sources in rule and skill files.

## Non-Examples

- Listing impressive sources that did not influence the file.
- Inventing a URL or publication date.
- Citing a homepage when a more specific page was used.
- Copying long passages into a rule file.
- Treating a bibliography as a substitute for accurate synthesis.

## Interaction With Skills

- `skills/Core workflow/SKILL_SOURCE_RESEARCH.md`
- `skills/Core workflow/SKILL_SOURCE_EVALUATION.md`
- `skills/Core workflow/SKILL_SYNTHESIS.md`
- `skills/Quality control/SKILL_OUTPUT_REVIEW.md`

## Quality Check

- Are all material researched claims supported?
- Are source details accurate and sufficient?
- Are access dates included for web sources?
- Are sources recorded in the register where required?
- Are quotations short, necessary and clearly attributed?
- Are weak or unused sources omitted?

## Sources

- Author-date - Australian Government Style Manual - https://www.stylemanual.gov.au/referencing-and-attribution/author-date - Accessed 2026-05-17
- Evaluating information - Monash University Library - https://www.monash.edu/library/help/assignments-research/finding-and-evaluating-information/evaluating-information - Accessed 2026-05-17
- Quick guide: plain language - Australian Government Style Manual - https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language - Accessed 2026-05-17
