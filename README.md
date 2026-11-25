# test — public humor clip preview

Lightweight static preview of **3** JA humor clips (~3.2s each) taken from current private humor stock (`githito.xapi` `api` / packed `videos`).

## Pages

After GitHub Pages is enabled on `main` (source: Deploy from a branch → `/` root):

**https://githitosh.github.io/test/**

## Contents

| Path | What |
| --- | --- |
| `index.html` | Simple list: video + clickable X status URL |
| `clips/*.mp4` | Three single-clip Phone MP4s (URL burned on frames) |
| `clips/manifest.json` | Clip metadata (id, handle, status URL) |
| `.nojekyll` | Allow Pages to serve as-is |

No player stack, no tokens, no private stock JSON.
