# Free Kinetic Stage Sneaker Showcase for Shopify

Add a luxury, motion-driven sneaker showcase section to any Shopify theme — free or paid — with no app required.

## Overview

Kinetic Stage Sneaker Showcase turns your products into a cinematic hero stage. Each slide is one Shopify product: the shoe swoops in diagonally, lands with a natural bounce, and a floor shadow squashes and stretches in sync. The canvas and the glass card glow in the colors you choose for every slide. Everything else (title, price, sizes, colors, gallery, video, rating) is pulled from the product automatically and is fully customizable through the Shopify theme editor.

## Features

- Works with any Shopify theme (built and tested on Horizon)
- No third-party apps required
- Product-driven slides: title, vendor, description, price, compare-at price, sizes, colors, gallery and reviews rating come from the product
- Swoop-in, bounce and settle shoe animation with a floor shadow bound to the shoe's height
- Per-slide **Canvas color 1 / 2** (for example green and white) that blur onto the outer canvas and tint the glass card
- Size pills and color swatches that appear only when the product has real Size / Color variants
- Gallery thumbnails with a "+N" badge, built from the product images
- Video modal (YouTube, Vimeo or MP4) from the slide URL or the product's own video
- Animated add-to-cart button (ripple, spinner, drawn checkmark) that updates the Horizon cart drawer without a page reload
- Keyboard arrows, touch swipe, mouse wheel over the stage, and optional autoplay
- Fully responsive, with reduced-motion and no-GSAP fallbacks
- Lightweight: vanilla JavaScript plus GSAP 3 (loaded from cdnjs only if your theme does not already provide it)

## Getting Started

1. Download or copy the section file from this directory
2. Go to your Shopify Admin → **Online Store** → **Themes**
3. Click **Edit Code** on your active theme
4. Under **Sections**, click **Add a new section**, name it `kinetic-stage-sneaker-showcase` and paste the code
5. Add **Kinetic Stage Showcase** to your desired page via the theme customizer

## Customization

Once added, the section can be configured directly in the **Shopify Theme Editor**.

**Slide blocks** (up to 10)

- Pick a product for each slide
- Optional overrides for brand, title, description, hero image and video URL
- Canvas color 1 and 2 for the slide's glow (leave empty to auto-generate from the product color)
- Fallback swatch color and rating

**Section settings**

- **Layout:** height, card width, padding, radius, mirrored layout
- **Stage and shoe:** stage height, shoe size, shoe and shadow position, floor shadow
- **Visible elements:** toggle logo, subtitle, thumbnails, rating, sizes, swatches, price, video and scrubber
- **Buttons and labels:** add-to-cart style, shape, hover color and text, and what happens after adding (open cart drawer, stay on page, or go to cart page)
- **Typography:** fonts, title, subtitle, price and body sizes
- **Colors:** canvas, card, text, price, stars, buttons, size pills and swatch ring
- **Ambient glow and texture:** glow opacity and size, glow shade inside the card, card glass blur, film grain
- **Animation:** speed, bounce, entry direction, idle float, tilt, autoplay, keyboard, swipe and wheel controls
- **Advanced:** custom CSS

## Tips

- Use transparent PNG or WebP product images for the best result. Photos with a background still work but look boxed.
- Name your product options **Size** and **Color** so they are detected automatically.
- To show a rating, add the standard `reviews.rating` product metafield or set a fallback rating on the slide.
- The cart drawer refresh is written for the Horizon theme. On other themes, set **After adding to cart** to "Go to cart page" or "Stay on page".

## Resources

- [Shopify Sections Documentation](https://shopify.dev/docs/storefronts/themes/architecture/sections)
- [Shopify Theme Editor Guide](https://help.shopify.com/en/manual/online-store/themes/theme-structure/extend/edit-theme-code)

---

*Part of the [Free Shopify Sections](https://github.com/websensepro1/free-shopify-sections) collection.*
