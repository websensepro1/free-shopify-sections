# Featured Testimonials Section

A centered, infinite-loop testimonial carousel for Shopify with a rating badge, partial-star ratings and an optional floating video widget.

## Overview

The active review card sits in the center, enlarged and fully opaque, while the side cards are dimmed. Customers can use arrows, drag/swipe, click a card or let autoplay move through the reviews. A star-rating badge sits above the carousel, and an optional sticky video bubble in the corner expands on click.

## Features

- Center-focused carousel with seamless infinite loop
- Arrow buttons, mouse drag, touch swipe and click-to-focus
- Optional autoplay (3–10 seconds)
- Rating badge with partial stars (e.g. 4.7 fills 70% of the last star)
- Per-review star rating in 0.5 steps
- Floating sticky video widget (bottom left or right) that expands on click, with title and CTA button
- Use a Shopify-uploaded video or an external MP4 URL, with poster image and autoplay/loop/mute/controls options
- Font picker plus preset web fonts, with size, style and decoration controls for heading, card title and card body
- Solid or gradient section background, card radius and optional shadows
- Customizable colors for cards, stars, arrows and buttons
- Fully responsive for all screen sizes
- Compatible with any Shopify 2.0 theme, no paid app required

## Getting Started

1. In your Shopify admin go to **Online Store → Themes → ⋯ → Edit code**.
2. Under **Sections**, click **Add a new section** and name it `featured-testimonials`.
3. Paste the contents of `featured-testimonials.liquid` and click **Save**.
4. Go to **Customize**, click **+ Add section** and choose **Featured Testimonials**.
5. Add or edit **Review Card** blocks with the rating, title, review text, name and date.

## Customization

**Section settings**
- Heading and rating badge (prefix, score, star rating, subtitle)
- Floating video: enable, position, video source, poster, playback options, overlay title and button
- Typography: font, sizes, styles and decorations
- Bottom button text and link
- Autoplay on/off and duration
- Background color/gradient, text colors, card radius and shadow
- Active card, side card, star, arrow and button colors
- Maximum width and top/bottom padding

**Review Card block**
- Star rating (1–5, step 0.5)
- Review title and body text
- Customer name and date text

## Notes

- The floating video is fixed to the viewport, so it stays visible while the visitor scrolls. Turn it off with **Enable Floating Video Widget** if you only want the carousel.
- With no Shopify video selected, the widget plays the external MP4 URL setting. Replace the default sample URL with your own video.

## Resources

- [Shopify Theme Development Docs](https://shopify.dev/docs/themes)
- [Liquid Template Language Reference](https://shopify.dev/docs/api/liquid)
- [Shopify Section Schema](https://shopify.dev/docs/themes/architecture/sections/section-schema)

---
*Part of the [Free Shopify Sections](https://github.com/websensepro1/free-shopify-sections) collection.*
