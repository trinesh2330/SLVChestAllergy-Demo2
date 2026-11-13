S.L.V Chest & Allergy Clinic — Hostinger production package (Step 41 — final consolidation)

UPLOAD
1. Back up the current Hostinger public_html folder before replacing anything.
2. Confirm the correct document root in Hostinger hPanel.
3. Enable a valid SSL certificate before relying on the HTTPS redirect in .htaccess.
4. Upload the CONTENTS of this ZIP directly into public_html. index.html should be directly inside public_html, not inside an extra nested folder.
5. Keep .htaccess in the document root. This package includes ErrorDocument 404 /404.html for Apache/LiteSpeed hosting.

AFTER UPLOAD
- Open each page and check images, navigation, and contact links.
- Visit a deliberately invalid URL (for example /this-page-should-not-exist) and confirm the custom 404 page appears AND the response status is HTTP 404.
- Check HTTPS, redirects, and response headers in a browser/network inspection tool.
- Confirm the clinic's address, phone, email, hours, doctor credentials, services, equipment, awards, and privacy wording with the clinic.
- Submit sitemap.xml to Google Search Console after the site is approved and live.

SCOPE / LIMITATIONS
- Static website only. No online appointment form or booking backend is included.
- .htaccess is intended for Apache/LiteSpeed; it is not used by GitHub Pages or every hosting platform.
- This package has not been deployed or live-server tested. It is not a penetration-test certification.
