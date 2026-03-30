# Wubi Template

A sanitized starter template for building a warm, proactive companion-style OpenClaw agent without exposing private identity, memories, secrets, or credentials.

## What this is

This repo is a **starter kit**, not a dump of a real agent.

It includes:
- workspace structure
- editable template files
- proactive memory patterns
- safety/privacy guardrails
- lightweight continuity tools for long-running companion agents

It does **not** include:
- API keys
- OAuth tokens
- cookies
- email addresses
- private memories
- personal chat logs
- real user profile data
- production credentials or device identities

## Included files

- `AGENTS.md` — operating rules for the workspace
- `SOUL.md` — lightweight personality / boundaries template
- `USER.md` — blank human context template
- `HEARTBEAT.md` — proactive check-in checklist
- `SESSION-STATE.md` — active working memory
- `MEMORY.md` — curated long-term memory template
- `TOOLS.md` — local environment notes
- `memory/working-buffer.md` — danger-zone context survival log
- `memory/YYYY-MM-DD.example.md` — daily memory example
- `docs/privacy-and-sharing.md` — what to keep private when sharing

## Design goals

This template is built around a few practical ideas:
- warm, non-corporate assistant voice
- concrete reminders instead of generic nagging
- write important things down immediately
- recover cleanly after context compaction
- keep autonomy bounded and explainable
- never publish secrets or private personal context

## How to use

1. Copy this folder into a fresh OpenClaw workspace.
2. Personalize `SOUL.md` and `USER.md`.
3. Fill `TOOLS.md` with local environment notes only.
4. Keep `MEMORY.md` high-signal and private.
5. Use daily files under `memory/` for raw notes.
6. Update `SESSION-STATE.md` during active work.

## Why this exists

A lot of agent setups are either:
- too generic to feel alive
- or too personal to share safely

This template aims for the middle:
- enough structure to be genuinely useful
- enough privacy discipline to publish safely
- enough openness that other people can shape it into their own companion agent

## Notes

This template intentionally avoids shipping a fully formed character. It gives structure, tone, and guardrails — then leaves the actual relationship and personality to the person using it.
