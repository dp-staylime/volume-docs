# Product Badges

Product Badges are small labels that appear on product cards and product pages to highlight key attributes — such as sale status, newness, or low stock.

### Badge Types

Volume supports the following badge types out of the box:

| Badge     | Trigger                                                            |
| --------- | ------------------------------------------------------------------ |
| Sale      | Product has a compare-at price set                                 |
| New       | Product was created within the "new" threshold (configurable days) |
| Sold Out  | All variants are out of stock                                      |
| Low Stock | Remaining inventory falls below a set threshold                    |
| Custom    | Manually assigned via product tags                                 |

📸 SCREENSHOT: Product card showing Sale, New, and Sold Out badges

### Badge Style

Configure the visual appearance of badges:

* **Shape** — Rounded, Square, or Pill
* **Size** — Small, Medium, or Large
* **Position** — Top-left, Top-right, Bottom-left, or Bottom-right (on the product image)

📸 SCREENSHOT: Badge position options on product card

### Badge Colors

Set individual colors for each badge type: background color and text color. This allows Sale badges to be red, New badges to be green, and so on.

### Custom Badges via Tags

To create a custom badge, add a tag to a product in Shopify admin using the format:

badge:Label Text

Example: badge:Bestseller will display a "Bestseller" badge on that product's card.

### "New" Badge Threshold

Set how many days after a product's creation date it should display the "New" badge. After this period, the badge disappears automatically.
