# VitePress

VitePress is a Vite and Vue powered static site generator widely used for developer documentation. It converts Markdown content into fast, beautiful documentation sites with support for Vue components embedded directly in Markdown pages.

VitePress ships a polished default theme with built-in dark mode, mobile-responsive layout, full-text local search, Algolia DocSearch integration, internationalization, and automatic sitemap generation. Its configuration is TypeScript-first, providing IntelliSense for all config options. A rich build hook system (`buildEnd`, `postRender`, `transformHead`, `transformHtml`, `transformPageData`) enables advanced customizations such as PWA support and custom search indexing. Data loaders allow fetching remote or local file data at build time for generating dynamic content like blog indexes and API references.

- **Website:** https://vitepress.dev
- **Documentation:** https://vitepress.dev/guide/getting-started
- **GitHub:** https://github.com/vuejs/vitepress

## Artifacts

| Type | File | Description |
|------|------|-------------|
| JSON Schema | [json-schema/vitepress-config-schema.json](json-schema/vitepress-config-schema.json) | Schema for the VitePress site configuration file (`.vitepress/config.ts`) |
| JSON Schema | [json-schema/vitepress-frontmatter-schema.json](json-schema/vitepress-frontmatter-schema.json) | Schema for per-page YAML frontmatter including layout, hero, and features |
| JSON-LD | [json-ld/vitepress-context.jsonld](json-ld/vitepress-context.jsonld) | Linked data context mapping VitePress entities to standard vocabularies |
