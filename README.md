# marketplace-product-assets

Stable public marketplace product assets.

Do not rename or replace an existing hashed asset; publish changed assets under a
new hash-derived path.

Each file is named `main-<first 12 hex of its own sha256>.png`. Marketplaces cache
by URL: an edited image served from the same address keeps showing the old
picture, so a changed asset must arrive at a new address instead.

Images are the manufacturers' own product assets (Pioneer DJ, AlphaTheta),
published here so marketplace listings can reference a stable HTTPS URL.
