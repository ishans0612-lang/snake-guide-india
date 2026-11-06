# Snake Guide World

A no-build, static educational snake guide. Open `index.html` for the dark-green themed guide with snake names and photo lookups, `gallery.html` for a smaller photo gallery, `catalog.html` to request up to 2,000 taxonomy records from iNaturalist, or `identify.html` for experimental photo-based visual suggestions.

## Run locally

Use GitHub Pages or a local static server. External Wikimedia/iNaturalist APIs require an internet connection. Camera access generally requires HTTPS or localhost.

## Features

- Responsive, dark-green Snake Guide World landing page and curated snake directory.
- Search and broad guide-category filter.
- Real images are looked up dynamically on Wikimedia Commons using scientific names. They are **not stored in this repository**; every available image links to its file page and displays contributor/license information where available. Image matches can be absent or mislabeled.
- `gallery.html` is a separate photo gallery using Wikimedia Commons search.
- `catalog.html` requests up to 2,000 snake taxonomy records from iNaturalist in batches.
- `identify.html` is an experimental photo suggestion page that sends selected images to iNaturalist computer vision. Suggestions are not definitive identification.
- First-aid information for suspected snakebite is provided on the home page; emergency phone numbers have been removed.

## Safety, privacy, and limitations

This educational guide is not a medical resource or a definitive identification tool. Never use photos or automated suggestions to decide whether a snake is safe or venomous. Never approach, handle, trap, or provoke wildlife to take a picture. For a suspected bite, move away from the snake and seek urgent medical care through local services; do not delay treatment. Follow local medical professionals' advice, as protocols can vary by region.

The photo-suggestion page sends the selected image to the public iNaturalist computer-vision endpoint. Do not upload sensitive images. This site does not store the image. External service availability, API policies, and rate limits may change.

Species names, guide notes, and broad venom labels need expert review before public/commercial use. Do not rely on the emergency or range details as verified facts. Photos are served by Wikimedia Commons and each has its own license; follow its attribution and reuse terms. There may be no suitable photo for a given species.

## Third-party data and images

- [iNaturalist public API](https://api.inaturalist.org/v1/docs/) — taxonomy and experimental computer-vision suggestions.
- [Wikimedia Commons API](https://www.mediawiki.org/wiki/API:Search) — images and per-image file/license pages.

No commercial value or sale price is guaranteed.
