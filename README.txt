ID AutoWorks — Off‑Platform Build (Static Site)

What this is
- A complete static website build that matches the Option B style you approved (dark, clean, high‑trust, owner‑first).
- Pages: Home, Sell Your Shop (landing), Our Approach, FAQ, Contact, Privacy Policy, Disclaimer.

How to view locally
1) Unzip the folder
2) Open index.html in a browser

How to move into Squarespace (domain + hosting are already on Squarespace)
You have two practical options:

Option 1 (Recommended): Recreate using Squarespace sections + Custom CSS
- Create pages in Squarespace with the same page names:
  Home
  Sell Your Shop
  Our Approach
  FAQ
  Contact
  Privacy Policy
  Disclaimer
- For each page, add “Blank Page” or a minimal template, then add sections:
  - Hero section (headline, paragraph, buttons)
  - Feature cards (3 columns)
  - Credibility section (2 columns)
  - Form section (Squarespace Form Block)
- Paste the provided CSS into:
  Design → Custom CSS
  (Squarespace will apply it site‑wide; you can scope later if needed.)

Forms
- Use Squarespace Form Block and set the storage / email routing to:
  info@idautoworks.com

Calendly
- Add a Code Block and paste the embed from contact.html (Calendly inline widget).
- Or keep it as a button link to:
  https://calendly.com/idautoworks-info/30min

Privacy + Disclaimer
- Add as separate pages and link them in the footer (already included in this build).

Option 2: Use a single “Code Block” per page (quick but less editable)
- You can copy the <main>…</main> content from each HTML file into Squarespace Code Blocks.
- Still paste styles.css into Custom CSS.

Notes
- This static build uses mailto: for forms because static sites don’t have a backend.
- Once in Squarespace, replace forms with Squarespace Form Blocks so submissions reliably go to your inbox.