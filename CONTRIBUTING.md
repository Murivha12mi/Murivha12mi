# Contributing Guidelines

## Version Control Expectations
- Use version control for every change.
- Keep commits focused and scoped to a single logical change.
- Ensure the history reads clearly when viewed in GitHub/GitLab.

## Commit Conventions
Use [Conventional Commits](https://www.conventionalcommits.org/) to keep history consistent.

**Format**
```
<type>(<optional scope>): <subject>
```

**Common types**
- `feat`: new user-facing functionality
- `fix`: bug fix
- `docs`: documentation-only change
- `refactor`: code change that neither fixes a bug nor adds a feature
- `test`: adding or updating tests
- `chore`: tooling or maintenance tasks

**Examples**
- `feat(api): add pagination to list endpoint`
- `fix(ui): prevent double submit on save`
- `docs: add contribution and commit guidelines`

## Pull Request Log
Every pull request should include:
- **Summary** of changes
- **Testing** performed (with commands and results)
- **Notes** for reviewers (risks, migrations, or follow-ups)

Use the repository PR template to keep this consistent.
