# [Product name]

> **One line:** [Who is it for, and what job does it do for them?]

- **Team:** [Names]
- **Product Page:** `https://gen-ai-lab-f26.github.io/[your-repo]/`
- **Live app or demo:** [Link, if you have one]

## Start here

1. **Turn on your Product Page:** Settings → Pages → Deploy from a branch → main → /docs → Save. About a minute later it's live at the address above.
2. **Add your teammates:** Settings → Collaborators and teams → Add people, with the Write role.
3. **Start [`INTENT.md`](./INTENT.md) during Week 5 (November 24):** who it's for, their workflow today, and your riskiest assumption.
4. **Build the smallest version that runs on a real case,** and start testing it early.
5. **Log your checks and testers in [`TEST_LOG.md`](./TEST_LOG.md) as you go,** not the night before.
6. **Keep your Product Page current** in [`docs/index.md`](./docs/index.md). It's plain text: replace everything in [brackets].

## Make your commits count

Everyone on the team commits to this repo on at least two different days every week. It's part of your own grade. Git only knows a commit is yours if it knows who you are, so run this once in your cube or on your laptop, with your own name and the email on your GitHub account:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

If GitHub keeps your email private, use the noreply address it shows under Settings → Emails. Commits you make on GitHub's website count automatically.

## The easiest way to edit

You don't need to install anything. On GitHub, open a file, press the pencil to edit it, then press **Commit changes**. Your Product Page updates about a minute later.

To add your screenshot, open the `docs` folder, choose **Add file → Upload files**, and upload a picture named `demo.png`. It replaces the placeholder.

## Let your agent help

Clone this repo into your cube or onto your laptop, start your agent (Pi, Claude Code or Codex) inside the folder, and try:

- "Read INTENT.md and TEST_LOG.md, then fill in docs/index.md. Don't make anything up: leave a [bracket] wherever we don't have the answer yet."
- "Show me what changed, write a short commit message that says why, then commit and push."

## What's in this repo

| File | What it's for | Hand in? |
| --- | --- | --- |
| [`docs/index.md`](./docs/index.md) | Your public Product Page: pitch, demo, evidence | Its link |
| [`INTENT.md`](./INTENT.md) | Your one-page product brief | Yes |
| [`TEST_LOG.md`](./TEST_LOG.md) | Baseline, five checks, testers, fixes | Yes |
| [`AGENTS.md`](./AGENTS.md) | The rules your agent reads first | |
| [`.env.example`](./.env.example) | Where API keys go. Your real `.env` stays off GitHub. | |

The [Final Project brief](https://www.icerynk.com/c/fa26-tech-ub-41-7w2-001/content/final-project-ai-product-and-demo) in Icerynk has the rubric and the submission box.

## Working from your cube or laptop

```bash
git clone https://github.com/gen-ai-lab-f26/<your-repo>.git
cd <your-repo>
```

Pull before you start (`git pull`), commit when something works, and push when you're done (`git push`). Pushing from your cube asks for your GitHub username and a password: use a personal access token (GitHub → Settings → Developer settings → Personal access tokens), never your GitHub password. Treat the token like a password and keep it out of the repo.

## Running it

[Ask your agent to write the exact install and run commands here and in `AGENTS.md`.]
