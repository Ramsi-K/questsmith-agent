# Repeatable Task: Store GitHub Project Index

## Purpose

- Persist the results of a GitHub project crawl in a structured, queryable format for future reference, automation, and outreach.

## Task Checklist

1. **Input**

   - Receive a list of indexed projects, each with:
     - Project Name
     - Repo Link
     - Subfolder Path (if any)
     - Summary
     - Tags
     - Tech/Tools
     - Last Updated
     - (Optional) Additional metadata

2. **Select Storage Backend**

   - Choose where to store the data:
     - Notion database (recommended for job search sprints)
     - Google Sheet
     - Local JSON or CSV file
     - SQLite database

3. **Define Schema**

   - Ensure the following fields are present:
     - Project Name
     - Repo Link
     - Subfolder Path
     - Summary
     - Tags
     - Tech/Tools
     - Last Updated
     - (Optional) Date Indexed

4. **Write Data**

   - Overwrite or append to the storage backend as specified.
   - Ensure data is deduplicated and up-to-date.

5. **Verify**
   - Confirm that all projects are stored and retrievable.
   - (Optional) Log the date/time of this indexing run.

### How to Trigger

- “Store my latest GitHub project index in Notion.”
- “Dump indexed projects to JSON/CSV/Sheets.”

---
