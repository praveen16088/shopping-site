🛒 Namaste Cart

Namaste Cart is an e-commerce web application that showcases products using the [DummyJSON API](https://dummyjson.com). Users can browse categorized products, view product details, and manage a shopping cart with data stored in the browser using `localStorage`.

📸 Preview

[Namaste Cart Homepage](https://assets.tatacliq.com/medias/sys_master/images/65236471611422.png)


📌 Features

- 🛍️ **Product Listing** – Browse products by categories like Beauty, Smartphones, Furniture, Groceries, and Laptops.
- 🔎 **Product Details Page** – See detailed product information dynamically by clicking the product.
- 🛒 **Cart System** – Add and remove items from cart, cart data saved in localStorage.
- ✅ **Responsive UI** – Built using Bootstrap for mobile-friendly experience.
- 🔗 **Routing with Query Params** – View products via URL like `product.html?pid=12`.
- 🌐 **API Integration** – Uses [DummyJSON](https://dummyjson.com) to fetch product data.



📂 Project Structure



Namaste-Cart/
│
├── index.html               # Home page
├── /pages
│   ├── product.html         # Single product detail page
│   └── cart.html            # Cart page
├── style.css                # Custom styling
├── script.js                # Logic for homepage
├── common.js                # Shared logic (cart, addToCart, etc.)
└── README.md                # This file


🛠️ Setup Instructions

1. Clone the repository
bash
git clone https://github.com/your-username/namaste-cart.git
cd namaste-cart


2. Open `index.html` in your browser

> You can simply double-click the `index.html` file or use a local development server like VS Code Live Server.



🚀 Technologies Used

* HTML5
* CSS3
* JavaScript (ES6+)
* [Bootstrap 5.3](https://getbootstrap.com/)
* [DummyJSON API](https://dummyjson.com)



## 📦 How Cart Works

* When a user clicks "Add To Cart", the product object is stored in `localStorage`.
* Cart count updates live in the navbar.
* Items are rendered dynamically on the Cart page.

---

## 💡 Future Improvements

* 🔐 User authentication
* 🧾 Order placement page
* 🖼️ Product filters and sorting
* 🛍️ Checkout and payment simulation

---

👨‍💻 Author

**Praveen Kumar**
[GitHub](https://github.com/praveen16088)
Feel free to fork, star, or contribute!

---

## 📃 License

This project is open-source and free to use under the [MIT License](LICENSE).



📸 Preview

[Homepage Screenshot](./assets/Screenshot 2025-08-02 153950.png)

```
