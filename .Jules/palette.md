## 2025-05-20 - Localized ARIA Labels for Icon-Only Buttons
**Learning:** Icon-only buttons (such as quantity increase/decrease buttons with Lucide icons) in localized single-page JavaScript apps require explicit localized `aria-label` attributes in the application's primary language (Arabic) to ensure screen reader users receive actionable context.
**Action:** When adding or modifying interactive controls with icon-only inner HTML in `app.js`, always include descriptive, localized `aria-label` attributes.
