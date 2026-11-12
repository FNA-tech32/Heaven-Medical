# 🏥 Heaven Studio — Dental & Medical Practice Website

### Modern, High-Performance Dental Clinic Platform for Oakville, ON

Welcome to the official web repository for **Heaven Studio**, a premier dental clinic and medical care provider located in Oakville, Ontario. The platform is designed to provide patients with an intuitive, accessible experience to explore clinical dental services, review patient feedback, locate the clinic, and book appointments through multiple communication channels.

---

## 🌟 Overview

**Heaven Studio** provides comprehensive family, preventive, restorative, and cosmetic dental treatments in Oakville. Located centrally on Lakeshore Road East, Heaven Studio caters to patients across Oakville and neighbouring communities including Bronte, Clearview, River Oaks, West Oak Trails, and Palermo.

The website delivers a fast, mobile-first patient portal built with semantic HTML5, modern CSS3 styling tokens, interactive JavaScript navigation with accessibility features, and Schema.org structured data for rich search engine indexing.

---

## 📞 Multi-Channel Contact & Alternative Details

Patients can reach Heaven Studio through multiple dedicated communication lines:

| Contact Method | Primary Channel | Alternative / Direct Channel |
| :--- | :--- | :--- |
| **Phone Line** | `+1 905-845-5566` | `+1 289-813-5566` *(Direct / Emergencies)* |
| **Email Support** | `info@heavenstudio.ca` | `appointments@heavenstudio.ca` *(Bookings & Records)* |
| **Online Booking** | [Book Online Form](https://heavenstudio.ca/book-online/) | [Direct Phone Inquiry](tel:+19058455566) |
| **Physical Address** | **114 Lakeshore Road East**, Oakville, ON, L6J 6N2, Canada | — |

### 🕒 Clinic Hours of Operation

- **Monday – Friday**: 8:00 AM – 6:00 PM
- **Saturday**: 9:00 AM – 3:00 PM
- **Sunday**: Closed *(Emergency On-Call Support Available)*

---

## ✨ Key Website Features

- **Brand & Visual Identity**: Cohesive, professional design crafted for **Heaven Studio** featuring a clean medical color palette, crisp typography via Google Fonts (Inter), and clear trust signals.
- **Service Highlights**:
  - **Comprehensive Dental Check-ups & Cleanings**: Routine exams, digital X-rays, plaque/tartar removal, and oral cancer screenings.
  - **Cosmetic Smile Enhancement**: Teeth whitening, porcelain veneers, and Invisalign clear aligners.
  - **Restorative Dentistry**: Tooth-colored composite fillings, porcelain crowns, bridges, and root canal therapy.
  - **Dental Implants & Replacement**: Modern surgical tooth replacement and implant restorations.
  - **Pediatric & Family Dentistry**: Gentle dental care tailored for children, teens, and seniors.
- **Dedicated Multi-Channel Contact Section**: High-visibility contact cards detailing primary and alternative telephone numbers, inquiry and appointment emails, and consultation hours.
- **Interactive Location Map**: Embedded Google Maps iframe displaying the exact clinic coordinates at 114 Lakeshore Road East in Oakville.
- **Accessible Navigation Drawer**: Responsive slide-out menu with CSS-only fallback (`:checked` state) and JavaScript keyboard support (`Escape`, `Enter`, `Space`) for full WCAG accessibility.
- **Social Proof & Verified Testimonials**: Five-star patient review cards highlighting gentle care, professional staff, and comfortable visits.
- **Interactive FAQ Accordion**: Expandable `<details>` FAQ covering services, consultation pricing, and service areas.
- **SEO & Search Rich Results**:
  - Valid Schema.org `LocalBusiness`, `FAQPage`, `BreadcrumbList`, `WebPage`, `HowTo`, and `Review` structured data.
  - Full OpenGraph (`og:*`) and Twitter Card (`twitter:*`) metadata for social sharing.
  - Canonical link tags and semantic HTML5 hierarchy.

---

## 🛠️ Technology Stack

| Layer | Technology | Details |
| :--- | :--- | :--- |
| **Markup** | HTML5 | Semantic structure (`<header>`, `<nav>`, `<article>`, `<section>`, `<footer>`, `<aside>`) |
| **Styling** | Vanilla CSS3 | Custom responsive grid system, CSS variables, mobile media queries |
| **Typography** | Google Fonts | Inter (weights: 300, 400, 500, 600, 700) |
| **Interactivity** | Vanilla JavaScript (ES6) | Touch-friendly navigation drawer, keyboard trap/accessibility handling, lifecycle observers |
| **Maps** | Google Maps Embed API | Embedded interactive map for Oakville clinic location |
| **Rich Snippets** | JSON-LD / Schema.org | `@graph` configuration with LocalBusiness, Ratings, FAQs, Reviews, and HowTo |

---

## 📂 Project Structure

```bash
Heaven-Medical/
├── index.html                    # Main landing page for Heaven Studio Oakville
├── google2778a0d5afbef098.html   # Google Search Console verification file
└── README.md                     # Comprehensive project documentation
```

---

## 🚀 Getting Started & Local Development

This project has zero external package dependencies and can be run immediately in any modern web browser or lightweight local server.

### Option 1: Direct File Opening
Double-click `index.html` or open it with your preferred web browser:
```bash
# On Windows PowerShell
Start-Process .\index.html
```

### Option 2: Local HTTP Server (Recommended)
Using Node.js / npx:
```bash
npx -y serve .
```

Or using Python 3:
```bash
python -m http.server 3000
```
Open `http://localhost:3000` in your web browser.

---

## 🔍 SEO & Rich Snippets Configuration

The site includes comprehensive Schema.org JSON-LD microdata:
- **`@type: LocalBusiness`**: Identifies **Heaven Studio** with telephone numbers, multi-point contacts (customer service & emergency), address, and official social media profiles.
- **`@type: FAQPage`**: Generates expandable FAQ rich cards on Google Search results.
- **`@type: AggregateRating`**: Displays 5.0-star rating signals with verified patient feedback.
- **`@type: BreadcrumbList`**: Structured navigation breadcrumbs for search engine crawling.

---

## 📄 License & Attribution

© 2026 **Heaven Studio**. All rights reserved.
Licensed for Heaven Studio clinical practice and web platform operations.
