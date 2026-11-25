# test — public humor clip preview

Lightweight static preview of JA humor clips (~3.2s each) from private humor stock (`githito.xapi` `api` → `v1/stock-humor-ja.json`), about **10** clips from posts within the last 6 hours (Asia/Tokyo), including 2–3 おはよう系 when available.

## Pages

**https://githitosh.github.io/test/**

## Contents

| Path | What |
| --- | --- |
| `index.html` | Video + ⬇️ MP4 download (button) + **plain-text** status URL with **Copy** (no `<a href>` on the page) |
| `clips/*.mp4` | Single-clip Phone MP4s (URL burned on frames) |
| `clips/manifest.json` | Clip metadata (id, handle, status URL, ages) |
| `.nojekyll` | Allow Pages to serve as-is |

No player stack, no tokens, no private stock JSON. Copy uses a **clean** `https://x.com/.../status/...` string (openable). X may still show a link card when that text is pasted into a post — that is X’s behavior. We do **not** ZWSP-break URLs (that would block click-through).
