# Investiiq Tools Website

Production-ready static web tools platform for deployment at `/public_html/tools/` on Hostinger shared hosting.

## Folder Structure

- `index.html` homepage
- `components/` reusable header/footer partials
- `assets/css/app.css` theme styles
- `assets/js/app.js` shared logic for all tools
- `tools/` tool pages (image, text, SEO, finance, PDF UI)
- `pages/` About, Contact, Privacy, Cookies, Terms
- `blog/index.html` blog listing layout
- `sitemap.xml`, `robots.txt`

## Deployment (Hostinger cPanel)

1. Zip repository contents.
2. Open **File Manager** in Hostinger.
3. Upload and extract into `public_html/tools/`.
4. Ensure URL serves from `https://tools.investiiq.com/tools/`.
5. Submit `https://tools.investiiq.com/tools/sitemap.xml` in Google Search Console.
6. Connect AdSense code to placeholders once approved.

## Notes

- All current image/text/SEO/finance tools process in-browser.
- PDF suite is UI + architecture-ready (backend can be connected later).
- Designed for mobile-first performance and AdSense policy compliance.
