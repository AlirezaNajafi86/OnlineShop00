# 🛍️ OnlineShop

### Modern E-Commerce Platform

A modern e-commerce website built with **WordPress, WooCommerce, Elementor Pro, and Docker**, designed with a premium **Liquid Glass UI** and a dark, minimal visual identity.

---

## ✨ Highlights

* 🎨 Premium Liquid Glass interface
* 🌙 Dark / Light mode
* 🛍️ WooCommerce-powered store
* 📦 Custom product pages
* 🛒 Custom Cart & Checkout experience
* 👤 Custom My Account interface
* 🔎 Advanced product search
* 📱 Responsive design
* ⚡ WebP image optimization
* 🐳 Docker-based development environment

---

## 🛠️ Tech Stack

| Technology    | Usage                    |
| ------------- | ------------------------ |
| WordPress     | CMS                      |
| WooCommerce   | E-Commerce               |
| Elementor Pro | UI / Page Builder        |
| Kadence       | Theme                    |
| MariaDB       | Database                 |
| Docker        | Development & Deployment |
| Cloudflare    | DNS / Security / CDN     |

---

## 🎨 Design

The interface follows a modern dark aesthetic with:

* Dark Blue backgrounds
* White typography
* Transparent surfaces
* Subtle blur
* Rounded corners
* Glass-style components
* Minimal visual hierarchy

---

## 🏗️ Architecture

```text
                    Internet
                       │
                       ▼
                  Cloudflare
                       │
                       ▼
                     VPS
                       │
                     Docker
                  ┌────┴────┐
                  │         │
             WordPress   MariaDB
```

---

## 📸 Preview

Screenshots of the project will be added here.

### Homepage

![Homepage](screenshots/homepage.png)

### Product Page

![Product Page](screenshots/product-page.png)

### Cart

![Cart](screenshots/cart.png)

### Checkout

![Checkout](screenshots/checkout.png)

### My Account

![My Account](screenshots/my-account.png)

---

## 🚀 Deployment

The project is developed locally using Docker and is designed for deployment on a Linux VPS.

Production architecture:

```text
Cloudflare
     ↓
Linux VPS
     ↓
Docker
     ↓
WordPress + MariaDB
```

The production environment is designed for **24/7 availability**, independent of the local development machine.

---

## 📌 Project Status

🟡 **In Development**

The UI, WooCommerce customization, responsive layouts, and production deployment are being finalized.

---

## 🔐 Repository Scope

This repository is intended as a **portfolio and project presentation**.

Production files, databases, credentials, customer information, and private configuration are intentionally excluded.
