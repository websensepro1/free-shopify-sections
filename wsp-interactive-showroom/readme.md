# WSP Interactive Showroom Section for Shopify

Turn your collection into a fashion runway. Models stand in a 3D multi-row showroom that you can scroll through and drag sideways. Hover a model to see its name and price, click to open a full look spotlight with piece list, size selection, Add to Bag and Add the Full Look — all without leaving the page.

## Overview

This section displays your products as full-length models standing on a runway. Rows of models sit at different depths — the front row is sharp and clickable, the rows behind are smaller and softly blurred. Scrolling moves you forward through the rows, dragging moves you sideways, and the whole stage slowly drifts on its own. Clicking a model opens a detail overlay where shoppers can see the look, browse its pieces, pick a size and add to cart. Everything is built with Liquid, CSS and plain JavaScript — no paid app required.

## Features

- No paid apps required
- 3D multi-row runway with depth, scale and background blur
- Scroll (mouse wheel / touch) to move through the rows, drag to move sideways
- Optional auto horizontal drift (pauses while the shopper interacts)
- Custom cursor badge on hover showing look name, look number and price (desktop)
- Look spotlight overlay with large model image, description and link to the product page
- Previous / next look navigation with look counter (e.g. `01 / 24`)
- Piece list per look — main product plus up to 3 additional pieces
- Size / variant pills (sold-out variants are disabled) with live price update
- **Add to bag** for the selected piece and **Add the full look** for the whole outfit
- Add to Cart without page reload — refreshes the cart drawer and cart count (Dawn-based themes)
- Product image, title, price, description and variants are pulled automatically from the selected product
- Fully responsive — dedicated stacked layout and smaller models on mobile
- Colour, size, spacing, speed and blur controls in the theme editor

## Getting Started

1. Go to your Shopify Admin → **Online Store** → **Themes**
2. Click **…** → **Edit code** on your active theme
3. In the **Sections** folder, click **Add a new section** and name it `wsp-interactive-showroom`
4. Replace everything in the new file with the code from [`wsp-interactive-showroom.liquid`](wsp-interactive-showroom.liquid) and click **Save**
5. Open **Customize**, click **Add section** and choose **WSP Interactive Showroom**
6. Add a **Fashion Look** block for each look (the section starts with 6 blocks by default)

## Adding Looks

Each **Fashion Look** block has:

| Setting | Description |
|---|---|
| Select Product (Full Outfit / Model) | Main product of the look. Its featured image is shown on the runway and in the overlay; its title, price, description and sizes are fetched automatically |
| Custom Look Name (Optional) | Overrides the product title. Leave empty to use the product's own name |
| Custom Description (Optional) | Overrides the product description. Leave empty to use the product's description (HTML stripped, trimmed to 250 characters) |
| Piece 1 / Piece 2 / Piece 3 (Optional) | Extra products shown in the piece list, e.g. jacket, trousers, shoes |

> **Tip:** Use a full-length model photo with a transparent background (PNG / WebP) as the product's featured image, with the same canvas size for every look, so all models stand at the same height on the runway.

**How images are chosen:** main product's featured image → Piece 1's featured image → built-in placeholder image.

**Add the full look:** if a main product is selected, its first available variant is added to the cart. If no main product is selected, the first available variant of each additional piece is added.

> With more than 3 looks, each row starts from a different look so neighbouring rows look varied. If you have fewer looks than the runway needs, they repeat to fill the stage.

## Section Settings

| Group | What you can change |
|---|---|
| Stage & Model Dimensions | Section height (70–100vh), focal model height (400–650px), horizontal spacing between models (240–420px) |
| Scroll & 3D Depth Controls | Wheel scroll sensitivity (1–8), auto horizontal drift speed (0 to disable, up to 2), background blur strength (2–8px) |
| Colors & Styling | Background, foreground text, muted text, border, drawer panel background |
| Perk / Shipping Note | Small note shown at the bottom of the look panel (e.g. delivery and returns info) |

## Notes

- Loads the **Cormorant Garamond** and **Manrope** fonts from Google Fonts.
- Cart drawer refresh is built for Dawn-based themes (`cart-drawer`, `cart-icon-bubble`). On other themes the item is still added to the cart and the section falls back to clicking the theme's cart icon.
- Best used as a full-width, full-screen section — scrolling over the stage moves through the runway instead of scrolling the page.
- The "Size guide" button is a visual placeholder — connect it to your own size chart popup if needed.

## Resources

- [Shopify Liquid Reference](https://shopify.dev/docs/api/liquid)
- [Shopify Cart AJAX API](https://shopify.dev/docs/api/ajax/reference/cart)
- [Section Schema Docs](https://shopify.dev/docs/storefronts/themes/architecture/sections/section-schema)

---

*Part of the [Free Shopify Sections](https://github.com/websensepro1/free-shopify-sections) collection.*
