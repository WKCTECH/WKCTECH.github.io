# WKCTECH.com
Wilson Key Computer Technology
# WKCTECH Digital Infrastructure

This repository hosts the public-facing site for **WKCTECH**, managed by Kathryn Elizabeth Wilson. 

## 🌐 Site Overview
- **URL:** [https://wkctech.com](https://wkctech.com)
- **Primary Stack:** Static HTML/CSS hosted via GitHub Pages.
- **Integrations:** Microsoft 365 (Bookings, Forms, and Custom DNS Management).

## 🛡️ Architecture & Security
This site follows a **decoupled architecture** to minimize the attack surface and ensure data sovereignty:
- **DNS Management:** Authoritatively handled via Microsoft 365.
- **SSL/TLS:** Automated provisioning via Let's Encrypt (GitHub Pages).
- **Hardened Headers:** Implements Content Security Policy (CSP) to upgrade insecure requests and prevent mixed-content vulnerabilities.
- **Data Handling:** All PII (Personally Identifiable Information) captured via forms or booking requests is processed and stored within a secured Microsoft 365 tenant, keeping the frontend entirely stateless.

## 🚀 Deployment
Changes pushed to the `main` branch are automatically deployed via GitHub Actions to the custom domain.

## 📁 Repository Structure
- `index.html`: Main landing page with M365 embeds.
- `favicon.ico`: Custom branding asset.
- `CNAME`: Domain configuration for wkctech.com.

---
*Managed by WKCTECH | Cybersecurity & Collaboration Systems*
