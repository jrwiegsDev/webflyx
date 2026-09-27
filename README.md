# WebFlyx (Git practice repo)

> **Status: Archived (September 2026).** A sandbox from [Boot.dev](https://www.boot.dev/)'s Learn Git course, completed in May 2026. It's kept public as a record of that coursework and is no longer maintained.

The content is intentionally simple: a small, made-up movie catalog of Markdown and CSV files. The point of the repo is its **commit history**, not the files. Each commit message starts with a letter (A–L) matching a step in the course.

## What's in the history

| Concept | Where to see it |
|---|---|
| Commits and staging | `A` through `E` on `main` |
| Branching | The `add_classics` feature branch (`D`, `H`, `I`, `L`) |
| Merge commits | `F: Merge branch 'add_classics'` brings the branch into `main` |
| Keeping a branch up to date | `K` merges `main` back into `add_classics` |
| Amending a commit | `K` was committed from VS Code and then amended to fix its message |
| Pull requests | [PR #1](https://github.com/jrwiegsDev/webflyx/pull/1) merges `add_classics` into `main` on GitHub |

To see the branch and merge structure yourself:

```bash
git clone https://github.com/jrwiegsDev/webflyx.git
cd webflyx
git log --graph --oneline --all
```

## Files

- `contents.md`: an index of the repo's files
- `titles.md`: movie titles in the catalog
- `classics.csv`: classic movies with director and year
- `quotes/`: memorable quotes, one Markdown file per movie
