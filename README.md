# SmartLitter storefront starter

A custom Next.js storefront concept for SmartLitter, using the supplied logo and taking broad e-commerce inspiration from PetPivot's product-led structure.

## Included
- Responsive homepage for desktop and mobile
- Supplied SmartLitter SVG logo
- Shop section with starter product cards
- Interactive cart drawer and quantity controls
- USD/GBP display toggle (GBP is an approximate visual conversion, not live FX)
- FAQ and newsletter UI

## Important: prototype, not live checkout
Product names, prices, discounts and illustrations are placeholders. Replace them with verified products, accurate specifications and supplier-approved product photography. The newsletter form does not store addresses. Checkout is intentionally not connected to a payment provider. Do not accept orders until a commerce backend, payment processing, shipping/returns policies and real product information are configured. Do not publish fake reviews or unverified product/safety claims.

## Easiest launch path for a non-coder
1. Create a GitHub account: https://github.com/signup
2. Create a repository named `smartlitter-store` and upload the project files.
3. Create a Vercel account: https://vercel.com/signup and import that GitHub repository.
4. Vercel detects Next.js and deploys the prototype.
5. Connect Shopify (recommended for a beginner) or another supported commerce backend for real products, orders and checkout. Payment eligibility depends on the country where the business is registered.

## Run locally
Requires Node.js 20 or later:

```bash
npm install
npm run dev
```
Then open http://localhost:3000.
