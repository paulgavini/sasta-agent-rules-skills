# Skill: Source Evaluation

## Purpose

This skill allows the agent to judge whether sources are credible, current, relevant, accurate, age-appropriate and suitable for school use before using them in a rule, skill or teaching resource.

## When To Use

Use this skill when:

- research has produced multiple possible sources
- a source is not official or primary
- curriculum, SACE, policy, safety, software or assessment accuracy matters
- a source may be biased, outdated, commercial or too advanced for students
- student-facing resources depend on external content
- the user supplies sources and asks whether they are suitable

## Inputs

- source title, organisation, URL and publication or update date
- intended use of the source
- subject, year level and audience
- competing or supporting sources
- whether the source is official, academic, professional, commercial, media or informal
- required standard of evidence for the task

## Process

1. Identify the source type and publisher.
2. Check whether the source directly answers the research question.
3. Check authority:
   - Who produced it?
   - Is the author or organisation qualified?
   - Is it an official source for this matter?
4. Check accuracy:
   - Are claims supported by evidence?
   - Can key claims be verified against other reliable sources?
   - Are there obvious errors or unsupported leaps?
5. Check currency:
   - Is the source current enough for the topic?
   - Does the topic change quickly, such as software, AI, cybersecurity, pricing, policy or curriculum?
6. Check purpose and bias:
   - Is the source informing, persuading, selling, advocating or entertaining?
   - Does it selectively present evidence?
7. Check relevance for school use:
   - Is it age-appropriate?
   - Is it suitable for Australian or South Australian school context?
   - Does it respect privacy, safety and inclusion?
8. Rank the source against alternatives.
9. Use the source only for claims it can reasonably support.
10. Record limitations or unresolved concerns in `AGENT_BUILD_PROGRESS.md` where relevant.

## Output

For quick evaluation:

```markdown
## Source Evaluation
- Source:
- Use:
- Authority:
- Currency:
- Accuracy:
- Relevance:
- Limitations:
- Decision: Use / Use with caution / Do not use
```

For project tracking, summarise the decision in `SOURCE_REGISTER.md` and unresolved issues in `AGENT_BUILD_PROGRESS.md`.

## Quality Criteria

- Official sources are preferred for curriculum, SACE, policy and software instructions.
- Academic or research sources are checked for relevance and practical classroom transfer.
- Commercial or advocacy sources are not used as neutral evidence without caution.
- Current topics use current sources.
- Student-facing sources are age-appropriate and safe.
- Evaluation decisions are concise and evidence-based.

## Related Rules

- `rules/Research/RULE_PREFERRED_SOURCES.md`
- `rules/Research/RULE_SOURCE_HIERARCHY.md`
- `rules/Research/RULE_RESEARCH_REQUIRED.md`
- `rules/Research/RULE_CITATION_AND_BIBLIOGRAPHY.md`
- `rules/Quality control/RULE_ACCURACY_CHECK.md`
- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`

## Example User Requests

- `Check whether these websites are suitable for a Year 8 research task.`
- `Evaluate this article before using it in a cybersecurity lesson.`
- `Which source should I trust for SACE assessment rules?`
- `Can this YouTube tutorial be used for a student-facing Python task?`

## Failure Modes

- Assuming a source is reliable because it looks professional.
- Using a source because it agrees with the desired conclusion.
- Ignoring publication date for fast-changing topics.
- Using a university-level source directly with Year 8 students without adaptation.
- Treating a source as authoritative outside its area of expertise.

## Completion Checklist

- Has authority been checked?
- Has currency been checked against the topic?
- Has accuracy been compared with other reliable sources where needed?
- Has purpose or bias been considered?
- Is the source suitable for the student's age and school context?
- Has the use decision been recorded?

## Sources

- Question your sources — Monash University — https://www.monash.edu/student-academic-success/sharpen-your-thinking/critical-thinking/question-your-sources — Accessed 2026-05-16
- Evaluating information — Monash University Library — https://www.monash.edu/library/help/assignments-research/finding-and-evaluating-information/evaluating-information — Accessed 2026-05-16
- Evidence use in schools national snapshot: Summary of findings — Australian Education Research Organisation — https://www.edresearch.edu.au/summaries-explainers/research-summaries/evidence-use-schools-national-snapshot-summary — Accessed 2026-05-16
