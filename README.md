# openfruit-site

The website of [OpenFruit](https://github.com/ssilvestri15/openfruit) and
[OpenFruit Studio](https://github.com/ssilvestri15/openfruit-studio), served by
GitHub Pages from the `main` branch.

A single static `index.html` (fonts: Syne and Syne Mono from Google Fonts) plus
the brand assets in `assets/`. The download buttons look up the newest release
of each repository through the GitHub API, prereleases included, and fall back
to the Releases page.

Preview locally:

```bash
python -m http.server 8765
```
