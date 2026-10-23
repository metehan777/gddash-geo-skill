# gddash-geo-skill

A Claude Code skill that turns the GDdash "GEO Guide 2027" (John Shehata, https://gddash.com/geo-optimization-guide/) into a 91-action, evidence-graded playbook for planning, auditing and measuring visibility in AI search (ChatGPT, Google AI Overviews/AI Mode, Bing Copilot, Perplexity, Claude).

## Install

```bash
git clone https://github.com/metehan777/gddash-geo-skill.git ~/.claude/skills/geo-optimization-guide
```

Start a new Claude Code session so the skill is picked up.

## Usage

Run `/geo-optimization-guide` in Claude Code, optionally followed by a task, for example:

```
/geo-optimization-guide audit example.com for AI search visibility
```

Automatic invocation is off (`disable-model-invocation: true` in `SKILL.md`) because the playbook is about 87 KB (~20k tokens) and its description matches most SEO questions. Delete that line if you want Claude to load the skill on its own.
