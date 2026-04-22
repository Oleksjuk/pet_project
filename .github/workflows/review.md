---
name: Project Code Reviewer
on:
  pull_request:
    types: [opened, synchronize]
permissions:
  contents: read
---

# Instructions

Please review the changes in this pull request. 
Pay special attention to the initialization endpoints in the migration service and ensure their logic is correctly set up. 
Ensure that no deprecated update functionality is being reintroduced.