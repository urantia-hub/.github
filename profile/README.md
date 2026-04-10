## UrantiaHub

Open-source tools and infrastructure for the Urantia Papers. Everything is MIT-licensed (code) and CC0 (content).

**[urantiahub.com](https://urantiahub.com)** — Read the papers with bookmarks, notes, AI chat, and reading progress tracking.

**[urantia.dev](https://urantia.dev)** — Developer API with full-text search, semantic search, 4,400+ entities, audio narrations, and TypeScript SDKs.

**[demo.urantia.dev](https://demo.urantia.dev)** — Try the API interactively.

### Get Started

```bash
npm install @urantia/api
```

```typescript
import { UrantiaAPI } from '@urantia/api'

const api = new UrantiaAPI()
const { data: results } = await api.search({ query: 'love and service' })
```

### Preservation

The English text is permanently archived on [Arweave](https://arweave.net/3RLvenzfBZ60GlOygqu6DtlbEhOWldQSqjGuMSVOg9I), the [Internet Archive](https://archive.org/details/urantia-papers-english-json-2026), and across this organization's public repos — with Bitcoin-anchored OpenTimestamps proofs on all licenses.

### Links

[API Docs](https://urantia.dev) · [Interactive Demo](https://demo.urantia.dev) · [Read the Papers](https://urantiahub.com) · [MCP Plugin](https://github.com/urantia-hub/urantia-papers-plugin) · [Donate](https://urantia.dev/support)
