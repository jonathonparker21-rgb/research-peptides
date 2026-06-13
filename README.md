## Research Peptides Website

Professional, ready-to-deploy static website template for a **research peptides / research chemicals supplier**.

**Repository:** https://github.com/jonathonparker21-rgb/research-peptides

**Live demo (once deployed):** Will be at your Cloudflare Pages URL (e.g. research-peptides.pages.dev)

### ⚠️ CRITICAL LEGAL DISCLAIMERS

**ALL PRODUCTS AND INFORMATION ON THIS SITE ARE FOR RESEARCH USE ONLY.**

- These compounds are **not intended for human consumption**, therapeutic use, or any use in humans or animals.
- They are sold strictly for **in vitro laboratory research purposes** by qualified researchers and institutions.
- By using or deploying this template you acknowledge that you are solely responsible for ensuring full compliance with all applicable local, state, federal, and international laws and regulations (including but not limited to FDA, DEA, and equivalent bodies).
- This template includes prominent, repeated warnings as required for such products. **Do not remove or weaken these disclaimers.**

**This is a demonstration / starter template.** It does not constitute legal, regulatory, or business advice. Real-world sale of research peptides requires proper business licensing, supplier verification, record-keeping, and often registration or exemptions. Misuse of this template or the products it represents can result in serious legal consequences.

### What You Get

- Modern, clean, mobile-responsive single-page website (one `index.html`)
- Product catalog with categories, search, and detail modals
- Fully functional client-side shopping cart (persists with localStorage)
- Checkout flow with **4 mandatory research-use legal affirmations** (checkboxes)
- Repeated, highly visible "Research Use Only / Not for Human Use" warnings on banner, products, modals, cart, checkout, FAQ, and footer
- Fake "order" simulation (clearly marked as demo, no real payment)
- Easy to customize (edit the `products` JS array)

### Quick Deploy to Cloudflare Pages (Recommended)

This site is a static single-file HTML site — perfect for Cloudflare Pages (free, fast CDN, custom domains, security headers, etc.).

1. Go to [Cloudflare Dashboard](https://dash.cloudflare.com) → **Pages** → **Create a project** → **Connect to Git**
2. Authorize Cloudflare to access your GitHub (this installs the Cloudflare GitHub App / "plugin" on your account and will prompt to select the repo)
3. Select the `research-peptides` repository
4. Configure build:
   - Framework preset: **None**
   - Build command: (leave blank)
   - Build output directory: (leave blank)
5. Click **Save and Deploy**
6. Your site will be live at `https://<your-project>.pages.dev`
7. (Optional) Add a custom domain in the project settings → Custom domains

**Note:** The `_headers` file in the repo configures security headers and CSP automatically for Cloudflare Pages.

Alternative (GitHub Pages):
1. Repo Settings → Pages → Source: Deploy from a branch → main / (root)
2. Site at `https://jonathonparker21-rgb.github.io/research-peptides`

### Customization

Open `index.html` and edit the `products` array (in the JS near the top). You can:
- Change names, prices, sizes, purity, descriptions
- Add or remove products
- Update categories

**Important:** Keep all the warning banners, badges, modals, and checkout affirmations. They are intentionally very prominent.

### Recommended Real-World Additions (if you go live)
- Backend + Stripe or other payment (with strong verification)
- Institutional / researcher verification step
- Real COA delivery per lot
- Proper Terms of Service + Privacy Policy (linked from footer)
- Audit logging of orders
- Shipping restrictions to verified research addresses only

**Never market or sell research peptides for human use.** Doing so is illegal in virtually every jurisdiction and can lead to severe penalties.

### File Structure
- `index.html` — Complete standalone site
- `README.md` — This file
- `.nojekyll` — (for GitHub Pages compatibility)
- `_headers` — Cloudflare Pages security headers and CSP

Consult legal counsel if you plan to operate an actual research supply business.

Use responsibly.