# Contribution Guide

## Branching Strategy
- **main branch** → always stable, production-ready
- **feature branches** → use `feature/<name>` for new features
- **fix branches** → use `fix/<issue>` for bug fixes

## Commit Message Format
Follow the conventional commit style:
- `feat:` → new feature
- `fix:` → bug fix
- `docs:` → documentation updates
- `chore:` → non-code changes (configs, deps)

Example:
```
feat(auth): add JWT-based login system
```

## Pull Requests
- Ensure your branch is up to date with `main`
- Include clear description of changes
- Request review before merging

## Code Style
- Prettier + ESLint (will be configured later)
- Keep functions small and modular
- Write comments for complex logic
