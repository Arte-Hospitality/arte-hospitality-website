# Arte Hospitality website

Initial responsive portfolio implementation for Arte Hospitality on Ocean Drive, Miami Beach.

## Preview locally
Open `index.html` in a browser. The current implementation is a static single-page application using hash routes, so no build step is required.

## Pages
Home, About, Entities, 8 property detail pages, Owners, Events and Contact.

## Before production
- Replace editorial placeholder photography with licensed property images and provide accurate alt text.
- Replace placeholder owner portraits and biographies.
- Add verified booking URLs in the `bookingUrls` map in `index.html`; until then buttons link to contact rather than pretending reservations are active.
- Connect Events and Contact to a secure server endpoint, database, spam protection and transactional email. Current forms use mailto and do not save submissions.
- Add official logos, licensed fonts, accurate property addresses, hours, phone numbers and website URLs.
- Add production SEO metadata and schema.org per route.
- Test mobile browsers, accessibility and cross-browser behavior before publishing.

## Hosting
Can be hosted as a static site on GitHub Pages, Vercel or Netlify. A custom domain and deployment are not yet configured.

This is an initial implementation, not a verified production launch.