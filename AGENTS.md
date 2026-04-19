# AGENTS.md

This is a configuration repository for the Zed editor. It contains settings,
keymaps, and tasks that customize the Zed editor.

## Repository structure

- `settings.json` - Main configuration file with editor preferences, language
  settings, agent configuration, and UI customization
- `keymap.json` - Custom keyboard shortcuts and Vim mode bindings
- `tasks.json` - Custom tasks for the task runner

## Modifying configuration

- All JSON files include comments
- When editing, preserve existing structure and comments
- Fetch reference docs for `settings.json` to verify correct keys and values:
  <https://zed.dev/docs/reference/all-settings>
- When editing `keymap.json`, use the context-based binding system
