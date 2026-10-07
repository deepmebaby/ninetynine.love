# ninetynine.love

Static landing page for ninetynine. GitHub Pages serves it as is. There is no build step.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The page. All CSS and JS are inline. |
| `llms.txt` | Plain-text summary of the product for AI agents. |
| `CNAME` | Custom domain for GitHub Pages. |
| `.nojekyll` | Stops the Jekyll build on GitHub Pages. |
| `assets/` | Logo, favicon, touch icon, social preview image. |

## Deploy

1. Push this directory to the root of a GitHub repository, for example `deepmebaby/ninetynine.love`.
2. In the repository, open Settings > Pages. Set the source to "Deploy from a branch", branch `main`, folder `/ (root)`.
3. At the DNS provider of `ninetynine.love`, add 4 `A` records for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
4. Add a `CNAME` record for `www` with the value `<github-user-or-org>.github.io`.
5. When the certificate is ready, select "Enforce HTTPS" in Settings > Pages.

## Preview

Open `index.html` in a browser. There is no server to start.
