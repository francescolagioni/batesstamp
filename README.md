# BatesStamp — website

The product website for BatesStamp, a macOS app that applies Bates numbering to
batches of PDFs. Published with GitHub Pages, served from the root of `main`.

Plain HTML and one hand-written stylesheet. No framework, no build step, no
external font, no remote asset of any kind: the site makes the same promise the
app does — it loads nothing from anywhere else.

## Editing

Do not edit these files here. They are copied from `site/` in the application
repository, which is where the site is written and reviewed. Publishing runs:

```sh
./publish-site.sh
```

from that repository, which copies `site/` over this working copy, commits and
pushes. Anything edited here directly is overwritten on the next publish.

## Files

| | |
|---|---|
| `index.html` | product page |
| `support.html` | contact address and FAQ |
| `privacy.html` | privacy policy |
| `style.css` | the whole stylesheet |
| `images/` | the four screenshots, 1440 px wide |
| `.nojekyll` | serve the files as they are, without running Jekyll |
