# GitHub Automation Action

GitHub Action that auto-labels issues and pull requests based on keyword rules.

## Features
- Reads issue/PR title + body
- Applies inferred labels (`bug`, `feature`, `docs`, `ci`)
- Works for opened and edited events

## Files
- `action.yml`: Action metadata
- `dist/index.js`: Runtime action code
- `.github/workflows/example.yml`: Example workflow usage

## Usage
Place this action in your repository (or publish it), then reference it in workflows.

## Next upgrades
- Config-driven rules from `triage.yml`
- Auto-comments with templates
- Changelog generation on merge