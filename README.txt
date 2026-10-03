REDLINERS PERFORMANCE — WEBSITE
================================

UPLOAD (chiptuningnis.com)
  Upload EVERYTHING in this folder to the web root (public_html / www),
  keeping the structure exactly:
      index.html
      css/   (tailwind.css)
      js/    (car3d.js, fx.js, i18n.js, process.js, vendor/...)
      img/   (all photos, partners/, work/)
  index.html will NOT work on its own — it needs these folders next to it.

TEST ON YOUR COMPUTER
  Unzip, open the folder, double-click index.html.
  (Or use the single file redliners-performance.html — everything is built in.)

BOOKING E-MAILS (one-time activation)
  Inquiries go to redliners.mms@gmail.com via FormSubmit.
  After uploading, send one test booking from the LIVE site, then click
  "Activate Form" in the e-mail FormSubmit sends you (check Spam).
  Sending from a file opened on your computer may be refused by FormSubmit —
  always test on the live site.

WHERE TO EDIT
  Texts (Serbian / Bulgarian) ... js/i18n.js
  English texts ................. index.html
  Process console lines ......... js/process.js
  Photos ........................ img/

SEO (search engines)
  Upload the WHOLE folder, including:
      sr/index.html  bg/index.html   (Serbian & Bulgarian pages Google can index)
      robots.txt  sitemap.xml        (must sit in the web root)
  Then in Google Search Console (search.google.com/search-console):
      add chiptuningnis.com → Sitemaps → submit  sitemap.xml
  Language pages: https://chiptuningnis.com/sr/  and  https://chiptuningnis.com/bg/
