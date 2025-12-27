# AGENTS.md

## Repository Overview

This is a configuration repository for the Zed editor. It contains settings,
keymaps, and tasks that customize the Zed development environment.

## Repository Structure

- `settings.json` - Main configuration file with editor preferences, language
  settings, agent configuration, and UI customization
- `keymap.json` - Custom keyboard shortcuts and vim mode bindings
- `tasks.json` - Custom tasks for the task runner

## Modifying Configuration

When editing `settings.json`:

- The file uses JSON with comments
- Preserve existing structure and comments
- The edit predictions `disabled_globs` list protects sensitive files from AI
  editing
- Agent configuration includes both default model settings and per-provider
  server settings

When editing `keymap.json`:

- Uses context-based binding system
- Existing bindings are vim-mode aware with specific contexts

