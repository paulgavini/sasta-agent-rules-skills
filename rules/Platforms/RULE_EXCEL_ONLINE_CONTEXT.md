# Rule: Excel Online Context

## Purpose

Ensure Excel for the web resources use realistic spreadsheet features, clear formulas and school-safe collaboration practices.

## Applies To

- spreadsheet tasks
- data-entry templates
- graphing and charting activities
- formulas and functions
- CSV imports
- CSV preparation for DB Browser for SQLite
- Excel workbook sources for Power BI
- online collaboration workflows
- teacher answer keys

## Rule Statement

The agent must design Excel Online tasks around browser-based workbook behaviour, clear cell references and accessible spreadsheet structure.

## Requirements

- Refer to the platform as Excel for the web or Excel Online when appropriate.
- Use clear A1-style cell references unless another style is explicitly required.
- Label raw data, calculations and outputs separately.
- Prefer simple formulas and named ranges where they improve clarity.
- Include expected formula results or check values for answer keys.
- Do not assume desktop-only Excel features, macros, add-ins or external data connections will work in the browser.
- Account for OneDrive, SharePoint, Teams or LMS file access when collaboration is required.
- For database-development tasks, require clean tabular data: one header row, one field per column, one record per row, no merged cells, no blank headings and consistent data types.
- When exporting from Excel for DB Browser for SQLite, prefer a separate CSV file for each intended table and keep key fields stable.
- When Excel is a source for Power BI, prefer formatted Excel tables or clearly bounded ranges and document where the source workbook is stored.
- Avoid collecting or sharing identifiable student data unless approved and necessary.
- Use accessible tables, readable headings and meaningful chart labels.
- Preserve formulas as editable text rather than screenshots.

## Decision Logic

If the task needs basic formulas, charts, database-ready table preparation or collaborative editing, Excel Online is usually suitable. If the task needs macros, advanced desktop-only analysis or complex data connections, state the limitation and suggest a desktop Excel or simplified browser-safe alternative. If the next tool is DB Browser for SQLite, make the CSV handoff explicit. If the next tool is Power BI, make the workbook or CSV source path and refresh assumptions explicit. If student data is involved, use sample, anonymised or aggregated data first.

## Examples

- Use `=AVERAGE(B2:B11)` with a labelled "Average" row and a check value.
- Put raw measurements on one sheet and a summary chart on another only if students can navigate sheets confidently.
- Provide a CSV paste-in option when file upload may be blocked.
- Prepare `Customers.csv` and `Orders.csv` as two separate tables before importing them into DB Browser for SQLite.
- Keep a stable `customer_id` field in Excel so the same key can be used as a foreign key in SQLite.

## Non-Examples

- Asking students to run a macro in Excel Online.
- Hiding formulas in screenshots.
- Building a graph task without axis labels or units.
- Assuming every student has edit access to the same shared workbook.
- Publishing a class workbook containing names and marks.
- Merging title cells or adding decorative blank rows to a table that students must export to DB Browser for SQLite.
- Treating a Power BI report as proof that the underlying database design is correct without checking keys and relationships.

## Interaction With Skills

- `skills/Digital Technologies/SKILL_EXCEL_ONLINE.md`
- `skills/Digital Technologies/SKILL_DATABASES.md`
- `skills/Digital Technologies/SKILL_POWER_BI.md`
- `skills/Digital Technologies/SKILL_DATA_ANALYSIS.md`
- `rules/Digital technologies/RULE_DATA_ETHICS.md`
- `rules/Digital technologies/RULE_DEVICE_CONSTRAINTS.md`
- `rules/Document output/RULE_TABLE_STYLE.md`
- `rules/Science/RULE_DATA_AND_UNCERTAINTY.md`

## Quality Check

- Are formulas, references and expected outputs clear?
- Is the workflow browser-safe?
- Are charts labelled and accessible?
- Is student data protected?
- Are collaboration permissions realistic?
- Is there a fallback if sharing or upload fails?
- Is the table suitable for CSV export to DB Browser for SQLite or import into Power BI if that is part of the task?

## Sources

- Overview of formulas in Excel for the web - Microsoft Support - https://support.microsoft.com/en-gb/office/overview-of-formulas-in-excel-for-the-web-34519a4e-1e8d-4f4b-84d4-d642c4f63263 - Accessed 2026-05-17
- Import or export text (.txt or .csv) files - Microsoft Support - https://support.microsoft.com/en-au/office/import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba - Accessed 2026-05-17
- About Power Query in Excel - Microsoft Support - https://support.microsoft.com/en-gb/office/about-power-query-in-excel-7104fbee-9e62-4cb9-a02e-5bfb1a6c536a - Accessed 2026-05-17
- Guide to securing personal information - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/handling-personal-information/guide-to-securing-personal-information - Accessed 2026-05-17
