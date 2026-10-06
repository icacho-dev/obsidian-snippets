# Obsidian Colossus: CSS Snippets

> *"Give me your broken, your default, your huddled CSS yearning to render free. The wretched refuse of your mismatched themes. Send these, the poorly parsed, tempest-tossed to me. I lift my lamp beside the vault door!"*

A sanctuary for custom Obsidian UI overrides. This repository is dedicated to granular, surgical styling fixes without the bloat of installing a monolithic theme.

## The Arsenal

| Snippet | Description | Target | Demo |
| --- | --- | --- | --- |
| `monokai-codeblocks.css` | Forces a Monokai dark theme strictly on code blocks without bleeding into inline code or breaking Live Preview rendering. | `.cm-line.HyperMD-codeblock`, `.markdown-rendered pre` | <img width="1624" height="1061" alt="image" src="https://github.com/user-attachments/assets/161f397c-71d1-4476-9381-6ec52b6031ac" />
 |

## Deployment

1. Drop the `.css` files into your `vault/.obsidian/snippets/` directory.
2. Reload and enable them via **Settings > Appearance > CSS snippets**.

## Philosophy

No fragile selectors that break on the next minor Obsidian release. No mandatory dependencies. Just targeted CSS strikes to fix the specific UI elements that bother you. Pull requests are welcome if you have a snippet for a UI quirk that has been driving you insane.
