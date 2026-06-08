╔══════════════════════════════════════════════════════════════╗
║         AUTOMOR — COMPLETE WEBSITE DEPLOYMENT GUIDE         ║
╚══════════════════════════════════════════════════════════════╝

FILES IN THIS ZIP:
  index.html   → Complete website (all pages + admin panel)
  .htaccess    → Apache routing + HTTPS + security headers
  README.txt   → This guide

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  UPLOAD TO HOSTINGER (OR ANY CPANEL HOSTING)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  1. Login → hpanel.hostinger.com
  2. My Hosting → Manage → File Manager
  3. Open "public_html" folder
  4. Delete all existing files inside it
  5. Upload: index.html + .htaccess
  6. Visit your domain → website is live!

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  OTHER HOSTING PLATFORMS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  NETLIFY (Free — Easiest):
  1. Go to netlify.com → Sign up free
  2. Create a file named "_redirects" with content:
         /*    /index.html   200
  3. Drag & drop all 3 files onto Netlify deploy area
  4. Done — live in 30 seconds

  VERCEL (Free):
  1. Go to vercel.com → Sign up
  2. Create "vercel.json":
         {"rewrites":[{"source":"/(.*)", "destination":"/index.html"}]}
  3. Upload via Vercel CLI: vercel deploy

  GITHUB PAGES (Free):
  1. Create GitHub repo → upload index.html
  2. Settings → Pages → Deploy from branch → main
  3. Live at: yourusername.github.io/repo-name
  (No .htaccess needed — hash routing works automatically)

  CLOUDFLARE PAGES (Free + Fastest CDN):
  1. pages.cloudflare.com → New project
  2. Upload folder with index.html
  3. Done — global CDN automatically

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  ADMIN PANEL ACCESS (PRIVATE — DO NOT SHARE)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  METHOD 1 — URL (live website):
    https://yourdomain.com/#admin
    (The #admin disappears from URL bar instantly)

  METHOD 2 — Keyboard shortcut:
    Ctrl + Shift + A  (Windows/Linux)
    Cmd  + Shift + A  (Mac)

  DEFAULT PASSWORD:  admin123

  ⚠ CHANGE YOUR PASSWORD IMMEDIATELY:
    Admin Panel → Security tab → Change Password

  SECURITY FEATURES:
    ✓ Zero public links on the website
    ✓ 3 wrong attempts = 30-second lockout
    ✓ Session memory only (auto-logout on refresh)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  PRODUCT AUTHENTICITY / QR CODES
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  Each product has a unique verification URL:
    https://yourdomain.com/#verify/PRODUCTCODE

  Get QR codes:
    Admin Panel → QR & Verify tab
    → Set your domain
    → Download QR images for printing

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  ADMIN PANEL — ALL SECTIONS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  Dashboard      → Stats, quick actions
  Brand & Contact→ Brand name, email, phone, address, social
  Header & Logo  → Logo upload, navigation links, CTA button
  Homepage       → Hero image/text/PDF, trust strip, why section
  Products       → Add/Edit/Delete + gallery + PDF + verify code
  Categories     → Add/Edit/Delete + images
  QR & Verify    → QR codes for product packaging
  Blog Posts     → Add/Edit/Delete articles
  FAQ            → Add/Edit/Delete questions
  Footer         → Tagline, menus, copyright
  SEO            → Meta tags, Google Analytics, robots
  Security       → Change admin password
  Inquiries      → View contact form submissions

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  REBRAND TO ANY COMPANY
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  Everything is editable from the Admin Panel:
  → Change brand name, logo, colors, all text
  → Add your own products, categories, blog posts
  → Update contact details and social links
  → No coding required

╔══════════════════════════════════════════════════════════════╗
║  Template designed for global OEM automotive B2B brands     ║
╚══════════════════════════════════════════════════════════════╝
