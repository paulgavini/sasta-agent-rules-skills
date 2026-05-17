# Skill: Power BI

## Purpose

This skill allows the agent to create Power BI learning tasks, dashboard plans and safe data visualisation guidance, including reports built from Excel workbooks, CSV exports or database query results.

## When To Use

Use this skill when the user asks for:

- a Power BI lesson
- a dashboard plan
- report design guidance
- data visualisation tasks
- reports from Excel tables, CSV files or DB Browser for SQLite query exports
- dashboard tasks connected to a database-development unit
- Power BI sharing or publishing notes
- safe use of school or sample datasets

## Inputs

- dataset and sensitivity level
- audience and purpose of the report
- Power BI Desktop, service or Teams context
- source format: Excel workbook, CSV export, DB Browser for SQLite query result or other approved dataset
- licensing and workspace information if known
- required visuals, measures or filters
- whether sharing or publishing is required
- student or staff user group

## Process

1. Define the decision or question the report should support.
2. Check data sensitivity and use sample or aggregated data where possible.
3. Identify the data source and required cleaning.
4. If the source comes from DB Browser for SQLite, use exported CSV files or a teacher-approved connector workflow and keep the SQL query that produced the dataset visible.
5. If the source comes from Excel, prefer clean Excel tables or supported workbook data rather than visually formatted sheets.
6. Choose visuals that match the data type and comparison needed.
7. Keep report pages focused and readable.
8. Add filters, slicers and summaries only when they support interpretation.
9. Check sharing, licence and permission assumptions.
10. Warn about underlying semantic model access when sharing.
11. Provide an Excel fallback when Power BI access is uncertain.
12. Treat Power BI as the visualisation and reporting layer, not the primary tool for designing relational tables or teaching SQL.

## Output

```markdown
# Power BI Plan

## Purpose
## Dataset
## Source Path From Excel Or DB Browser
## Visuals
## Filters
## Sharing And Permissions
## Privacy Checks
## Fallback
```

## Quality Criteria

- The report purpose is clear.
- Visuals are appropriate for the data.
- Source tables or query exports are documented.
- Licensing and access assumptions are explicit.
- Privacy risks are handled.
- Underlying data access is not ignored.
- The task has a practical fallback.

## Related Rules

- `rules/Platforms/RULE_POWER_BI_ONLINE_CONTEXT.md`
- `rules/Digital technologies/RULE_DATA_ETHICS.md`
- `rules/Digital technologies/RULE_DEVICE_CONSTRAINTS.md`
- `skills/Digital Technologies/SKILL_DATA_ANALYSIS.md`
- `skills/Digital Technologies/SKILL_EXCEL_ONLINE.md`

## Sources

- Microsoft Power BI training - Microsoft Learn - https://learn.microsoft.com/en-gb/training/powerplatform/power-bi?WT.mc_id=powerbi_landingpage-docs-link - Accessed 2026-05-17
- Get data from Excel workbook files - Microsoft Learn - https://learn.microsoft.com/en-us/power-bi/connect-data/service-excel-workbook-files - Accessed 2026-05-17
- Power Query Excel connector - Microsoft Learn - https://learn.microsoft.com/en-us/power-query/connectors/excel - Accessed 2026-05-17
- Share and Collaborate on Power BI Reports and Dashboards - Microsoft Learn - https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-share-dashboards - Accessed 2026-05-17
- Guide to securing personal information - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/handling-personal-information/guide-to-securing-personal-information - Accessed 2026-05-17
