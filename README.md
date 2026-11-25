# test — public humor 3-pack preview

Static preview of **10** JA humor packs. Each pack is **3 consecutive コマ** (3×3.2s ≈ 9.6s MP4) drawn from the 50 lowest-follower registered+filter-pass humor accounts (stock in `githito.xapi` `api` → `v1/stock-humor-ja.json`).

## Pages

**https://githitosh.github.io/test/**

## Contents

| Path | What |
| --- | --- |
| `index.html` | Video + ⬇️ MP4 download (button) + **plain-text** status URLs with **Copy** (no `<a href>` on the page) |
| `clips/pack-NN-*.mp4` | 3-clip concatenated Phone MP4s (URL burned on frames) |
| `clips/manifest.json` | Pack metadata (handles, status URLs, source order) |
| `.nojekyll` | Allow Pages to serve as-is |

No player stack, no tokens, no private stock JSON. Copy uses a **clean** `https://x.com/.../status/...` string (openable). X may still show a link card when that text is pasted into a post — that is X’s behavior. We do **not** ZWSP-break URLs (that would block click-through).
