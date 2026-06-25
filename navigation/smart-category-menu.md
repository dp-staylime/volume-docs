# Smart Category Menu

Smart Category Menu is a Volume-exclusive navigation feature that automatically generates a visual, category-based menu based on your Shopify collections — no manual setup required.

### How It Works

When enabled, the Smart Category Menu scans your active collections and builds a dynamic navigation panel with collection images, names, and links. It updates automatically as you add or remove collections in Shopify.

📸 SCREENSHOT: Smart Category Menu open on storefront

### Enabling Smart Category Menu

1. Go to **Online Store → Themes → Customize**
2. Open the **Header** section
3. Enable **Smart Category Menu** toggle
4. Select the menu to use as the source for categories

### Display Settings

| Setting                | Description                                                     |
| ---------------------- | --------------------------------------------------------------- |
| Columns                | Number of category columns in the panel                         |
| Show collection images | Display collection thumbnail images                             |
| Show product count     | Show number of products per collection                          |
| Image ratio            | Aspect ratio of collection images (Square, Portrait, Landscape) |

📸 SCREENSHOT: Smart Category Menu settings in theme customizer

### Filtering Collections

By default, all active collections appear. To exclude specific collections from the Smart Category Menu, add the tag `hide-from-menu` to that collection in Shopify admin.

### Performance Note

Smart Category Menu loads collection data dynamically. For stores with 50+ collections, consider limiting display to the most relevant categories to maintain fast load times.
