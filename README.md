# Aristra Docs

The documentation for Aristra: Aristra Code, Aristra Desktop, the Aristra CLI and Aristra One, published with [Mintlify](https://mintlify.com).

- `docs.json` is the site's configuration and navigation.
- Each page is an `.mdx` file. Its path without the extension is its URL and its entry in `docs.json`.
- What is merged to `main` is published.

Preview locally with Mintlify's CLI:

```sh
npm i -g mint
mint dev            # http://localhost:3000
mint broken-links   # check internal links
```

`AGENTS.md` has the naming and style the pages follow.
