# Suji Science / Results

Goal: Add a standalone responsive Shopify section matching Pencil Group 9 desktop and Mobile Science, without altering Horizon, store themes, or homepage templates.

Scope: `sections/suji-science-results.liquid` only for implementation. Merchant-selectable product images, editable headings, CTA, references, and metric blocks grouped by research category. The user adds it through the Theme Editor.

- [x] Map desktop/mobile layout and Skeleton conventions. Evidence: Pencil `CERgJ`, `QwjWt`; `assets/critical.css` constrains section content unless `.full-width`.
- In progress: implement the standalone section.
- [x] Implement Liquid, schema/preset, and responsive CSS in one independent section. Blocks: metric with category, study label, value, and description; section settings: product images, headings, CTA, source notes. Evidence: `sections/suji-science-results.liquid` created.
- [x] Verify schema and section structure, report any unrun storefront checks, and hand off editor setup. Evidence: schema JSON parsed with unique section IDs and four default metrics (two per category); `shopify theme check --path /Users/diegodq/Documents/dev/assessment-skeleton` passed with 41 files inspected and zero offenses. Storefront visual checks remain for the user to perform in the Theme Editor.

Constraints: The Skeleton directory has no Git repository, so no branch/commit was possible without separately initializing Git. No Shopify pull/push/publish or development-theme command was run. Live desktop/mobile preview and image/editor settings are pending user verification.
