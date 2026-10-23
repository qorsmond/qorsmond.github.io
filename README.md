# quintinorsmond.dev

My personal site: who I am, what I've built, and where to find my writing. The writing itself lives on [Bits to Live By](https://www.bitstoliveby.com/).

Plain HTML and CSS, served by GitHub Pages from `master`. There is no build step: edit a page, push, and it's live.

| Path | What it is |
| --- | --- |
| `index.html` | Home: introduction, current work on Bits to Live By, where the years went, closing |
| `projects/index.html` | Still building (FeatureKit; Baseline, Tokens, Layouts, Behaviors) and earlier work (Framealot, Farm-IT) |
| `contact/index.html` | Contact |
| `404.html` | Not found (GitHub Pages serves it for any missing path) |
| `assets/site.css` | All the styles; colours are tokens at the top |
| `assets/images`, `assets/logos`, `assets/fonts` | Photos and screenshots, the Farm-IT logo, self-hosted Roboto |
| `sitemap.xml`, `robots.txt` | For search engines; update `lastmod` when a page changes |

The header and footer are repeated in each page, so a change to either goes in all four.

To preview locally:

```bash
python3 -m http.server 8765
```

Until October 2026 the site was a Gatsby 2 build whose source had been lost, so only the compiled output was in this repository. It was rebuilt as static pages with the same design; the old build is in the git history.
