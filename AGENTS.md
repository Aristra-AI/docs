# Documentation project instructions

## About this project

- Aristra's user documentation, built on [Mintlify](https://mintlify.com).
- Pages are MDX files with YAML frontmatter (`title`, `description`). Configuration and navigation live in `docs.json`.
- Run `mint dev` to preview and `mint broken-links` to check links before a change is merged.
- A page describes the product as it ships. When a feature changes, the page changes with it.

## Naming

- **Aristra Code** is the coding agent, on every surface: Aristra Desktop's Code tab, the Aristra CLI, editors and a cloud computer.
- **Aristra Desktop** is the Mac app. The `aristra` command is the **Aristra CLI**.
- **Aristra One** is the website, app.aristralabs.com.
- **Aristra Cloud** is what a plan pays for.
- Chats are "chats". Say "commands", not "slash commands", and "non-interactive mode", not "headless".

## Style

- Address the reader as "you", in the active voice, one idea per sentence.
- Plain words over jargon. Say what something does, then how to use it.
- No em dashes: use a colon, a comma or two sentences.
- Sentence case for headings. Bold for UI elements (**Settings**), code formatting for commands, settings, file names and paths.
- Tables for options, settings and comparisons; a short example before the details.

## The Account and plans tab

The prices, limits and allowances on the `account/` pages are the product's own figures. Change a figure only when the product changes it, and change every page that names it.
