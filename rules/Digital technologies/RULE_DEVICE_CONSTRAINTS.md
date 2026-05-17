# Rule: Device Constraints

## Purpose

Ensure Digital Technologies resources are realistic for school-managed devices, restricted networks, browser-based tools, student accounts and classroom time.

## Applies To

- programming and digital project tasks
- software setup instructions
- web-based tools and platforms
- microcontroller, robotics and sensor activities
- data, spreadsheet and dashboard tasks
- database-development tasks using DB Browser for SQLite, Excel and Power BI
- relief lessons and LMS-ready instructions

## Rule Statement

The agent must account for likely device, browser, network, account, installation, accessibility and safety constraints before recommending a digital workflow.

## Requirements

- Prefer the user's named platform, device and school system when supplied.
- Do not assume students can install software, browser extensions, packages or drivers.
- Offer browser-based or no-install alternatives where practical.
- Check whether a task needs accounts, logins, email verification, cloud storage or public sharing.
- Avoid workflows that require students to enter personal information into unapproved tools.
- Include offline, unplugged or low-tech alternatives when access is uncertain.
- Keep file formats and exports compatible with common school systems such as LMS, Microsoft 365 or Google Workspace when relevant.
- For database-development tasks, check whether DB Browser for SQLite is already installed or approved on student devices before giving installation-dependent instructions.
- Plan for file handling between tools: Excel workbook or CSV source files, SQLite `.sqlite` or `.db` files, exported query results and Power BI report files or service uploads.
- Do not assume students can install SQLite tools, ODBC drivers, Power BI Desktop, gateways, extensions or connectors unless the school context confirms it.
- Prefer teacher-supplied starter files and exported CSVs when installation, permissions or storage paths are uncertain.
- State hardware needs clearly for micro:bit, robotics, sensors or other devices.
- Plan for shared devices, slow internet, blocked websites, battery limits and missing peripherals.
- Include accessibility needs such as screen size, captions, keyboard access, readable text and assistive technology.
- Do not promise that a platform will work unless it has been checked or the user has supplied that context.

## Decision Logic

If device access is unknown, design the simplest realistic workflow and state assumptions. If the task depends on a specific tool, list the minimum requirements and a fallback. If privacy, account creation or installation is involved, flag the need for teacher or school approval before student use.

## Examples

- Use a browser-based Python editor for a short lesson, with a local or unplugged tracing task as a fallback.
- Provide Scratch instructions that work in the online editor and note when saving requires an account.
- For a micro:bit task, list the board, USB cable or Bluetooth requirement, battery pack if needed, browser and pairing requirement.
- For a data task, provide a CSV file path or pasted sample data rather than requiring students to sign up for a new service.
- For a DB Browser task, provide a teacher-supplied starter `.sqlite` file or CSV files if students cannot create files reliably on managed devices.
- For a Power BI task, provide an Excel or CSV fallback if students do not have Power BI Desktop or the required service licence.

## Non-Examples

- Assuming students can install Python packages on school laptops.
- Requiring a personal email sign-up for a one-lesson activity without approval.
- Building a lesson around a blocked website with no fallback.
- Asking students to upload identifiable data to a public platform.
- Giving instructions that only work on a large screen when students may use tablets.
- Assuming students can install DB Browser for SQLite or Power BI Desktop on locked-down school laptops.
- Requiring students to connect Power BI directly to a live database when a CSV export would meet the learning goal safely.

## Interaction With Skills

- `rules/Digital technologies/RULE_DATA_ETHICS.md`
- `rules/Quality control/RULE_CLASSROOM_REALISM.md`
- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`
- `skills/Digital Technologies/SKILL_EXCEL_ONLINE.md`
- `skills/Digital Technologies/SKILL_DATABASES.md`
- `skills/Digital Technologies/SKILL_POWER_BI.md`
- `skills/Electronics/SKILL_MICROBIT_PROGRAMMING.md`
- `skills/LMS and school systems/SKILL_LMS_READY_OUTPUT.md`

## Quality Check

- Are required devices, accounts and permissions explicit?
- Is installation avoided or justified?
- Is there a practical fallback if access fails?
- Are privacy and data-entry risks considered?
- Will the activity fit normal classroom time and supervision?
- Is the workflow usable on likely student devices?
- Are database, spreadsheet and Power BI file handoffs realistic for managed student devices?

## Sources

- Technologies - Australian Curriculum, Assessment and Reporting Authority - https://www.australiancurriculum.edu.au/curriculum-information/understand-this-learning-area/technologies - Accessed 2026-05-17
- Best Practice Framework for Online Safety Education - eSafety Commissioner - https://www.esafety.gov.au/educators/best-practice-framework - Accessed 2026-05-17
- Guide to securing personal information - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/handling-personal-information/guide-to-securing-personal-information - Accessed 2026-05-17
- Make content accessible - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/make-content-accessible - Accessed 2026-05-17
- DB Browser for SQLite - DB Browser for SQLite project - https://sqlitebrowser.org/ - Accessed 2026-05-17
- DB Browser for SQLite GitHub project - sqlitebrowser - https://github.com/sqlitebrowser/sqlitebrowser - Accessed 2026-05-17
