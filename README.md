# Humanizer: how to use it

Humanizer is a Claude skill that makes stories, scripts and essays read as human-written. It follows the findings of a study that told AI fiction apart from human fiction by its structure alone.

## Install (Claude Code)

1. Create a folder called `humanizer` inside `~/.claude/skills/`.
2. Put the `humanizer-SKILL.md` file in that folder and rename it to `SKILL.md`.
3. Restart Claude Code.

## Use it

Type `/humanizer` before your writing request:

```
/humanizer write a 500-word short story about a lighthouse keeper
```

You can also paste your own draft and ask it to humanize the draft.

Claude plans the structure first. Then it writes using the study's rules, such as never stating the moral and adding a subplot. It checks the draft against a checklist before handing it back.

## Using claude.ai instead?

Zip the `humanizer` folder and upload it under Settings > Capabilities > Skills. Then ask Claude to "use the humanizer skill".

## The research

StoryScope: Investigating idiosyncrasies in AI fiction (University of Maryland + Google DeepMind)
https://arxiv.org/abs/2604.03136
