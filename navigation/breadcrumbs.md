# Breadcrumbs

Show visitors their current location within the store — e.g. `Home / Collection / Product`. Improves navigation and product discoverability.

Configure from **Theme settings → Breadcrumbs**. Can be added as a **section** or **block** depending on the page template.

`[SCREENSHOT: Breadcrumbs shown on product page]`

---

## SEO consideration

Breadcrumbs link products via their collection path, which creates multiple URLs for the same product:

- `storename.com/collections/tshirts/products/logo-tee`
- `storename.com/collections/sale/products/logo-tee`

Shopify automatically handles canonical tags to prioritize the main product URL in search engines. In most cases enabling breadcrumbs is recommended — the navigation benefit outweighs the SEO trade-off.

---

## Path style options

### Show collections list page

Includes a link to the collections list page right after Home:

`Home / Collections / Tops / T-shirt`

### Show top-level category

If you use [Smart Category Menu](smart-category-menu.md), this option adds the top-level category to the breadcrumb path:

`Home / Clothing / Tops / T-shirt`

---

## Related

- [Smart Category Menu](smart-category-menu.md) — required for Show top-level category option
- [Header & Menu Styles](header-and-menu-styles.md)
