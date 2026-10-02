# Storm Window

A pixel-art desk by a rainy city window. The monitor on the desk mixes rain,
wind and thunder, plays YouTube, or switches off.

## Run it

    python3 -m http.server 8000

then open http://localhost:8000. YouTube only plays when the page is served
this way; opening the file directly still gives you the weather.

## Releases

`index.html` is the working copy. Every release is also kept as a plain file
in `releases/`, so no git is needed to open an old one, for example
http://localhost:8000/releases/v1.html.

| Release | File | What it added |
|---|---|---|
| v1 | `releases/v1.html` | The scene, weather controls and synthesised sound |
| v2 | `releases/v2.html` | Video and power keys on the monitor, five video presets |

To cut a release: copy `index.html` to `releases/vN.html`, add a row above,
commit, and tag the commit `vN`.
