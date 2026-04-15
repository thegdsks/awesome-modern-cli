# Contributing to Modern CLI

Thank you for helping grow this list! Please read these guidelines before submitting a pull request.

## How to Add a Tool

1. **One tool per pull request.** This keeps reviews focused and the git history clean.
2. Fork the repo, create a branch, and edit `README.md`.
3. Add your entry in the correct category, maintaining **alphabetical order** within the section.
4. Submit a pull request using the provided PR template.

## Entry Format

Every entry must follow this format:

```markdown
- [tool-name](https://github.com/owner/repo) - Brief description of what it does. Replaces `classic-tool`. `language`
```

**Example:**

```markdown
- [ripgrep](https://github.com/BurntSushi/ripgrep) - Recursively searches directories for a regex pattern, respecting gitignore. Replaces `grep`. `Rust`
```

Required fields:
- **Tool name** with link to the repository
- **Description** -- what it does, not just "it's fast" or "it's written in Rust"
- **Replaces** -- which classic Unix/POSIX tool it modernizes
- **Language** -- primary implementation language

## Quality Criteria

A tool must meet **all** of the following to be included:

- **100+ GitHub stars** -- demonstrates community interest
- **Actively maintained** -- at least one commit in the last 12 months
- **Solves a real problem** -- provides a genuine improvement over the classic tool it replaces (speed, UX, features, safety)
- **Installable** -- published via a package manager or provides pre-built binaries

## What Makes a Good Submission

- Explain *why* the tool is awesome, not just what language it uses
- Screenshots or GIFs showing the tool in action are encouraged
- If the tool replaces multiple classic tools, pick the primary one

## What Will Get Your PR Closed

- Tools that do not meet the quality criteria above
- Entries not in alphabetical order
- Multiple tools in a single PR
- Self-promotion without disclosure (mention if you are the author)
- Duplicate entries

## Updating an Existing Entry

If a tool has changed significantly (renamed, new repo URL, expanded scope), feel free to submit a PR updating its entry. Explain what changed in the PR description.

## Questions?

Open an issue if you are unsure whether a tool fits. We are happy to discuss before you invest time in a PR.
