# Image Grid

Display a gallery of images on any page using the **Image Grid** section. Images are stored in a page metafield and loaded dynamically.

`[SCREENSHOT: Image Grid section on storefront]`

---

## Setup

### Step 1 — Create a metafield

1. Go to **Shopify Admin → Settings → Custom data → Pages**
2. Click **Add definition**
3. Fill in:
   - **Name:** Gallery
   - **Namespace and key:** `custom.gallery` *(must be exact)*
   - **Type:** File — List of files
4. Save

`[SCREENSHOT: Gallery metafield definition setup]`

### Step 2 — Create a page and upload images

1. Go to **Shopify Admin → Online Store → Pages**
2. Create a new page with a descriptive name (e.g. "Project X Photos")
3. Scroll down to the **Gallery** metafield
4. Upload your images

### Step 3 — Add Image Grid to a template

1. Open **Theme Editor** and navigate to the template where you want to display the gallery
2. Add the **Image Grid** section
3. In the section settings, select the page you created

`[SCREENSHOT: Image Grid section settings with page selector]`

---

## Related

- [Layout](../theme-settings/layout.md) — grid settings for sections
