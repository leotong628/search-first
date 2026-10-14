# search-first

An Agent Skill that instructs an AI agent to search public issues, release notes and docs before guessing at a fix.

A skill is instructions in a file. It guides an agent; it does not enforce anything.

## Install

```
npx skills add leotong628/search-first
```

Or copy `skills/search-first/` into `~/.claude/skills/` (or `.claude/skills/` in a project). For Claude.ai, zip the `search-first` folder and upload it.

`npx` runs a separately fetched third-party command that this project has not audited. Prefer copying the files from a tagged release.

## What is in it

One short `SKILL.md` (see `skills/search-first/SKILL.md`). No scripts, no dependencies.

## Status

Version 0.1, written from daily use and reviewed before publication. It has not yet been tested against a baseline with formal evals; treat it as a working draft and open an issue with what you see.

## How this was made

Designed and directed by Leo Tong, written with AI agents (Claude). Licence: MIT.
