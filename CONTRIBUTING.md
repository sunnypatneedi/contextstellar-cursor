# Contributing to contextstellar-cursor

Thanks for wanting to help improve context engineering in Cursor. Contributions of all kinds are welcome — new rules, skills, bug reports, and documentation.

## Quick Start

```bash
git clone https://github.com/sunnypatneedi/contextstellar-cursor
```

## Structure

```
rules/          # Cursor rules (.mdc files)
skills/         # Cursor skills
assets/         # Plugin assets (logo, etc.)
```

## Types of Contributions

### 1. New rules

Rules live in `rules/` as `.mdc` files. Each rule should:
- Have a clear `description` in the frontmatter
- Specify `globs` for which files it applies to
- Focus on one concern (caching, ordering, provider patterns, etc.)

### 2. New skills

Skills live in `skills/` as directories with a skill definition file.

### 3. Bug reports

Open an issue with:
- Which rule or skill is affected
- Steps to reproduce
- Expected vs actual behavior

### 4. Documentation

README and inline docs are fair game.

## Pull Request Guidelines

- Keep PRs focused — one concern per PR
- Test rules in a real Cursor workspace before submitting
- Update the README if you're adding new rules or skills

## Security Vulnerabilities

Please don't open public issues for security vulnerabilities. See [SECURITY.md](./SECURITY.md) for the responsible disclosure process.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](./LICENSE).
