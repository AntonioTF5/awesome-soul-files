# Contributing to awesome-soul-files

## How to add an entry

1. **Fork** this repository
2. **Add your soul file** somewhere publicly accessible — your own GitHub repo, a Gist, or inline in a PR
3. **Validate it**: `npx soul-cli validate your-file.soul.md` — must pass
4. **Add one line** to the appropriate section in README.md: `[Agent name](link) — one-line description`
5. **Open a pull request**

## Quality bar

An entry is accepted if the soul file:

- Validates against the SOUL.md schema (run `npx soul-cli validate`)
- Has a `personality` field that is specific to this agent — not "a helpful assistant"
- Has at least `tone`, `values`, and `knowledge_domains` filled in
- Would be genuinely useful to deploy, not a demonstration of the format
- Does not duplicate an existing entry in purpose and character

The one-line description in the README:
- States what the agent *is*, not what it *does* (e.g., "A Stoic philosopher" not "Helps with philosophy")
- Under 80 characters

## What gets rejected

- Generic agents ("helpful assistant", "friendly chatbot")
- Exact duplicates of existing entries
- Entries that fail schema validation
- Soul files containing real personal data, API keys, or sensitive information
- Entries with broken links

## Process

Maintainers review PRs on a best-effort basis. If your PR has been open for more than two weeks without feedback, feel free to ping in the comments.

## Code of conduct

Technical, direct, no jargon. Disagree with the work, not the person.
