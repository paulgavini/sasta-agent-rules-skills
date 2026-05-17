# Rule: Data Ethics

## Purpose

Ensure Digital Technologies tasks involving data, online tools, AI systems or student information use ethical, privacy-aware and age-appropriate practices.

## Applies To

- data collection and analysis tasks
- surveys, forms and spreadsheets
- dashboards and visualisations
- database-development tasks using Excel, DB Browser for SQLite and Power BI
- AI, machine learning and recommendation-system examples
- cybersecurity and online safety tasks
- student-facing digital projects
- teacher notes involving personal or sensitive information

## Rule Statement

The agent must treat data ethics as part of the design of digital solutions, including privacy, consent, fairness, security, transparency, data minimisation and potential harm.

## Requirements

- Identify whether data is personal, sensitive, confidential, school-owned, public or synthetic.
- Prefer anonymised, de-identified, aggregated or synthetic data for classroom examples.
- Do not ask students to collect unnecessary personal information.
- Avoid using real student names, contact details, health information, behaviour records or assessment data in public tools.
- State when consent, school approval or teacher judgement is needed.
- Include data minimisation: collect only what is needed for the learning purpose.
- Consider bias, representation and unfair impact when using data to make decisions.
- Explain that de-identified data can sometimes become identifiable when combined with other information.
- Include privacy and security controls appropriate to the task, such as access limits, passwords, passphrases or multi-factor authentication.
- When data moves between Excel, DB Browser for SQLite and Power BI, check each export, import and shared file for personal information, hidden columns, unnecessary identifiers and re-identification risk.
- Keep student database tasks based on fictional, synthetic, anonymised or public datasets unless the teacher has explicitly approved authentic data.
- Make online safety advice practical and strengths-based rather than fear-based.
- Do not fabricate datasets or claims about data sources; label sample data clearly.

## Decision Logic

If a task can use synthetic or low-risk data, use that first. If authentic data is needed, reduce the data fields, remove identifiers and state the approvals or safeguards required. If a task involves student personal information, online platforms, AI tools or publication, pause to check privacy, consent, platform terms and school policy requirements.

## Examples

- Use fictional survey responses about preferred project themes rather than real student wellbeing data.
- Use suburb-level public environmental data rather than individual location tracking.
- Ask students to discuss how missing groups in a dataset could affect a recommendation.
- State that a dashboard should show aggregated class results, not individual student names.
- Use fictional customer, product or library-loan data for SQL practice instead of real student records.
- Export only the fields needed for a Power BI report rather than the whole SQLite database if some columns are sensitive.

## Non-Examples

- Uploading identifiable student work or assessment data to an unapproved public AI tool.
- Asking students to collect classmates' private details when the task only needs categories.
- Treating "anonymous" survey data as safe without checking whether combinations of answers identify someone.
- Using a biased dataset without discussing limitations.
- Publishing student-created data products without checking consent and privacy settings.
- Sharing a Power BI report from a SQLite export while leaving sensitive source fields in the semantic model.
- Using real names or assessment records in Excel before importing them into a student SQLite database.

## Interaction With Skills

- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`
- `rules/Digital technologies/RULE_DEVICE_CONSTRAINTS.md`
- `skills/Digital Technologies/SKILL_DATA_ANALYSIS.md`
- `skills/Digital Technologies/SKILL_DATABASES.md`
- `skills/Digital Technologies/SKILL_EXCEL_ONLINE.md`
- `skills/Digital Technologies/SKILL_CYBERSECURITY_CONTEXTS.md`
- `skills/Digital Technologies/SKILL_POWER_BI.md`

## Quality Check

- Has the data type and sensitivity been identified?
- Is personal information avoided or minimised?
- Are privacy, consent and school-policy needs visible?
- Are bias and fairness considered where data informs decisions?
- Is the source of data real, cited or clearly labelled as sample data?
- Are security controls proportionate to the risk?

## Sources

- Technologies - Australian Curriculum, Assessment and Reporting Authority - https://www.australiancurriculum.edu.au/curriculum-information/understand-this-learning-area/technologies - Accessed 2026-05-17
- Best Practice Framework for Online Safety Education - eSafety Commissioner - https://www.esafety.gov.au/educators/best-practice-framework - Accessed 2026-05-17
- Guide to securing personal information - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/handling-personal-information/guide-to-securing-personal-information - Accessed 2026-05-17
- Guidance on privacy and the use of commercially available AI products - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/guidance-on-privacy-and-the-use-of-commercially-available-ai-products - Accessed 2026-05-17
