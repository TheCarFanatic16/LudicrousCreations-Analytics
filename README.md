# LudicrousCreations Analytics

Internal pageview + engagement dashboard for the
[LudicrousCreations website](https://github.com/TheCarFanatic16/LudicrousCreations).
Deployed separately from the main site via its own GitHub Pages.

- **Live dashboard:** see repo Settings -> Pages for the URL once enabled.
- Plain HTML/CSS/JS, no build step, no framework.
- Reads pageview and engagement-bucket counters written client-side by
  `js/analytics.js` and `js/product-analytics.js` in the main site repo,
  via a free, no-account counter API (abacus.jasoncameron.dev).
- No cookies, no personal data -- anonymous counts only.
- The page is `noindex` and isn't linked from the main site's navigation,
  but the URL itself is not access-controlled -- anyone with the link (or
  who guesses the counter namespace) can view it. Treat the link as
  "unlisted," not "private."
