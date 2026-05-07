# Trust & Security — example documentation site

A minimal, good-looking [Mintlify](https://mintlify.com) documentation site set
up as an example of a single-purpose docs site. The current content is a Trust
& Security landing page plus a pointer to the canonical Trust Center.

## Local preview

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run from the repo root:

```bash
mint dev
```

Preview at [http://localhost:3000](http://localhost:3000).

## Structure

- `index.mdx` — landing page
- `security.mdx` — Trust Center pointer page
- `docs.json` — site config (theme, navigation, navbar)
- `.github/workflows/notify-intercom-internal-agent.yml` — pull-request hook
  that asks an external content-review agent to scan workspace help-center
  content for material that may need updating in light of a change.

## License

MIT — see `LICENSE`.
