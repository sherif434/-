## 2026-03-06 - Accessible Labels on Dynamic Cart Quantity Controllers
**Learning:** Dynamic HTML template strings generating icon-only quantity buttons (+/-) frequently omit `aria-label` attributes, rendering cart quantity controls inaccessible to screen reader users in localized UI environments.
**Action:** Always include localized `aria-label` attributes (`aria-label="إنقاص الكمية"` / `aria-label="زيادة الكمية"`) on icon-only quantity controller buttons rendered dynamically in JavaScript templates.
