# DIY Digital Garage — Launch Guide

## What is included
- Responsive single-page storefront with search, filters, featured catalog, FAQ, and a live Gumroad product link.
- Five draft product slots labeled Coming soon (not purchasable until you add checkout links).
- No hosting backend, account logins, customer data collection, or recurring charges in the website code.

## Publish for free
1. Create a free GitHub account if needed.
2. Create a public repository named `diy-digital-garage`.
3. Upload `index.html` at the repository root.
4. In repository Settings > Pages, select Deploy from a branch, `main`, root `/`, and Save.
5. Wait for GitHub to provide the public site URL. Test the store and Gumroad checkout link.

## Add products
Open `index.html` and locate `const products=[`. For each product, set its real price and add `url:'https://...'` with the actual public Gumroad product URL after uploading and testing the product file. Never publish a buy link until the file is available.

## Automated workflow
- Product creation: use AI to draft templates, then manually validate formulas, content and usability.
- Fulfillment: upload each product to Gumroad; Gumroad handles checkout and digital delivery.
- Traffic: create batches of Pinterest pins and schedule them using Pinterest's available scheduling tools or an approved scheduler. Use unique descriptions and avoid spam.
- Monitoring: review Gumroad orders, broken links, customer issues and traffic once a week.
- Optional advanced automation: use an approved workflow tool (such as Make or Zapier) to route new product drafts to a review queue. Do not auto-publish unreviewed files or claims.

## Suggested 30-day rollout
Week 1: publish site, test existing checkout, prepare boat tracker and checklist.
Week 2: release 2-3 validated products and publish matching pins.
Week 3: release business and home templates; create product bundles.
Week 4: check visits, clicks and purchases; improve the highest-performing pages.

## Important
This is a ready-to-publish website, not a deployed live website. Hosting, Gumroad account changes, payment connections, scheduled posts, and automated product generation are NOT configured by this package. No income is guaranteed. Check current provider fees and policies before launch.
