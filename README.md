# Snake Guide World

A no-build, static educational snake guide. Open `index.html` for the curated starter directory, or `catalog.html` to load up to 2,000 snake species taxonomy records from the public iNaturalist API. Both pages use no paid API. The catalog searches Wikimedia Commons for CC-licensed or public-domain photos and displays attribution links when a suitable match is available.

## Run locally

Open `index.html` or `catalog.html` in a modern browser. For browser security and cross-origin requests, use a local static server or GitHub Pages to test the external APIs. GitHub Pages can host the site for free.

## Main site features

- Responsive Snake Guide World landing page and curated starter directory.
- Search, region and broad venom-category filters, saved entries, light/dark theme.
- Country/region emergency-number selector.
- Free Wikimedia Commons photo lookup with visible source/license attribution where available.
- Separate `catalog.html` page that can load up to 2,000 snake taxonomy records from iNaturalist in batches, with search and lazy photo lookup.

## Data, safety, and limitations

This is educational content, not a medical resource or a definitive identification tool. Never use photos or this guide to decide whether a snake is safe. The large catalog only presents taxonomy names and optional common names; venom status and geographic ranges are deliberately not inferred. Taxonomy can change and records may vary between authorities. For suspected bites, contact local emergency services and seek urgent medical care.

Emergency-number coverage is limited. Numbers and availability can vary by locality, telecom network, and country. Confirm the correct number with official local sources, especially before travelling. Before publishing or selling, ask a qualified herpetologist to review curated species content and check emergency numbers against current official sources.

## Free data and photo sources

- [iNaturalist public API](https://api.inaturalist.org/v1/docs/) — taxonomy records.
- [Wikimedia Commons API](https://www.mediawiki.org/wiki/API:Search) — images; the catalog filters photo results to CC BY, CC BY-SA, CC0, or public domain and links to the Commons file page for attribution and full terms. Image availability is not guaranteed for every species.

No commercial value or sale price is guaranteed.
