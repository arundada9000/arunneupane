# Changelog

All notable changes to this project will be documented in this file.

## [2.0.1] - 2026-09-11

### Fixed
- Empty `for` attribute on the contact form Message label (now points to `User-message`)
- Scroll-spy crash when scrolling through sections without a nav link (`qualification`, `project`, `testimonial`); query results are now null-guarded
- Preloader removal was delayed 4s after its fade-out; reduced to 600ms
- Removed dead `submitButton` lookup that never matched (submit button is a `<button>`, not `<input type="submit">`)
- Added `.gitignore` so editor-local config (`.claude/`, `.vs/`, `.vscode/`) stays out of the repo
- "Stay & Browse" modal button was unstyled; `.button` now resets native button defaults (`border`, `font-family`, `cursor`), fixing all `<button>` elements
- Removed now-redundant inline `border`/`cursor` styles on the contact submit button
- Contact form Name, Email, and Subject inputs now `required`, preventing submissions with only a message

### Added
- Dedicated 1200x630 Open Graph social card (`og-social.png`) for consistent link previews
- `og:image:width`, `og:image:height`, `og:image:alt` meta tags
- `twitter:site` and `twitter:image:alt` meta tags
- JSON-LD Person updated: `worksFor` (Sajilo Digital), `affiliation` (Code for Change Rupandehi), current `jobTitle`, expanded `knowsAbout`
- Descriptive `alt` on About image; corrected Portfolio 4 alt to "Stack Visualization"

### Changed
- Removed stale `arunneupane20` keyword; keyword list updated
- Qualification updated to completed BSc.CSIT degree
- Em dashes replaced across HTML and docs (style: no em dashes, no emojis)
- Completed BSc.CSIT updated in qualification section and AUTHOR.md

## [2.0.0] - 2026-09-11

### Added
- Old-portfolio notice modal on page load with link to [current portfolio](https://arunneupane.vercel.app)
- "Current Portfolio" navigation link with NEW badge
- "Current Portfolio" footer link
- LinkedIn, X/Twitter, and YouTube social links (home + footer)
- `domain` field auto-appended to contact form submissions for origin tracking
- Open Graph and Twitter Card meta tags for rich social previews
- JSON-LD Person structured data for search engines
- Canonical URL meta tag
- `robots`, `author` meta tags
- Escape-key and overlay-click dismiss for the notice modal
- Body scroll lock while modal is open

### Fixed
- Facebook URL corrected from `arunneupane9000` to `arundada9000` (home + footer)
- Nav grid updated from 3-column to 4-column to accommodate 7 nav items
- Copyright year updated to 2026

### Changed
- Page title updated to reflect archived status
- Meta description rewritten with current portfolio context
- Sitemap lastmod updated

## [1.0.0] - 2025-01-01

### Added
- Initial release
