# Miguel Castro | Private Practice

Static single-page site for `private.miguelcastro.works`.

## Files

```text
index.html
README.md
```

The site is self-contained. CSS and JavaScript are included inside `index.html`.

## Deploy

Upload `index.html` to the root of the hosting target.

Recommended options:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Any static host

No build step is required.

## Domain

Production URL:

```text
https://private.miguelcastro.works/
```

Point the subdomain to the chosen static host using that provider’s DNS instructions.

## Content

The page includes:

- private practice landing section
- signal/about proof statement
- selected proof section
- Vimeo embeds for four case videos
- local theater mode for case videos
- Miguel’s Language Model as the fifth proof item
- Bring Me In section
- compact footer

## Links to verify before launch

- Contact: `mailto:miguel@miguelcastro.cc`
- LinkedIn: `https://www.linkedin.com/in/miguelcastroe/`
- Portfolio: `https://miguelcastro.works/`
- About: `/about`
- MLM: `https://private.miguelcastro.works/`

## Vimeo notes

The proof videos are embedded through Vimeo player URLs. If a video does not render on the live domain, check Vimeo privacy settings and make sure `private.miguelcastro.works` is allowed as an embed domain.

## Launch checklist

- Test desktop, tablet and mobile.
- Confirm Vimeo videos render on the live domain.
- Open and close theater mode.
- Test Escape key on desktop.
- Check footer links.
- Confirm `/about` behavior before announcing the site.
- Add an OG image later if needed.

## Editing

Most content lives in the `cases` array inside the `<script>` block:

```js
const cases = [...]
```

Typography, grid and responsive behavior live in the `<style>` block.
