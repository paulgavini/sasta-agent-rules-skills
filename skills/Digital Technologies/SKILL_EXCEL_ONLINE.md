# Skill: Excel Online

## Purpose

This skill allows the agent to create Excel Online spreadsheet tasks that use clear data structures, formulas, charts and collaboration assumptions, including data preparation for DB Browser for SQLite and Power BI.

## When To Use

Use this skill when the user asks for:

- an Excel Online activity
- a spreadsheet formula task
- data entry or analysis templates
- charts from class data or sample data
- CSV-to-spreadsheet workflows
- spreadsheet preparation for DB Browser for SQLite
- CSV export or import checks for database tables
- Excel data sources for Power BI reports
- spreadsheet answer keys

## Inputs

- data source or sample dataset
- required formulas, charts or summaries
- student year level and spreadsheet experience
- whether the spreadsheet will become a database table, CSV export or Power BI source
- whether students work individually or collaboratively
- Microsoft 365, OneDrive, SharePoint, Teams or LMS context
- privacy and data-sensitivity requirements
- output format

## Process

1. Define the question the spreadsheet should answer.
2. Separate raw data, calculations and outputs.
3. Use clear headings and consistent units.
4. Choose simple formulas and references suited to Excel for the web.
5. Provide check values or expected results where useful.
6. Create charts only when they support comparison or interpretation.
7. Include sharing and permissions assumptions if collaboration is requested.
8. Use sample, anonymised or aggregated data where privacy matters.
9. Check for browser-safe features and avoid desktop-only assumptions.
10. For database development, structure data so each sheet or table has one record type, one header row, no merged cells, no blank heading cells and consistent data types.
11. Preserve identifiers needed for database relationships, such as primary-key and foreign-key fields, but use fictional or de-identified values for classroom data.
12. When DB Browser for SQLite is the next step, specify whether students should copy data, download CSV files or use a teacher-supplied exported file, depending on the school's browser and file-access constraints.
13. When Power BI is the next step, keep source tables clean and explain whether Power BI will import an Excel workbook, a CSV export or another approved dataset.

## Output

```markdown
# Excel Online Task

## Goal
## Data Layout
## Formulas
## Chart Or Summary
## Database Preparation Notes
## CSV Or Power BI Export Notes
## Checks
## Privacy Or Sharing Notes
```

## Quality Criteria

- Data layout is clear.
- Formulas use editable text and visible references.
- Charts are labelled.
- Database-ready tables have one record type per table, consistent field names and stable key fields.
- CSV or Power BI handoff notes are clear.
- Collaboration assumptions are realistic.
- Student data is protected.
- Browser limitations are considered.

## Related Rules

- `rules/Platforms/RULE_EXCEL_ONLINE_CONTEXT.md`
- `rules/Digital technologies/RULE_DATA_ETHICS.md`
- `rules/Digital technologies/RULE_DEVICE_CONSTRAINTS.md`
- `rules/Document output/RULE_TABLE_STYLE.md`
- `rules/Science/RULE_DATA_AND_UNCERTAINTY.md`

## Sources

- Overview of formulas in Excel for the web - Microsoft Support - https://support.microsoft.com/en-gb/office/overview-of-formulas-in-excel-for-the-web-34519a4e-1e8d-4f4b-84d4-d642c4f63263 - Accessed 2026-05-17
- Import or export text (.txt or .csv) files - Microsoft Support - https://support.microsoft.com/en-au/office/import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba - Accessed 2026-05-17
- About Power Query in Excel - Microsoft Support - https://support.microsoft.com/en-gb/office/about-power-query-in-excel-7104fbee-9e62-4cb9-a02e-5bfb1a6c536a - Accessed 2026-05-17
- Guide to securing personal information - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/handling-personal-information/guide-to-securing-personal-information - Accessed 2026-05-17
