# AGENTS.md: rules for your coding agent

Your agent reads this file first. Keep it short and current.

## Project

- **What this builds:** [One or two sentences]
- **Who it's for:** see `INTENT.md`
- **Stack:** [For example: Python 3.12, one HTML page, the OpenRouter API]
- **Product Page:** `docs/index.md`, plain Markdown that GitHub Pages turns into the team's public page. Fill it only with facts from `INTENT.md` and `TEST_LOG.md`, and leave a [bracket] where the team has no answer yet.

## Commands

- **Install:** `[For example: python3 -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt]`
- **Run:** `[For example: python app.py]`
- **Check:** `[For example: python tests/check.py]`

## Rules

1. **Plan first.** Before changing more than one file, propose a short plan and wait for a yes.
2. **Small changes.** One change at a time, small enough to explain in a sentence.
3. **Explain it.** Say what changed, why, what could break, and how you checked it.
4. **Check your work.** Run the checks and record the results in `TEST_LOG.md`. Never invent a result.
5. **No secrets in code.** Read keys from `.env`. Add new variable names to `.env.example`, never their values.
6. **Ask before acting on the world.** Don't send messages, spend money or publish anything without a person's OK.
7. **Stop when stuck.** If a fix fails twice, stop, say what failed, and ask before trying a third way.
