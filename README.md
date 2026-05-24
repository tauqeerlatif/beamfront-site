# Beamfront Advisory - Corporate Website

This repository contains the production source code and configuration assets for the official corporate website of Beamfront Advisory, accessible at [https://beamfrontadvisory.com.au](https://beamfrontadvisory.com.au).

---

## 🛠️ Infrastructure & Tech Stack

* **Frontend:** Semantic HTML5, CSS3 Custom Theme Variables, JavaScript ES6.
* **Fonts & Icons:** Google Fonts (Inter) & FontAwesome v6.5.1 CDN.
* **Contact Form Routing:** Secure AJAX backend management powered via Formspree CDN integration.
* **Hosting Engine:** GitHub Pages (Automated deployment via main branch pushes).
* **Assets Configuration:** Dynamic inline SVG data-URI vector Favicon (`#00D2FF` Cyan layout mapping).

---

## 🌐 DNS & Domain Routing Configurations

For future reference or platform migrations, the domain `beamfrontadvisory.com.au` is pointed from GoDaddy to GitHub servers using the following production zone rules:

### 1. Naked Domain A-Records (`@` Host)
Points root traffic directly to GitHub Pages load balancers:
* `185.199.108.153`
* `185.199.109.153`
* `185.199.110.153`
* `185.199.111.153`

### 2. Subdomain CNAME Record (`www` Host)
Aliases web traffic safely to your specific user deployment target:
* **Host:** `www`
* **Points To:** `tauqeerlatif.github.io`

---

## 📂 Structural Overview

* `index.html` — Main engineering landing page, strategic advisory profiles, and interactive contact console.
* `privacy-policy.html` — Secure user privacy standards and corporate regulatory parameters.
* `terms-of-service.html` — Terms governing preliminary design validation briefs.
* `CNAME` — Static custom domain verification instruction block for GitHub Pages routing engines.
