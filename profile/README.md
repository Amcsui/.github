## AMCSUI Collaboration Guideline
Welcome to the GitHub Guidelines for AMCSUI. These guidelines aim to ensure a consistent, organized, and efficient workflow within our GitHub organization.

### Repository Management
- Each repository should have a designated admin responsible for overseeing changes and ensuring commitment to guidelines.
- All proposed changes should be submitted as pull requests for review by the repository admin. This process helps maintain code quality and prevents unintended modifications.
- If the admin is unable to merge a pull request due to technical limitations, a member of the technical team should assist in the process.

### Branching Strategy
- Create a new branch for each specific subject or feature to isolate changes and facilitate management.
- After merging a branch, promptly remove it to keep the repository organized and prevent clutter.
- Once a pull request is submitted, refrain from adding new commits unless absolutely necessary to maintain focus and prevent conflicts.
- Squash merging is preferred as it combines multiple commits into a single commit, reducing the number of commits in the main branch and improving readability. Unless the branch addresses multiple unrelated issues, consider merging it to avoid fragmentation.

### Commit Guidelines
- Write commit messages using imperative verb forms (e.g., "Add new feature," "Fix bug") to clearly convey the intent of the change. Think to yourself ` If applied, my commit will ` and proceed to write your commit.
- Keep commit messages short and descriptive, providing a concise summary of the change.
- For projects with multiple scopes, use keywords to specify the area affected by the change, for example:

  `Docs: Fix spelling mistakes in the main tutorial`
- If necessary, include a list of detailed changes starting with a hyphen to provide more context and clarify the modifications, for example:
```
- Fix crashing on startup bug
- Update the project structure
- ...
```
- Avoid Ending Sentences with Punctuation
