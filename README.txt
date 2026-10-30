Peace's portfolio — static site

Upload the whole folder (index.html + photos/) to any static host:
GitHub Pages, Netlify, Vercel, Cloudflare Pages, or a plain web server.
Keep index.html and the photos/ folder side by side.

Notes
- Everything is a single HTML file plus images. three.js loads from cdnjs and fonts from Google Fonts.
- Features that depend on the claude.ai runtime (AI Assistant, in-page message storage, vCard download)
  fall back automatically when self-hosted: the Assistant answers from built-in facts, "Save contact" copies
  details to the clipboard, and Mail hands off to the visitor's own mail app.
- Contact details live in the CONTACT block near the top of the script in index.html.
- Optional: set CONTACT.sendEndpoint to a Formspree (or similar) form URL to receive messages server-side.
