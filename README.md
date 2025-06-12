Here’s a comprehensive **README.md** file summarizing the entire project setup so far — your e-commerce site for **Beads & Feels Kenya**.

---

## 📘 `README.md`

````markdown
# Beads & Feels Kenya

Welcome to **Beads & Feels Kenya**, an elegant, handcrafted accessories e-commerce website built with pure HTML, Tailwind CSS, and vanilla JavaScript — with a static frontend-only approach that simulates full cart and checkout functionality.

---

## 🌍 Overview

**Beads & Feels Kenya** sells vibrant African-inspired handmade accessories including:

- Bracelets
- Earrings
- Waistbeads
- Necklaces
- Anklets
- Beaded Keyholders

Each category has its own dedicated HTML page, with a user-friendly shopping experience and localStorage-based cart logic.

---

## 🎨 Color Palette

- **Primary:** `#f07218` (Orange)
- **Accent:** `#852527` (Burgundy)
- **Highlight:** `#e9a001` (Gold)

These colors are used throughout the interface for consistency and vibrant appeal.

---

## 📁 Folder Structure

```bash
beads-feels/
├── index.html                 # Homepage
├── cart.html                 # Cart & payment summary
├── custom-orders.html       # Custom order request form
├── bracelets.html
├── earrings.html
├── necklaces.html
├── waistbeads.html
├── anklets.html
├── beadedkeyholders.html
├── img/
│   ├── waistbead1.jpg
│   ├── anklet1.jpg
│   ├── keyholder1.jpg
│   └── ...other product images
├── css/
│   └── (optional custom styles if added)
├── js/
│   └── cart.js (optional - can keep JS inline or split here)
└── README.md
````

---

## 🛒 Features

* ✅ Clean navigation bar with links to categories, cart, and custom orders
* ✅ Each category page lists 3+ products with:

  * Image
  * Name
  * Price
  * “Add to Cart” functionality using localStorage
* ✅ Cart totals automatically calculated
* ✅ Simulated payment section (M-Pesa, Bank Transfer, etc.)
* ✅ Custom Order Form
* ✅ Mobile responsive using Tailwind CSS

---

## 💳 Payment Instructions

On the cart page:

* Users will be shown the **total cost**
* Payment options displayed:

  * M-Pesa Till Number
  * Bank Account Number
* User confirms payment by pasting their **transaction code**

⚠️ *This system does not auto-verify payments — it's a static simulation with manual confirmation.*

---

## 🧾 How to Add More Products

1. Go to the respective category HTML file.
2. Copy and paste an existing product block.
3. Update:

   * Product name
   * Price
   * Image source (`img/yourimage.jpg`)
4. Make sure the image is stored inside the `img/` folder.

---

## 🔧 Local Setup

1. Clone or download the project folder.
2. Open `index.html` in a browser.
3. To test full functionality:

   * Navigate between pages using the navbar
   * Add items to cart
   * Open `cart.html` to review purchases and simulate checkout

---

## 💡 Future Improvements

* Add testimonials and reviews section
* Export cart data as printable invoice
* Integrate with a backend (e.g. Firebase, PHP, or Node.js) for real-time order management
* Add product filtering or search by tags

---

## 🧵 Made in Nairobi with love 🧡

**Beads & Feels Kenya**
“Wear Your Story”

---

```

Would you like this in a downloadable `.zip` with the current website files, or do you want to proceed to building the `custom-orders.html` page or the cart/payment page (`cart.html`) next?
```
