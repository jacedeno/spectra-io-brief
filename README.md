# Spectra-IO Sales Brief

Bilingual single-page sales presentation for **Spectra-IO** — wireless vibration monitoring
and FFT diagnostics for heavy industry. A product by [excemca.com](https://excemca.com) ·
[GeekendZone](https://geekendzone.com).

**Live:**
- English: https://jacedeno.github.io/spectra-io-brief/
- Español: https://jacedeno.github.io/spectra-io-brief/es/

## Structure

```
index.html      English version (self-contained: inline CSS + SVG diagram)
es/index.html   Spanish version (faithful, idiomatic — not literal)
images/         All assets, committed locally (no hotlinking)
```

Both pages share the same 10-section structure and visual system (warm paper background,
brand-blue identity color `#1d5fd6`, orange accent for card tags, navy for links). Print
styles are included, so either page can be saved as a PDF handout.

## Updating app screenshots

Screenshots come from the live app with branding edits injected **in the browser session
only** (the live site is never modified):

1. Log in at `spectra.excemca.com` (email + one-time code).
2. Before each capture, hide the `by MRI` span and any element containing the logged-in
   email (DOM `display:none` injection).
3. Desktop shots at 1920×1080: overview, sensor detail (FFT / trend / waveform), alerts.
   Mobile shots at 390×844. Featured sensor: one with rich spectral content.
4. Review every capture for customer-identifying names or PII before committing.

## Image credits

- Industrial stock photos: [Unsplash](https://unsplash.com) (Unsplash license — free for
  commercial use).
- Sensor, installation, and gateway-panel photos: Excemca — real production installation.
- Contact: **cedenoj@excemca.com** (do not use personal addresses in this repo).
