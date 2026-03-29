# Claude Instructions

## Git Rules

- Commit & push on every change (no confirmation needed)
- One commit = one responsibility (split as small as possible)
- Commit messages must be written in Japanese, concisely
- Follow Conventional Commits format

### Commit Message Format

```
<type>: <summary in Japanese>

Co-Authored-By: Claude <noreply@anthropic.com>
```

### Types

| Type | When to use |
|---|---|
| `feat` | New feature or new file |
| `chore` | Config files, miscellaneous tasks |
| `refactor` | Refactoring |

### Examples

```
docs: day1タシケントの旅程を追加

Co-Authored-By: Claude <noreply@anthropic.com>
```

```
fix: day3ブハラの宿泊情報を修正

Co-Authored-By: Claude <noreply@anthropic.com>
```