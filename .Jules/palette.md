# Palette's Journal - Critical UX & Accessibility Learnings

## 2026-06-29 - Accessible Quantity Controls in Cart
**Learning:** Icon-only quantity increment/decrement buttons (`+` and `-`) in cart items lacked explicit `aria-label`s, preventing screen reader users from understanding button actions (e.g., "تقليل الكمية" / "زيادة الكمية").
**Action:** Always provide descriptive `aria-label` attributes to icon-only quantity control buttons in shopping cart components.
