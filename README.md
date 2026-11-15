# soot.css

soot.css is a classless CSS stylesheet. Its goal is to be lightweight, opinionated, and flexible. It's meant to be a drop-in stylesheet for small and medium-sized websites.

For a quickstart and examples, check out the docs: [soot.spoons.fyi](https://soot.spoons.fyi)

## Publish

Install `csso` dev dependency:

```sh
npm i
```

Publish

```sh
npm publish --access public
```

## Docs site

The docs site is static files in `docs/`, served by Cloudflare Workers (static assets). To run it locally:

```sh
npx wrangler dev
```

Deploys run on Cloudflare Workers Builds through the Cloudflare GitHub app: every push to `main` deploys to production. No secrets are stored in this repository.
