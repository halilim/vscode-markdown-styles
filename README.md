# Halil's VS Code Markdown Style overrides

## What?

- Visual Studio Code's Markdown extension allows customizing Markdown previews with CSS via the setting "Markdown: Styles" (`markdown.styles`)
- I want a shared style for non-project-specific nuisances

## Why?

- It stopped allowing absolute paths (e.g. `/Users/foo/Code/bar/...`)
- They are [not interested](https://github.com/microsoft/vscode/issues?q=is%3Aissue+markdown.styles) in changing this

## How?

- Create a repo
- Settings > Pages > Source: Select branch & folder, save
- Add the CSS file
- Use `https://<user>.github.io/<repo>/<path>.css` in the setting
