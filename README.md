# Aristra Docs

The documentation for Aristra on every surface (the web, Aristra Desktop, Aristra Code and the Aristra CLI) and for Aristra One, your account's plan, published with [Mintlify](https://mintlify.com).

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

## License

The text of these docs is licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0): you may share and adapt it, with credit. See `LICENSE.md`.
