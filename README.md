# Little Tommy's Big Universe — card links

This repo is a GitHub Pages redirect hub for Little Tommy's Big Universe promo cards. Opening a card link records one scan, then sends the reader straight to Tommy's Book 5 on Amazon:

https://www.amazon.com/dp/B0HNDVYKM7

GitHub Pages has no built-in analytics. Each page fires a [hitscounter.dev](https://hitscounter.dev/) pixel (`label=LTBU`) for its own public address, waits until that pixel loads or fails (or about 400ms), then redirects. There is no stats page in this repo: loading a hits badge increments the count.

## Public URLs

These work once GitHub Pages is live from the `main` branch at the site root:

- https://mandmbchillin-tech.github.io/go/ — default fallback, counted as home
- https://mandmbchillin-tech.github.io/go/kq/ — cards handed out at KQ Ranch
- https://mandmbchillin-tech.github.io/go/card/ — general business cards
- https://mandmbchillin-tech.github.io/go/halloween/ — Halloween and other seasonal cards

## Adding a campaign

A new card campaign is added as a new path. Create a folder with its own `index.html` (so the trailing-slash URL works), point the tracking pixel at that page's public URL, and redirect to the same Amazon page.
