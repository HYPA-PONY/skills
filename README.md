# HYPA PONY skills for Claude Code

Two prompts, installable as skills.

- **/hypa-brain** builds the Hypa Brain memory factory: private repo + mirror, save-every-turn
  hooks, secret/contract/destruction gates, the brain CLI, and a SPEC.md of numbered laws with
  a self-test behind each one. Run once per machine; safe to re-run (converges, never rebuilds).
- **/hypaloop [goal]** runs HYPALOOP v2, a dual-audited work loop that drives a goal to
  verified completion and keeps its state in files so it survives a context limit.

## Install

```
/plugin marketplace add HYPA-PONY/skills
/plugin install hypa@hypapony
```

Or copy the two folders in `plugins/hypa/skills/` into `~/.claude/skills/`.

Prefer to read before you run? Both prompts are published in full at https://hypapony.com

Hypa Brain is an independent project. Claude and Claude Code are trademarks of Anthropic.
Not affiliated with or endorsed by Anthropic.
