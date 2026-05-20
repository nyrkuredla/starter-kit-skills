# starter-kit-skills
A pair of AI skill files for figuring out what you actually need, and then building it.

---

## What's in here

```
starter-kit/
  skill-builder/
    SKILL.md          ← needs analysis interview agent
  solution-builder/
    SKILL.md          ← artifact builder agent
  README.md
  LICENSE
```

---

## The idea

Many AI workflows fail at the same place: someone asks for a tool before they
understand their actual problem. They get a generic answer, use it twice, and
abandon it.

This kit runs you through two focused steps instead:

1. **Skill-Builder** interviews you. It's looking for what you
   *actually do*, not what you *wish* you did. At the end it produces a
   **Session Brief** — a single Markdown file capturing your situation,
   behavioral patterns, constraints, and a proposed solution direction.

2. **Solution-Builder** reads the Session Brief and builds the artifact. Because
   it knows your context specifically, what it produces is shaped around you —
   not a generic template you'll tweak once and ignore.

The output might be a reusable prompt, a checklist, a workflow, or just "do X." The most important thing is that it properly fits your needs, constraints, and preferences, and is designed to be used and reused over time to solve your actual problem.

---

## How to use these

These are **SKILL.md files** — structured instruction files for AI agents. They
work with any LLM chat interface (option A) or agentic AI setup that supports system prompts or custom
instructions (Claude Code, OpenAI Codex, Google Antigravity, Cursor, VS Code Copilot, etc.) (option B).

### Option A: Paste into a chat interface (ChatGPT, Claude, Gemini, etc.)

1. Open `skill-builder/SKILL.md`
2. Copy the entire file contents
3. Paste it as the first message in a new chat
4. Answer the interview questions
5. Save the Session Brief it produces as a `.md` file
6. Open a new chat, paste `solution-builder/SKILL.md` as the first
   message, then paste your Session Brief
7. Confirm the plan, get your artifact

### Option B: Use as agent skill files

If you're running an agentic setup (e.g., a local agent framework, Cursor
agents, or VS Code extensions), place the folders directly in your agent skills
directory and invoke them by name.

---

## What you'll get out

A working artifact (prompt, template, checklist, or workflow) sized for your
actual situation; a solution designed speciically for you, that
you can use immediately.

---

## License

MIT. Use it, fork it, break it, improve it.
