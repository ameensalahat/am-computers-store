# AM Computers Store — Full-Stack E-Commerce Website

A fully responsive, client-side e-commerce website for a computer hardware retail store. Built as a multi-page application featuring product browsing, a shopping cart, and a clean, modern UI.

---

## Technologies Used

| Layer      | Technology                          |
|------------|-------------------------------------|
| Markup     | HTML5                               |
| Styling    | CSS3, Bootstrap 5                   |
| Scripting  | JavaScript (ES5+), jQuery           |
| UI Library | Swiper.js (carousels), Modernizr    |
| Fonts      | Google Fonts (Jost, Lato)           |

---

## Key Features

- **Product Browsing** — Dedicated shop pages for Laptops and Desktop PCs with product cards, pricing, and add-to-cart buttons
- **Shopping Cart** — Cart page with item summary, delivery options, promo code field, and total price display
- **Product Carousels** — Swiper.js powered sliders for featured products, smart watches, and customer testimonials
- **Search Popup** — Animated full-screen search overlay with keyboard (Esc) support
- **Quantity Controls** — Increment/decrement product quantity directly on product pages
- **Sale Countdown** — Countdown timer UI for active promotions
- **Responsive Design** — Fully responsive layout using Bootstrap 5 grid and CSS media queries, optimized for desktop, tablet, and mobile
- **Payment & Shipping Display** — Visa, Mastercard, PayPal, and DHL icons integrated into the footer
- **Newsletter Signup** — Email subscription section
- **Blog Section** — Post cards with images and excerpt previews

---

## Project Structure

```
AMStore/
├── index.html          # Homepage — hero banner, featured products, testimonials
├── about.html          # About page
├── account.html        # Login / account page
├── cart.html           # Shopping cart
├── laptop-shop.html    # Laptops product listing
├── pc-shop.html        # Desktop PCs product listing
├── style.css           # Custom styles
├── css/
│   ├── bootstrap.min.css   # Bootstrap 5 framework
│   ├── vendor.css           # Third-party styles
│   └── ajax-loader.gif      # Loading spinner
├── js/
│   ├── jquery-1.11.0.min.js # jQuery library
│   ├── main.js              # Main application logic
│   ├── script.js            # Search popup & quantity controls
│   ├── plugins.js           # jQuery plugin extensions
│   └── modernizr.js         # HTML5 feature detection
└── images/                  # Product photos, brand logos, and UI assets
```

---

## Pages

| Page               | Description                                      |
|--------------------|--------------------------------------------------|
| `index.html`       | Homepage with hero banner, product sections, blog |
| `laptop-shop.html` | Laptop product catalog                            |
| `pc-shop.html`     | Desktop PC product catalog                        |
| `cart.html`        | Shopping cart with order summary                  |
| `account.html`     | User login / account management                   |
| `about.html`       | Company information                               |

---

## Screenshots

![screenshot](screenshots/Screenshot%202026-05-13%20154454.png)
![screenshot](screenshots/Screenshot%202026-05-13%20154530.png)
![screenshot](screenshots/Screenshot%202026-05-13%20154553.png)
![screenshot](screenshots/Screenshot%202026-05-13%20154625.png)
![screenshot](screenshots/Screenshot%202026-05-13%20154639.png)
![screenshot](screenshots/Screenshot%202026-05-13%20154707.png)
![screenshot](screenshots/Screenshot%202026-05-13%20154716.png)
![screenshot](screenshots/Screenshot%202026-05-13%20154741.png)
![screenshot](screenshots/Screenshot%202026-05-13%20154759.png)

---

## Getting Started

No build step required. Open `index.html` in any modern browser to run the project locally.

---

## Author

**Ameen Salahat**
