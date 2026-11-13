# Experiment 11 — Performance Optimization

- `style.min.css` and `app.min.js` are compact production-style assets.
- Images below the fold use `loading="lazy"`.
- `_headers` provides an example of long-lived cache headers for fingerprinted static assets. In production, version asset filenames before applying immutable caching.
- Compare before/after with Lighthouse and DevTools Network; record real measurements from your deployment.
