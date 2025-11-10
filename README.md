# 🚧 KDS Systems Inc. — Under Construction

Welcome to the official holding page for **KDS Systems Inc.**, a technology solutions firm based in Greenwich, Connecticut.

This minimal, responsive webpage serves as our temporary presence while we build a new high-performance website.  
It’s sleek, fast, and optimized for GitHub Pages with Cloudflare DNS and HTTPS support.

---

## ✨ Overview

**Tagline:** _Engineering what’s next._

The page features:
- A black, high-tech aesthetic with soft neon glow accents
- Smooth logo animation on page load (reduced motion friendly)
- Full contact information for easy reach
- SEO and social sharing metadata (OG + manifest)
- Automated deployment through GitHub Actions

---

## 🧱 Project Structure

/kds-under-construction
├─ .github/workflows/pages.yml      # GitHub Pages CI/CD workflow
├─ assets/
│  ├─ favicon.ico                   # Generated from company logo
│  ├─ logo.png                      # Company logo (animated on load)
│  ├─ og-image.png                  # Social preview banner
│  └─ site.webmanifest              # Web manifest for PWA compatibility
├─ css/styles.css                   # Core layout and animation styles
├─ js/main.js                       # Motion logic and accessibility
├─ index.html                       # Main splash page
├─ 404.html                         # Fallback for broken links
└─ README.md

---

## 📞 Contact Information

**KDS Systems Inc.**  
500 W Putnam Ave Suite 400  
Greenwich, CT 06830  

📱 **Phone:** [203-497-6300](tel:2034976300)  
✉️ **Email:** [Info@KDSytemsInc.com](mailto:Info@KDSytemsInc.com)

---

## 🚀 Deployment Instructions

1. **Push to GitHub**
   ```bash
   git init -b main
   git add .
   git commit -m "feat: initial under construction site"
   git remote add origin git@github.com:YOUR_GITHUB_USERNAME/kds-under-construction.git
   git push -u origin main

	2.	Enable GitHub Pages
	•	Go to your repository → Settings → Pages
	•	Under Build and deployment, select GitHub Actions
	•	GitHub will automatically deploy using the provided workflow (pages.yml)

⸻

🌐 Custom Domain (via Cloudflare)

To use a custom domain such as www.kdssystemsinc.com:
	1.	Add a file named CNAME at the project root containing:

www.kdssystemsinc.com


	2.	In Cloudflare DNS, create:
	•	CNAME www → YOUR_GITHUB_USERNAME.github.io (set Proxied ☁️)
	•	Redirect the apex domain (kdssystemsinc.com) to www
	3.	In Cloudflare SSL/TLS settings:
	•	Enable Always Use HTTPS
	•	Enable Automatic HTTPS Rewrites

⸻

✅ Validation Checklist
	•	Page loads successfully via HTTPS
	•	Logo animation renders cleanly on desktop & mobile
	•	Apex domain redirects correctly
	•	GitHub Actions workflow passes
	•	Lighthouse score ≥ 90
	•	OG image preview displays correctly when shared
	•	Contact links (phone/email) work as expected

⸻

🔄 Rollback & Maintenance
	•	Revert any deploy with:

git revert <commit-sha>


	•	If DNS is misconfigured, temporarily remove the CNAME file.
	•	Pause Cloudflare proxy (☁️ → ⚫️) for debugging if needed.

⸻

🌟 Optional Enhancements
	•	Integrate Cloudflare Web Analytics for privacy-safe insights
	•	Add a Turnstile CAPTCHA for future contact forms
	•	Serve a newsletter signup via Cloudflare Workers
	•	Include robots.txt or security.txt for compliance

⸻

🧩 License

This project is licensed under the MIT License.
Feel free to fork or adapt it for your own use.

⸻

©️ {year} KDS Systems Inc. — All rights reserved.
Built with modern web standards. Deployed on GitHub Pages.
