# 🏢 Virtual Shopping Mall Mobile App

> A modern, realistic, multi-floor 3D Virtual Shopping Mall mobile application built with zero dependencies (HTML5, CSS3 Glassmorphism, Vanilla JS). Simulates a multi-floor shopping mall experience complete with elevator lift animation, 5 distinct shopping floors, search & filter engine, shopping cart, multi-gateway checkout, live delivery order tracking, and printable tax invoices.

![Virtual Mall Banner](images/mall_banner_3d.jpg)

---

## 🌟 Key Features

- **📱 Mobile Shell & Viewport Mode Switcher**:
  - Simulated iPhone 15 Pro device frame view.
  - Interactive toggle button to switch seamlessly between **Mobile View** and **Full Desktop View**.

- **🛗 Interactive 3D Multi-Floor Layout & Glass Elevator**:
  - Real-time elevator lift animation moving between Ground Floor (GF) and 4th Floor (4F) with visual floor indicators and chime effects.
  - 3D perspective floor plan visualization with store hot-spots.

- **🛍️ 5 Department Floors & Comprehensive Product Catalog**:
  - **Ground Floor (GF)**: Cosmetics & Accessories (*Perfumes, Earrings, Necklaces, Bracelets, Watches, Handbags, Makeup, Skincare, Sunglasses*).
  - **First Floor (1F)**: Women's Wear (*Pure Silk Sarees, Kurtis, Dresses, Tops, Jeans, Ethnic Wear, Footwear, Handbags*).
  - **Second Floor (2F)**: Men's Wear (*T-Shirts, Shirts, Jeans, Formal Wear, Blazers, Jackets, Leather Shoes, Sportswear*).
  - **Third Floor (3F)**: Kids' Wear & Toys (*Baby clothing, Boys & Girls wear, Toys, Kids Footwear, Baby Care*).
  - **Fourth Floor (4F)**: Books & Lifestyle (*Story Books, Novels, Educational Books, Stationery, Home Décor*).

- **🔍 Search, Filter & Sorting Engine**:
  - Universal real-time product search bar across all 5 floors.
  - Category pill filter bar per floor.
  - Sorting options: Price (Low to High / High to Low), Highest Rated, Newest.

- **🛒 Wishlist & Cart System**:
  - One-tap Wishlist heart toggle with counter badges.
  - Sliding Cart drawer with real-time subtotal, 18% GST (9% CGST + 9% SGST), express shipping fee calculation, and promo coupon engine (`MALL20`, `WELCOME10`, `FREESHIP`).

- **💳 Secure Multi-Gateway Checkout**:
  - Saved Address selection and new address creation form.
  - Payment Gateways: **Credit/Debit Card**, **UPI** (with generated QR code & VPA), **Net Banking**, **Mall Cash Wallet**, and **Cash on Delivery (COD)**.

- **🚚 Live Order Tracking & Digital Invoice**:
  - Animated order status timeline (*Placed ➔ Confirmed ➔ Packed ➔ Out for Delivery ➔ Delivered*).
  - Courier executive contact details & vehicle number.
  - Simulated live route map with moving delivery van animation.
  - Printable & downloadable digital tax invoice (`window.print()`).

---

## 📁 Repository Structure

```text
virtual-shopping-mall/
├── index.html          # Main HTML structure & app shell
├── styles.css          # Luxury dark mode design system & animations
├── README.md           # Documentation
├── .gitignore          # Git ignore configuration
├── images/             # Product and 3D mall artwork
│   ├── mall_banner_3d.jpg
│   ├── perfume_luxury.jpg
│   ├── saree_silk.jpg
│   └── mens_blazer.jpg
└── js/                # Modular JavaScript application code
    ├── data.js         # 5-Floor product catalog & coupons
    ├── mall3d.js       # 3D floor layout & elevator controller
    ├── cart.js         # Cart, wishlist, & coupon engine
    ├── checkout.js     # Multi-step checkout & payment gateways
    ├── orders.js       # Order history & live tracking
    ├── invoice.js      # Digital tax invoice generator
    ├── auth.js         # User profile & Mall Wallet
    └── app.js          # App orchestrator & search router
```

---

## 🚀 How to Run Locally

1. Clone or download the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/virtual-shopping-mall.git
   cd virtual-shopping-mall
   ```

2. Start any local web server (e.g. using Python or Node):
   ```bash
   # Using Python 3
   python -m http.server 8080
   ```

3. Open your browser and navigate to:
   [http://localhost:8080](http://localhost:8080)

---

## 🛠️ Built With

- **HTML5** - Semantic web components & modal dialogues
- **CSS3** - Glassmorphism effects, flexbox/grid, CSS 3D transforms, custom animations
- **Vanilla JavaScript (ES6+)** - State management, local persistence, modular design

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
