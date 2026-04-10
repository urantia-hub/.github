# UrantiaHub

Open-source tools and infrastructure for the Urantia Papers. Everything here is MIT-licensed (code) and CC0 (content) — use it however you want.

## What We Build

**[urantiahub.com](https://urantiahub.com)** — Reading platform with bookmarks, notes, AI chat, reading progress, and daily quotes.

**[urantia.dev](https://urantia.dev)** — Developer API with full-text search, semantic search, entities, audio, and OAuth. TypeScript SDKs on npm.

**[demo.urantia.dev](https://demo.urantia.dev)** — Interactive demo of the API.

## Repositories

### Core Infrastructure

| Repo | Description |
|------|-------------|
| [urantia-dev-api](https://github.com/urantia-hub/urantia-dev-api) | Hono + Drizzle API on Cloudflare Workers |
| [urantia-dev-sdks](https://github.com/urantia-hub/urantia-dev-sdks) | TypeScript SDKs — @urantia/api and @urantia/auth |
| [urantia-dev-mintlify-docs](https://github.com/urantia-hub/urantia-dev-mintlify-docs) | API documentation site |
| [urantia-data-sources](https://github.com/urantia-hub/urantia-data-sources) | R2 data bucket management (papers, audio, entities, embeddings) |
| [data](https://github.com/urantia-hub/data) | Urantia Papers in structured JSON + MP3 audio |

### Applications

| Repo | Description |
|------|-------------|
| [OpenUrantia.com](https://github.com/urantia-hub/OpenUrantia.com) | UrantiaHub reading platform (Next.js) |
| [urantia-dev-demo](https://github.com/urantia-hub/urantia-dev-demo) | Interactive API demo site |
| [urantia-dev-example-app](https://github.com/urantia-hub/urantia-dev-example-app) | Minimal OAuth example app |
| [urantia-papers-plugin](https://github.com/urantia-hub/urantia-papers-plugin) | MCP plugin for Claude Desktop and Cursor |

### Research & Media

| Repo | Description |
|------|-------------|
| [urantia-render](https://github.com/urantia-hub/urantia-render) | Rust video renderer for YouTube narrations |
| [urantia-860x-experiment](https://github.com/urantia-hub/urantia-860x-experiment) | Physics verification of the 860x wavelength ratio claim |

## Licensing

| What | License |
|------|---------|
| All source code | [MIT](https://opensource.org/licenses/MIT) |
| All content (text, audio, embeddings, translations, AI content) | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) |
| The Urantia Book English text | Public domain (since 2006) |

## Preservation

The English text is permanently archived across multiple platforms:

- **Arweave** — immutable blockchain storage ([JSON](https://arweave.net/3RLvenzfBZ60GlOygqu6DtlbEhOWldQSqjGuMSVOg9I) · [TXT](https://arweave.net/0YgTs2SJmIkCHxouFPdN-pWFon0ZnhjYQpg7F2DW70o))
- **Internet Archive** — [urantia-papers-english-json-2026](https://archive.org/details/urantia-papers-english-json-2026)
- **GitHub** — this organization (forkable, version-controlled)
- **OpenTimestamps** — Bitcoin-anchored proofs on all LICENSE files

## Contributing

Every repo has a README with setup instructions. Fork it, make changes, open a PR. Questions? [kelson@urantia.dev](mailto:kelson@urantia.dev)

## Disclaimer

This is an independent community project by [Adams Technologies LLC](https://adamstechnologies.com). It is not affiliated with, endorsed by, or connected with Urantia Foundation. The original English text of *The Urantia Book* is in the public domain. All use of "Urantia" is nominative fair use to identify the subject matter.
