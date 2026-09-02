# Music Radio

Tune into real, live music radio streams from around the world — no talk, no news, just music. Runs entirely in your browser.

**Live:** <https://music-radio.slippylabs.com/>

## What it does

- Real, live music streams from around the world — no talk, no news.
- Stations including FIP, KEXP, SomaFM, Radio Paradise, WWOZ, WFMU and NRK.
- Grouped by genre, with a persistent now-playing panel that survives browsing the list.

## Run it locally

A static site. No build step, no package manager, no dependencies:

```
git clone git@github.com:slippylabs/music-radio.slippylabs.com.git
cd music-radio.slippylabs.com
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Notes

The player is client-side, but **the streams are not mine** — they are the public broadcast feeds of the stations listed, played directly from their own servers. Nothing is proxied, cached or rehosted here. A station that goes down, geoblocks, or changes its stream URL will stop working until the URL is updated.

---

Part of [Slippy Labs](https://slippylabs.com). Every tool is indexed at
[projects.slippylabs.com](https://projects.slippylabs.com).
