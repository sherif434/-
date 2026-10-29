## 2026-10-29 - Accessible Cart Quantity Controls in Localized UI
**Learning:** Icon-only buttons in dynamically rendered cart items lack accessible names, making screen readers announce them generically or skip them. Including item titles in ARIA labels (e.g., `aria-label="إنقاص كمية ${item.product.title}"`) provides unambiguous context for assistive technology users.
**Action:** Always provide descriptive, item-specific ARIA labels for icon-only buttons created inside template literals in dynamic UI renderers.
