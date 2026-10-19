# Superpowers, Ponytail and UI UX Pro Max for Claude Code

Add three Claude Code plugins with one marketplace:

| Plugin | What it does |
| --- | --- |
| [Superpowers](https://github.com/obra/superpowers) | Proven working habits: test-driven development, systematic debugging, planning before coding, and code review. |
| [Ponytail](https://github.com/DietrichGebert/ponytail) | "Lazy senior dev" mode: pushes Claude toward the simplest, shortest solution that works. |
| [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | A searchable design library of styles, color palettes, font pairings and chart guidance for building UI. |

## Install

Add the marketplace once:

```
/plugin marketplace add Adrian-withlol/claude-superpowers
```

Then install any of the plugins:

```
/plugin install superpowers@avela-superpowers
/plugin install ponytail@avela-superpowers
/plugin install ui-ux-pro-max@avela-superpowers
```

Type each command on its own. Then restart Claude Code.

Or from a terminal:

```
claude plugin marketplace add Adrian-withlol/claude-superpowers
claude plugin install superpowers@avela-superpowers
claude plugin install ponytail@avela-superpowers
claude plugin install ui-ux-pro-max@avela-superpowers
```

## Update

```
/plugin marketplace update avela-superpowers
```

This repo points straight at each plugin's original repository, so every install gets the latest version. No code is copied here.

## Remove

```
/plugin uninstall superpowers@avela-superpowers
/plugin uninstall ponytail@avela-superpowers
/plugin uninstall ui-ux-pro-max@avela-superpowers
/plugin marketplace remove avela-superpowers
```

## Credits

This repo only provides an install listing. All three plugins are released under the MIT License by their authors. Report bugs or request features at the original repositories:

- Superpowers by [Jesse Vincent](https://github.com/obra): [obra/superpowers](https://github.com/obra/superpowers/issues)
- Ponytail by [Dietrich Gebert](https://github.com/DietrichGebert): [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail/issues)
- UI UX Pro Max by [nextlevelbuilder](https://github.com/nextlevelbuilder): [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/issues)
