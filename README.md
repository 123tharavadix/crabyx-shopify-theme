# CRABYX Shopify Theme

A responsive, editable Shopify Online Store 2.0 theme for CRABYX. The theme uses Shopify Liquid, Shopify products, collections, customer accounts, cart APIs and native checkout.

## Features

- Responsive desktop, tablet and mobile storefront
- Animated landing/hero experience
- Editable sections through Shopify Theme Editor
- Shopify product and collection data
- Product detail page with variant selector and quantity controls
- AJAX add-to-cart and slide-out cart drawer
- Cart removal without full page reload
- Search navigation
- Customer account/login link when customer accounts are enabled
- Browser-local wishlist
- Desktop mega menu built from Shopify collections
- Mobile menu and bottom navigation
- About, Contact and Report Issue pages
- SEO title, canonical URL and meta description
- Shopify checkout integration
- No separate product database required

## Install

1. Open Shopify Admin.
2. Go to Online Store > Themes.
3. Create a new blank/custom theme or upload a ZIP of this repository after downloading it from GitHub.
4. In the Shopify code editor, ensure the repository files are placed in the standard Shopify theme folders: assets, config, layout, sections, snippets, templates and locales.
5. Go to Customize and configure the CRABYX Theme Settings, hero, featured products, collections and other sections.
6. Create Shopify pages with handles `about`, `contact`, and `report-issue` if they do not already exist.
7. Assign the supplied page templates to those pages.
8. Create collections and add products in Shopify Admin. The theme reads products directly from Shopify.
9. Enable customer accounts in Shopify Settings > Customer accounts if you want the Account navigation item.
10. Preview on desktop and mobile, then publish when ready.

## Shopify integration

Products, variants, prices, inventory and checkout remain in Shopify. The theme uses `/cart.js`, `/cart/add.js`, and `/cart/change.js` for asynchronous cart interactions. Shopify remains the source of truth for commerce and payment processing.

## Wishlist

The initial wishlist implementation uses browser localStorage so it requires no external database or app. For cross-device persistent wishlists, replace it with a Shopify-compatible wishlist app or authenticated customer metafield/app backend.

## Customization

Theme settings include brand name, accent color, background color, text color, animation toggle and mobile bottom navigation toggle. Sections expose their own editable text, links, collections and product counts.

## Recommended production checks

- Add your final logo and brand imagery in Theme Editor.
- Configure shipping, taxes, payments, policies and domains in Shopify Admin.
- Test every product variant and inventory state.
- Test checkout and customer accounts on the live store.
- Add analytics, consent/privacy configuration and marketing integrations as required.
- Test accessibility, performance and SEO before launch.
