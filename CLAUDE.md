# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

A reference guide — written in plain Markdown — cataloging the Gen X pop culture movies and TV shows most commonly quoted by people born roughly 1965–1980. It is a content project, not a software project. There are no build steps, tests, linters, or dependencies.

## File structure

| File | Contents |
| --- | --- |
| `README.md` | Introduction, how-to-use, decade index, link to glossary, closing notes |
| `movies-1970s.md` | Entries 1–14 |
| `movies-1980s.md` | Entries 15–45 |
| `movies-1990s.md` | Entries 46–88 |
| `movies-2000s.md` | Entries 89–104 |
| `tv-shows.md` | Entries 105–135 |
| `quick-quote-glossary.md` | Cheat-sheet tables (quote → source), one section per decade + TV |

## Entry format

Every entry in the decade files follows this structure:

```markdown
## N. Title (Year)

**Plot in plain language.** ...

**Why it stuck.** ...

**Quotes you'll actually hear.**
- "Quote text." — Scene context. How/when Gen X deploys it.

**Where it pops up now.** ...

---
```

New entries must match this format exactly. The entry number (`N.`) is sequential across all files (1970s starts at 1, 1980s picks up where 1970s ends, etc.).

## Glossary format

`quick-quote-glossary.md` contains Markdown tables, one per decade:

```markdown
## The 1970s

| If you hear this… | They are quoting… |
| --- | --- |
| "Quote text." | Movie Title (Year) |
```

When adding a new entry to a decade file, add the corresponding quotes to the matching decade section of the glossary.

## Conventions

- Decade files each start with `[Back to the main index](README.md)` and a brief era-context paragraph before the first entry.
- Profanity is partially censored with asterisks (e.g., `f***`, `b****`, `a**`) throughout.
- Relative dates in entries should be written in absolute terms where possible.
- The README entry count line (`**Total: 135 entries across the whole guide.**`) should be updated whenever entries are added.
