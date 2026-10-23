## 2026-10-23 - Cart Quantity Control ARIA Labels
**Learning:** Dynamically generated icon-only buttons in the cart drawer (minus/plus icons) lacked `aria-label` attributes, making cart quantity adjustments non-accessible to screen reader users.
**Action:** Always ensure dynamically rendered icon-only buttons include descriptive `aria-label` attributes (e.g., `aria-label="تقليل الكمية"` and `aria-label="زيادة الكمية"`).
