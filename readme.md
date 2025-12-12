# Dynamatic Bundles

Dynamatic Bundles is a Shopify app designed to boost your Average Order Value (AOV) by offering smart, customizable bundle experiences directly on your storefront. Instead of selling single items, you can encourage customers to buy more by combining related products, offering strategic discounts, or giving shoppers the freedom to build their own perfect kits.

Whether you want to sell a fixed set of items or a “build-your-own-box” experience, Dynamatic provides the flexibility to create the perfect offer.

<!-- IMAGE: Dashboard overview showing the Bundles tool interface in the Dynamatic app -->
![...](/Dashboard-overview.png)
## Where It Works

Dynamatic Bundles affects what customers see on:

- Storefront pages (product pages, collection pages, landing pages)
- The shopping cart (how bundle items appear)
- Shopify Admin (bundle configuration and reporting)

<!-- IMAGE: Example of a bundle displayed on a storefront page and in the cart -->

---

## Prerequisites

Before setting up Dynamatic Bundles, ensure you have:

### Required

- An active Shopify store (Basic plan or higher)
- A Shopify Online Store 2.0–compatible theme
- The Dynamatic app installed and activated

### Recommended

- Products created in your Shopify catalog
- Collections organized (for collection-based bundles)
- High-quality product images (recommended: at least 1000×1000 px)

### Permissions Needed

- Access to Shopify Admin
- Permission to install/manage apps
- Permission to edit theme (for Section layouts)

---

## Glossary (Quick Reference)

| Term            | Definition                                                                 |
|-----------------|----------------------------------------------------------------------------|
| AOV             | Average Order Value – average amount spent per transaction                |
| App Embed       | Shopify feature allowing apps to inject code into themes                  |
| Bundle          | Group of products sold together under special pricing or logic            |
| Bundle ID       | Unique identifier for a bundle, used when embedding it into a theme       |
| BAP             | “Bundle as Product” – how bundles appear in the cart                      |
| Cart Transform  | Display mode that groups multiple items under a single cart line          |
| Multi BAP       | Display mode that shows each bundle item as a separate cart line          |
| Product Feed    | Dynamic product list based on rules/filters                               |
| Section         | Shopify theme component that can be added/removed via Theme Editor        |
| Tiered Discount | Discount that increases with quantity (buy more, save more)               |
| Trigger Product | Main product that activates an Add-ons Bundle widget                      |

A more complete glossary is included near the end of this document.

---

## Table of Contents

1. [Introduction](#dynamatic-bundles)
2. [Bundle Types Overview](#bundle-types-overview)
3. [How to Set Up Dynamatic Bundles](#how-to-set-up-dynamatic-bundles)
4. [Bundle Builder](#bundle-builder)
5. [Prebuilt Bundles](#prebuilt-bundles)
6. [Add-ons Bundle](#add-ons-bundle)
7. [Bundle Builder Lite](#bundle-builder-lite)
8. [Best Practices & Helpful Tips](#best-practices--helpful-tips)
9. [Theme Compatibility](#theme-compatibility)
10. [Inventory Considerations](#inventory-considerations)
11. [Analytics & Performance Tracking](#analytics--performance-tracking)
12. [Mobile Experience](#mobile-experience)
13. [Troubleshooting Guide](#troubleshooting-guide)
14. [Frequently Asked Questions](#frequently-asked-questions)
15. [Extended Glossary](#extended-glossary)
16. [Known Limitations](#known-limitations)
17. [SEO for Bundle Pages](#seo-for-bundle-pages)
18. [International Stores](#international-stores)
19. [Getting Help](#getting-help)
20. [Document Version History](#document-version-history)

---

## Bundle Types Overview
![...](/Four-types-of-bundle.png)

Dynamatic offers four flexible bundle types to support different sales strategies and design needs.

### Where Bundle Types Work

- **Bundle Builder / Bundle Builder Lite**  
  - Storefront: Dedicated landing page or embedded section  
  - Cart: Items shown as grouped or separate depending on settings

- **Prebuilt Bundles**  
  - Storefront: Behave like standard products (can appear in collections, search, etc.)  
  - Cart: Can show as one merged item or separate components

- **Add-ons Bundle**  
  - Storefront: Appears on selected product pages as a “Frequently Bought Together”/upsell widget  
  - Cart: Addon items are added as standard cart line items

### The 4 Flexible Bundle Types

| Bundle Type         | Best For Whom?                                                       | Creates a Real Product?      | Best Use Case                                         |
|---------------------|----------------------------------------------------------------------|------------------------------|-------------------------------------------------------|
| Bundle Builder      | Merchants who want full, custom bundle flows (Mix & Match, Build-a-Box) | No                           | Gift boxes, custom kits, build-your-own sets         |
| Prebuilt Bundle     | Merchants who want a fixed bundle that behaves like a standard product | Optional (Create/Link/None) | Classic “Buy these 3 together & save” offers         |
| Add-ons Bundle      | Merchants wanting frequently-bought-together or upsell items on product pages | No                           | “Complete the look,” warranties, gift wrapping       |
| Bundle Builder Lite | Merchants needing a quick mix-and-match solution without complexity  | No                           | Small stores or testing simple bundle concepts       |

IMAGE PLACEMENT MARKER #1  
Caption: “Visual comparison of all four bundle types as they appear to customers”
[Insert: 4-panel comparison image showing storefront view of each bundle type] 


---

## How to Set Up Dynamatic Bundles

Quick Links: [Create Bundle](#1-create-your-bundle) | [Enable Script](#2-enable-the-dynamatic-bundles-script) | [Publish](#3-publish-your-bundle)


Follow this step-by-step guide to configure, enable, and publish bundles on your storefront.

### 1. Create Your Bundle

First, define the type of bundle you wish to offer and configure its contents within the app dashboard.

#### A. Choose Bundle Type

1. Go to **Shopify Admin → Apps → Dynamatic → Tools → Bundles**.
2. Click **Create bundle**.
3. Select one of the following bundle options:
   - **Prebuilt** – A fixed set of products sold together.
   - **Add-ons** – Complementary products offered alongside a main item.
   - **Bundle Builder** – Customers build their own custom bundle.
   - **Bundle Builder Lite** – Simplified version of the Builder for quick setup.

#### B. Configure Basic Settings

Once the type is selected:

- **Add Products** – Select the specific items to include in the bundle.
- **Set Pricing** – Define fixed prices or configure discount rules.
- **Customize Layout** – Adjust the visual appearance to match your store’s branding.
- **Review** – Verify product combinations and display settings.

### 2. Enable the Dynamatic Bundles Script

Bundles will not appear on your site unless the app embed is enabled for the theme.

Steps:

1. Go to **Shopify Admin → Online Store → Themes**.
2. Click **Customize** on the theme where you want bundles to appear.
3. In the left sidebar, click the **App Embeds** icon.
4. Locate **Dynamatic Bundles** and toggle it **ON**.
5. Click **Save** in the top-right corner.

IMAGE PLACEMENT MARKER #19  
[Insert: GIF showing complete App Embed activation process]  
Caption: “Enabling the Dynamatic Bundles script in Theme Editor”

IMAGE PLACEMENT MARKER #20  
[Insert: Annotated screenshot of App Embeds panel with Dynamatic Bundles toggle]  
Caption: “Locate and toggle ON the Dynamatic Bundles app embed”

> Warning: If you change your theme in the future, you must repeat these steps for the new theme.

### 3. Publish Your Bundle

1. In the Dynamatic app, open the bundle you want to publish.
2. Select placement (Full Page or Section, depending on type).
3. Confirm all product selections and pricing rules.
4. Preview the bundle on your storefront.
5. Click **Save** and toggle the bundle **Active**.

IMAGE PLACEMENT MARKER #12  
[Insert: Annotated screenshot showing Save button and Active toggle locations]  
Caption: “Save your changes and toggle the bundle to Active”

---

## Bundle Builder

Bundle Builder is the most versatile option, allowing you to create custom “Build-a-Box” or “Mix & Match” experiences.

Estimated setup time: 15–25 minutes (depending on complexity)

Quick Links: [Create Bundle](#step-1-create-a-new-bundle) | [Add Products](#step-3-add--organize-products) | [Set Pricing](#step-4-set-discounts--pricing) | [Publish](#step-6-save--publish)

### Step 1: Create a New Bundle
1. Navigate to **Shopify Admin → Apps → Dynamatic → Tools → Bundles**.
2. Click **Create bundle**.
3. Select **Bundle Builder**.
4. Enter an internal name and click **Create**.

[Insert: GIF showing complete flow from Shopify Admin → Apps → Dynamatic → Tools → Bundles → Create bundle → Select Bundle Builder → Enter name → Create]  
“Creating a new Bundle Builder in Dynamatic”
![...](/create-bundle-builder.png)

---

### Step 2: Choose Your Layout

Decide how the bundle will be presented to customers.

| Layout Type | Best Use Case                                               | How to Implement                                                                                                                                      |
|------------|--------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| Full Page  | Recommended for large bundles. Generates a dedicated page.   | After saving, click **View page** in your bundle list. Link this URL directly in navigation, email, or ads.                                          |
| Section    | Best for embedding on existing pages (Homepage, Product).    | Copy the **Bundle ID** from the app. In Theme Editor: **Add Block → Dynamatics Bundle Kit → Select “Section Bundle” → Paste ID** and Save.           |

IMAGE PLACEMENT
[Insert: Comparison image showing Full Page layout vs. Section layout] 
![...](/Full-vs-slelect.png)

IMAGE PLACEMENT MARKER #4  
[Insert: GIF demonstrating Section bundle embedding process in Theme Editor]  
Caption: “How to embed a Section Bundle into your Shopify theme”

---

### Step 3: Add & Organize Products

1. In the bundle editor, click **Add products**.

You can populate products from:

- **Individual Products** – Select specific SKUs.
- **Collections** – Use an entire collection (e.g., “Pick 3 from the Snacks collection”).
- **Product Feeds (Advanced)** – Dynamic lists driven by rules (e.g., all snacks in stock under $20).

IMAGE PLACEMENT MARKER #5  
[Insert: Screenshot of "Add Products" modal with all three source options visible]  
![...](/Add-products.png)
Caption: “Three ways to add products: Individual, Collections, or Product Feeds”

#### Organize with Categories

For the best customer experience, structure your bundle as logical steps:

- Create categories (e.g., “Step 1: Choose Base”, “Step 2: Pick Flavors”, “Free Gift”).
- Drag and drop products into their categories.
- Optionally set minimum and maximum quantity limits per category.

IMAGE PLACEMENT MARKER #6  
[Insert: GIF showing drag-and-drop product organization into categories]  
Caption: “Organizing products into logical steps using drag-and-drop”

> Note: Category quantity limits help guide customers (for example, “Choose exactly 2 bases and at least 3 toppings”).

#### Select Product Display Type

Choose how products are shown on the storefront:

- **Tabs** – Categories appear as tabs; best for 3–6 distinct categories.
- **Sections** – Categories stacked vertically with headers.
- **Infinity** – Single endless grid with no visible category separation.

IMAGE PLACEMENT MARKER #7  
[Insert: 3-panel comparison of Tabs, Sections, and Infinity display types]  
Caption: “Product Display Types: Tabs (left), Sections (center), Infinity (right)”

---

### Step 4: Set Discounts & Pricing

Define how prices change as customers build their bundle.

#### 1. Choose Discount Type

- **Fixed Discount** – Discount stays the same regardless of quantity.
- **Tiered Discount** – Discount increases at specific quantity thresholds.

IMAGE PLACEMENT MARKER #8  
[Insert: Diagram comparing Fixed discount (flat line) vs. Tiered discount (stepped progression)]  
Caption: “Fixed Discount applies the same savings regardless of quantity. Tiered Discount increases savings as customers add more items.”
![...](/image-compare-split.png)

#### 2. Choose Discount Method

| Method       | Function                                             | Example                         |
|--------------|------------------------------------------------------|---------------------------------|
| Fixed Amount | Subtracts a specific amount from each item           | $5.00 off per item              |
| Percentage   | Subtracts a percentage from each item                | 15% off per item                |
| Set Price    | Sets a fixed price for the bundle as a whole         | 5 items for $49.99 total        |
| No Discount  | Groups products without price incentives             | Curated gift sets with no deal  |

#### Example: Tiered Discount Setup

- Tier 1: Buy 2+ items → Get 10% off  
- Tier 2: Buy 4+ items → Get 20% off  
- Tier 3: Buy 6+ items → Get 25% off + Free Gift

IMAGE PLACEMENT MARKER #9  
[Insert: Screenshot of tiered discount setup matching the Tier 1/2/3 example]  
Caption: “Example tiered discount configuration”

#### Pro Tip for Tiered Messages

For the final tier success message (default: `Congratulations! You got {{reward}}`):

- Do not remove the `{{reward}}` placeholder.
- The app automatically replaces it with the configured reward text (e.g., “25% discount”).

IMAGE PLACEMENT MARKER #10  
[Insert: Screenshot highlighting the {{reward}} placeholder in success message field]  
Caption: “Keep the {{reward}} placeholder—it automatically displays your discount value”
![...](/displays-your-discount-value.png)

---

### Step 5: Configure Settings

Fine-tune how your bundle behaves.

#### Cart Appearance

- **Multi BAP (Recommended)**  
  - Each bundle item appears as its own line in the cart.  
  - Best for transparent pricing and clean inventory tracking.

- **Cart Transform**  
  - Items appear grouped under a single “bundle” name.  
  - Best for a simpler, less cluttered cart.

IMAGE PLACEMENT MARKER #11  
[Insert: Side-by-side cart screenshots]  
Caption: “Left: Multi BAP shows items as separate line items | Right: Cart Transform groups items under bundle name”

> Note: Cart appearance can affect how other apps (e.g., loyalty or analytics apps) interpret your orders. Test if you rely heavily on third‑party integrations.

#### Page Title (Full Page layout only)

- Set the public title for the bundle landing page.  
- The URL handle is typically fixed after creation.

#### Audience

- Restrict visibility by:
  - Customer tags (e.g., “wholesale”)
  - Country
  - Or show to **Everyone**

#### Schedule

- Set a start and end date for:
  - Limited-time promotions
  - Flash sales
  - Seasonal offers

---

### Step 6: Save & Publish

1. Click **Save** to store your changes.
2. In the bundle list, toggle the bundle to **Active**.
3. Preview on your storefront to confirm look and behavior.

(Also covered in [Setup Guide](#3-publish-your-bundle).)

---

### Appendix: Adding a Section Bundle to a Product Page

Use this if you selected the **Section** layout for a Bundle Builder.

1. In Dynamatic, open your bundle.
2. Copy the **Bundle ID** from the top-right corner of the bundle editor.
3. Go to **Shopify Admin → Online Store → Themes → Customize**.
4. Open the page template where you want the bundle (e.g., product page).
5. Click **Add section** or **Add block** (depends on theme).
6. Choose **Apps → Dynamatics Bundle Kit**.
7. In the settings on the right:
   - Set **Bundle Type** to **Section Bundle**.
   - Paste your **Bundle ID**.
8. Click **Save**.

IMAGE PLACEMENT MARKER #13  
[Insert: Complete GIF of Section Bundle embedding process from start to finish]  
Caption: “Complete process: Copying Bundle ID and adding to Theme Editor”

Customers can now build the bundle directly on that page.

---

## Prebuilt Bundles

Prebuilt Bundles are designed for curated sets where you control exactly what the customer buys (e.g., “The Complete Skincare Set”, “Summer BBQ Kit”). Customers do not choose items individually; they buy the fixed set you define.

Estimated setup time: 10–15 minutes

### Key Differences from Bundle Builder

- Fixed contents (no mix-and-match)
- Optional real product creation (bundle can appear like a standard product)
- Simpler configuration

IMAGE PLACEMENT MARKER #14  
[Insert: Customer view of a Prebuilt Bundle on storefront]  
Caption: “Example Prebuilt Bundle: ‘The Complete Skincare Set’ with fixed contents”

### Product Configuration

Decide how the bundle exists in Shopify:

| Option           | Function                                                         | Best For                                      |
|------------------|------------------------------------------------------------------|-----------------------------------------------|
| Create Product   | Creates a new product in Shopify for this bundle                | New kits that do not exist yet                |
| Link to Existing | Connects bundle logic to an already-created product             | Bundles you already set up with SEO content   |
| No Product       | Applies bundle discount logic only, no standalone product entity| Simple grouped discounts without extra SKUs   |

IMAGE PLACEMENT MARKER #15  
[Insert: Screenshot of Product Configuration options (Create Product / Link to Existing / No Product)]  
Caption: “Choose how your Prebuilt Bundle exists in Shopify”
![...](/Product-Configuration-option.png)

### Visual Settings

- **Bundle Product Title** – Name shown to customers (e.g., “Holiday Starter Pack”).
- **Custom Image** – Upload an image representing the full kit.

### Cart Display Options

Choose how the bundle appears at checkout:

- **Merged with Base Product** – Shows as a single line item (bundle product).
- **Separate Line Items** – Shows each component separately in the cart.

(Use similar cart screenshots as in [Bundle Builder → Cart Appearance](#step-5-configure-settings).)

### Inventory Considerations

See [Inventory Considerations](#inventory-considerations) for full details, especially around:

- How “Create Product” affects SKU inventory
- How “Link to Existing” behaves
- How Prebuilt with “No Product” interacts with component inventory

---

## Add-ons Bundle

Add-ons Bundles are used to drive impulse purchases by suggesting complementary items on a product page (e.g., “Frequently Bought Together”, “Complete the look”, warranties, add-ons).

Estimated setup time: 5–10 minutes

### Concept & Usage

- A widget on the product page that suggests extra products.
- Customers can add extras to the cart without leaving the page.
- Ideal for boosting AOV with low-friction upsells.

IMAGE PLACEMENT MARKER #16  
[Insert: Screenshot of Add-ons widget on product page with "Complete the Look" items]  
Caption: “Add-ons Bundle displaying complementary products on a product page”

IMAGE PLACEMENT MARKER #17  
[Insert: GIF showing 1-click add-on functionality from customer perspective]  
Caption: “Customers can add complementary items instantly with a single click”

### Key Features

- Automatic placement on selected product pages
- 1-click add to cart for add-on items
- Uses the same discount and design system as Bundle Builder for consistency

### How to Configure

1. In Dynamatic, create or edit an **Add-ons Bundle**.
2. Select **Trigger Products** – the main products whose pages will show the widget.
3. Select **Addon Products** – the items you want to offer as upsells (warranty, gift wrap, accessories).
4. Optionally configure discounts (fixed, percentage, or set price).
5. Save and ensure the bundle is **Active**.

---

## Bundle Builder Lite

Bundle Builder Lite is a streamlined version of the full Builder, focused on speed and simplicity.

Estimated setup time: 5–10 minutes

### Concept & Usage

- Stripped-down mix-and-match experience.
- For small stores, quick tests, or simple offers.
- No tiered discount logic or advanced styling.

### Key Simplifications

| Feature   | Full Bundle Builder                           | Bundle Builder Lite                            |
|----------|-----------------------------------------------|------------------------------------------------|
| Discounts| Fixed & Tiered (buy more, save more)         | Fixed or Percentage only (no tiers)           |
| Layout   | Full Page or Section                          | Section Layout only                            |
| Complexity| Advanced styling & logic                     | Minimal settings for rapid deployment          |

IMAGE PLACEMENT MARKER #18  
[Insert: Interface comparison of Full Bundle Builder vs. Lite version]  
Caption: “Bundle Builder Lite offers a streamlined interface with fewer settings”

### How to Configure

1. In Dynamatic, create a **Bundle Builder Lite** bundle.
2. Select products to include in the offer.
3. Set a single discount rule (e.g., “15% off the total when at least 3 items are selected”).
4. Use the Theme Editor to embed the Lite Section:
   - Copy the Bundle ID from the app.
   - In Theme Editor, add **Dynamatics Bundle Kit** section or block.
   - Paste the Bundle ID and Save.

---

## Best Practices & Helpful Tips

To maximize results:

- Always preview bundles on your actual theme before publishing.
- Use clear, concise product titles and strong images.
- Offer at least a small discount to increase bundle adoption.
- Place bundles on high-traffic pages:
  - Best-selling product pages
  - Homepage features
  - Dedicated campaign landing pages

---

## Theme Compatibility

### Supported Themes

Dynamatic Bundles is compatible with all Shopify Online Store 2.0 themes, including (but not limited to):

- Dawn and Dawn-based themes
- Other 2.0 themes that support App Blocks and App Embeds

### Legacy Theme Users (Shopify 1.0)

If your theme does not support App Blocks or App Embeds:

1. Contact support for manual integration options.
2. Consider upgrading to a Shopify 2.0 theme for the best experience.

### Known Theme-Specific Considerations

| Theme    | Notes                                                     |
|----------|-----------------------------------------------------------|
| Dawn     | Full compatibility                                       |
| Impulse  | May require custom CSS for perfect alignment              |
| Prestige | Section placement and spacing may vary                    |

### Custom Themes

For custom-built themes, ensure:

- The theme supports App Blocks and App Embeds.
- Section schema is valid.
- Custom JavaScript does not override or interfere with cart behavior.

---

## Inventory Considerations

Correct inventory behavior depends on bundle type and configuration.

### How Bundle Inventory Works

- **Bundle Builder / Bundle Builder Lite / Add-ons**
  - Deducts inventory from individual component products when an order is placed.
- **Prebuilt (Create Product)**
  - Creates a separate product/SKU.
  - Inventory is tracked on the bundle product, not individual components.
- **Prebuilt (Link to Existing)**
  - Uses inventory of the linked existing product.
- **Prebuilt (No Product)**
  - No standalone product created; inventory is deducted from individual components.

### Overselling Prevention (Prebuilt “Create Product”)

If your bundle contains multiple products with different stock levels:

- Set the bundle product’s inventory to the lowest stock level among its components.

Example:  
Bundle includes Product A (50 units) and Product B (30 units)  
→ Set bundle inventory to 30 to avoid overselling B.

---

## Analytics & Performance Tracking

IMAGE PLACEMENT MARKER #23  
[Insert: Screenshot of Analytics dashboard]  
Caption: “Bundle performance overview in Dynamatic”

### Viewing Bundle Performance

If your app includes an analytics area (for example, **Dynamatic → Bundles → Analytics**), you can typically view:

- Total bundle sales
- Average bundle value
- Conversion rate by bundle type
- Top-performing bundles

### Key Metrics to Monitor

| Metric            | What It Tells You                                | Typical Healthy Range |
|-------------------|--------------------------------------------------|------------------------|
| Bundle Take Rate  | % of visitors who purchase bundles               | 5–15%                 |
| AOV Lift          | Increase in order value driven by bundles        | 15–40%                |
| Bundle Conversion | % of bundle views that result in a purchase      | 3–8%                  |

### Integrating with Shopify Analytics

Bundle sales appear in Shopify Analytics:

- **Sales by Product** – For Prebuilt bundles created as products.
- **Sales by Discount** – If you use discount-based bundles.

---

## Mobile Experience

All bundle types are mobile-responsive by default.

IMAGE PLACEMENT MARKER #24  
[Insert: Side-by-side screenshots showing desktop vs. mobile bundle display]  
Caption: “Bundles adjust layout automatically for smaller screens”

### Automatic Responsiveness

- Grid layouts adapt from 4-column to 2-column to 1-column.
- Buttons and inputs are touch-friendly.
- Carousels support swipe gestures (where enabled).

### Mobile-Specific Tips

- Test on real devices, not just browser simulators.
- Keep titles and descriptions short to avoid wrapping.
- Limit product counts or categories where possible.
- Ensure tap targets are at least 44×44 px for usability.

---

## Troubleshooting Guide

### Bundle Not Appearing on Storefront

**Symptoms:** Bundle is active in app but invisible on the site.

**Solutions:**

1. Verify the **App Embed** is enabled (see [Setup](#2-enable-the-dynamatic-bundles-script)).
2. Confirm the bundle status is set to **Active**.
3. Check if the bundle is scheduled for a future date.
4. Confirm you are viewing the correct theme (Live vs. Draft).
5. Clear browser cache and, if applicable, theme cache.
6. For Section Bundles, ensure the section/block is added to the correct template.

IMAGE PLACEMENT MARKER #21  
[Insert: Screenshot showing App Embed toggle in OFF position with visual indicator]  
Caption: “If your bundle isn't appearing, check that this toggle is ON”

IMAGE PLACEMENT MARKER #22  
[Insert: Flowchart diagram for troubleshooting "Bundle Not Appearing"]  
Caption: “Quick decision tree for bundle visibility issues”

### Discount Not Applying at Checkout

**Symptoms:** Bundle shows on the page, but discount is missing or incorrect.

**Solutions:**

1. Check for conflicting Shopify discount codes or automatic discounts.
2. Verify the discount rules are configured correctly in the bundle.
3. Ensure minimum quantity thresholds are met in the cart.
4. Confirm that the customer matches audience restrictions (tags, country).

### Products Not Showing in Bundle

**Symptoms:** Bundle widget shows but some products are missing.

**Solutions:**

1. Ensure products are **published** and available in the online sales channel.
2. Confirm they are in stock (inventory > 0).
3. If using collection-based or feed-based bundles:
   - Check that products belong to the correct collection.
   - Verify feed rules are not excluding them.
4. Verify any location-based or tag-based restrictions.

### Cart Transform Issues

**Symptoms:** Items not grouping correctly or cart display looks wrong.

**Solutions:**

1. Switch temporarily to **Multi BAP** to diagnose behavior.
2. Check for theme customizations or cart drawer apps that might override cart rendering.
3. Test in a Shopify default theme (e.g., Dawn) to isolate theme issues.
4. Contact support with:
   - Theme name/version
   - Screenshots of the cart
   - Bundle configuration details

---

## Frequently Asked Questions

### General Questions

**Q: Can I use multiple bundle types on the same product page?**  
A: Yes, you can combine Add-ons with other bundle types. Avoid placing more than one complex Bundle Builder on the same page to prevent confusion or layout issues.

**Q: Do bundles work with subscription products?**  
A: Subscription product support may be limited. If you use a subscription app, test thoroughly or contact support for recommended setups.

**Q: Can customers use discount codes with bundles?**  
A: This depends on your Shopify discount configuration. In many setups, bundle discounts and discount codes can stack, but store-wide discount rules may override stacking. Always test with your own discount settings.

**Q: What happens if a bundle product goes out of stock?**  
A: That product becomes unavailable for selection. The bundle remains active with remaining items, unless your rules require that product.

**Q: Can I duplicate an existing bundle?**  
A: Yes. In the bundle list, click the options menu (for example, three dots) next to a bundle and choose **Duplicate**.

### Technical Questions

**Q: Does the app affect page load speed?**  
A: Dynamatic is optimized for performance and typically has minimal impact. Actual performance may vary depending on theme complexity and installed apps.

**Q: Are bundles compatible with headless Shopify setups?**  
A: Limited compatibility may be available via APIs. Contact support for details.

**Q: Can I use bundles with Shopify POS?**  
A: Prebuilt bundles created as real products usually work with POS. Other bundle types are primarily for online storefronts.

---

## Extended Glossary

| Term               | Definition                                                                 |
|--------------------|----------------------------------------------------------------------------|
| AOV                | Average Order Value                                                        |
| App Embed          | Shopify feature allowing apps to inject code into the theme               |
| BAP                | “Bundle as Product” cart behavior                                         |
| Cart Transform     | Option grouping bundle items under a single cart line                     |
| Multi BAP          | Option displaying each bundle item as a separate cart line                |
| Product Feed       | Dynamic product list based on filters/rules (collection, tags, price, etc.)|
| Section            | A configurable block in Shopify themes                                   |
| Tiered Discount    | Discount structure where savings increase at certain quantity thresholds |
| Trigger Product    | Product whose page loads an Add-ons Bundle widget                        |
| Full Page Bundle   | Bundle with its own dedicated landing page URL                           |
| Section Bundle     | Bundle embedded inside an existing page via Theme Editor                 |

---

## Known Limitations

> Adjust the concrete limits below to match your actual app constraints.

| Limitation                 | Details                                                             |
|---------------------------|---------------------------------------------------------------------|
| Max products per bundle   | e.g., 50 products                                                   |
| Max categories per bundle | e.g., 10 categories                                                 |
| Subscription products     | May not be fully supported; test or consult support                |
| Digital products          | Supported with some limitations around fulfillment flows           |
| B2B pricing               | Uses Shopify’s customer-specific pricing when available            |

---

## SEO for Bundle Pages

### Full Page Bundles

- Customize the page title and meta description in bundle settings if supported.
- Ensure URLs follow a meaningful structure, such as:  
  `https://yourstore.com/pages/bundle-name`
- Link bundle pages from your navigation, collection pages, or campaigns.

### Best Practices

- Use descriptive, keyword-rich bundle names (e.g., “Vegan Snack Box – 10 Pack”).
- Write unique bundle descriptions; avoid duplicating product descriptions.
- Add alt text for all bundle images (especially hero and category images).

---

## International Stores

### Multi-Currency

- Bundle prices typically convert based on Shopify Markets or currency settings.
- Percentage discounts usually convert smoothly; fixed-amount discounts should be tested in multiple currencies.

### Multi-Language

- Bundle names and descriptions generally support Shopify’s translation features.
- Translate via **Shopify Admin → Settings → Languages**, or your translation app.
- Verify all bundle texts (titles, buttons, success messages) are translated as expected.

---

## Getting Help

### Self-Service Resources

- Video tutorials: *(link if available)*
- Knowledge base: *(link if available)*
- Community forum: *(link if available)*

### Contact Support

- Email: `support@dynamatic.com` (replace with your real support email)
- In-app chat: If available, via the Dynamatic app interface
- Usual response time: Within 24 hours during business days

When contacting support, include:

1. Your store URL
2. The bundle name and/or ID
3. A clear description of the issue
4. Screenshots (storefront, cart, and bundle settings)
5. Theme name and version

---

## Document Version History

| Version | Date       | Changes                            |
|---------|------------|-------------------------------------|
| 1.0     | YYYY-MM-DD | Initial GitHub README documentation|

For app feature changes and release notes, see the app’s changelog (link if available).
