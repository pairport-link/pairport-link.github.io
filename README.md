# pairport.link

Static build of the PairPort web app, served by GitHub Pages at
<https://pairport.link>.

The source lives in `procks/QuickSynch`. To publish a new build:

1. `npm run build` in the source repo.
2. Copy `dist/index.html` and `dist/assets/*` here.
3. Commit and push.

`CNAME` pins the custom domain, `.nojekyll` keeps Jekyll from dropping
`.well-known/`, and `.well-known/assetlinks.json` is the Android App Links
association file for `link.pairport.app`.
