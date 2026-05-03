# VitePress (vitepress)

VitePress is a Vite and Vue powered static site generator widely used for developer documentation. It converts Markdown content into fast, beautiful documentation sites with support for Vue components embedded directly in Markdown pages. VitePress is the official documentation framework used by Vue, Vite, Rollup, Pinia, and many open source projects.

VitePress ships a polished default theme with built-in dark mode, mobile-responsive layout, full-text local search, Algolia DocSearch integration, internationalization, and automatic sitemap generation. Its configuration is TypeScript-first, providing IntelliSense for all config options. A rich build hook system enables advanced customizations, and data loaders allow fetching remote or local file data at build time.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/vitepress/refs/heads/main/apis.yml)

## Tags

- Documentation
- Markdown
- Open Source
- Static Site Generator
- Vite
- Vue

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-03

## APIs

### VitePress Runtime API

Vue composition functions for use in custom themes and pages: useData(), useRoute(), useRouter(), withBase(), Content component, and ClientOnly component.

**Human URL:** [https://vitepress.dev/reference/runtime-api](https://vitepress.dev/reference/runtime-api)

### VitePress Site Configuration

TypeScript-first configuration exported from .vitepress/config.ts controlling all site metadata, routing, theming, Markdown, Vite/Vue integration, and build hooks.

**Human URL:** [https://vitepress.dev/reference/site-config](https://vitepress.dev/reference/site-config)

## Common Properties

- [Website](https://vitepress.dev)
- [Documentation](https://vitepress.dev/guide/getting-started)
- [GitHub](https://github.com/vuejs/vitepress)

## Artifacts

| Type | File | Description |
|------|------|-------------|
| JSON Schema | [json-schema/vitepress-config-schema.json](json-schema/vitepress-config-schema.json) | Schema for the VitePress site configuration file |
| JSON Schema | [json-schema/vitepress-frontmatter-schema.json](json-schema/vitepress-frontmatter-schema.json) | Schema for per-page YAML frontmatter |
| JSON Structure | [json-structure/vitepress-config-structure.json](json-structure/vitepress-config-structure.json) | Structural documentation for the site configuration |
| JSON-LD | [json-ld/vitepress-context.jsonld](json-ld/vitepress-context.jsonld) | Linked data context mapping VitePress entities to standard vocabularies |
| Vocabulary | [vocabulary/vitepress-vocabulary.yml](vocabulary/vitepress-vocabulary.yml) | VitePress domain vocabulary and terminology |

## Examples

- [Site Configuration](examples/vitepress-config-example.json)
- [Frontmatter](examples/vitepress-frontmatter-example.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
