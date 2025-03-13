# Code Review Guidelines

## Pull Request Review Process

### 1. Understand the Narrative
- Determine the narrative by reading the pull request description and list of commits
- If the commits seem to jump between topics or address unrelated issues, leave a comment asking for clarification or changes

### 2. Verify Commit Structure
- Lightly scan the message and contents of each commit, starting from the beginning of the branch
- Verify smallness and atomicity by checking that:
  - Each commit does one thing
  - No commit includes incomplete implementations
- Recommend splitting or combining commits that are incorrectly scoped

### 3. Detailed Commit Analysis
- Thoroughly read each commit
- Ensure the commit message sufficiently explains the code by:
  - Checking that implementation matches the intent
  - Verifying that the code matches the stated implementation
- Use the context and justification to guide your understanding of the code
- If any of the requisite information is missing, ask for clarification from the author

### 4. Final Verification
- Finally, with a complete mental model of the commit's changes and the overarching narrative, confirm the code is efficient and bug-free