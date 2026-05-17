# Rule: Power BI Online Context

## Purpose

Ensure Power BI Online resources account for licensing, sharing, permissions, data sensitivity and dashboard design constraints.

## Applies To

- Power BI report and dashboard tasks
- data visualisation lessons
- reports created from database query results
- Excel workbook or CSV data-source workflows
- Power BI service workflows
- sharing and publishing instructions
- teacher or staff-facing dashboard notes
- student data analysis tasks

## Rule Statement

The agent must treat Power BI Online as a permissioned cloud reporting service where sharing a report can also expose underlying data unless access is deliberately controlled.

## Requirements

- Use the current Microsoft term Power BI service when precision matters, and note that users may call it Power BI Online.
- Check whether the task needs Power BI Desktop, the Power BI service, Teams, SharePoint or Excel integration.
- Check whether the source data comes from Excel, CSV exports, DB Browser for SQLite query results or another approved source.
- Do not assume students or staff have Power BI Pro, Premium Per User or suitable Fabric/Premium capacity.
- State sharing, workspace and app permissions clearly.
- Treat public links and broad organisation links as inappropriate for private or sensitive data.
- Warn that sharing reports or dashboards can grant access to underlying semantic models unless security is configured.
- Prefer sample, synthetic, anonymised or aggregated datasets for teaching.
- Treat Power BI as the reporting and visualisation layer for database-development tasks; do not use it as a substitute for schema design, keys, relationships or SQL query evidence in DB Browser for SQLite.
- Keep the source path visible, such as Excel workbook, CSV export or SQL query result, so students can trace a visual back to the database evidence.
- Include row-level security or restricted access only when the user asks for deployment guidance and the context supports it.
- Avoid publishing identifiable student data, assessment data or behaviour records.
- Design visuals with clear titles, labels, filters, legends and accessible colour choices.
- Provide a non-Power BI fallback, such as Excel charts, when licensing or access is uncertain.

## Decision Logic

If the task is classroom learning, keep the dataset low-risk and focus on interpreting visuals. If the task is an operational dashboard, clarify audience, permissions, refresh needs and data sensitivity before drafting. If sharing is requested, explain the license and access assumptions rather than promising that all recipients can open the report.

## Examples

- Use a fictional canteen sales dataset to teach bar charts, filters and summaries.
- State that a shared report link may require the recipient to sign in and have the correct licence.
- Recommend an Excel chart when the learning goal is basic visualisation and Power BI access is uncertain.
- Build a report from an exported SQLite query result, then ask students to explain which SQL query produced the data.
- Use Power BI to compare categories from a clean Excel table after students have checked the table structure.

## Non-Examples

- Publishing a public report containing student names or marks.
- Assuming a free Power BI account can share dashboards with a class.
- Hiding sensitive columns in visuals while leaving the underlying model accessible.
- Ignoring row-level security when different viewers should see different data.
- Treating dashboard design as only decoration rather than data communication.
- Using Power BI visuals to hide or bypass a poorly designed database schema.
- Connecting to a live or shared dataset without checking permissions, refresh and underlying data access.

## Interaction With Skills

- `skills/Digital Technologies/SKILL_POWER_BI.md`
- `skills/Digital Technologies/SKILL_DATABASES.md`
- `skills/Digital Technologies/SKILL_EXCEL_ONLINE.md`
- `skills/Digital Technologies/SKILL_DATA_ANALYSIS.md`
- `rules/Digital technologies/RULE_DATA_ETHICS.md`
- `rules/Digital technologies/RULE_DEVICE_CONSTRAINTS.md`
- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`
- `rules/Document output/RULE_TABLE_STYLE.md`

## Quality Check

- Are licensing and access assumptions explicit?
- Is the dataset safe for the intended audience?
- Are sharing and permission risks explained?
- Are visuals readable and meaningful?
- Is there a lower-friction fallback if Power BI access fails?
- Are privacy and security controls proportionate?
- Can the report be traced back to an approved Excel, CSV or DB Browser query source?

## Sources

- Microsoft Power BI training - Microsoft Learn - https://learn.microsoft.com/en-gb/training/powerplatform/power-bi?WT.mc_id=powerbi_landingpage-docs-link - Accessed 2026-05-17
- Get data from Excel workbook files - Microsoft Learn - https://learn.microsoft.com/en-us/power-bi/connect-data/service-excel-workbook-files - Accessed 2026-05-17
- Power Query Excel connector - Microsoft Learn - https://learn.microsoft.com/en-us/power-query/connectors/excel - Accessed 2026-05-17
- Share and Collaborate on Power BI Reports and Dashboards - Microsoft Learn - https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-share-dashboards - Accessed 2026-05-17
- Guide to securing personal information - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/handling-personal-information/guide-to-securing-personal-information - Accessed 2026-05-17
