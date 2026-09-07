# ETHRome 2026 Hacker Manual

The Hacker Manual of **ETHRome 2026**, the hackathon by [urbe.eth](https://urbe.build) at Urbe Hub, Rome, **Friday 11 to Sunday 13 September 2026**, in plain Markdown. Rules, prizes and bounties, schedule, judging, submissions, code of conduct, demo video, and a guide to Rome.

It exists so you can put the manual **inside your agentic tools** (Claude Code, Cursor, Codex, anything that reads files or URLs) and keep it up to date with a `git pull`.

The canonical version is the website: **https://ethrome.org/hackermanual**. If anything here ever disagrees with the site, the site wins.

<!-- sync:start -->
Synced from [https://ethrome.org/hackermanual](https://ethrome.org/hackermanual) on **2026-09-07** (site commit `b1e7066`).
<!-- sync:end -->

## What is inside

| File | What it is |
|---|---|
| `manual/` | One Markdown file per page of the manual, same names as the site |
| `HACKER-MANUAL.md` | All ten pages in one file, to paste into any context window |
| `llms.txt` | Index of the pages in the [llms.txt](https://llmstxt.org) convention |
| `AGENTS.md`, `CLAUDE.md` | Instructions for the agent reading this repo (same content) |

## Use it with your agent

**Clone it next to your project**, or add it as a submodule, and pull before each session:

```bash
git clone https://github.com/urbeETH/ethrome-2026-hacker-manual.git
# or, inside your project
git submodule add https://github.com/urbeETH/ethrome-2026-hacker-manual.git hacker-manual
```

**Claude Code:** clone it into your project and the `CLAUDE.md` is picked up automatically; or reference a page directly, for example `@hacker-manual/manual/judging.md`.

**Cursor, Codex and other tools that take a docs URL:** point them at the whole manual in one file, `https://raw.githubusercontent.com/urbeETH/ethrome-2026-hacker-manual/main/HACKER-MANUAL.md`, or at `llms.txt` for the page index.

## Related

- [urbeETH/llm-docs](https://github.com/urbeETH/llm-docs): documentation of web3 tools packaged for AI editors, from the same community.
- Questions: [hello@urbe.build](mailto:hello@urbe.build) or the Telegram group linked in the manual.

## License

Content licensed under [CC BY 4.0](LICENSE). ETHRome and Urbe Hub names and logos belong to their owners.
