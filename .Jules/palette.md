## 2025-10-26 - Quantity Adjustment Button ARIA Labels
**Learning:** Icon-only buttons for quantity adjustment (+ and -) in shopping carts are unannounced or poorly read by screen readers unless explicit ARIA labels in the application's locale are provided.
**Action:** Always include localized `aria-label` attributes on icon-only quantity control buttons (e.g., `aria-label="تقليل الكمية"` and `aria-label="زيادة الكمية"`).
