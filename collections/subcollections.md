# Subcollections

Display related or subcollections as a horizontal slider on collection pages. Helps customers narrow their search and discover relevant products faster.

Subcollections can be displayed in two places:
- As part of the **Collection Banner** section
- As a standalone **Subcollection Banners** section (if you don't need a collection image)

`[SCREENSHOT: Subcollections slider on collection page]`

---

## Setup

### Step 1 — Create a metafield

1. Go to **Shopify Admin → Settings → Custom data → Collections**
2. Click **Add definition**
3. Fill in:
   - **Name:** Subcollections
   - **Namespace and key:** `custom.subcollections` *(must be exact)*
   - **Type:** Collection — List of collections
4. Save

`[SCREENSHOT: Subcollections metafield definition]`

### Step 2 — Bulk assign subcollections

1. Go to **Products → Collections**
2. Select all collections → **Bulk edit**
3. Click **Columns** → add **Metafields → Subcollections**
4. Assign subcollections to each parent collection as needed

`[SCREENSHOT: Bulk edit collections with Subcollections column]`

### Step 3 — Connect dynamic source in Theme Editor

1. Open the **Collection Banner** or **Subcollection Banners** section in Theme Editor
2. Click the **dynamic source icon** next to the **Collections** field
3. Select **Template → Collection → Subcollections**
4. Save

`[SCREENSHOT: Connecting dynamic source in Theme Editor]`

---

## Related

- [Collection Banner](collection-banner.md)
- [Smart Category Menu](../navigation/smart-category-menu.md) — top-level category navigation
