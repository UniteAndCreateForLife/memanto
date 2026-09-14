# Claude Code + Memanto Integration

`claudecode-memanto` is a convenience CLI that installs the same Claude Code integration as `memanto connect claude-code`.

## Installation

pip install claudecode-memanto

## Usage

Install into the current project's `.claude` directory:

claudecode-memanto install

Install into `~/.claude`:

claudecode-memanto install --global

Remove the integration from the current project:

claudecode-memanto uninstall

The core integration adds its standard `CLAUDE.md` instructions and the `SessionStart`, `PreCompact`, and `PostToolUse` hooks. Hook commands use the installed Memanto Python interpreter and preserve unrelated user hooks during reinstall and removal.

## Configuration

Set `MOORCHEH_API_KEY` before starting Claude Code. The core Memanto CLI provides all memory configuration and operations.
