# Sunblock Sites

Live client marketing sites published by the Sunblock Studio sales team, via the internal
Website Maker tool (see the private `sunblock-internal` repo).

## Structure

```
<salesperson-slug>/<business-slug>/index.html
```

Each folder is one published client site, served by GitHub Pages at:

```
https://davidmelnik-alt.github.io/sunblock-sites/<salesperson-slug>/<business-slug>/
```

`manifest.json` at the repo root is a machine-readable index of every published site
(business name, salesperson, URL, publish date) — the internal tool's "Published Sites"
tab reads this file to show the team what's live.
