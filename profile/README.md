## Packages

The [7-docs][1] monorepo contains two packages: [@7-docs/cli][2] and [@7-docs/edge][3]

Use [@7-docs/cli][2] to ingest content into a vector database.

Use the [@7-docs/edge][3] package to query your content from anywhere JavaScript runs.

- Node.js: [@7-docs/edge][4]
- Deno: [https://esm.sh/@7-docs/edge][5]

## Starterkits

- [Template with Next.js and Supabase][6]
- [Template for Deno with Aleph.js and Pinecone][7]

## Demo

Multiple demos using different content using `@7-docs/edge` running on various edge function providers:

| Ingested from           | Location                             | Platform    | Database | Repository               |
| :---------------------- | :----------------------------------- | ----------- | -------- | :----------------------- |
| [Knip][8]               | [knip.deno.dev][9]                   | Deno Deploy | Pinecone | [knip][10]               |
| [release-it][11]        | [release-it.deno.dev][12]            | Deno Deploy | Pinecone | [release-it][13]         |
| [Deno Manual][14]       | [7-docs-aleph-pinecone.deno.dev][15] | Deno Deploy | Pinecone | [deno-aleph-pinecone][7] |
| [reactjs/react.dev][16] | [7d-next.fly.dev][17]                | Fly.io      | Supabase | [demo-next][18]          |
| [reactjs/react.dev][16] | [7d-eta.vercel.app][19]              | Vercel      | Supabase | [demo-next][18]          |

[1]: https://github.com/7-docs/7-docs
[2]: https://github.com/7-docs/7-docs/tree/main/packages/cli
[3]: https://github.com/7-docs/7-docs/tree/main/packages/edge
[4]: https://www.npmjs.com/package/@7-docs/edge
[5]: https://esm.sh/@7-docs/edge
[6]: https://github.com/7-docs/template-next-supabase
[7]: https://github.com/7-docs/template-deno-aleph-pinecone
[8]: https://github.com/webpro/knip
[9]: https://knip.deno.dev
[10]: https://github.com/7-docs/knip
[11]: https://github.com/release-it/release-it
[12]: https://release-it.deno.dev
[13]: https://github.com/7-docs/release-it
[14]: https://github.com/denoland/manual/blob/main/README.md
[15]: https://7-docs-aleph-pinecone.deno.dev
[16]: https://github.com/reactjs/react.dev
[17]: https://7d-next.fly.dev
[18]: https://github.com/7-docs/demo-next
[19]: https://7d-eta.vercel.app
