# Linen

Warm paper tones with ink-brown accents for [Multica](https://multica.ai). This is the sample theme of the [Multica theme store](https://github.com/multica-ai/multica-themes): fork it to start your own.

Install it from **Settings → Appearance → Browse** in Multica, or download `theme.zip` from the latest release and import it.

## Make your own from this

1. Fork this repository and change `id`, `name` and `author` in `manifest.json`.
2. Edit `theme.css`. The variables and `data-mc` anchors a theme can use are listed in [docs/theming.md](https://github.com/multica-ai/multica/blob/main/docs/theming.md).
3. Check it: `pnpm theme:check <this folder>` from a checkout of `multica-ai/multica`.
4. Publish it: bump `version` in `manifest.json`, tag the commit with the same version (`v1.0.0` or `1.0.0`), and push the tag. The release workflow attaches `theme.zip`.
5. List it in the store: open a pull request on [multica-ai/multica-themes](https://github.com/multica-ai/multica-themes).

The theme API is in beta: variables, anchors and the manifest may change.

## License

MIT
