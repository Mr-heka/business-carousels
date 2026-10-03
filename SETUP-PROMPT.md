# Setup prompt

For Claude Code or Codex. Copy the block below and paste it into your agent.

```text
Install the business-carousels skill from https://github.com/Mr-heka/business-carousels

1. Clone the repository into a temporary folder.
2. Copy the folder skills/business-carousels, including its references and assets folders, to:
   - ~/.claude/skills/business-carousels if you are Claude Code
   - ~/.agents/skills/business-carousels if you are Codex
   If that folder already exists, show me what differs and ask before replacing it.
3. The skill contains only Markdown, JSON and example images. There is nothing to run or install, and it needs no accounts or API keys.
4. Confirm SKILL.md is in place, delete the temporary clone, and tell me in two sentences how to start a carousel with it.
```

Using Claude in the browser or the app, or ChatGPT? You don't need to install anything: paste [PROMPT.md](PROMPT.md) into a chat instead. See [QUICKSTART.md](QUICKSTART.md).
