# Visit the Karoo — visitor-first self-drive holiday planner

The homepage invites visitors to create a personal road trip. `planner.html` is the primary feature, powered by `assets/planner.js` and `assets/site.css`.

## What works today

- Start from Cape Town, George, Gqeberha, Johannesburg, Graaff-Reinet or Aberdeen.
- Generate a suggested 3-, 4-, 5-, 6-, 7- or 10-day itinerary based on interest (scenery, heritage, farm stays, astronomy and food).
- Open and edit any destination, stopover, experience or personal note.
- Add/remove/reorder days, and enter a departure date to see dated itineraries.
- Save itinerary privately to browser localStorage, with automatic saving after editing. Copies persist across reloads in the same browser (not synced across devices).
- Copy to clipboard, share a text summary to WhatsApp or print to PDF using the browser print function.
- Open individual driving legs in Google Maps; for up to seven days, open a full suggested route.
- Start from existing curated tour cards through `planner.html?route=...`.
- Discover available accommodation operators and activities where verified links exist; unverified placeholders are not shown as bookings.

## Scope and limits

This is a **static, front-end-only** visitor preview. No user accounts, server-side saved plans, email booking confirmations, AI-generated itineraries, payment processing, booking integrations, automatic distance calculation, live road status or live accommodation availability are implemented. Sample stops are curated examples, **not assured or optimised driving routes**; users must check road conditions, times, seasonal closures and safety in Google Maps and with operators.

The coloured Karoo regions remain schematic and must not be treated as official tourism or administrative boundaries. Website remains `noindex,nofollow` until real content, ownership/permission, canonical URL, sitemap and SEO strategy are approved.

## Deployment

Static HTML/CSS/JS deployed from GitHub repository `andrevercuiel/visitthekaroo` through Vercel. Vercel project should use Framework Preset **Other**, root `./`, no build command. Domain `visitthekaroo.co.za` must be connected and DNS verified separately.