# Linked Products

Linked Products lets you display separate products as color swatches on the product page — without using Shopify variants. Use this when each color is a separate product in your catalog.

`[SCREENSHOT: Linked Products swatches on product page]`

---

## When to use

Some stores create separate products per color instead of using variants because of Shopify limitations:

1. Show each color as a **separate product** on collection pages
2. Display **only images of the selected color** in the product gallery on product pages

Linked Products solves this by connecting those separate products and displaying them as a color swatch block on the product page.

---

## Setup

### Step 1 — Create a metafield

1. Go to **Shopify Admin → Settings → Custom data → Products**
2. Click **Add definition**
3. Fill in exactly:
   - **Name:** Linked products
   - **Namespace and key:** `custom.linked_products`
   - **Type:** Product — List of products
4. Save

`[SCREENSHOT: Linked products metafield definition setup]`

### Step 2 — Link products together

1. Open a product in Shopify Admin
2. Scroll down to the **Linked products** metafield
3. Select all color variants of this product (including the current product — put it first so it appears selected)
4. Repeat this for each linked product

`[SCREENSHOT: Selecting linked products in the metafield on product page]`

### Step 3 — Add the block in Theme Editor

1. Go to **Theme Editor → Default product template**
2. Inside **Product overview** section, click **Add block → Linked Products**
3. Save

`[SCREENSHOT: Linked Products block added in Theme Editor]`

---

## Design settings

Adjust the appearance of Linked Products swatches in **Theme settings → Variant Picker → Linked Products**:

| Setting | Description |
|---------|-------------|
| **Image size (desktop / mobile)** | Size of each product thumbnail |
| **Media ratio** | Aspect ratio for the swatch images |
| **Focal point** | Crop anchor for swatch images |
| **Corner radius** | Border radius of the swatch thumbnails |

---

## Related

- [Variant Picker](../theme-settings/variant-picker.md) — Linked Products display settings
- [Color Swatches](color-swatches.md) — native Shopify swatches setup
