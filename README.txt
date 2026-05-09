# Static Site Export
Generated: 2026-05-09

## File Structure

  index.html             Home page
  {page-slug}/
    index.html           Additional pages

## Deployment

Netlify / Vercel  — Drop this folder on their dashboard.
GitHub Pages      — Push contents to a repo and enable Pages.
Any static host   — Upload to any web server or CDN.

## Notes

Pages load Tailwind CSS from https://cdn.tailwindcss.com (development CDN).
For production, replace the CDN <script> with a compiled stylesheet.
Images reference URLs from your original host — re-upload media as needed.
