
# softhoarders.me && soft-hoarders.com

A single-page static website for Soft Hoarders — the FTC Robotics team from Craiova, Romania. The site presents the team's mission, achievements, upcoming events, sponsors, and team roster.

## What this site contains
- [index.html](index.html) — page structure and content
- [styles.css](styles.css) — styles (cacheable, separate from HTML for faster load)
- [main.js](main.js) — interactions, i18n, lazy map/results (deferred)
- [images/robot.webp](images/robot.webp) — optimized hero robot image (~96KB)
- [images/logo.webp](images/logo.webp) — optimized header logo (~4KB)
- [LICENSE](LICENSE) — project license

## Purpose
The site documents Soft Hoarders' activities and achievements and serves as a public-facing hub for the team and community. It highlights:
- Team background and mission
- Recent achievements and competition results
- Upcoming events and timeline
- Sponsors and supporters
- Contact information and community resources

## Quick start
No build tools are required. To view the site locally, simply open [index.html](index.html) in any modern web browser.

Optional: serve with a static server for local development (example using Python 3):

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

## Team
Soft Hoarders is FTC Robotics Team 12560 based in Craiova, Romania. According to the site metadata, the team has been active since 2016 and qualified for the European Premier Event 2025.

For the full team roster, roles, and bios, please see the Team section in [index.html](index.html).

## Contributing
- Suggest edits by opening a pull request with changes to `index.html` and this `README.md`.
- For content updates (roster, events, sponsors), update the corresponding sections inside `index.html`.

## Contact
Contact details and social links are available on the site itself — check the footer of [index.html](index.html) for the preferred channels.

## Google Ad Grants notes
The site includes About and Programs sections, clear navigation, CTAs, and performance optimizations (lazy-loaded map/API, local WebP hero image). After deploying, rerun [PageSpeed Insights](https://pagespeed.web.dev/) on mobile before resubmitting your Ad Grants activation request.

## License
See [LICENSE](LICENSE) for license and usage terms.
