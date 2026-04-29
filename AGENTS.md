# AGENTS.md

This repository contains configuration for the Zed editor, including settings,
keymaps, and tasks.

## Repository structure

- `settings.json` - Main configuration file with editor preferences, language
  settings, agent configuration, and UI customization.
- `keymap.json` - Custom keyboard shortcuts and Vim mode bindings.
- `tasks.json` - Custom tasks for the task runner.

## Modifying configuration

- JSON files may include comments.
- When editing, preserve existing structure and comments.
- Fetch the reference docs for `settings.json` to verify correct keys and values:
  <https://zed.dev/docs/reference/all-settings>
- When editing `keymap.json`, use the context-based binding system.
