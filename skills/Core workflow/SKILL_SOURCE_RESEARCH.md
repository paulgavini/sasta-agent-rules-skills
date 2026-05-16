# Skill: Source Research

## Purpose

This skill allows the agent to find, select and record credible sources for curriculum, science, technology, assessment, software, safety and school workflow tasks.

## When To Use

Use this skill when a request involves:

- current curriculum, SACE, policy, safety or software information
- factual claims that could change over time
- assessment standards, performance standards or official guidance
- technical instructions for tools such as Excel Online, Power BI, Scratch, micro:bit, GameMaker or Python
- cybersecurity, privacy, AI or online safety advice
- research-informed teaching practice
- sources requested by the user

## Inputs

- research question or information need
- subject, year level and task type
- preferred jurisdiction or authority
- date sensitivity
- required source type, such as official policy, documentation, curriculum, research or classroom resource
- whether citations or a bibliography are required
- any sources already supplied by the user

## Process

1. Define the research question narrowly.
2. Identify the highest-authority source category for the question.
3. Search official sources first:
   - Australian Curriculum or ACARA
   - SACE Board of South Australia
   - South Australian Department for Education
   - AITSL
   - AERO
   - eSafety Commissioner
   - official software documentation
   - government or university sources
4. Use reputable secondary sources only when official sources are unavailable, incomplete or need interpretation.
5. Check publication date, update date and jurisdiction.
6. Compare sources where accuracy matters.
7. Record each source in `SOURCE_REGISTER.md` with title, organisation, URL, access date, files used by and relevance.
8. Keep research notes short and task-focused.
9. Do not invent sources, URLs, publication dates or claims.
10. If web access is unavailable, draft from established knowledge only when safe and mark the relevant file as needing source verification.

## Output

For internal research notes:

```markdown
## Research Notes
- Question:
- Best source:
- Supporting sources:
- Key findings:
- Limits or uncertainty:
- Files using these sources:
```

For source lists inside rule or skill files, use:

```markdown
- Source title — Organisation/publisher — URL — Accessed YYYY-MM-DD
```

For the project source register, use the table format already established in `SOURCE_REGISTER.md`.

## Quality Criteria

- Sources are reputable, relevant and current enough for the task.
- Official sources are preferred for curriculum, SACE, policy and software instructions.
- Source relevance is recorded clearly.
- Claims in the drafted file can be traced to sources or supplied context.
- Weak sources do not drive the final output.
- The source list is concise and does not pad the file with unnecessary citations.

## Related Rules

- `rules/Research/RULE_RESEARCH_REQUIRED.md`
- `rules/Research/RULE_PREFERRED_SOURCES.md`
- `rules/Research/RULE_SOURCE_HIERARCHY.md`
- `rules/Research/RULE_CITATION_AND_BIBLIOGRAPHY.md`
- `rules/Research/RULE_THREE_PASS_RESEARCH.md`
- `rules/Quality control/RULE_NO_HALLUCINATED_FILES.md`

## Example User Requests

- `Research the latest SACE Chemistry assessment requirements before drafting the task.`
- `Find official Excel Online guidance for charts and filters.`
- `Use reputable sources to make a Year 9 cybersecurity context.`
- `Check the current Australian Curriculum wording for Year 8 Digital Technologies.`

## Failure Modes

- Using a blog or forum when an official curriculum or software source exists.
- Citing a source that was not opened or checked.
- Recording a source without explaining why it is relevant.
- Using outdated software instructions for a current platform.
- Treating AI-generated text as a source of truth.

## Completion Checklist

- Has the research question been defined?
- Were official or primary sources checked first?
- Are publication or access dates recorded?
- Are sources entered in `SOURCE_REGISTER.md`?
- Are unsupported claims removed or marked for verification?
- Is the source list proportional to the file?

## Sources

- Evidence use in schools national snapshot: Summary of findings — Australian Education Research Organisation — https://www.edresearch.edu.au/summaries-explainers/research-summaries/evidence-use-schools-national-snapshot-summary — Accessed 2026-05-16
- Author-date — Australian Government Style Manual — https://www.stylemanual.gov.au/referencing-and-attribution/author-date — Accessed 2026-05-16
- Australian Framework for Generative Artificial Intelligence (AI) in Schools — Australian Government Department of Education — https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools — Accessed 2026-05-16
