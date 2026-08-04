# VitePress (vitepress)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
