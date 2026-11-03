# Revelation: The Illuminated Codex

A guide to the Book of Revelation, in English, Spanish and Russian.
Live at <https://andresmessina-sdg.github.io/revelation-explainer/>.

## Updating from the codex

`index.html` comes from the illuminated codex artifact. An artifact can only
load fonts from Google, so after copying a new `index.html` in, run:

```bash
python3 tools/localize-fonts.py
```

It swaps the Google Fonts link for `fonts/fonts.css`, downloading any font the
new page needs into `fonts/`. Readers' browsers then ask no other site for the
fonts. Commit `index.html` and anything new in `fonts/` together.
