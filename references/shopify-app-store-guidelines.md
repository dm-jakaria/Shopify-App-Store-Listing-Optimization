# Shopify App Store Listing Guidelines & Compliance Reference

This document outlines official constraints, character limits, policy rules, and formatting best practices for publishing and optimizing listings on the Shopify App Store, based on [Shopify Dev Documentation](https://shopify.dev/docs/apps/launch/shopify-app-store/best-practices).

---

## 1. Official Character Limits & Field Specifications

| Asset / Field | Official Character Limit | Search & Conversion Priority | Compliance Rules |
| :--- | :--- | :--- | :--- |
| **App Name** | **Max 30 characters** (hard limit) | **Top Ranking Priority** | Must lead with your unique brand name. Format: `[Brand Name] [Descriptor]`. Never lead with a generic word or integration partner name. Do not include "Shopify". |
| **App Card Subtitle** | **Max 62 characters** (hard limit) | **Top Ranking Priority** | Must be a complete sentence highlighting the merchant outcome. High search weighting. Do not repeat title words. |
| **App Introduction** | **Max 100 characters** (hard limit) | **Top Conversion Priority** | First text under featured image. Explains what the app does and who it helps. Avoid keyword stuffing or incomplete sentences. |
| **App Details (Overview)** | **Max 500 characters** (hard limit) | **Medium Priority** | Concise problem-solution overview. Clear functional explanation. Fluff-free. |
| **Feature List (up to 5)** | **Up to 5 features, max 80 chars each** | **Medium Priority** | Describe functionality and merchant value, not underlying software mechanics (e.g. React/GraphQL). |
| **Search Terms** | **Up to 5 search terms** | **Top Ranking Priority** | Entered in Partner Dashboard. Single concept per term. Complete words only. Never duplicate words in the App Name. |
| **Integrations** | **Up to 6 tools / apps** | **Search & Trust Signal** | Only list tools you directly integrate with. Never list Shopify itself. |
| **Google Title Tag** | **55 - 60 characters** | **Off-Platform SEO** | Optimized for Google and AI search engines (ChatGPT, Claude, Perplexity). |
| **Google Meta Description** | **150 - 160 characters** | **Off-Platform SEO** | Compelling summary of the app's value proposition for Google search snippets. |

---

## 2. Storefront Performance & Speed Requirements

Apps that impact the storefront are subject to strict automated Lighthouse performance testing before approval:

### Weighted Scoring Architecture:
Shopify tests the app's effect on store performance by measuring Lighthouse scores before and after app installation across three core pages:

| Page Tested | Weight in Overall Score |
| :--- | :--- |
| **Product Details Page** | **40%** |
| **Collection Page** | **43%** |
| **Homepage** | **17%** |

- **Threshold**: An app must not reduce the store's Lighthouse performance score by more than **10 points**.
- **Storefront Impact**: Render delay must remain under **50ms**.
- **Extension Architecture**: Must use **Theme App Extensions (App Blocks & App Embeds)** so that uninstalling removes 100% of app assets with zero orphaned liquid code.

---

## 3. Checkout Extension & Deceptive Design Rules

All apps extending Shopify Checkout must adhere to strict anti-deceptive UX guidelines:
1. **Optional Charges Must Be Off by Default**: Any additional fee, tips, or shipping protection cannot be pre-selected or disguised as an opt-out gift.
2. **Charges Must Be Itemized**: Extra charges must be clearly visible and itemized on the storefront, cart, and checkout.
3. **Lowest Shipping Price by Default**: Shipping options must default to the lowest-priced option, never the most expensive.

---

## 4. Brand & Trademark Compliance

- **No Unauthorized Use of "Shopify"**: Do not include "Shopify" in the app title. If describing compatibility, use `{Brand Name} Integration for {Platform}`.
- **No Superlatives**: Banned phrases include "#1 App", "Best App", "Shopify's Favorite", or "Guaranteed 10x ROI".
- **Transparent Billing**: Enterprise plans and external charges must be disclosed in the "Description of additional charges" section.
