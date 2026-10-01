# Slash commands

For an overview of Codex CLI slash commands, see [this documentation](https://developers.openai.com/codex/cli/slash-commands).

In the TUI, slash completion also lists enabled user-installed skills as
`/name (skill)` with their descriptions. A builtin command with the same name
appears before the skill. Select the skill with the arrow keys and press Enter
to invoke it, or accept it with Tab or `/` to insert its `$name` mention before
submitting. Skill selections use the same resolved skill path as `$` completion.
