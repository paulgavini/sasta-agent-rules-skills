# Skill: Databases

## Purpose

This skill allows the agent to create beginner database tasks that model data clearly before implementation, with students using DB Browser for SQLite as the main database application and Excel or Power BI where they support the database workflow.

## When To Use

Use this skill when the user asks for:

- database design lessons
- entity relationship diagrams
- tables, fields, records, primary keys or foreign keys
- data normalisation at an introductory level
- database queries
- spreadsheet-to-database comparisons
- DB Browser for SQLite activities
- SQLite table creation, CSV import or query tasks
- Excel-to-SQLite or SQLite-to-Power BI workflows
- assessment scaffolds for database design

## Inputs

- scenario or information system
- required entities and data fields
- year level and prior experience
- tool context: DB Browser for SQLite, SQLite, Excel, Power BI, diagram only or other
- whether queries are required
- whether data begins in Excel, CSV files or an existing SQLite database
- whether students need to export query results for Excel or Power BI
- privacy and data-sensitivity requirements
- assessment conditions

## Process

1. Define the purpose of the database.
2. Identify entities and their attributes.
3. Decide what each record represents.
4. Choose primary keys that identify records clearly.
5. Identify relationships and possible foreign keys.
6. Check for repeated groups or mixed data in one field.
7. Create a simple ERD or table schema before implementation.
8. If using Excel first, clean the worksheet so each column is one field, each row is one record, headings are consistent, data types are clear and each table can be exported as a separate CSV file.
9. In DB Browser for SQLite, create or open the SQLite database, create the tables, set primary keys and import CSV data only after the schema is clear.
10. Write beginner SQLite queries only after the structure is clear.
11. Test queries against expected records and explain any empty or unexpected results.
12. Export query results or clean tables as CSV for Excel or Power BI only when analysis or visualisation is part of the task.
13. Use Power BI for reporting, filtering and visualisation, not as the primary database design environment.
14. Keep copies of original data, the `.sqlite` or `.db` file, exported CSV files and student query evidence clearly named.

## Output

```markdown
# Database Design

## Scenario
## Entities
## Tables And Fields
## Relationships
## DB Browser For SQLite Steps
## Excel Or CSV Preparation
## Sample Records
## SQL Queries
## Excel Or Power BI Output
## Privacy Checks
```

## Quality Criteria

- Each table has a clear purpose.
- Field names are meaningful.
- Keys and relationships are explained.
- Sample data is safe and realistic.
- SQLite queries match the schema and are tested.
- Excel is used for data preparation, checking or simple summaries rather than as a substitute for the relational database.
- Power BI is used for visualisation and reporting rather than database storage.
- The design is appropriate for the year level.

## Related Rules

- `rules/Digital technologies/RULE_DATA_ETHICS.md`
- `rules/Digital technologies/RULE_DEVICE_CONSTRAINTS.md`
- `rules/Digital technologies/RULE_CODE_CLARITY.md`
- `skills/Digital Technologies/SKILL_DATA_ANALYSIS.md`
- `skills/Digital Technologies/SKILL_EXCEL_ONLINE.md`
- `skills/Digital Technologies/SKILL_POWER_BI.md`

## Sources

- Technologies - Australian Curriculum, Assessment and Reporting Authority - https://www.australiancurriculum.edu.au/curriculum-information/understand-this-learning-area/technologies - Accessed 2026-05-17
- Digital Technologies - All elements 7-10 - Australian Curriculum, Assessment and Reporting Authority - https://www.australiancurriculum.edu.au/media/6965/technologies_digital_technologies_all_elements_7-10.pdf - Accessed 2026-05-17
- Guide to securing personal information - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/handling-personal-information/guide-to-securing-personal-information - Accessed 2026-05-17
- DB Browser for SQLite - DB Browser for SQLite project - https://sqlitebrowser.org/ - Accessed 2026-05-17
- DB Browser for SQLite GitHub project - sqlitebrowser - https://github.com/sqlitebrowser/sqlitebrowser - Accessed 2026-05-17
- Query Language Understood by SQLite - SQLite - https://sqlite.org/lang.html - Accessed 2026-05-17
