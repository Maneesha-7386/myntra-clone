# 🛍️ Myntra Clone – Frontend E-Commerce Web App

A feature-rich **Myntra Clone** built with **React.js**, replicating the core shopping experience of India's leading fashion e-commerce platform. This is a **frontend-only** project demonstrating modern frontend development practices including component-based architecture, state management, routing, and responsive design.

## 🌐 Live Demo

🔗 **[View Live Project](https://m-y-n-t-r-a-c-l-o-n-e1e2e3s4h5a.netlify.app/)**

---

## ✨ Features

- 🏠 **Home Page** – Dynamic banners, carousels, and curated product sections
- 👕 **Category Pages** – Men, Women, Kids, Beauty, Home & Living, GenZ
- 📄 **Product Listing** – Advanced filtering and sorting with dynamic category routing
- 🔍 **Product Details** – Detailed product view with size selection and add-to-bag/wishlist
- 🛒 **Shopping Bag** – Add, remove, and manage items with real-time price summary
- ❤️ **Wishlist** – Save favorite products for later
- 💳 **Checkout Flow** – Multi-step checkout with address management and payment page
- 📦 **Order Management** – Order history and order confirmation page
- 👤 **User Profile** – Profile management with login/authentication
- 🎁 **Gift Cards & Coupons** – Gift card purchase and coupon management
- ⭐ **Myntra Insider** – Loyalty program page
- 📱 **Responsive Design** – Fully responsive across all devices

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **React 19** | UI library for building component-based interfaces |
| **Vite** | Fast build tool and development server |
| **Redux Toolkit** | Global state management (cart, wishlist, auth, orders, filters) |
| **React Router v7** | Client-side routing and navigation |
| **Tailwind CSS** | Utility-first CSS framework for styling |
| **Axios** | HTTP client for API requests |
| **Lucide React & React Icons** | Icon libraries |
| **React Slick** | Carousel/slider component |

---

## 📁 Project Structure

```
myntra-clone/
├── public/
├── src/
│   ├── api/             # API service layer
│   ├── assets/           # Images and static assets
│   ├── components/       # Reusable UI components
│   │   ├── Banner/       # Banner components
│   │   ├── Beauty/       # Beauty section components
│   │   ├── Cards/        # Product card variants
│   │   ├── Carousel/     # Image carousels
│   │   ├── Checkout/     # Checkout components
│   │   ├── Listing/      # Product listing components
│   │   ├── Navbar/       # Navigation bar
│   │   ├── Sections/     # Homepage sections
│   │   ├── Sidebar/      # Sidebar navigation
│   │   ├── Footer.jsx
│   │   └── ProductCard.jsx
│   ├── data/             # Static data files
│   ├── pages/            # Route-level page components
│   │   ├── Home.jsx
│   │   ├── Men.jsx, Women.jsx, Kids.jsx
│   │   ├── Beauty.jsx, HomeLiving.jsx, Genz.jsx
│   │   ├── ListingPage.jsx, ProductDetails.jsx
│   │   ├── Bag.jsx, Wishlist.jsx
│   │   ├── Payment.jsx, OrderConfirmed.jsx
│   │   ├── Profile.jsx, Login.jsx
│   │   ├── Orders.jsx, Addresses.jsx
│   │   ├── Coupons.jsx, GiftCards.jsx
│   │   └── MyntraInsider.jsx
│   ├── store/            # Redux store and slices
│   │   ├── store.js
│   │   ├── authSlice.js
│   │   ├── cartSlice.js
│   │   ├── wishlistSlice.js
│   │   ├── ordersSlice.js
│   │   ├── productsSlice.js
│   │   └── filterSlice.js
│   ├── utils/            # Utility functions
│   ├── App.jsx           # Main app with routes
│   ├── main.jsx          # Entry point
│   └── index.css         # Global styles
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
└── postcss.config.js
```

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v18 or above)
- **npm** (v9 or above)

### Installation

```bash
# Clone the repository
git clone https://github.com/Maneesha-7386/Myntra-Clone12.git

# Navigate to the project directory
cd Myntra-Clone12

# Install dependencies
npm install

# Start the development server
npm run dev
```

The app will be available at `http://localhost:5173`

---

## 📸 Key Pages

| Page | Description |
|---|---|
| `/` | Home page with banners, carousels, and product sections |
| `/men`, `/women`, `/kids` | Category-specific product listings |
| `/beauty`, `/home-living` | Lifestyle category pages |
| `/:categorySlug` | Dynamic product listing with filters |
| `/bag` | Shopping bag with price summary |
| `/wishlist` | Saved favorite items |
| `/payment` | Payment and checkout |
| `/order-confirmed` | Order confirmation |
| `/profile` | User profile management |
| `/orders` | Order history |

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is open source and available for learning purposes.

---

## 👩‍💻 Author

**Maneesha**

- GitHub: [@Maneesha-7386](https://github.com/Maneesha-7386)

---

⭐ **If you found this project helpful, please give it a star!**
