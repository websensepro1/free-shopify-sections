# Show Sale Discount Percentage

Display the sale discount percentage badge on product cards and product pages in your Shopify store, showing customers exactly how much they are saving.

## Overview

This guide walks you through replacing the default "Sale" badge in your Shopify theme with a dynamic percentage discount badge (e.g., "20% OFF"). It uses Liquid logic to calculate the discount across all product variants and displays the maximum discount — giving customers clear, compelling savings information that drives conversions.

## Features

- Dynamic percentage discount badge on product cards
- Shows maximum discount across all product variants
- Replaces the generic "Sale" label with a specific percentage
- Works with Shopify Dawn and similar themes
- No paid app required — pure Liquid implementation
- Compatible with both product cards and product pages
- Also includes a dedicated price block for the product page template

## Video Tutorial

[![Show Sale Discount Percentage in Shopify](https://i.ytimg.com/vi/ynLP7Wqx-Vc/maxresdefault.jpg)](https://youtu.be/ynLP7Wqx-Vc?list=PLvT_6E7D1NZIlHa09cgswsjD9QunUpHKy)
> Click the image above to watch the full step-by-step tutorial.

## Getting Started

### Step 1: Update the Product Card Badge
1. In your Shopify admin, navigate to **Online Store → Themes → Edit Code**
2. Locate the `_product-card-gallery.liquid` file (or equivalent in your theme)
3. Replace the existing sale badge code with the provided Liquid snippet that calculates and displays the discount percentage

### Step 2: Add the Price Block
1. In the code editor, create a new block file named `price.percentage.liquid`
2. Paste the provided block code into the file and save

### Step 3: Add the Block to the Product Page Template
1. Navigate to **Themes → Customize → Product Page Template**
2. Add the new **Price Percentage** block to the product page layout as shown in the tutorial

## Customization

- **Badge label:** Modify the "% OFF" suffix text to match your preferred phrasing
- **Rounding:** Adjust how the discount percentage is rounded (floor, round, ceil)
- **Badge styling:** Update colors and typography via your theme's CSS
- **Display logic:** Show the badge only when the discount exceeds a minimum threshold

## Resources

- [Shopify Theme Development Docs](https://shopify.dev/docs/themes)
- [Liquid Template Language Reference](https://shopify.dev/docs/api/liquid)
- [Shopify Section Schema](https://shopify.dev/docs/themes/architecture/sections/section-schema)

---
*Part of the [Free Shopify Sections](https://github.com/websensepro1/free-shopify-sections) collection.*