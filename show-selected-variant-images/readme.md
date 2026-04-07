# Show Selected Variant Images

Display only the images for the selected variant on your Shopify product page, improving user experience by filtering out irrelevant product photos.

## Overview

By default, Shopify product pages show all images for a product regardless of which variant is selected. This guide shows you how to filter the product image gallery so that only the images tagged or associated with the currently selected variant are shown — reducing visual clutter and helping customers focus on exactly what they are about to purchase.

## Features

- Dynamically filter product images by selected variant
- Hides images from non-selected variants
- Improves product page UX and reduces confusion
- Compatible with Shopify Dawn and similar themes
- No paid app required — implemented with Liquid and JavaScript
- Works for color, size, style, and other variant types
- Smooth image gallery update on variant selection

## Video Tutorial

[![Show Selected Variant Images in Shopify](https://i.ytimg.com/vi/ZlGgxhrwRQE/maxresdefault.jpg)](https://youtu.be/ZlGgxhrwRQE?list=PLvT_6E7D1NZIlHa09cgswsjD9QunUpHKy)
> Click the image above to watch the full step-by-step tutorial.

## Getting Started

1. In your Shopify admin, navigate to **Online Store → Themes → Edit Code**
2. Locate your product template Liquid file (e.g., `product.json` or `main-product.liquid`)
3. Add the provided Liquid and JavaScript snippet to filter images by selected variant
4. Ensure your product images are named or tagged consistently with your variant options
5. Save the file and verify the behavior on your product pages

> **Tip:** Always duplicate your theme before making code changes.

## Customization

- **Variant option:** Configure which variant option (e.g., Color) is used to filter images
- **Fallback behavior:** Define what to show if no variant-specific images are found
- **Transition animation:** Add a fade or slide animation when images update
- **Thumbnail sync:** Ensure thumbnail navigation also updates to match the selected variant

## Resources

- [Shopify Theme Development Docs](https://shopify.dev/docs/themes)
- [Liquid Template Language Reference](https://shopify.dev/docs/api/liquid)
- [Shopify Product Variants Documentation](https://shopify.dev/docs/api/liquid/objects/product#product-variants)

---
*Part of the [Free Shopify Sections](https://github.com/websensepro1/free-shopify-sections) collection.*