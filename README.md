# claude-catppuccin

Catppuccin Mocha status line and theme for Claude Code. Works on Windows (Git Bash), Linux and macOS.

Needs `jq`, `git` and a Nerd Font.

```sh
cp statusline.sh ~/.claude/statusline.sh
mkdir -p ~/.claude/themes && cp themes/catppuccin-mocha.json ~/.claude/themes/
```

Then in `~/.claude/settings.json`:

```json
"theme": "custom:catppuccin-mocha",
"statusLine": { "type": "command", "command": "bash ~/.claude/statusline.sh", "padding": 0 }
```

Status line based on [tjhanley's gist](https://gist.github.com/tjhanley/01f2d2b682739bdc4802db74655d37c7).
Theme from [vishwajitsarnobat/catppuccin-claude-code](https://github.com/vishwajitsarnobat/catppuccin-claude-code) (MIT, see `themes/LICENSE`).
