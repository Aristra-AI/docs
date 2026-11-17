# Documentation project instructions

## About this project

- Aristra's user documentation, built on [Mintlify](https://mintlify.com).
- Pages are MDX files with YAML frontmatter (`title`, `description`). Configuration and navigation live in `docs.json`.
- Run `mint dev` to preview and `mint broken-links` to check links before a change is merged.
- A page describes the product as it ships. When a feature changes, the page changes with it. Check a claim against the product before writing it; don't describe what is planned.

## How the site is organized

- **Aristra** (pages at the root, `surfaces/`): Aristra itself, the backbone. Your account, chats, memory, projects, files, Craft, connectors and scheduled tasks, and the surfaces you use it on.
- **Aristra Code** (`code/`): one surface, Aristra working in folders on your computer, with its own guides, configuration and reference.
- **Account and plans** (`account/`): the plans, the balance, usage and prices, and export.

## Naming

- **Aristra** is the assistant. Each place you use it is a **surface**: the web and phone, Aristra Desktop, Aristra Code, Telegram and a cloud computer.
- **Aristra One** is your account's plan (Free, Plus, Pro or Max) and its account pages, as in Desktop's **Aristra One** menu: your plan, balance, usage and devices. It is never the website.
- The website is app.aristralabs.com: say "the website" or "on the web".
- **Aristra Desktop** is the Mac app. Its two tabs are the **Chat** tab and the **Code** tab.
- **Aristra Code** is Aristra working in folders on your computer: the terminal, Desktop's Code tab and editors. The `aristra` command is the **Aristra CLI**.
- **Aristra Cloud** is what a plan pays for: Aristra's models, the cloud agent and everything else Aristra hosts.
- Chats are "chats". Say "commands", not "slash commands", and "non-interactive mode", not "headless".

## Style

- Address the reader as "you", in the active voice, one idea per sentence.
- Plain words over jargon. Say what something does, then how to use it.
- No em dashes: use a colon, a comma or two sentences.
- Sentence case for headings. Bold for UI elements (**Settings**), code formatting for commands, settings, file names and paths.
- Tables for options, settings and comparisons; a short example before the details.

## The Account and plans tab

The prices, limits and allowances on the `account/` pages are the product's own figures. Change a figure only when the product changes it, and change every page that names it.
