# Agent Delivery Report (free template)

Your coding agent says "done". This makes it tell you what it actually did.

One small skill file. At the end of every task, Claude Code, Codex or Cursor writes a short report:

1. What changed
2. Why
3. What it skipped
4. What could break
5. What it could not verify
6. How to check it

The point is the honest parts: skipped work and unverified claims show up before you merge, not after.

## Install

**Claude Code**
```bash
mkdir -p .claude/skills/delivery-report
cp SKILL.md .claude/skills/delivery-report/SKILL.md
```
Or put it in `~/.claude/skills/delivery-report/` to use it in every repo.

**Codex CLI**
Paste the body of `SKILL.md` (everything below the front matter) into `AGENTS.md` at your repo root, or into `~/.codex/AGENTS.md`.

**Cursor**
```bash
mkdir -p .cursor/rules
cp cursor/delivery-report.mdc .cursor/rules/
```
It is set to always apply.

## Files

| File | What it is |
|---|---|
| `SKILL.md` | The skill. Tells the agent when and how to write the report. |
| `delivery-report-template.md` | The report format, for PR descriptions or by hand. |
| `cursor/delivery-report.mdc` | Same skill as a Cursor rule. |

## Want more?

The full kit has five report templates (full, short, bug fix, refactor, research), filled examples, a review checklist and a PDF guide. It is paid and optional:
https://renandlsantos-ai-agent.github.io/agent-delivery-report/#pricing

This free template stays free and MIT licensed. Issues and PRs welcome.
