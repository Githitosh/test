# test — public humor clip preview

Lightweight static preview of JA humor clips (~3.2s each) from private humor stock (`githito.xapi` `api` → `v1/stock-humor-ja.json`), limited to posts within the last 6 hours (Asia/Tokyo).

## Pages

**https://githitosh.github.io/test/**

## Contents

| Path | What |
| --- | --- |
| `index.html` | Video + ⬇️ MP4 download + **plain-text** status URL with **Copy** (not a hyperlink) |
| `clips/*.mp4` | Single-clip Phone MP4s (URL burned on frames) |
| `clips/manifest.json` | Clip metadata (id, handle, status URL, ages) |
| `.nojekyll` | Allow Pages to serve as-is |

No player stack, no tokens, no private stock JSON. Paste the copied URL into X as text so link-card image fetch does not run from this page.
