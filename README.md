# Revelation: The Illuminated Codex

A guide to the Book of Revelation, in English, Spanish and Russian.
Live at <https://andresmessina-sdg.github.io/revelation-explainer/>.

## Updating from the codex

`index.html` comes from the illuminated codex artifact. An artifact loads its
fonts from Google and its artwork from Wikimedia Commons, so after copying a
new `index.html` in, run:

```bash
python3 tools/localize.py
```

It swaps the Google Fonts link for `fonts/fonts.css` and points every image at
a copy in `images/`, downloading anything new. `images/SOURCES.md` records
where each image came from. Readers' browsers then load the page entirely from
this site; only a video, when a reader presses play, comes from YouTube.
Commit `index.html` with anything new in `fonts/` and `images/`.
