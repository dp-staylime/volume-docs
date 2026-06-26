# Product Grid & Filtering

Configure product display, pagination, filtering, and the grid switcher for collection pages.

`[SCREENSHOT: Product grid on collection page]`

---

## Grid columns switcher

Allow customers to toggle between up to three grid layouts. The selected layout is saved in local storage and persists while browsing collection pages.

`[SCREENSHOT: Grid switcher icons on collection page]`

To configure:

1. **Default grid** — set the standard grid layout
2. **Secondary grid** — enable for a wider product view (more columns)
3. **Preview grid** — enable to show product images only, no card content

> **Note:** On mobile, only the default and preview grids are used. The secondary grid is disabled on mobile.

---

## Filtering

Three filter layout styles are available:

| Style | Description |
|-------|-------------|
| **Drawer** | Filters open in a side panel |
| **Vertical** | Filters displayed in a sidebar alongside the grid |
| **Horizontal** | Filters displayed in a bar above the grid |

For **Drawer** and **Vertical** styles: define which filter tabs are expanded by default using the **Tabs always open** field — enter tab names separated by commas.

### Filter configuration

Volume fully supports native Shopify filters, including color swatches via category metafields — no coding required. Swatches appear consistently across product pages, collection filters, and product cards.

- [Set up category metafields for color filters](https://help.shopify.com/en/manual/custom-data/metafields/category-metafields/using-category-metafields#step-two)
- [Use metaobjects for advanced filtering](https://help.shopify.com/en/manual/custom-data/metaobjects)

---

## Related

- [Color Swatches](../products/color-swatches.md) — native swatch setup
- [Filter Swatches](../theme-settings/filter-swatches.md) — display settings for filter swatches
- [Collection Banner](collection-banner.md)
