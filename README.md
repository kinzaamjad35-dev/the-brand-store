# The Brand Store

A Magento 2 e-commerce website for laptop batteries, chargers and parts, based in Lahore, Pakistan.

**Live site:** [www.thebrandstore.pk](https://www.thebrandstore.pk)

---

## Overview

The Brand Store is a retail website that supplies laptop batteries, chargers, keyboards and related parts to customers in Pakistan. I rebuilt and improved the live store, with an emphasis on helping customers identify the correct part, expanding the catalogue, and presenting the site more clearly.

This repository is a public showcase of that work. The source code remains private because the site is a live commercial store.

## Features

- **AI chat assistant.** A Botpress assistant that answers customer questions and provides links to live product pages.
- **Photo-based model finder.** Customers can photograph a laptop, battery or charger label. Optical character recognition runs in the browser and is built to accept HEIC photographs from iPhone cameras and to handle rotated images.
- **Parts-by-model search.** A search flow that helps customers find compatible parts for a given laptop model, with a brand filter.
- **Interface redesign.** The header, menu and footer were redesigned for a clearer layout.
- **Catalogue.** The product catalogue was expanded with product photographs and search-engine-oriented descriptions.
- **Customer contact.** Floating WhatsApp and live-chat controls are placed on the storefront so that customers can reach the shop without leaving the page.

## Screenshots

### Homepage (desktop)

![The Brand Store homepage on a desktop display](docs/screenshots/homepage-desktop.png)

### Homepage (mobile)

<img src="docs/screenshots/homepage-mobile.png" alt="The Brand Store homepage on a mobile display" width="390">

### Laptop Batteries category

![Laptop Batteries category page](docs/screenshots/category-laptop-batteries.png)

### Product page

![Apple MacBook Air 13-inch M4 battery product page](docs/screenshots/product-macbook-air-battery.png)

## Technical Stack

![Magento](https://img.shields.io/badge/Magento%202-0F2C4C?style=flat-square)
![PHP](https://img.shields.io/badge/PHP-0F2C4C?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-0F2C4C?style=flat-square)
![OCR](https://img.shields.io/badge/In--browser%20OCR-0F2C4C?style=flat-square)
![Botpress](https://img.shields.io/badge/Botpress-0F2C4C?style=flat-square)
![Cloudflare](https://img.shields.io/badge/Cloudflare-0F2C4C?style=flat-square)

**Platform:** Magento 2, PHP, JavaScript  
**Assistant and recognition:** Botpress; in-browser optical character recognition in the style of Tesseract.js  
**Infrastructure:** Cloudflare

## Source Code

The source code for the live store is private. The public website is the definitive view of the project:

[www.thebrandstore.pk](https://www.thebrandstore.pk)
