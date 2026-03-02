> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}

## Cursor Cloud specific instructions

- **Dev server**: Run `mint dev` from the workspace root (where `docs.json` lives). Serves on `http://localhost:3000` by default. Use `--port <N>` for a different port.
- **Link checking** (lint equivalent): Run `mint broken-links`. The starter template has 3 pre-existing broken links in `essentials/images.mdx` and `essentials/settings.mdx`; these are not regressions.
- **No build step**: This is a content-only Mintlify docs site. There is no `package.json`, no test suite, and no traditional build. The Mintlify CLI handles everything.
- **Hot reload**: The `mint dev` server watches for file changes and hot-reloads automatically.
- **AGENTS.md in .mintignore**: `AGENTS.md` is listed in `.mintignore` so the Mintlify CLI does not attempt to parse it as MDX (HTML comments cause parse errors).
