# TERM LOAN — Premium Business Website

A premium dark black / dark-blue static business website designed for GitHub Pages.

## Business information used
- Enterprise: TERM LOAN
- Udyam Registration: UDYAM-UP-29-0257019
- Type: Micro
- Major Activity: Trading
- Unit: Term Loan
- Registration date: 07/09/2026
- Commencement: 20/11/2025
- Phone: 7669808439
- Email: Wealthwizardsfinancial0@gmail.com
- Address: Building No. 20, Term Loan, Block B, New Rohtak Road, Karol Bagh, Uttar Pradesh, District Ghaziabad, PIN 110005
- NIC activity: 74101 — Fashion design related to textiles, wearing apparel, shoes, jewelry, furniture and other fashion goods as well as other personal or household goods

Source: supplied Udyam Registration Certificate. Legal/business details should be checked against the current certificate before publishing.

## Structure
`index.html`, `about.html`, `services.html`, `products.html`, `portfolio.html`, `faq.html`, `contact.html`, `privacy.html`, `assets/style.css`, `assets/app.js`, `assets/images/`.

## Run locally
Open `index.html` in a browser, or use any simple local static server. No backend is required for page rendering.

## GitHub Pages
1. Create a GitHub repository.
2. Upload all files while preserving the folder structure.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select your main branch and `/root` (or the repository root), then save.
6. Wait for GitHub Pages to publish the site.
7. Open the generated `github.io` address.

## Custom domain
In **Settings → Pages**, enter your domain under **Custom domain** and enable HTTPS when available. At your domain registrar, point DNS to GitHub Pages using the records GitHub currently provides for your repository. If you prefer a CNAME file, create a root-level `CNAME` containing only your domain.

## Replace images
Put images in `assets/images/` and update the relevant `<img src="./assets/images/...">` paths. The current design mainly uses CSS visual placeholders so the site does not depend on broken remote images.

## Update company details
Search the HTML files for `TERM LOAN`, phone, email, Udyam number, and address. Replace consistently. For larger edits, update the repeated footer/header values in each page.

## Update services/products/portfolio
Edit the cards in `services.html`, `products.html`, and `portfolio.html`. Remove placeholder content before publishing.

## WhatsApp / Phone / Email
The current phone/email links are generated from the supplied certificate. WhatsApp uses `https://wa.me/917669808439`.

## Social links
No social media URLs were supplied, so none are falsely claimed. Add real profile URLs only when confirmed.

## Contact form
The form is intentionally static and does not pretend to send email. Connect Formspree, Netlify Forms, a CRM/form provider, or your own backend if actual submissions are required.

## Important
The Udyam certificate contains source formatting for the address that appears internally inconsistent. This package preserves the certificate wording rather than inventing a correction. Verify the final public address before deployment.
