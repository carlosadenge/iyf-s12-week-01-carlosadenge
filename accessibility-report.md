# Accessibility Audit Report – Week 1

## Issues Found

1. **Images** – Some images were missing meaningful `alt` attributes.
2. **Headings** – Heading hierarchy needed to be clearer (one h1 → h2 → h3).
3. **Links** – Some links had non-descriptive text.
4. **Language** – Confirmed `lang="en"` is present on the `<html>` tag.
5. **Form labels** – All form inputs now have proper associated `<label>` elements.

## How I Fixed Them

- Added meaningful `alt` text to every image.
- Ensured proper heading order: one `<h1>`, then `<h2>`, then `<h3>`.
- Made all link text descriptive (e.g. “View my projects” instead of “click here”).
- Verified every form input has a matching `<label for="...">`.
- Used semantic HTML elements (`header`, `nav`, `main`, `footer`, `article`, etc.).
