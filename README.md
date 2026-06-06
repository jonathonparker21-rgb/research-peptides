## Research Peptides Website

Professional, ready-to-deploy static website template for a **research peptides / research chemicals supplier**.

**Repository:** https://github.com/jonathonparker21-rgb/research-peptides

### ⚠️ CRITICAL LEGAL DISCLAIMERS

**ALL PRODUCTS AND INFORMATION ON THIS SITE ARE FOR RESEARCH USE ONLY.**

- These compounds are **not intended for human consumption**, therapeutic use, or any use in humans or animals.
- They are sold strictly for **in vitro laboratory research purposes** by qualified researchers and institutions.
- By using or deploying this template you acknowledge that you are solely responsible for ensuring full compliance with all applicable local, state, federal, and international laws and regulations (including but not limited to FDA, DEA, and equivalent bodies).
- This template includes prominent, repeated warnings as required for such products. **Do not remove or weaken these disclaimers.**

**This is a demonstration / starter template.** It does not constitute legal, regulatory, or business advice. Real-world sale of research peptides requires proper business licensing, supplier verification, record-keeping, and often registration or exemptions. Misuse of this template or the products it represents can result in serious legal consequences.

### What You Get

- Modern, clean, mobile-responsive single-page website
- Product catalog with categories, search, and detail modals
- Fully functional client-side shopping cart (localStorage)
- Checkout flow with **mandatory research-use affirmations**
- Repeated, highly visible "Research Use Only / Not for Human Use" warnings throughout
- Fake "order" simulation (clearly marked as demo)
- Easy to customize products (edit the JS array in `index.html`)

### Quick Deploy (Recommended)

**Vercel (easiest):**
1. Import the GitHub repo
2. Deploy (no build step needed)
3. Done

**Netlify:**
1. Drag the folder or connect GitHub repo
2. Publish directory = `/` (or root)

**GitHub Pages:**
1. Go to repo Settings → Pages
2. Source: Deploy from a branch → `main` / `/ (root)`
3. Save

The site will be live at `https://<your-username>.github.io/research-peptides`

### Customization

1. **Products**: Edit the `products` array near the top of the `<script>` in `index.html`. Add/remove items, change prices, descriptions, categories.
2. **Branding**: Search/replace "APEX RESEARCH" and update colors in the Tailwind script config.
3. **Contact / Checkout**: The checkout is simulated. For real orders you would need a backend (e.g. Formspree, Supabase Edge Functions + Stripe, or custom server) + compliance/KYC flow.
4. **Images**: Currently using placeholder colored cards + SVG icons. Replace with real product photos / lab imagery for production (ensure you have rights and proper labeling).

### Recommended Production Additions

- Real payment processing with strong verification (Stripe + manual review for research buyers)
- Customer verification / institutional email checks
- Backend order storage + audit log
- COA (Certificate of Analysis) PDF serving per lot
- Age / research-purpose gate on first visit
- Shipping only to verified research addresses
- Full Terms of Service + Privacy Policy pages
- Integration with inventory / accounting

**Never sell or market these products for human use.**

### File Structure

- `index.html` — The complete standalone website (Tailwind via CDN + vanilla JS)
- `README.md` — This file

### Support / Next Steps

Fork or clone this repo. Update the product list with your actual catalog (with real lot numbers, COAs, etc.).

If you intend to operate a real research supply business, consult legal counsel familiar with research chemical regulations in your jurisdiction.

---

**License**: This template is provided as-is for legitimate research supply demonstration purposes. Use at your own risk.