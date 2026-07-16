# Z Petrochemicals FZE — Website

Corporate website for Z Petrochemicals FZE, a UAE-based trading company specializing
in urea supply to Mexico and Latin America.

- **Live site:** https://zpetrochem.com
- **Hosting:** GitHub Pages (static, no build step)
- **Stack:** Single-page static HTML/CSS/JS, bilingual English/Spanish toggle

## Editing

Everything lives in `index.html` (markup, styles, and the EN/ES language toggle).
Edit and push to `main` — GitHub Pages redeploys automatically.

## Custom domain

`CNAME` pins the custom domain (`zpetrochem.com`). DNS is managed at the domain
registrar (Hostinger): four `A` records on the apex pointing at GitHub Pages IPs,
plus a `www` CNAME.
