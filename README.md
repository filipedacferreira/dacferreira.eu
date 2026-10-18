# dacferreira.eu

My personal site. One hand-written HTML page, no frameworks, no build step.

## Run locally

```sh
npx serve public
```

Opening `public/index.html` directly also works. `404.html` needs a server, since it loads assets from the site root.

## Deploy

Hosted on Cloudflare Pages.

```sh
npx wrangler pages deploy
```

## Files

Everything in `public/` is published:

- `index.html`: the site
- `404.html`: not-found page
- `fonts/`: self-hosted Instrument Sans (OFL)
- `og.png`: link preview image, rendered from `_og/og.html`
- `favicon.svg`, `apple-touch-icon.png`, `robots.txt`, `sitemap.xml`

`_og/og.html` is the source for the preview image and isn't published.

## Credits

- Colours: [Catppuccin](https://catppuccin.com) Latte and Mocha
- Icons: [Lucide](https://lucide.dev)
- Circuit outline: [bacinger/f1-circuits](https://github.com/bacinger/f1-circuits) (MIT)
- Analytics: [Umami](https://umami.is)
