---
"@shopify/hydrogen": patch
---

Clarify in the skills that `ShopifyScripts` `i18n.currency` must be set when Shopify analytics is enabled. The hosted analytics script drops every event, including `page_viewed`, until `window.Shopify.currency.active` exists.
