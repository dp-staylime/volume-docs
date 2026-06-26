# Color swatches

Volume natively supports Shopify color swatches — no custom code required. When set up correctly, swatches display consistently across product pages, product cards, and collection filters.

`[SCREENSHOT: Color swatches on product page]`

---

## Native support (recommended)

The easiest and most reliable way to set up color swatches is via Shopify's **category metafields**.

Follow the steps in the [Shopify Help Center guide](https://help.shopify.com/en/manual/custom-data/metafields/category-metafields/using-category-metafields#step-two) to configure swatches using category metafields.

> **Tip:** Volume also supports displaying a **variant image** as a swatch. See [Variant Picker](../theme-settings/variant-picker.md) settings for details.

---

## Legacy methods

Use these methods only if you cannot upgrade to Shopify product categories.

### HEX colors

1. Go to **Theme settings → Variant picker**
2. Scroll down to **Custom colors for swatches**
3. Add your color name and HEX code in the format `Name:#HEX`

Example: `Wine:#722F37`

> ⚠️ The color name must exactly match the corresponding variant label — including capitalization.

### Image files

1. Prepare square PNG images named after your color options:
   - Example: `red.png` for "Red", `ocean_blue.png` for "Ocean blue"
   - Recommended size: **60×60px**, max file size: **under 20KB**
2. Go to **Shopify Admin → Content → Files** and upload the images
3. Once the Color pills feature is enabled, swatches are automatically assigned by matching file names to variant labels

---

## Related

- [Variant Picker](../theme-settings/variant-picker.md) — display types, layout options, and linked products
- [Filter Swatches](../theme-settings/filter-swatches.md) — color swatches in collection filters
