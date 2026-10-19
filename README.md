# Superpowers, Ponytail, UI UX Pro Max and Caveman for Claude Code

Add four Claude Code plugins with one marketplace:

| Plugin | What it does |
| --- | --- |
| [Superpowers](https://github.com/obra/superpowers) | Proven working habits: test-driven development, systematic debugging, planning before coding, and code review. |
| [Ponytail](https://github.com/DietrichGebert/ponytail) | "Lazy senior dev" mode: pushes Claude toward the simplest, shortest solution that works. |
| [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | A searchable design library of styles, color palettes, font pairings and chart guidance for building UI. |
| [Caveman](https://github.com/JuliusBrussee/caveman) | Ultra-short replies: cuts filler while keeping code, commands and exact error messages. |

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
/plugin install caveman@avela-superpowers
```

Type each command on its own. Then restart Claude Code.

Or from a terminal:

```
claude plugin marketplace add Adrian-withlol/claude-superpowers
claude plugin install superpowers@avela-superpowers
claude plugin install ponytail@avela-superpowers
claude plugin install ui-ux-pro-max@avela-superpowers
claude plugin install caveman@avela-superpowers
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
/plugin uninstall caveman@avela-superpowers
/plugin marketplace remove avela-superpowers
```

## Credits

This repo only provides an install listing. Superpowers, Ponytail and UI UX Pro Max are released under the MIT License, and Caveman under the Apache License 2.0, by their authors. Report bugs or request features at the original repositories:

- Superpowers by [Jesse Vincent](https://github.com/obra): [obra/superpowers](https://github.com/obra/superpowers/issues)
- Ponytail by [Dietrich Gebert](https://github.com/DietrichGebert): [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail/issues)
- UI UX Pro Max by [nextlevelbuilder](https://github.com/nextlevelbuilder): [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill/issues)
- Caveman by [Julius Brussee](https://github.com/JuliusBrussee): [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman/issues)
