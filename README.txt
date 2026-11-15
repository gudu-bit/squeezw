SQUEEZE — DEPLOYMENT PACKAGE

Files:
- index.html: the complete static website.

Deploy on Vercel:
1. Open https://vercel.com/new
2. Choose the option to deploy a static project or import a Git repository.
3. Put index.html in the project root (or upload this folder through a Git repository).
4. No build command is required; set the output directory to the project root (.).
5. Deploy.

Deploy on Netlify:
1. Open https://app.netlify.com/drop
2. Drag the extracted squeeze-deploy folder onto the page.
3. Netlify will publish the static site and provide a public URL.

Notes:
- The site uses browser-side processing and CDN-hosted libraries, so an internet connection is needed to load those libraries.
- MP3 encoding uses the LAME JS library loaded from a CDN.
- Browser support varies by file codec. Current Chrome or Edge is recommended.
- The 300 MB per-file limit is a safety guard against browser memory exhaustion.
- PDF-to-Office conversions are text-based and do not preserve full layout.
- PDF compression rasterizes pages, which can remove searchable text and vector content.
- This is a static front-end project; it does not include a backend, accounts, cloud storage, analytics, or server-side conversion.
