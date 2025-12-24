# 🌍 eSimNote - Global Travel Connectivity Platform

![Version](https://img.shields.io/badge/version-2.0.0-blue?style=flat-square)
![PHP](https://img.shields.io/badge/PHP-8.2-777BB4?style=flat-square&logo=php&logoColor=white)
![Status](https://img.shields.io/badge/status-active-success?style=flat-square)
![License](https://img.shields.io/badge/license-Proprietary-red?style=flat-square)

> **Stop Paying Roaming Fees.** Grab a [free eSIM trial](https://esimnote.com/claim.php) and get instant connectivity for travelers in 200+ countries.

**eSimNote** is a lightweight, high-performance web platform designed to sell and distribute eSIM profiles instantly. Built with a focus on speed, SEO, and conversion optimization, it features a custom "Glassmorphism" UI and a robust Free Trial claiming engine.

---

## 🚀 Key Features

* **⚡ Instant Delivery:** Automated QR code generation and email delivery via PHP Mailer integration.
* **🎁 Viral "Free Trial" Engine:** A dedicated funnel to claim a [free eSIM trial](https://esimnote.com/) designed to capture leads by offering 1GB free data.
* **📱 Device Compatibility Check:** Built-in logic to educate users on compatible devices (iPhone XR+, Pixel 3+, etc.).
* **🎨 Neo-Mint Aesthetic:** A custom dark-mode UI with glassmorphic elements, optimized for high contrast and mobile readability.
* **📝 SEO Optimized Blog:** A lightweight, database-free blog engine (`blog.php`) with auto-generated Schema Markup and Open Graph tags.
* **🔒 Security First:** Strict validation on trial claims to prevent abuse (IP limiting and email verification logic).

---

## 🛠️ Tech Stack

* **Backend:** PHP 8.0+ (No heavy frameworks, pure performance)
* **Frontend:** HTML5, CSS3 (Custom Variables), Vanilla JavaScript
* **Styling:** Custom CSS (Glassmorphism), FontAwesome 6 Pro
* **Database:** *Mock Data Arrays* (Currently file-based for speed, scalable to MySQL/MariaDB)
* **Server:** Apache / Nginx compatible

---

## 📂 Project Structure

```bash
eSimNote/
├── cdn/                  # Static assets (images, icons, manifest)
│   ├── favicon-32x32.png
│   └── og-social-card.jpg
├── index.php             # Homepage (Landing & Pricing)
├── claim.php             # Free Trial Funnel
├── blog.php              # SEO Blog Engine
├── plans.php             # Dynamic Pricing Page
├── terms.php             # Terms of Service
├── privacy.php           # Privacy Policy
├── 404.php               # Custom Error Page
└── README.md             # Documentation
