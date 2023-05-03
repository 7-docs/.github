Build awesome "chat with your content" applications and integrations.

This GitHub organization houses a collection of TypeScript packages, starter kits and demos.

## Using OpenAI with JavaScript

Read the article about [Using OpenAI with JavaScript][1] for a longer introduction and more details.

## Packages

The [7-docs][2] monorepo contains two packages: [@7-docs/cli][3] and [@7-docs/edge][4]

Use [@7-docs/cli][3] to ingest content into a vector database.

Use the [@7-docs/edge][4] package to query your content from anywhere JavaScript runs.

- Node.js: [@7-docs/edge][5]
- Deno: [https://esm.sh/@7-docs/edge][6]

## Starter Kits

- [Template with Next.js and Supabase][7]
- [Template for Deno with Aleph.js and Pinecone][8]

## Demo

Multiple demos using different content using `@7-docs/edge` running on various edge function providers:

| Ingested from           | Location                             | Platform    | Database | Repository               |
| :---------------------- | :----------------------------------- | ----------- | -------- | :----------------------- |
| [Knip][9]               | [knip.deno.dev][10]                  | Deno Deploy | Pinecone | [knip][11]               |
| [release-it][12]        | [release-it.deno.dev][13]            | Deno Deploy | Pinecone | [release-it][14]         |
| [Deno Manual][15]       | [7-docs-aleph-pinecone.deno.dev][16] | Deno Deploy | Pinecone | [deno-aleph-pinecone][8] |
| [reactjs/react.dev][17] | [7d-next.fly.dev][18]                | Fly.io      | Supabase | [demo-next][19]          |
| [reactjs/react.dev][17] | [7d-eta.vercel.app][20]              | Vercel      | Supabase | [demo-next][19]          |

[1]: https://www.webpro.nl/articles/using-openai-with-javascript
[2]: https://github.com/7-docs/7-docs
[3]: https://github.com/7-docs/7-docs/tree/main/packages/cli
[4]: https://github.com/7-docs/7-docs/tree/main/packages/edge
[5]: https://www.npmjs.com/package/@7-docs/edge
[6]: https://esm.sh/@7-docs/edge
[7]: https://github.com/7-docs/template-next-supabase
[8]: https://github.com/7-docs/template-deno-aleph-pinecone
[9]: https://github.com/webpro/knip
[10]: https://knip.deno.dev
[11]: https://github.com/7-docs/knip
[12]: https://github.com/release-it/release-it
[13]: https://release-it.deno.dev
[14]: https://github.com/7-docs/release-it
[15]: https://github.com/denoland/manual/blob/main/README.md
[16]: https://7-docs-aleph-pinecone.deno.dev
[17]: https://github.com/reactjs/react.dev
[18]: https://7d-next.fly.dev
[19]: https://github.com/7-docs/demo-next
[20]: https://7d-eta.vercel.app
