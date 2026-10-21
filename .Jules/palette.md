## 2026-10-21 - Icon-only quantity buttons in Arabic ecommerce UI
**Learning:** In Arabic RTL e-commerce interfaces, quantity control buttons (+ and -) rendered with Lucide icons lack accessible text names for screen readers unless explicitly labeled with localized `aria-label`s.
**Action:** Always provide localized `aria-label="تقليل الكمية"` and `aria-label="زيادة الكمية"` attributes on icon-only quantity adjustment controls.
