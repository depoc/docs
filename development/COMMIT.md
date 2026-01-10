# Git Commit Message Convention

This guide defines a consistent style for Git commit messages using standard commit types.

`<type>[optional scope]: description`

## Commit Types

| Type       | Purpose                                                          |
| ---------- | ---------------------------------------------------------------- |
| `feat`     | A new feature                                                    |
| `fix`      | A bug fix                                                        |
| `chore`    | Routine tasks, tooling, build setup, etc. No user-facing changes |
| `refactor` | Code changes that neither fix a bug nor add a feature            |
| `style`    | Code formatting, missing semicolons, indentation, etc.           |
| `docs`     | Documentation changes only                                       |
| `test`     | Adding or refactoring tests; no production code change           |
| `perf`     | Performance improvements                                         |
| `ci`       | CI/CD config or scripts                                          |
| `build`    | Changes affecting build system or dependencies                   |
| `revert`   | Reverts a previous commit                                        |

## Examples

- `feat(product): add product filtering by category`
- `fix(auth): resolve login redirect issue`
- `chore: clean up unused dependencies`
- `refactor(cart): simplify discount calculation logic`
- `style: format code with Prettier`
- `docs(readme): add deployment instructions`
- `test(api): add tests for order creation endpoint`
- `perf(query): reduce number of joins in report view`
- `ci: add lint step to GitHub Actions`
- `build: upgrade to Node.js 20`
- `revert: revert "feat(auth): add JWT authentication"`

---

## Guidelines

- Use present tense (e.g., "add", not "added").
- Keep the message concise but descriptive.
- Include a scope when applicable: `feat(api)`, `fix(ui)`, etc.