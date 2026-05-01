# narra-gym.github.io

Source for the Narra Gym landing site, served at <https://narra-gym.github.io/>.

## Stack

Plain static HTML and CSS, no build step. GitHub Pages serves the repo root directly.

## Local preview

Open `index.html` in a browser, or run a tiny local server from the repo root:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Files

| File           | Purpose                                                |
| -------------- | ------------------------------------------------------ |
| `index.html`   | Main landing page                                      |
| `404.html`     | Custom 404, served by GitHub Pages on missing routes   |
| `favicon.svg`  | Site icon                                              |
| `robots.txt`   | Crawler rules, points to the sitemap                   |
| `sitemap.xml`  | One-entry sitemap for the homepage                     |

## Deploy

Pushing to the `main` branch publishes automatically. In repository **Settings → Pages**, the source should be set to `Deploy from a branch`, branch `main`, folder `/ (root)`.
