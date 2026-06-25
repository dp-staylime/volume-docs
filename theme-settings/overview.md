# Overview

### Colors & Color Schemes

Volume theme supports up to **21 color schemes**. Each color scheme defines a unique combination of colors used across the storefront.

Each color scheme includes:

* **Background** — page/section background color
* **Surface** — cards, overlays, secondary backgrounds
* **Text** — primary text color
* **Primary** — buttons, links, interactive elements
* **Accent** — highlighted elements, badges

Color schemes are assigned per-section in the Theme Editor. You can create up to 21 schemes under **Theme settings → Colors**.

📸 SCREENSHOT: Colors panel in Theme Editor showing color scheme list

***

### Typography

#### Base Font Size

Use the **Base font size** slider to scale all text proportionally across the store.

#### Heading Control

Volume provides granular control over heading styles:

* **H1–H6** — each can be configured independently
* **Font family** — separate font for headings vs. body text
* **Font weight, size, line height, letter spacing**

#### Special Heading Styles

* **Secondary heading** — wrap heading text in `{curly brackets}` to apply an alternate font style
* **Highlighted heading** — wrap text in `[square brackets]` to apply a decorative highlight effect

📸 SCREENSHOT: Typography settings panel

***

### Layout

Control the overall page grid and content width.

| Setting              | Options                |
| -------------------- | ---------------------- |
| **Page Grid**        | Full-width / Max-width |
| **Secondary Grid**   | Full-width / Max-width |
| **Alternative Grid** | Full-width / Max-width |

* **Full-width** — content spans the full browser width
* **Max-width** — content is constrained to a maximum container width

📸 SCREENSHOT: Layout settings in Theme Editor

***

### Variant Picker

Choose how product variants are displayed on product pages and cards.

| Style             | Description                            |
| ----------------- | -------------------------------------- |
| **Dropdown**      | Standard select dropdown               |
| **Pill**          | Clickable pill/button for each variant |
| **Color Swatch**  | Color dot (uses variant color)         |
| **Variant Image** | Shows variant media thumbnail          |

📸 SCREENSHOT: Variant picker styles comparison

***

### Product Card

Configure how products appear in grids and collection pages.

**Update Variant Price/Badge** — product card price and badge update when a variant is selected

**Available Sizes** — show a list of available sizes directly on the product card

**Media Style options:**

* Media aspect ratio
* Show second image on hover

**Content Style options:**

* Vendor display
* Price placement
* Star rating display

📸 SCREENSHOT: Product card settings

***

### Collection Card

Two card styles available for collection listings:

1. **Style 1** — Image with title overlay
2. **Style 2** — Image above title

📸 SCREENSHOT: Collection card style options

***

### Filter Swatches

Control how filter options are displayed in collection filter panels.

| Style            | Description                      |
| ---------------- | -------------------------------- |
| **Checkbox**     | Standard checkbox list           |
| **Pill**         | Clickable pill buttons           |
| **Color Swatch** | Color dot (mapped to HEX values) |
| **Thumbnail**    | Small image thumbnails           |

***

### Product Badges

Configure automatic badges on product cards.

**Default badge labels:**

* **Sale** — shown when a product has a compare-at price
* **Sold out** — shown when inventory is 0
* **Preorder** — shown when preorder template is active

**Custom badge via metafield:**

Add a custom badge to any product using the `custom.badge` metafield:

1. Go to **Shopify Admin → Products**
2. Open a product
3. In the **Metafields** section, find or create `custom.badge`
4. Enter the badge label text

📸 SCREENSHOT: Product badges settings
