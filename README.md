# Roosevelt Shanghai Static Site

This repository contains a pure static HTML site for Roosevelt Shanghai.

## Pages

- English: `/en/`
- Chinese: `/cn/`
- Root: `/` redirects to `/en/`

The language switch is configured as follows:

- English page shows `CN` and links to `../cn/`
- Chinese page shows `EN` and links to `../en/`

## Deploy to Cloudflare Pages

No framework or build step is required.

1. In Cloudflare Pages, connect this GitHub repository.
2. Choose **None** or leave framework preset unset.
3. Set **Build command** to blank.
4. Set **Build output directory** to `/`.
5. Deploy.

Because all internal page, image, CSS, and JavaScript references are relative, the site can be deployed on Cloudflare Pages, GitHub Pages, or a custom domain without changing paths.
