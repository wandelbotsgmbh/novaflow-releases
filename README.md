# novaflow-releases

Public feed of the newest stable NovaFlow version, served by GitHub Pages:

https://wandelbotsgmbh.github.io/novaflow-releases/latest.json

```json
{ "version": "2026.10.52", "released_at": "…", "release_url": "…" }
```

Written by the `publish-latest-version` job of NovaFlow's `promote.yml`
for every stable release marked latest (deploy key secret
`NOVAFLOW_RELEASES_DEPLOY_KEY`). The NovaFlow installer reads it to recommend
that version, and falls back to the version baked into its image when the
file is out of reach. Do not edit by hand.
