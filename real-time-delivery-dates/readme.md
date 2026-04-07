# Real-Time Delivery Dates

Display real-time estimated delivery dates on your Shopify store using custom Liquid code and product metafields, helping build brand trust and reduce cart abandonment.

## Overview

This tutorial and section implementation teaches you how to show accurate, product-specific estimated delivery dates on your Shopify product pages — without expensive third-party apps. By leveraging Shopify metafields and custom Liquid logic, you can provide customers with shipping timelines that build confidence and encourage purchase completion.

## Features

- Real-time estimated delivery date display on product pages
- Uses Shopify product metafields for per-product shipping timelines
- No expensive third-party app required
- Dynamically calculates estimated delivery based on current date
- Customizable messaging and date format
- Builds customer trust and reduces cart abandonment
- Compatible with any Shopify theme

## Video Tutorial

[![Real-Time Delivery Dates on Shopify](https://i.ytimg.com/vi/spVGFSMnOZ0/maxresdefault.jpg)](https://youtu.be/spVGFSMnOZ0?list=PLvT_6E7D1NZIlHa09cgswsjD9QunUpHKy)
> Click the image above to watch the full step-by-step tutorial.

## Getting Started

1. In your Shopify admin, navigate to **Settings → Custom data → Products** and create a metafield for shipping lead time (e.g., min and max days)
2. Add the Liquid snippet to your product template to calculate and display the delivery date range
3. Populate the shipping metafields for each product in your catalog
4. Optionally style the delivery date display to match your theme
5. Save and publish your changes

## Customization

- **Lead time metafields:** Set minimum and maximum shipping days per product
- **Date format:** Configure how the estimated delivery date is displayed
- **Messaging:** Customize the label text (e.g., "Estimated delivery: Mon, Apr 14 – Wed, Apr 16")
- **Business day logic:** Optionally exclude weekends from the delivery calculation
- **Placement:** Position the delivery date near the Add to Cart button for maximum impact

## Resources

- [Shopify Metafields Documentation](https://shopify.dev/docs/apps/custom-data/metafields)
- [Shopify Theme Development Docs](https://shopify.dev/docs/themes)
- [Liquid Template Language Reference](https://shopify.dev/docs/api/liquid)

---
*Part of the [Free Shopify Sections](https://github.com/websensepro1/free-shopify-sections) collection.*