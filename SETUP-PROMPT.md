# Setup prompt

For Claude Code or Codex. Copy the whole block below and paste it into your agent.

```text
Install the business-carousels skill from https://github.com/SelrAI-Skool-Community/business-carousels

1. Clone the repository into a temporary folder with a shallow sparse checkout: use `git clone --depth 1 --filter=blob:none --sparse`, then run `git sparse-checkout set skills/business-carousels` in the clone.
2. Use the complete skills/business-carousels folder, including SKILL.md, references and assets. Its destination is:
   - ~/.claude/skills/business-carousels if you are Claude Code
   - ~/.agents/skills/business-carousels if you are Codex
3. If the destination already exists, compare it with the incoming folder before changing anything. If they match, leave it in place. If they differ, show added, changed and local-only files, with text diffs where possible, then ask me what to do. Keep my existing folder untouched until I answer.
4. If the destination is absent, copy the complete folder there. Confirm SKILL.md, its referenced pages and example images are present before deleting the temporary clone. The skill needs no scripts, accounts or API keys.
5. Tell me in two sentences how to start a carousel with it.
```

Using Claude in the browser or the app, or ChatGPT? You don't need to install anything: paste [PROMPT.md](PROMPT.md) into a chat instead. See [QUICKSTART.md](QUICKSTART.md).
