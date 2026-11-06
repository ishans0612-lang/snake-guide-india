# Snake Guide World

A no-build, static educational snake guide. Open `index.html` for the curated starter directory, `catalog.html` to request up to 2,000 taxonomy records from the public iNaturalist API, or `identify.html` to submit a photo to iNaturalist computer vision for non-definitive visual suggestions. No paid API is required, but the catalog and photo suggestions need an internet connection and rely on third-party public services.

## Run locally

Open the site through GitHub Pages or a local static server. Camera access typically needs a secure context (HTTPS/localhost); `identify.html` also accepts an existing image file.

## Features

- Responsive Snake Guide World landing page and curated starter directory.
- Search, region and broad venom-category filters, saved entries, and a light/dark theme.
- Country/region emergency-number selector.
- Free Wikimedia Commons photo lookup with visible source/license attribution where available.
- `catalog.html` requests up to 2,000 snake taxonomy records from iNaturalist in batches and offers search and lazy photo lookup.
- `identify.html` lets a user take/select a photo and ask iNaturalist computer vision for up to eight possible look-alikes.

## Safety, privacy, and limitations

This is educational content, not a medical resource or a definitive identification tool. Never use photos or this guide to decide whether a snake is safe. Automated suggestions may be incorrect; their match score is not a probability, and this feature does not determine venom status. Never approach, handle, trap, or provoke wildlife to take a picture. For suspected bites, move away, contact local emergency services, and seek urgent medical care.

On the photo-suggestion page, the selected image is sent to the public iNaturalist computer-vision endpoint. Do not upload sensitive images. This site does not store the selected image. Third-party service availability, usage policies, and rate limits may change.

The large catalog presents taxonomy names and optional common names; venom status and geographic ranges are deliberately not inferred. Taxonomy changes over time. Emergency-number coverage is limited; verify the correct number with current official local sources. Before publishing or selling, get expert review of the curated species information, image attribution, and safety content.

## Data and image sources

- [iNaturalist public API](https://api.inaturalist.org/v1/docs/) — taxonomy and computer-vision suggestions.
- [Wikimedia Commons API](https://www.mediawiki.org/wiki/API:Search) — images; photo pages link to source and license information. Image availability is not guaranteed for every species.

No commercial value or sale price is guaranteed.
