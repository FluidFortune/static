# STATIC

**Lightweight GitHub-native podcast publisher**

A single HTML file that runs in your browser. Add episodes to your GitHub Pages podcast site with one click. Generates episode pages, show index pages, and valid RSS feeds automatically.

Built by [Fluid Fortune](https://fluidfortune.com). MIT License.

## Quick Start

1. Download `static.html` and open in Chrome
2. Configure your GitHub token and podcast repo in the sidebar
3. Fill in episode details, hit PUBLISH
4. STATIC generates the episode page, updates the show index, and regenerates the RSS feed automatically

## What It Generates Per Publish

- `[show]/episodes/[slug].html` — individual episode page with inline audio player
- `[show]/index.html` — show homepage with inline players for all episodes
- `[show]/episodes.json` — episode manifest
- `[show]/feed.xml` — valid RSS/podcast feed (Apple Podcasts, Spotify compatible)

## Audio Hosting

Host your audio at [archive.org](https://archive.org) for free. Paste the direct audio URL into STATIC. No bandwidth costs.

## License

MIT — do what you want with it.
