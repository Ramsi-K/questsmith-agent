---

## Repeatable Task: Deep GitHub Project Indexing

### Purpose
- Keep the user's project catalogue up-to-date for job search, portfolio, and outreach.
- Auto-tag and summarize all repos, including subfolder projects and key scripts.
- Use as a single source of truth for micro-projects, resume tailoring, and outreach.

### Task Checklist

1. **Select GitHub Profile**
   - Input: GitHub username or profile URL.

2. **Crawl All Public Repos**
   - For each repo:
     - Parse main `README.md` in root.
     - Parse all `README.md` files in first-level subfolders.
     - If no README, look for:
       - Notebooks (`.ipynb`)
       - Key scripts (`train.py`, `main.py`, etc.)
       - `/docs` or `/examples` folders.

3. **Extract & Summarize**
   - For each project/subproject:
     - Name, short summary, main tech/tools, and tags (AI, MLOps, Product, Research, etc.).
     - Repo link and subfolder path (if not root).
     - Optional: Last updated date.

4. **Auto-Tag**
   - Based on detected keywords, libraries, and context.

5. **Output**
   - Notion-ready table (or CSV/JSON) with:
     - Project Name
     - Repo Link
     - Subfolder Path
     - Summary
     - Tags
     - Tech/Tools
     - Last Updated

6. **(Optional) Schedule**
   - Set a reminder to re-run this crawl every X weeks or after major repo updates.

### How to Trigger
- “Update my GitHub project index.”
- “Deep crawl my GitHub for new projects.”
- “Re-catalogue all repos for job search.”

### What You’ll Get
- A single, up-to-date, auto-tagged project index for all public work.
- No more manual portfolio curation or missed micro-projects.
- Always ready for targeted outreach and resume tailoring.

---
