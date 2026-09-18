# Hands-of-Hope-Community-Outreach-charity-website-
A website for hands of hope charity, to but reach more users.
## Changelog

### Part 2 — CSS Styling & Responsive Design (2026-09-18)

**Feedback from Part 1:**
No corrective changes were required. Part 1 was approved as submitted, so the
HTML structure, content, navigation, and file/folder layout carry forward into
Part 2 unchanged.

**Changes made in this phase:**

- Created a single external stylesheet, `css/style.css`, and linked it
  identically in `<head>` on all five pages (`index.html`, `about.html`,
  `services.html`, `enquiry.html`, `contact.html`).
- Established a base style layer: `box-sizing: border-box` reset, a shared
  colour system defined as CSS custom properties (deep teal, burnt clay,
  ochre accent, warm paper background), and a consistent type and spacing
  scale.
- Applied typography styling — `font-family`, fluid `font-size` via
  `clamp()`, `line-height`, and `font-weight` — to headings and body text.
- Built the page layouts with a mix of Flexbox (navigation bar, hero
  actions, buttons) and CSS Grid (two- and three-column content sections,
  the stats strip, and the footer).
- Styled decorative elements: card borders, subtle `box-shadow`, form field
  styling, and button variants (`btn--primary`, `btn--outline`,
  `btn--outline-dark`).
- Added interactive states using pseudo-classes (`:hover` on links and
  buttons, `:focus-visible` on all interactive elements for keyboard
  accessibility).
- Implemented responsive design: relative units throughout, and media
  queries at 640px, 700px, 780px, and 820px covering the navigation menu,
  hero layout, grid columns, stats strip, and footer.
- Replaced the two elements that would otherwise have needed JavaScript
  with pure-CSS equivalents, since JavaScript functionality is scoped to
  Part 3 of this project:
  - Mobile navigation menu now uses a CSS-only checkbox/label toggle.
  - The FAQ accordion on the homepage now uses native
    `<details>`/`<summary>` elements.
- Replaced two corrupted image assets (`images/mark-steam.svg` and
  `images/hero-table.svg`) that had been saved as HTML error pages instead
  of valid SVG markup, with original hand-built SVG illustrations matching
  the site's colour palette.
- Confirmed all form fields on `enquiry.html` and `contact.html` rely on
  native HTML5 validation attributes (`required`, `pattern`, `minlength`)
  rather than JavaScript, consistent with the current project phase.

  ## References

freeCodeCamp.org (2018) *CSS Full Course – Includes Flexbox and CSS Grid Tutorials*. [Online video]. Available at: https://www.youtube.com/@freecodecamp (Accessed: 25 August 2026).

Net Ninja, The (2019) *HTML & CSS Crash Course*. [Online video]. Available at: https://www.youtube.com/@NetNinja (Accessed: 25 August 2026).

Powell, K. (2021) *Learn CSS Grid the Easy Way*. [Online video]. Available at: https://www.youtube.com/watch?v=rg7Fvvl3taU (Accessed: 25 August 2026).

Powell, K. (2022) *The Secret to Mastering CSS Layouts*. [Online video]. Available at: https://www.youtube.com/kevinpowell (Accessed: 26 August 2026).

Traversy, B. (2017) *CSS Grid Layout Crash Course*. [Online video]. Available at: https://www.youtube.com/@TraversyMedia (Accessed: 26 August 2026).

Cook, K. (2018) *Learn CSS in 20 Minutes*. [Online video]. Available at: https://www.youtube.com/c/webdevsimplified (Accessed: 26 August 2026).

Ai was used the better enhanced the code and styling
