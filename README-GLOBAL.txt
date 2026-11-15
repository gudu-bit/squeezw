SQUEEZE — GLOBAL-READY STATIC WEBSITE

Included:
- index.html with international-friendly metadata, social sharing tags, structured data,
  crawlable service descriptions and FAQs.
- robots.txt allowing search engines to crawl the site.

BEFORE DEPLOYING
1. Choose and connect your own domain (preferably a memorable .com if available).
2. Deploy this folder as a static site on a host with a global CDN (for example, Cloudflare Pages,
   Netlify or Vercel).
3. After the domain is connected, add a canonical URL tag to index.html:
   <link rel="canonical" href="https://YOUR-DOMAIN/">
   Replace YOUR-DOMAIN with your real domain. Do not leave the placeholder.
4. Create sitemap.xml using your real domain, with your live public URLs, then submit it in
   Google Search Console and Bing Webmaster Tools.
5. Verify the domain in Google Search Console. Submit the sitemap and inspect the homepage.
6. Set up analytics with a privacy notice appropriate to the countries you serve.
7. Test the site from mobile and desktop browsers in multiple regions.

IMPORTANT LIMITATIONS
- This update improves international SEO foundations; it cannot guarantee first place in Google.
- Search engines decide indexing and ranking. New sites can take days or weeks to be indexed,
  and meaningful rankings can take months.
- This is still a single-page static app. For competitive global SEO, build separate,
  useful landing pages for each real tool (image compressor, PDF compressor, etc.) with unique
  content and working canonical URLs.
- Video/audio and some document conversions depend on browser support. Do not advertise
  unsupported formats as guaranteed.
- A global CDN improves delivery speed but does not guarantee availability in every country.
