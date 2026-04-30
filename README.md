# 🛍️ Lumière — Product Catalog

A luxury dark-themed product catalog web application built with pure **HTML, CSS, and JavaScript** — no frameworks, no dependencies, no build tools required. Just open the file in a browser and it works.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-gold?style=flat&logo=render)](https://product-catalog-gmij.onrender.com)

---

## 🌐 Live Demo

👉 **[https://product-catalog-gmij.onrender.com](https://product-catalog-gmij.onrender.com)**

---

## 📸 Preview

> A dark editorial-styled product catalog with a gold accent palette, smooth animations, slide-out cart drawer, and full localStorage persistence.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🗂️ Product Listing | 12 products across 6 categories with images, badges, ratings |
| 🔍 Search Bar | Live search filtering by name, description, or category |
| 🏷️ Category Filter | One-click chip filters (All, Watches, Apparel, Home, etc.) |
| 🪟 Product Detail Popup | Modal with full image, description, discount %, tags |
| 🛒 Add to Cart | Add from card or product detail modal |
| 🔢 Cart Count Badge | Animated badge on the cart button |
| 🗃️ Cart Drawer | Slide-out cart with quantity controls and totals |
| ❌ Remove from Cart | Remove individual items from the cart |
| 💾 localStorage | Cart persists across page refreshes automatically |
| 📱 Responsive | Works on desktop, tablet, and mobile |

---

## 🚀 Getting Started

### Option 1 — Open directly
Just download `product-catalog.html` and open it in any modern browser. That's it.

### Option 2 — Clone the repo
```bash
git clone https://github.com/your-username/lumiere-product-catalog.git
cd lumiere-product-catalog
# Open product-catalog.html in your browser
```

### Option 3 — GitHub Pages
1. Go to your repository **Settings**
2. Navigate to **Pages**
3. Set source to `main` branch, `/ (root)`
4. Visit `https://your-username.github.io/lumiere-product-catalog/product-catalog.html`

---

## 📁 Project Structure

```
lumiere-product-catalog/
│
└── product-catalog.html    # Complete single-file application
└── README.md               # This file
```

Everything — HTML, CSS, and JavaScript — lives in one self-contained file.

---

## 🛠️ Built With

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, Grid, Flexbox, animations, backdrop-filter
- **Vanilla JavaScript** — No libraries or frameworks
- **Google Fonts** — Cormorant Garamond (serif) + DM Sans (sans-serif)
- **Unsplash** — Product images via CDN
- **localStorage API** — Cart persistence

---

## 🎨 Design Highlights

- Dark luxury editorial aesthetic with gold (`#c9a84c`) accents
- Sticky header and toolbar
- Smooth card hover animations with image zoom
- Staggered fade-up animation on product cards
- Slide-out cart drawer with overlay
- Toast notification on add to cart
- Responsive grid layout (`auto-fill`, `minmax`)
- Custom scrollbar styling

---

## 📦 Product Categories

- ⌚ Watches
- 👕 Apparel
- 🏠 Home
- 💡 Electronics
- 👜 Accessories
- 👟 Footwear
- ☕ Kitchen

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| `Esc` | Close modal or cart drawer |

---

## 🔧 Customization

### Change the store name
Search for `Lumière` in the HTML file and replace with your store name.

### Add a new product
Add an object to the `PRODUCTS` array in the `<script>` section:

```javascript
{
  id: 13,
  name: "Your Product Name",
  cat: "Category",          // Must match an existing or new category
  price: 99,
  oldPrice: 129,            // Set to null if no discount
  rating: 5,                // 1–5
  badge: "new",             // "new", "sale", "hot", or null
  desc: "Product description here.",
  tags: ["tag1", "tag2"],
  img: "https://your-image-url.jpg"
}
```

### Change the color scheme
Edit the CSS variables at the top of the `<style>` block:

```css
:root {
  --bg:      #0f0e0c;   /* Page background */
  --gold:    #c9a84c;   /* Primary accent  */
  --gold-lt: #e2c27a;   /* Light accent    */
  --text:    #f0ebe2;   /* Body text       */
}
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

Built with ❤️ using pure HTML, CSS & JavaScript.  
Feel free to fork, star ⭐, and customize!
