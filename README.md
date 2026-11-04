# andrewrobi.dev

Personal engineering blog of Andrew Robinson. Frontend mechanics, measured.

Built with [Astro](https://astro.build), deployed on Cloudflare Pages.

## Development

Requires [pnpm](https://pnpm.io). Node is pinned per-project via `.npmrc`
(`use-node-version`), so pnpm fetches the right Node automatically. No global
Node install needed.

```bash
pnpm install
pnpm dev       # local dev server
pnpm build     # static build to ./dist
```

Posts are markdown files in `src/content/blog/`. Adding a post is adding a
file.

## Licensing

- **Code** (everything outside `src/content/`): [MIT](./LICENSE)
- **Content** (posts, images, and figures in `src/content/`):
  [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — share and adapt
  with attribution to Andrew Robinson and a link back
- **Code snippets inside posts**: MIT, use them freely
