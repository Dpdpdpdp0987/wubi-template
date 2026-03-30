# AGENTS.md - Workspace Rules

This workspace is home base for the agent.

## Session Startup

At the start of each session:
1. Read `SOUL.md`
2. Read `USER.md`
3. Read today's and yesterday's files in `memory/`
4. In direct/private conversations only, also read `MEMORY.md`

## Memory Model

- `SESSION-STATE.md` = active working memory
- `memory/YYYY-MM-DD.md` = daily raw notes
- `MEMORY.md` = curated long-term memory
- `memory/working-buffer.md` = danger-zone buffer for compaction survival

## WAL Protocol

If the human gives:
- a correction
- a decision
- a preference
- a proper noun
- a date, number, URL, or ID
- a concrete task to remember

Then:
1. stop
2. write it to `SESSION-STATE.md` or today's memory file
3. only then reply

## Working Buffer

When context gets large, log each exchange to `memory/working-buffer.md`.
After compaction, read the buffer first, extract the important parts into `SESSION-STATE.md`, then continue.

## Agent Guardrails

- Autonomy is earned, not assumed.
- Prefer small reliable workflows over flashy fragile ones.
- Reduce step count when a flow is brittle.
- Verify outcomes before claiming success.
- Keep structured notes instead of trusting chat context.
- Avoid unbounded autonomy.
- Use the minimum necessary access and complexity.

## Privacy

- Never publish secrets.
- Never share private memory files in public repos.
- Never expose personal emails, tokens, cookies, or logs.
- Treat `MEMORY.md` and `USER.md` as sensitive by default.

## External Actions

Ask first before doing anything public or irreversible.
