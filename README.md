# Skynet Eats – Accessible Landing Page

A grocery delivery landing page rebuilt to meet WCAG accessibility guidelines.
The starting point was an intentionally inaccessible page from Scrimba's
accessible web development course. Every lesson became its own issue, branch
and pull request, so the commit history doubles as a log of the fixes.

## What was fixed

- **Semantic structure.** Replaced generic wrappers with `nav`, `main`,
  `section` and `footer` landmarks, and put the heading levels in order.
- **Colour contrast.** Reworked the greens so every text and background
  pairing meets the AAA contrast ratio.
- **Images.** Added descriptive alt text to content images.
- **Links.** Made link text descriptive on its own and gave links a
  non-colour visual cue.
- **Forms.** Added visible labels, accessible placeholders and a real
  submit button to the sign-up form.
- **Lists.** Marked up navigation, statistics and social links as lists so
  screen readers announce item counts.
- **Scalable type.** Converted font sizes from px to rem so text respects
  the user's browser settings.
- **Keyboard navigation.** Added a skip link that appears on focus and jumps
  straight to the main content.
- **Responsive layout.** The page reflows on narrow screens instead of
  overflowing.

## Run it locally

```
npm install
npm run dev
```

Vite serves the page at http://localhost:5173.

## Built with

HTML, CSS and Vite. No frameworks.

## Course

Built while working through Scrimba's
[Fullstack Developer Path](https://scrimba.com/fullstack-path-c0fullstack).
The starter code is Scrimba's; the fixes are mine.
