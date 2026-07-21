---
name: Daily Report Status
on:
  workflow_dispatch:
permissions:
  contents: read
  issues: read
  copilot-requests: write
safe-outputs:
  create-issue:
---

After identifying the most-reacted issue, write one sentence explaining why resolving it
would benefit the team, based on the issue title and description.