> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is the functional documentation site for **Gastuki** (expense tracking via
  WhatsApp + loyalty/analytics for merchants, plus an MCP server for AI agents).
- It is built on [Mintlify](https://mintlify.com)
- Content is written in **Spanish (Argentina)**
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- The docs describe **functional behavior**, not implementation details
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- **Cliente / Usuario final**: end user, identified by their WhatsApp phone number
- **Comercio / Merchant**: a registered business (rutas `/merchant/*`)
- **Sello (stamp)**, **Cupón (coupon)**, **Happy Moment / Ruleta**: loyalty primitives
- Routes under `/merchant/*` use **snake_case**; all other routes use **camelCase**

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
