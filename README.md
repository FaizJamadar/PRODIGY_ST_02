# Task 02 — Compatibility Testing

**Track:** Software Testing (ST) — Prodigy InfoTech Internship
**Application Under Test:** [Shoplane E-commerce Website](https://shoplane-by-lassie.netlify.app/)

## What I did
Tested the site's homepage, navigation, cart, and checkout flow across Chrome, Firefox, and a mobile viewport to check for layout and functional consistency.

## Bugs Found
1. **Broken navigation links** — Clicking "CLOTHING" or "ACCESSORIES" in the nav bar leads to a 404 page in all browsers.
2. **Missing search bar on mobile** — The search bar is fully visible on desktop but disappears entirely on mobile viewports, with no alternative (like a search icon).
3. **Inconsistent product image alignment** — Product grid images show alignment/spacing issues in Chrome (2 images affected) and Firefox (1 image affected), but align correctly on mobile.

## Coverage
- Chrome (Desktop) — Tested
- Firefox (Desktop) — Tested
- Mobile viewport — Tested
- Safari — Not tested (no Safari environment available)

## Files
- `CompatibilityTestCases.xlsx` — full test case documentation with actual results and pass/fail status
