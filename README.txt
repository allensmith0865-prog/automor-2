╔══════════════════════════════════════════════════════════════╗
║   AUTOMOR — WHITE-LABEL TEMPLATE — DEPLOYMENT & USER GUIDE   ║
╚══════════════════════════════════════════════════════════════╝

FILES IN THIS ZIP:
  index.html   → Complete website (everything built in)
  .htaccess    → Apache routing + HTTPS + security headers
  README.txt   → This guide

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  STEP 1 — UPLOAD TO HOSTINGER (or any cPanel hosting)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  1. Login -> hpanel.hostinger.com
  2. My Hosting -> Manage -> File Manager
  3. Open "public_html" -> delete existing files
  4. Upload: index.html + .htaccess
  5. Visit your domain -> website is live!

  OTHER HOSTS:
  - Netlify / Vercel / Cloudflare Pages: drag & drop index.html
    (hash-based routing - no extra config needed)
  - GitHub Pages: upload index.html, enable Pages

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  STEP 2 — ACCESS ADMIN / EDIT MODE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Go to:  https://yourdomain.com/#admin
  (the #admin disappears from the URL bar instantly - no trace)

  OR press:  Ctrl+Shift+A  (Windows)  /  Cmd+Shift+A (Mac)

  DEFAULT PASSWORD:  admin123

  CHANGE YOUR PASSWORD IMMEDIATELY:
  After logging in, click the "Security" button (lock icon) in
  the orange top bar -> a panel opens on the right -> enter your
  current password, then your new password (min 6 chars) ->
  click "Update Password". Done.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  HOW EDITING WORKS (Elementor-style, click-to-edit)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  1. Log into admin (#admin or Ctrl+Shift+A)
  2. An orange bar appears fixed at the top of the site
  3. Every section of every page now shows a small
     "EDIT" button (pencil icon) in its top-right corner
  4. Click any EDIT button -> a panel slides in from the right
     with all the fields for that section
  5. Make your changes -> click "Apply Changes"
  6. The page updates immediately - preview your changes live
  7. Repeat for any other section / page you want to change
  8. When finished with ALL edits, click:

         SAVE & EXPORT   (top-right of orange bar)

  9. A new "index.html" file downloads automatically with
     ALL your changes built permanently into the code
  10. Upload this new index.html to Hostinger, REPLACING the
      old one (File Manager -> public_html -> upload -> overwrite)
  11. Your changes are now PERMANENT and visible to every
      visitor - no database, no backend needed

  IMPORTANT: "Save & Export" only works on your LIVE
  deployed website (after Step 1, real hosting). It does
  not work in chat preview windows - deploy first, then edit.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  ALL EDITABLE SECTIONS - what each EDIT button controls
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  ON-PAGE EDIT BUTTONS (click directly on the page):

  HEADER            -> Logo (upload image or text), navigation
                        menu links, header CTA button
  HERO SECTION      -> Background image, badge, headline,
                        sub-text, both buttons, full company
                        catalog PDF (upload/download link)
  TRUST STRIP       -> 5 trust badge texts on homepage
  CATEGORIES SECTION -> Section title & description text
  FEATURED SECTION  -> Section title text
  WHY SECTION       -> "Why Choose Us" title + 4 cards
  CTA BANNER        -> Mid-page call-to-action banner text
  BLOG SECTION      -> Blog preview section title
  FOOTER            -> Tagline, menu links, copyright,
                        certification text
  ABOUT PAGE        -> Headline, intro, 4 pillars, capability
                        table, bottom CTA - everything
  CONTACT INFO      -> Brand name, tagline, email, phone,
                        address, working hours (3 rows),
                        social media links, homepage stats
  VERIFY PAGE TEXT  -> Authenticity page success & failure
                        messages - use [brand] as a
                        placeholder, it auto-fills your
                        brand name
  SEO               -> Site title, meta description, keywords,
                        OG image, Google Analytics ID, robots

  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ORANGE TOP BAR BUTTONS (full management modals):

  Products    -> Add / Edit / Delete products - main image,
                  image gallery, PDF catalog (per product),
                  technical specs table, compatible models,
                  featured flag, authenticity verify code
  Categories  -> Add NEW categories, edit existing, delete
                  (with warning if products are assigned)
  Blog        -> Add / Edit / Delete blog posts - cover image,
                  excerpt, full content
  FAQ         -> Add / Edit / Delete FAQ questions & answers
  QR          -> View & download QR codes for every product
                  (set your domain, then download PNG to print
                  on packaging)
  Security    -> Change your admin password

  INQUIRIES (bottom-right floating button, admin only)
              -> View all contact form submissions

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  PRODUCT AUTHENTICITY / QR VERIFICATION SYSTEM
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Every product has a unique verification code and URL:
    https://yourdomain.com/#verify/CODE

  TO GET QR CODES:
  1. Admin -> QR (top bar)
  2. Enter your live domain
  3. Download each product's QR image (PNG)
  4. Print on product packaging / labels

  TO CUSTOMIZE THE VERIFY PAGE MESSAGES:
  While logged in as admin, visit yourdomain.com/#verify/anycode
  (or scan a real product QR), then click the EDIT button at
  top-right labelled "VERIFY PAGE TEXT". Edit success badge,
  headline, message, CTA - and the failure state (invalid code)
  messages too. Use [brand] in any text field to auto-insert
  your brand name.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  REBRAND TO YOUR OWN COMPANY - QUICK CHECKLIST
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  [ ] HEADER          -> upload your logo / set logo text
  [ ] CONTACT INFO    -> your brand name, email, phone, address,
                          working hours, social links
  [ ] HERO SECTION    -> your headline, background image, full
                          catalog PDF
  [ ] ABOUT PAGE      -> your company story, pillars, capabilities
  [ ] VERIFY PAGE TEXT -> review wording (auto-uses your brand
                          name via [brand])
  [ ] FOOTER          -> tagline, links, copyright
  [ ] SEO             -> site title, description, keywords
  [ ] Products        -> replace with your own products, images,
                          PDFs, specs
  [ ] Categories      -> your own category names/images
  [ ] Blog / FAQ      -> your own content (or delete defaults)
  [ ] Security        -> change the admin password
  [ ] SAVE & EXPORT   -> download -> re-upload to your hosting

  Everything is template-ready - no coding required.

╔══════════════════════════════════════════════════════════════╗
║  Industrial OEM B2B catalog template - fully white-label     ║
╚══════════════════════════════════════════════════════════════╝
