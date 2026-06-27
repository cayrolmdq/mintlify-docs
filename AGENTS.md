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

Audience by section:

- **Público general (SEO/AEO):** todo salvo "Para desarrolladores". Escribir para
  cualquier persona, no para perfiles técnicos.
- **Técnico:** la sección "Para desarrolladores" (`mcp.mdx`, `convenciones-api.mdx`).

Reglas para las páginas de público general:

- Español rioplatense (Argentina), voseo, segunda persona ("vos/tu")
- Tono cercano y sin jerga; explicar conceptos, no listar endpoints
- Optimizar para SEO y AEO: títulos en forma de pregunta, una respuesta directa al
  inicio, secciones de "Preguntas frecuentes" (`<AccordionGroup>`), enlaces internos
- No incluir tablas de endpoints, snake_case/camelCase ni códigos HTTP en páginas
  de público general (eso va solo en la sección técnica)
- Una idea por oración; usar componentes Mintlify (`<Card>`, `<Steps>`, `<Note>`,
  `<Tip>`, `<Accordion>`) donde aporten

## Content boundaries

- Documentar **comportamiento funcional y beneficios**, no implementación interna
- No documentar operaciones de admin interno ni detalles sensibles de seguridad
