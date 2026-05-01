# TechMarket 🛒⚡

> Kenya's premier electronics marketplace — connecting buyers and sellers of phones, laptops, TVs, gadgets and more.

---

## Overview

TechMarket is a clean, professional single-page web application that allows electronics buyers and sellers to connect directly. Built with pure HTML, CSS, and JavaScript — no frameworks, no backend required.

---

## Features

### 🛍 Browse Listings
- View all electronics listings in a responsive product grid
- Live search by product name, description, or seller
- Filter by category (Phones, Laptops, TVs, Audio, Gaming, Cameras)
- Filter by condition (New / Used)
- Click any listing to view full product details

### ➕ Post a Listing (Sellers)
- Fill in product title, category, condition, price, and location
- Add a detailed description
- Upload a product photo
- Listing appears instantly in Browse after submission

### 💬 Messages (Chat)
- Chat interface between buyers and sellers
- Conversations sidebar with contact list
- Click "Chat" on any listing to start a conversation with the seller
- Auto-reply simulation for demo purposes

### 🔐 Authentication
- Sign In and Sign Up modal
- Role selection: Buyer, Seller, or Both

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts (Syne + DM Sans) |
| Hosting | GitHub Pages / Netlify (recommended) |

No npm. No build step. No dependencies to install.

---

## Getting Started

### Run Locally

Just open the file in your browser:

```bash
# Clone the repo
git clone https://github.com/yourusername/techmarket.git

# Open in browser
open techmarket.html
```

### Deploy to GitHub Pages

1. Push the repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch**
4. Save — your site will be live at:

```
https://yourusername.github.io/techmarket
```

### Deploy to Netlify (Alternative)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop `techmarket.html` onto the dashboard
3. Done — live in seconds with a free URL

---

## Project Structure

```
techmarket/
├── techmarket.html   # Entire application (single file)
└── README.md         # This file
```

---

## Customization

| What to change | Where to look |
|---|---|
| Product listings | `const products = [...]` in the `<script>` tag |
| Brand name / logo | `.nav-logo` in HTML and `<title>` tag |
| Color scheme | `:root` CSS variables at the top of `<style>` |
| Categories | `<select>` dropdowns in Browse and Post sections |
| Currency | Replace `KES` in price display logic |

---

## Roadmap

- [ ] Firebase backend for real listings and auth
- [ ] WhatsApp chat integration
- [ ] Seller ratings and reviews
- [ ] Favorites / wishlist
- [ ] Price negotiation feature
- [ ] M-Pesa payment integration
- [ ] Seller dashboard with analytics
- [ ] Mobile app (React Native)

---

## License

MIT License — free to use, modify, and distribute.

---

## Author

Built with ❤️ for the Kenyan electronics market.


