# What is ELI5 Rule?

I was getting burned out reading AI outputs. 
So I made a simple rule: ELI5 — 'Explain Like I'm Five.' 

It's simple. Try it.

# How to Apply

ELI5 ships as a Claude Code **output style** — a file that changes Claude's tone at the system-prompt level, while `keep-coding-instructions: true` keeps all of its coding abilities intact.

## Steps

1. Copy `output-styles/eli5.md` into `~/.claude/output-styles/`
2. In Claude Code, run `/config` → Output style → pick **ELI5**
3. Start a new session (or `/clear`). Done.

> `~/.claude/output-styles` → available in all projects. Use `<project>/.claude/output-styles` to apply to one project only.
>
> Prefer settings? Set `"outputStyle": "ELI5"` in `~/.claude/settings.json` instead of step 2.
