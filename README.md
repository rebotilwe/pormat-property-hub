# Pormat Property Hub

Single-page web portal for Pormat Property Group clients to browse listings and send enquiries.

## Structure
- `index.html` — the full site (HTML, CSS, JS all in one file)
- `assets/images/` — drop real property photos here once received
- `assets/docs/` — any supporting property documents/brochures

## Deploying
No build step needed. Options:
1. Netlify — drag the whole folder onto https://app.netlify.com/drop
2. GitHub Pages — push this folder to a repo, enable Pages on the main branch
3. Vercel — `vercel deploy` from inside this folder

## Updating listings
Property data lives near the top of the `<script>` tag in index.html,
in the `properties` array. Edit name, location, price, specs, and description
there, and swap the placeholder skyline graphic for a real `<img>` tag
once photos are available.

## Contact routing
- WhatsApp: 066 090 1485
- Email: Dolly@pormat.co.za
