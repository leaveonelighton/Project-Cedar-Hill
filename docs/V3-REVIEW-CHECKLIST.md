# Website V3 QA Checklist

Production verification completed August 13, 2026.

- [x] Homepage identity is Leave One Light On, not The Light in the Window.
- [x] Metallic gold appears premium and restrained; no distracting sparkle.
- [x] Reduced-motion preference disables decorative animation.
- [x] The book site link routes to https://thelightinthewindowbook.com/.
- [x] Keep the Light On is presented as an invitation/action, not the movement name.
- [x] No page claims current 501(c)(3) recognition or tax-deductibility.
- [x] Story, House, and Gormans pages use consistent V3 navigation/footer.
- [x] Find Help language does not imply clinical/crisis treatment by the organization.
- [x] Contact page uses movement identity and the tested contact mailbox.
- [x] Legacy `book.html` and `resources.html` routes redirect to their current destinations; no placeholder `#` links remain on upgraded pages.
- [x] Desktop visual QA complete.
- [x] Mobile/responsive QA complete.
- [x] Images verified after Hostinger deployment.
- [x] Owner approved the production changes before their respective merges.
- [x] `robots.txt` and the nine-page `sitemap.xml` return HTTP 200.
- [x] Google Search Console processed the current sitemap successfully and discovered nine pages.

## Production route verification

- `/` and `/index.html` return HTTP 200.
- `/book.html` returns HTTP 301 to `/books.html`.
- `/resources.html` returns HTTP 301 to `/find-help.html`.
- All nine canonical V3 pages return HTTP 200.
- The external book, 988 Lifeline, and 211 destinations return HTTP 200.
