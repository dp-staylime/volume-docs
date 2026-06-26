# Smart Category Menu

A Volume-exclusive navigation feature for stores with 2–4 top-level categories (e.g. Men / Women / Kids, or Clothing / Shoes / Bags). Creates separate landing pages per category with a dynamic bottom bar menu.

`[SCREENSHOT: Smart Category Menu in action on storefront]`

---

## What it does

1. **Separate home pages** per top-level category — each with its own relevant sections
2. **Dynamic bottom menu** that updates based on the selected top-level category
3. **Third nested menu level** — beyond Shopify's standard two levels
4. **Breadcrumb path** includes the top-level category for easier navigation

---

## Setup

### Step 1 — Define top-level categories

Decide on your top-level categories (e.g. Men / Women / Kids) and which collections and subcollections belong to each.

### Step 2 — Create category landing pages

**For the first category:** use the Home page. Add sections relevant to that category.

**For subsequent categories:** use collection templates.

To copy the Home page layout into a collection template:
1. Go to **Online Store → Edit Code → open `index.json`**
2. Copy the entire contents
3. Paste into `templates/collection.parent-collection-2.json`
4. Save

To create additional templates: **Collections → Create template** → enter a name → select **parent-collection-2** in the Based on dropdown.

`[SCREENSHOT: Duplicating a collection template in Theme Editor]`

> **Tip:** Optionally create a minimalist Home page that directs users to choose a category, and assign all top-level categories to collection templates.

### Step 3 — Assign templates to collections

In Shopify Admin, open each top-level category collection and assign the corresponding template.

`[SCREENSHOT: Assigning a template to a collection in Shopify Admin]`

### Step 4 — Create the top-level menu

1. Go to **Shopify Admin → Content → Menus → Add menu**
2. Add your top-level categories as first-level items
3. Set the first item to **Homepage** (or link to a collection if using the hub page approach)

`[SCREENSHOT: Top-level menu structure in Shopify Admin]`

### Step 5 — Create per-category menus

Create a separate menu for each top-level category (e.g. a "Men" menu with men's collections).

> ⚠️ **Important:** The **handle** of each menu must exactly match the name of the corresponding top-level category item.

`[SCREENSHOT: Menu handle matching the category name]`

### Step 6 — Enable Smart Category Menu in Theme Editor

1. Open the **Header** section in Theme Editor
2. Select the top-level category menu under **Menu**
3. Check **Enable smart category menu**

### Step 7 — Create collection metafield

Create a metafield to assign each collection to its top-level category:

1. Go to **Shopify Admin → Settings → Custom data → Collections → Add definition**
2. Fill in:
   - **Name:** Top level category
   - **Namespace and key:** `custom.top_level_category` *(must be exact)*
   - **Type:** Single line text — One value
3. Save

### Step 8 — Assign collections and products to categories

**Bulk edit collections:**
1. Go to **Products → Collections**
2. Select all → **Bulk edit**
3. Add the **Top level category** metafield column and fill in each collection

**Assign products via tags:**
Add a tag matching the top-level category name to each product. Alternatively, create the same metafield for products as for collections.

---

## Related

- [Header & Menu Styles](header-and-menu-styles.md) — header layouts and menu configuration
- [Breadcrumbs](breadcrumbs.md) — Show top-level category in breadcrumb path
