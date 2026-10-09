# VOYAGEUR EXPEDITIONS — Curated Global Journeys & Luxury Travel Portal

A luxury travel and expedition web application built with modern **HTML5**, **CSS3**, and **Vanilla JavaScript**. Designed for seamless exploration, itinerary customization, real-time booking estimation, and currency conversion.

---

## 🌟 Key Features

1. **Editorial Luxury Aesthetic & Responsive Layout**
   - Clean, modern layout with high-resolution imagery and glassmorphic navigation.
   - **Light & Dark Theme Toggle**: Easily toggle between daytime canvas and midnight dark mode with saved preferences in `localStorage`.
   - Distinctive typography using Google Fonts: *Playfair Display* (Editorial Titles), *Cinzel* (Brand Monogram), and *Plus Jakarta Sans* (Clean Modern UI).

2. **Real-Time Dynamic Currency Converter**
   - Switch between **USD ($)**, **EUR (€)**, **GBP (£)**, **AUD (A$)**, and **JPY (¥)** instantly.
   - Dynamically recalculates all expedition cards, itinerary estimators, bucket list totals, and checkout figures across the entire website without page reload.

3. **Curated Expedition Catalog & Advanced Filtering**
   - 12 comprehensive global destinations across 7 continents:
     - *Amalfi Coast & Capri* (Italy)
     - *Kyoto & Mount Fuji Zen Journey* (Japan)
     - *Swiss Alps & Glacier Express* (Switzerland)
     - *Serengeti & Ngorongoro Big 5 Safari* (Tanzania)
     - *Santorini Sunset & Aegean Odyssey* (Greece)
     - *Reykjavik & Northern Lights* (Iceland)
     - *Bora Bora Overwater Sanctuary* (French Polynesia)
     - *Bali Sacred Temples & Ubud Rainforest* (Indonesia)
     - *Machu Picchu & Inca Sacred Valley* (Peru)
     - *Banff & Canadian Rockies Wilderness* (Canada)
     - *Marrakech Medina & Sahara Stargazing* (Morocco)
     - *Patagonia Glaciers & Torres del Paine* (Chile & Argentina)
   - Category filtering pills: *All, Tropical & Coastal, Mountain & Snow, Cultural Heritage, Safari & Wildlife, Nordic & Arctic, Desert & Oasis*.
   - Live search by destination, country, keywords, or style tags.
   - Interactive budget slider ($1,500 – $5,000+).
   - Multi-option sorting: *Featured, Price: Low to High, Price: High to Low, Highest Rated, Duration*.

4. **Detailed Itinerary & Quick View Modal**
   - High-definition photo gallery with interactive thumbnail switcher.
   - Day-by-day expandable accordion itinerary with highlighted daily moments.
   - Clear *What's Included* vs *Not Included* comparison checklists.
   - **Interactive Live Cost Estimator**:
     - Adjust number of travelers with increment/decrement counters.
     - Choose accommodation tier (*Standard Boutique, Signature View Suite +$250, Presidential Villa +$600*).
     - Select bespoke add-ons (*VIP Helicopter Transfer +$200, Travel Protection +$80, Private Photographer +$150*).
     - Live instant total calculation in selected currency.

5. **Interactive "Trip Matchmaker" Quiz ("Find Your Perfect Journey")**
   - 3-step intuitive questionnaire analyzing travel companions, dream landscapes, and travel pace.
   - Algorithm calculates top 2 tailored destination matches with percentage score (e.g. *98% Match*), instant details modal, and direct booking actions.
   - Retake quiz anytime.

6. **Interactive Smart Packing Checklist Generator**
   - Select destination terrain (*Beach, Mountain, Cultural, Safari, Nordic, Desert*).
   - Dynamically generates essential packing items with checklist boxes.
   - Live progress bar showing percentage of items packed.
   - Built-in **Print / Save Checklist** function with print-optimized CSS styles.

7. **Persistent Bucket List Drawer (Saved Trips)**
   - Click the heart icon on any destination card to bookmark or remove.
   - Slide-out right panel showing saved journeys, thumbnail, duration, price, and combined budget total.
   - Synchronized header badge counter with `localStorage` persistence.

8. **Multi-Step Booking Simulator & Checkout Modal**
   - Traveler information input (name, email, phone, dietary/special requests).
   - Date picker and travel party size adjuster.
   - Accommodation tier and add-on selection.
   - **Promo Code Engine**: Test codes like **`VOYAGE15`** (15% off) and **`SUMMER100`** ($100 off).
   - Simulated payment method selection (Credit Card, Apple Pay / Google Pay, Concierge Wire).
   - Generates unique bespoke **Expedition Confirmation Ticket** with reference ID (e.g. `BK-VOY-773921`), trip details, and printable summary.

9. **Traveler Stories & Interactive Review Submission**
   - Carousel grid of authentic explorer reviews with star ratings and verified badges.
   - Interactive **Write a Review** modal allowing visitors to submit their own review which immediately displays on the site and persists in `localStorage`.

10. **The Voyageur Journal & Guides**
    - Rich editorial travel articles with read modals.

11. **Interactive FAQ Accordion & Newsletter Club**
    - Accordion addressing cancellations, flight arrangements, and customization.
    - VIP newsletter signup triggering instant coupon toast notifications.

---

## 📁 File Structure

```text
e:\New folder\New folder (3)\
│
├── index.html            # Semantic HTML5 structure, navigation, sections & modals
├── README.md             # Documentation, user guide & promo code list
│
├── css\
│   └── style.css         # Responsive styling, glassmorphism, themes, animations
│
└── js\
    ├── destinations.js   # Destination catalog, itineraries, currencies, packing data
    └── app.js            # App state, currency engine, filters, modals, quiz & checkout
```

---

## 🚀 How to Run the Website

**Zero configuration or build steps required!**

1. Navigate to the folder `e:\New folder\New folder (3)\`.
2. Double-click **`index.html`** to open it in your web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari, etc.).
3. Or right-click `index.html` and choose **Open with -> Google Chrome**.

---

## 🎟️ Test Promo Codes

Enter these promo codes during the Booking Checkout:

| Promo Code | Discount Benefit |
| :--- | :--- |
| **`VOYAGE15`** | **15% Off** total expedition booking |
| **`SUMMER100`** | **$100 Instant Travel Credit** |
| **`WANDERLUST`** | **10% Off** welcome explorer discount |

---

## 🛠️ Customization Guide

- **Add New Destinations**: Open `js/destinations.js` and add an object to the `DESTINATIONS` array with title, price, itinerary days, and photos.
- **Adjust Colors or Branding**: Open `css/style.css` and modify variables in `:root` and `[data-theme="dark"]` (e.g., `--accent-primary`, `--coral-accent`).
- **Update Currencies & Rates**: Edit the `CURRENCIES` object in `js/destinations.js`.
