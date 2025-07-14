# Repeatable Task: Time-Boxed GitHub Project Indexing

## Purpose

- Quickly index and summarize only the user's GitHub projects that have been updated within a specified time window (e.g., last 7 days, last 30 days).
- Useful for sprint recaps, portfolio updates, or highlighting recent work for outreach.

## Task Checklist

1. **Select GitHub Profile**

   - Input: GitHub username or profile URL.

2. **Set Time Window**

   - Specify the time frame (e.g., last 7 days, last 30 days).

3. **Crawl Public Repos**

   - For each repo:
     - Check last updated date.
     - If updated within the time window:
       - Parse main `README.md` in root.
       - Parse all `README.md` files in first-level subfolders.
       - If no README, look for notebooks, key scripts, `/docs` or `/examples` folders.

4. **Extract & Summarize**

   - For each qualifying project/subproject:
     - Name, short summary, main tech/tools, tags.
     - Repo link and subfolder path (if not root).
     - Last updated date.

5. **Output**
   - Notion-ready table (or CSV/JSON) with:
     - Project Name
     - Repo Link
     - Subfolder Path
     - Summary
     - Tags
     - Tech/Tools
     - Last Updated

## How to Trigger

- “Index only my GitHub projects updated in the last [X] days.”
- “Show me new or changed repos this month.”

---
