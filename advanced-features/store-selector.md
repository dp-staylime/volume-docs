# Store Selector

Let customers check product pickup availability across your physical locations directly on collection and product pages.

`[SCREENSHOT: Store Selector drawer open on storefront]`

---

## Step 1 — Set up Shopify Locations

Configure your physical locations in Shopify Admin before setting up the Store Selector. Each location represents a place from which you fulfill orders or offer pickups.

[Shopify Locations setup guide →](https://help.shopify.com/en/manual/shipping/setting-up-and-managing-your-shipping/local-methods)

---

## Step 2 — Add the Store Selector Drawer

1. Open **Theme Editor**
2. Scroll to the bottom of the left panel → find the **Overlay** section group
3. Add the **Store selector drawer** section

Each **Store block** inside this drawer corresponds to one Shopify Location.

> ⚠️ **The Store name field must exactly match the location name in Shopify Admin → Settings → Locations.**

For each store block you can also add:
- Address
- Image
- Details (business hours, additional info)

`[SCREENSHOT: Store selector drawer settings in Theme Editor]`

---

## Step 3 — Add Store Selector to navigation

### Header

Open the **Header section** settings and enable the checkbox under **Store selector**.

### Menu Drawer

1. Go to the **Overlay** section group
2. Add the **Store selector** block inside the **Menu drawer** section

---

## Step 4 — Add pickup availability widgets

### Product cards

In any section or block that displays product cards, enable the **Show pickup availability** checkbox.

`[SCREENSHOT: Show pickup availability checkbox in section settings]`

### Product page

Add the **Pickup availability** block inside the **Product overview** section in the product template.

`[SCREENSHOT: Pickup availability block added in Product overview]`

---

## Colors

Customize the availability indicator colors in **Theme settings → Colors → Pickup availability**:

- Available text color
- Available icon color
- Out of stock text color
- Out of stock icon color

---

## Related

- [Colors & Color Schemes](../theme-settings/colors-and-color-schemes.md)
- [Header & Menu Styles](../navigation/header-and-menu-styles.md)
